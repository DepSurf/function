# Function: <code>io_issue_sqe</code>

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
int io_issue_sqe(struct io_kiocb *req, const struct io_uring_sqe *sqe, bool force_nonblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81387100)
Location: fs/io_uring.c:5274
Inline: False
Direct callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_wq_submit_work
```
**Symbols:**

```
ffffffff81387100-ffffffff8138824a: io_issue_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int io_issue_sqe(struct io_kiocb *req, bool force_nonblock, struct io_comp_state *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813981a0)
Location: fs/io_uring.c:6263
Inline: False
Direct callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_wq_submit_work
```
**Symbols:**

```
ffffffff813981a0-ffffffff81398bc7: io_issue_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int io_issue_sqe(struct io_kiocb *req, unsigned int issue_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8139f0e0)
Location: fs/io_uring.c:6139
Inline: False
Direct callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_wq_submit_work
```
**Symbols:**

```
ffffffff8139f0e0-ffffffff813a034b: io_issue_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int io_issue_sqe(struct io_kiocb *req, unsigned int issue_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (0)
Location: fs/io_uring.c:6700
Inline: False
Direct callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_wq_submit_work
```
**Symbols:**

```
ffffffff813ecb40-ffffffff813ede09: io_issue_sqe (STB_LOCAL)
ffffffff81cc5cb1-ffffffff81cc5cc6: io_issue_sqe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int io_issue_sqe(struct io_kiocb *req, unsigned int issue_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:8018
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_poll_check_events
```
**Symbols:**

```
ffffffff816cda00-ffffffff816cddf7: io_issue_sqe (STB_LOCAL)
ffffffff81e90b48-ffffffff81e90b5d: io_issue_sqe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int io_issue_sqe(struct io_kiocb *req, unsigned int issue_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:1842
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_poll_issue
```
**Symbols:**

```
ffffffff81790a80-ffffffff81790e86: io_issue_sqe (STB_LOCAL)
ffffffff82077685-ffffffff8207769a: io_issue_sqe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int io_issue_sqe(struct io_kiocb *req, unsigned int issue_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:1854
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_poll_issue
```
**Symbols:**

```
ffffffff817d1f90-ffffffff817d2387: io_issue_sqe (STB_LOCAL)
ffffffff820f76ca-ffffffff820f76df: io_issue_sqe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int io_issue_sqe(struct io_kiocb *req, unsigned int issue_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:1878
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_poll_issue
```
**Symbols:**

```
ffffffff818152b0-ffffffff818156bd: io_issue_sqe (STB_LOCAL)
ffffffff821d5080-ffffffff821d5095: io_issue_sqe.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct io_comp_state *cs</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct io_uring_sqe *sqe</code>
</li>
<li>
<b>Param reordered. </b>
<code>req, sqe, force_nonblock</code> ➡️ <code>req, force_nonblock, cs</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int issue_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>bool force_nonblock</code>
</li>
<li>
<b>Param removed. </b>
<code>struct io_comp_state *cs</code>
</li>
</ul>
</details>
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
