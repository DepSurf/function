# Function: <code>io_buffer_get_list</code>

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
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816d85b1)
Location: io_uring/io_uring.c:1495
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:io_register_pbuf_ring
  - io_uring/io_uring.c:io_provide_buffers
  - io_uring/io_uring.c:io_remove_buffers
  - io_uring/io_uring.c:io_buffer_select
  - io_uring/io_uring.c:io_kbuf_recycle
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
In io_uring/kbuf.c (ffffffff8179fe94)
Location: io_uring/kbuf.c:31
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_unregister_pbuf_ring
  - io_uring/kbuf.c:io_register_pbuf_ring
  - io_uring/kbuf.c:io_provide_buffers
  - io_uring/kbuf.c:io_remove_buffers
  - io_uring/kbuf.c:io_buffer_select
  - io_uring/kbuf.c:io_kbuf_recycle_legacy
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
In io_uring/kbuf.c (ffffffff817e10a5)
Location: io_uring/kbuf.c:31
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_pbuf_get_address
  - io_uring/kbuf.c:io_unregister_pbuf_ring
  - io_uring/kbuf.c:io_register_pbuf_ring
  - io_uring/kbuf.c:io_provide_buffers
  - io_uring/kbuf.c:io_remove_buffers
  - io_uring/kbuf.c:io_buffer_select
  - io_uring/kbuf.c:io_kbuf_recycle_legacy
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
In io_uring/kbuf.c (ffffffff8182582e)
Location: io_uring/kbuf.c:53
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_register_pbuf_status
  - io_uring/kbuf.c:io_unregister_pbuf_ring
  - io_uring/kbuf.c:io_register_pbuf_ring
  - io_uring/kbuf.c:io_provide_buffers
  - io_uring/kbuf.c:io_remove_buffers
  - io_uring/kbuf.c:io_buffer_select
  - io_uring/kbuf.c:io_kbuf_recycle_legacy
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
