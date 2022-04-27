---
title: "big-O"
date: 2022-04-27
categories: jekyll update
---

big-O : 알고리즘의 효율성을 나타내는 지표

시간복잡도
O(N) : N이 증가함에 따라 수행 시간도 증가
O(1) : 데이터와 관계없이 수행 시간 고정

최선의 경우 > O(1) or O(N)
최악의 경우 > O(N²)
평균적인 경우 > O(NlogN)

공간복잡도 (메모리)
크기가 n 인 배열 > O(n)
n x n의 2차원 배열 > O(n²)

int sum(int n) {
  if (n <= 0) {
    return 0;
  }
  
  return n + sum(n-1);
}
위 코드는 O(n)의 시간과 O(n)의 공간을 사용한다.

Big-O Complexity Chart : https://www.bigocheatsheet.com/
출처 : https://www.bigocheatsheet.com/

log N 수행시간 : 원소의 개수가 절반씩 줄어든다면 O(logN) 일 가능성이 크다.
