# Function: <code>compat_mc_getsockopt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int compat_mc_getsockopt(struct sock *sock, int level, int optname, char *optval, int *optlen, int (*getsockopt)(struct sock *, int, int, char *, int *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/compat.c (ffffffff8173e820)
Location: net/compat.c:628
Inline: True
```
**Symbols:**

```
ffffffff8173e820-ffffffff8173eac2: compat_mc_getsockopt.part.3 (STB_LOCAL)
ffffffff8173ead0-ffffffff8173eaef: compat_mc_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int compat_mc_getsockopt(struct sock *sock, int level, int optname, char *optval, int *optlen, int (*getsockopt)(struct sock *, int, int, char *, int *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/compat.c (ffffffff817ab4b0)
Location: net/compat.c:642
Inline: True
```
**Symbols:**

```
ffffffff817ab4b0-ffffffff817ab77a: compat_mc_getsockopt.part.5 (STB_LOCAL)
ffffffff817ab780-ffffffff817ab79f: compat_mc_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
int compat_mc_getsockopt(struct sock *sock, int level, int optname, char *optval, int *optlen, int (*getsockopt)(struct sock *, int, int, char *, int *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/compat.c (ffffffff817daad0)
Location: net/compat.c:642
Inline: True
```
**Symbols:**

```
ffffffff817daad0-ffffffff817dad9a: compat_mc_getsockopt.part.5 (STB_LOCAL)
ffffffff817dada0-ffffffff817dadbf: compat_mc_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int compat_mc_getsockopt(struct sock *sock, int level, int optname, char *optval, int *optlen, int (*getsockopt)(struct sock *, int, int, char *, int *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/compat.c (ffffffff817fa400)
Location: net/compat.c:641
Inline: True
```
**Symbols:**

```
ffffffff817fa400-ffffffff817fa72a: compat_mc_getsockopt.part.2 (STB_LOCAL)
ffffffff817fa730-ffffffff817fa759: compat_mc_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int compat_mc_getsockopt(struct sock *sock, int level, int optname, char *optval, int *optlen, int (*getsockopt)(struct sock *, int, int, char *, int *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/compat.c (ffffffff81877d50)
Location: net/compat.c:648
Inline: True
```
**Symbols:**

```
ffffffff81877d50-ffffffff81878094: compat_mc_getsockopt.part.2 (STB_LOCAL)
ffffffff818780a0-ffffffff818780cb: compat_mc_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int compat_mc_getsockopt(struct sock *sock, int level, int optname, char *optval, int *optlen, int (*getsockopt)(struct sock *, int, int, char *, int *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/compat.c (ffffffff818c9930)
Location: net/compat.c:663
Inline: True
Direct callers:
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
```
**Symbols:**

```
ffffffff818c9930-ffffffff818c9c78: compat_mc_getsockopt.part.3 (STB_LOCAL)
ffffffff818c9c80-ffffffff818c9cab: compat_mc_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int compat_mc_getsockopt(struct sock *sock, int level, int optname, char *optval, int *optlen, int (*getsockopt)(struct sock *, int, int, char *, int *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/compat.c (ffffffff818f4830)
Location: net/compat.c:668
Inline: True
Direct callers:
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
```
**Symbols:**

```
ffffffff818f4830-ffffffff818f4be4: compat_mc_getsockopt.part.3 (STB_LOCAL)
ffffffff818f4bf0-ffffffff818f4c1b: compat_mc_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int compat_mc_getsockopt(struct sock *sock, int level, int optname, char *optval, int *optlen, int (*getsockopt)(struct sock *, int, int, char *, int *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/compat.c (ffffffff81954640)
Location: net/compat.c:549
Inline: True
Direct callers:
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
```
**Symbols:**

```
ffffffff81954640-ffffffff819549f9: compat_mc_getsockopt.part.0 (STB_LOCAL)
ffffffff81954a00-ffffffff81954a2b: compat_mc_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int compat_mc_getsockopt(struct sock *sock, int level, int optname, char *optval, int *optlen, int (*getsockopt)(struct sock *, int, int, char *, int *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/compat.c (ffffffff8198ab00)
Location: net/compat.c:549
Inline: True
Direct callers:
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
```
**Symbols:**

```
ffffffff8198ab00-ffffffff8198ae11: compat_mc_getsockopt.part.0 (STB_LOCAL)
ffffffff8198ae20-ffffffff8198ae4b: compat_mc_getsockopt (STB_GLOBAL)
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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int compat_mc_getsockopt(struct sock *sock, int level, int optname, char *optval, int *optlen, int (*getsockopt)(struct sock *, int, int, char *, int *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/compat.c (ffff800010c33298)
Location: net/compat.c:549
Inline: True
Direct callers:
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
```
**Symbols:**

```
ffff800010c33298-ffff800010c33f8c: compat_mc_getsockopt.part.0 (STB_LOCAL)
ffff800010c33f90-ffff800010c34024: compat_mc_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int compat_mc_getsockopt(struct sock *sock, int level, int optname, char *optval, int *optlen, int (*getsockopt)(struct sock *, int, int, char *, int *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/compat.c (c000000000d2c3b0)
Location: net/compat.c:549
Inline: True
Direct callers:
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
```
**Symbols:**

```
c000000000d2c3b0-c000000000d2cce0: compat_mc_getsockopt.part.0 (STB_LOCAL)
c000000000d2cce0-c000000000d2cd48: compat_mc_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int compat_mc_getsockopt(struct sock *sock, int level, int optname, char *optval, int *optlen, int (*getsockopt)(struct sock *, int, int, char *, int *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/compat.c (ffffffff8192a970)
Location: net/compat.c:549
Inline: True
Direct callers:
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
```
**Symbols:**

```
ffffffff8192a970-ffffffff8192ac81: compat_mc_getsockopt.part.0 (STB_LOCAL)
ffffffff8192ac90-ffffffff8192acbb: compat_mc_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int compat_mc_getsockopt(struct sock *sock, int level, int optname, char *optval, int *optlen, int (*getsockopt)(struct sock *, int, int, char *, int *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/compat.c (ffffffff818e4720)
Location: net/compat.c:549
Inline: True
Direct callers:
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
```
**Symbols:**

```
ffffffff818e4720-ffffffff818e4a31: compat_mc_getsockopt.part.0 (STB_LOCAL)
ffffffff818e4a40-ffffffff818e4a6b: compat_mc_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int compat_mc_getsockopt(struct sock *sock, int level, int optname, char *optval, int *optlen, int (*getsockopt)(struct sock *, int, int, char *, int *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/compat.c (ffffffff8197bb00)
Location: net/compat.c:549
Inline: True
Direct callers:
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
```
**Symbols:**

```
ffffffff8197bb00-ffffffff8197be11: compat_mc_getsockopt.part.0 (STB_LOCAL)
ffffffff8197be20-ffffffff8197be4b: compat_mc_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int compat_mc_getsockopt(struct sock *sock, int level, int optname, char *optval, int *optlen, int (*getsockopt)(struct sock *, int, int, char *, int *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/compat.c (ffffffff8199e050)
Location: net/compat.c:549
Inline: True
Direct callers:
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
```
**Symbols:**

```
ffffffff8199e050-ffffffff8199e361: compat_mc_getsockopt.part.0 (STB_LOCAL)
ffffffff8199e370-ffffffff8199e39b: compat_mc_getsockopt (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
