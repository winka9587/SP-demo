
# sphereical pendulum simulation(SP_Demo)

visit Github Page to use this demo:

https://winka9587.github.io/SP-demo/

click "run" to enjoy(or suffer)

## about

This is a sphereical pendulum simulation demo base on WebGL

just change the wind, drag the ball and add friction coefficient

do what you want

(sample xyz is a reference point to make sure you know the right direction and position.)

<img src='https://raw.githubusercontent.com/winka9587/MD_imgs/main/Norproject/2022-08-19-data1.gif' width="50%" >

<img src='https://raw.githubusercontent.com/winka9587/MD_imgs/main/Norproject/2022-08-19-data2.gif' width="50%" >

## Note

根目录下有两个.html文件, 如果想要在本地运行demo可以使用sp-demo.html（搭配VSCode的live server扩展能够快速运行demo）

index.html专门为GithubPage 修改了js包的路径。因为GitHubPage使用ES6语法导入包在使用相对路径在的时候会遇到一点问题(https://github.com/jekyll/jekyll/issues/332 中可能有更优雅的解决方案但我已经不想搞了...)，直接向package路径中添加项目名称来导向正确的路径。

