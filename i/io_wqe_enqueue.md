# Function: <code>io_wqe_enqueue</code>

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
void io_wqe_enqueue(struct io_wqe *wqe, struct io_wq_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff8138a230)
Location: fs/io-wq.c:810
Inline: False
Direct callers:
  - fs/io-wq.c:io_wq_enqueue
  - fs/io-wq.c:io_worker_handle_work
  - fs/io-wq.c:io_worker_handle_work
```
**Symbols:**

```
ffffffff8138a230-ffffffff8138a342: io_wqe_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void io_wqe_enqueue(struct io_wqe *wqe, struct io_wq_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff8139b160)
Location: fs/io-wq.c:877
Inline: False
Direct callers:
  - fs/io-wq.c:io_wq_enqueue
  - fs/io-wq.c:io_worker_handle_work
  - fs/io-wq.c:io_worker_handle_work
```
**Symbols:**

```
ffffffff8139b160-ffffffff8139b29f: io_wqe_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void io_wqe_enqueue(struct io_wqe *wqe, struct io_wq_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/io-wq.c (0)
Location: fs/io-wq.c:764
Inline: False
Direct callers:
  - fs/io-wq.c:io_wq_enqueue
  - fs/io-wq.c:io_worker_handle_work
```
**Symbols:**

```
ffffffff813a29b0-ffffffff813a2b83: io_wqe_enqueue (STB_LOCAL)
ffffffff81bdccb1-ffffffff81bdccc9: io_wqe_enqueue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void io_wqe_enqueue(struct io_wqe *wqe, struct io_wq_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/io-wq.c (0)
Location: fs/io-wq.c:904
Inline: False
Direct callers:
  - fs/io-wq.c:io_wq_enqueue
  - fs/io-wq.c:io_worker_handle_work
```
**Symbols:**

```
ffffffff813f1f60-ffffffff813f2231: io_wqe_enqueue (STB_LOCAL)
ffffffff81cc5fae-ffffffff81cc5fe1: io_wqe_enqueue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void io_wqe_enqueue(struct io_wqe *wqe, struct io_wq_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io-wq.c (0)
Location: io_uring/io-wq.c:916
Inline: False
Direct callers:
  - io_uring/io-wq.c:io_wq_enqueue
  - io_uring/io-wq.c:io_worker_handle_work
  - io_uring/io-wq.c:io_worker_handle_work
```
**Symbols:**

```
ffffffff816da990-ffffffff816dacc4: io_wqe_enqueue (STB_LOCAL)
ffffffff81e92d46-ffffffff81e92d79: io_wqe_enqueue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void io_wqe_enqueue(struct io_wqe *wqe, struct io_wq_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io-wq.c (0)
Location: io_uring/io-wq.c:903
Inline: False
Direct callers:
  - io_uring/io-wq.c:io_wq_enqueue
  - io_uring/io-wq.c:io_worker_handle_work
  - io_uring/io-wq.c:io_worker_handle_work
```
**Symbols:**

```
ffffffff817a6aa0-ffffffff817a6deb: io_wqe_enqueue (STB_LOCAL)
ffffffff82077b0b-ffffffff82077b26: io_wqe_enqueue.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
