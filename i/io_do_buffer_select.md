# Function: <code>io_do_buffer_select</code>

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
In io_uring/io_uring.c (ffffffff816d2117)
Location: io_uring/io_uring.c:3738
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_recv
  - io_uring/io_uring.c:io_recvmsg
  - io_uring/io_uring.c:io_read
  - io_uring/io_uring.c:__io_import_iovec
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
In io_uring/net.c (ffffffff81797196)
Location: io_uring/kbuf.h:80
Inline: True
Inline callers:
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recvmsg
```
```
In io_uring/rw.c (ffffffff817a42f8)
Location: io_uring/kbuf.h:80
Inline: True
Inline callers:
  - io_uring/rw.c:io_read
  - io_uring/rw.c:__io_import_iovec
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
In io_uring/net.c (ffffffff817d7ee7)
Location: io_uring/kbuf.h:87
Inline: True
Inline callers:
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recvmsg
```
```
In io_uring/rw.c (ffffffff817e52f8)
Location: io_uring/kbuf.h:87
Inline: True
Inline callers:
  - io_uring/rw.c:io_read
  - io_uring/rw.c:__io_import_iovec
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
In io_uring/net.c (ffffffff8181c1a7)
Location: io_uring/kbuf.h:95
Inline: True
Inline callers:
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recvmsg
```
```
In io_uring/rw.c (ffffffff81828928)
Location: io_uring/kbuf.h:95
Inline: True
Inline callers:
  - io_uring/rw.c:__io_read
  - io_uring/rw.c:__io_import_iovec
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
