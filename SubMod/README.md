## GMA Android Sample
글로벌 표준앱 Sample 입니다.

#### Android Studio
- Arctic Fox | 2020.3.1 Patch3

#### Android SDK
- Target SDK 31
- Compile SDK 31
- Min SDK 21

#### Gradle
- Gradle 7.0.2
- Android Gradle Plugin 7.0.3
- Gradle JDK 11.0.10 (Embedded)

#### Kotlin
- Kotlin 1.5
- Kotlin Gradle Plugin 1.5.31

#### Git Submodule
- 샘플앱은 gma 모듈 프로젝트를 submodule로 포함하고 있습니다.
- 아래 명령어를 통해 모듈 프로젝트를 업데이트 받습니다.

```
git submodule add https://mobgit.shinhan.com/scm/gma/core_android.git
git submodule init
git submodule update --remote
```

#### Commit Rule
```
------------------------------------------
# <type>:<title> / title 50 characters

# description / Body 72 characters

# Issue Tracker Number or URL
------------------------------------------

# Type can be
#   feat    : new feature
#   fix     : bug fix
#   refactor: refactoring production code
#   style   : formatting, missing semi colons, etc; no code change
#   docs    : changes to documentation
#   test    : adding or refactoring tests
#             no productin code change
#   chore   : updating grunt tasks etc
#             no production code change
#   etc
# ------------------
#   Use the imperative mood in the title line
#   제목줄은 명령어로 작성한다.
#   Do not end the title line with a period
#   제목줄은 마침표로 끝내지 않는다.
#   Separate title from body with a blank line
#   본문과 제목에는 빈줄을 넣어서 구분한다.
#   Use the description to explain what and why vs. how
#   본문에는 "어떻게" 보다는 "왜"와 "무엇을" 설명한다.
#   Can use multiple lines with "-" for bullet points in description
#   본문에 목록을 나타낼때는 "-"로 시작한다.
# ------------------
```