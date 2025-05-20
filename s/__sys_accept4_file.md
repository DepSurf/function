# Function: <code>__sys_accept4_file</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
int __sys_accept4_file(struct file *file, unsigned int file_flags, struct sockaddr *upeer_sockaddr, int *upeer_addrlen, int flags, long unsigned int nofile);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e1030)
Location: net/socket.c:1703
Inline: False
Direct callers:
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - net/socket.c:__sys_accept4
```
**Symbols:**

```
ffffffff819e1030-ffffffff819e1225: __sys_accept4_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __sys_accept4_file(struct file *file, unsigned int file_flags, struct sockaddr *upeer_sockaddr, int *upeer_addrlen, int flags, long unsigned int nofile);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e0880)
Location: net/socket.c:1681
Inline: False
Direct callers:
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - net/socket.c:__sys_accept4
```
**Symbols:**

```
ffffffff819e0880-ffffffff819e0a75: __sys_accept4_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __sys_accept4_file(struct file *file, unsigned int file_flags, struct sockaddr *upeer_sockaddr, int *upeer_addrlen, int flags, long unsigned int nofile);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c68d0)
Location: net/socket.c:1672
Inline: False
Direct callers:
  - fs/io_uring.c:io_issue_sqe
  - net/socket.c:__sys_accept4
```
**Symbols:**

```
ffffffff819c68d0-ffffffff819c6ac5: __sys_accept4_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __sys_accept4_file(struct file *file, unsigned int file_flags, struct sockaddr *upeer_sockaddr, int *upeer_addrlen, int flags, long unsigned int nofile);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a75d80)
Location: net/socket.c:1801
Inline: False
Direct callers:
  - net/socket.c:__sys_accept4
```
**Symbols:**

```
ffffffff81a75d80-ffffffff81a75e18: __sys_accept4_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __sys_accept4_file(struct file *file, unsigned int file_flags, struct sockaddr *upeer_sockaddr, int *upeer_addrlen, int flags, long unsigned int nofile);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be8da0)
Location: net/socket.c:1881
Inline: False
Direct callers:
  - net/socket.c:__sys_accept4
```
**Symbols:**

```
ffffffff81be8da0-ffffffff81be8e44: __sys_accept4_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d95589)
Location: net/socket.c:1881
Inline: True
Inline callers:
  - net/socket.c:__sys_accept4
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e03bb9)
Location: net/socket.c:1911
Inline: True
Inline callers:
  - net/socket.c:__sys_accept4
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ec05e9)
Location: net/socket.c:1953
Inline: True
Inline callers:
  - net/socket.c:__sys_accept4
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
</ul>
