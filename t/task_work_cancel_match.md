# Function: <code>task_work_cancel_match</code>

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
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct callback_head *task_work_cancel_match(struct task_struct *task, bool (*match)(struct callback_head *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/task_work.c (ffffffff810cab75)
Location: kernel/task_work.c:74
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_cancel
Direct callers:
  - fs/io-wq.c:io_wq_exit_workers
```
**Symbols:**

```
ffffffff810caac0-ffffffff810cab63: task_work_cancel_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct callback_head *task_work_cancel_match(struct task_struct *task, bool (*match)(struct callback_head *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/task_work.c (ffffffff810ddcf5)
Location: kernel/task_work.c:74
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_cancel
Direct callers:
  - fs/io-wq.c:io_wq_put_and_exit
  - fs/io-wq.c:io_wqe_worker
  - fs/io-wq.c:io_queue_worker_create
```
**Symbols:**

```
ffffffff810ddc40-ffffffff810ddce3: task_work_cancel_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct callback_head *task_work_cancel_match(struct task_struct *task, bool (*match)(struct callback_head *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/task_work.c (ffffffff810f7875)
Location: kernel/task_work.c:87
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_cancel
Direct callers:
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wqe_worker
  - io_uring/io-wq.c:io_queue_worker_create
```
**Symbols:**

```
ffffffff810f77b0-ffffffff810f7861: task_work_cancel_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct callback_head *task_work_cancel_match(struct task_struct *task, bool (*match)(struct callback_head *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/task_work.c (ffffffff8111a045)
Location: kernel/task_work.c:87
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_cancel
Direct callers:
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wqe_worker
  - io_uring/io-wq.c:io_queue_worker_create
```
**Symbols:**

```
ffffffff81119f70-ffffffff8111a022: task_work_cancel_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct callback_head *task_work_cancel_match(struct task_struct *task, bool (*match)(struct callback_head *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/task_work.c (ffffffff811272b5)
Location: kernel/task_work.c:87
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_cancel
Direct callers:
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wq_worker
  - io_uring/io-wq.c:io_queue_worker_create
```
**Symbols:**

```
ffffffff811271e0-ffffffff81127292: task_work_cancel_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct callback_head *task_work_cancel_match(struct task_struct *task, bool (*match)(struct callback_head *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/task_work.c (ffffffff81131895)
Location: kernel/task_work.c:88
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_cancel
Direct callers:
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wq_worker
  - io_uring/io-wq.c:io_queue_worker_create
```
**Symbols:**

```
ffffffff811317c0-ffffffff81131872: task_work_cancel_match (STB_GLOBAL)
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
