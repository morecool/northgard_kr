# Northgard Hangeul Translation
## 노스가드 한글화 패치
 - 제작 : 삼류개발자 (coolseed@hotmail.com)
 - 버전 : v2.1.2.16332
 - 배포 : 디시인사이드 노스가드 마이너 갤러리 (https://gall.dcinside.com/mgallery/board/lists?id=gardnorth)
 - 소스 : https://github.com/morecool/northgard_kr

## 패치방법
### 정품 사용자

1. 게임의 리소스 파일을 한글화 작업할 디렉토리에 복사합니다.
  * C:\Program Files (x86)\Steam\steamapps\common\Northgard\res.pak 파일 복사

2. QuickBMS 툴을 이용하여 게임 리소스 파일의 압축을 풀어줍니다.

  * quickbms_4gb_files.exe 실행
  * quickbms 스크립트 파일 선택 (northgard.txt)
  * 리소스 압축파일 선택 (res.pak)
  * 압축 풀 디렉토리 선택 (아무 디렉토리나 새로 만들어서 그쪽으로 지정) (예)C:\north_kr)
  해당 리소스 파일이 압축이 풀립니다.
  
3. 한글화 적용
  * 한글화 패키지의 fonts 디렉토리내의 파일들을 [압축푼경로]\extra\font  디렉토리에 덮어씌움
  * 한글화 패키지의 lang 디렉토리내의 파일들을 [압축푼경로]\res\extra\lang 디렉토리에 덮어씌움
  
4. 리소스 파일 재구성
  * reimport2_4gb_files.bat 실행
  * quickbms 스크립트 파일 선택 (northgard.txt)
  * 리소스 압축파일 선택 (res.pak)
  * 변경된 파일 경로 선택 [압축푼경로] (예)C:\north_kr)
  변경된 파일이 리소스 압축파일에 적용됩니다.
  
5. 변경된 res.pak 파일을 노스가드 원래 파일로 덮어씌움
   C:\Program Files (x86)\Steam\steamapps\common\Northgard\res.pak

6. 완료
