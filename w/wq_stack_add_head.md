# Function: <code>wq_stack_add_head</code>

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
In io_uring/io_uring.c (ffffffff81e91d32)
Location: io_uring/io-wq.h:132
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:io_free_batch_list
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
In io_uring/io_uring.c (ffffffff81791840)
Location: io_uring/slist.h:107
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:io_free_batch_list
  - io_uring/io_uring.c:__io_alloc_req_refill
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
In io_uring/io_uring.c (ffffffff817d2ad8)
Location: io_uring/slist.h:88
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:io_free_batch_list
  - io_uring/io_uring.c:io_free_batch_list
  - io_uring/io_uring.c:__io_alloc_req_refill
```
```
In io_uring/net.c (ffffffff817d60c6)
Location: io_uring/slist.h:88
Inline: True
Inline callers:
  - io_uring/net.c:io_netmsg_recycle
```
```
In io_uring/rsrc.c (ffffffff817e1f91)
Location: io_uring/slist.h:88
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_rsrc_node_ref_zero
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
In io_uring/io_uring.c (ffffffff81815dec)
Location: io_uring/slist.h:88
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:io_free_batch_list
  - io_uring/io_uring.c:io_free_batch_list
  - io_uring/io_uring.c:__io_alloc_req_refill
```
```
In io_uring/net.c (ffffffff8181a326)
Location: io_uring/slist.h:88
Inline: True
Inline callers:
  - io_uring/net.c:io_netmsg_recycle
```
```
In io_uring/rsrc.c (ffffffff8182630f)
Location: io_uring/slist.h:88
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_rsrc_node_ref_zero
```
```
In io_uring/futex.c (ffffffff8182f07f)
Location: io_uring/slist.h:88
Inline: True
Inline callers:
  - io_uring/futex.c:io_futex_complete
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
