# 토마토 타이머 (뽀모도로 타이머)
## 기능
- SeekBar를 조작해 시간을 설정할 수 있습니다
- SeekBar의 핸들(thumb)을 잡고 목표 시간을 조정하면 타이머의 숫자가 변하고
- 손을 놓으면 타이머가 시작됩니다
- 목표 시간이 종료되면 벨이 한번 울립니다
- 시간 조정은 분 단위로 가능합니다

## 사용 기술
- SeekBar
- CountDownTimer
- SoundPool

### 해결하고싶은 문제
- SeekBar에서 Thumb와 Progress바가 같이 보이길 원해서 SeekBar 옵션에 `android:splitTrack="false"`를 추가해서 미리보기에는 적용 됐지만 실제 앱에는 적용되지 않은 채로 빌드됨

### 추후 업데이트 예정
- 다양한 설정 기능
    - 틱킹/벨 소리 on/off
    - 진동으로 알림 on/off
- pip모드 혹은 백그라운드 모드
- 시간 입력하여 설정
- 일시 중지 / 중지
- 집중 모드 (화면 까맣게 + 화면 잠금)
- 잠금 화면에서 표시