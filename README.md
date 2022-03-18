# Javacript
Javascript Study

#### NVM
nvm ls
nvm install Major.Minor.Patch
nvm uninstall Major.Minor.Patch
nvm use Major.Minor.Patch
nvm --version
nvm --help

#### NPM

npm init -y

- npm install -D xxx : 개발용 의존성 패키지 설치. (개발할 때만 도움을 받는 용도)
ex) npm install parcel-bundler -D (npm install -D parcel-bundler)

- npm install : 일반 의존성 패키지 설치. (개발 이후 웹 브라우저에서도 도움을 받아야할 용도)
ex) npm install lodash


package.json

"dev" : "parcel index.html",
"build" : "parcel build index.html : 사용자가 웹브라우저에서 보기 위한 방식.
npm run build 실행시 dist 폴더 생성됨 -> '난독화' 되어 자동 작성됨.



#### 유의적 버전(Semantic Versioning, SemVer)

^Major.Minor.Patch
E.g :12.14.1

^ : Major 버전 안에서 가장 최신 버전으로 업데이트 가능.
npm info lodash : lodash 정보 확인.
npm install lodash@4.17.20
npm update lodash

Major : 기존 버전과 호환되지 않는 새로운 버전. 
Minor : 기존 버전과 호환되는 새로운 기능이 추가된 버전.
Patch : 기존 버전과 호환되는 버그 및 오타 등이 수정된 버전.


#### NPM 프로젝트의 버전 관리(.gitignore)
- version 관리가 필요하지 않는 폴더는 삭제.
e.g) .cache, dist, node_modules 

.gitignore 파일을 만들어 올리지 않을 항목을 저장.

- git init
- git status
- git add . : 버전 추적
- git status : 변경 사항 추적 확인.
- git commit -m 'Project'
- git log
- remote add origin https://github.com/yuchan509/Test.git
- git push origin master

#### ECMA Scriptm (ES)

