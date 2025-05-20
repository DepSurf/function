# Function: <code>io_worker_ref_put</code>

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
void io_worker_ref_put(struct io_wq *wq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff813a24c0)
Location: fs/io-wq.c:163
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_exit_workers
  - fs/io-wq.c:io_wq_exit_workers
  - fs/io-wq.c:create_io_worker
  - fs/io-wq.c:create_worker_cb
Direct callers:
  - fs/io-wq.c:io_wqe_worker
```
**Symbols:**

```
ffffffff813a1f40-ffffffff813a1f5b: io_worker_ref_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void io_worker_ref_put(struct io_wq *wq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff813f301c)
Location: fs/io-wq.c:173
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_put_and_exit
  - fs/io-wq.c:create_io_worker
  - fs/io-wq.c:create_worker_cont
  - fs/io-wq.c:io_queue_worker_create
  - fs/io-wq.c:io_queue_worker_create
  - fs/io-wq.c:io_queue_worker_create
  - fs/io-wq.c:create_worker_cb
  - fs/io-wq.c:io_worker_cancel_cb
Direct callers:
  - fs/io-wq.c:io_wqe_worker
```
**Symbols:**

```
ffffffff813f0d80-ffffffff813f0d9b: io_worker_ref_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void io_worker_ref_put(struct io_wq *wq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff816dbb91)
Location: io_uring/io-wq.c:176
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:create_io_worker
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:create_worker_cb
  - io_uring/io-wq.c:io_worker_cancel_cb
Direct callers:
  - io_uring/io-wq.c:io_wqe_worker
```
**Symbols:**

```
ffffffff816d9690-ffffffff816d96b7: io_worker_ref_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void io_worker_ref_put(struct io_wq *wq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff817a7c9d)
Location: io_uring/io-wq.c:178
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:create_io_worker
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:create_worker_cb
  - io_uring/io-wq.c:io_worker_cancel_cb
Direct callers:
  - io_uring/io-wq.c:io_wqe_worker
```
**Symbols:**

```
ffffffff817a5550-ffffffff817a5577: io_worker_ref_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void io_worker_ref_put(struct io_wq *wq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff817e8b5d)
Location: io_uring/io-wq.c:171
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:create_io_worker
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:create_worker_cb
  - io_uring/io-wq.c:io_worker_cancel_cb
Direct callers:
  - io_uring/io-wq.c:io_wq_worker
```
**Symbols:**

```
ffffffff817e6530-ffffffff817e6557: io_worker_ref_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void io_worker_ref_put(struct io_wq *wq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff8182e90d)
Location: io_uring/io-wq.c:171
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:create_io_worker
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:create_worker_cb
  - io_uring/io-wq.c:io_worker_cancel_cb
Direct callers:
  - io_uring/io-wq.c:io_wq_worker
```
**Symbols:**

```
ffffffff8182c2f0-ffffffff8182c317: io_worker_ref_put (STB_LOCAL)
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
