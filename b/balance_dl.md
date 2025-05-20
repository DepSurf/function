# Function: <code>balance_dl</code>

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
<summary>In <code>5.4</code>: ✅</summary>

```c
int balance_dl(struct rq *rq, struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f2160)
Location: kernel/sched/deadline.c:1694
Inline: False
```
**Symbols:**

```
ffffffff810f2160-ffffffff810f21d6: balance_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int balance_dl(struct rq *rq, struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fd420)
Location: kernel/sched/deadline.c:1696
Inline: False
```
**Symbols:**

```
ffffffff810fd420-ffffffff810fd496: balance_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int balance_dl(struct rq *rq, struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fb9e0)
Location: kernel/sched/deadline.c:1794
Inline: False
```
**Symbols:**

```
ffffffff810fb9e0-ffffffff810fba60: balance_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int balance_dl(struct rq *rq, struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fdd00)
Location: kernel/sched/deadline.c:1773
Inline: False
```
**Symbols:**

```
ffffffff810fdd00-ffffffff810fdd80: balance_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int balance_dl(struct rq *rq, struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff81116240)
Location: kernel/sched/deadline.c:1774
Inline: False
```
**Symbols:**

```
ffffffff81116240-ffffffff811162c0: balance_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int balance_dl(struct rq *rq, struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8112fe40)
Location: kernel/sched/deadline.c:1922
Inline: False
```
**Symbols:**

```
ffffffff8112fe40-ffffffff8112ff11: balance_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int balance_dl(struct rq *rq, struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81159f10)
Location: kernel/sched/deadline.c:1929
Inline: False
```
**Symbols:**

```
ffffffff81159f10-ffffffff81159fe1: balance_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int balance_dl(struct rq *rq, struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8116a120)
Location: kernel/sched/deadline.c:1920
Inline: False
```
**Symbols:**

```
ffffffff8116a120-ffffffff8116a1f1: balance_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int balance_dl(struct rq *rq, struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff811777e0)
Location: kernel/sched/deadline.c:2002
Inline: False
```
**Symbols:**

```
ffffffff811777e0-ffffffff811778b1: balance_dl (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int balance_dl(struct rq *rq, struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffff800010153d90)
Location: kernel/sched/deadline.c:1694
Inline: False
```
**Symbols:**

```
ffff800010153d90-ffff800010153e2c: balance_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int balance_dl(struct rq *rq, struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c03a00c0)
Location: kernel/sched/deadline.c:1694
Inline: False
```
**Symbols:**

```
c03a00c0-c03a014c: balance_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int balance_dl(struct rq *rq, struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c0000000001a6c00)
Location: kernel/sched/deadline.c:1694
Inline: False
```
**Symbols:**

```
c0000000001a6c00-c0000000001a6cb4: balance_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int balance_dl(struct rq *rq, struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffe0000fba50)
Location: kernel/sched/deadline.c:1694
Inline: False
```
**Symbols:**

```
ffffffe0000fba50-ffffffe0000fbae2: balance_dl (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int balance_dl(struct rq *rq, struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810eb560)
Location: kernel/sched/deadline.c:1694
Inline: False
```
**Symbols:**

```
ffffffff810eb560-ffffffff810eb5d6: balance_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int balance_dl(struct rq *rq, struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810db580)
Location: kernel/sched/deadline.c:1694
Inline: False
```
**Symbols:**

```
ffffffff810db580-ffffffff810db5f6: balance_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int balance_dl(struct rq *rq, struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e8690)
Location: kernel/sched/deadline.c:1694
Inline: False
```
**Symbols:**

```
ffffffff810e8690-ffffffff810e8706: balance_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int balance_dl(struct rq *rq, struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f2980)
Location: kernel/sched/deadline.c:1694
Inline: False
```
**Symbols:**

```
ffffffff810f2980-ffffffff810f29f6: balance_dl (STB_LOCAL)
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
