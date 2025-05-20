# Function: <code>io_alloc_cache_get</code>

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
In io_uring/net.c (ffffffff817966de)
Location: io_uring/alloc_cache.h:24
Inline: True
Inline callers:
  - io_uring/net.c:io_recvmsg_prep_async
  - io_uring/net.c:io_sendmsg_prep_async
```
```
In io_uring/poll.c (ffffffff8179dac1)
Location: io_uring/alloc_cache.h:24
Inline: True
Inline callers:
  - io_uring/poll.c:io_arm_poll_handler
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
In io_uring/io_uring.c (ffffffff817ccacd)
Location: io_uring/alloc_cache.h:31
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_ring_ctx_free
```
```
In io_uring/net.c (ffffffff817d73de)
Location: io_uring/alloc_cache.h:31
Inline: True
Inline callers:
  - io_uring/net.c:io_recvmsg_prep_async
  - io_uring/net.c:io_sendmsg_prep_async
```
```
In io_uring/poll.c (ffffffff817dec04)
Location: io_uring/alloc_cache.h:31
Inline: True
Inline callers:
  - io_uring/poll.c:io_arm_poll_handler
```
```
In io_uring/rsrc.c (ffffffff817e2055)
Location: io_uring/alloc_cache.h:31
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_rsrc_node_alloc
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
In io_uring/io_uring.c (ffffffff8181122d)
Location: io_uring/alloc_cache.h:30
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_ring_ctx_free
```
```
In io_uring/net.c (ffffffff8181b64e)
Location: io_uring/alloc_cache.h:30
Inline: True
Inline callers:
  - io_uring/net.c:io_recvmsg_prep_async
  - io_uring/net.c:io_sendmsg_prep_async
```
```
In io_uring/poll.c (ffffffff81822fa4)
Location: io_uring/alloc_cache.h:30
Inline: True
Inline callers:
  - io_uring/poll.c:io_arm_poll_handler
```
```
In io_uring/rsrc.c (ffffffff818263d5)
Location: io_uring/alloc_cache.h:30
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_rsrc_node_alloc
```
```
In io_uring/futex.c (ffffffff8182f7ab)
Location: io_uring/alloc_cache.h:30
Inline: True
Inline callers:
  - io_uring/futex.c:io_futex_wait
  - io_uring/futex.c:io_futex_cache_free
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
