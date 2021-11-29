## textView 글자 흐르기

* xml에 아래와 같이 작성.
```java
        android:ellipsize="marquee"
        android:focusable="true"
        android:marqueeRepeatLimit="marquee_forever"
        android:singleLine="true"
```

* marquee_forever 는 기본 값이 -1이다. 즉, 몇 번 반복 할 것인가 라고 유추 할 수 있다. 
1을 넣으면 1번만 100을 넣으면 100 번 흐른 뒤 멈춘다.

* 코드에서 textView.setSelected(true)를 해주면 된다.

* 주의 아래와 같은 성질은 흘려보내는 효과가 나지 않는다.
1. editable(false)
2. maxWidth
3. maxLines
4. maxLength
4. editText에도 marquee속성이 있으나 적용하면 죽는다.... textView에서만 사용 해야함.






