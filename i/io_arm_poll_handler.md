# Function: <code>io_arm_poll_handler</code>

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
bool io_arm_poll_handler(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81386e00)
Location: fs/io_uring.c:4521
Inline: False
Direct callers:
  - fs/io_uring.c:__io_queue_sqe
```
**Symbols:**

```
ffffffff81386e00-ffffffff813870f8: io_arm_poll_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool io_arm_poll_handler(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81390370)
Location: fs/io_uring.c:5452
Inline: False
Direct callers:
  - fs/io_uring.c:__io_queue_sqe
```
**Symbols:**

```
ffffffff81390370-ffffffff8139055c: io_arm_poll_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool io_arm_poll_handler(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8139d400)
Location: fs/io_uring.c:5182
Inline: False
Direct callers:
  - fs/io_uring.c:__io_queue_sqe
```
**Symbols:**

```
ffffffff8139d400-ffffffff8139d661: io_arm_poll_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int io_arm_poll_handler(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813ec160)
Location: fs/io_uring.c:5660
Inline: False
Direct callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:__io_queue_sqe
```
**Symbols:**

```
ffffffff813ec160-ffffffff813ec365: io_arm_poll_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int io_arm_poll_handler(struct io_kiocb *req, unsigned int issue_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816cee00)
Location: io_uring/io_uring.c:6983
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_queue_async
  - io_uring/io_uring.c:io_queue_async
  - io_uring/io_uring.c:io_wq_submit_work
```
**Symbols:**

```
ffffffff816cee00-ffffffff816cf071: io_arm_poll_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int io_arm_poll_handler(struct io_kiocb *req, unsigned int issue_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/poll.c (ffffffff8179d8f0)
Location: io_uring/poll.c:691
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_queue_async
  - io_uring/io_uring.c:io_queue_async
  - io_uring/io_uring.c:io_wq_submit_work
```
**Symbols:**

```
ffffffff8179d8f0-ffffffff8179dbcb: io_arm_poll_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int io_arm_poll_handler(struct io_kiocb *req, unsigned int issue_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/poll.c (ffffffff817deb10)
Location: io_uring/poll.c:693
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_queue_async
  - io_uring/io_uring.c:io_queue_async
  - io_uring/io_uring.c:io_wq_submit_work
```
**Symbols:**

```
ffffffff817deb10-ffffffff817dedcd: io_arm_poll_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int io_arm_poll_handler(struct io_kiocb *req, unsigned int issue_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/poll.c (ffffffff81822eb0)
Location: io_uring/poll.c:714
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_queue_async
  - io_uring/io_uring.c:io_queue_async
  - io_uring/io_uring.c:io_wq_submit_work
```
**Symbols:**

```
ffffffff81822eb0-ffffffff818231a4: io_arm_poll_handler (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int issue_flags</code>
</li>
</ul>
</details>
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
