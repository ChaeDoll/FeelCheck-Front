## GitHub 사용법

- git pull origin 브랜치명 (해당 브랜치에 깃허브에 올라간 파일을 가져오기)
- git pull (계속 같은공간에 업로드하거나 받거나 할땐 origin 브랜치명 생략가능)
- git add . (깃허브에 올릴 파일 선택)
- git commit -m '메세지' (메세지와 함께 깃허브 올릴 준비)
- git push origin 브랜치명 (파일을 해당 브랜치에 업로드)
- git branch 브랜치명 (새롭게 브랜치를 생성)
- git chekcout 브랜치명 (해당 브랜치로 이동)

## npm

- 라이브러리가 없다고 뜨면 npm i (npm install)을 하면 됨.

## 애로사항

### 채윤 랩실 주의사항
- node_modules/@react-native-community/cli-server-api/build/statusPageMiddleware.js 에서 new URL(process.cwd())로 변경
- npm cache verify
- npm start