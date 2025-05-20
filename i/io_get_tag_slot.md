# Function: <code>io_get_tag_slot</code>

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
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e3e54)
Location: fs/io_uring.c:7849
Inline: True
Inline callers:
  - fs/io_uring.c:__io_sqe_buffers_update
  - fs/io_uring.c:io_sqe_buffers_register
  - fs/io_uring.c:__io_sqe_files_update
  - fs/io_uring.c:io_queue_rsrc_removal
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:io_rsrc_data_alloc
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
In io_uring/io_uring.c (ffffffff816cd894)
Location: io_uring/io_uring.c:9162
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_sqe_buffers_update
  - io_uring/io_uring.c:io_sqe_buffers_register
  - io_uring/io_uring.c:__io_sqe_files_update
  - io_uring/io_uring.c:io_sqe_files_register
  - io_uring/io_uring.c:io_rsrc_data_alloc
  - io_uring/io_uring.c:io_fixed_fd_install
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
In io_uring/filetable.c (ffffffff81793ff3)
Location: io_uring/rsrc.h:159
Inline: True
Inline callers:
  - io_uring/filetable.c:io_install_fixed_file
```
```
In io_uring/rsrc.c (ffffffff817a2c19)
Location: io_uring/rsrc.h:159
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_sqe_buffers_register
  - io_uring/rsrc.c:io_sqe_files_register
  - io_uring/rsrc.c:io_queue_rsrc_removal
  - io_uring/rsrc.c:__io_sqe_buffers_update
  - io_uring/rsrc.c:__io_sqe_files_update
  - io_uring/rsrc.c:io_rsrc_data_alloc
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
In io_uring/filetable.c (ffffffff817d4d03)
Location: io_uring/rsrc.h:143
Inline: True
Inline callers:
  - io_uring/filetable.c:io_install_fixed_file
```
```
In io_uring/rsrc.c (ffffffff817e3c36)
Location: io_uring/rsrc.h:143
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_sqe_buffers_register
  - io_uring/rsrc.c:io_sqe_files_register
  - io_uring/rsrc.c:io_queue_rsrc_removal
  - io_uring/rsrc.c:__io_sqe_buffers_update
  - io_uring/rsrc.c:__io_sqe_files_update
  - io_uring/rsrc.c:io_rsrc_data_alloc
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
In io_uring/filetable.c (ffffffff81818b3a)
Location: io_uring/rsrc.h:124
Inline: True
Inline callers:
  - io_uring/filetable.c:io_install_fixed_file
```
```
In io_uring/rsrc.c (ffffffff81827ce6)
Location: io_uring/rsrc.h:124
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_sqe_buffers_register
  - io_uring/rsrc.c:io_sqe_files_register
  - io_uring/rsrc.c:io_queue_rsrc_removal
  - io_uring/rsrc.c:__io_sqe_buffers_update
  - io_uring/rsrc.c:__io_sqe_files_update
  - io_uring/rsrc.c:io_rsrc_data_alloc
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
