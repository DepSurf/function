# Function: <code>io_queue_linked_timeout</code>

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
void io_queue_linked_timeout(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81381cf0)
Location: fs/io_uring.c:5695
Inline: False
Direct callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_wq_submit_work
  - fs/io_uring.c:io_queue_async_work
```
**Symbols:**

```
ffffffff81381cf0-ffffffff81381d8e: io_queue_linked_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void io_queue_linked_timeout(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81391be0)
Location: fs/io_uring.c:6539
Inline: False
Direct callers:
  - fs/io_uring.c:io_queue_sqe
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_wq_submit_work
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_iopoll_queue
```
**Symbols:**

```
ffffffff81391be0-ffffffff81391c71: io_queue_linked_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void io_queue_linked_timeout(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81397010)
Location: fs/io_uring.c:6414
Inline: False
Direct callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_wq_submit_work
  - fs/io_uring.c:io_queue_async_work
```
**Symbols:**

```
ffffffff81397010-ffffffff813970df: io_queue_linked_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void io_queue_linked_timeout(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e93d0)
Location: fs/io_uring.c:6994
Inline: False
Direct callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_wq_submit_work
  - fs/io_uring.c:io_queue_async_work
```
**Symbols:**

```
ffffffff813e93d0-ffffffff813e94d6: io_queue_linked_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void io_queue_linked_timeout(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816d2a70)
Location: io_uring/io_uring.c:8231
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_queue_async
  - io_uring/io_uring.c:io_queue_iowq
  - io_uring/io_uring.c:__io_arm_ltimeout
  - io_uring/io_uring.c:__io_arm_ltimeout
```
**Symbols:**

```
ffffffff816d2a70-ffffffff816d2b50: io_queue_linked_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void io_queue_linked_timeout(struct io_kiocb *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/timeout.c (ffffffff81799d80)
Location: io_uring/timeout.c:577
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_queue_async
  - io_uring/io_uring.c:io_queue_iowq
  - io_uring/io_uring.c:__io_arm_ltimeout
  - io_uring/io_uring.c:__io_arm_ltimeout
```
**Symbols:**

```
ffffffff81799d80-ffffffff81799e68: io_queue_linked_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void io_queue_linked_timeout(struct io_kiocb *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/timeout.c (ffffffff817dae50)
Location: io_uring/timeout.c:628
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_queue_async
  - io_uring/io_uring.c:io_queue_iowq
  - io_uring/io_uring.c:__io_arm_ltimeout
  - io_uring/io_uring.c:__io_arm_ltimeout
```
**Symbols:**

```
ffffffff817dae50-ffffffff817daf38: io_queue_linked_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void io_queue_linked_timeout(struct io_kiocb *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/timeout.c (ffffffff8181f140)
Location: io_uring/timeout.c:622
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_queue_async
  - io_uring/io_uring.c:io_queue_iowq
  - io_uring/io_uring.c:__io_arm_ltimeout
  - io_uring/io_uring.c:__io_arm_ltimeout
```
**Symbols:**

```
ffffffff8181f140-ffffffff8181f228: io_queue_linked_timeout (STB_GLOBAL)
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
