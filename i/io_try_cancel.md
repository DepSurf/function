# Function: <code>io_try_cancel</code>

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
int io_try_cancel(struct io_kiocb *req, struct io_cancel_data *cd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:7636
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_req_task_link_timeout
  - io_uring/io_uring.c:io_async_cancel
```
**Symbols:**

```
ffffffff816d3130-ffffffff816d32ef: io_try_cancel (STB_LOCAL)
ffffffff81e914e0-ffffffff81e914fe: io_try_cancel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int io_try_cancel(struct io_uring_task *tctx, struct io_cancel_data *cd, unsigned int issue_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/cancel.c (ffffffff8179e320)
Location: io_uring/cancel.c:81
Inline: False
Direct callers:
  - io_uring/timeout.c:io_req_task_link_timeout
  - io_uring/cancel.c:__io_async_cancel
```
**Symbols:**

```
ffffffff8179e320-ffffffff8179e402: io_try_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int io_try_cancel(struct io_uring_task *tctx, struct io_cancel_data *cd, unsigned int issue_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/cancel.c (ffffffff817df510)
Location: io_uring/cancel.c:81
Inline: False
Direct callers:
  - io_uring/timeout.c:io_req_task_link_timeout
  - io_uring/cancel.c:__io_async_cancel
```
**Symbols:**

```
ffffffff817df510-ffffffff817df5f2: io_try_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int io_try_cancel(struct io_uring_task *tctx, struct io_cancel_data *cd, unsigned int issue_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/cancel.c (ffffffff81823960)
Location: io_uring/cancel.c:104
Inline: False
Direct callers:
  - io_uring/timeout.c:io_req_task_link_timeout
  - io_uring/cancel.c:__io_async_cancel
```
**Symbols:**

```
ffffffff81823960-ffffffff81823a57: io_try_cancel (STB_GLOBAL)
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
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct io_uring_task *tctx</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int issue_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>struct io_kiocb *req</code>
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
