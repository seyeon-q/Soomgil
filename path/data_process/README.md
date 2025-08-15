**add_columns.ipynb**
nodes.csv, edges.geojson 데이터에 도로, 공원, 하천, 산 column 추가
도로는 1으로 초기화하고 나머지는 0으로 초기화

**add_type_tag**
수작업으로 폴리곤 그릴 수 있는 html 파일 생성
폴리곤 영역 안에 있는 nodes, edges 추출
해당하는 nodes, edges의 target_tag 값을 1로 변경(도로 column 값은 0로 변경)

**original_data**
전처리 하기 전의 원본 데이터들

**modified_data**
전처리가 된 데이터들

**backup_data**
선택했던 폴리곤의 정보들(selected_area.geojson) 백업