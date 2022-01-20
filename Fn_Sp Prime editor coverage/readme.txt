clinvar"N"_"XX"
XX : GG 또는 CC를 기준으로 만들 파일입니다.
N : N은 NGG 또는 CCN을 기준으로 얼마만큼 떨어져 있나입니다.
NGG는 가운데 G부터 1로 시작합니다. 

N | NNN | NNN | NGG 
9  | 876  |  543  | 210

CCN | NNN | NNN | N
012  | 345  | 678  | 9

이기 때문에,

clinvar5_GG, clinvar5_CC가 SpCas9의 범위 안에 있는 SNP
clinvar8_GG, clinvar8_CC가 Fncas9의 범위 안에 있는 SNP라 생각하시면 될 것 같습니다.

또한 clinvar5_GG의 경우
clinvaer1,2,3,4,5를 다 포함하고 있는 파일이라 생각하시면 편하십니다!