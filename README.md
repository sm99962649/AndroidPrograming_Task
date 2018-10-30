# **AndroidPrograming_Task**

> Git Instruction

> Markdown Grammer

---

## **Git Instruction**

- Add

| **Command** | **Description** |
| --- | --- |
| git add *파일* | stage area에 파일을 추가하여 commit 할 수 있도록 한다. |

- Commit

| **Command** | **Description** |
| --- | --- |
| git commit -m *”메시지”* | stage area에 있는 파일들을 commit 한다. |
| git commit -a -m *”메시지”* | 이미 추가된 파일이 수정 중인 상황에서 stage area에 올리지 않아도 stage area에 올리고 바로 commit 한다. |

- Remote

| **Command** | **Description** |
| --- | --- |
| git remote add *저장소 저장소주소* | 원격 저장소를 추가한다. |
| git remote -v | 원격 저장소 목록을 보여준다. |

- Clone

| **Command** | **Description** |
| --- | --- |
| git clone *주소 저장될 폴더* | git 원격 저장소에 있는 프로젝트를 내려받는다. |
| git clone –depth *숫자 주소* | 프로젝트가 많은 커밋들을 가지고 있을 경우 내려받는데 오래 걸리므로 depth 옵션을 사용하면 해당 숫자만큼의 최신 커밋들만 가지고 프로젝트를 내려받는다. |

- Push

| **Command** | **Description** |
| --- | --- |
| git push origin master | origin 원격 저장소에 master 브랜치에 추가된 스냅샷들을 올린다. |
| git push origin +master | origin 원격 저장소에 master 브랜치에 추가된 스냅샷들을 강제로 올린다. |

- Stash

| **Command** | **Description** |
| --- | --- |
| git stash | 변경된 내역들을 스택에 만들고 워킹디렉토리는 깨끗하게 비운다. |
| git stash list | 스택에 저장된 내역들을 확인할 수 있다. |
| git stash apply | 스택에 저장된 최신의 stash를 적용한다. |
| git stash apply *stash이름* | 스택에 저장된 stash중 이름이 같은 stash를 적용한다. |
| git stash apply –index | Stage 상태로 스택에 저장된 stash를 Stage 상태까지 복원한다. |

- Tag

| **Command** | **Description** |
| --- | --- |
| git tag | 만들어진 태그 목록을 보여준다. |
| git tag *태그* | 태그를 만든다. |
| git tag -l ‘v1.0′ | 1.0버전의 태그들만 검색하여 보여준다. |

- diff

| **Command** | **Description** |
| --- | --- |
| git diff | 파일 변경사항들을 보여준다. |
| git diff *파일* | 해당 파일의 변경사항을 보여준다. |

- branch

| **Command** | **Description** |
| --- | --- |
| git branch | 브랜치 목록을 보여준다. |
| git branch *브랜치* | 브랜치를 생성한다. |

- checkout

| **Command** | **Description** |
| --- | --- |
| git checkout *브랜치* | 해당 브랜치로 이동한다. |
| git checkout -b *브랜치* | 브랜치가 없으면 브랜치를 생성하고 이동한다. |

- merge

| **Command** | **Description** |
| --- | --- |
| git merge *브랜치* | 현재 브랜치에서 입력한 브랜치와 합친다. |

- reset

| **Command** | **Description** |
| --- | --- |
| git reset *커밋* *파일* | stage area에 있는 파일들을 모두 특정 커밋으로 되돌린다. |
| git reset --soft *커밋* | 수정사항을 유지하고 특정 커밋으로 되돌린다. |
| git reset --hard *커밋* | 수정사항을 무시하고 특정 커밋으로 되돌린다. |

---

## **Markdown Grammer**

- Headings

| **Command** | **Description** |
| --- | --- |
| #제목 | 텍스트 앞에 #기호를 추가한다. 1~6개에 따라 제목 크기가 결정된다. |

http://humit.tistory.com/194
