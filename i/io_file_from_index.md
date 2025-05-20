# Function: <code>io_file_from_index</code>

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
In fs/io_uring.c (ffffffff813810c2)
Location: fs/io_uring.c:5578
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:__io_sqe_files_scm
  - fs/io_uring.c:io_file_get
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
In fs/io_uring.c (ffffffff8138e54a)
Location: fs/io_uring.c:6453
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:__io_sqe_files_scm
  - fs/io_uring.c:io_file_get
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
In fs/io_uring.c (ffffffff81397ee3)
Location: fs/io_uring.c:6330
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_show_fdinfo
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:__io_sqe_files_scm
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
In fs/io_uring.c (ffffffff813e3a44)
Location: fs/io_uring.c:6888
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_show_fdinfo
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:__io_sqe_files_scm
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
In io_uring/io_uring.c (ffffffff81e900fb)
Location: io_uring/io_uring.c:8128
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_show_fdinfo
  - io_uring/io_uring.c:__io_sqe_files_unregister
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
In io_uring/fdinfo.c (ffffffff8179b576)
Location: io_uring/filetable.h:46
Inline: True
Inline callers:
  - io_uring/fdinfo.c:__io_uring_show_fdinfo
```
```
In io_uring/rsrc.c (ffffffff817a129c)
Location: io_uring/filetable.h:46
Inline: True
Inline callers:
  - io_uring/rsrc.c:__io_sqe_files_unregister
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
In io_uring/msg_ring.c (ffffffff817d9976)
Location: io_uring/filetable.h:56
Inline: True
Inline callers:
  - io_uring/msg_ring.c:io_msg_send_fd
```
```
In io_uring/fdinfo.c (ffffffff817dc69b)
Location: io_uring/filetable.h:56
Inline: True
Inline callers:
  - io_uring/fdinfo.c:__io_uring_show_fdinfo
```
```
In io_uring/cancel.c (ffffffff817df77a)
Location: io_uring/filetable.h:56
Inline: True
Inline callers:
  - io_uring/cancel.c:__io_sync_cancel
```
```
In io_uring/rsrc.c (ffffffff817e248d)
Location: io_uring/filetable.h:56
Inline: True
Inline callers:
  - io_uring/rsrc.c:__io_sqe_files_unregister
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
In io_uring/msg_ring.c (ffffffff8181dc96)
Location: io_uring/filetable.h:56
Inline: True
Inline callers:
  - io_uring/msg_ring.c:io_msg_send_fd
```
```
In io_uring/fdinfo.c (ffffffff81820c1c)
Location: io_uring/filetable.h:56
Inline: True
Inline callers:
  - io_uring/fdinfo.c:io_uring_show_fdinfo
```
```
In io_uring/cancel.c (ffffffff81823bda)
Location: io_uring/filetable.h:56
Inline: True
Inline callers:
  - io_uring/cancel.c:__io_sync_cancel
```
```
In io_uring/rsrc.c (ffffffff81826dcb)
Location: io_uring/filetable.h:56
Inline: True
Inline callers:
  - io_uring/rsrc.c:__io_sqe_files_unregister
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
