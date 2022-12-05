# fab_macro
-----------
## 1. 사용법
-----------
### 1.1 settings.json 설정
------------------
```
{
  "fab_version": "1.4.1",
  "device_version": "16.1",
  "member_num": 1,
  "path": "C:/Test/image",
  "limit": 1000,
  "offset":0
}
```
exe를 실행하기 전 json파일을 열어서 다운 받기 원하는 정보로 설정 부탁드립니다.(json파일은 메모장으로 열어 수정 가능합니다.)   
   
* fab_version: 앱스토어에 올라와 있는 팹 버전정보   
<https://apps.apple.com/kr/app/fab/id1534841196>   
앱스토어에 올라와 있는 버전 정보와 맞지 않을 경우, 팹에서 API호출을 막고 있으므로 되도록이면 버전을 맞춰주세요.   

* member_num: 멤버 번호
  * 희진: 1
  * 현진: 2
  * ~~하슬: 3(동작안됨)~~
  * 여진: 4
  * 비비: 5
  * 김립: 6
  * 진솔: 7
  * 최리: 8
  * 이브: 9
  * 츄: 10
  * 고원: 11
  * 올리비아혜: 12   
 *주의사항: 안드로이드로 업로드 한 사진의 경우 다운이 안됩니다. 현재 하슬이 사진과 김립 등 몇몇 멤버들의 일부 사진은 다운이 불가능합니다.(영상일 경우 썸네일만 저장됨)

* path: 이미지 저장 폴더 경로
저장할 폴더를 지정해주세요. 폴더가 존재하지 않을 경우 다운로드가 진행이 되지 않습니다. 예시에 적혀있는 형식대로 폴더 경로를 지정해주세요.   
예시: C:/Test/image

* limt: 받아올 메세지 수   
특별한 경우가 아니면 수정하지 말아주세요.

* offset: 시작 메세지 번호   
특별한 경우가 아니면 수정하지 말아주세요.

### 1.2 exe 실행
--------------
settings.json설정이 완료되었으면 저장 후 exe를 실행하세요. 다운로드가 완료되면 실행창이 자동으로 종료됩니다.   
오류가 발생할 경우 error.txt파일이 생성되므로 해당 txt파일을 확인바랍니다.


## 2. 문의
---------------
기타 문의 사항이나 
다운이 안되는 자료가 있다면 어떤 멤버의 언제 올라온 사진인지 아래 링크에 남겨주시기 바랍니다.   
<https://forms.gle/3wxqiHnR3DRihcVU7>
