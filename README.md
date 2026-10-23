# GitHub 프로필 배지와 개인 위키 예시

[![매직밀키트 커뮤니티](https://img.shields.io/badge/매직밀키트-커뮤니티_강의-1B1B1B)](https://www.skool.com/stack-small-wins-2688)
![마지막 업데이트](https://img.shields.io/github/last-commit/mmk-community/github-profile-examples?label=마지막%20업데이트&color=1B1B1B)
![방문](https://komarev.com/ghpvc/?username=mmk-community-github-profile-examples&label=방문&color=1B1B1B&style=flat)

「GitHub 프로필 꾸미기와 개인 위키」 강의에서 쓰는 예시 모음입니다. 배지와 카드가 실제로 어떻게 보이는지 이 화면에서 바로 보고, 아래 코드를 복사해 내 README 에 붙여 넣으면 됩니다.

> 강의는 매직밀키트 커뮤니티 스쿨에서 봅니다. 이 저장소는 강의에서 가리키는 예시 저장소입니다.

## 차례

1. [기술 배지](#1-기술-배지)
2. [아이콘 한 줄(skillicons)](#2-아이콘-한-줄skillicons)
3. [연락 배지](#3-연락-배지)
4. [방문자 배지](#4-방문자-배지)
5. [모양 고르기: style 5종](#5-모양-고르기-style-5종)
6. [통계 카드](#6-통계-카드)
7. [밝은 화면과 어두운 화면](#7-밝은-화면과-어두운-화면)
8. [위키 배지](#8-위키-배지)
9. [예시 파일](#9-예시-파일)

---

## 1. 기술 배지

![Claude Code](https://img.shields.io/badge/Claude_Code-1B1B1B?logo=claude&logoColor=white)
![Make](https://img.shields.io/badge/Make-6D00CC?logo=make&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-1B1B1B?logo=supabase&logoColor=3ECF8E)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=white)

```markdown
![Claude Code](https://img.shields.io/badge/Claude_Code-1B1B1B?logo=claude&logoColor=white)
![Make](https://img.shields.io/badge/Make-6D00CC?logo=make&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-1B1B1B?logo=supabase&logoColor=3ECF8E)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=white)
```

주소 모양은 `badge/<왼쪽 글자>-<오른쪽 글자>-<색>?logo=<로고 이름>` 입니다. 글자 안의 띄어쓰기는 `_`, 하이픈은 `--` 로 씁니다. 로고 이름은 [simpleicons.org](https://simpleicons.org) 에서 찾습니다.

## 2. 아이콘 한 줄(skillicons)

![skills](https://skillicons.dev/icons?i=ts,go,supabase,vercel,github&theme=dark)

```markdown
![skills](https://skillicons.dev/icons?i=ts,go,supabase,vercel,github&theme=dark)
```

## 3. 연락 배지

배지를 링크로 감싸면 누를 때 그 주소로 갑니다. 아래 주소는 모두 예시(example.com)이니 내 주소로 바꿉니다.

[![YouTube](https://img.shields.io/badge/YouTube-내_채널-FF0000?logo=youtube&logoColor=white)](https://example.com)
[![Blog](https://img.shields.io/badge/Blog-내_블로그-1B1B1B)](https://example.com)
[![Website](https://img.shields.io/badge/Web-example.com-EEA80C?logoColor=1B1B1B)](https://example.com)

```markdown
[![YouTube](https://img.shields.io/badge/YouTube-내_채널-FF0000?logo=youtube&logoColor=white)](https://example.com)
[![Blog](https://img.shields.io/badge/Blog-내_블로그-1B1B1B)](https://example.com)
[![Website](https://img.shields.io/badge/Web-example.com-EEA80C?logoColor=1B1B1B)](https://example.com)
```

이메일 주소와 전화번호는 배지에도 README 에도 넣지 않습니다. 공개 저장소의 글은 수집 프로그램이 긁어 갑니다.

## 4. 방문자 배지

![방문](https://komarev.com/ghpvc/?username=mmk-community-github-profile-examples&label=Profile%20views&color=1B1B1B&style=flat)

```markdown
![Profile views](https://komarev.com/ghpvc/?username=내아이디&label=Profile%20views&color=1B1B1B&style=flat)
```

이 저장소의 배지는 저장소 이름으로 세고 있습니다. 내 프로필에서는 `username=` 뒤를 내 아이디로 바꿉니다. 내가 새로 고친 것도 한 번으로 세니 분위기용으로 봅니다.

## 5. 모양 고르기: style 5종

| style | 모습 | 주소 끝 |
|---|---|---|
| flat(기본) | ![flat](https://img.shields.io/badge/Make-6D00CC?logo=make&logoColor=white&style=flat) | `&style=flat` |
| flat-square | ![flat-square](https://img.shields.io/badge/Make-6D00CC?logo=make&logoColor=white&style=flat-square) | `&style=flat-square` |
| for-the-badge | ![for-the-badge](https://img.shields.io/badge/Make-6D00CC?logo=make&logoColor=white&style=for-the-badge) | `&style=for-the-badge` |
| plastic | ![plastic](https://img.shields.io/badge/Make-6D00CC?logo=make&logoColor=white&style=plastic) | `&style=plastic` |
| 로고 없음 | ![로고 없음](https://img.shields.io/badge/Make-6D00CC?style=flat) | `logo=` 부분을 지움 |

한 README 안에서는 한 가지 모양으로 맞춥니다. `for-the-badge` 는 눈에 잘 띄지만 5개가 넘으면 화면이 무거워 보입니다.

## 6. 통계 카드

예시 계정은 GitHub 의 공식 마스코트 계정 `octocat` 입니다. `username=` 뒤를 내 아이디로 바꿉니다.

![GitHub stats](https://github-readme-stats.vercel.app/api?username=octocat&show_icons=true&hide_border=true&theme=dark)
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=octocat&layout=compact&hide_border=true&theme=dark)

![Streak](https://streak-stats.demolab.com?user=octocat&theme=dark&hide_border=true)

```markdown
![GitHub stats](https://github-readme-stats.vercel.app/api?username=octocat&show_icons=true&hide_border=true&theme=dark)
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=octocat&layout=compact&hide_border=true&theme=dark)
![Streak](https://streak-stats.demolab.com?user=octocat&theme=dark&hide_border=true)
```

매직밀키트 색(차콜과 오렌지)으로 맞춘 카드입니다.

![브랜드 색 카드](https://github-readme-stats.vercel.app/api?username=octocat&show_icons=true&bg_color=1B1B1B&title_color=EEA80C&text_color=FFFFFF&icon_color=EEA80C&hide_border=true)

```text
&bg_color=1B1B1B&title_color=EEA80C&text_color=FFFFFF&icon_color=EEA80C&hide_border=true
```

> 통계 카드는 남이 운영하는 공용 서버에서 그립니다. 사용량이 몰리면 카드 대신 오류 그림이 뜨는 날이 있습니다. 그런 날은 잠시 기다립니다.

## 7. 밝은 화면과 어두운 화면

`<picture>` 를 쓰면 보는 사람의 화면 설정에 맞춰 카드가 바뀝니다. GitHub 오른쪽 위 내 사진 > Settings > Appearance 에서 Light 와 Dark 를 번갈아 바꿔 아래 카드를 보세요.

<picture>
  <source media="(prefers-color-scheme: dark)"
          srcset="https://github-readme-stats.vercel.app/api?username=octocat&show_icons=true&hide_border=true&theme=dark">
  <img alt="GitHub stats" height="165"
       src="https://github-readme-stats.vercel.app/api?username=octocat&show_icons=true&hide_border=true&theme=default">
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)"
          srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=octocat&layout=compact&hide_border=true&theme=dark">
  <img alt="Top languages" height="165"
       src="https://github-readme-stats.vercel.app/api/top-langs/?username=octocat&layout=compact&hide_border=true&theme=default">
</picture>

```html
<picture>
  <source media="(prefers-color-scheme: dark)"
          srcset="https://github-readme-stats.vercel.app/api?username=octocat&show_icons=true&hide_border=true&theme=dark">
  <img alt="GitHub stats" height="165"
       src="https://github-readme-stats.vercel.app/api?username=octocat&show_icons=true&hide_border=true&theme=default">
</picture>
```

- `source` 줄은 어두운 화면일 때 쓸 그림입니다.
- `img` 줄은 그 밖의 경우, 즉 밝은 화면일 때 쓸 그림입니다.

## 8. 위키 배지

개인 위키 저장소를 만들었다면 프로필에서 바로 넘어가게 합니다. 아래는 이 저장소로 띄운 모습입니다.

[![내 생활 위키](https://img.shields.io/badge/내_생활_위키-1B1B1B?logo=github&logoColor=white)](examples/life-wiki)
![마지막 업데이트](https://img.shields.io/github/last-commit/mmk-community/github-profile-examples?label=마지막%20업데이트&color=1B1B1B)

```markdown
[![내 생활 위키](https://img.shields.io/badge/내_생활_위키-1B1B1B?logo=github&logoColor=white)](https://github.com/내아이디/my-wiki)
![마지막 업데이트](https://img.shields.io/github/last-commit/내아이디/my-wiki?label=마지막%20업데이트&color=1B1B1B)
```

둘째 배지는 마지막으로 글을 고친 때를 저절로 보여 줍니다. 공개 저장소에서만 나옵니다.

## 9. 예시 파일

| 파일 | 무엇 |
|---|---|
| [examples/profile-readme/developer.md](examples/profile-readme/developer.md) | 개발자형 프로필 README: 배지, 통계 카드, 대표 프로젝트 |
| [examples/profile-readme/first-timer.md](examples/profile-readme/first-timer.md) | 코딩을 처음 하는 분용 프로필 README: 소개, 위키 배지, 요즘 쓴 글 |
| [examples/profile-readme/minimal.md](examples/profile-readme/minimal.md) | 가장 짧은 프로필 README: 세 줄 |
| [examples/life-wiki/](examples/life-wiki) | 생활 위키 예시: 요리, 여행, 읽은 책, 업무 메모 폴더와 목차 |

프로필 README 를 쓰려면 내 아이디와 똑같은 이름의 공개 저장소를 만들고, 위 파일 하나를 그 저장소의 `README.md` 로 붙여 넣습니다.
