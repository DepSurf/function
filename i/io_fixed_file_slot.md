# Function: <code>io_fixed_file_slot</code>

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
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81397ee3)
Location: fs/io_uring.c:6321
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_show_fdinfo
  - fs/io_uring.c:__io_sqe_files_update
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:__io_sqe_files_scm
  - fs/io_uring.c:io_file_get
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
Location: fs/io_uring.c:6882
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_show_fdinfo
  - fs/io_uring.c:__io_sqe_files_update
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:__io_sqe_files_scm
  - fs/io_uring.c:io_init_req
  - fs/io_uring.c:io_close
  - fs/io_uring.c:__io_splice_prep
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
Location: io_uring/io_uring.c:8122
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_show_fdinfo
  - io_uring/io_uring.c:__io_sqe_files_update
  - io_uring/io_uring.c:io_sqe_files_register
  - io_uring/io_uring.c:__io_sqe_files_unregister
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_issue_sqe
  - io_uring/io_uring.c:io_async_cancel
  - io_uring/io_uring.c:io_fixed_fd_install
  - io_uring/io_uring.c:io_splice
  - io_uring/io_uring.c:io_tee
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
In io_uring/io_uring.c (ffffffff817913f6)
Location: io_uring/filetable.h:41
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_issue_sqe
```
```
In io_uring/filetable.c (ffffffff8179434d)
Location: io_uring/filetable.h:41
Inline: True
Inline callers:
  - io_uring/filetable.c:io_fixed_fd_remove
  - io_uring/filetable.c:io_install_fixed_file
```
```
In io_uring/msg_ring.c (ffffffff81798bd1)
Location: io_uring/filetable.h:41
Inline: True
Inline callers:
  - io_uring/msg_ring.c:io_msg_ring
```
```
In io_uring/fdinfo.c (ffffffff8179b576)
Location: io_uring/filetable.h:41
Inline: True
Inline callers:
  - io_uring/fdinfo.c:__io_uring_show_fdinfo
```
```
In io_uring/cancel.c (ffffffff8179e58c)
Location: io_uring/filetable.h:41
Inline: True
Inline callers:
  - io_uring/cancel.c:__io_sync_cancel
```
```
In io_uring/rsrc.c (ffffffff817a1e58)
Location: io_uring/filetable.h:41
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_sqe_files_register
  - io_uring/rsrc.c:__io_sqe_files_unregister
  - io_uring/rsrc.c:__io_sqe_files_update
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
In io_uring/io_uring.c (ffffffff817d2658)
Location: io_uring/filetable.h:37
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_issue_sqe
```
```
In io_uring/filetable.c (ffffffff817d502d)
Location: io_uring/filetable.h:37
Inline: True
Inline callers:
  - io_uring/filetable.c:io_fixed_fd_remove
  - io_uring/filetable.c:io_install_fixed_file
```
```
In io_uring/msg_ring.c (ffffffff817d9976)
Location: io_uring/filetable.h:37
Inline: True
Inline callers:
  - io_uring/msg_ring.c:io_msg_send_fd
```
```
In io_uring/fdinfo.c (ffffffff817dc69b)
Location: io_uring/filetable.h:37
Inline: True
Inline callers:
  - io_uring/fdinfo.c:__io_uring_show_fdinfo
```
```
In io_uring/cancel.c (ffffffff817df77a)
Location: io_uring/filetable.h:37
Inline: True
Inline callers:
  - io_uring/cancel.c:__io_sync_cancel
```
```
In io_uring/rsrc.c (ffffffff817e2fd7)
Location: io_uring/filetable.h:37
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_sqe_files_register
  - io_uring/rsrc.c:__io_sqe_files_unregister
  - io_uring/rsrc.c:__io_sqe_files_update
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
In io_uring/io_uring.c (ffffffff81815898)
Location: io_uring/filetable.h:37
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_issue_sqe
```
```
In io_uring/filetable.c (ffffffff81818e7d)
Location: io_uring/filetable.h:37
Inline: True
Inline callers:
  - io_uring/filetable.c:io_fixed_fd_remove
  - io_uring/filetable.c:io_install_fixed_file
```
```
In io_uring/msg_ring.c (ffffffff8181dc96)
Location: io_uring/filetable.h:37
Inline: True
Inline callers:
  - io_uring/msg_ring.c:io_msg_send_fd
```
```
In io_uring/fdinfo.c (ffffffff81820c1c)
Location: io_uring/filetable.h:37
Inline: True
Inline callers:
  - io_uring/fdinfo.c:io_uring_show_fdinfo
```
```
In io_uring/cancel.c (ffffffff81823bda)
Location: io_uring/filetable.h:37
Inline: True
Inline callers:
  - io_uring/cancel.c:__io_sync_cancel
```
```
In io_uring/rsrc.c (ffffffff818270ac)
Location: io_uring/filetable.h:37
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_sqe_files_register
  - io_uring/rsrc.c:__io_sqe_files_unregister
  - io_uring/rsrc.c:__io_sqe_files_update
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
