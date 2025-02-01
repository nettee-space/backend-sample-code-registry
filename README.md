<h1 align="center">✨ Introduction.</h1>

이 레포지터리는 여러 서브 모듈을 모아 둔 수퍼 레포지터리(메타 레포지터리)입니다.  
프로젝트의 코드 스타일을 단계적으로 파악할 수 있도록, 다음 목록을 서브모듈로 포함합니다.

1. [**layerd**](https://github.com/nettee-space/backend-sample-layered-simple-crud) (`main` 브랜치)
2. [**hexagonal**](https://github.com/nettee-space/backend-sample-hexagonal-simple-crud) (`main` 브랜치)
3. **multi-module** (예정)
  
## Installation

`--recursive` 옵션으로 서브모듈의 내용까지 모두 클론받습니다.  
또한 만약 이 레포지터리에 작업하기 위해서 프로젝트를 다운로드 한다면 추가로 SSH 인증을 이용하십시오.

```bash
git clone --recursive https://github.com/nettee-space/backend-sample-code-registry.git
```

<details>
  <summary><i>SSH 인증 사용 시</i></summary>

  ```bash
  git clone --recursive git@github.com:nettee-space/backend-sample-code-registry.git
  ```
  
</details>

<br />

<h1 align="center">✍️ Summary of Each Project</h1>

<table border="3" width="1080" align="center">
  <tr>
    <td>
      초기 단계 파악을 위한 프로젝트일수록 <strong>복잡한 설명을 줄이고</strong>, 간단한 코드로 구조를 전달하는 것을 목표로 합니다. <br />
      마지막 단계 프로젝트에서 비교적 복잡한 관리가 적용될 수 있습니다.  
    </td>
  </tr>
</table>

### 1. Layered Architecture

- 익숙한 아키텍처 내에서 코드 스타일 적응에 집중합니다.  
- 기본 CRUD 적응이면서도, 의외로 현업자에게도 낯설 수 있는 몇 가지 작업 방식에 초점을 둡니다.  
- **_이 단계에서는 복잡한 설계나 코드를 생략하고, 오로지 구조 이해를 돕는 데 집중합니다._**  

### 2. Hexagonal Architecture

- **헥사고날 아키텍처에서** 각 계층의 역할에 대한 이해와 오해, 그중 핵심적인 부분을 공유하며 서로의 생각을 진단합니다.  
- 깃과 깃허브 협업으로 활발한 이슈 생성과 이를 위한 템플릿, 직관적인 label 목록을 관리합니다.  
- **테스트 코드 및 코드리뷰** 문화를 도입합니다.  

### 3. Multi-Module Project (+ Hexagonal Architecture)

> 본격적인 팀의 코드 스타일이 담기는 프로젝트입니다.

- 모듈의 세분화로 **헥사고날 아키텍처에** 남은 설계적 미스를 진단합니다.  
- **유틸리티 모듈, 코어 모듈, 공통 모듈을** 생성하고 본격적으로 관리합니다. (일부 모듈을 라이브러리로 배포할 수도 있습니다.)  
