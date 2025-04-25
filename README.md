
## 🌸 Cherry Blossom 컴파일러 설치 방법

Cherry Blossom 언어를 사용하려면 컴파일러가 필요합니다. 아래 순서를 따라 설치해주세요.

### 1. 최신 컴파일러 다운로드

- [Cherry Blossom Releases](https://github.com/CherryBlossomFoundation/CherryBlossom/releases) 페이지에서 가장 최신 버전의 **컴파일러(.exe)** 파일을 다운로드하세요.

### 2. 원하는 위치에 Cherry.exe 이동

- 예: `C:\CherryBlossomCompiler`

### 3. 환경 변수 설정

#### ➤ `%cb_path%` 설정

- `cb_path`는 Cherry Blossom 언어의 루트 경로입니다.
- 예:  
  ```sh
  setx cb_path "C:\CherryBlossomCompiler"
  ```

#### ➤ `%PATH%`에 추가

- 컴파일러 실행 파일이 포함된 폴더를 `%PATH%`에 추가해야 합니다.  
- 예:  
  ```sh
  setx PATH "%PATH%;C:\CherryBlossomCompiler"
  ```

> ℹ️ `setx`는 영구 적용 명령입니다. 명령 프롬프트를 껐다 켠 후 적용됩니다.

---

### ✅ 확인

```sh
cherry
```

이 명령어로 Cherry Blossom 컴파일러가 정상 작동하는지 확인하세요.

## 🎨 확장 적용 방법 (Cherry Blossom Theme)

이 확장은 **전용 커스텀 테마**를 함께 사용할 때 가장 잘 어울립니다.

### ✅ 테마 적용 방법

#### 방법 1: GUI 메뉴 이용
1. 왼쪽 아래 **톱니바퀴 아이콘(⚙)** 클릭  
2. `테마` → `색 테마` 선택  
3. **Cherry Blossom Theme** 선택

#### 방법 2: 단축키 이용
1. `Ctrl + K` 누른 후  
2. 이어서 `Ctrl + T` 입력  
3. 테마 목록에서 **Cherry Blossom Theme** 선택

> 테마를 적용한 후 `.cb` 파일을 열어보세요. 🌸  
> JetBrains 스타일의 매크로 강조와 함께 아름다운 문법 하이라이팅을 경험할 수 있습니다.
