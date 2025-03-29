# 📘 上传指南：使用 Fork + Pull Request（PR）

本指南将详细介绍如何使用 GitHub 的 Fork + Pull Request 流程，将您的成果（论文、数据集、工具）上传到 GUET-AI-Hub 平台。

---

## ✨ 什么是 Fork + PR？

Fork 是将仓库“复制”到自己的账户下，便于修改和上传文件。Pull Request（PR）是请求平台管理员将您的修改合并到主仓库。

这个流程不需要管理员给权限，是开源社区最常用的协作方式。

---

## ✅ 上传步骤

### 第 1 步：Fork 仓库到自己账户

1. 打开目标仓库，例如：
   - 论文仓库：[AI-Papers](https://github.com/GUET-AI-Hub/AI-Papers)
   - 数据集仓库：[AI-Datasets](https://github.com/GUET-AI-Hub/AI-Datasets)
   - 工具仓库：[AI-Tools-Systems](https://github.com/GUET-AI-Hub/AI-Tools-Systems)

2. 点击右上角 **“Fork”** 按钮  
3. 选择自己的 GitHub 账户，创建一个同名的副本仓库  
   - 您将获得一个链接类似 `https://github.com/yourname/AI-Papers`

---

### 第 2 步：在 Fork 后的仓库中上传文件

1. 进入您的 Fork 仓库  
2. 点击 `Add file → Upload files`  
3. 上传您的内容，建议新建一个文件夹,例如：
```
Paper_张三_2024_图神经网络
├── README.md
├── paper.pdf
├── bibtex.txt
```

5. 填写提交说明（如“添加论文张三-图神经网络”）  
6. 点击 “Commit changes” 提交

---

### 第 3 步：发起 Pull Request（PR）

1. 返回您 Fork 的仓库主页  
2. 点击 “**Contribute**” 或 “Pull requests” → “New pull request”  
3. 比较分支：
   - **base repository**：GUET-AI-Hub/AI-Papers（或其他）
   - **head repository**：您的账户名/AI-Papers
4. 填写说明，点击 “Create pull request”

---

### 第 4 步：等待管理员审核

- 管理员会审核您的提交内容，如无问题会点击合并（Merge）
- 合并成功后，您的文件就正式进入平台仓库啦！

您也可以在 PR 下留言交流，如有修改建议也会标注提示。


## 📂 推荐文件结构（参考）

- **论文**：

```
Paper_姓名_年份_关键词
├── README.md
├── paper.pdf
├── bibtex.txt
```


- **数据集**：

```
Dataset_姓名_关键词
├── README.md
├── data
└── LICENSE
```
- **工具**：

```
Tool_姓名_关键词
├── README.md
├── main.py
└── requirements.txt
```






