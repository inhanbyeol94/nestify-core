<div align="center">
  <img src="https://github.com/user-attachments/assets/f120f124-5bbc-498b-b1fa-2bfdbdf568eb" width="400">
</div>

# Nestify Core
서브모듈은 모든 프로젝트에서 공통적으로 사용하는 기능과 유틸리티를 포함하고 있으며, 특정 프로젝트에 국한되지 않는 범용적인 기능들을 담고 있습니다.

<br/>

## Setup
```bash
git submodule add -b core https://github.com/inhanbyeol94/nestify-submodule.git src/_utils/submodules/core
```

<br/>

## Read-Only Scope

**이 서브모듈은 읽기 전용(read-only)** 으로 설정되어 있으며, 다음과 같은 이유로 직접 수정이 불가합니다.

- **범용성**: `Core` 서브모듈은 모든 프로젝트에 걸쳐 사용될 수 있는 기능을 제공하므로, 특정 프로젝트에 종속되지 않습니다.
- **일관성 유지**: 모든 프로젝트에서 동일한 코드 베이스를 유지하기 위해 서브모듈은 수정되지 않고 공유됩니다.
- **확장성 고려**: 프로젝트별 기능 추가가 필요할 경우, 이 서브모듈 외부에서 별도로 확장하여 사용할 것을 권장합니다.
