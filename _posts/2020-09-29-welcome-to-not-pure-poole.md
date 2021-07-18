---
layout: post
title: 백준 2231번 "분해합"
date: 2021-07-18 20:00 +0800
last_modified_at: 2020-10-01 01:08:25 +0800
tags: [일상]
toc:  false
---
<strong>Question:</strong>

어떤 자연수 N이 있을 때, 그 자연수 N의 분해합은 N과 N을 이루는 각 자리수의 합을 의미한다. 
어떤 자연수 M의 분해합이 N인 경우, M을 N의 생성자라 한다. 
예를 들어, 245의 분해합은 256(=245+2+4+5)이 된다. 
따라서 245는 256의 생성자가 된다. 
물론, 어떤 자연수의 경우에는 생성자가 없을 수도 있다. 
반대로, 생성자가 여러 개인 자연수도 있을 수 있다.

자연수 N이 주어졌을 때, N의 가장 작은 생성자를 구해내는 프로그램을 작성하시오.

<strong>Input:</strong>

첫째 줄에 자연수 N(1 ≤ N ≤ 1,000,000)이 주어진다.

<strong>Output:</strong>

첫째 줄에 답을 출력한다. 생성자가 없는 경우에는 0을 출력한다.

<strong>Example Case:</strong>

Input: 
216
Output:
198


<mark>풀이 과정:</mark>
이 문제는 방정식을 이용하여 풀이 방향을 이끌어 나가려고 한 문제이다.
예를 들어, 자연수 245의 분해합이 256인데,
이는, 256 = 245 + 2 + 4 + 5을 의미한다.
이를 방정식으로 나타내본다면,
<em> x + y + z + 100x + 10y + z = N </em>
의 값을 구하는 것이다.

따라서, 처음엔
{% highlight js linenos %}
#include <iostream>

using namespace std;

int main() {
  int N,K = 0;
  cin >> N;

}


{% endhighlight %}










