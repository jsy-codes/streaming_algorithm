# Streaming Algorithms (Bloom / Count-Min / HyperLogLog) on Wikipedia Clickstream (kowiki 2026-10)

## 실행 방법
1. `clickstream-kowiki-2026-10.tsv` 를 이 폴더에 둔다 (https://dumps.wikimedia.org/other/clickstream/2026-10/ 에서 gz 다운로드 후 압축 해제).
2. `pip install -r requirements.txt`
3. `jupyter nbconvert --to notebook --execute streaming_algorithms.ipynb` (약 6분, 단일 코어 기준) 또는 노트북을 열어 순서대로 실행.
   - 데이터 경로는 환경변수 `DATA_PATH`, 출력 폴더는 `OUT_DIR`(기본 `results/`)로 바꿀 수 있다.
4. 결과 CSV/그림은 `results/` 에 저장된다.
