# PC 모니터 (PcMonitor)

CPU·메모리·디스크·네트워크·GPU 사용량과 온도를 실시간 그래프로 보여주는 Windows 프로그램입니다.

## 다운로드

[**PcMonitor.zip 받기**](https://github.com/jeoncassis/PcMonitor/releases/latest/download/PcMonitor.zip) (Windows 10/11)

압축을 풀고 `PcMonitor.exe`를 실행하세요. 처음 실행할 때 "Windows의 PC 보호" 창이 뜨면 **추가 정보 → 실행**을 누르세요.

## 기능

- 실시간 그래프, 일시정지(Space), 갱신 간격 선택, 항상 위
- 작업 표시줄 트레이에 CPU 사용률 숫자 표시, 최소화하면 트레이로 숨김
- CPU·메모리·온도 기준 초과 시 알림 (기준값·지속 시간·반복 간격 설정)
- 설정은 `%APPDATA%\PcMonitor\settings.ini`, 알림 기록은 `alerts.log`에 저장

온도는 메인보드(ACPI) 센서 값이라 CPU 코어 온도보다 낮게 나올 수 있습니다.

