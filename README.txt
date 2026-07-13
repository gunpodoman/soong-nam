GitHub Pages 배포용 2D 캐릭터 리깅 사이트

이 패키지는 외부 파일이나 서버 프로그램 없이 index.html 하나만으로 작동합니다.

아이패드에서 배포하는 방법

1. 파일 앱에서 ZIP 파일을 눌러 압축을 풉니다.
2. GitHub에서 새 Public 저장소를 만듭니다.
3. Add file, Upload files를 누릅니다.
4. 압축을 푼 폴더 안의 index.html과 .nojekyll을 업로드합니다.
5. Commit changes를 누릅니다.
6. 저장소의 Settings, Pages로 이동합니다.
7. Source에서 Deploy from a branch를 선택합니다.
8. Branch는 main, 폴더는 /(root)로 지정하고 Save를 누릅니다.
9. 배포가 완료되면 표시되는 주소로 접속합니다.

주의

ZIP 파일 자체를 저장소에 올리면 사이트가 실행되지 않습니다. 파일 앱에서 먼저 압축을 풀고, 압축 내부의 파일을 저장소 최상위 경로에 올려야 합니다.
