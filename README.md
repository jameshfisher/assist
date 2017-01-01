USB controller:

```
         _.=H=._____||___.=J=.__
        / \_.=G=.___==_____.=I=._\
       / /   K                    \
      / /    ^                A    \
     / /  N<   >L           D   B   \
    | |      v                C      |
    | |      M    _S_      _O_       |
    | |        V(( E )T R(( F )P     |
    | |     /\    ---      ---/\     |
    | |    /  \____U________Q/\ \    |
    \_\___/                    \_\___/

```

The controller is fucked in that the stick axes overlap with other buttons and
emit the same key codes. Specifically:

* B = P
* D = R
* K = S
* M = U

We "fix" this by ignoring the bottom two sticks. Then we have [A,N].
