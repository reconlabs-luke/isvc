# isvc


# Submodule
## Clone

```bash
git clone git@github.com:reconlabs-luke/plicar.git --recurse-submodules
```
- 서브모듈까지 한번에 clone

## Clone for specific branch
```bash
BRANCH_NAME=develop
git config -f .gitmodules submodule.submodule.branch ${BRANCH_NAME}
git submodule update --remote --recursive
```
- clone 후 특정 브랜치로 이용하려면 위 명령어 수행
- default branch : master/main
