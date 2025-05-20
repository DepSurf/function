# Function: <code>io_is_uring_fops</code>

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
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool io_is_uring_fops(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8178c7ea)
Location: io_uring/io_uring.c:3431
Inline: True
Inline callers:
  - io_uring/io_uring.c:__ia32_sys_io_uring_register
  - io_uring/io_uring.c:__x64_sys_io_uring_register
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:io_file_get_normal
  - io_uring/io_uring.c:io_file_get_flags
  - io_uring/io_uring.c:io_uring_get_socket
Direct callers:
  - io_uring/filetable.c:io_install_fixed_file
  - io_uring/openclose.c:io_close
  - io_uring/msg_ring.c:io_msg_ring
  - io_uring/sqpoll.c:io_sq_offload_create
  - io_uring/sqpoll.c:io_get_sq_data
  - io_uring/tctx.c:io_ringfd_register
  - io_uring/rsrc.c:io_sqe_files_register
  - io_uring/rsrc.c:__io_sqe_files_update
```
**Symbols:**

```
ffffffff81792800-ffffffff8179281c: io_is_uring_fops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool io_is_uring_fops(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817cda9d)
Location: io_uring/io_uring.c:3717
Inline: True
Inline callers:
  - io_uring/io_uring.c:__do_sys_io_uring_register
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:io_file_get_normal
  - io_uring/io_uring.c:io_uring_get_socket
Direct callers:
  - io_uring/filetable.c:io_install_fixed_file
  - io_uring/openclose.c:io_close
  - io_uring/msg_ring.c:io_msg_ring
  - io_uring/sqpoll.c:io_sq_offload_create
  - io_uring/sqpoll.c:io_get_sq_data
  - io_uring/tctx.c:io_ringfd_register
  - io_uring/rsrc.c:io_sqe_files_register
  - io_uring/rsrc.c:__io_sqe_files_update
```
**Symbols:**

```
ffffffff817d3570-ffffffff817d358f: io_is_uring_fops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool io_is_uring_fops(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff818160cc)
Location: io_uring/io_uring.c:3740
Inline: True
Inline callers:
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:io_file_get_normal
Direct callers:
  - io_uring/filetable.c:io_install_fixed_file
  - io_uring/openclose.c:io_close
  - io_uring/msg_ring.c:io_msg_ring
  - io_uring/sqpoll.c:io_sq_offload_create
  - io_uring/sqpoll.c:io_get_sq_data
  - io_uring/tctx.c:io_ringfd_register
  - io_uring/rsrc.c:io_sqe_files_register
  - io_uring/rsrc.c:__io_sqe_files_update
  - io_uring/register.c:__do_sys_io_uring_register
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff81817380-ffffffff8181739f: io_is_uring_fops (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
