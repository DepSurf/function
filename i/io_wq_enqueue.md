# Function: <code>io_wq_enqueue</code>

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
void io_wq_enqueue(struct io_wq *wq, struct io_wq_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff8138b0c0)
Location: fs/io-wq.c:838
Inline: False
Direct callers:
  - fs/io_uring.c:io_queue_async_work
```
**Symbols:**

```
ffffffff8138b0c0-ffffffff8138b0e0: io_wq_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void io_wq_enqueue(struct io_wq *wq, struct io_wq_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff8139c320)
Location: fs/io-wq.c:905
Inline: False
Direct callers:
  - fs/io_uring.c:__io_queue_async_work
```
**Symbols:**

```
ffffffff8139c320-ffffffff8139c340: io_wq_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void io_wq_enqueue(struct io_wq *wq, struct io_wq_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff813a3470)
Location: fs/io-wq.c:791
Inline: False
Direct callers:
  - fs/io_uring.c:io_queue_async_work
```
**Symbols:**

```
ffffffff813a3470-ffffffff813a3490: io_wq_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void io_wq_enqueue(struct io_wq *wq, struct io_wq_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff813f2950)
Location: fs/io-wq.c:954
Inline: False
Direct callers:
  - fs/io_uring.c:io_queue_async_work
```
**Symbols:**

```
ffffffff813f2950-ffffffff813f296e: io_wq_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void io_wq_enqueue(struct io_wq *wq, struct io_wq_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff816db4d0)
Location: io_uring/io-wq.c:969
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_queue_iowq
```
**Symbols:**

```
ffffffff816db4d0-ffffffff816db4f8: io_wq_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void io_wq_enqueue(struct io_wq *wq, struct io_wq_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff817a75a0)
Location: io_uring/io-wq.c:956
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_queue_iowq
```
**Symbols:**

```
ffffffff817a75a0-ffffffff817a75c8: io_wq_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void io_wq_enqueue(struct io_wq *wq, struct io_wq_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io-wq.c (0)
Location: io_uring/io-wq.c:900
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_queue_iowq
  - io_uring/io-wq.c:io_worker_handle_work
  - io_uring/io-wq.c:io_worker_handle_work
```
**Symbols:**

```
ffffffff820f7be5-ffffffff820f7c02: io_wq_enqueue.cold (STB_LOCAL)
ffffffff817e7b70-ffffffff817e7f18: io_wq_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void io_wq_enqueue(struct io_wq *wq, struct io_wq_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io-wq.c (0)
Location: io_uring/io-wq.c:924
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_queue_iowq
  - io_uring/io-wq.c:io_worker_handle_work
  - io_uring/io-wq.c:io_worker_handle_work
```
**Symbols:**

```
ffffffff821d55bd-ffffffff821d55d2: io_wq_enqueue.cold (STB_LOCAL)
ffffffff8182d980-ffffffff8182dcf1: io_wq_enqueue (STB_GLOBAL)
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
