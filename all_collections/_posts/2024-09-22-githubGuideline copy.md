---
layout: post
title: 깃허브 가이드라인
date: 2024-09-22
categories: [Github]
---

이 글은 가장 기초적인 협업 툴이라고 할 수 있는 깃허브 사용 방법을 설명하기 위한 글입니다.

# 초심자를 위한 GitHub Desktop 사용법

GitHub Desktop은 초보 개발자가 명령어 없이도 Git과 GitHub를 쉽게 사용할 수 있는 GUI 도구입니다. 이 가이드는 GitHub Desktop을 처음 사용하는 개발자들을 위해 단계별로 설명합니다.

---

## 1. GitHub Desktop 설치하기

### 1.1 GitHub Desktop 다운로드

- [GitHub Desktop 공식 페이지](https://desktop.github.com/)에서 운영 체제에 맞는 GitHub Desktop을 다운로드하고 설치합니다.

### 1.2 GitHub 계정으로 로그인

- GitHub Desktop을 설치하고 실행한 후 GitHub 계정으로 로그인합니다.
- 아직 계정이 없다면 [GitHub](https://github.com/)에서 계정을 생성하세요.
- 위 사이트에 접속한후 우측 상단의 `Sign Up` 버튼으로 계정을 생성할 수 있습니다.
  ![Group-1-5.png](https://i.postimg.cc/NGzjPtsD/Group-1-5.png)

---

## 2. GitHub Desktop 사용하기

![Group-2-1.png](https://i.postimg.cc/28bm3XpS/Group-2-1.png)

### 2.1 새 저장소 만들기

1. **새로운 저장소 생성**
   ![Group-3-1.png](https://i.postimg.cc/CxpQsc27/Group-3-1.png)

   - 상단 `File` 메뉴에서 **New Repository**를 선택하여 새 저장소를 만듭니다.
   - 저장소 이름을 입력하고, 저장할 위치를 지정합니다.

2. **저장소를 GitHub에 업로드**
   - 저장소를 만든 후 상단 중앙의 **Publish repository** 버튼을 클릭하여 로컬 저장소를 GitHub에 업로드합니다.
   - 이후 웹으로 깃허브 사이트에 들어가 생성된 repository를 확인할 수 있습니다.

---

### 2.2 기존 저장소 클론(clone)하기

1. **클론할 저장소 선택**
   ![Group-3.png](https://i.postimg.cc/X7GR8GYj/Group-3.png)

   - GitHub의 다른 프로젝트를 로컬로 가져오려면 **Clone a repository from the Internet** 옵션을 사용합니다.
   - 저장소 URL을 입력하거나 GitHub 계정에서 직접 선택할 수 있습니다.

2. **클론 후 파일 변경**
   - 클론한 후, 파일을 수정하거나 추가하면 GitHub Desktop이 자동으로 변경 사항을 추적합니다.

---

### 2.3 변경 사항 커밋하기

1. **변경 사항 확인**

   - 프로젝트 폴더에서 파일을 수정하면 GitHub Desktop이 자동으로 변경 사항을 추적합니다.
   - 좌측의 **Changes** 탭에서 수정된 파일을 확인할 수 있습니다.

2. **커밋하기**
   - 변경 사항을 확인한 후, **Summary**에 커밋 메시지를 입력합니다.
   - **Commit to main** 버튼을 눌러 변경 사항을 커밋합니다.

---

### 2.4 GitHub로 푸시(Push)하기

![Group-3-2.png](https://i.postimg.cc/ZYGWjNxj/Group-3-2.png)

1. **푸시 작업**
   - 커밋한 변경 사항을 GitHub로 업로드하려면 **Push origin** 버튼을 클릭합니다.
   - 로컬에서 작업한 내용을 원격 저장소에 적용할 수 있습니다.

---

### 2.5 브랜치(Branch) 관리하기

1. **새로운 브랜치 만들기**
   ![Group-4.png](https://i.postimg.cc/BZMhKq5q/Group-4.png)

   - 기능 추가나 개선 작업을 할 때는 새로운 브랜치를 생성하여 작업합니다.
   - **Current Branch** 버튼을 클릭한 후 **New Branch**를 선택해 브랜치를 생성합니다.

2. **브랜치 전환하기**
   ![Group-4-1.png](https://i.postimg.cc/s2jQ7R4r/Group-4-1.png)
   ![Group-4-2.png](https://i.postimg.cc/HxPS8gRZ/Group-4-2.png)
   - 작업 중인 브랜치를 변경하려면 **Current Branch**를 클릭하고 원하는 브랜치로 전환할 수 있습니다.
   - 첫 브랜치 변경이라면 **Publish branch**를 눌러 브랜치 생성을 완료합니다.
   - 이제 브랜치 내에서 하는 작업은 Main에 영향을 주지 않습니다. 많은 시도와 실패를 하셔도 무방합니다.

---

### 2.6 풀 리퀘스트(Pull Request) 보내기

1. **Pull Request 생성**
   ![Group-5.png](https://i.postimg.cc/CMcZDKvL/Group-5.png)
   ![Group-4-3.png](https://i.postimg.cc/NMHc0pPH/Group-4-3.png)
   ![Group-4-4.png](https://i.postimg.cc/Gpb8Gs1t/Group-4-4.png)
   - 작업이 완료되면, 커밋을 진행하고 브랜치를 메인 브랜치에 병합하고자 **Push Origin**,풀 리퀘스트를 보냅니다.
     ![Group-4-5.png](https://i.postimg.cc/9FzvXxRF/Group-4-5.png)
   - GitHub 웹사이트에서 `Pull Request` 탭으로 이동하여 **Create Pull Request** 버튼을 클릭합니다.
   - 위 과정으로 **Pull Request**는 완료되었습니다.
     ![Group-4-6.png](https://i.postimg.cc/wTc0pLFT/Group-4-6.png)
   - 이후 프로젝트의 PM은 GitHub에서 리포지토리 -> Pull Request에 들어가 해당 요청을 병합하여 메인 프로젝트와 동기화 할 수 있습니다.

---
