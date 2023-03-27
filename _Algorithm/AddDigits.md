---
layout: single
title:  "자릿수 더하기 C++"
---

# [프로그래머스] 자릿수 더하기 C++

```cpp
#include <iostream>

using namespace std;
int solution(int n)
{
    int answer = 0;

    // 자릿수 더하기
    while (n>0)
    {
        answer+=n%10;
        n/=10;
    }

    return answer;
}
```
