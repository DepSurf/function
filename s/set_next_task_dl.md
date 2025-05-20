# Function: <code>set_next_task_dl</code>

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
void set_next_task_dl(struct rq *rq, struct task_struct *p, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f16c0)
Location: kernel/sched/deadline.c:1746
Inline: True
```
**Symbols:**

```
ffffffff810f16c0-ffffffff810f1818: set_next_task_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void set_next_task_dl(struct rq *rq, struct task_struct *p, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fa930)
Location: kernel/sched/deadline.c:1748
Inline: True
```
**Symbols:**

```
ffffffff810fa930-ffffffff810faa88: set_next_task_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void set_next_task_dl(struct rq *rq, struct task_struct *p, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f8de0)
Location: kernel/sched/deadline.c:1846
Inline: True
```
**Symbols:**

```
ffffffff810f8de0-ffffffff810f8f48: set_next_task_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void set_next_task_dl(struct rq *rq, struct task_struct *p, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fad10)
Location: kernel/sched/deadline.c:1825
Inline: True
```
**Symbols:**

```
ffffffff810fad10-ffffffff810faefa: set_next_task_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_next_task_dl(struct rq *rq, struct task_struct *p, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/deadline.c (ffffffff811169ad)
Location: kernel/sched/deadline.c:1826
Inline: True
Direct callers:
  - kernel/sched/deadline.c:pick_next_task_dl
```
**Symbols:**

```
ffffffff811168f0-ffffffff81116b21: set_next_task_dl (STB_LOCAL)
ffffffff81ca69c2-ffffffff81ca69ec: set_next_task_dl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_next_task_dl(struct rq *rq, struct task_struct *p, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81139014)
Location: kernel/sched/deadline.c:1974
Inline: True
Direct callers:
  - kernel/sched/build_policy.c:pick_next_task_dl
```
**Symbols:**

```
ffffffff81138f30-ffffffff811391b1: set_next_task_dl (STB_LOCAL)
ffffffff81e5685a-ffffffff81e56884: set_next_task_dl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_next_task_dl(struct rq *rq, struct task_struct *p, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff811636e9)
Location: kernel/sched/deadline.c:1981
Inline: True
Direct callers:
  - kernel/sched/build_policy.c:pick_next_task_dl
```
**Symbols:**

```
ffffffff811635f0-ffffffff8116386e: set_next_task_dl (STB_LOCAL)
ffffffff82057a7a-ffffffff82057aa4: set_next_task_dl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_next_task_dl(struct rq *rq, struct task_struct *p, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81173ec8)
Location: kernel/sched/deadline.c:1972
Inline: True
Direct callers:
  - kernel/sched/build_policy.c:pick_next_task_dl
```
**Symbols:**

```
ffffffff81173dd0-ffffffff8117404d: set_next_task_dl (STB_LOCAL)
ffffffff820d62a0-ffffffff820d62ca: set_next_task_dl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_next_task_dl(struct rq *rq, struct task_struct *p, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81181793)
Location: kernel/sched/deadline.c:2054
Inline: True
Direct callers:
  - kernel/sched/build_policy.c:pick_next_task_dl
```
**Symbols:**

```
ffffffff81181730-ffffffff811818f8: set_next_task_dl (STB_LOCAL)
ffffffff821b143e-ffffffff821b1468: set_next_task_dl.cold (STB_LOCAL)
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
void set_next_task_dl(struct rq *rq, struct task_struct *p, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffff800010153f38)
Location: kernel/sched/deadline.c:1746
Inline: True
```
**Symbols:**

```
ffff800010153f38-ffff8000101540c4: set_next_task_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void set_next_task_dl(struct rq *rq, struct task_struct *p, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c03a0728)
Location: kernel/sched/deadline.c:1746
Inline: True
```
**Symbols:**

```
c03a0728-c03a08e8: set_next_task_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void set_next_task_dl(struct rq *rq, struct task_struct *p, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c0000000001a7600)
Location: kernel/sched/deadline.c:1746
Inline: True
Direct callers:
  - kernel/sched/deadline.c:pick_next_task_dl
```
**Symbols:**

```
c0000000001a7600-c0000000001a77e4: set_next_task_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void set_next_task_dl(struct rq *rq, struct task_struct *p, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffe0000fbae2)
Location: kernel/sched/deadline.c:1746
Inline: True
```
**Symbols:**

```
ffffffe0000fbae2-ffffffe0000fbbfe: set_next_task_dl (STB_LOCAL)
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
void set_next_task_dl(struct rq *rq, struct task_struct *p, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810eaac0)
Location: kernel/sched/deadline.c:1746
Inline: True
```
**Symbols:**

```
ffffffff810eaac0-ffffffff810eac18: set_next_task_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void set_next_task_dl(struct rq *rq, struct task_struct *p, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810daae0)
Location: kernel/sched/deadline.c:1746
Inline: True
```
**Symbols:**

```
ffffffff810daae0-ffffffff810dac38: set_next_task_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void set_next_task_dl(struct rq *rq, struct task_struct *p, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e7bf0)
Location: kernel/sched/deadline.c:1746
Inline: True
```
**Symbols:**

```
ffffffff810e7bf0-ffffffff810e7d48: set_next_task_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void set_next_task_dl(struct rq *rq, struct task_struct *p, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f2e60)
Location: kernel/sched/deadline.c:1746
Inline: True
```
**Symbols:**

```
ffffffff810f2e60-ffffffff810f2fb8: set_next_task_dl (STB_LOCAL)
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
