# **필터 추가시 주의사항**

이번에 새로 추가된 필터 요소 기능에 대한 몆가지 주의사항을 알려드립니다.

필터 요소 기능은 한 채팅에 여러 조건을 부여할 수 있는 기능입니다.

만약 필터에 필터 요소가 1개 이면서 제외로 설정되어 있는 경우 필터 기능이 제대로 동작하지 않을 수 있습니다.

***

![FilterElements_1](./assets/filterElements_1.png)

> 위와 같이 설정한 경우 채팅의 닉네임이 "Nightbot" 인 채팅을 수집합니다.

![FilterElements_1](./assets/filterElements_2.png)

> 반대로 필터의 조건을 제외로 설정하면 닉네임이 "Nightbot" 인 채팅은 수집하지 않습니다.

![FilterElements_1](./assets/filterElements_3.png)

> 그러나 "Nightbot" 의 채팅을 제외하기 위해 위와 같이 설정하면 필터 기능이 제대로 동작하지 않습니다.
왜냐하면 위 설정은 **"Nightbot" 닉네임이 아닌 채팅을 제외**하는 설정이기 때문입니다.

![FilterElements_1](./assets/filterElements_4.png)

> 반대로 세번째 예시의 필터의 조건을 포함으로 설정하면 **'Nightbot' 닉네임이 없는 채팅을 모두 포함**하는 설정이 됩니다.

채팅이 나오지 않거나 모든 채팅이 그대로 복사되는 현상을 겪고 계시는 분들은 세번째, 네번째 예시와 같이 설정된 필터가 있는지 확인해주세요.
