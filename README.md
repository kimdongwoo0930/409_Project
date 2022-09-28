# 개발환경 구축 (윈도우 기준)

### 프론트(React-native)
1.
    chocolately 설치하기
    
        @"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"
    설치 한 후 설치 확인
        
        choco –version
---

2.
    nodejs 설치하기 (명령프롬프트를 관리자 권행으로 실행)
        
        choco install -y nodejs.install
    
    설치 확인
    
        node -–version
    
        npm --version
---
3.
   python 설치하기
   
         choco install -y python2
         
         python --version
---

4.
   React native CLI 설치하기
   
         npm install -g react-native-cli
      
         npx react-native --version
---

5. 
   JDK 설치하기
   
         choco install -y jdk8
         
         java -version
---

6. 안드로이드 스튜디오 설치하기

   * 다운로드 -> 설치 완료 -> SDK Manager
   * show package details 체크하기
         
         Android SDK Platform 29
         intel x86 Atom System Image
         Google APIs Intel x86 Atom System Image
         Google APIs Intel x86 Atom_64 System Image
   * 위에 목록들을 찾아서 선택한 후 OK버튼을 눌러 설치해줍니다. 


   
7. 안드로이드 스튜디오 환경변수 설정해주기
* 자세한 설명은 참고하세요
* https://voidfunction-e.tistory.com/entry/%EC%9C%88%EB%8F%84%EC%9A%B0%EC%97%90-react-native-%EA%B0%9C%EB%B0%9C-%ED%99%98%EA%B2%BD-%EA%B5%AC%EC%B6%95%ED%95%98%EA%B8%B0

8. 직접 프로젝트 생성하지말고 자기 브랜치에 있는 Frontend 파일을 클론해서 작업하기

