# go-lazy-frame 代码自动生成

> 偷懒，是程序员的基本守则
>
> - 仓库地址：
>   - github：[https://github.com/go-lazy-frame/go-lazy-frame-generate.git](https://github.com/go-lazy-frame/go-lazy-frame-generate.git)
>   - gitee：[https://gitee.com/go-lazy-frame/gol-lazy-frame-generate.git](https://gitee.com/go-lazy-frame/gol-lazy-frame-generate.git)

1. 复制 config.example.json 重命名为 config.json
2. 编辑 config.json 配置，配置项说明，请直接查看配置文件，对应修改即可
3. 根据不同的 OS 平台执行对应的可执行文件：
   1. MacOS：`./gen.macos [gen][new][del] <param>`
   2. Linux：`./gen.linux [gen][new][del] <param>`
   3. Windows：`.\gen.exe [gen][new][del] <param>`
   
   以下文档，将以 linux 平台为例。
4. 操作说明：
   - `./gen.linux gen`：代码生成操作
   - `./gen.linux new`：新项目创建操作

## 代码生成操作：`./gen.linux gen`

- 执行文件后，也可以带上配置文件名，若不指定，则为 `config.json`，例如：

```shell
# 加载同目录下的 config-xxx.json 配置文件
 ./gen.linux gen config-xxx.json
 # 加载同目录下的 config.json 配置文件
 ./gen.linux gen
```

- 也可指定环境变量：`config.file.path`，指定加载其他路径的配置




