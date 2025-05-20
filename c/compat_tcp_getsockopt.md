# Function: <code>compat_tcp_getsockopt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int compat_tcp_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81767f70)
Location: net/ipv4/tcp.c:2927
Inline: False
```
**Symbols:**

```
ffffffff81767f70-ffffffff81767f98: compat_tcp_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int compat_tcp_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff817d4570)
Location: net/ipv4/tcp.c:3003
Inline: False
```
**Symbols:**

```
ffffffff817d4570-ffffffff817d4598: compat_tcp_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int compat_tcp_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818042b0)
Location: net/ipv4/tcp.c:3096
Inline: False
```
**Symbols:**

```
ffffffff818042b0-ffffffff818042d8: compat_tcp_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int compat_tcp_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81823a50)
Location: net/ipv4/tcp.c:3206
Inline: False
```
**Symbols:**

```
ffffffff81823a50-ffffffff81823a78: compat_tcp_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int compat_tcp_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818a3500)
Location: net/ipv4/tcp.c:3342
Inline: False
```
**Symbols:**

```
ffffffff818a3500-ffffffff818a3528: compat_tcp_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int compat_tcp_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818f8730)
Location: net/ipv4/tcp.c:3557
Inline: False
```
**Symbols:**

```
ffffffff818f8730-ffffffff818f8758: compat_tcp_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int compat_tcp_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819252f0)
Location: net/ipv4/tcp.c:3603
Inline: False
```
**Symbols:**

```
ffffffff819252f0-ffffffff81925318: compat_tcp_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int compat_tcp_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81988900)
Location: net/ipv4/tcp.c:3682
Inline: False
```
**Symbols:**

```
ffffffff81988900-ffffffff8198892b: compat_tcp_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int compat_tcp_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819bfd50)
Location: net/ipv4/tcp.c:3700
Inline: False
```
**Symbols:**

```
ffffffff819bfd50-ffffffff819bfd7b: compat_tcp_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int compat_tcp_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aab050)
Location: net/ipv4/tcp.c:3892
Inline: True
```
**Symbols:**

```
ffffffff81aab050-ffffffff81aab07b: compat_tcp_getsockopt (STB_GLOBAL)
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
int compat_tcp_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffff800010c73e80)
Location: net/ipv4/tcp.c:3700
Inline: False
```
**Symbols:**

```
ffff800010c73e80-ffff800010c73f0c: compat_tcp_getsockopt (STB_GLOBAL)
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
int compat_tcp_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (c000000000d7a060)
Location: net/ipv4/tcp.c:3700
Inline: False
```
**Symbols:**

```
c000000000d7a060-c000000000d7a0b8: compat_tcp_getsockopt (STB_GLOBAL)
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
int compat_tcp_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff8195fbc0)
Location: net/ipv4/tcp.c:3700
Inline: False
```
**Symbols:**

```
ffffffff8195fbc0-ffffffff8195fbeb: compat_tcp_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int compat_tcp_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819196b0)
Location: net/ipv4/tcp.c:3700
Inline: False
```
**Symbols:**

```
ffffffff819196b0-ffffffff819196db: compat_tcp_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int compat_tcp_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819ca390)
Location: net/ipv4/tcp.c:3700
Inline: False
```
**Symbols:**

```
ffffffff819ca390-ffffffff819ca3bb: compat_tcp_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int compat_tcp_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819d3f00)
Location: net/ipv4/tcp.c:3700
Inline: False
```
**Symbols:**

```
ffffffff819d3f00-ffffffff819d3f2b: compat_tcp_getsockopt (STB_GLOBAL)
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
