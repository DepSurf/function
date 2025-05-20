# Function: <code>pick_next_task_dl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct task_struct *pick_next_task_dl(struct rq *rq, struct task_struct *prev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810c2d90)
Location: kernel/sched/deadline.c:1155
Inline: False
```
**Symbols:**

```
ffffffff810c2d90-ffffffff810c2edc: pick_next_task_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct task_struct *pick_next_task_dl(struct rq *rq, struct task_struct *prev, struct pin_cookie cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810c6720)
Location: kernel/sched/deadline.c:1132
Inline: False
```
**Symbols:**

```
ffffffff810c6720-ffffffff810c6867: pick_next_task_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct task_struct *pick_next_task_dl(struct rq *rq, struct task_struct *prev, struct pin_cookie cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810cc710)
Location: kernel/sched/deadline.c:1121
Inline: False
```
**Symbols:**

```
ffffffff810cc710-ffffffff810cc857: pick_next_task_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct task_struct *pick_next_task_dl(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810c80b0)
Location: kernel/sched/deadline.c:1659
Inline: False
```
**Symbols:**

```
ffffffff810c80b0-ffffffff810c826f: pick_next_task_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct task_struct *pick_next_task_dl(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810cf890)
Location: kernel/sched/deadline.c:1652
Inline: False
```
**Symbols:**

```
ffffffff810cf890-ffffffff810cfa55: pick_next_task_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct task_struct *pick_next_task_dl(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810d7450)
Location: kernel/sched/deadline.c:1711
Inline: False
```
**Symbols:**

```
ffffffff810d7450-ffffffff810d75fb: pick_next_task_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct task_struct *pick_next_task_dl(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e1a10)
Location: kernel/sched/deadline.c:1718
Inline: False
```
**Symbols:**

```
ffffffff810e1a10-ffffffff810e1c1c: pick_next_task_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct task_struct *pick_next_task_dl(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e84f0)
Location: kernel/sched/deadline.c:1717
Inline: False
```
**Symbols:**

```
ffffffff810e84f0-ffffffff810e86fd: pick_next_task_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *pick_next_task_dl(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f1820)
Location: kernel/sched/deadline.c:1777
Inline: True
```
**Symbols:**

```
ffffffff810f1820-ffffffff810f1871: pick_next_task_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *pick_next_task_dl(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810faa90)
Location: kernel/sched/deadline.c:1778
Inline: True
```
**Symbols:**

```
ffffffff810faa90-ffffffff810faadc: pick_next_task_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *pick_next_task_dl(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f8f50)
Location: kernel/sched/deadline.c:1876
Inline: True
```
**Symbols:**

```
ffffffff810f8f50-ffffffff810f8f9c: pick_next_task_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *pick_next_task_dl(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810faf00)
Location: kernel/sched/deadline.c:1855
Inline: True
```
**Symbols:**

```
ffffffff810faf00-ffffffff810faf4c: pick_next_task_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct task_struct *pick_next_task_dl(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff81116b30)
Location: kernel/sched/deadline.c:1872
Inline: False
```
**Symbols:**

```
ffffffff81116b30-ffffffff81116b80: pick_next_task_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct task_struct *pick_next_task_dl(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff811391c0)
Location: kernel/sched/deadline.c:2024
Inline: False
```
**Symbols:**

```
ffffffff811391c0-ffffffff81139222: pick_next_task_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct task_struct *pick_next_task_dl(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81163880)
Location: kernel/sched/deadline.c:2031
Inline: False
```
**Symbols:**

```
ffffffff81163880-ffffffff811638eb: pick_next_task_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct task_struct *pick_next_task_dl(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81174060)
Location: kernel/sched/deadline.c:2022
Inline: False
```
**Symbols:**

```
ffffffff81174060-ffffffff811740cb: pick_next_task_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct task_struct *pick_next_task_dl(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81181910)
Location: kernel/sched/deadline.c:2114
Inline: False
```
**Symbols:**

```
ffffffff81181910-ffffffff8118198c: pick_next_task_dl (STB_LOCAL)
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
struct task_struct *pick_next_task_dl(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffff8000101540c8)
Location: kernel/sched/deadline.c:1777
Inline: True
```
**Symbols:**

```
ffff8000101540c8-ffff800010154150: pick_next_task_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *pick_next_task_dl(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c03a08e8)
Location: kernel/sched/deadline.c:1777
Inline: True
```
**Symbols:**

```
c03a08e8-c03a0974: pick_next_task_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct task_struct *pick_next_task_dl(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c0000000001a77f0)
Location: kernel/sched/deadline.c:1777
Inline: False
```
**Symbols:**

```
c0000000001a77f0-c0000000001a7888: pick_next_task_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *pick_next_task_dl(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffe0000fbbfe)
Location: kernel/sched/deadline.c:1777
Inline: True
```
**Symbols:**

```
ffffffe0000fbbfe-ffffffe0000fbc6c: pick_next_task_dl (STB_LOCAL)
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
struct task_struct *pick_next_task_dl(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810eac20)
Location: kernel/sched/deadline.c:1777
Inline: True
```
**Symbols:**

```
ffffffff810eac20-ffffffff810eac71: pick_next_task_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *pick_next_task_dl(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810dac40)
Location: kernel/sched/deadline.c:1777
Inline: True
```
**Symbols:**

```
ffffffff810dac40-ffffffff810dac91: pick_next_task_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *pick_next_task_dl(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e7d50)
Location: kernel/sched/deadline.c:1777
Inline: True
```
**Symbols:**

```
ffffffff810e7d50-ffffffff810e7da1: pick_next_task_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *pick_next_task_dl(struct rq *rq, struct task_struct *prev, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f2fc0)
Location: kernel/sched/deadline.c:1777
Inline: True
```
**Symbols:**

```
ffffffff810f2fc0-ffffffff810f3011: pick_next_task_dl (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct pin_cookie cookie</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct rq_flags *rf</code>
</li>
<li>
<b>Param removed. </b>
<code>struct pin_cookie cookie</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct task_struct *prev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct rq_flags *rf</code>
</li>
</ul>
</details>
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
