# ToggleSwitch

ToggleSwitch는 특정 문자열을 대응되는 문자열로 토글하는 기능을 제공합니다.

### 대응 문자열 목록
- `true` ↔ `false`
- `public` ↔ `private`
- `x` ↔ `y`
- `width` ↔ `height`
- `AddEventListener` ↔ `RemoveEventListener`
- `OnEnable` ↔ `OnDisable`
- `InitEvent` ↔ `RemoveEvent`
- `+=` ↔ `-=`

## Visual Studio에서 단축키로 등록하는 방법

### 1. Visual Commander 설치 및 커맨드 생성
1. Visual Studio를 실행합니다.
2. `Extensions > Manage Extensions`를 클릭합니다.
3. 'Visual Commander'를 검색하고 설치합니다.
4. Visual Studio를 재시작합니다.
5. `Extensions > VCmd > Import`를 클릭합니다.
6. `ToggleSwitch.vcmd` 파일을 선택해 커맨드를 불러옵니다.
7. `OK`를 클릭합니다.

### 2. 커맨드를 단축키로 등록
1. `Tools > Options`를 클릭합니다.
2. `Environment > Keyboard`를 선택합니다.
3. `Show commands containing` 입력란에 `VCmd.Command01`를 입력합니다.
4. 검색 결과에서 해당 커맨드를 선택합니다.
5. `Press shortcut keys` 입력란에 사용할 단축키를 입력합니다.
6. `Assign` 버튼을 클릭하여 단축키를 할당합니다.
7. `OK`를 클릭하여 설정을 저장합니다.
