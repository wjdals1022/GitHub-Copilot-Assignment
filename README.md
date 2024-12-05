# GitHub-Copilot-Assignmnet

## 프로젝트 개요
이 프로젝트는 다양한 **정렬 알고리즘**(버블 정렬, 선택 정렬, 퀵 정렬, 병합 정렬)을 C++로 구현한 프로그램입니다. 사용자가 입력한 배열을 각 알고리즘으로 정렬하고, 각 알고리즘의 실행 시간을 측정하여 출력합니다. 이 프로젝트는 알고리즘의 성능을 비교하고, 각 정렬 알고리즘의 특성을 이해하는 데 유용합니다.

## 구현된 정렬 알고리즘
- **Bubble Sort (버블 정렬)**: 인접한 요소들을 비교하여 큰 값을 뒤로 보내는 방식으로 정렬합니다. 시간 복잡도는 O(n²)입니다.
- **Selection Sort (선택 정렬)**: 배열에서 최솟값을 찾아 첫 번째 위치와 교환하고, 그 다음으로 최솟값을 찾아 두 번째 위치와 교환하는 방식으로 정렬합니다. 시간 복잡도는 O(n²)입니다.
- **Quick Sort (퀵 정렬)**: 기준값(pivot)을 선택하여 배열을 두 부분으로 나누고, 각 부분을 재귀적으로 정렬하는 분할 정복 알고리즘입니다. 평균 시간 복잡도는 O(n log n)입니다.
- **Merge Sort (병합 정렬)**: 배열을 두 개의 부분으로 나누고, 각각을 재귀적으로 정렬한 후 병합하는 알고리즘입니다. 시간 복잡도는 O(n log n)입니다.

## 사용 방법
1. 프로젝트를 클론하거나 다운로드합니다.
2. C++ 컴파일러에서 코드를 실행합니다.
3. 프로그램이 실행되면, 배열의 크기와 값을 입력받습니다.
4. 각 정렬 알고리즘의 결과와 실행 시간을 확인할 수 있습니다.

### 예시 실행
Enter the number of elements: 5 Enter the elements: 5 3 8 2 1

Bubble Sort: 1 2 3 5 8 Time taken: 50 microseconds

Selection Sort: 1 2 3 5 8 Time taken: 40 microseconds

Quick Sort: 1 2 3 5 8 Time taken: 30 microseconds

Merge Sort: 1 2 3 5 8 Time taken: 20 microseconds
