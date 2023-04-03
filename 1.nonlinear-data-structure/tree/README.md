# 트리 (tree)

- 그래프의 일종으로 두 노드 사이의 하나의 간선만 연결되어 있는, 최소 연결과 계층 형태의 비선형 자료구조
- 트리 구조 및 용어
  - 노드(node) : 하나 이상의 값을 갖는 객체 단위
  - 간선(edge) : 두 노드를 연결하는 선
  - 루트 노드(Root node) : 부모가 없는 최상위 노드
  - 단말 노드(Leaf node) : 자식이 없는 노드
  - 부모 노드(Parent node) : 특정 Sub-Tree 내에서의 하위 노드
  - 자식 노드(Child node) : 특정 Sub-Tree 내에서의 하위 노드
  - 형제 (Sibling) : 같은 부모를 가르키는 노드



![image](https://user-images.githubusercontent.com/121809824/229544727-afcf1f3e-3fad-43f4-8e93-f4fe3eee4255.png)


--- 
- 트리 특징
  - 주요특징: '최소 연결 트리'로 불림, 계층 모델, 방향 비순환 그래프(DAG:Directed Acyclic Graph) 한 종류
  - 트리종류: 이진트리, 이진탐색트리, AVL, 트리, 힙(Heap) 
  - 용어
    - 노드크기(size): 자신을 포함한 모든 자손 노드의 개수
    - 노드 깊이(depth): 루트에서 특정 노드에 도달하기 위한 간선의 개수
    - 노드 레벨(level): 트리의 특정 깊이를 가지는 노드의 집합
    - 노드 차수(degree): 노드가 지닌 가지의 수
    - 트리 차수(tree degree): 트리의 최대 차수 
    - 트리 높이(height): 루트 노드에서 가장 깊숙이 있는 노드의 


![image](https://user-images.githubusercontent.com/121809824/229547683-83061215-13ef-4190-ba72-2fe082d4c498.png)


