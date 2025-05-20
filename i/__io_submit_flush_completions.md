# Function: <code>__io_submit_flush_completions</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __io_submit_flush_completions(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:2929
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:tctx_task_work
  - io_uring/io_uring.c:ctx_flush_and_put
  - io_uring/io_uring.c:io_fallback_req_func
```
**Symbols:**

```
ffffffff816d5ab0-ffffffff816d5bb4: __io_submit_flush_completions (STB_LOCAL)
ffffffff81e91a78-ffffffff81e91a8c: __io_submit_flush_completions.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __io_submit_flush_completions(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8178ede0)
Location: io_uring/io_uring.c:1451
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:__io_run_local_work
  - io_uring/io_uring.c:ctx_flush_and_put
  - io_uring/io_uring.c:io_fallback_req_func
```
**Symbols:**

```
ffffffff8178ede0-ffffffff8178efc9: __io_submit_flush_completions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __io_submit_flush_completions(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817d0100)
Location: io_uring/io_uring.c:1547
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:__io_run_local_work
  - io_uring/io_uring.c:tctx_task_work
  - io_uring/io_uring.c:ctx_flush_and_put
  - io_uring/io_uring.c:io_fallback_req_func
```
**Symbols:**

```
ffffffff817d0100-ffffffff817d02f5: __io_submit_flush_completions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __io_submit_flush_completions(struct io_ring_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81813290)
Location: io_uring/io_uring.c:1568
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:__io_run_local_work
  - io_uring/io_uring.c:tctx_task_work
  - io_uring/io_uring.c:ctx_flush_and_put
  - io_uring/io_uring.c:io_fallback_req_func
  - io_uring/rw.c:io_do_iopoll
```
**Symbols:**

```
ffffffff81813290-ffffffff81813536: __io_submit_flush_completions (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
