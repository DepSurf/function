# Function: <code>kernel_setsockopt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kernel_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff816fd850)
Location: net/socket.c:3249
Inline: False
```
**Symbols:**

```
ffffffff816fd850-ffffffff816fd89b: kernel_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kernel_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81764380)
Location: net/socket.c:3251
Inline: False
```
**Symbols:**

```
ffffffff81764380-ffffffff817643cb: kernel_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kernel_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817913b0)
Location: net/socket.c:3299
Inline: False
```
**Symbols:**

```
ffffffff817913b0-ffffffff817913fb: kernel_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kernel_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817aeee0)
Location: net/socket.c:3349
Inline: False
```
**Symbols:**

```
ffffffff817aeee0-ffffffff817aef2b: kernel_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kernel_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81826fd0)
Location: net/socket.c:3351
Inline: False
```
**Symbols:**

```
ffffffff81826fd0-ffffffff8182702b: kernel_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kernel_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81870230)
Location: net/socket.c:3315
Inline: False
```
**Symbols:**

```
ffffffff81870230-ffffffff8187028b: kernel_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kernel_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81890e00)
Location: net/socket.c:3381
Inline: False
```
**Symbols:**

```
ffffffff81890e00-ffffffff81890e5b: kernel_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kernel_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818db6f0)
Location: net/socket.c:3647
Inline: False
```
**Symbols:**

```
ffffffff818db6f0-ffffffff818db74b: kernel_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kernel_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8190de40)
Location: net/socket.c:3728
Inline: False
```
**Symbols:**

```
ffffffff8190de40-ffffffff8190de9b: kernel_setsockopt (STB_GLOBAL)
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
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
int kernel_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba2cf8)
Location: net/socket.c:3728
Inline: False
```
**Symbols:**

```
ffff800010ba2cf8-ffff800010ba2e04: kernel_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kernel_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc3c70)
Location: net/socket.c:3728
Inline: False
```
**Symbols:**

```
c0cc3c70-c0cc3cf4: kernel_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kernel_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c76440)
Location: net/socket.c:3728
Inline: False
```
**Symbols:**

```
c000000000c76440-c000000000c76520: kernel_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kernel_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe000739d0a)
Location: net/socket.c:3728
Inline: False
```
**Symbols:**

```
ffffffe000739d0a-ffffffe000739d80: kernel_setsockopt (STB_GLOBAL)
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
int kernel_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818ade40)
Location: net/socket.c:3728
Inline: False
```
**Symbols:**

```
ffffffff818ade40-ffffffff818ade9b: kernel_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kernel_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81867d90)
Location: net/socket.c:3728
Inline: False
Direct callers:
  - net/ipv4/udp_tunnel.c:udp_sock_create4
  - net/ipv6/ip6_udp_tunnel.c:udp_sock_create6
  - net/ipv6/ip6_udp_tunnel.c:udp_sock_create6
```
**Symbols:**

```
ffffffff81867d90-ffffffff81867deb: kernel_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kernel_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818fee40)
Location: net/socket.c:3728
Inline: False
```
**Symbols:**

```
ffffffff818fee40-ffffffff818fee9b: kernel_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kernel_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8191fe30)
Location: net/socket.c:3728
Inline: False
```
**Symbols:**

```
ffffffff8191fe30-ffffffff8191fe8b: kernel_setsockopt (STB_GLOBAL)
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
