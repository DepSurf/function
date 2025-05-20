# Function: <code>io_req_task_complete</code>

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
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void io_req_task_complete(struct io_kiocb *req, bool *locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (0)
Location: fs/io_uring.c:2713
Inline: False
```
**Symbols:**

```
ffffffff813e9ff0-ffffffff813ea111: io_req_task_complete (STB_LOCAL)
ffffffff81cc5c39-ffffffff81cc5c4d: io_req_task_complete.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void io_req_task_complete(struct io_kiocb *req, bool *locked);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (ffffffff816d1e6a)
Location: io_uring/io_uring.c:3243
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_poll_remove
```
**Symbols:**

```
ffffffff816d0900-ffffffff816d0a71: io_req_task_complete (STB_LOCAL)
ffffffff81e91405-ffffffff81e9141a: io_req_task_complete.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void io_req_task_complete(struct io_kiocb *req, bool *locked);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (ffffffff8178e931)
Location: io_uring/io_uring.c:1601
Inline: True
Direct callers:
  - io_uring/timeout.c:io_req_task_link_timeout
  - io_uring/timeout.c:io_req_task_link_timeout
  - io_uring/timeout.c:io_req_tw_fail_links
  - io_uring/poll.c:io_poll_remove
  - io_uring/poll.c:io_poll_task_func
  - io_uring/poll.c:io_poll_task_func
  - io_uring/rw.c:io_req_rw_complete
  - io_uring/notif.c:io_notif_complete_tw_ext
```
**Symbols:**

```
ffffffff820775e3-ffffffff820775f8: io_req_task_complete.cold (STB_LOCAL)
ffffffff8178e8d0-ffffffff8178e9a2: io_req_task_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void io_req_task_complete(struct io_kiocb *req, struct io_tw_state *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (ffffffff817cf611)
Location: io_uring/io_uring.c:1684
Inline: True
Direct callers:
  - io_uring/uring_cmd.c:io_uring_cmd_done
  - io_uring/timeout.c:io_req_task_link_timeout
  - io_uring/timeout.c:io_req_task_link_timeout
  - io_uring/timeout.c:io_req_tw_fail_links
  - io_uring/timeout.c:io_timeout_complete
  - io_uring/poll.c:io_poll_remove
  - io_uring/poll.c:io_poll_task_func
  - io_uring/poll.c:io_poll_task_func
  - io_uring/rw.c:io_req_rw_complete
  - io_uring/notif.c:io_notif_complete_tw_ext
```
**Symbols:**

```
ffffffff820f7612-ffffffff820f7627: io_req_task_complete.cold (STB_LOCAL)
ffffffff817cf5b0-ffffffff817cf652: io_req_task_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void io_req_task_complete(struct io_kiocb *req, struct io_tw_state *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (ffffffff81812751)
Location: io_uring/io_uring.c:1708
Inline: True
Direct callers:
  - io_uring/uring_cmd.c:io_uring_cmd_done
  - io_uring/timeout.c:io_req_task_link_timeout
  - io_uring/timeout.c:io_req_task_link_timeout
  - io_uring/timeout.c:io_req_tw_fail_links
  - io_uring/timeout.c:io_timeout_complete
  - io_uring/poll.c:io_poll_remove
  - io_uring/poll.c:io_poll_task_func
  - io_uring/poll.c:io_poll_task_func
  - io_uring/rw.c:io_req_rw_complete
  - io_uring/notif.c:io_notif_complete_tw_ext
  - io_uring/waitid.c:io_waitid_complete
  - io_uring/futex.c:io_futexv_complete
  - io_uring/futex.c:io_futex_complete
```
**Symbols:**

```
ffffffff821d4fc8-ffffffff821d4fdd: io_req_task_complete.cold (STB_LOCAL)
ffffffff818126f0-ffffffff81812792: io_req_task_complete (STB_GLOBAL)
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
<code>struct io_tw_state *ts</code>
</li>
<li>
<b>Param removed. </b>
<code>bool *locked</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
