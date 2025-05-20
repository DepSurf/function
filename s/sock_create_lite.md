# Function: <code>sock_create_lite</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sock_create_lite(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff816fcec0)
Location: net/socket.c:961
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_kernel_create
```
**Symbols:**

```
ffffffff816fcec0-ffffffff816fcf49: sock_create_lite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sock_create_lite(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81763b50)
Location: net/socket.c:958
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_kernel_create
```
**Symbols:**

```
ffffffff81763b50-ffffffff81763bd9: sock_create_lite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sock_create_lite(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81790b80)
Location: net/socket.c:1001
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_kernel_create
```
**Symbols:**

```
ffffffff81790b80-ffffffff81790c09: sock_create_lite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sock_create_lite(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817ae4a0)
Location: net/socket.c:1050
Inline: False
Direct callers:
  - net/socket.c:kernel_accept
  - net/netlink/af_netlink.c:__netlink_kernel_create
```
**Symbols:**

```
ffffffff817ae4a0-ffffffff817ae529: sock_create_lite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sock_create_lite(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81826570)
Location: net/socket.c:1069
Inline: False
Direct callers:
  - net/socket.c:kernel_accept
  - net/netlink/af_netlink.c:__netlink_kernel_create
```
**Symbols:**

```
ffffffff81826570-ffffffff818265f9: sock_create_lite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sock_create_lite(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8186fca0)
Location: net/socket.c:1102
Inline: False
Direct callers:
  - net/socket.c:kernel_accept
  - net/netlink/af_netlink.c:__netlink_kernel_create
```
**Symbols:**

```
ffffffff8186fca0-ffffffff8186fd2c: sock_create_lite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sock_create_lite(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81890870)
Location: net/socket.c:1080
Inline: False
Direct callers:
  - net/socket.c:kernel_accept
  - net/netlink/af_netlink.c:__netlink_kernel_create
```
**Symbols:**

```
ffffffff81890870-ffffffff818908fc: sock_create_lite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sock_create_lite(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818da770)
Location: net/socket.c:1208
Inline: False
Direct callers:
  - net/socket.c:kernel_accept
  - net/netlink/af_netlink.c:__netlink_kernel_create
```
**Symbols:**

```
ffffffff818da770-ffffffff818da7fe: sock_create_lite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sock_create_lite(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8190c8c0)
Location: net/socket.c:1208
Inline: False
Direct callers:
  - net/socket.c:kernel_accept
  - net/netlink/af_netlink.c:__netlink_kernel_create
```
**Symbols:**

```
ffffffff8190c8c0-ffffffff8190c94e: sock_create_lite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sock_create_lite(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819de630)
Location: net/socket.c:1218
Inline: False
Direct callers:
  - net/socket.c:kernel_accept
  - net/netlink/af_netlink.c:__netlink_kernel_create
```
**Symbols:**

```
ffffffff819de630-ffffffff819de6be: sock_create_lite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sock_create_lite(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819de070)
Location: net/socket.c:1196
Inline: False
Direct callers:
  - net/socket.c:kernel_accept
  - net/netlink/af_netlink.c:__netlink_kernel_create
```
**Symbols:**

```
ffffffff819de070-ffffffff819de0fe: sock_create_lite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sock_create_lite(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c4080)
Location: net/socket.c:1187
Inline: False
Direct callers:
  - net/socket.c:kernel_accept
  - net/netlink/af_netlink.c:__netlink_kernel_create
```
**Symbols:**

```
ffffffff819c4080-ffffffff819c410e: sock_create_lite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sock_create_lite(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a73320)
Location: net/socket.c:1257
Inline: False
Direct callers:
  - net/socket.c:kernel_accept
  - net/netlink/af_netlink.c:__netlink_kernel_create
```
**Symbols:**

```
ffffffff81a73320-ffffffff81a733ae: sock_create_lite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sock_create_lite(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be5de0)
Location: net/socket.c:1305
Inline: False
Direct callers:
  - net/socket.c:kernel_accept
  - net/netlink/af_netlink.c:__netlink_kernel_create
```
**Symbols:**

```
ffffffff81be5de0-ffffffff81be5e7a: sock_create_lite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sock_create_lite(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d91ff0)
Location: net/socket.c:1310
Inline: False
Direct callers:
  - net/socket.c:kernel_accept
  - net/netlink/af_netlink.c:__netlink_kernel_create
```
**Symbols:**

```
ffffffff81d91ff0-ffffffff81d9208a: sock_create_lite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sock_create_lite(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e003a0)
Location: net/socket.c:1338
Inline: False
Direct callers:
  - net/socket.c:kernel_accept
  - net/netlink/af_netlink.c:__netlink_kernel_create
```
**Symbols:**

```
ffffffff81e003a0-ffffffff81e0043a: sock_create_lite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sock_create_lite(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ebc900)
Location: net/socket.c:1360
Inline: False
Direct callers:
  - net/socket.c:kernel_accept
  - net/netlink/af_netlink.c:__netlink_kernel_create
```
**Symbols:**

```
ffffffff81ebc900-ffffffff81ebc99a: sock_create_lite (STB_GLOBAL)
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
int sock_create_lite(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba1790)
Location: net/socket.c:1208
Inline: False
Direct callers:
  - net/socket.c:kernel_accept
  - net/netlink/af_netlink.c:__netlink_kernel_create
```
**Symbols:**

```
ffff800010ba1790-ffff800010ba1840: sock_create_lite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sock_create_lite(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc376c)
Location: net/socket.c:1208
Inline: False
Direct callers:
  - net/socket.c:kernel_accept
  - net/netlink/af_netlink.c:__netlink_kernel_create
```
**Symbols:**

```
c0cc376c-c0cc3804: sock_create_lite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sock_create_lite(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c75d70)
Location: net/socket.c:1208
Inline: False
Direct callers:
  - net/socket.c:kernel_accept
  - net/netlink/af_netlink.c:__netlink_kernel_create
```
**Symbols:**

```
c000000000c75d70-c000000000c75e4c: sock_create_lite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sock_create_lite(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe00073989a)
Location: net/socket.c:1208
Inline: False
Direct callers:
  - net/socket.c:kernel_accept
  - net/netlink/af_netlink.c:__netlink_kernel_create
```
**Symbols:**

```
ffffffe00073989a-ffffffe000739928: sock_create_lite (STB_GLOBAL)
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
int sock_create_lite(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818ac8c0)
Location: net/socket.c:1208
Inline: False
Direct callers:
  - net/socket.c:kernel_accept
  - net/netlink/af_netlink.c:__netlink_kernel_create
```
**Symbols:**

```
ffffffff818ac8c0-ffffffff818ac94e: sock_create_lite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sock_create_lite(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81866810)
Location: net/socket.c:1208
Inline: False
Direct callers:
  - net/socket.c:kernel_accept
  - net/netlink/af_netlink.c:__netlink_kernel_create
```
**Symbols:**

```
ffffffff81866810-ffffffff8186689e: sock_create_lite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sock_create_lite(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818fd8c0)
Location: net/socket.c:1208
Inline: False
Direct callers:
  - net/socket.c:kernel_accept
  - net/netlink/af_netlink.c:__netlink_kernel_create
```
**Symbols:**

```
ffffffff818fd8c0-ffffffff818fd94e: sock_create_lite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sock_create_lite(int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8191e940)
Location: net/socket.c:1208
Inline: False
Direct callers:
  - net/socket.c:kernel_accept
  - net/netlink/af_netlink.c:__netlink_kernel_create
```
**Symbols:**

```
ffffffff8191e940-ffffffff8191e9ce: sock_create_lite (STB_GLOBAL)
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
