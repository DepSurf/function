# Function: <code>trace_io_uring_complete</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8137d634)
Location: include/trace/events/io_uring.h:295
Inline: True
Inline callers:
  - fs/io_uring.c:__io_cqring_fill_event
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
In fs/io_uring.c (ffffffff8139057f)
Location: include/trace/events/io_uring.h:295
Inline: True
Inline callers:
  - fs/io_uring.c:__io_cqring_fill_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813993a8)
Location: include/trace/events/io_uring.h:296
Inline: True
Inline callers:
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_submit_flush_completions
  - fs/io_uring.c:io_req_complete_post
  - fs/io_uring.c:io_cqring_fill_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e8504)
Location: include/trace/events/io_uring.h:296
Inline: True
Inline callers:
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_submit_flush_completions
  - fs/io_uring.c:io_req_complete_post
  - fs/io_uring.c:io_cqring_fill_event
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
In io_uring/io_uring.c (ffffffff816cbf43)
Location: include/trace/events/io_uring.h:340
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_fill_cqe_aux
  - io_uring/io_uring.c:io_fill_cqe_aux
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8178d744)
Location: include/trace/events/io_uring.h:326
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_fill_cqe_aux
  - io_uring/io_uring.c:io_fill_cqe_aux
  - io_uring/io_uring.c:__io_fill_cqe_req
  - io_uring/io_uring.c:__io_fill_cqe_req
```
```
In io_uring/rw.c (ffffffff817a37a7)
Location: include/trace/events/io_uring.h:326
Inline: True
Inline callers:
  - io_uring/rw.c:__io_fill_cqe_req
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817cefb3)
Location: include/trace/events/io_uring.h:326
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_fill_cqe_aux
  - io_uring/io_uring.c:io_fill_cqe_aux
  - io_uring/io_uring.c:__io_fill_cqe_req
  - io_uring/io_uring.c:__io_fill_cqe_req
```
```
In io_uring/rw.c (ffffffff817e47d6)
Location: include/trace/events/io_uring.h:326
Inline: True
Inline callers:
  - io_uring/rw.c:__io_fill_cqe_req
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
In io_uring/io_uring.c (ffffffff818133ff)
Location: include/trace/events/io_uring.h:326
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_submit_flush_completions
  - io_uring/io_uring.c:__io_submit_flush_completions
  - io_uring/io_uring.c:__io_req_complete_post
  - io_uring/io_uring.c:__io_req_complete_post
  - io_uring/io_uring.c:io_fill_cqe_aux
  - io_uring/io_uring.c:io_fill_cqe_aux
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
