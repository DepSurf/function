# Function: <code>__io_fill_cqe_req</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (ffffffff816ce370)
Location: io_uring/io_uring.c:2244
Inline: True
Direct callers:
  - io_uring/io_uring.c:io_poll_task_func
  - io_uring/io_uring.c:io_do_iopoll
  - io_uring/io_uring.c:__io_submit_flush_completions
  - io_uring/io_uring.c:handle_prev_tw_list
  - io_uring/io_uring.c:io_fail_links
  - io_uring/io_uring.c:io_req_complete_post
```
**Symbols:**

```
ffffffff816ce370-ffffffff816ce615: __io_fill_cqe_req.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate ⚠️</summary>

```c
bool __io_fill_cqe_req(struct io_ring_ctx *ctx, struct io_kiocb *req);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8178d560)
Location: io_uring/io_uring.h:129
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_submit_flush_completions
  - io_uring/io_uring.c:__io_req_complete_post
```
```
In io_uring/rw.c (ffffffff817a3740)
Location: io_uring/io_uring.h:129
Inline: False
Direct callers:
  - io_uring/rw.c:io_do_iopoll
```
**Symbols:**

```
ffffffff8178d560-ffffffff8178d6c4: __io_fill_cqe_req (STB_LOCAL)
ffffffff817a3740-ffffffff817a38a4: __io_fill_cqe_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate ⚠️</summary>

```c
bool __io_fill_cqe_req(struct io_ring_ctx *ctx, struct io_kiocb *req);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817ce940)
Location: io_uring/io_uring.h:136
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_submit_flush_completions
  - io_uring/io_uring.c:__io_req_complete_post
```
```
In io_uring/rw.c (ffffffff817e4770)
Location: io_uring/io_uring.h:136
Inline: False
Direct callers:
  - io_uring/rw.c:io_do_iopoll
```
**Symbols:**

```
ffffffff817ce940-ffffffff817ceaa4: __io_fill_cqe_req (STB_LOCAL)
ffffffff817e4770-ffffffff817e48d4: __io_fill_cqe_req (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
