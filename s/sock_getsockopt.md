# Function: <code>sock_getsockopt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sock_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817031d0)
Location: net/core/sock.c:1029
Inline: False
Direct callers:
  - net/socket.c:kernel_getsockopt
  - net/socket.c:SyS_socketcall
  - net/compat.c:compat_sock_getsockopt
  - net/compat.c:compat_sock_getsockopt
```
**Symbols:**

```
ffffffff817031d0-ffffffff81703912: sock_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sock_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81769c70)
Location: net/core/sock.c:1029
Inline: False
Direct callers:
  - net/socket.c:kernel_getsockopt
  - net/socket.c:SyS_socketcall
  - net/compat.c:compat_sock_getsockopt
  - net/compat.c:compat_sock_getsockopt
```
**Symbols:**

```
ffffffff81769c70-ffffffff8176a49e: sock_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sock_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81796d60)
Location: net/core/sock.c:1037
Inline: False
Direct callers:
  - net/socket.c:kernel_getsockopt
  - net/socket.c:SyS_socketcall
  - net/compat.c:compat_sock_getsockopt
  - net/compat.c:compat_sock_getsockopt
```
**Symbols:**

```
ffffffff81796d60-ffffffff8179758e: sock_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sock_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817b64a0)
Location: net/core/sock.c:1093
Inline: False
Direct callers:
  - net/socket.c:kernel_getsockopt
  - net/socket.c:SyS_socketcall
```
**Symbols:**

```
ffffffff817b64a0-ffffffff817b6e5a: sock_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sock_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8182ea60)
Location: net/core/sock.c:1097
Inline: False
Direct callers:
  - net/socket.c:kernel_getsockopt
  - net/socket.c:SyS_socketcall
```
**Symbols:**

```
ffffffff8182ea60-ffffffff8182f44c: sock_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int sock_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:1108
Inline: False
Direct callers:
  - net/socket.c:kernel_getsockopt
  - net/socket.c:__sys_getsockopt
  - net/compat.c:__compat_sys_getsockopt
  - net/compat.c:__compat_sys_getsockopt
```
**Symbols:**

```
ffffffff818798c5-ffffffff818798dd: sock_getsockopt.cold.66 (STB_LOCAL)
ffffffff81878ee0-ffffffff81879850: sock_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int sock_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:1093
Inline: False
Direct callers:
  - net/socket.c:kernel_getsockopt
  - net/socket.c:__sys_getsockopt
  - net/compat.c:__compat_sys_getsockopt
  - net/compat.c:__compat_sys_getsockopt
```
**Symbols:**

```
ffffffff8189a515-ffffffff8189a52d: sock_getsockopt.cold.65 (STB_LOCAL)
ffffffff81899890-ffffffff8189a4a0: sock_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int sock_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:1213
Inline: False
Direct callers:
  - net/socket.c:kernel_getsockopt
  - net/socket.c:__sys_getsockopt
  - net/compat.c:__compat_sys_getsockopt
```
**Symbols:**

```
ffffffff818e4beb-ffffffff818e4c03: sock_getsockopt.cold (STB_LOCAL)
ffffffff818e3e90-ffffffff818e4aa1: sock_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int sock_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:1215
Inline: False
Direct callers:
  - net/socket.c:kernel_getsockopt
  - net/socket.c:__sys_getsockopt
  - net/compat.c:__compat_sys_getsockopt
```
**Symbols:**

```
ffffffff81916d88-ffffffff81916da0: sock_getsockopt.cold (STB_LOCAL)
ffffffff81916070-ffffffff81916c79: sock_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int sock_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:1302
Inline: False
Direct callers:
  - net/socket.c:__sys_getsockopt
  - net/compat.c:__compat_sys_getsockopt
```
**Symbols:**

```
ffffffff819e96fd-ffffffff819e9715: sock_getsockopt.cold (STB_LOCAL)
ffffffff819e7260-ffffffff819e7ef0: sock_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int sock_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:1292
Inline: False
Direct callers:
  - net/socket.c:__sys_getsockopt
```
**Symbols:**

```
ffffffff81c3047c-ffffffff81c30494: sock_getsockopt.cold (STB_LOCAL)
ffffffff819e6ce0-ffffffff819e79b7: sock_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int sock_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:1308
Inline: False
Direct callers:
  - net/socket.c:__sys_getsockopt
```
**Symbols:**

```
ffffffff81c22754-ffffffff81c2276c: sock_getsockopt.cold (STB_LOCAL)
ffffffff819cccb0-ffffffff819cd98d: sock_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sock_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:1417
Inline: False
Direct callers:
  - net/socket.c:__sys_getsockopt
```
**Symbols:**

```
ffffffff81d34ba5-ffffffff81d34bbd: sock_getsockopt.cold (STB_LOCAL)
ffffffff81a7c410-ffffffff81a7d19a: sock_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sock_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:1539
Inline: False
Direct callers:
  - net/socket.c:__sys_getsockopt
```
**Symbols:**

```
ffffffff81f010f1-ffffffff81f01109: sock_getsockopt.cold (STB_LOCAL)
ffffffff81bf2660-ffffffff81bf33c9: sock_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sock_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81da10d0)
Location: net/core/sock.c:1963
Inline: False
Direct callers:
  - net/socket.c:__sys_getsockopt
```
**Symbols:**

```
ffffffff81da10d0-ffffffff81da1105: sock_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sock_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81e0f9a0)
Location: net/core/sock.c:2021
Inline: False
Direct callers:
  - net/socket.c:__sys_getsockopt
```
**Symbols:**

```
ffffffff81e0f9a0-ffffffff81e0f9d5: sock_getsockopt (STB_GLOBAL)
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int sock_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffff800010baf008)
Location: net/core/sock.c:1215
Inline: False
Direct callers:
  - net/socket.c:kernel_getsockopt
  - net/socket.c:__arm64_sys_getsockopt
  - net/compat.c:__compat_sys_getsockopt
```
**Symbols:**

```
ffff800010baf008-ffff800010bafe1c: sock_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sock_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c0cccb2c)
Location: net/core/sock.c:1215
Inline: False
Direct callers:
  - net/socket.c:kernel_getsockopt
  - net/socket.c:__se_sys_getsockopt
```
**Symbols:**

```
c0cccb2c-c0ccd730: sock_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sock_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c000000000c84d40)
Location: net/core/sock.c:1215
Inline: False
Direct callers:
  - net/socket.c:kernel_getsockopt
  - net/socket.c:__sys_getsockopt
  - net/compat.c:__compat_sys_getsockopt
```
**Symbols:**

```
c000000000c84d40-c000000000c85cf4: sock_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sock_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffe000740b22)
Location: net/core/sock.c:1215
Inline: False
Direct callers:
  - net/socket.c:kernel_getsockopt
  - net/socket.c:__se_sys_getsockopt
```
**Symbols:**

```
ffffffe000740b22-ffffffe0007411c2: sock_getsockopt (STB_GLOBAL)
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
int sock_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:1215
Inline: False
Direct callers:
  - net/socket.c:kernel_getsockopt
  - net/socket.c:__sys_getsockopt
  - net/compat.c:__compat_sys_getsockopt
```
**Symbols:**

```
ffffffff818b6d88-ffffffff818b6da0: sock_getsockopt.cold (STB_LOCAL)
ffffffff818b6070-ffffffff818b6c79: sock_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int sock_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:1215
Inline: False
Direct callers:
  - net/socket.c:kernel_getsockopt
  - net/socket.c:__sys_getsockopt
  - net/compat.c:__compat_sys_getsockopt
```
**Symbols:**

```
ffffffff81870cd8-ffffffff81870cf0: sock_getsockopt.cold (STB_LOCAL)
ffffffff8186ffc0-ffffffff81870bc9: sock_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int sock_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:1215
Inline: False
Direct callers:
  - net/socket.c:kernel_getsockopt
  - net/socket.c:__sys_getsockopt
  - net/compat.c:__compat_sys_getsockopt
```
**Symbols:**

```
ffffffff81907d88-ffffffff81907da0: sock_getsockopt.cold (STB_LOCAL)
ffffffff81907070-ffffffff81907c79: sock_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int sock_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:1215
Inline: False
Direct callers:
  - net/socket.c:kernel_getsockopt
  - net/socket.c:__sys_getsockopt
  - net/compat.c:__compat_sys_getsockopt
```
**Symbols:**

```
ffffffff81928db9-ffffffff81928dd1: sock_getsockopt.cold (STB_LOCAL)
ffffffff819280a0-ffffffff81928caa: sock_getsockopt (STB_GLOBAL)
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
