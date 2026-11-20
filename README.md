<p align="center">
  <img src="icon.png" width="112" alt="RenLocalizer 로고">
</p>

<h1 align="center">RenLocalizer</h1>

**한국어** | [English](README.en.md)

<p align="center">
  <b>Ren'Py 비주얼 노벨을 원하는 언어로 플레이하세요.</b><br>
  게임을 끌어다 놓고, 언어를 고른 뒤 번역을 시작하세요.<br>
  무료 오픈 소스 도구로, 135개 언어를 지원하며 번역 후에도 게임을 실행할 수 있습니다.
</p>

<p align="center">
  <a href="https://github.com/Lord0fTurk/RenLocalizer/releases/latest/download/RenLocalizer-Windows-x64.zip"><img alt="Windows용 다운로드" src="https://img.shields.io/badge/Windows-Download-06B6D4?style=for-the-badge&logo=windows&logoColor=white"></a>
  <a href="https://github.com/Lord0fTurk/RenLocalizer/releases/latest/download/RenLocalizer-Linux-x64.AppImage"><img alt="Linux용 다운로드" src="https://img.shields.io/badge/Linux-Download-06B6D4?style=for-the-badge&logo=linux&logoColor=white"></a>
  <a href="https://github.com/Lord0fTurk/RenLocalizer/releases/latest/download/RenLocalizer-macOS-arm64.dmg"><img alt="macOS용 다운로드 (Apple Silicon)" src="https://img.shields.io/badge/macOS%20(Apple%20Silicon)-Download-06B6D4?style=for-the-badge&logo=apple&logoColor=white"></a>
</p>

<p align="center">
  <a href="https://github.com/Lord0fTurk/RenLocalizer/releases"><img alt="최신 릴리스" src="https://img.shields.io/github/v/release/Lord0fTurk/RenLocalizer?style=flat-square&label=latest&color=111827"></a>
  <a href="https://github.com/Lord0fTurk/RenLocalizer/releases"><img alt="다운로드 횟수" src="https://img.shields.io/github/downloads/Lord0fTurk/RenLocalizer/total?style=flat-square&color=111827"></a>
  <img alt="Ren'Py 7 및 8" src="https://img.shields.io/badge/Ren'Py-7%20%26%208-111827?style=flat-square">
</p>

<p align="center">
  <a href="#how-it-works">사용 방법</a> ·
  <a href="#which-engine-should-i-use">번역 엔진</a> ·
  <a href="#why-your-game-keeps-working">게임 보호 방식</a> ·
  <a href="#questions">자주 묻는 질문</a> ·
  <a href="https://github.com/Lord0fTurk/RenLocalizer/wiki">위키</a> ·
  <a href="CHANGELOG.md">변경 사항</a>
</p>

<p align="center">
  <img src=".github/assets/demo.gif" width="860" alt="RenLocalizer에서 게임을 불러와 튀르키예어로 번역하고 편집기에서 검수하는 모습">
</p>

---

<a name="how-it-works"></a>

## 사용 방법

별도 설정이나 프로그래밍 없이 사용할 수 있습니다. 다운로드하고 압축을 푼 뒤 실행하세요.

<table>
  <tr>
    <td width="36%">
      <a name="1-drop-in-your-game"></a>
      <h3>1. 게임 불러오기</h3>
      게임 폴더나 <code>.exe</code> 파일을 창에 끌어다 놓거나 <b>Folder</b> / <b>EXE File</b>을 사용하세요. RenLocalizer가 게임 이름과 버전, Ren'Py 버전을 표시합니다.
    </td>
    <td><img src=".github/assets/step-1-game.png" width="520" alt="게임을 불러온 번역 화면. 게임 이름과 버전, 번역할 언어와 원본 언어, 엔진 및 실행 패널이 보입니다."></td>
  </tr>
  <tr>
    <td>
      <a name="2-pick-a-language"></a>
      <h3>2. 언어 선택하기</h3>
      135개 언어 중에서 검색할 수 있습니다. 기본 엔진인 Google 번역은 계정 없이 사용할 수 있습니다.
    </td>
    <td><img src=".github/assets/step-2-language.png" width="520" alt="검색할 수 있는 번역 대상 언어 목록에서 튀르키예어가 선택된 모습"></td>
  </tr>
  <tr>
    <td>
      <a name="3-translate-and-play"></a>
      <h3>3. 번역하고 플레이하기</h3>
      <b>Translate</b>를 누릅니다. 번역이 끝나면 <b>Launch Game</b>을 눌러 선택한 언어로 게임을 실행합니다.
    </td>
    <td><img src=".github/assets/step-3-play.png" width="520" alt="번역한 줄 수와 Launch Game, Review in Editor 버튼이 보이는 번역 결과 화면"></td>
  </tr>
</table>

> [!TIP]
> 게임이 업데이트되면 번역을 다시 실행하세요. 이미 번역한 줄은 재사용하고 새 줄만 번역을 위해 전송합니다.

---

<a name="which-engine-should-i-use"></a>

## 어떤 번역 엔진을 써야 하나요?

| 원하는 방식 | 추천 엔진 | 준비할 것 |
| :--- | :--- | :--- |
| **무료로 바로 번역** | Google 번역 또는 Bing | 계정과 API 키 없이 쓸 수 있습니다. |
| **높은 번역 품질** | DeepSeek, Gemini 또는 OpenAI | 해당 서비스의 API 키가 필요합니다. DeepSeek는 비용이 낮고 Gemini에는 무료 등급이 있습니다. |
| **오프라인에서 데이터 보호** | 로컬 LLM | `.gguf` 모델 파일, Ollama 또는 LM Studio가 필요합니다. 데이터는 컴퓨터 밖으로 전송되지 않습니다. |

AI 엔진은 대사를 장면 단위로 읽으며 화자와 상대를 함께 파악해 말투, 성별, 인물 관계를 일관되게 반영합니다.

<details>
<summary><b>전체 엔진 비교</b></summary>
<br>

| 엔진 | 준비할 것 | 비용 | 특징 |
| :--- | :--- | :--- | :--- |
| Google 번역 | 없음 | 무료 | 기본 엔진입니다. 한도에 걸리지 않도록 여러 엔드포인트를 번갈아 사용합니다. |
| Bing / Microsoft Edge | 없음 | 무료 | Google과 별도의 사용 한도가 적용되며, 실패하면 Google로 전환합니다. |
| DeepSeek | API 키 | 저렴 | 비용 대비 번역 품질이 좋습니다. |
| Google Gemini | API 키 | 무료 등급 / 유료 | 긴 컨텍스트를 지원합니다. |
| OpenRouter | API 키 | 모델마다 다름 | 키 하나로 수백 가지 모델(`vendor/model` 형식)을 이용할 수 있습니다. 별도 설정이 필요 없습니다. |
| OpenAI | API 키 | 유료 | 기본 URL을 지정하면 다른 OpenAI 호환 서비스도 사용할 수 있습니다. |
| 로컬 LLM, 내장 실행기 | `.gguf` 파일 | 무료 | RenLocalizer가 llama.cpp를 내려받아 실행합니다. 추가 설치가 필요 없습니다. |
| 로컬 LLM, Ollama / LM Studio | 실행 중인 해당 앱 | 무료 | 이미 불러온 모델을 사용합니다. Hy-MT 같은 번역 모델의 프로필이 포함되어 있습니다. |
| LibreTranslate | 자체 서버 | 무료 | 직접 호스팅합니다. |

</details>

---

<a name="why-your-game-keeps-working"></a>

## 번역 후에도 게임이 실행되는 이유

Ren'Py 스크립트를 일반 텍스트처럼 처리하는 번역 도구에서는 태그 하나만 손상돼도 게임이 중단될 수 있습니다. RenLocalizer는 게임이 사용하는 코드와 표기를 보존하도록 설계되었습니다.

<table>
  <tr>
    <td width="50%" valign="top">
      <b>코드 보존</b><br>
      <code>{b}</code>, <code>{color=…}</code> 같은 텍스트 태그와 <code>[player_name]</code> 같은 변수를 번역 전에 잠그고 번역 후 확인합니다. 손상된 줄은 다시 번역하고, 다시 실패하면 게임이 중단되지 않도록 원문을 유지합니다.
    </td>
    <td width="50%" valign="top">
      <b>표준 Ren'Py 번역 파일</b><br>
      <code>game/tl/</code>에 표준 번역 파일을 쓰고 Ren'Py 자체 번역 도구와 같은 줄 ID를 사용합니다. 문자열 중복 오류를 방지합니다.
    </td>
  </tr>
  <tr>
    <td valign="top">
      <b>패키징·컴파일된 게임</b><br>
      소스가 없어도 컴파일된 <code>.rpyc</code> 스크립트를 읽고, 일부 사용자 지정 보호가 적용된 파일을 포함해 <code>.rpa</code> 아카이브를 풉니다.
    </td>
    <td valign="top">
      <b>문자와 쓰기 방향 지원</b><br>
      글자가 빈 상자로 표시되면 해당 언어를 지원하는 글꼴로 바꿀 수 있습니다. 아랍어, 페르시아어, 히브리어는 오른쪽에서 왼쪽으로 표시합니다.
    </td>
  </tr>
  <tr>
    <td valign="top">
      <b>이름과 용어 일관성</b><br>
      기본적으로 등장인물 이름을 유지합니다. 용어집에 등록한 용어는 모든 줄에서 일관되게 사용합니다.
    </td>
    <td valign="top">
      <b>번역 결과 직접 검수</b><br>
      내장 편집기에서 각 줄의 번역과 원문을 함께 볼 수 있습니다. 검색, 필터, 수정, 번역 재제안이 가능하며 나중에 다시 번역해도 편집 내용이 유지됩니다.
    </td>
  </tr>
</table>

<p align="center">
  <img src=".github/assets/editor.png" width="860" alt="원문과 번역문을 나란히 보여 주는 번역 편집기">
</p>

---

<a name="questions"></a>

## 자주 묻는 질문

<details>
<summary><b>게임을 시작하면 여전히 영어로 표시됩니다.</b></summary>
<br>

**Settings › General & Output › Start the game in the translated language**는 기본적으로 켜져 있습니다. 게임을 시작할 때 언어를 전환하는 작은 파일을 추가합니다. 이 설정을 껐거나 게임이 자체 언어를 강제로 사용한다면 **Toolbox › Language Activation**에서 언어를 선택하세요. 자체 언어 메뉴가 있는 게임에서는 Preferences에도 해당 언어가 표시됩니다.
</details>

<details>
<summary><b>일부 줄이 여전히 영어로 표시됩니다.</b></summary>
<br>

인물 이름, 효과음, 짧은 감탄사는 여러 언어에서 같은 형태로 쓰이는 경우가 많아 그대로 둡니다. 결과 요약에서 번역한 줄, 원문을 유지한 줄, 게임 보호를 위해 보류한 줄의 수를 확인할 수 있습니다. 편집기에서 원하는 줄을 직접 번역하세요. 화자 이름까지 번역하려면 **Settings › General & Output › Translate Character & Speaker Names**를 켜세요.
</details>

<details>
<summary><b>게임 파일이나 저장 데이터가 변경되나요?</b></summary>
<br>

저장 데이터는 건드리지 않습니다. RenLocalizer는 `game/tl/<language>/`에 번역을 저장하고 `game/`에 `zzz_`로 시작하는 작은 파일을 몇 개 추가합니다. 게임 스크립트가 `.rpa` 아카이브에 들어 있으면 압축을 풀고 디스크 공간을 절약하기 위해 아카이브를 삭제합니다.

> [!IMPORTANT]
> 처음 번역하기 전에 게임 폴더의 사본을 보관하세요. 특히 `.rpa` 아카이브를 사용하는 게임은 반드시 백업하세요.

번역을 제거하려면 `game/tl/<language>/`와 RenLocalizer가 추가한 `zzz_` 파일을 삭제하세요.
</details>

<details>
<summary><b>Windows 경고가 뜨거나 백신이 앱을 감지합니다.</b></summary>
<br>

앱에 코드 서명이 없어 Windows SmartScreen 경고가 표시될 수 있습니다. **More info › Run anyway**를 누르세요(튀르키예어 Windows에서는 **Yine de çalıştır**). 일부 백신은 PyInstaller로 패키징한 앱을 잘못 감지합니다. 모든 릴리스는 이 저장소의 소스로 **GitHub Actions**에서 공개 빌드됩니다. 확인하고 싶다면 오픈 소스 코드를 직접 살펴보거나 AI 도구로 검토한 뒤 [소스에서 실행](#for-power-users)할 수 있습니다.
</details>

<details>
<summary><b>macOS에서 앱이 손상되었거나 열 수 없다고 표시됩니다.</b></summary>
<br>

macOS용 다운로드에는 **macOS 13 이상이 설치된 Apple Silicon Mac(M1 이상)**이 필요합니다. Intel Mac에서는 [소스에서 실행](#for-power-users)하세요. 칩 종류는 Apple 메뉴 › 이 Mac에 관하여에서 확인할 수 있습니다.

macOS는 공증을 받지 않은 앱을 차단합니다. RenLocalizer를 응용 프로그램 폴더로 옮기고 다음 방법 중 하나를 사용하세요.

- **macOS 15 Sequoia**에서는 앱을 한 번 연 뒤 **시스템 설정 › 개인정보 보호 및 보안**에서 아래로 스크롤해 **그래도 열기(Open Anyway)**를 누르세요. Sequoia에서는 Control 키를 누른 채 클릭한 뒤 열기를 선택하는 방법이 작동하지 않습니다.
- **모든 버전**에서 터미널로 다음 명령을 한 번 실행한 뒤 평소처럼 앱을 열 수 있습니다.

```bash
xattr -cr /Applications/RenLocalizer.app
```

그래도 열리지 않으면 macOS 버전, 칩 종류, 오류 메시지 원문을 포함해 [이슈를 등록](https://github.com/Lord0fTurk/RenLocalizer/issues)하세요.
</details>

<details>
<summary><b>어떤 게임을 지원하나요?</b></summary>
<br>

Windows, Linux, macOS에서 Ren'Py 7 또는 8로 만든 게임을 지원합니다. macOS `.app` 게임, 컴파일된 `.rpyc` 파일만 제공하는 게임, `.rpa` 아카이브에 들어 있는 게임도 포함됩니다.
</details>

자세한 도움말은 [위키](https://github.com/Lord0fTurk/RenLocalizer/wiki)에서 확인하세요. 버그를 발견했다면 [이슈를 등록](https://github.com/Lord0fTurk/RenLocalizer/issues)하세요.

---

<a name="for-power-users"></a>

## 고급 사용법

<details>
<summary><b>명령줄</b></summary>
<br>

릴리스에는 앱과 함께 `RenLocalizerCLI`가 포함되어 있습니다. 소스에서 실행할 때는 `python run_cli.py`를 사용합니다. 앱과 같은 설정을 읽으며, 명령줄 옵션이 있으면 해당 값을 우선 적용합니다.

```bash
# Google 번역으로 튀르키예어로 번역 (기본값)
python run_cli.py translate "C:\Games\MyVisualNovel\game.exe"

# DeepSeek로 러시아어로 번역
python run_cli.py translate "C:\Games\MyVisualNovel\game.exe" -e deepseek -t ru --api-key YOUR_KEY

# 로컬 모델로 독일어로 번역하고 숨겨진 문자열까지 검사
python run_cli.py translate "C:\Games\MyVisualNovel\game.exe" -e local_llm -t de --deep-scan

# 이미 번역한 언어로 게임이 시작되도록 설정
python run_cli.py activate-language "C:\Games\MyVisualNovel" --lang turkish

# 단계별 대화형 메뉴
python run_cli.py --interactive
```

전체 옵션은 `python run_cli.py translate --help`에서 확인하세요.
</details>

<details>
<summary><b>소스에서 실행하기</b></summary>
<br>

Python 3.11 이상이 필요합니다.

```bash
git clone https://github.com/Lord0fTurk/RenLocalizer.git
cd RenLocalizer
python -m venv .venv
```

Windows에서는 `.venv\Scripts\activate`, Linux와 macOS에서는 `source .venv/bin/activate`로 가상 환경을 활성화한 뒤 아래 명령을 실행하세요.

```bash
pip install -r requirements.txt
python run.py
```
</details>

<details>
<summary><b>보호 방식 자세히 보기</b></summary>
<br>

- **자리표시자**는 각 줄을 전송하기 전에 Ren'Py 문법을 엔진이 변경하지 않는 표기로 바꿉니다. Google과 Bing은 유니코드 괄호 토큰을 사용하고 AI 엔진은 `<ph id="N">` 태그를 사용합니다.
- **복원**은 완전히 일치하는 토큰을 복구하는 단계부터 엔진이 변경하거나 옮긴 토큰을 고치는 단계까지 여러 단계로 진행됩니다. 어긋난 텍스트 태그 순서는 안전하게 고칠 수 있을 때 되돌립니다.
- **무결성 검사**에서 누락된 자리표시자, 노출된 토큰, 일치하지 않는 `%` 지정자, Ren'Py에서 허용하지 않는 태그가 발견되면 해당 줄을 다시 번역하고 그래도 실패하면 원문을 유지합니다.
- **AI 일괄 처리 형식**은 장면(화자 정보 포함), JSON, XML을 지원합니다. 규모가 작거나 번역 전용인 모델에는 줄마다 별도로 요청할 수 있습니다.
- **출력 방식**은 기본 Ren'Py `translate` 블록 또는 작은 런타임 훅이 읽는 `strings.json` 파일입니다.

</details>

---

<a name="support-the-project"></a>

## 프로젝트 후원

RenLocalizer는 여가 시간에 개발하는 무료 도구입니다. 도움이 되었다면 다음 방법으로 프로젝트에 힘을 보탤 수 있습니다.

- 다른 사람도 찾을 수 있도록 저장소에 별을 눌러 주세요.
- [Patreon에서 개발자 후원하기](https://www.patreon.com/cw/LordOfTurk)
- 버그와 아이디어는 [Issues](https://github.com/Lord0fTurk/RenLocalizer/issues)에 남겨 주세요. 변경 사항을 기여하려면 [CONTRIBUTING.md](CONTRIBUTING.md)를 참고하세요.

---

<a name="license-and-credits"></a>

## 라이선스와 사용한 프로젝트

RenLocalizer는 [GNU General Public License v3.0](LICENSE)으로 배포합니다.

다음 오픈 소스 프로젝트를 사용합니다.

| 프로젝트 | 라이선스 | 용도 |
| :--- | :---: | :--- |
| [llama.cpp](https://github.com/ggml-org/llama.cpp) | MIT | 내장 GGUF 실행기. 사용자가 요청하면 RenLocalizer가 공식 `llama-server` 빌드를 내려받아 SHA256으로 검증하고 관리합니다. 릴리스에는 포함되지 않습니다. |
| [PyQt6 / Qt](https://www.qt.io) | GPL-3.0 / LGPL-3.0 | 데스크톱 인터페이스(QML) |
| [Lucide](https://lucide.dev) | ISC | 인터페이스 아이콘. Lucide 아이콘 글꼴 일부가 라이선스(`LUCIDE_LICENSE.txt`)와 함께 `src/gui/qml/fonts/`에 포함됩니다. |
| [unrpa](https://github.com/Lattyware/unrpa) | GPL-3.0 | `.rpa` 아카이브 추출 |
| [rpycdec](https://pypi.org/project/rpycdec/) | MIT | `.rpyc` 디컴파일 보조 |
| [rich](https://github.com/Textualize/rich) | MIT | 명령줄 인터페이스 |

번역 엔진은 공개 엔드포인트나 공식 SDK로 연결합니다(Google 번역, Edge 엔드포인트를 통한 Microsoft Translator, LibreTranslate, OpenAI, Google Gemini, DeepSeek).
