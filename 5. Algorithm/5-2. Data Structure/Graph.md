## DFS에 대해 아는대로 설명해 주세요.

DFS는 깊이 우선 탐색으로, 루트 노드 혹은 임의 노드에서 다음 브랜치로 넘어가기 전에 해당 브랜치를 모두 탐색하는 방법으로, 스택 또는 재귀함수로 구현합니다.

모든 경롤르 방문해야할 경우 적합한 그래프 탐색 알고리즘입니다.

## BFS에 대해 아는대로 설명해 주세요.

BFS는 너비 우선 탐색으로, 루트 노드 또는 읨의 노드에서 인접한 노드부터 먼저 탐색하는 방법으로, 큐를 통해 구현합니다.

최소 비용을 구할 때 적합한 그래프 탐색 알고리즘입니다.

## 다익스트라 알고리즘에 대해 아는대로 설명해 주세요.

다익스트라 알고리즘은 특정한 정점에서 다른 모든 정점으로 가는 최단 경로를 기록하는 알고리즘입니다. 주로 가중치가 있는 그래프에서 각 간선의 가중치 합이 최소가 되는 경로를 찾을 때 사용합니다.

최단 거리 값은 무한대로 초기화한 상태로 시작합니다. 시작 정점의 최단 거리는 0이고, 방문 처리를 합니다. 시작 정점과 연결된 정점들의 최단 거리 값을 갱신합니다. 방문하지 않은 정점 중 최단 거리가 최소인 정점을 찾습니다. 찾은 정점을 방문 처리를 한 다음, 해당 정점과 연결된 방문하지 않은 정점의 최단 거리 값을 갱신합니다.
이 과정을 모든 정점을 방문할 때까지 반복합니다.
