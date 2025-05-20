# Function: <code>io_req_queue_tw_complete</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/msg_ring.c (ffffffff817988e6)
Location: io_uring/io_uring.h:406
Inline: True
Inline callers:
  - io_uring/msg_ring.c:io_msg_tw_fd_complete
  - io_uring/msg_ring.c:io_msg_tw_complete
```
```
In io_uring/timeout.c (ffffffff81799fa9)
Location: io_uring/io_uring.h:406
Inline: True
Inline callers:
  - io_uring/timeout.c:io_kill_timeouts
  - io_uring/timeout.c:io_disarm_next
  - io_uring/timeout.c:io_disarm_next
  - io_uring/timeout.c:io_flush_timeouts
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
In io_uring/msg_ring.c (ffffffff817d9813)
Location: io_uring/io_uring.h:382
Inline: True
Inline callers:
  - io_uring/msg_ring.c:io_msg_tw_fd_complete
  - io_uring/msg_ring.c:io_msg_tw_complete
```
```
In io_uring/timeout.c (ffffffff817da6f9)
Location: io_uring/io_uring.h:382
Inline: True
Inline callers:
  - io_uring/timeout.c:io_disarm_next
  - io_uring/timeout.c:io_disarm_next
  - io_uring/timeout.c:io_flush_timeouts
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/msg_ring.c (ffffffff8181db33)
Location: io_uring/io_uring.h:384
Inline: True
Inline callers:
  - io_uring/msg_ring.c:io_msg_tw_fd_complete
  - io_uring/msg_ring.c:io_msg_tw_complete
```
```
In io_uring/timeout.c (ffffffff8181e9e9)
Location: io_uring/io_uring.h:384
Inline: True
Inline callers:
  - io_uring/timeout.c:io_disarm_next
  - io_uring/timeout.c:io_disarm_next
  - io_uring/timeout.c:io_flush_timeouts
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
