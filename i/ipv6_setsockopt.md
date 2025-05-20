# Function: <code>ipv6_setsockopt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int ipv6_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff817ddf70)
Location: net/ipv6/ipv6_sockglue.c:884
Inline: True
```
**Symbols:**

```
ffffffff817ddf70-ffffffff817de00d: ipv6_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int ipv6_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff8184bff0)
Location: net/ipv6/ipv6_sockglue.c:885
Inline: True
```
**Symbols:**

```
ffffffff8184bff0-ffffffff8184c0a4: ipv6_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int ipv6_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff8187dec0)
Location: net/ipv6/ipv6_sockglue.c:900
Inline: True
```
**Symbols:**

```
ffffffff8187dec0-ffffffff8187df74: ipv6_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ipv6_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff818a3f20)
Location: net/ipv6/ipv6_sockglue.c:902
Inline: True
```
**Symbols:**

```
ffffffff818a3f20-ffffffff818a3fce: ipv6_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ipv6_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff819268e0)
Location: net/ipv6/ipv6_sockglue.c:911
Inline: True
```
**Symbols:**

```
ffffffff819268e0-ffffffff81926977: ipv6_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int ipv6_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff8197ed00)
Location: net/ipv6/ipv6_sockglue.c:923
Inline: True
```
**Symbols:**

```
ffffffff8197ed00-ffffffff8197ed8d: ipv6_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int ipv6_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff819b52d0)
Location: net/ipv6/ipv6_sockglue.c:929
Inline: True
```
**Symbols:**

```
ffffffff819b52d0-ffffffff819b535d: ipv6_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int ipv6_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff81a23d60)
Location: net/ipv6/ipv6_sockglue.c:933
Inline: True
```
**Symbols:**

```
ffffffff81a23d60-ffffffff81a23df2: ipv6_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int ipv6_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff81a5a7e0)
Location: net/ipv6/ipv6_sockglue.c:939
Inline: True
```
**Symbols:**

```
ffffffff81a5a7e0-ffffffff81a5a872: ipv6_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ipv6_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff81b53350)
Location: net/ipv6/ipv6_sockglue.c:890
Inline: False
Direct callers:
  - net/ipv6/raw.c:rawv6_setsockopt
```
**Symbols:**

```
ffffffff81b53350-ffffffff81b533e2: ipv6_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ipv6_setsockopt(struct sock *sk, int level, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff81b618b0)
Location: net/ipv6/ipv6_sockglue.c:992
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_setsockopt
  - net/ipv6/raw.c:rawv6_setsockopt
```
**Symbols:**

```
ffffffff81b618b0-ffffffff81b61953: ipv6_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ipv6_setsockopt(struct sock *sk, int level, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff81b4fb80)
Location: net/ipv6/ipv6_sockglue.c:992
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_setsockopt
  - net/ipv6/raw.c:rawv6_setsockopt
```
**Symbols:**

```
ffffffff81b4fb80-ffffffff81b4fc23: ipv6_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ipv6_setsockopt(struct sock *sk, int level, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff81c16ee0)
Location: net/ipv6/ipv6_sockglue.c:992
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_setsockopt
  - net/ipv6/raw.c:rawv6_setsockopt
```
**Symbols:**

```
ffffffff81c16ee0-ffffffff81c16f83: ipv6_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ipv6_setsockopt(struct sock *sk, int level, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff81db2bb0)
Location: net/ipv6/ipv6_sockglue.c:1010
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_setsockopt
  - net/ipv6/raw.c:rawv6_setsockopt
```
**Symbols:**

```
ffffffff81db2bb0-ffffffff81db2c88: ipv6_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ipv6_setsockopt(struct sock *sk, int level, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff81f81350)
Location: net/ipv6/ipv6_sockglue.c:1012
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_setsockopt
  - net/ipv6/raw.c:rawv6_setsockopt
```
**Symbols:**

```
ffffffff81f81350-ffffffff81f81419: ipv6_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ipv6_setsockopt(struct sock *sk, int level, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff81fe1620)
Location: net/ipv6/ipv6_sockglue.c:1001
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_setsockopt
  - net/ipv6/raw.c:rawv6_setsockopt
```
**Symbols:**

```
ffffffff81fe1620-ffffffff81fe16e9: ipv6_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ipv6_setsockopt(struct sock *sk, int level, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff820af540)
Location: net/ipv6/ipv6_sockglue.c:981
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_setsockopt
  - net/ipv6/raw.c:rawv6_setsockopt
```
**Symbols:**

```
ffffffff820af540-ffffffff820af609: ipv6_setsockopt (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int ipv6_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffff800010d1f9a8)
Location: net/ipv6/ipv6_sockglue.c:939
Inline: True
```
**Symbols:**

```
ffff800010d1f9a8-ffff800010d1fa94: ipv6_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int ipv6_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (c0e24758)
Location: net/ipv6/ipv6_sockglue.c:939
Inline: True
```
**Symbols:**

```
c0e24758-c0e24818: ipv6_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int ipv6_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (c000000000e4e010)
Location: net/ipv6/ipv6_sockglue.c:939
Inline: True
```
**Symbols:**

```
c000000000e4e010-c000000000e4e13c: ipv6_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int ipv6_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffe000861d92)
Location: net/ipv6/ipv6_sockglue.c:939
Inline: True
```
**Symbols:**

```
ffffffe000861d92-ffffffe000861e2e: ipv6_setsockopt (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int ipv6_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff819f9e70)
Location: net/ipv6/ipv6_sockglue.c:939
Inline: True
```
**Symbols:**

```
ffffffff819f9e70-ffffffff819f9f02: ipv6_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int ipv6_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff819b6c30)
Location: net/ipv6/ipv6_sockglue.c:939
Inline: True
```
**Symbols:**

```
ffffffff819b6c30-ffffffff819b6cc2: ipv6_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int ipv6_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff81a648f0)
Location: net/ipv6/ipv6_sockglue.c:939
Inline: True
```
**Symbols:**

```
ffffffff81a648f0-ffffffff81a64982: ipv6_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int ipv6_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff81a70e20)
Location: net/ipv6/ipv6_sockglue.c:939
Inline: True
```
**Symbols:**

```
ffffffff81a70e20-ffffffff81a70eb2: ipv6_setsockopt (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char *optval</code> ➡️ <code>sockptr_t optval</code>
</li>
</ul>
</details>
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
