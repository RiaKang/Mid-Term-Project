# Mid-Term-Project
Repository for Open Source Software Learning

안녕하세요 단국대학교 소프트웨어학과 강승민입니다.

OpenSource Software 과목을 통해 자기소개 홈페이지 제작을 하게 되었습니다.

****************************************************************************************************************************************************
<<<<<<<<다운로드 및 이용 방법>>>>>>>>

제작한 페이지를 도메인과 연결하지 않았기 때문에, 페이지 확인을 위해서는 이 Repository에 있는 파일을 다운받으셔야 합니다.

index.html 파일, image파일 2개, video 파일 1개로 이루어져있습니다.

중앙 부근 초록색 <> Code 박스를 클릭한 뒤, Download Zip을 통해 압축파일을 다운로드하고 압축을 해제합니다.

index.html과 image, video 파일을 모두 같은 폴더 안에 저장한 뒤 Html 파일을 실행시키면 정상적으로 이미지와 비디오가 존재하는 페이지를 보실 수 있습니다.
****************************************************************************************************************************************************


자기소개 홈페이지 과제를 진행하며 VS Code와 Github를 연동시켜 제작하게 되었으며, 
과제를 통해 알게된 내용 중 연동을 위한 필수적인 내용만 짧게 서술하려 합니다.

VS Code를 통해 Terminal에
git remote add origin URL 명령어를 통해 VS Code와 Github를 연동시킬 수 있습니다.
URL의 위치에 연동시키고 싶은 Repository의 주소를 입력합니다.

git remote -v 명령어를 Terminal에 입력하면, 현재 연동 상태를 알 수 있으며,
정상적으로 연동되었을 시 해당 Repository 주소를 볼 수 있습니다.

git remote remove origin 명령어를 이용하여 연동을 해제할 수 있습니다.

VS Code와 Github를 연동 후 수정한 파일을 Github에 업로드하고 싶다면

git add .

git commit -m "something"

git push origin master

세 가지 명령어를 통해 업로드할 수 있습니다

git add . 는 변경된 사항을 전체적으로 저장하고

git commit 은 "something" 부분에 설명을 적어 commit한 내용을 서술합니다.

git push origin master 는 master 위치에 변경한 사항들을 push하여 적용합니다.
