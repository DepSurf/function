# Function: <code>__io_cqring_events</code>

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
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8138b41e)
Location: fs/io_uring.c:1727
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_poll
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_wake_function
  - fs/io_uring.c:io_iopoll_check
  - fs/io_uring.c:__io_cqring_overflow_flush
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
In fs/io_uring.c (ffffffff813a1992)
Location: fs/io_uring.c:1386
Inline: True
Inline callers:
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_uring_poll
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_wake_function
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_submit_flush_completions
  - fs/io_uring.c:io_req_complete_post
  - fs/io_uring.c:io_cqring_fill_event
  - fs/io_uring.c:__io_cqring_overflow_flush
  - fs/io_uring.c:__io_cqring_overflow_flush
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
In fs/io_uring.c (ffffffff813f0391)
Location: fs/io_uring.c:1601
Inline: True
Inline callers:
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_uring_poll
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_submit_flush_completions
  - fs/io_uring.c:io_req_complete_post
  - fs/io_uring.c:io_cqring_fill_event
  - fs/io_uring.c:__io_cqring_overflow_flush
  - fs/io_uring.c:__io_cqring_overflow_flush
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
In io_uring/io_uring.c (ffffffff816d6c57)
Location: io_uring/io_uring.c:1977
Inline: True
Inline callers:
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:io_uring_poll
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:__io_cqring_overflow_flush
  - io_uring/io_uring.c:__io_get_cqe
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
In io_uring/io_uring.c (ffffffff8178f915)
Location: io_uring/io_uring.c:176
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_iopoll_check
  - io_uring/io_uring.c:__io_get_cqe
  - io_uring/io_uring.c:__io_cqring_overflow_flush
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
In io_uring/io_uring.c (ffffffff817d12b7)
Location: io_uring/io_uring.c:175
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_iopoll_check
  - io_uring/io_uring.c:__io_get_cqe
  - io_uring/io_uring.c:__io_cqring_overflow_flush
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
In io_uring/io_uring.c (ffffffff81814567)
Location: io_uring/io_uring.c:188
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_iopoll_check
  - io_uring/io_uring.c:io_cqe_cache_refill
  - io_uring/io_uring.c:__io_cqring_overflow_flush
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
