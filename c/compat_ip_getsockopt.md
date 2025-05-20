# Function: <code>compat_ip_getsockopt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int compat_ip_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff817604c0)
Location: net/ipv4/ip_sockglue.c:1536
Inline: True
Direct callers:
  - net/ipv4/udp.c:compat_udp_getsockopt
```
**Symbols:**

```
ffffffff817604c0-ffffffff817605a0: compat_ip_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int compat_ip_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff817cc7b0)
Location: net/ipv4/ip_sockglue.c:1554
Inline: True
Direct callers:
  - net/ipv4/udp.c:compat_udp_getsockopt
```
**Symbols:**

```
ffffffff817cc7b0-ffffffff817cc88e: compat_ip_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int compat_ip_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff817fc4b0)
Location: net/ipv4/ip_sockglue.c:1597
Inline: True
Direct callers:
  - net/ipv4/udp.c:compat_udp_getsockopt
```
**Symbols:**

```
ffffffff817fc4b0-ffffffff817fc58e: compat_ip_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int compat_ip_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff8181c850)
Location: net/ipv4/ip_sockglue.c:1586
Inline: True
Direct callers:
  - net/ipv4/udp.c:compat_udp_getsockopt
```
**Symbols:**

```
ffffffff8181c850-ffffffff8181c92e: compat_ip_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int compat_ip_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff8189b7a0)
Location: net/ipv4/ip_sockglue.c:1579
Inline: True
Direct callers:
  - net/ipv4/udp.c:compat_udp_getsockopt
```
**Symbols:**

```
ffffffff8189b7a0-ffffffff8189b862: compat_ip_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int compat_ip_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff818efce0)
Location: net/ipv4/ip_sockglue.c:1588
Inline: False
Direct callers:
  - net/ipv4/udp.c:compat_udp_getsockopt
```
**Symbols:**

```
ffffffff818efce0-ffffffff818efdc0: compat_ip_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int compat_ip_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff8191d5d0)
Location: net/ipv4/ip_sockglue.c:1585
Inline: False
Direct callers:
  - net/ipv4/udp.c:compat_udp_getsockopt
```
**Symbols:**

```
ffffffff8191d5d0-ffffffff8191d6b0: compat_ip_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int compat_ip_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff8197f930)
Location: net/ipv4/ip_sockglue.c:1587
Inline: False
Direct callers:
  - net/ipv4/udp.c:compat_udp_getsockopt
```
**Symbols:**

```
ffffffff8197f930-ffffffff8197fa1a: compat_ip_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int compat_ip_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff819b5da0)
Location: net/ipv4/ip_sockglue.c:1587
Inline: False
Direct callers:
  - net/ipv4/udp.c:compat_udp_getsockopt
```
**Symbols:**

```
ffffffff819b5da0-ffffffff819b5ea9: compat_ip_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int compat_ip_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81aa04a0)
Location: net/ipv4/ip_sockglue.c:1760
Inline: False
Direct callers:
  - net/ipv4/udp.c:compat_udp_getsockopt
```
**Symbols:**

```
ffffffff81aa04a0-ffffffff81aa078b: compat_ip_getsockopt (STB_GLOBAL)
```
</details>
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
int compat_ip_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffff800010c674e0)
Location: net/ipv4/ip_sockglue.c:1587
Inline: False
Direct callers:
  - net/ipv4/udp.c:compat_udp_getsockopt
```
**Symbols:**

```
ffff800010c674e0-ffff800010c6785c: compat_ip_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int compat_ip_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (c000000000d6b700)
Location: net/ipv4/ip_sockglue.c:1587
Inline: False
Direct callers:
  - net/ipv4/udp.c:compat_udp_getsockopt
```
**Symbols:**

```
c000000000d6b700-c000000000d6b984: compat_ip_getsockopt (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int compat_ip_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81955c10)
Location: net/ipv4/ip_sockglue.c:1587
Inline: False
Direct callers:
  - net/ipv4/udp.c:compat_udp_getsockopt
```
**Symbols:**

```
ffffffff81955c10-ffffffff81955d19: compat_ip_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int compat_ip_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff8190f700)
Location: net/ipv4/ip_sockglue.c:1587
Inline: False
Direct callers:
  - net/ipv4/udp.c:compat_udp_getsockopt
```
**Symbols:**

```
ffffffff8190f700-ffffffff8190f809: compat_ip_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int compat_ip_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff819c03e0)
Location: net/ipv4/ip_sockglue.c:1587
Inline: False
Direct callers:
  - net/ipv4/udp.c:compat_udp_getsockopt
```
**Symbols:**

```
ffffffff819c03e0-ffffffff819c04e9: compat_ip_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int compat_ip_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff819c9dc0)
Location: net/ipv4/ip_sockglue.c:1587
Inline: False
Direct callers:
  - net/ipv4/udp.c:compat_udp_getsockopt
```
**Symbols:**

```
ffffffff819c9dc0-ffffffff819c9ec9: compat_ip_getsockopt (STB_GLOBAL)
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
