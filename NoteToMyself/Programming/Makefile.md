## Syntax

```makefile
Target: dependencies 
  Command
```
- コマンドのショートカットに便利
- gitとかdockerとかros2のコマンド省略したり、まとめてコマンド実行したりする時によい
- justとかと違ってmakeは大体入ってる
- 入ってるかは`make -v`で確認できる