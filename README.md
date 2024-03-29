## Kaggle Football data 분석 및 시각화

- id : 선수 고유의 아이디
- name : 이름
- age : 나이
- continent : 선수들의 국적이 포함되어 있는 대륙입니다
- contract_until : 선수의 계약기간이 언제까지인지 나타내어 줍니다
- position : 선수가 선호하는 포지션입니다. ex) 공격수, 수비수 등
- prefer_foot : 선수가 선호하는 발입니다. ex) 오른발
- reputation : 선수가 유명한 정도입니다. ex) 높은 수치일 수록 유명한 선수
- stat_overall : 선수의 현재 능력치 입니다.
- stat_potential : 선수가 경험 및 노력을 통해 발전할 수 있는 정도입니다.
- stat_skill_moves : 선수의 개인기 능력치 입니다.
- value : FIFA가 선정한 선수의 이적 시장 가격 (단위 : 유로) 입니다

### 분석 요약
- Name 컬럼은 삭제(유의미한 도출이 나오지 않는다 판단)
- Age는 20 초반 ~ 중반에 대부분 분포
- 유럽 국적의 사람이 절반 이상
- 현재 능력치, 잠재력 분포 확인
- 포지션은 미드필더가 가장 많음
- 주 발이 오른발이 많다는 것 확인 가능
- 계약기간 : 2021, 2020, 2019 선수 대부분
- 평판은 1이 대부분
- 개인기 능력 2가 제일 많고, 5는 소수라는 것 확인
------------------------
- 미드필더는 개인기 능력치의 값이 4가 많으며, 가치는 2보다 3이 3보다 4가 평균적으로 높은 것을 볼 수 있다. 하지만 개인기 능력치가 5라고해서 가치가 높다라고 판단 할 수 없다.
- 수비수는 개인기 능력치의 값이 2가 많으며, 가치는 2가 3보다 높은 것을 볼 수 있다. 따라서 수비수는 개인기가 중요하지 않다고 판단 할 수 있다.
- 공격수는 개인기 능력치의 값이 2의 값이 적은 것을 볼 수 있으며, 개인기 능력치의 값이 4인 사람들이 평균적으로 가치가 높은 것을 볼 수 있다.
- 골키퍼는 개인기 능력치가 1이며, 모두 동일한 것을 볼 수 있다.
