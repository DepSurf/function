# Function: <code>balance_rt</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int balance_rt(struct rq *rq, struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810efdd0)
Location: kernel/sched/rt.c:1472
Inline: True
```
**Symbols:**

```
ffffffff810efdd0-ffffffff810efe56: balance_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int balance_rt(struct rq *rq, struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f9720)
Location: kernel/sched/rt.c:1529
Inline: False
```
**Symbols:**

```
ffffffff810f9720-ffffffff810f97a6: balance_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int balance_rt(struct rq *rq, struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f7ad0)
Location: kernel/sched/rt.c:1531
Inline: False
```
**Symbols:**

```
ffffffff810f7ad0-ffffffff810f7b62: balance_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int balance_rt(struct rq *rq, struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f98c0)
Location: kernel/sched/rt.c:1531
Inline: False
```
**Symbols:**

```
ffffffff810f98c0-ffffffff810f9952: balance_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int balance_rt(struct rq *rq, struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff81113120)
Location: kernel/sched/rt.c:1546
Inline: False
```
**Symbols:**

```
ffffffff81113120-ffffffff811131b2: balance_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int balance_rt(struct rq *rq, struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff811303c0)
Location: kernel/sched/rt.c:1701
Inline: False
```
**Symbols:**

```
ffffffff811303c0-ffffffff811304c0: balance_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int balance_rt(struct rq *rq, struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8115a600)
Location: kernel/sched/rt.c:1697
Inline: False
```
**Symbols:**

```
ffffffff8115a600-ffffffff8115a700: balance_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int balance_rt(struct rq *rq, struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8116a810)
Location: kernel/sched/rt.c:1697
Inline: False
```
**Symbols:**

```
ffffffff8116a810-ffffffff8116a910: balance_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int balance_rt(struct rq *rq, struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81177ef0)
Location: kernel/sched/rt.c:1642
Inline: False
```
**Symbols:**

```
ffffffff81177ef0-ffffffff81177ff0: balance_rt (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int balance_rt(struct rq *rq, struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffff800010151360)
Location: kernel/sched/rt.c:1472
Inline: True
```
**Symbols:**

```
ffff800010151360-ffff800010151418: balance_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int balance_rt(struct rq *rq, struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c039c5b8)
Location: kernel/sched/rt.c:1472
Inline: True
```
**Symbols:**

```
c039c5b8-c039c65c: balance_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int balance_rt(struct rq *rq, struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c0000000001a2210)
Location: kernel/sched/rt.c:1472
Inline: True
```
**Symbols:**

```
c0000000001a2210-c0000000001a22e8: balance_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int balance_rt(struct rq *rq, struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffe0000f966c)
Location: kernel/sched/rt.c:1472
Inline: True
```
**Symbols:**

```
ffffffe0000f966c-ffffffe0000f9712: balance_rt (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int balance_rt(struct rq *rq, struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e96c0)
Location: kernel/sched/rt.c:1472
Inline: True
```
**Symbols:**

```
ffffffff810e96c0-ffffffff810e9746: balance_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int balance_rt(struct rq *rq, struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810d9190)
Location: kernel/sched/rt.c:1472
Inline: True
```
**Symbols:**

```
ffffffff810d9190-ffffffff810d9216: balance_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int balance_rt(struct rq *rq, struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e6300)
Location: kernel/sched/rt.c:1472
Inline: True
```
**Symbols:**

```
ffffffff810e6300-ffffffff810e6386: balance_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int balance_rt(struct rq *rq, struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f0020)
Location: kernel/sched/rt.c:1472
Inline: True
```
**Symbols:**

```
ffffffff810f0020-ffffffff810f00a6: balance_rt (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
