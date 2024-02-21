# 프로젝트 요약

**Project name:** 모션트랙킹 마우스 & 음성인식 키보드

**Project goal:** 이 프로젝트의 목표는 사용자의 `편의성`과 `접근성`을 향상시키는 것입니다. 모션과 음성을 활용함으로써 기존의 마우스와 키보드 조작 방식에 비해 더 자연스럽고 효율적인 컴퓨터 조작 경험을 제공하는 것이 목적입니다.

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)<img src="https://img.shields.io/badge/Visual Studio Code-007ACC?style=flat-square&logo=Visual Studio Code&logoColor=white"/>![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)

## 팀구성

|이름|메인임무|
|---|---|
|김승환|음성처리 Speech to Text 구현|
|김용철|영상처리, 모션 인식을 통한 마우스 제어|
|임선웅|올어라운드 스페셜리스트|

## Objectives:

- **사용자 경험 향상**: 프로젝트의 주요 목표 중 하나는 사용자의 컴퓨터 조작을 보다 자연스럽고 편리하게 만드는 것 입니다. 
- **액세스 가능성 향상**: 음성인식 기술을 통해 장애인이나 신체적 제약이 있는 사용자들도 키보드와 마우스를 사용하지 않고도 컴퓨터를 조작할 수 있는 가능성을 제시합니다. 
- **효율성 향상**:  키보드를 타이핑하는 것보다 음성 명령을 사용하여 빠르고 정확하게 텍스트를 입력할 수 있으며, 마우스를 움직이는 대신 손의 제스처를 사용하여 컴퓨터를 조작할 수 있습니다.
- **기술 혁신**: 이 프로젝트는 새로운 인터페이스 기술을 개발하고 적용함으로써 기존의 키보드와 마우스 조작 방식을 넘어선다는 기술적 도전을 제공합니다.

## Constraints:

- 프로젝트를 완료하는 데 할당된 시간이 제한되어 있습니다. 
- [insert]
- [insert]
- [insert]
- [insert]
- [insert]

## Assumptions:

- 음성인식 기술을 사용하는 부분에서 인터넷 속도에 제한을 받는 경우가 있습니다.

<br>

# 프로젝트 범위 및 계획

## In Scope:

- Mediapipe를 통한 모션 마킹 구현
- 모션을 통한 마우스 제어 구현
- 음성 인식을 통한 Speech to text 구현

## Out of Scope:

- 복잡한 모션을 통한 제어 구현
- 라즈베리파이에 구현
- C++구현

## Gantt Chart

```mermaid
gantt
    dateFormat  MM-DD-YYYY
    title       모션인식 마우스& 음성인식 키보드 프로젝트 Gantt Chart
	
	section 음성인식 Speech to Text 코드 구현
		자료 조사 및 코드 해석 :done, 2024-02-18, 1d
                코드 작성 및 STT구현 완료  :crit, 2024-02-19, 1d
		해당 코드 영상처리 코드랑 합치기 :2024-02-23, 1d
	
	section 손동작 인식 마우스 제어
		자료조사 및 코드 해석	: 2024-02-20, 1d
                영상에 모션 마킹  :crit, 2024-02-21, 1d
```

## Kanban

|BACKLOG  |TO-DO    |IN-PROGRESS        |COMPLETED       |
|---------|---------|-------------------|----------------|
|Speech to text 코딩  |         |                   |`completed`       |
|영상 마킹         |         |`in-progress`        |                |
|모션 인식         |`to-do`    |                   |                |
|코드 병합         |`to-do`    |                   |                |
|실행 파일 생성         |`to-do`    |                   |                |

<br>

# 회의록 

### 1차 프로젝트 계획 회의 | 2024-02-20 | 참석자: 김승환, 김용철

| 안건        | 내용                                       | 결정사항                             |
|------------|--------------------------------------------|--------------------------------------|
| 프로젝트 일정 조정 | - 금일 계획 및 일정을 확인하고 이행할 필요가 있음 | - 프로젝트 방향성 고정 |
| 역할 분담   | - 각 팀원들의 역할을 재확인, 임선웅 팀원의 역할에 대한 논의 필요 <br> - 중요한 임무에 대한 책임자를 지정해야 함. | - 음성인식: 김승환 <br> - 영상처리: 김용철  <br> - 미정: 임선웅 |
| 기타 사항   | - 주말 제외 매일 회의가 진행됩니다. <br> - 추가 안건이 있으면 미리 공유해주시기 바랍니다. | - 다음 회의 일정을 확정합니다.    |

### 2차 프로젝트 회의 | 2024-02-21 | 참석자: 김승환, 김용철, 임선웅

| 안건        | 내용                                       | 결정사항                             |
|------------|--------------------------------------------|--------------------------------------|
|||

<br>

# 프로젝트 일지

|날짜|이름|뭐 했나요 ?|
|---|---|---|
|2024-02-20|김승환|- 깃허브 README 레이아웃 작성 <br> - 음성인식 코드 완료|


<br>

# 기술 요약

## 모션 사용법

### 마우스 클릭 (좌)
![마우스 클릭](proofvideo/mouseclick.gif)

### 마우스 더블클릭 (좌)
![마우스 더블클릭](proofvideo/mousedoubleclick.gif)

### 마우스 클릭 (우)
![마우스 더블클릭](proofvideo/mouserightclick.gif)

### 마우스 드래그
![마우스 드래그](proofvideo/mousedrag.gif)

### 마우스 클릭&드래그 (좌)
![마우스 클릭&드래그](proofvideo/mouseclickdrag.gif)

### 키보드로 변경
![마우스 클릭&드래그](proofvideo/mouse_to_keyboard.gif)
