---
layout: single
title:  "자릿수 더하기 C++"
---

### string 변환 없이 푸는 방법

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
