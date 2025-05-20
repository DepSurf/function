# Function: <code>io_cqring_fill_event</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132e8e6)
Location: fs/io_uring.c:497
Inline: True
Inline callers:
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_cqring_add_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void io_cqring_fill_event(struct io_ring_ctx *ctx, u64 ki_user_data, long int res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813405d0)
Location: fs/io_uring.c:568
Inline: True
Direct callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_cqring_add_event
```
**Symbols:**

```
ffffffff813405d0-ffffffff81340648: io_cqring_fill_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81382537)
Location: fs/io_uring.c:1327
Inline: True
Inline callers:
  - fs/io_uring.c:io_async_find_and_cancel
  - fs/io_uring.c:io_timeout_remove
  - fs/io_uring.c:__io_timeout_cancel
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_poll_add
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_async_task_func
  - fs/io_uring.c:__io_fail_links
  - fs/io_uring.c:__io_fail_links
  - fs/io_uring.c:io_req_link_next
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81398b27)
Location: fs/io_uring.c:1884
Inline: True
Inline callers:
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_async_find_and_cancel
  - fs/io_uring.c:io_timeout_remove
  - fs/io_uring.c:io_timeout_cancel
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_poll_task_func
  - fs/io_uring.c:__io_req_task_cancel
  - fs/io_uring.c:io_fail_links
  - fs/io_uring.c:io_kill_linked_timeout
  - fs/io_uring.c:io_flush_timeouts
  - fs/io_uring.c:io_kill_timeouts
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool io_cqring_fill_event(struct io_ring_ctx *ctx, u64 user_data, long int res, unsigned int cflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813936d0)
Location: fs/io_uring.c:1600
Inline: False
Direct callers:
  - fs/io_uring.c:io_kill_timeouts
  - fs/io_uring.c:io_rsrc_put_work
  - fs/io_uring.c:io_rsrc_put_work
  - fs/io_uring.c:io_link_timeout_fn
  - fs/io_uring.c:io_link_timeout_fn
  - fs/io_uring.c:io_async_cancel
  - fs/io_uring.c:io_timeout_cancel
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_poll_complete
  - fs/io_uring.c:io_poll_complete
  - fs/io_uring.c:io_disarm_next
  - fs/io_uring.c:io_fail_links
  - fs/io_uring.c:io_commit_cqring
```
**Symbols:**

```
ffffffff813936d0-ffffffff813937a2: io_cqring_fill_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool io_cqring_fill_event(struct io_ring_ctx *ctx, u64 user_data, long int res, unsigned int cflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e0f10)
Location: fs/io_uring.c:1826
Inline: False
Direct callers:
  - fs/io_uring.c:io_kill_timeouts
  - fs/io_uring.c:io_rsrc_put_work
  - fs/io_uring.c:io_timeout_cancel
  - fs/io_uring.c:__io_poll_complete
  - fs/io_uring.c:__io_poll_complete
  - fs/io_uring.c:io_disarm_next
  - fs/io_uring.c:io_disarm_next
  - fs/io_uring.c:io_fail_links
  - fs/io_uring.c:__io_commit_cqring_flush
```
**Symbols:**

```
ffffffff813e0f10-ffffffff813e0fde: io_cqring_fill_event (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void io_cqring_fill_event(struct io_ring_ctx *ctx, u64 ki_user_data, long int res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffff8000104012a0)
Location: fs/io_uring.c:568
Inline: True
Direct callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_cqring_add_event
```
**Symbols:**

```
ffff8000104012a0-ffff800010401358: io_cqring_fill_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void io_cqring_fill_event(struct io_ring_ctx *ctx, u64 ki_user_data, long int res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c05d28b4)
Location: fs/io_uring.c:568
Inline: True
Direct callers:
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_poll_complete
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_cqring_add_event
```
**Symbols:**

```
c05d28b4-c05d2954: io_cqring_fill_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void io_cqring_fill_event(struct io_ring_ctx *ctx, u64 ki_user_data, long int res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c000000000509d70)
Location: fs/io_uring.c:568
Inline: True
Direct callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_cqring_add_event
```
**Symbols:**

```
c000000000509d70-c000000000509df8: io_cqring_fill_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void io_cqring_fill_event(struct io_ring_ctx *ctx, u64 ki_user_data, long int res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffe0002acc96)
Location: fs/io_uring.c:568
Inline: True
Direct callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_cqring_add_event
```
**Symbols:**

```
ffffffe0002acc96-ffffffe0002acd24: io_cqring_fill_event (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void io_cqring_fill_event(struct io_ring_ctx *ctx, u64 ki_user_data, long int res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81338bb0)
Location: fs/io_uring.c:568
Inline: True
Direct callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_cqring_add_event
```
**Symbols:**

```
ffffffff81338bb0-ffffffff81338c28: io_cqring_fill_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void io_cqring_fill_event(struct io_ring_ctx *ctx, u64 ki_user_data, long int res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813298e0)
Location: fs/io_uring.c:568
Inline: True
Direct callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_cqring_add_event
```
**Symbols:**

```
ffffffff813298e0-ffffffff81329958: io_cqring_fill_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void io_cqring_fill_event(struct io_ring_ctx *ctx, u64 ki_user_data, long int res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81336680)
Location: fs/io_uring.c:568
Inline: True
Direct callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_cqring_add_event
```
**Symbols:**

```
ffffffff81336680-ffffffff813366f8: io_cqring_fill_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void io_cqring_fill_event(struct io_ring_ctx *ctx, u64 ki_user_data, long int res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81349750)
Location: fs/io_uring.c:568
Inline: True
Direct callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_cqring_add_event
```
**Symbols:**

```
ffffffff81349750-ffffffff813497c8: io_cqring_fill_event (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
