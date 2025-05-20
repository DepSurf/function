# Function: <code>io_rsrc_node_switch</code>

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
<summary>In <code>5.13</code>: ✅</summary>

```c
void io_rsrc_node_switch(struct io_ring_ctx *ctx, struct io_rsrc_data *data_to_kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813980c0)
Location: fs/io_uring.c:7117
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:__io_sqe_buffers_update
  - fs/io_uring.c:io_sqe_buffers_register
  - fs/io_uring.c:__io_sqe_files_update
  - fs/io_uring.c:io_sqe_files_register
```
**Symbols:**

```
ffffffff813980c0-ffffffff81398193: io_rsrc_node_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void io_rsrc_node_switch(struct io_ring_ctx *ctx, struct io_rsrc_data *data_to_kill);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e9046)
Location: fs/io_uring.c:7769
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffers_register
  - fs/io_uring.c:io_sqe_files_register
Direct callers:
  - fs/io_uring.c:__io_sqe_buffers_update
  - fs/io_uring.c:__io_sqe_files_update
  - fs/io_uring.c:io_close
```
**Symbols:**

```
ffffffff813e3c10-ffffffff813e3ce3: io_rsrc_node_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void io_rsrc_node_switch(struct io_ring_ctx *ctx, struct io_rsrc_data *data_to_kill);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (ffffffff816c93b6)
Location: io_uring/io_uring.c:9078
Inline: True
Direct callers:
  - io_uring/io_uring.c:io_uring_create
  - io_uring/io_uring.c:__io_sqe_buffers_update
  - io_uring/io_uring.c:__io_sqe_buffers_update
  - io_uring/io_uring.c:io_sqe_buffers_register
  - io_uring/io_uring.c:__io_sqe_files_update
  - io_uring/io_uring.c:__io_sqe_files_update
  - io_uring/io_uring.c:io_sqe_files_register
  - io_uring/io_uring.c:io_rsrc_ref_quiesce
  - io_uring/io_uring.c:io_fixed_fd_install
  - io_uring/io_uring.c:io_fixed_fd_install
```
**Symbols:**

```
ffffffff816c9380-ffffffff816c93de: io_rsrc_node_switch (STB_LOCAL)
ffffffff81e8f534-ffffffff81e8f5d8: io_rsrc_node_switch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void io_rsrc_node_switch(struct io_ring_ctx *ctx, struct io_rsrc_data *data_to_kill);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff817a2d4d)
Location: io_uring/rsrc.c:283
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_sqe_buffers_register
  - io_uring/rsrc.c:io_sqe_files_register
Direct callers:
  - io_uring/io_uring.c:io_uring_create
  - io_uring/filetable.c:io_fixed_fd_remove
  - io_uring/filetable.c:io_install_fixed_file
  - io_uring/rsrc.c:__io_sqe_buffers_update
  - io_uring/rsrc.c:__io_sqe_buffers_update
  - io_uring/rsrc.c:__io_sqe_files_update
  - io_uring/rsrc.c:__io_sqe_files_update
```
**Symbols:**

```
ffffffff817a0e60-ffffffff817a0f5c: io_rsrc_node_switch (STB_GLOBAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
