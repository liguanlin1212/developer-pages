---
layout: post
title: "leecode2:高精度问题与快速判断单调序列技巧 && 更新FastAPI笔记"
date: 2026-03-26
---

# leecode2 

## 加一（高精度问题）

https://gcnqbk3mr3ut.feishu.cn/docx/OxOxdl7vIo43A5xI5WucNqzYnAg

总结：
1. 对于高精度问题，我们不能直接转为整数变量去运算，因为会超出整型变量的表示范围，因此，我们应该对数组进行原地操作，或者转为字符串来操作；


## 快速判断单调序列（技巧）

https://gcnqbk3mr3ut.feishu.cn/docx/LWUFdVU4Vo9Q0sx7nrpcLo7PnZF

```
class Solution {
public:
    bool isMonotonic(vector<int>& nums) {
        return is_sorted(nums.begin(), nums.end()) || is_sorted(nums.rbegin(), nums.rend());
    }
};
```
<img width="847" height="480" alt="image" src="https://github.com/user-attachments/assets/d1e74e25-12e2-43f4-8d54-b3753a821f11" />


# 更新FastAPI笔记

<img width="400" height="778" alt="image" src="https://github.com/user-attachments/assets/70f0e6d0-18ad-4760-8183-62ec62367b70" />

<img width="246" height="774" alt="image" src="https://github.com/user-attachments/assets/b4cd41ee-2a7b-402c-9d81-0de22144fa22" />
