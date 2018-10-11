# 编辑及输出

1. 单篇以 markdown 文件编写，经脚本处理成 html 及 pdf；

    ```shell
    pandoc IN.md -so OUT.html
    # see more on https://pandoc.org/demos.html
    ```

1. 维护 toc 列表：

    1. 经脚本处理成 SUMMARY.md，以供 gitbook 输出：

        1. 本地可输出 pdf；
        1. 多网页需要在线服务(gitbook, kancloud)；

    1. 自动处理成 toc.html，以供 html 输出
