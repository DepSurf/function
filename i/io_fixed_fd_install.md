# Function: <code>io_fixed_fd_install</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
int io_fixed_fd_install(struct io_kiocb *req, unsigned int issue_flags, struct file *file, unsigned int file_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816d3d90)
Location: io_uring/io_uring.c:5211
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_files_update
  - io_uring/io_uring.c:io_socket
  - io_uring/io_uring.c:io_accept
  - io_uring/io_uring.c:io_openat2
```
**Symbols:**

```
ffffffff816d3d90-ffffffff816d40e9: io_fixed_fd_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int io_fixed_fd_install(struct io_kiocb *req, unsigned int issue_flags, struct file *file, unsigned int file_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/filetable.c (ffffffff81794260)
Location: io_uring/filetable.c:131
Inline: False
Direct callers:
  - io_uring/openclose.c:io_openat2
  - io_uring/net.c:io_socket
  - io_uring/net.c:io_accept
  - io_uring/rsrc.c:io_files_update
```
**Symbols:**

```
ffffffff81794260-ffffffff817942ee: io_fixed_fd_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int io_fixed_fd_install(struct io_kiocb *req, unsigned int issue_flags, struct file *file, unsigned int file_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/filetable.c (ffffffff817d4f50)
Location: io_uring/filetable.c:123
Inline: False
Direct callers:
  - io_uring/openclose.c:io_openat2
  - io_uring/net.c:io_socket
  - io_uring/net.c:io_accept
  - io_uring/rsrc.c:io_files_update
```
**Symbols:**

```
ffffffff817d4f50-ffffffff817d4fde: io_fixed_fd_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int io_fixed_fd_install(struct io_kiocb *req, unsigned int issue_flags, struct file *file, unsigned int file_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/filetable.c (ffffffff81818da0)
Location: io_uring/filetable.c:120
Inline: False
Direct callers:
  - io_uring/openclose.c:io_openat2
  - io_uring/net.c:io_socket
  - io_uring/net.c:io_accept
  - io_uring/rsrc.c:io_files_update
```
**Symbols:**

```
ffffffff81818da0-ffffffff81818e2e: io_fixed_fd_install (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
