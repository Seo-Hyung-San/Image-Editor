# Image Editor(<https://github.com/Seo-Hyung-San>)


## Description

- OCR기술을 활용한 이미지 번역 및 편집 에디터

## Use Lang

- Python
- Javascript
- PHP

## Use Library & API

- Lama
- EasyOCR
- OpenCV
- Papago API
- Google Translation API
- KonvaJS

## DataBase

- MariaDB
<br><br>
<div align="center">

# =Simulation=
  
</div>

<div align="center">

# Detecting
<br>
<img src="https://user-images.githubusercontent.com/104816477/204208796-80403561-b4fa-43a7-a15e-a9b61fbd78c1.gif">

# Translate
<br>
<img src="https://user-images.githubusercontent.com/104816477/209915016-76075e1f-79ef-4c70-9e3d-be8f43fd3135.gif">

# Editing
<br>
<img src="https://user-images.githubusercontent.com/104816477/204208814-415c0334-1708-4569-b802-6156a4487a87.gif">

# Merge
<br>
<img src="https://user-images.githubusercontent.com/104816477/204208821-499c2dd8-d379-4c9f-acd5-0524a616794b.gif">

# Crop
<br>
<img src="https://user-images.githubusercontent.com/104816477/204208828-c5dd6eaf-e7f1-4dc7-808c-f27e6eb57940.gif">

# Eraser
<br>
<img src="https://user-images.githubusercontent.com/104816477/209915019-9ffaaeeb-91f2-458f-a448-c945f2a8060e.gif">

# Redo & Undo
<br>
<img src="https://user-images.githubusercontent.com/104816477/204208835-f14eb7a9-ee83-45a4-b3cf-f1b2fe117ff1.gif">

</div>

## Info

- Period : 2022-08-22 ~ 2022-11-14
- 개인 작업물 메모를 위한 ReadMe로 따로 소스코드는 공개하지 않음.

## References

- KonvaJS (<https://konvajs.org/api/Konva.html>)
- EasyOCR (<https://github.com/JaidedAI/EasyOCR>)
- Lama (<https://github.com/saic-mdal/lama>)
- Lama-cleaner (<https://github.com/Sanster/lama-cleaner>)
- PAPAGO API (<https://developers.naver.com/docs/papago/README.md>)
- Google Translation (<https://cloud.google.com/translate/docs/overview>)

## Memo
- 2023-01-12: Thread 방식으로 변경하여 텍스트 디텍팅 속도 개선 (8초->1초)
- 2023-01-26: 텍스트 색상 추출 후 Konva Text에 반영
- 2023-03-08: 특정 사용자에게서 텍스트가 깨지는 현상 발생 -> 인텔의 특정 내부 그래픽으로 인한 문제로 확인 -> 하드웨어 가속 종료로 임시조치..
