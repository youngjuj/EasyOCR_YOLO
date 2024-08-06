# EasyOCR과 YOLOv8, FastText, Kahiii
를 활용한 영수증 글자추출 및 카테고리 분류

1. YOLOv8-seg 모델을 활용하여, 텍스트영역을 분리
2. 분리된 영역의 이미지에서 EasyOCR을 활용하여 텍스트 추출
3. FastText를 활용하여 추출된 글자의 카테고리 분류

(Python 3.9)
