# Function: <code>do_accept</code>

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
<summary>In <code>5.15</code>: ✅</summary>

```c
struct file *do_accept(struct file *file, unsigned int file_flags, struct sockaddr *upeer_sockaddr, int *upeer_addrlen, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a75bf0)
Location: net/socket.c:1742
Inline: False
Direct callers:
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - net/socket.c:__sys_accept4_file
```
**Symbols:**

```
ffffffff81a75bf0-ffffffff81a75d72: do_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct file *do_accept(struct file *file, unsigned int file_flags, struct sockaddr *upeer_sockaddr, int *upeer_addrlen, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be8bf0)
Location: net/socket.c:1822
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_accept
  - io_uring/io_uring.c:io_accept
  - net/socket.c:__sys_accept4_file
```
**Symbols:**

```
ffffffff81be8bf0-ffffffff81be8d94: do_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct file *do_accept(struct file *file, unsigned int file_flags, struct sockaddr *upeer_sockaddr, int *upeer_addrlen, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d95390)
Location: net/socket.c:1822
Inline: False
Direct callers:
  - io_uring/net.c:io_accept
  - io_uring/net.c:io_accept
  - net/socket.c:__sys_accept4
```
**Symbols:**

```
ffffffff81d95390-ffffffff81d95534: do_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct file *do_accept(struct file *file, unsigned int file_flags, struct sockaddr *upeer_sockaddr, int *upeer_addrlen, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e039b0)
Location: net/socket.c:1851
Inline: False
Direct callers:
  - io_uring/net.c:io_accept
  - io_uring/net.c:io_accept
  - net/socket.c:__sys_accept4
```
**Symbols:**

```
ffffffff81e039b0-ffffffff81e03b6a: do_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct file *do_accept(struct file *file, unsigned int file_flags, struct sockaddr *upeer_sockaddr, int *upeer_addrlen, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ec03e0)
Location: net/socket.c:1893
Inline: False
Direct callers:
  - io_uring/net.c:io_accept
  - io_uring/net.c:io_accept
  - net/socket.c:__sys_accept4
```
**Symbols:**

```
ffffffff81ec03e0-ffffffff81ec059a: do_accept (STB_GLOBAL)
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
