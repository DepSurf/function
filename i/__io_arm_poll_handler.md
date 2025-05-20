# Function: <code>__io_arm_poll_handler</code>

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
__poll_t __io_arm_poll_handler(struct io_kiocb *req, struct io_poll_iocb *poll, struct io_poll_table *ipt, __poll_t mask, wait_queue_func_t wake_func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8137f190)
Location: fs/io_uring.c:4481
Inline: False
Direct callers:
  - fs/io_uring.c:io_poll_add
  - fs/io_uring.c:io_arm_poll_handler
```
**Symbols:**

```
ffffffff8137f190-ffffffff8137f31c: __io_arm_poll_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
__poll_t __io_arm_poll_handler(struct io_kiocb *req, struct io_poll_iocb *poll, struct io_poll_table *ipt, __poll_t mask, wait_queue_func_t wake_func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8138d250)
Location: fs/io_uring.c:5411
Inline: False
Direct callers:
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_arm_poll_handler
```
**Symbols:**

```
ffffffff8138d250-ffffffff8138d3f7: __io_arm_poll_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
__poll_t __io_arm_poll_handler(struct io_kiocb *req, struct io_poll_iocb *poll, struct io_poll_table *ipt, __poll_t mask, wait_queue_func_t wake_func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813979b0)
Location: fs/io_uring.c:5136
Inline: False
Direct callers:
  - fs/io_uring.c:io_arm_poll_handler
```
**Symbols:**

```
ffffffff813979b0-ffffffff81397bb7: __io_arm_poll_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
__poll_t __io_arm_poll_handler(struct io_kiocb *req, struct io_poll_iocb *poll, struct io_poll_table *ipt, __poll_t mask, wait_queue_func_t wake_func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (0)
Location: fs/io_uring.c:5608
Inline: False
Direct callers:
  - fs/io_uring.c:io_arm_poll_handler
```
**Symbols:**

```
ffffffff813e45c0-ffffffff813e47e7: __io_arm_poll_handler (STB_LOCAL)
ffffffff81cc5ac3-ffffffff81cc5af4: __io_arm_poll_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __io_arm_poll_handler(struct io_kiocb *req, struct io_poll_iocb *poll, struct io_poll_table *ipt, __poll_t mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:6905
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_poll_add
  - io_uring/io_uring.c:io_arm_poll_handler
```
**Symbols:**

```
ffffffff816ce7d0-ffffffff816cea39: __io_arm_poll_handler (STB_LOCAL)
ffffffff81e90d1c-ffffffff81e90d48: __io_arm_poll_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __io_arm_poll_handler(struct io_kiocb *req, struct io_poll *poll, struct io_poll_table *ipt, __poll_t mask, unsigned int issue_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/poll.c (0)
Location: io_uring/poll.c:563
Inline: False
Direct callers:
  - io_uring/poll.c:io_poll_add
  - io_uring/poll.c:io_arm_poll_handler
```
**Symbols:**

```
ffffffff8179d350-ffffffff8179d574: __io_arm_poll_handler (STB_LOCAL)
ffffffff82077926-ffffffff8207793b: __io_arm_poll_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __io_arm_poll_handler(struct io_kiocb *req, struct io_poll *poll, struct io_poll_table *ipt, __poll_t mask, unsigned int issue_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/poll.c (0)
Location: io_uring/poll.c:565
Inline: False
Direct callers:
  - io_uring/poll.c:io_poll_add
  - io_uring/poll.c:io_arm_poll_handler
```
**Symbols:**

```
ffffffff817de580-ffffffff817de7a4: __io_arm_poll_handler (STB_LOCAL)
ffffffff820f799e-ffffffff820f79b3: __io_arm_poll_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __io_arm_poll_handler(struct io_kiocb *req, struct io_poll *poll, struct io_poll_table *ipt, __poll_t mask, unsigned int issue_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/poll.c (0)
Location: io_uring/poll.c:586
Inline: False
Direct callers:
  - io_uring/poll.c:io_poll_add
  - io_uring/poll.c:io_arm_poll_handler
```
**Symbols:**

```
ffffffff81822950-ffffffff81822b74: __io_arm_poll_handler (STB_LOCAL)
ffffffff821d5391-ffffffff821d53a6: __io_arm_poll_handler.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>wait_queue_func_t wake_func</code>
</li>
<li>
<b>Return type changed. </b>
<code>__poll_t</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int issue_flags</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct io_poll_iocb *poll</code> ➡️ <code>struct io_poll *poll</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
