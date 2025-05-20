# Function: <code>io_queue_rsrc_removal</code>

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
In fs/io_uring.c (ffffffff813982ea)
Location: fs/io_uring.c:7789
Inline: True
Inline callers:
  - fs/io_uring.c:__io_sqe_buffers_update
  - fs/io_uring.c:__io_sqe_files_update
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int io_queue_rsrc_removal(struct io_rsrc_data *data, unsigned int idx, struct io_rsrc_node *node, void *rsrc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813dfdf0)
Location: fs/io_uring.c:8417
Inline: False
Direct callers:
  - fs/io_uring.c:__io_sqe_buffers_update
  - fs/io_uring.c:__io_sqe_files_update
  - fs/io_uring.c:io_close
```
**Symbols:**

```
ffffffff813dfdf0-ffffffff813dfe6e: io_queue_rsrc_removal (STB_LOCAL)
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
In io_uring/io_uring.c (ffffffff816cabe0)
Location: io_uring/io_uring.c:9690
Inline: True
Direct callers:
  - io_uring/io_uring.c:__io_sqe_buffers_update
  - io_uring/io_uring.c:__io_sqe_files_update
  - io_uring/io_uring.c:io_fixed_fd_install
```
**Symbols:**

```
ffffffff816cabe0-ffffffff816cac6c: io_queue_rsrc_removal.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int io_queue_rsrc_removal(struct io_rsrc_data *data, unsigned int idx, struct io_rsrc_node *node, void *rsrc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff817a11d0)
Location: io_uring/rsrc.c:756
Inline: False
Direct callers:
  - io_uring/filetable.c:io_fixed_fd_remove
  - io_uring/filetable.c:io_install_fixed_file
  - io_uring/rsrc.c:__io_sqe_buffers_update
  - io_uring/rsrc.c:__io_sqe_files_update
```
**Symbols:**

```
ffffffff817a11d0-ffffffff817a1260: io_queue_rsrc_removal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int io_queue_rsrc_removal(struct io_rsrc_data *data, unsigned int idx, void *rsrc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff817e2380)
Location: io_uring/rsrc.c:644
Inline: False
Direct callers:
  - io_uring/filetable.c:io_fixed_fd_remove
  - io_uring/filetable.c:io_install_fixed_file
  - io_uring/rsrc.c:__io_sqe_buffers_update
  - io_uring/rsrc.c:__io_sqe_files_update
```
**Symbols:**

```
ffffffff817e2380-ffffffff817e244f: io_queue_rsrc_removal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int io_queue_rsrc_removal(struct io_rsrc_data *data, unsigned int idx, void *rsrc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff81826730)
Location: io_uring/rsrc.c:639
Inline: False
Direct callers:
  - io_uring/filetable.c:io_fixed_fd_remove
  - io_uring/filetable.c:io_install_fixed_file
  - io_uring/rsrc.c:__io_sqe_buffers_update
  - io_uring/rsrc.c:__io_sqe_files_update
```
**Symbols:**

```
ffffffff81826730-ffffffff818267ff: io_queue_rsrc_removal (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct io_rsrc_node *node</code>
</li>
<li>
<b>Param reordered. </b>
<code>data, idx, node, rsrc</code> ➡️ <code>data, idx, rsrc</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
