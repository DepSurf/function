# Function: <code>compat_tcp_setsockopt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int compat_tcp_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81768bd0)
Location: net/ipv4/tcp.c:2623
Inline: False
```
**Symbols:**

```
ffffffff81768bd0-ffffffff81768bf8: compat_tcp_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int compat_tcp_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff817d5530)
Location: net/ipv4/tcp.c:2668
Inline: False
```
**Symbols:**

```
ffffffff817d5530-ffffffff817d5558: compat_tcp_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int compat_tcp_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818054e0)
Location: net/ipv4/tcp.c:2706
Inline: False
```
**Symbols:**

```
ffffffff818054e0-ffffffff81805508: compat_tcp_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int compat_tcp_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81825c30)
Location: net/ipv4/tcp.c:2791
Inline: False
```
**Symbols:**

```
ffffffff81825c30-ffffffff81825c58: compat_tcp_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int compat_tcp_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818a2d50)
Location: net/ipv4/tcp.c:2888
Inline: False
```
**Symbols:**

```
ffffffff818a2d50-ffffffff818a2d78: compat_tcp_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int compat_tcp_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818f96e0)
Location: net/ipv4/tcp.c:3072
Inline: False
```
**Symbols:**

```
ffffffff818f96e0-ffffffff818f9708: compat_tcp_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int compat_tcp_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81927610)
Location: net/ipv4/tcp.c:3080
Inline: False
```
**Symbols:**

```
ffffffff81927610-ffffffff81927638: compat_tcp_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int compat_tcp_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff8198a7b0)
Location: net/ipv4/tcp.c:3153
Inline: False
```
**Symbols:**

```
ffffffff8198a7b0-ffffffff8198a7db: compat_tcp_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int compat_tcp_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819bed50)
Location: net/ipv4/tcp.c:3169
Inline: False
```
**Symbols:**

```
ffffffff819bed50-ffffffff819bed7b: compat_tcp_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int compat_tcp_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aac510)
Location: net/ipv4/tcp.c:3341
Inline: True
```
**Symbols:**

```
ffffffff81aac510-ffffffff81aac53b: compat_tcp_setsockopt (STB_GLOBAL)
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
int compat_tcp_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffff800010c72780)
Location: net/ipv4/tcp.c:3169
Inline: False
```
**Symbols:**

```
ffff800010c72780-ffff800010c7280c: compat_tcp_setsockopt (STB_GLOBAL)
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
int compat_tcp_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (c000000000d7ae20)
Location: net/ipv4/tcp.c:3169
Inline: False
```
**Symbols:**

```
c000000000d7ae20-c000000000d7ae78: compat_tcp_setsockopt (STB_GLOBAL)
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
int compat_tcp_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff8195ebc0)
Location: net/ipv4/tcp.c:3169
Inline: False
```
**Symbols:**

```
ffffffff8195ebc0-ffffffff8195ebeb: compat_tcp_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int compat_tcp_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819186b0)
Location: net/ipv4/tcp.c:3169
Inline: False
```
**Symbols:**

```
ffffffff819186b0-ffffffff819186db: compat_tcp_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int compat_tcp_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819c9390)
Location: net/ipv4/tcp.c:3169
Inline: False
```
**Symbols:**

```
ffffffff819c9390-ffffffff819c93bb: compat_tcp_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int compat_tcp_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819d2ee0)
Location: net/ipv4/tcp.c:3169
Inline: False
```
**Symbols:**

```
ffffffff819d2ee0-ffffffff819d2f0b: compat_tcp_setsockopt (STB_GLOBAL)
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
