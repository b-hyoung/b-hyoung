### UI/UX에 관심이 많고
### 에러해결의 짜릿함을 즐기는
### 프론트엔드 개발자 박형석입니다.

---

  ### Skill
  - HTML/CSS
  - React / Redux
  - JavaScript
  - JQuery
  - TypeScript ( Study ..ing)
  - AWS (S3 배포)
  
  
      
  ### Project
   -  [PortFolio](http://reactportpolio.s3-website.ap-northeast-2.amazonaws.com) (포트폴리오 사이트)
   -  [Clover](https://github.com/djgnfj-svg/Clover) (소모임 커뮤니티 사이트)
   -  [ReSee](https://github.com/djgnfj-svg/Resee_project) (개인 노트 사이트)
   -  [Eriwa](https://github.com/djgnfj-svg/Eriwa) (게임 전적검색 사이트)

<a href="https://www.gitanimals.org/en_US?utm_medium=image&utm_source=b-hyoung&utm_content=farm">
<img
  src="https://render.gitanimals.org/farms/b-hyoung"
  width="1000"
  height="350"
/>
</a>


# .github/workflows/update-readme.yml
name: Update README with commit hours

on:
  schedule:
    - cron: "0 * * * *" # 매시간마다
  workflow_dispatch:

jobs:
  update-readme:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - name: Generate commit hours
        run: |
          git log --pretty=format:"%ad" --date=iso | \
          awk '{ split($2,t,":"); hour=t[1]; count[hour]++ } END { for (i in count) print i,count[i] }' | sort > commit_hours.txt
      - name: Add to README
        run: |
          echo "### 🕒 My Commit Hours" > commit_hours.md
          cat commit_hours.txt >> commit_hours.md
