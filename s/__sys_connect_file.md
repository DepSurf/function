# Function: <code>__sys_connect_file</code>

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
int __sys_connect_file(struct file *file, struct __kernel_sockaddr_storage *address, int addrlen, int file_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e1360)
Location: net/socket.c:1839
Inline: False
Direct callers:
  - fs/io_uring.c:io_connect
  - fs/io_uring.c:io_connect
  - net/socket.c:__sys_connect
```
**Symbols:**

```
ffffffff819e1360-ffffffff819e13c8: __sys_connect_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __sys_connect_file(struct file *file, struct __kernel_sockaddr_storage *address, int addrlen, int file_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e0bb0)
Location: net/socket.c:1818
Inline: False
Direct callers:
  - fs/io_uring.c:io_connect
  - fs/io_uring.c:io_connect
  - net/socket.c:__sys_connect
```
**Symbols:**

```
ffffffff819e0bb0-ffffffff819e0c18: __sys_connect_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __sys_connect_file(struct file *file, struct __kernel_sockaddr_storage *address, int addrlen, int file_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c6bf0)
Location: net/socket.c:1809
Inline: False
Direct callers:
  - fs/io_uring.c:io_connect
  - fs/io_uring.c:io_connect
  - net/socket.c:__sys_connect
```
**Symbols:**

```
ffffffff819c6bf0-ffffffff819c6c58: __sys_connect_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __sys_connect_file(struct file *file, struct __kernel_sockaddr_storage *address, int addrlen, int file_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a75f40)
Location: net/socket.c:1882
Inline: False
Direct callers:
  - fs/io_uring.c:io_connect
  - fs/io_uring.c:io_connect
  - net/socket.c:__sys_connect
```
**Symbols:**

```
ffffffff81a75f40-ffffffff81a75fa8: __sys_connect_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __sys_connect_file(struct file *file, struct __kernel_sockaddr_storage *address, int addrlen, int file_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be8fd0)
Location: net/socket.c:1962
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_connect
  - net/socket.c:__sys_connect
```
**Symbols:**

```
ffffffff81be8fd0-ffffffff81be9050: __sys_connect_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __sys_connect_file(struct file *file, struct __kernel_sockaddr_storage *address, int addrlen, int file_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d95740)
Location: net/socket.c:1959
Inline: False
Direct callers:
  - io_uring/net.c:io_connect
  - net/socket.c:__sys_connect
```
**Symbols:**

```
ffffffff81d95740-ffffffff81d957c0: __sys_connect_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __sys_connect_file(struct file *file, struct __kernel_sockaddr_storage *address, int addrlen, int file_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e03d70)
Location: net/socket.c:1989
Inline: False
Direct callers:
  - io_uring/net.c:io_connect
  - net/socket.c:__sys_connect
```
**Symbols:**

```
ffffffff81e03d70-ffffffff81e03df3: __sys_connect_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __sys_connect_file(struct file *file, struct __kernel_sockaddr_storage *address, int addrlen, int file_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ec07a0)
Location: net/socket.c:2031
Inline: False
Direct callers:
  - io_uring/net.c:io_connect
  - net/socket.c:__sys_connect
```
**Symbols:**

```
ffffffff81ec07a0-ffffffff81ec0823: __sys_connect_file (STB_GLOBAL)
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
