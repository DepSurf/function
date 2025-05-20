# Function: <code>io_queue_worker_create</code>

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
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff813a26a6)
Location: fs/io-wq.c:311
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool io_queue_worker_create(struct io_worker *worker, struct io_wqe_acct *acct, task_work_func_t func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff813f18a0)
Location: fs/io-wq.c:339
Inline: False
Direct callers:
  - fs/io-wq.c:io_workqueue_create
  - fs/io-wq.c:io_wqe_dec_running
```
**Symbols:**

```
ffffffff813f18a0-ffffffff813f19ec: io_queue_worker_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool io_queue_worker_create(struct io_worker *worker, struct io_wqe_acct *acct, task_work_func_t func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff816da250)
Location: io_uring/io-wq.c:346
Inline: False
Direct callers:
  - io_uring/io-wq.c:io_workqueue_create
  - io_uring/io-wq.c:io_wqe_dec_running
```
**Symbols:**

```
ffffffff816da250-ffffffff816da3aa: io_queue_worker_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool io_queue_worker_create(struct io_worker *worker, struct io_wqe_acct *acct, task_work_func_t func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff817a6300)
Location: io_uring/io-wq.c:348
Inline: False
Direct callers:
  - io_uring/io-wq.c:io_workqueue_create
  - io_uring/io-wq.c:io_wqe_dec_running
```
**Symbols:**

```
ffffffff817a6300-ffffffff817a6474: io_queue_worker_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool io_queue_worker_create(struct io_worker *worker, struct io_wq_acct *acct, task_work_func_t func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff817e7270)
Location: io_uring/io-wq.c:351
Inline: False
Direct callers:
  - io_uring/io-wq.c:io_workqueue_create
  - io_uring/io-wq.c:io_wq_dec_running
```
**Symbols:**

```
ffffffff817e7270-ffffffff817e73d5: io_queue_worker_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool io_queue_worker_create(struct io_worker *worker, struct io_wq_acct *acct, task_work_func_t func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff8182d030)
Location: io_uring/io-wq.c:362
Inline: False
Direct callers:
  - io_uring/io-wq.c:io_workqueue_create
  - io_uring/io-wq.c:io_wq_dec_running
```
**Symbols:**

```
ffffffff8182d030-ffffffff8182d195: io_queue_worker_create (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct io_wqe_acct *acct</code> ➡️ <code>struct io_wq_acct *acct</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
