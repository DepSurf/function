# Function: <code>__get_unused_fd_flags</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __get_unused_fd_flags(unsigned int flags, long unsigned int nofile);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81339bbd)
Location: fs/file.c:543
Inline: True
Inline callers:
  - fs/file.c:ksys_dup
Direct callers:
  - fs/io_uring.c:io_openat2
  - net/socket.c:__sys_accept4_file
```
**Symbols:**

```
ffffffff81339700-ffffffff81339727: __get_unused_fd_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __get_unused_fd_flags(unsigned int flags, long unsigned int nofile);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81344cdd)
Location: fs/file.c:528
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - fs/file.c:__receive_fd
Direct callers:
  - fs/io_uring.c:io_openat2
  - net/socket.c:__sys_accept4_file
```
**Symbols:**

```
ffffffff81345170-ffffffff81345184: __get_unused_fd_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __get_unused_fd_flags(unsigned int flags, long unsigned int nofile);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8134aea0)
Location: fs/file.c:528
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - fs/file.c:__receive_fd
Direct callers:
  - fs/io_uring.c:io_openat2
  - net/socket.c:__sys_accept4_file
```
**Symbols:**

```
ffffffff8134b4f0-ffffffff8134b504: __get_unused_fd_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __get_unused_fd_flags(unsigned int flags, long unsigned int nofile);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81398c00)
Location: fs/file.c:528
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - fs/file.c:receive_fd
Direct callers:
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_openat2
  - net/socket.c:__sys_accept4_file
```
**Symbols:**

```
ffffffff81399350-ffffffff81399364: __get_unused_fd_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int __get_unused_fd_flags(unsigned int flags, long unsigned int nofile);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8141b44e)
Location: fs/file.c:557
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - fs/file.c:receive_fd
Direct callers:
  - io_uring/io_uring.c:io_socket
  - io_uring/io_uring.c:io_accept
  - io_uring/io_uring.c:io_openat2
  - net/socket.c:__sys_accept4_file
```
**Symbols:**

```
ffffffff8141bcc0-ffffffff8141bcde: __get_unused_fd_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int __get_unused_fd_flags(unsigned int flags, long unsigned int nofile);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814a750e)
Location: fs/file.c:557
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - fs/file.c:receive_fd
Direct callers:
  - io_uring/openclose.c:io_openat2
  - io_uring/net.c:io_socket
  - io_uring/net.c:io_accept
```
**Symbols:**

```
ffffffff814a7e30-ffffffff814a7e4e: __get_unused_fd_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int __get_unused_fd_flags(unsigned int flags, long unsigned int nofile);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814dc4ee)
Location: fs/file.c:557
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - fs/file.c:receive_fd
Direct callers:
  - io_uring/openclose.c:io_openat2
  - io_uring/net.c:io_socket
  - io_uring/net.c:io_accept
```
**Symbols:**

```
ffffffff814dce10-ffffffff814dce2e: __get_unused_fd_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int __get_unused_fd_flags(unsigned int flags, long unsigned int nofile);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8150ee26)
Location: fs/file.c:557
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
Direct callers:
  - io_uring/openclose.c:io_openat2
  - io_uring/net.c:io_socket
  - io_uring/net.c:io_accept
```
**Symbols:**

```
ffffffff8150f5d0-ffffffff8150f5ee: __get_unused_fd_flags (STB_GLOBAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
