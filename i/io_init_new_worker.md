# Function: <code>io_init_new_worker</code>

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
<summary>In <code>5.15</code>: ✅</summary>

```c
void io_init_new_worker(struct io_wqe *wqe, struct io_worker *worker, struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff813f11e0)
Location: fs/io-wq.c:704
Inline: False
Direct callers:
  - fs/io-wq.c:create_io_worker
  - fs/io-wq.c:create_worker_cont
```
**Symbols:**

```
ffffffff813f11e0-ffffffff813f127f: io_init_new_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void io_init_new_worker(struct io_wqe *wqe, struct io_worker *worker, struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff816d95d0)
Location: io_uring/io-wq.c:714
Inline: False
Direct callers:
  - io_uring/io-wq.c:create_io_worker
  - io_uring/io-wq.c:create_worker_cont
```
**Symbols:**

```
ffffffff816d95d0-ffffffff816d9681: io_init_new_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void io_init_new_worker(struct io_wqe *wqe, struct io_worker *worker, struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff817a5480)
Location: io_uring/io-wq.c:701
Inline: False
Direct callers:
  - io_uring/io-wq.c:create_io_worker
  - io_uring/io-wq.c:create_worker_cont
```
**Symbols:**

```
ffffffff817a5480-ffffffff817a5531: io_init_new_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void io_init_new_worker(struct io_wq *wq, struct io_worker *worker, struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff817e6450)
Location: io_uring/io-wq.c:701
Inline: False
Direct callers:
  - io_uring/io-wq.c:create_io_worker
  - io_uring/io-wq.c:create_worker_cont
```
**Symbols:**

```
ffffffff817e6450-ffffffff817e6511: io_init_new_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void io_init_new_worker(struct io_wq *wq, struct io_worker *worker, struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff8182c210)
Location: io_uring/io-wq.c:725
Inline: False
Direct callers:
  - io_uring/io-wq.c:create_io_worker
  - io_uring/io-wq.c:create_worker_cont
```
**Symbols:**

```
ffffffff8182c210-ffffffff8182c2d1: io_init_new_worker (STB_LOCAL)
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
<b>Param added. </b>
<code>struct io_wq *wq</code>
</li>
<li>
<b>Param removed. </b>
<code>struct io_wqe *wqe</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
