# Function: <code>io_iopoll_try_reap_events</code>

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
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (ffffffff813970d2)
Location: fs/io_uring.c:2562
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
Direct callers:
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
**Symbols:**

```
ffffffff813964e0-ffffffff813965ad: io_iopoll_try_reap_events.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (ffffffff8139a505)
Location: fs/io_uring.c:2361
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
Direct callers:
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
**Symbols:**

```
ffffffff81399950-ffffffff81399a1f: io_iopoll_try_reap_events.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (ffffffff813e9c50)
Location: fs/io_uring.c:2558
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
Direct callers:
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
**Symbols:**

```
ffffffff813e8a10-ffffffff813e8ada: io_iopoll_try_reap_events.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void io_iopoll_try_reap_events(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81e91dc3)
Location: io_uring/io_uring.c:3081
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_ring_ctx_wait_and_kill
```
**Symbols:**

```
ffffffff81e91dc3-ffffffff81e91e4f: io_iopoll_try_reap_events (STB_LOCAL)
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
In io_uring/io_uring.c (ffffffff8178f4cc)
Location: io_uring/io_uring.c:1511
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
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
In io_uring/io_uring.c (ffffffff817d0821)
Location: io_uring/io_uring.c:1591
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
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
In io_uring/io_uring.c (ffffffff81814116)
Location: io_uring/io_uring.c:1612
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
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
</ul>
