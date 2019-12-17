# Github
Github에 새로 생성한 organization에 대한 설명과 프로젝트 운영 방식에 대해서 공유하고자 합니다.

Github는 2007년 10월부터 시작되어 현재(2019년 8월 기준)  100,000,000개의 Repository가 운영중이며 40,000,000명 이상의 사람이 활동 중인 형상 관리 시스템입니다.

Github에 업로드 된 Open Source가 많아서 쉽게 코드를 확인하고, 발전에 기여할 수도 있습니다.
이 경우에는 Github ID를 제출함으로써 자기소개서를 대체할 수도 있을 것 같네요.


## Organization
After School 이라는 이름의 Organization을 생성 했습니다.

보통 회사 이름이나, 오픈소스재단의 이름을 사용합니다.

팀원을 초대할 수 있으며, 내부에 repository를 여러 개 만들 수 있습니다.


## Project
pjt로 시작하는 repository를 생성했습니다. 각자 자유롭게 repository를 사용하면 됩니다.

Pull Request를 사용하셔도 되고, master branch에 직접 push 하셔도 상관 없습니다.

Commit Message도 자유롭게 사용하세요.

코드 리뷰가 필요한 경우에는 Pull Request를 사용하시는 것을 추천드립니다.


## Five Speech
### 강연 업데이트
Markdown에 익숙한 사람은 README.md 파일에 본인의 Speech 내용을 직접 업데이트 하세요.

워드, 파워포인트 등 파일을 사용하고자 한다면 동일한 path에 파일을 올리시고 README.md 파일을 아래와 같이 업데이트 해주세요. (예: 파일 이름이 charlie.pptx 인 경우)

```
[강연 파일 다운로드](./charlie.pptx)
```

외부 링크를 연결하고자 하면 아래와 같이 입력하세요.

```
[강연 보러 가기](https://charlie.kim/first_birthday)
```

### A week later
기존에 작성한 README.md 파일과 외부 파일은 해당 날짜의 directory를 생성해서 넣으시고, 새로운 README.md 파일을 만들어 주세요.

```
mkdir 191218
mv README.md charlie.pptx 191218/
vim README.md
```
