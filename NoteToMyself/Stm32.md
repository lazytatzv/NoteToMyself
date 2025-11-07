## coding 
- HALとLLライブラリがあるけど、殆どHALで事足りる
- ピンの設定はcube mxからできる
- ideは重いからmakefile出してvscodeで書いていくことにする
- コード書くときは基本C言語

## cubemxについて
- stm32の設定部分のコードを自動生成してくれる
- 若干重い
- pin configでcommunicationの設定をしたり、gpio周りの設定、ピンの割り振りなどをする
- clock configはそんなにいじることは無さそうなきがしている

## HALライブラリについて
- HAL_関数は少しずつ覚えていく必要がある
- 細かい仕様はAPI refを読む
- HAL_DELAYなどもArduinoとは大分ちがう