# 한국어 관계(relation) 추출 골드 스탠다드

### 폴더 구조 설명
* relation-info: 골드 스탠다드 데이터의 관계 정보
	* relation-definition.txt: 골드 스탠다드 데이터의 관계들의 정의
* guidelines: 한국어 관계 추출 골드 스탠다드 제작 시 어노테이터들에게 제공된 가이드라인 문서들
	* DS Annotation Guideline (Silver Standard).pdf: 실버 스탠다드 제작 시 사용된 가이드라인 문서
* silver-standard: 사람이 태깅해서 만든 실버 스탠다드로, 어느정도 신뢰할 수 있으나 완벽한 정답셋에는 미치지 못함. 한 데이터당 한 명의 어노테이터가 작업
* gold-standard-v1: 사람이 태깅해서 만든 골드 스탠다드로, 한 데이터당 세 명의 어노테이터가 작업한 결과
	* agreement_content.txt: 세 명의 어노테이터 모두 동일한 정답을 제출한 데이터들
	* conflict2agreement_content.txt: 세 명의 어노테이터가 다른 정답을 제출하여 Majority Voting을 적용한 데이터들
