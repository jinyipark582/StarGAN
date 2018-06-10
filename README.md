## StarGAN

### 용어 정의
* Attribute : meaningful features (ex. hair color, gender, and age)
* Attribute values : particular values (ex. black/blond/brown for hair color)
* Domain : set of images sharing the same attribute value


### CycleGAN 단점
* n개의 Domains 에 대해 nC2 개의 Generators 와 n개의 Discriminants 가 필요, Domains 가 많아질수록 학습에 어려움
* 특정 attribute 를 지정하여 학습할 수 없음

### StarGAN 목적
* Using Mask vector, n개의 Domains에 대해 1개의 Generators 와 1개의 Discriminats로 동시에 학습
* Using label, 특정 attribute 를 지정하여 학습하여 학습, 여러개 조합 동시에 가능

### StarGAN 개요
![starGAN_idea] (./starGAN_idea.jpg)
