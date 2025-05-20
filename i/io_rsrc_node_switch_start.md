# Function: <code>io_rsrc_node_switch_start</code>

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
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (ffffffff8139e9ba)
Location: fs/io_uring.c:7142
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_register_rsrc_update
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffers_register
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:io_issue_sqe
Direct callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_register_rsrc_update
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffers_register
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff81392020-ffffffff813920ba: io_rsrc_node_switch_start.part.0 (STB_LOCAL)
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
In fs/io_uring.c (ffffffff813ee959)
Location: fs/io_uring.c:7794
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_register_rsrc_update
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffers_register
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_close
Direct callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_register_rsrc_update
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffers_register
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_close
```
**Symbols:**

```
ffffffff813dfe70-ffffffff813dff0a: io_rsrc_node_switch_start.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int io_rsrc_node_switch_start(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816d4c9e)
Location: io_uring/io_uring.c:9106
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_register_rsrc_update
  - io_uring/io_uring.c:io_sqe_buffers_register
  - io_uring/io_uring.c:io_sqe_files_register
Direct callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:io_uring_create
  - io_uring/io_uring.c:io_rsrc_ref_quiesce
  - io_uring/io_uring.c:io_files_update
  - io_uring/io_uring.c:io_files_update
  - io_uring/io_uring.c:io_fixed_fd_install
```
**Symbols:**

```
ffffffff816cb020-ffffffff816cb0d6: io_rsrc_node_switch_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int io_rsrc_node_switch_start(struct io_ring_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff817a2942)
Location: io_uring/rsrc.c:311
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_register_rsrc_update
Direct callers:
  - io_uring/io_uring.c:io_uring_create
  - io_uring/filetable.c:io_fixed_fd_remove
  - io_uring/filetable.c:io_install_fixed_file
  - io_uring/rsrc.c:io_sqe_buffers_register
  - io_uring/rsrc.c:io_sqe_files_register
  - io_uring/rsrc.c:io_files_update
  - io_uring/rsrc.c:io_files_update
  - io_uring/rsrc.c:io_register_files_update
```
**Symbols:**

```
ffffffff817a0f70-ffffffff817a1026: io_rsrc_node_switch_start (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
