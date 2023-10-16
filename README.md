# Hello_git

학교에서 **오픈소스 SW 개론**을 공부하면서 

유닉스에 쬑끔 배우고 깃 활용 방법 배우고 깃 플로우, 깃헙 플로우에 대해 어떻게 하는지에 대해 배웠다.

근데 치매 이슈로 안쓰면 분명 까먹을꺼 오조오억퍼센트로 아니까 여기에 기록하려고 한다.

여기에 기록하면서 README파일 작성하는것도 연습되고 좋은 방법이라고 생각한다.

치매 방지용이여서 사진은 안쓸꺼니까 자세한걸 원하는 사람들은 추후에 **개발 블로그**에도 정리해서 올릴테니까 

**개발 블로그** 이용해주길 바란다.








---
# git 설치

git 사용하려면 리눅스 환경에서 사용해야되는데 

윈도우면 **[gitbash](https://git-scm.com/ "wsl이나 우분투, SVM 설정등 마음 조리지 말자")** 설치하는게 가장 좋다.

---
# git 

git은 **리누스 토발즈**가 만들었다 -> 깃험에서 git 클론 후 리버스 커밋 로그 확인

git은 버전관리할때 좋다 혹은 일을 진행하다가 잘못하고 되돌아가야 할때 좋다.

버전관리는 꼭 git으로만 해야되는건 아니다

하지만 **버전관리**나 이러한 파일관리를 저학년부터 깃을 통해 활용한다면 좋은 **포트폴리오**가 될 수 있다.


## git 시작하기

```
git version

git config --global user.name \"\<name\>\"

git config \-\-config \-\-global user.email \"\<e-mail\>\" 

git config \-\-list -> git config 내용 확인
```

**깃헙**과 **계정**을 맞췄다면

`git init + 폴더명`

 로컬 저장소에 **세팅**해주자

작업트리, 스테이지 영역, 저장소 글 쓰기

**log 관련 명령어**

```
git log

git log --oneline

git log --oneline --all

git log --oneline --all --graph

```



`git diff`
 : 현재 woking directory의 마지막 commit과 차이점을 비교

`git diff <commit#1> <commit#2>`
 : 두 커밋의 차이점을 비교


## git 버전 관리

명령어 단위로 글 쓰기



## .gitignore 작성

## branch

고민해보고 git 버전관리 명령어랑 같이 쓸지 고민하기

근데 rebase랑 merge 생각하면 따로 분류해야될거같음
head랑 master 등 로컬 위주로 먼저 작성하고 나중에 원격 파트 갈때 origin등 가리키는거 설명 조지기 (아 깃플로우 깃헙플로우도 나중에 적기)

stash랑 switch 




## git cycle

`git status` - 깃의 상태를 확인 할 수 있다.

<img width="1102" alt="스크린샷 2023-10-15 오후 9 26 51" src="https://github.com/cod0216/Hello_git/assets/83526046/c7bf64f6-43c0-4c83-9ef4-c4860a94baad">


**Untracked** : git에서 파일을 추적하지 않는 상태 -> add시 staged 영역으로 간다

**Modified** : git에서 파일을 추적 중이며, 수정된 내용이 있는 상태

**Staged** : git에서 commit에 적용될 파일의 상태 -> 이후 unmodified로 돌아가게 된다.(**Untracked상태 아님\!**)

**unmodified** : git에서 파일을 추적 중이며, 수정된 내용이 없는 상태

**Remote** : 원격저장소 (Gitgub)

## git 복귀






---

# vim 

vi 에디터는 노션에 정리해놨는데 여기에도 쓸지는 고민중이다.

그래도 향상된 친구 vim이 서운해 할 수 도 있으니 자리라도 만들어 주자

---







