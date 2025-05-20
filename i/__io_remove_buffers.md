# Function: <code>__io_remove_buffers</code>

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
In fs/io_uring.c (ffffffff8137c855)
Location: fs/io_uring.c:3177
Inline: True
Inline callers:
  - fs/io_uring.c:__io_destroy_buffers
  - fs/io_uring.c:__io_destroy_buffers
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_provide_buffers
  - fs/io_uring.c:io_provide_buffers
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
In fs/io_uring.c (ffffffff8138aed3)
Location: fs/io_uring.c:4158
Inline: True
Inline callers:
  - fs/io_uring.c:__io_destroy_buffers
  - fs/io_uring.c:__io_destroy_buffers
  - fs/io_uring.c:io_provide_buffers
  - fs/io_uring.c:io_provide_buffers
  - fs/io_uring.c:io_remove_buffers
  - fs/io_uring.c:io_remove_buffers
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
In fs/io_uring.c (ffffffff8139acb1)
Location: fs/io_uring.c:3928
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_provide_buffers
  - fs/io_uring.c:io_provide_buffers
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
In fs/io_uring.c (ffffffff813e5289)
Location: fs/io_uring.c:4348
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_provide_buffers
  - fs/io_uring.c:io_provide_buffers
Direct callers:
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff813deb00-ffffffff813debb9: __io_remove_buffers.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (ffffffff816c93e0)
Location: io_uring/io_uring.c:5330
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:__io_uring_register
Direct callers:
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_remove_buffers
```
**Symbols:**

```
ffffffff816c93e0-ffffffff816c9522: __io_remove_buffers.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In io_uring/kbuf.c (ffffffff8179f47c)
Location: io_uring/kbuf.c:208
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_unregister_pbuf_ring
  - io_uring/kbuf.c:io_unregister_pbuf_ring
  - io_uring/kbuf.c:io_destroy_buffers
  - io_uring/kbuf.c:io_destroy_buffers
  - io_uring/kbuf.c:io_destroy_buffers
  - io_uring/kbuf.c:io_destroy_buffers
Direct callers:
  - io_uring/kbuf.c:io_remove_buffers
```
**Symbols:**

```
ffffffff8179edb0-ffffffff8179eef2: __io_remove_buffers.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In io_uring/kbuf.c (ffffffff817e1010)
Location: io_uring/kbuf.c:209
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_unregister_pbuf_ring
  - io_uring/kbuf.c:io_remove_buffers
  - io_uring/kbuf.c:io_destroy_buffers
  - io_uring/kbuf.c:io_destroy_buffers
Direct callers:
  - io_uring/kbuf.c:io_unregister_pbuf_ring
  - io_uring/kbuf.c:io_remove_buffers
  - io_uring/kbuf.c:io_destroy_buffers
  - io_uring/kbuf.c:io_destroy_buffers
```
**Symbols:**

```
ffffffff817dffa0-ffffffff817e0166: __io_remove_buffers.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In io_uring/kbuf.c (ffffffff81825707)
Location: io_uring/kbuf.c:256
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_unregister_pbuf_ring
  - io_uring/kbuf.c:io_remove_buffers
  - io_uring/kbuf.c:io_destroy_buffers
  - io_uring/kbuf.c:io_destroy_buffers
Direct callers:
  - io_uring/kbuf.c:io_unregister_pbuf_ring
  - io_uring/kbuf.c:io_remove_buffers
  - io_uring/kbuf.c:io_destroy_buffers
  - io_uring/kbuf.c:io_destroy_buffers
```
**Symbols:**

```
ffffffff81824440-ffffffff818245ab: __io_remove_buffers.part.0 (STB_LOCAL)
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
