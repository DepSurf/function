# Function: <code>__io_commit_cqring_flush</code>

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
void __io_commit_cqring_flush(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e4cf0)
Location: fs/io_uring.c:1578
Inline: False
Direct callers:
  - fs/io_uring.c:io_kill_timeouts
  - fs/io_uring.c:io_rsrc_put_work
  - fs/io_uring.c:io_poll_task_func
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_submit_flush_completions
  - fs/io_uring.c:__io_req_find_next
  - fs/io_uring.c:io_req_complete_post
  - fs/io_uring.c:__io_cqring_overflow_flush
```
**Symbols:**

```
ffffffff813e4cf0-ffffffff813e4ed7: __io_commit_cqring_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __io_commit_cqring_flush(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:1955
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_rsrc_put_work
  - io_uring/io_uring.c:io_poll_task_func
  - io_uring/io_uring.c:io_poll_check_events
  - io_uring/io_uring.c:io_accept
  - io_uring/io_uring.c:io_msg_ring
  - io_uring/io_uring.c:io_do_iopoll
  - io_uring/io_uring.c:__io_submit_flush_completions
  - io_uring/io_uring.c:io_free_batch_list
  - io_uring/io_uring.c:handle_prev_tw_list
  - io_uring/io_uring.c:handle_prev_tw_list
  - io_uring/io_uring.c:io_req_complete_post
  - io_uring/io_uring.c:__io_cqring_overflow_flush
```
**Symbols:**

```
ffffffff816ca7f0-ffffffff816ca8f2: __io_commit_cqring_flush (STB_LOCAL)
ffffffff81e8fb74-ffffffff81e8fc6a: __io_commit_cqring_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __io_commit_cqring_flush(struct io_ring_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8178df90)
Location: io_uring/io_uring.c:573
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_submit_flush_completions
  - io_uring/io_uring.c:io_aux_cqe
  - io_uring/io_uring.c:io_cq_unlock_post
  - io_uring/rw.c:io_do_iopoll
```
**Symbols:**

```
ffffffff8178df90-ffffffff8178e0de: __io_commit_cqring_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __io_commit_cqring_flush(struct io_ring_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817ce490)
Location: io_uring/io_uring.c:611
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_submit_flush_completions
  - io_uring/io_uring.c:__io_submit_flush_completions
  - io_uring/io_uring.c:io_aux_cqe
  - io_uring/io_uring.c:io_aux_cqe
  - io_uring/io_uring.c:io_cq_unlock_post
  - io_uring/rw.c:io_do_iopoll
```
**Symbols:**

```
ffffffff817ce490-ffffffff817ce641: __io_commit_cqring_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __io_commit_cqring_flush(struct io_ring_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81811740)
Location: io_uring/io_uring.c:624
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_submit_flush_completions
  - io_uring/io_uring.c:io_fill_cqe_req_aux
  - io_uring/io_uring.c:io_cq_unlock_post
```
**Symbols:**

```
ffffffff81811740-ffffffff818118f0: __io_commit_cqring_flush (STB_GLOBAL)
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
