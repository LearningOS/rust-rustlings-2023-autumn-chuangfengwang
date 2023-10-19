
# 环境
1. 安装 rust
    ```bash
    brew install rustup
    rustup-init
    source "$HOME/.cargo/env"
    
    # 检验安装
    rustup -v
    rustc -V
    ```
2. 加入课程专属 classroom
   1. 点击[链接](https://classroom.github.com/a/gbr5Jk7V)
   2. 加入课程,并授权,创建类似 https://github.com/LearningOS/rust-rustlings-2023-autumn-chuangfengwang 的仓库
   3. 点击 Open in Visual Studio Code, 会调用本地 vsc, 安装插件, 在 home目录下clone刚创建的仓库,位置类似 `github-classroom/LearningOS/rust-rustlings-2023-autumn-chuangfengwang`
      1. 如果存在 `Open Assignment: Failed to run git clone xxx` 的问题, 点进创建的仓库页面 https://github.com/LearningOS/rust-rustlings-2023-autumn-chuangfengwang , 用自己可以的方式 clone 到本地, 并用 vsc 打开
   4. 在 vsc 里打开 terminal (默认目录为当前项目的根目录,不在的话cd过去), 执行 `cargo install --path .` , 会安装 rustlings 及其依赖
      1. 如果已经安装了官方版的 rustlings, 先卸载 `cargo uninstall rustlings`
   5. 在**项目根目录**下执行 `rustlings watch` 看看是不是 100 道题
   
# 解题
在**项目根目录**下执行 `rustlings watch`, 修改代码, 保存时会触发编译
编译运行通过后, 删除行注释 `// I AM NOT DONE`
git 提交后 push (git add, git commit, git push 三个操作), 触发 classroom 自动判定
