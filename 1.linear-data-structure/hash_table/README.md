# 해시함수 (Hash Function)

- 임의의 길이의 데이터를 고정된 길이의 데이터로 매핑하는 함수
- 해시 함수 특성
  - 압축성: 다양한 가변 길이의 입력에 대해 고정된 크기의 결과값을 반환하는 성질
  - 효율성: 어떤 입력 값에 대해서도 많은 자원과 시간이 소요되지 않고 처리되는 성질
  - 저항성: 결과값을 바탕으로 입력 값을 찾는 것이 불가능한 성질


--- 

![image](https://user-images.githubusercontent.com/121809824/229341079-cca9a642-526c-4b4a-93cf-c5ed6371e7e1.png)





# 해시테이블 (Hash Table)

- 임의의 길이의 데이터를 고정된 길이의 데이터로 매핑하는 함수
- 우선순위 정렬방식: 배열 기반, 연결리스트 기반, 힙(Heap) 기반 등의 정렬 방식 존재
- 구현 메서드 (method)
  - 데이터 전체 획득/ 비어있는지 확인: PriorityQueue.getBuffer(), PriorityQueue.Empty()
  - 데이터 추가/삭제: PriorityQueue.enqueue(), PriorityQueue.dequeue();
  - 첫번째 데이터/ 사이즈 /전체 삭제: PriorityQueue.front(), PriorityQueue.size(), PriorityQueue.clear()

