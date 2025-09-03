# ue-info
언리얼 엔진 관련 정보 모음

# 릭
공식 컨트롤릭 강의


# 블렌더 애드온
https://github.com/poly-hammer/BlenderTools

## 원격실행 활성화
프로젝트의 DefaultEngine.ini 마지막줄에 추가 
또는 프로젝트 세팅의 Enable Remote Execution 항목 활성
```
[/Script/PythonScriptPlugin.PythonScriptPluginSettings]
bRemoteExecution=True
```
## 레거시 FBX 활성
UE 5.5 이상 사용시 아래 내용을 프로젝트의 DefaultEngine.ini 마지막줄에 추가
```
[ConsoleVariables]
Interchange.FeatureFlags.Import.FBX=False
```
# 기즈모
## 기본 기즈모 아크볼 회전
* Editor Preferences > Enable Arcball Rotate 
## 새 기즈모 활성
* 플러그인 > New TRS Gizmos 활성후 재시작
* Editor Preferences > Enable New Gizmos
