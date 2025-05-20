# Function: <code>__io_prep_linked_timeout</code>

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
struct io_kiocb *__io_prep_linked_timeout(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813dd9b0)
Location: fs/io_uring.c:1412
Inline: False
Direct callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_wq_submit_work
  - fs/io_uring.c:io_queue_async_work
```
**Symbols:**

```
ffffffff813dd9b0-ffffffff813dda12: __io_prep_linked_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct io_kiocb *__io_prep_linked_timeout(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816d2c95)
Location: io_uring/io_uring.c:1776
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_arm_ltimeout
Direct callers:
  - io_uring/io_uring.c:io_queue_async
  - io_uring/io_uring.c:io_queue_iowq
```
**Symbols:**

```
ffffffff816c6040-ffffffff816c60c2: __io_prep_linked_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct io_kiocb *__io_prep_linked_timeout(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8178a775)
Location: io_uring/io_uring.c:376
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_arm_ltimeout
Direct callers:
  - io_uring/io_uring.c:io_queue_async
  - io_uring/io_uring.c:io_queue_iowq
```
**Symbols:**

```
ffffffff81786f10-ffffffff81786f92: __io_prep_linked_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct io_kiocb *__io_prep_linked_timeout(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817caed5)
Location: io_uring/io_uring.c:408
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_arm_ltimeout
Direct callers:
  - io_uring/io_uring.c:io_queue_async
  - io_uring/io_uring.c:io_queue_iowq
```
**Symbols:**

```
ffffffff817c7450-ffffffff817c74d2: __io_prep_linked_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct io_kiocb *__io_prep_linked_timeout(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8180f375)
Location: io_uring/io_uring.c:422
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_arm_ltimeout
Direct callers:
  - io_uring/io_uring.c:io_queue_async
  - io_uring/io_uring.c:io_queue_iowq
```
**Symbols:**

```
ffffffff8180c120-ffffffff8180c1a2: __io_prep_linked_timeout (STB_LOCAL)
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
