# Function: <code>io_install_fixed_file</code>

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
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (ffffffff813e7740)
Location: fs/io_uring.c:8432
Inline: True
Direct callers:
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_openat2
```
**Symbols:**

```
ffffffff813e7740-ffffffff813e7940: io_install_fixed_file.isra.0 (STB_LOCAL)
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
In io_uring/io_uring.c (ffffffff816d3dd7)
Location: io_uring/io_uring.c:9707
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_fixed_fd_install
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int io_install_fixed_file(struct io_ring_ctx *ctx, struct file *file, u32 slot_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/filetable.c (ffffffff81793f00)
Location: io_uring/filetable.c:60
Inline: False
Direct callers:
  - io_uring/filetable.c:__io_fixed_fd_install
  - io_uring/filetable.c:__io_fixed_fd_install
```
**Symbols:**

```
ffffffff81793f00-ffffffff817940c4: io_install_fixed_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int io_install_fixed_file(struct io_ring_ctx *ctx, struct file *file, u32 slot_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/filetable.c (ffffffff817d4c50)
Location: io_uring/filetable.c:63
Inline: False
Direct callers:
  - io_uring/filetable.c:__io_fixed_fd_install
  - io_uring/filetable.c:__io_fixed_fd_install
```
**Symbols:**

```
ffffffff817d4c50-ffffffff817d4da8: io_install_fixed_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int io_install_fixed_file(struct io_ring_ctx *ctx, struct file *file, u32 slot_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/filetable.c (ffffffff81818ab0)
Location: io_uring/filetable.c:63
Inline: False
Direct callers:
  - io_uring/filetable.c:__io_fixed_fd_install
  - io_uring/filetable.c:__io_fixed_fd_install
```
**Symbols:**

```
ffffffff81818ab0-ffffffff81818bfb: io_install_fixed_file (STB_LOCAL)
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
