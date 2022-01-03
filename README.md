# 제목: readme 제작 명령어
## 작은 제목
### 소제목(더 작은 제목)
readme 제작 명령어
markdown language : 사용설명서 만들기 

<img src="./mainconcept/pani.png">
->html에서 이미지 넣을 때 명령어. 암기
src (소스)
./ 나랑 같은 경로에 있는 이라는 뜻 

```
->사용되는 폰트, 색상 콘셉트, 
1.로고는 이미지로 저장 2.플랜아이에 대한 설명: 타임라인은 최소 3초마다 왼쪽에서 오른쪽으로 선색이 나타나며  “문장을” 시간 지나면 타임라인 따라 자동으로 상하로 스크롤되며 “message”가 오른쪽에서 왼쪽으로 애니메이션 되며 들어옴
```
-> 기호 이름: 백틱 (1번 왼쪽의 작은 따옴표)
``` -> 사진에 대한 설명 , 영역 구분 
```로 시작 ```로 끝맺음  (맥도 같은 위치)
```


# 기호이름
(숫자 계속 1로 해도 자기가 알아서 바꿔줌)
1. ` 백틱 : 1번 왼쪽의 작은
따옴표
1. ~ 틸드
1. ^ 캐럿
1. & 앰퍼센트
1. | 파이프
1. \= 백슬래시 
1. / 슬래시

# 파일명, 폴더명 사용시 주의점
html 소스로 사용할 이미지
1. 파일명은 반드시 영문으로 시작
1. 의미 있는 파일명 <BR>
 (EX.1월에 보이는 배너1)
1. 파일명, 폴더명은 반드시 띄어쓰기 사용하지 말 것

 - 서버: 리눅스 환경 (띄어쓰기 인식 X) (아무대서나 볼 수 있게 서버에 올려야 함 )
4. 대소문자 구분해서 사용할 것 (리눅스는 대문자와 소문자 다르게 인식. 대문자로 쓰면 소문자로 치면 못찾음)

# 이름 만드는 규칙 : 문화, 학문 
1. 카멜표기법 : 단어와 단어 사이 첫 글자는 대문자
2. 스네이크 표기법: 단어와 단어 사이를 -로 표시 <BR> 
(뱀 처럼 길다 -----)
3. 파스칼 표기법: 첫글자를 대문자로 사용
4.

# 이미지 파일 확장자
## 웹에 업로드 할 수 있는 확장자
- jpg: 투명표현이 불가능
- png: 투명표현이 가능
- gif: 투명표현, 애니메이션 가능
- webm: 새로운 이미지 포맷 

 **1번 왼쪽** :진하게 표현
 
 # 이모지 : 윈도우 기능 
 윈도우 로고키 + 마침표 .  (맥에서는...? ->커멘드 + 컨트롤 + 스페이스 바 )


# git: 리눅스 명령 환경
git-scm.com 다운로드
폴더이동> 마우스 오른쪽 버튼 > git-bash here
컨트롤 누르고 마우스 키우면 커져 

# git upload
```
echo "# afterClass" >> README.md
//문서를 만든다. 
git init
// git 폴더 초기화
git add README.md
// git 업로드 할 파일 선택
(git add .) 
-> 다 올리는 것
(git status ->틀렸는지 아닌지 보는 것)
git commit -m "first commit"
// 버전 관리에 들어갈 설명 쓰기
commit :  수정될 때 마다 
git branch -M main
// master -> main 으로 이름이 바뀜 
git config --global user.email "suan0603@naver.com"
git config --global user.email "usuanyou"
//오픈소스니까 다른 사람이 내꺼보고 질문할 수 있도록
git remote add origin https://github.com/usuanyou/afterClass.git
//업로드할 폴더와 로컬폴더를 연결
-내 컴퓨터 안 폴더랑 git 폴더 연결
// staging: 업로드할 준비
git push -u origin main
// 진짜 업로드 함 -진짜 올리는 거
```

# 두번째 접속 후 업로드
```
git remote add origin https://github.com/usuanyou/afterClass.git
git branch -M main
git push -u origin main
```

git init
git clone 사이트주소 
// 그 폴더 있는거 내 컴에 받는 것
아니면 그 사이트에서 다운로드 zip
#afterclass
# afterClass
# afterClass
# afterClass
# afterClass
# afterClass
# study
# study
