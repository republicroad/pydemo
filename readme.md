
# python练习


## vscode config

[使用环境变量在终端中激活环境](https://github.com/microsoft/vscode-python/wiki/Activate-Environments-in-Terminal-Using-Environment-Variables)  

## 目录结构
docs 是python中重要的知识点文档.

```bash
$ tree -L 2 .
.
├── docs
│   ├── area_base_demo.json
│   ├── chinook.zip
│   ├── Chinook_PostgreSql.sql
│   ├── Chinook数据分析.pdf
│   ├── Duckdb测试数据集问题答案--本地数据.pdf
│   ├── 后端1.pdf
│   ├── 后端2.pdf
│   ├── 后端3.pdf
│   └── 后端4.pdf
├── fastapidemo.py  # fastapi 
├── pgdemo.py       # fastapi,postgresql
├── readme.md
├── redisdemo.py    # fastapi,redis
├── requirements.txt
└── tests
    └── test_fastapi_db_transaction.py
```



## 练习
> 参考 docs/后端3.pdf 中的 chinook 中的er图, 在 fastapi 中实现 employees customers 这两个表的增删改查接口.  
> 将redis的其他数据结构实现为 fastapi 的一个endpoint(接口)  


运行程序:  
> uvicorn.exe redisdemo:app