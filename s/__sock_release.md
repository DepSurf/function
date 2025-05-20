# Function: <code>__sock_release</code>

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
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void __sock_release(struct socket *sock, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/socket.c (0)
Location: net/socket.c:593
Inline: False
Direct callers:
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sock_create
  - net/socket.c:sock_close
  - net/socket.c:sock_create_lite
  - net/socket.c:sock_alloc_file
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff8186f360-ffffffff8186f3f5: __sock_release (STB_LOCAL)
ffffffff8187447a-ffffffff81874492: __sock_release.cold.24 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void __sock_release(struct socket *sock, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/socket.c (0)
Location: net/socket.c:572
Inline: False
Direct callers:
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sock_create
  - net/socket.c:sock_close
  - net/socket.c:sock_create_lite
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff8188f820-ffffffff8188f8c5: __sock_release (STB_LOCAL)
ffffffff81894d4a-ffffffff81894d62: __sock_release.cold.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __sock_release(struct socket *sock, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/socket.c (0)
Location: net/socket.c:583
Inline: False
Direct callers:
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sock_create
  - net/socket.c:sock_close
  - net/socket.c:sock_create_lite
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff818d9880-ffffffff818d9924: __sock_release (STB_LOCAL)
ffffffff818df10c-ffffffff818df124: __sock_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void __sock_release(struct socket *sock, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/socket.c (0)
Location: net/socket.c:583
Inline: False
Direct callers:
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sock_create
  - net/socket.c:sock_close
  - net/socket.c:sock_create_lite
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff8190b860-ffffffff8190b904: __sock_release (STB_LOCAL)
ffffffff819112dc-ffffffff819112f4: __sock_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __sock_release(struct socket *sock, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/socket.c (ffffffff819e0965)
Location: net/socket.c:598
Inline: True
Direct callers:
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_accept4_file
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sock_create
  - net/socket.c:sock_close
  - net/socket.c:sock_create_lite
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff819dda50-ffffffff819ddaf4: __sock_release (STB_LOCAL)
ffffffff819e31ee-ffffffff819e3206: __sock_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __sock_release(struct socket *sock, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/socket.c (ffffffff819e01b5)
Location: net/socket.c:590
Inline: True
Direct callers:
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_accept4_file
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sock_create
  - net/socket.c:sock_close
  - net/socket.c:sock_create_lite
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff819dd440-ffffffff819dd4e4: __sock_release (STB_LOCAL)
ffffffff81c30334-ffffffff81c3034c: __sock_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __sock_release(struct socket *sock, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/socket.c (ffffffff819c6215)
Location: net/socket.c:592
Inline: True
Direct callers:
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_accept4_file
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sock_create
  - net/socket.c:sock_close
  - net/socket.c:sock_create_lite
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff819c3690-ffffffff819c3734: __sock_release (STB_LOCAL)
ffffffff81c22612-ffffffff81c2262a: __sock_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __sock_release(struct socket *sock, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/socket.c (ffffffff81a74de5)
Location: net/socket.c:642
Inline: True
Direct callers:
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sock_create
  - net/socket.c:sock_close
  - net/socket.c:sock_create_lite
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff81a72f20-ffffffff81a72fc4: __sock_release (STB_LOCAL)
ffffffff81d3497a-ffffffff81d34992: __sock_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __sock_release(struct socket *sock, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/socket.c (ffffffff81be7b15)
Location: net/socket.c:643
Inline: True
Direct callers:
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sys_socket_file
  - net/socket.c:__sock_create
  - net/socket.c:sock_close
  - net/socket.c:sock_create_lite
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff81be5880-ffffffff81be592e: __sock_release (STB_LOCAL)
ffffffff81f00ea6-ffffffff81f00ebe: __sock_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __sock_release(struct socket *sock, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d91b00)
Location: net/socket.c:645
Inline: True
Direct callers:
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sock_create
  - net/socket.c:sock_close
  - net/socket.c:sock_create_lite
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff81d91b00-ffffffff81d91bbd: __sock_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __sock_release(struct socket *sock, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81dffde0)
Location: net/socket.c:648
Inline: True
Direct callers:
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sock_create
  - net/socket.c:sock_close
  - net/socket.c:sock_create_lite
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff81dffde0-ffffffff81dffe9d: __sock_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __sock_release(struct socket *sock, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ebc280)
Location: net/socket.c:650
Inline: True
Direct callers:
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sock_create
  - net/socket.c:sock_close
  - net/socket.c:sock_create_lite
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff81ebc280-ffffffff81ebc33d: __sock_release (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __sock_release(struct socket *sock, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba0e08)
Location: net/socket.c:583
Inline: False
Direct callers:
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sock_create
  - net/socket.c:sock_close
  - net/socket.c:sock_create_lite
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffff800010ba0e08-ffff800010ba0ecc: __sock_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __sock_release(struct socket *sock, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc31c4)
Location: net/socket.c:583
Inline: False
Direct callers:
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sock_create
  - net/socket.c:sock_close
  - net/socket.c:sock_create_lite
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
c0cc31c4-c0cc328c: __sock_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __sock_release(struct socket *sock, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c74f00)
Location: net/socket.c:583
Inline: False
Direct callers:
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sock_create
  - net/socket.c:sock_close
  - net/socket.c:sock_create_lite
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
c000000000c74f00-c000000000c7504c: __sock_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __sock_release(struct socket *sock, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe000738b60)
Location: net/socket.c:583
Inline: False
Direct callers:
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sock_create
  - net/socket.c:sock_close
  - net/socket.c:sock_create_lite
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffe000738b60-ffffffe000738c08: __sock_release (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void __sock_release(struct socket *sock, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/socket.c (0)
Location: net/socket.c:583
Inline: False
Direct callers:
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sock_create
  - net/socket.c:sock_close
  - net/socket.c:sock_create_lite
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff818ab860-ffffffff818ab904: __sock_release (STB_LOCAL)
ffffffff818b12dc-ffffffff818b12f4: __sock_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void __sock_release(struct socket *sock, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/socket.c (0)
Location: net/socket.c:583
Inline: False
Direct callers:
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sock_create
  - net/socket.c:sock_close
  - net/socket.c:sock_create_lite
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff818657b0-ffffffff81865854: __sock_release (STB_LOCAL)
ffffffff8186b22c-ffffffff8186b244: __sock_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void __sock_release(struct socket *sock, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/socket.c (0)
Location: net/socket.c:583
Inline: False
Direct callers:
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sock_create
  - net/socket.c:sock_close
  - net/socket.c:sock_create_lite
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff818fc860-ffffffff818fc904: __sock_release (STB_LOCAL)
ffffffff819022dc-ffffffff819022f4: __sock_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void __sock_release(struct socket *sock, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/socket.c (0)
Location: net/socket.c:583
Inline: False
Direct callers:
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sock_create
  - net/socket.c:sock_close
  - net/socket.c:sock_create_lite
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff8191d8d0-ffffffff8191d974: __sock_release (STB_LOCAL)
ffffffff81923298-ffffffff819232b0: __sock_release.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
