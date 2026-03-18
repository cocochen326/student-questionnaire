# Formspree 表单 ID 配置说明

## 需要配置的内容

在 `index.html` 文件中，找到这一行：

```html
<form id="questionnaireForm" action="https://formspree.io/f/xvgpqznl" method="POST">
```

将 `xvgpqznl` 替换为你在 Formspree 创建的表单 ID。

---

## 配置步骤

### 1. 注册 Formspree
访问：https://formspree.io/

### 2. 创建新表单
- 点击 "New Form"
- 输入表单名称（如：Student Questionnaire）
- 输入接收邮箱：**124086081@qq.com**
- 点击 "Create"

### 3. 获取表单 ID
- 创建成功后，你会看到一个表单 URL，格式如：
  `https://formspree.io/f/abcd1234`
- 复制最后的 ID（如：`abcd1234`）

### 4. 更新 index.html
将表单 URL 中的 ID 替换为你刚获取的 ID

### 5. 验证邮箱
- Formspree 会发送验证邮件到 124086081@qq.com
- 点击邮件中的验证链接

### 6. 测试
- 提交一次测试问卷
- 检查邮箱是否收到数据

---

## 免费额度
- 每月 50 次提交
- 足够个人使用
