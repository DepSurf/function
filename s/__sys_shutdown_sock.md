# Function: <code>__sys_shutdown_sock</code>

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
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __sys_shutdown_sock(struct socket *sock, int how);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e18ed)
Location: net/socket.c:2178
Inline: True
Inline callers:
  - net/socket.c:__sys_shutdown
  - net/socket.c:__sys_shutdown
Direct callers:
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff819e1870-ffffffff819e18a6: __sys_shutdown_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __sys_shutdown_sock(struct socket *sock, int how);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c798d)
Location: net/socket.c:2172
Inline: True
Inline callers:
  - net/socket.c:__sys_shutdown
  - net/socket.c:__sys_shutdown
Direct callers:
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff819c7910-ffffffff819c7946: __sys_shutdown_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __sys_shutdown_sock(struct socket *sock, int how);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a76cdd)
Location: net/socket.c:2245
Inline: True
Inline callers:
  - net/socket.c:__sys_shutdown
  - net/socket.c:__sys_shutdown
Direct callers:
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff81a76c60-ffffffff81a76c96: __sys_shutdown_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int __sys_shutdown_sock(struct socket *sock, int how);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be9ee4)
Location: net/socket.c:2320
Inline: True
Inline callers:
  - net/socket.c:__sys_shutdown
  - net/socket.c:__sys_shutdown
Direct callers:
  - io_uring/io_uring.c:io_shutdown
```
**Symbols:**

```
ffffffff81be9e60-ffffffff81be9e9b: __sys_shutdown_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int __sys_shutdown_sock(struct socket *sock, int how);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d967e4)
Location: net/socket.c:2312
Inline: True
Inline callers:
  - net/socket.c:__sys_shutdown
  - net/socket.c:__sys_shutdown
Direct callers:
  - io_uring/net.c:io_shutdown
```
**Symbols:**

```
ffffffff81d96750-ffffffff81d9678b: __sys_shutdown_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int __sys_shutdown_sock(struct socket *sock, int how);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e04e34)
Location: net/socket.c:2349
Inline: True
Inline callers:
  - net/socket.c:__sys_shutdown
  - net/socket.c:__sys_shutdown
Direct callers:
  - io_uring/net.c:io_shutdown
```
**Symbols:**

```
ffffffff81e04da0-ffffffff81e04ddb: __sys_shutdown_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int __sys_shutdown_sock(struct socket *sock, int how);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ec16f4)
Location: net/socket.c:2419
Inline: True
Inline callers:
  - net/socket.c:__sys_shutdown
  - net/socket.c:__sys_shutdown
Direct callers:
  - io_uring/net.c:io_shutdown
```
**Symbols:**

```
ffffffff81ec1660-ffffffff81ec169b: __sys_shutdown_sock (STB_GLOBAL)
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
