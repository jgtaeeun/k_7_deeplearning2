텍스트 전처리                -벡터 		       -모델
판다스                        bow            ML
	                         Tf-idf           DL
                            n-gram
	               버트모델(러깅페이크.전이학습)





1)사용자 또는 api로부터 정보수집을 통해 csv또는 excel 출력
데이터분석가: json(api)=>csv또는 excel로 변환 using python
웹개발자: form(웹) using React



2)전처리 통해 전처리 된 csv또는 excel 출력
데이터분석가:  pandas로 가공-텍스트인 경우 na, 불용어/이미지인 경우 사이즈
웹개발자: 검증

3)저장
데이터분석가:  가공은 파일에 저장(.csv) +주기성데이터는 sql사용해서 db에 저장+ *이미지, 엑셀은 db에 저장하지 않는다.
웹개발자: 검증은 db에 저장

4)처리(ai)를 통해 모델파일 출력(.json)
판다스로 분석->결과 출력
ml -단일시계열, 분리,군집
dl-다중시계열, 이미지(cnn), 자연어처리(rnn)


5)정보전달
pdf (seaborn, matplot)
json파일을 flask로 react에 보내고 react에서 웹으로 출력


파이썬, 판다스, SQL
DL	(파이토치)				-소리로 예측
CNN						  -직업군:중공업
ML(랜덤포레스트.트리)       -직업군:은행권
FLASK(API만들수 있어야함)