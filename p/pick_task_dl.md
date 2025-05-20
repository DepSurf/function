# Function: <code>pick_task_dl</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *pick_task_dl(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff81116b35)
Location: kernel/sched/deadline.c:1856
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_task_dl
```
**Symbols:**

```
ffffffff811150c0-ffffffff811150ed: pick_task_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *pick_task_dl(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff811391c5)
Location: kernel/sched/deadline.c:2008
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_next_task_dl
```
**Symbols:**

```
ffffffff8112e010-ffffffff8112e054: pick_task_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *pick_task_dl(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81163885)
Location: kernel/sched/deadline.c:2015
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_next_task_dl
```
**Symbols:**

```
ffffffff81157e20-ffffffff81157e5b: pick_task_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *pick_task_dl(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81174065)
Location: kernel/sched/deadline.c:2006
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_next_task_dl
```
**Symbols:**

```
ffffffff81167f20-ffffffff81167f5b: pick_task_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct task_struct *pick_task_dl(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8117e8a0)
Location: kernel/sched/deadline.c:2085
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:pick_next_task_dl
```
**Symbols:**

```
ffffffff8117e8a0-ffffffff8117e957: pick_task_dl (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
