### 1차 접근
    자연수 집합으로부터 '666'이 포함된 숫자 앞에서부터 세기
    메모리 부족으로 실패

### 2차 접근
1. '666' 기준으로 앞뒤에 1~9를 붙여보자
2. '1666', ... '9666', '6661', ... '6669'
    - '6666'이 겹치는 문제 발생

    - 겹치는 건 귀찮아서 set으로 처리

3. sort후 N-1번째 index의 값 출력
    - 생각해보니까 6660이 없음
    - 0-9를 붙이고 0666은 int로 바꿔 666이랑 같게 만들고
    - set으로 중복 처리