# Function: <code>io_scm_file_account</code>

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
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (ffffffff816d3b70)
Location: io_uring/io_uring.c:9440
Inline: True
Direct callers:
  - io_uring/io_uring.c:__io_sqe_files_update
  - io_uring/io_uring.c:io_sqe_files_register
  - io_uring/io_uring.c:io_fixed_fd_install
  - io_uring/io_uring.c:io_fixed_fd_install
```
**Symbols:**

```
ffffffff816d3b70-ffffffff816d3d90: io_scm_file_account.isra.0 (STB_LOCAL)
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
In io_uring/filetable.c (ffffffff81793fe2)
Location: io_uring/rsrc.h:95
Inline: True
Inline callers:
  - io_uring/filetable.c:io_install_fixed_file
```
```
In io_uring/rsrc.c (ffffffff817a1e42)
Location: io_uring/rsrc.h:95
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_sqe_files_register
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
In io_uring/filetable.c (ffffffff817d4cf6)
Location: io_uring/rsrc.h:93
Inline: True
Inline callers:
  - io_uring/filetable.c:io_install_fixed_file
```
```
In io_uring/rsrc.c (ffffffff817e2fcd)
Location: io_uring/rsrc.h:93
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_sqe_files_register
  - io_uring/rsrc.c:__io_sqe_files_update
```
</details>
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
