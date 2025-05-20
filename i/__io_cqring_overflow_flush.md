# Function: <code>__io_cqring_overflow_flush</code>

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
bool __io_cqring_overflow_flush(struct io_ring_ctx *ctx, bool force, struct task_struct *tsk, struct files_struct *files);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81391c80)
Location: fs/io_uring.c:1767
Inline: False
Direct callers:
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_iopoll_check
```
**Symbols:**

```
ffffffff81391c80-ffffffff81391f37: __io_cqring_overflow_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool __io_cqring_overflow_flush(struct io_ring_ctx *ctx, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81395360)
Location: fs/io_uring.c:1452
Inline: False
Direct callers:
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff81395360-ffffffff8139555e: __io_cqring_overflow_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool __io_cqring_overflow_flush(struct io_ring_ctx *ctx, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e4ee0)
Location: fs/io_uring.c:1672
Inline: False
Direct callers:
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff813e4ee0-ffffffff813e50ea: __io_cqring_overflow_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool __io_cqring_overflow_flush(struct io_ring_ctx *ctx, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816cf3d0)
Location: io_uring/io_uring.c:2096
Inline: False
Direct callers:
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:io_ring_ctx_wait_and_kill
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff816cf3d0-ffffffff816cf644: __io_cqring_overflow_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __io_cqring_overflow_flush(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8178e450)
Location: io_uring/io_uring.c:649
Inline: False
Direct callers:
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_iopoll_check
```
**Symbols:**

```
ffffffff8178e450-ffffffff8178e5f8: __io_cqring_overflow_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __io_cqring_overflow_flush(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817ced90)
Location: io_uring/io_uring.c:683
Inline: False
Direct callers:
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_iopoll_check
```
**Symbols:**

```
ffffffff817ced90-ffffffff817cef37: __io_cqring_overflow_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __io_cqring_overflow_flush(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81811f30)
Location: io_uring/io_uring.c:691
Inline: False
Direct callers:
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_iopoll_check
```
**Symbols:**

```
ffffffff81811f30-ffffffff818120d8: __io_cqring_overflow_flush (STB_LOCAL)
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
<b>Param removed. </b>
<code>struct task_struct *tsk</code>
</li>
<li>
<b>Param removed. </b>
<code>struct files_struct *files</code>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool force</code>
</li>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>void</code>
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
