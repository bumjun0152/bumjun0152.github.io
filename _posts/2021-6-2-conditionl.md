---
layout :single
title : "print문_04"
---

[문제 상황]  
가위, 바위, 보 게임을 만들어 봅시다. 가위바위 
보 게임은 다음과 같이 진행됩니다. 
ex1) 
나 입력(가위:s, 바위:r, 보:p): s 
너 입력(가위:s, 바위:r, 보:p): s 
비겼다. 
ex2) 
나 입력(가위:s, 바위:r, 보:p): r 
너 입력(가위:s, 바위:r, 보:p): s 
이겼다. 
ex3) 
나 입력(가위:s, 바위:r, 보:p): p 
너 입력(가위:s, 바위:r, 보:p): s 
졌다. 

~~~
|코드|
me=input('I select ( r / s / p ): ')
you=input('You select ( r / s / p ): ')
if (me=='r' and you=='p') or (me=='s' and you=='r') or (me=='p' and you=='s'):
  print('You WIN !')
elif me==you:
  print('DREW !')
else:
  print('You LOSE !')
~~~

|출력 결과|
나: s 상대방:p 이겼다.
 
 
