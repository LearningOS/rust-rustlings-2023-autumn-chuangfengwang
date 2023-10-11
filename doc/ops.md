
# 环境
1. 安装 rust
    ```bash
    brew install rustup
    rustup-init
    source "$HOME/.cargo/env"

    rustup -v
    rustc -V
    ```
2. 加入课程专属 classroom
   1. 点击[链接](https://classroom.github.com/a/gbr5Jk7V)
   2. 加入课程授权,创建类似 https://github.com/LearningOS/rust-rustlings-2023-autumn-chuangfengwang 的仓库
   3. 点击 Open in Visual Studio Code, 会调用本地 vsc, 安装插件, 在 home目录下clone刚创建的仓库,位置类似 `github-classroom/LearningOS/rust-rustlings-2023-autumn-chuangfengwang`
   4. 在 vsc 里打开 terminal (默认目录为当前项目的根目录,不在的话cd过去), 执行 `cargo install --path .` , 会安装 rustlings及其依赖
   5. 在**项目根目录**下执行 `rustlings watch` 看看是不是 100 道题
   
# 解题
