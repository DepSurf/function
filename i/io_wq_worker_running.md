# Function: <code>io_wq_worker_running</code>

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
void io_wq_worker_running(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff8138b020)
Location: fs/io-wq.c:606
Inline: False
Direct callers:
  - kernel/sched/core.c:schedule
```
**Symbols:**

```
ffffffff8138b020-ffffffff8138b05e: io_wq_worker_running (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void io_wq_worker_running(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff8139c280)
Location: fs/io-wq.c:639
Inline: False
Direct callers:
  - kernel/sched/core.c:schedule
```
**Symbols:**

```
ffffffff8139c280-ffffffff8139c2be: io_wq_worker_running (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void io_wq_worker_running(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff813a33c0)
Location: fs/io-wq.c:613
Inline: False
Direct callers:
  - kernel/sched/core.c:schedule
```
**Symbols:**

```
ffffffff813a33c0-ffffffff813a3404: io_wq_worker_running (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void io_wq_worker_running(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff813f28a0)
Location: fs/io-wq.c:668
Inline: False
Direct callers:
  - kernel/sched/core.c:schedule
```
**Symbols:**

```
ffffffff813f28a0-ffffffff813f28e5: io_wq_worker_running (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void io_wq_worker_running(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff816db410)
Location: io_uring/io-wq.c:681
Inline: False
Direct callers:
  - kernel/sched/core.c:schedule
```
**Symbols:**

```
ffffffff816db410-ffffffff816db475: io_wq_worker_running (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void io_wq_worker_running(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff817a74c0)
Location: io_uring/io-wq.c:668
Inline: False
Direct callers:
  - kernel/sched/core.c:schedule
```
**Symbols:**

```
ffffffff817a74c0-ffffffff817a7525: io_wq_worker_running (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void io_wq_worker_running(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff817e7a90)
Location: io_uring/io-wq.c:668
Inline: False
Direct callers:
  - kernel/sched/core.c:schedule
```
**Symbols:**

```
ffffffff817e7a90-ffffffff817e7af5: io_wq_worker_running (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void io_wq_worker_running(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff8182d8a0)
Location: io_uring/io-wq.c:692
Inline: False
Direct callers:
  - kernel/sched/core.c:rt_mutex_post_schedule
  - kernel/sched/core.c:schedule
```
**Symbols:**

```
ffffffff8182d8a0-ffffffff8182d905: io_wq_worker_running (STB_GLOBAL)
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
