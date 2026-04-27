# CSS 弹性盒子 — 引导式探索活动

欢迎！在这个活动中，你将一次**取消注释**一个 CSS 代码块，然后观察网页预览中发生的变化。

> **你的目标：** 在我们全班讨论之前，先自己弄清楚每个代码块的作用。

## "取消注释"是什么意思？

删除写着"删除此行"的那一行。

**示例 — 之前：**
```css
/* 删除此行
.header {
  background-color: #2c3e50;
}

删除此行 */
```

**示例 — 之后：**
```css
.header {
  background-color: #2c3e50;
}
```

---

## 逐步探索

按顺序完成每一个步骤。每完成一步后，查看预览页面，并在笔记中回答思考问题。

---

### 第 1 步 — 取消注释 `.body`

找到这个代码块并取消注释：

```css
.body {
  font-family: Arial, sans-serif;
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}
```

**思考问题：** 你注意到了什么？有什么移动或改变了吗？

---

### 第 2 步 — 取消注释 `.header`

找到这个代码块并取消注释：

```css
.header {
  background-color: #2c3e50;
  color: white;
  padding: 24px;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 8px;
}
```

保存并查看预览。

**思考问题：** 标题和副标题移动到哪里了？你认为是哪个属性导致了这个变化？删除 `flex-direction`，会发生什么？

> **提示：** 注意 `align-items` 和 `flex-direction`。

---

### 第 3 步 — 取消注释 `.nav`

找到这个代码块并取消注释：

```css
.nav {
  background-color: #34495e;
  padding: 12px 24px;
  display: flex;
  flex-direction: row;
  justify-content: center;
  gap: 24px;
}
```

保存并查看预览。

**思考问题：** 导航链接发生了什么变化？是什么在它们之间创造了间距？把 `flex-direction` 改成 `column`，会发生什么？

> **提示：** 注意 `gap` 和 `flex-direction: row`。

---

### 第 4 步 — 取消注释 `.a-style`

找到这个代码块并取消注释：

```css
.a-style {
  color: white;
  text-decoration: none;
  font-size: 1rem;
}
```

保存并查看预览。

**思考问题：** 链接有什么变化？这是弹性盒子的效果，还是其他原因？

> **提示：** 不是每个 CSS 属性都是弹性盒子属性——有些只是普通样式。

---

### 第 5 步 — 取消注释 `.main`

找到这个代码块并取消注释：

```css
.main {
  flex: 1;
  display: flex;
  gap: 24px;
  padding: 32px 24px;
  background-color: #ecf0f1;
}
```

保存并查看预览。

**思考问题：** main 里面的两个区块发生了什么？你认为 `flex: 1` 在做什么？加上 `flex-direction: column`，会发生什么？

> **提示：** 两个区块现在并排放置了。是哪个属性导致了这个变化？

---

### 第 6 步 — 取消注释 `.section`

找到这个代码块并取消注释：

```css
.section {
  display: flex;
  flex: 1;
  flex-direction: column;
  gap: 8px;
  background-color: white;
  padding: 24px;
  border-radius: 6px;
}
```

保存并查看预览。

**思考问题：** 两个区块现在宽度相同。是哪个属性让它们相等的？加上 `flex-direction: column` 会怎样？

> **提示：** 观察 `.section` 上的 `flex: 1`——把它和 `.main` 上的 `flex: 1` 比较一下。

---

### 第 7 步 — 取消注释 `.footer`

找到这个代码块并取消注释：

```css
.footer {
  background-color: #2c3e50;
  color: white;
  padding: 16px 24px;
  display: flex;
  justify-content: center;
  align-items: center;
}
```

保存并查看预览。

**思考问题：** 页脚文字居中了。是哪两个属性做到这一点的？它们有什么区别？

> **提示：** 一个控制左右居中，一个控制上下居中。

---

## 完成了！

你的页面现在应该包含：

- 带有居中文字的深色页眉
- 链接并排显示的导航栏
- 两个并排放置的等宽区块
- 带有居中文字的深色页脚

---

## 小组讨论

和你的搭档讨论，并写下：

| | 你的答案 |
|---|---|
| **一个发现** — 你注意到弹性盒子做了什么 |  |
| **一个疑问** — 你还有什么不明白的地方 |  |

你们将向全班分享这些内容。

---

## 挑战（提前完成的同学）

你能改变 CSS 中的一个值，并在保存之前预测会发生什么吗？

试试这些：

- 将 `.nav` 中的 `justify-content: center` 改为 `justify-content: space-between` — 会发生什么？
- 将 `.main` 中的 `flex-direction: row` 改为 `flex-direction: column` — 会发生什么？
- 从 `.section` 中删除 `flex: 1` — 两列会发生什么变化？

先写下你的预测，然后保存并检查结果。
