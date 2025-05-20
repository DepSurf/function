# Function: <code>io_prep_async_link</code>

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
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81399317)
Location: fs/io_uring.c:1566
Inline: True
Inline callers:
  - fs/io_uring.c:io_queue_sqe
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_iopoll_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void io_prep_async_link(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813991a0)
Location: fs/io_uring.c:1258
Inline: True
Direct callers:
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_queue_async_work
```
**Symbols:**

```
ffffffff813991a0-ffffffff8139920c: io_prep_async_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void io_prep_async_link(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e44a0)
Location: fs/io_uring.c:1465
Inline: True
Direct callers:
  - fs/io_uring.c:io_drain_req
  - fs/io_uring.c:io_queue_async_work
```
**Symbols:**

```
ffffffff813e44a0-ffffffff813e450c: io_prep_async_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void io_prep_async_link(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816cb550)
Location: io_uring/io_uring.c:1833
Inline: True
Direct callers:
  - io_uring/io_uring.c:io_drain_req
  - io_uring/io_uring.c:io_queue_iowq
```
**Symbols:**

```
ffffffff816cb550-ffffffff816cb5c9: io_prep_async_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void io_prep_async_link(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81790230)
Location: io_uring/io_uring.c:436
Inline: True
Direct callers:
  - io_uring/io_uring.c:io_drain_req
  - io_uring/io_uring.c:io_queue_iowq
```
**Symbols:**

```
ffffffff81790230-ffffffff817902a9: io_prep_async_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void io_prep_async_link(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817cba30)
Location: io_uring/io_uring.c:474
Inline: True
Direct callers:
  - io_uring/io_uring.c:io_drain_req
  - io_uring/io_uring.c:io_queue_iowq
```
**Symbols:**

```
ffffffff817cba30-ffffffff817cbaa9: io_prep_async_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void io_prep_async_link(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8180ff20)
Location: io_uring/io_uring.c:488
Inline: True
Direct callers:
  - io_uring/io_uring.c:io_drain_req
  - io_uring/io_uring.c:io_queue_iowq
```
**Symbols:**

```
ffffffff8180ff20-ffffffff8180ff99: io_prep_async_link (STB_LOCAL)
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
