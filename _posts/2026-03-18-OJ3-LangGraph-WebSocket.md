---
layout: post
title: "OJ指针类型 与 LangGraph、WebSocket总结笔记"
date: 2026-03-18
---

## OJ 指针类型三道错题：

### 查找数组最大值（指针访问）

飞书笔记：https://gcnqbk3mr3ut.feishu.cn/docx/WFzadjJ5YokR0DxA9yTcGmq5nLe

<img width="240" height="243" alt="image" src="https://github.com/user-attachments/assets/6ea242f4-5352-4409-8707-5a94e5fd7b75" />

总结：
1. 在oj中，对于数组空间，若不采取动态分配，则在开辟空间的时候应该开大点；
2. 对于指针的使用，应熟练掌握其本质核心；

---

### 动态矩阵（指针与堆内存分配）

飞书笔记： https://gcnqbk3mr3ut.feishu.cn/docx/PJytdUMAtos4gJxlOPScz3SmnCe

<img width="253" height="222" alt="image" src="https://github.com/user-attachments/assets/3e7f8eaa-1d91-4862-b29c-5b0a884b5940" />

总结：
1. 熟练掌握动态创建二维数组；
2. 补充拓展：释放动态二维数组的内存的方法：逐层释放：

    for(int i=0;i<m;i++)
    {   
        delete[] p[i]; //先释放行内列数组
    }
    delete[] p;  //再释放行指针数组

   ---

   ### 函数调用（函数指针）

   飞书笔记：https://gcnqbk3mr3ut.feishu.cn/docx/C5pTdFggCohUTtxPGwqc61ionRe

   <img width="280" height="287" alt="image" src="https://github.com/user-attachments/assets/2fd394c9-a121-429a-8a18-eb7ee0e256c4" />

总结：
1. 在使用getline、cin.ignore()时需添加头文件<cstring>,注意getline的使用格式，对于字符数组和字符串的格式有所不同；
2. 掌握函数指针的使用；

## LangGraph框架快速入门 总结笔记

飞书笔记： https://gcnqbk3mr3ut.feishu.cn/docx/VebLdCRPmozQS0xZ63NcTtkOnhe

<img width="1413" height="843" alt="image" src="https://github.com/user-attachments/assets/efee8cc7-4e5e-46e3-94ab-752be419ecb0" />

##  WebSocket 用法 总结笔记

飞书笔记： https://gcnqbk3mr3ut.feishu.cn/docx/EstBdRw0YofAyrxUupBcxIsUnie

<img width="1414" height="838" alt="image" src="https://github.com/user-attachments/assets/4023512d-e7ac-4326-bec1-3919131d4882" />

