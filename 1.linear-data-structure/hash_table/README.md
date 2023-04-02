# 해시함수 (Hash Function)

- 임의의 길이의 데이터를 고정된 길이의 데이터로 매핑하는 함수
- 해시 함수 특성
  - 압축성: 다양한 가변 길이의 입력에 대해 고정된 크기의 결과값을 반환하는 성질
  - 효율성: 어떤 입력 값에 대해서도 많은 자원과 시간이 소요되지 않고 처리되는 성질
  - 저항성: 결과값을 바탕으로 입력 값을 찾는 것이 불가능한 성질


--- 

![image](https://user-images.githubusercontent.com/121809824/229341079-cca9a642-526c-4b4a-93cf-c5ed6371e7e1.png)





# 해시테이블 (Hash Table)

- Hash 함수를 사용하여 평균 O(1) 시간 복잡도로 특정 값을 시속하게 찾는 자료구조
- 충돌(Collision) 해결 방법 
  - 해시 함수 변경: 더 큰 숫자의 공간과 Modular 산술 값을 이용해 충돌 최소화
  - 자료구조 확장: Open Addressing Method (선형 조사법, 이중해시) , Close Addressing Method(체이닝)
- 구현 메서드 (method)
  - 객체초기화/ 크기반환: HashTable.clear(), HashTable.size()
  - 전체 데이터 반환/전체 데이터 출력: HashTable.getBuffer(), HashTable.print();
  - 데이터 추가/ 삭제 /반환: HashTable.put(), HashTable.remove(), HashTable.get()

![image](https://user-images.githubusercontent.com/121809824/229341325-be691414-e846-4ae4-ac0a-c42a5953cfe8.png)
