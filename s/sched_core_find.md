# Function: <code>sched_core_find</code>

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
struct task_struct *sched_core_find(struct rq *rq, long unsigned int cookie);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ee960)
Location: kernel/sched/core.c:194
Inline: True
Direct callers:
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:pick_next_task
```
**Symbols:**

```
ffffffff810ee960-ffffffff810ee9b1: sched_core_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *sched_core_find(struct rq *rq, long unsigned int cookie);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8110b1f0)
Location: kernel/sched/core.c:268
Inline: True
Direct callers:
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:pick_next_task
```
**Symbols:**

```
ffffffff8110b1f0-ffffffff8110b25f: sched_core_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *sched_core_find(struct rq *rq, long unsigned int cookie);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811315c0)
Location: kernel/sched/core.c:265
Inline: True
Direct callers:
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:pick_next_task
```
**Symbols:**

```
ffffffff811315c0-ffffffff8113162f: sched_core_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct task_struct *sched_core_find(struct rq *rq, long unsigned int cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8113d2b0)
Location: kernel/sched/core.c:299
Inline: False
Direct callers:
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:pick_next_task
```
**Symbols:**

```
ffffffff8113d2b0-ffffffff8113d352: sched_core_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct task_struct *sched_core_find(struct rq *rq, long unsigned int cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81148420)
Location: kernel/sched/core.c:300
Inline: False
Direct callers:
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:pick_next_task
```
**Symbols:**

```
ffffffff81148420-ffffffff811484c2: sched_core_find (STB_LOCAL)
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
