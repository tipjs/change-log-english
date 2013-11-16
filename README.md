# ChangeLog 를 지탱하는 영어

[원문](https://gist.github.com/hayajo/3938098) - [https://gist.github.com/hayajo/3938098](https://gist.github.com/hayajo/3938098)

![](http://cdn-ak.f.st-hatena.com/images/fotolife/h/hayajo_prpr/20130118/20130118093039.jpg?1358469248)

ChangeLog를 작성할 때 자주 사용되는 영어를 정리했습니다.

대부분 인용입니다.

## 기본형

기본적인 문법입니다. 나머지는 단어를 알고 있으면 대개 어떻게든 된다고 합니다.

### 대문자로 시작한다

    Fix possible memory leak
    Removed obsolete username_max_length

### 마침표를 붙이지 않는다

    Changed A to B
    Upgraded A to version 1.0

### 동사의 과거형으로 시작 "~을 ...했습니다" 형

    Fixed a performance regression
    (성능이 저하하는 버그를 수정하였습니다.)

### "~는 ... 할 수 있습니다" 형

now + 동사의 과거 분사. 사양 변경 등의 경우에 사용합시다.

    Minimized pages are now hidden
    (최소화 된 페이지는 앞으로 숨길 수 있습니다)

### 명사구만

"~ (라고하는) 것" 적인.

    Many usability improvements
    (많은 유용성의 향상)

## 조금 편리한 표현

익숙해졌으면 약간의 재치를 살려봅시다.

### 가끔

a possible 를 사용

    a possible crash.
    (가끔 충돌)

    a possible null pointer dereference.
    (가끔 널포인트 역참조)

### 결함

치명적이지 않는 결함은 issue를 사용한다.

    the stability issue.
    (안정성 문제)

## 자주 사용하는 동사

- 신규 추가

  add, added

        Added support for bridgeless SLI with GeForce 8 GPUs

- 개선

  improve, improved

        Improved device handling

- 변경

  change, changed

        Changed A to B

- 수정

  modify, modified

        Modified IPv6 default listen address

- 버그 수정

  fix, fixed

        Fixed a bug in test.t

- 삭제

  remove, removed

        Removed a dependency to Huge::Module

- 취소 (되돌리기)

  revert, reverted

        Revert the 'require' in command.cmd to do 'do'

- 업데이트

  update, updated

        Updated docs for new-features options

  > Win7 -> Win7-SP1

- 기능추가

  upgrade, upgraded

        upgraded to 1.0

  > Win7 -> Win8

- 유효/무효

  enable, enabled / disable, disabled

        Enabled type checking of the app in MyApp::sub

- 확장

  extend, extended

- 강화, 향상

  enhance, enhanced

- 구현

  implement, implemented

        Implemented app.streaming in all blocking servers

- 리팩터링

  refactor, refactored

        Refactored MyApp

- 최적화

  optimize, optimized

        Optimized a process

- 절감, 절약

  reduce, reduced

        Reduced kernel virtual memory usage with some GeForce 8 GPUs

## 관사(a, the, any, some)

- a, the

  그것과 다른 것을 대체 할 문장이 성립되는 경우.
  어느쪽이든 상관없을때 a

  그것이 아니면 문장이 성립되지 않는 경우.
  그게 아니면 안되는 것이 the

  > - 그래서 거지는 "Would you give me a quarter."(25센트를 줄래)라고 말하는반면 거래에서는 "Give me the money."(그돈을 넘겨라)라고 말하는겁니다....라는것은 반농담입니다만 그런 것입니다.
  > - OOP(Object Oriented Programming)로 말하면 a가 class고 the가 instance.

- any, some

  any => a, some => the

  > ♪Help! I need somebody<br/>
  > ♪Help! Not just anybody

### 주의사항

- 고유명사에는 the를 안붙임

  고유명사: 인명이나 그룹명, 지명등 그것이외에는 존재하지않는 특정의 대상을 나타내는 명사

  > Sun, Moon, Internet

- 작품소개에서는 a 를 사용

  > - Spirited Away' is a Miyazaki film. The movie won the Academy Award in 2001.
  > - It's a Sony

## 인용

- [Changelogのための英文テンプレート集 - ぴょぴょぴょ？ - Linuxとかプログラミングの覚え書き -](http://d.hatena.ne.jp/pyopyopyo/20070920)
- [辞書で引けない技術英語 ChangeLogでよく使う表現](http://linuxenglish.blog83.fc2.com/blog-entry-115.html)
- [404 Blog Not Found:プログラマーでなくてもわかるaとtheの違い](http://blog.livedoor.jp/dankogai/archives/50963216.html)
- [aとtheの話: 極東ブログ](http://finalvent.cocolog-nifty.com/fareastblog/2004/02/athe.html)
- [英語でコミットを書こう](https://speakerdeck.com/pwim/ying-yu-dekomitutowoshu-kou)
- [コミットメッセージの書き方 - ククログ(2012-02-21)](http://www.clear-code.com/blog/2012/2/21.html)
- [わかりやすいコミットメッセージの書き方 - ククログ(2013-04-24)](http://www.clear-code.com/blog/2013/4/24.html)

## 그럼

Enjoy!

