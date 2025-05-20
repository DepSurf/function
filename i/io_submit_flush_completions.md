# Function: <code>io_submit_flush_completions</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
void io_submit_flush_completions(struct io_comp_state *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81391280)
Location: fs/io_uring.c:1902
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_sqes
```
**Symbols:**

```
ffffffff81391280-ffffffff81391388: io_submit_flush_completions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void io_submit_flush_completions(struct io_comp_state *cs, struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81398d00)
Location: fs/io_uring.c:2150
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:tctx_task_work
  - fs/io_uring.c:tctx_task_work
```
**Symbols:**

```
ffffffff81398d00-ffffffff81398fcb: io_submit_flush_completions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void io_submit_flush_completions(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e7e50)
Location: fs/io_uring.c:2372
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_req_task_complete
  - fs/io_uring.c:tctx_task_work
  - fs/io_uring.c:ctx_flush_and_put
  - fs/io_uring.c:io_fallback_req_func
```
**Symbols:**

```
ffffffff813e7e50-ffffffff813e8179: io_submit_flush_completions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816d6259)
Location: io_uring/io_uring.c:1354
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:tctx_task_work
  - io_uring/io_uring.c:ctx_flush_and_put
  - io_uring/io_uring.c:io_fallback_req_func
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817916d3)
Location: io_uring/io_uring.c:169
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:__io_run_local_work
  - io_uring/io_uring.c:ctx_flush_and_put
  - io_uring/io_uring.c:io_fallback_req_func
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817d2960)
Location: io_uring/io_uring.c:168
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:__io_run_local_work
  - io_uring/io_uring.c:tctx_task_work
  - io_uring/io_uring.c:ctx_flush_and_put
  - io_uring/io_uring.c:io_fallback_req_func
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81814038)
Location: io_uring/io_uring.c:181
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:__io_run_local_work
  - io_uring/io_uring.c:tctx_task_work
  - io_uring/io_uring.c:ctx_flush_and_put
  - io_uring/io_uring.c:io_fallback_req_func
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
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct io_ring_ctx *ctx</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct io_comp_state *cs</code>
</li>
<li>
<b>Param reordered. </b>
<code>cs, ctx</code> ➡️ <code>ctx</code>
</li>
</ul>
</details>
</li>
</ul>
