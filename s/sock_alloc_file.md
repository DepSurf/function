# Function: <code>sock_alloc_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct file *sock_alloc_file(struct socket *sock, int flags, const char *dname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff816fb860)
Location: net/socket.c:355
Inline: False
Direct callers:
  - net/socket.c:sock_map_fd
  - net/socket.c:SYSC_accept4
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
```
**Symbols:**

```
ffffffff816fb860-ffffffff816fb98f: sock_alloc_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct file *sock_alloc_file(struct socket *sock, int flags, const char *dname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817622c0)
Location: net/socket.c:355
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SYSC_accept4
  - net/socket.c:sock_map_fd
```
**Symbols:**

```
ffffffff817622c0-ffffffff817623f0: sock_alloc_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct file *sock_alloc_file(struct socket *sock, int flags, const char *dname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8178f2f0)
Location: net/socket.c:397
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SYSC_accept4
  - net/socket.c:sock_map_fd
```
**Symbols:**

```
ffffffff8178f2f0-ffffffff8178f420: sock_alloc_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct file *sock_alloc_file(struct socket *sock, int flags, const char *dname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817adba0)
Location: net/socket.c:395
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SYSC_accept4
  - net/socket.c:sock_map_fd
```
**Symbols:**

```
ffffffff817adba0-ffffffff817adcd0: sock_alloc_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct file *sock_alloc_file(struct socket *sock, int flags, const char *dname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81825df0)
Location: net/socket.c:395
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SYSC_accept4
  - net/socket.c:sock_map_fd
```
**Symbols:**

```
ffffffff81825df0-ffffffff81825f32: sock_alloc_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct file *sock_alloc_file(struct socket *sock, int flags, const char *dname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8186f560)
Location: net/socket.c:389
Inline: False
Direct callers:
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
```
**Symbols:**

```
ffffffff8186f560-ffffffff8186f6a9: sock_alloc_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct file *sock_alloc_file(struct socket *sock, int flags, const char *dname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8188f910)
Location: net/socket.c:387
Inline: False
Direct callers:
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
```
**Symbols:**

```
ffffffff8188f910-ffffffff8188f99b: sock_alloc_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct file *sock_alloc_file(struct socket *sock, int flags, const char *dname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818d9970)
Location: net/socket.c:390
Inline: False
Direct callers:
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
```
**Symbols:**

```
ffffffff818d9970-ffffffff818d9a03: sock_alloc_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct file *sock_alloc_file(struct socket *sock, int flags, const char *dname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8190b950)
Location: net/socket.c:390
Inline: False
Direct callers:
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
```
**Symbols:**

```
ffffffff8190b950-ffffffff8190b9e3: sock_alloc_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct file *sock_alloc_file(struct socket *sock, int flags, const char *dname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819ddb20)
Location: net/socket.c:404
Inline: False
Direct callers:
  - net/socket.c:__sys_accept4_file
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
```
**Symbols:**

```
ffffffff819ddb20-ffffffff819ddbc0: sock_alloc_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct file *sock_alloc_file(struct socket *sock, int flags, const char *dname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819dd510)
Location: net/socket.c:404
Inline: False
Direct callers:
  - net/socket.c:__sys_accept4_file
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
```
**Symbols:**

```
ffffffff819dd510-ffffffff819dd5b0: sock_alloc_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct file *sock_alloc_file(struct socket *sock, int flags, const char *dname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c3760)
Location: net/socket.c:405
Inline: False
Direct callers:
  - net/socket.c:__sys_accept4_file
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
```
**Symbols:**

```
ffffffff819c3760-ffffffff819c3800: sock_alloc_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct file *sock_alloc_file(struct socket *sock, int flags, const char *dname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a72ff0)
Location: net/socket.c:455
Inline: False
Direct callers:
  - net/socket.c:do_accept
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
```
**Symbols:**

```
ffffffff81a72ff0-ffffffff81a73090: sock_alloc_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct file *sock_alloc_file(struct socket *sock, int flags, const char *dname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be5960)
Location: net/socket.c:456
Inline: False
Direct callers:
  - net/socket.c:do_accept
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sys_socket_file
```
**Symbols:**

```
ffffffff81be5960-ffffffff81be5a20: sock_alloc_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct file *sock_alloc_file(struct socket *sock, int flags, const char *dname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d91c10)
Location: net/socket.c:458
Inline: False
Direct callers:
  - net/socket.c:do_accept
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sys_socket_file
```
**Symbols:**

```
ffffffff81d91c10-ffffffff81d91cd0: sock_alloc_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct file *sock_alloc_file(struct socket *sock, int flags, const char *dname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81dffef0)
Location: net/socket.c:460
Inline: False
Direct callers:
  - net/socket.c:do_accept
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sys_socket_file
```
**Symbols:**

```
ffffffff81dffef0-ffffffff81dfffb7: sock_alloc_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct file *sock_alloc_file(struct socket *sock, int flags, const char *dname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ebc390)
Location: net/socket.c:462
Inline: False
Direct callers:
  - net/socket.c:do_accept
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sys_socket_file
```
**Symbols:**

```
ffffffff81ebc390-ffffffff81ebc457: sock_alloc_file (STB_GLOBAL)
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
struct file *sock_alloc_file(struct socket *sock, int flags, const char *dname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba0f38)
Location: net/socket.c:390
Inline: False
Direct callers:
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
```
**Symbols:**

```
ffff800010ba0f38-ffff800010ba0fec: sock_alloc_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct file *sock_alloc_file(struct socket *sock, int flags, const char *dname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc32d4)
Location: net/socket.c:390
Inline: False
Direct callers:
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
```
**Symbols:**

```
c0cc32d4-c0cc3374: sock_alloc_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct file *sock_alloc_file(struct socket *sock, int flags, const char *dname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c750b0)
Location: net/socket.c:390
Inline: False
Direct callers:
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
```
**Symbols:**

```
c000000000c750b0-c000000000c751bc: sock_alloc_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct file *sock_alloc_file(struct socket *sock, int flags, const char *dname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe000738c64)
Location: net/socket.c:390
Inline: False
Direct callers:
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
```
**Symbols:**

```
ffffffe000738c64-ffffffe000738d04: sock_alloc_file (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct file *sock_alloc_file(struct socket *sock, int flags, const char *dname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818ab950)
Location: net/socket.c:390
Inline: False
Direct callers:
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
```
**Symbols:**

```
ffffffff818ab950-ffffffff818ab9e3: sock_alloc_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct file *sock_alloc_file(struct socket *sock, int flags, const char *dname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818658a0)
Location: net/socket.c:390
Inline: False
Direct callers:
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
```
**Symbols:**

```
ffffffff818658a0-ffffffff81865933: sock_alloc_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct file *sock_alloc_file(struct socket *sock, int flags, const char *dname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818fc950)
Location: net/socket.c:390
Inline: False
Direct callers:
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
```
**Symbols:**

```
ffffffff818fc950-ffffffff818fc9e3: sock_alloc_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct file *sock_alloc_file(struct socket *sock, int flags, const char *dname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8191d9c0)
Location: net/socket.c:390
Inline: False
Direct callers:
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
```
**Symbols:**

```
ffffffff8191d9c0-ffffffff8191da53: sock_alloc_file (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
