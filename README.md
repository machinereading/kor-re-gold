# 한국어 관계(relation) 추출 골드 스탠다드

### 폴더 구조 설명
* relation-info: 골드 스탠다드 데이터의 관계 정보
	* relation-definition.txt: 골드 스탠다드 데이터의 관계들의 정의
* guidelines: 한국어 관계 추출 골드 스탠다드 제작 시 어노테이터들에게 제공된 가이드라인 문서들
	* DS Annotation Guideline (Silver Standard).pdf: 실버 스탠다드 제작 시 사용된 가이드라인 문서
* silver-standard: 사람이 태깅해서 만든 실버 스탠다드로 완벽한 정답셋에는 미치지 못함. 한 데이터당 한 명의 어노테이터가 작업 결과
* gold-standard-v1: 사람이 태깅해서 만든 골드 스탠다드로, 한 데이터당 세 명의 어노테이터가 작업한 결과
	* agreement_content.txt: 세 명의 어노테이터 모두 동일한 정답을 제출한 데이터들
	* conflict2agreement_content.txt: 세 명의 어노테이터가 다른 정답을 제출하여 Majority Voting을 적용한 데이터들


### gold-standard 파일 형식
TSV format
* HeadEntity (tab) TailEntity (tab) Relation (tab) Sentence (tab) ID (tab) Answer

### silver-standard 파일 형식
TSV format
* HeadEntity (tab) TailEntity (tab) Relation (tab) Sentence (tab) Answer

### 골드 및 실버 스탠다드 내 Sentence의 형태
* Entity Tagging: 이중 대괄호로 문장 내 개체 표현
* Head/Tail Entity 표현: 
	* [[ _sbj_ ]] = HeadEntity
	* [[ _obj_ ]] = TailEntity
	* ex) 프린스턴_(뉴저지_주)	미국	country	아이리스 장은  [[ 제2차_세계대전 ]]  당시  [[ _obj_ ]] 으로 이민 온 교수 부모 사이에서  [[ 1968년 ]]  미국  [[ 뉴저지_주 ]]   [[ _sbj_ ]] 에서 태어났다.
		* 예문 해석 : 아이리즈 장은 제2차_세계대전 당시 미국으로 이민 온 교수 부모 사이에서 1968년 미국 뉴저지_주 프린스턴_(뉴저지_주)에서 태어났다.

### Publications
* Coming soon...

### Licenses
* `CC BY-NC-SA` [Attribution-NonCommercial-ShareAlike](https://creativecommons.org/licenses/by-nc-sa/2.0/)
* If you want to commercialize this resource, [please contact to us](http://mrlab.kaist.ac.kr/contact)

### Contact
`nam.sangha at gmail.com`

### Acknowledgement
This work was supported by Institute for Information & communications Technology Promotion(IITP) grant funded by the Korea government(MSIT) (2013-0-00109, WiseKB: Big data based self-evolving knowledge base and reasoning platform)
