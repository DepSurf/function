# Function: <code>io_wq_worker_sleeping</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void io_wq_worker_sleeping(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff8138b060)
Location: fs/io-wq.c:624
Inline: False
Direct callers:
  - kernel/sched/core.c:schedule
```
**Symbols:**

```
ffffffff8138b060-ffffffff8138b0b9: io_wq_worker_sleeping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void io_wq_worker_sleeping(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff8139c2c0)
Location: fs/io-wq.c:657
Inline: False
Direct callers:
  - kernel/sched/core.c:schedule
```
**Symbols:**

```
ffffffff8139c2c0-ffffffff8139c319: io_wq_worker_sleeping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void io_wq_worker_sleeping(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff813a3410)
Location: fs/io-wq.c:631
Inline: False
Direct callers:
  - kernel/sched/core.c:schedule
```
**Symbols:**

```
ffffffff813a3410-ffffffff813a346c: io_wq_worker_sleeping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void io_wq_worker_sleeping(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff813f28f0)
Location: fs/io-wq.c:686
Inline: False
Direct callers:
  - kernel/sched/core.c:schedule
```
**Symbols:**

```
ffffffff813f28f0-ffffffff813f2941: io_wq_worker_sleeping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void io_wq_worker_sleeping(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff816db480)
Location: io_uring/io-wq.c:699
Inline: False
Direct callers:
  - kernel/sched/core.c:schedule
```
**Symbols:**

```
ffffffff816db480-ffffffff816db4c4: io_wq_worker_sleeping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void io_wq_worker_sleeping(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff817a7540)
Location: io_uring/io-wq.c:686
Inline: False
Direct callers:
  - kernel/sched/core.c:schedule
```
**Symbols:**

```
ffffffff817a7540-ffffffff817a7584: io_wq_worker_sleeping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void io_wq_worker_sleeping(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff817e7b10)
Location: io_uring/io-wq.c:686
Inline: False
Direct callers:
  - kernel/sched/core.c:schedule
```
**Symbols:**

```
ffffffff817e7b10-ffffffff817e7b53: io_wq_worker_sleeping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void io_wq_worker_sleeping(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff8182d920)
Location: io_uring/io-wq.c:710
Inline: False
Direct callers:
  - kernel/sched/core.c:rt_mutex_pre_schedule
  - kernel/sched/core.c:schedule
```
**Symbols:**

```
ffffffff8182d920-ffffffff8182d963: io_wq_worker_sleeping (STB_GLOBAL)
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
