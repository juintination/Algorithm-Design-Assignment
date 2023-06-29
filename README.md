# Algorithm-Design-Assignment
Comparison of QuickSort and LCS Algorithms

---

## 알고리즘 설계 과제 내용

- 설계과제#1 : QuickSort를 3가지(Iterative, Recursive(devide&conquer), Randomized(pivot 요소 랜덤으로 선택)) 버전으로 구현하여 각 알고리즘에 따른 비교 연산 횟수를 비교하는 프로그램 작성
  - 입력 데이터는 아래와 같이 랜덤으로 생성
    ```
    for i(데이터의 사이즈) = 10**2, 10**4, 10**8, 10**16, ...  // 본인 컴퓨터가 적당한 시간 내에 감당할 수 있는 한... 
      for j=1,2,...,30(30개세트를만듬)  // i 사이즈 만큼의 데이터를 j 생성하는 for loop 
        data_set(i,j) = {x | x = random[1..i] * i} 
    ```

- 설계과제#2 : LCS(Longest Common Substring) 알고리즘을 3가지(Recursive, Dynamic Programming(Top-down, Bottom-up)) 버전으로 구현하여 각 알고리즘에 따른 연산 횟수를 비교하고 LCS Path Recovery 알고리즘과 LCS 문제를 변형한 연속적으로 나타나는 LCS(예시: X = abcde, Y=bde 인 경우에 LCS = de)를 구하는 알고리즘을 작성 및 인공지능의 코딩 능력 테스트하는 프로그램 작성
  - 입력 데이터는 아래와 같이 랜덤으로 생성
    ```
    모든 데이터는 알파벳으로 구성
    X/Y 각 스트링 집합의 데이터는 길이가 1 이상 10 이하, 10 이상 20 이하로 3개씩 생성
    모든 가능한 데이터 36쌍에 대한 위의 결과 출력
    ```
    
---

## 기타 사항

- 지도교수 : 신지애 교수님

- 개발환경 : <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white"> <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=Jupyter&logoColor=white">

## 참고

- [설계과제#1 동영상](https://youtu.be/SodVD21TndI)
- [설계과제#2 동영상](https://youtu.be/3SK4hXTHt7Y)
