# ghc

> 格拉斯哥 Haskell 编译器。
> 编译并链接 Haskell 源文件。
> 更多信息: <https://downloads.haskell.org/ghc/latest/docs/users_guide/usage.html>.

- 寻找并编译当前目录下的所有模组（module）：

`ghc Main`

- 编译单个文件：

`ghc {{源/文件/的路径.hs}}`

- 优化编译：

`ghc -O {{源/文件/的路径.hs}}`

- 编译目标文件（.o）：

`ghc -c {{源/文件/的路径.hs}}`

- 启动 REPL（交互式 shell）：

`ghci`

- 对表达式求值：

`ghc -e {{表达式}}`
