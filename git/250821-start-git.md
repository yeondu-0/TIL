# Start git

## Index

- shell, vim command
- what is git?
- Pre-commit
- git branch

### Shell, Vim Command

1. shell command

```shell
$ cd dev
$ mv main.py bin
```

2. vim command

vim은 지구상의 가장 완벽한 텍스트 에디터 입니다.

```text
mode:
normal, insert, visual, comman-line
```

### What is git?

- git: 분산형 버전관리 시스템
- Blob / Tree / Commit
- Working Directory > Staging Area > Local Repository > Remote Repository
- git add > git commit > git push
- Conventional Commit: prefix+설명
- .gitignore

### Pre-commit
commit 전 확인해야 할 사항 자동 수정

### git Branch
분기점을 생성하여 독립적으로 코드를 변경할 수 있도록 도와주는 모델

```shell
$ git branch fizz
$ git branch
$ git switch main
$ git merge fizz
```
