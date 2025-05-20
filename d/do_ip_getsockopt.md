# Function: <code>do_ip_getsockopt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_ip_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff8175fcb0)
Location: net/ipv4/ip_sockglue.c:1266
Inline: False
```
**Symbols:**

```
ffffffff8175fcb0-ffffffff817603ec: do_ip_getsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_ip_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff817cbf50)
Location: net/ipv4/ip_sockglue.c:1281
Inline: False
```
**Symbols:**

```
ffffffff817cbf50-ffffffff817cc6ea: do_ip_getsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_ip_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff817fbc40)
Location: net/ipv4/ip_sockglue.c:1321
Inline: False
```
**Symbols:**

```
ffffffff817fbc40-ffffffff817fc3ee: do_ip_getsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_ip_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff8181bff0)
Location: net/ipv4/ip_sockglue.c:1310
Inline: False
```
**Symbols:**

```
ffffffff8181bff0-ffffffff8181c78a: do_ip_getsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_ip_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff8189af40)
Location: net/ipv4/ip_sockglue.c:1306
Inline: False
```
**Symbols:**

```
ffffffff8189af40-ffffffff8189b6e6: do_ip_getsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int do_ip_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_sockglue.c (0)
Location: net/ipv4/ip_sockglue.c:1310
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
```
**Symbols:**

```
ffffffff818ef480-ffffffff818efc06: do_ip_getsockopt (STB_LOCAL)
ffffffff818f1747-ffffffff818f1753: do_ip_getsockopt.cold.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int do_ip_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_sockglue.c (0)
Location: net/ipv4/ip_sockglue.c:1307
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
```
**Symbols:**

```
ffffffff8191cc60-ffffffff8191d4f2: do_ip_getsockopt (STB_LOCAL)
ffffffff8191f2a7-ffffffff8191f2b3: do_ip_getsockopt.cold.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int do_ip_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_sockglue.c (0)
Location: net/ipv4/ip_sockglue.c:1309
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
```
**Symbols:**

```
ffffffff8197efc0-ffffffff8197f856: do_ip_getsockopt (STB_LOCAL)
ffffffff81981bef-ffffffff81981bfb: do_ip_getsockopt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int do_ip_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_sockglue.c (0)
Location: net/ipv4/ip_sockglue.c:1309
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
```
**Symbols:**

```
ffffffff819b5500-ffffffff819b5d96: do_ip_getsockopt (STB_LOCAL)
ffffffff819b842f-ffffffff819b843b: do_ip_getsockopt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int do_ip_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_sockglue.c (0)
Location: net/ipv4/ip_sockglue.c:1472
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_getsockopt
```
**Symbols:**

```
ffffffff81a9fab0-ffffffff81aa03bb: do_ip_getsockopt (STB_LOCAL)
ffffffff81aa2d55-ffffffff81aa2d61: do_ip_getsockopt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int do_ip_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_sockglue.c (0)
Location: net/ipv4/ip_sockglue.c:1515
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_getsockopt
```
**Symbols:**

```
ffffffff81aaa3b0-ffffffff81aaad11: do_ip_getsockopt (STB_LOCAL)
ffffffff81c32583-ffffffff81c3258f: do_ip_getsockopt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int do_ip_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_sockglue.c (0)
Location: net/ipv4/ip_sockglue.c:1515
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_getsockopt
```
**Symbols:**

```
ffffffff81a95960-ffffffff81a9632e: do_ip_getsockopt (STB_LOCAL)
ffffffff81c2486e-ffffffff81c2487a: do_ip_getsockopt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int do_ip_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_sockglue.c (0)
Location: net/ipv4/ip_sockglue.c:1515
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_getsockopt
```
**Symbols:**

```
ffffffff81b50dc0-ffffffff81b51797: do_ip_getsockopt (STB_LOCAL)
ffffffff81d3a1a7-ffffffff81d3a1b3: do_ip_getsockopt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int do_ip_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_sockglue.c (0)
Location: net/ipv4/ip_sockglue.c:1526
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_getsockopt
```
**Symbols:**

```
ffffffff81cddd30-ffffffff81cde640: do_ip_getsockopt (STB_LOCAL)
ffffffff81f06925-ffffffff81f06931: do_ip_getsockopt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_ip_getsockopt(struct sock *sk, int level, int optname, sockptr_t optval, sockptr_t optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81ea1630)
Location: net/ipv4/ip_sockglue.c:1530
Inline: False
Direct callers:
  - net/core/filter.c:sol_ip_sockopt
  - net/ipv4/ip_sockglue.c:ip_getsockopt
```
**Symbols:**

```
ffffffff81ea1630-ffffffff81ea215d: do_ip_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_ip_getsockopt(struct sock *sk, int level, int optname, sockptr_t optval, sockptr_t optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81effe30)
Location: net/ipv4/ip_sockglue.c:1552
Inline: False
Direct callers:
  - net/core/filter.c:sol_ip_sockopt
  - net/ipv4/ip_sockglue.c:ip_getsockopt
```
**Symbols:**

```
ffffffff81effe30-ffffffff81f00973: do_ip_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_ip_getsockopt(struct sock *sk, int level, int optname, sockptr_t optval, sockptr_t optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81fc3fa0)
Location: net/ipv4/ip_sockglue.c:1503
Inline: False
Direct callers:
  - net/core/filter.c:sol_ip_sockopt
  - net/ipv4/ip_sockglue.c:ip_getsockopt
```
**Symbols:**

```
ffffffff81fc3fa0-ffffffff81fc4c14: do_ip_getsockopt (STB_GLOBAL)
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
int do_ip_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffff800010c663d0)
Location: net/ipv4/ip_sockglue.c:1309
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
```
**Symbols:**

```
ffff800010c663d0-ffff800010c6718c: do_ip_getsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_sockglue.c (c0d75c64)
Location: net/ipv4/ip_sockglue.c:1309
Inline: True
```
**Symbols:**

```
c0d75c64-c0d76658: do_ip_getsockopt.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_ip_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (c000000000d6a900)
Location: net/ipv4/ip_sockglue.c:1309
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
```
**Symbols:**

```
c000000000d6a900-c000000000d6b4a4: do_ip_getsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffe0007cd6b0)
Location: net/ipv4/ip_sockglue.c:1309
Inline: True
```
**Symbols:**

```
ffffffe0007cd6b0-ffffffe0007cdcba: do_ip_getsockopt.constprop.0 (STB_LOCAL)
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
int do_ip_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_sockglue.c (0)
Location: net/ipv4/ip_sockglue.c:1309
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
```
**Symbols:**

```
ffffffff81955370-ffffffff81955c06: do_ip_getsockopt (STB_LOCAL)
ffffffff8195829f-ffffffff819582ab: do_ip_getsockopt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int do_ip_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_sockglue.c (0)
Location: net/ipv4/ip_sockglue.c:1309
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
```
**Symbols:**

```
ffffffff8190ee60-ffffffff8190f6f6: do_ip_getsockopt (STB_LOCAL)
ffffffff81911d8f-ffffffff81911d9b: do_ip_getsockopt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int do_ip_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_sockglue.c (0)
Location: net/ipv4/ip_sockglue.c:1309
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
```
**Symbols:**

```
ffffffff819bfb40-ffffffff819c03d6: do_ip_getsockopt (STB_LOCAL)
ffffffff819c2a6f-ffffffff819c2a7b: do_ip_getsockopt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int do_ip_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_sockglue.c (0)
Location: net/ipv4/ip_sockglue.c:1309
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
```
**Symbols:**

```
ffffffff819c9510-ffffffff819c9db4: do_ip_getsockopt (STB_LOCAL)
ffffffff819cc46f-ffffffff819cc47b: do_ip_getsockopt.cold (STB_LOCAL)
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
<b>Param removed. </b>
<code>unsigned int flags</code>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char *optval</code> ➡️ <code>sockptr_t optval</code>
</li>
<li>
<b>Param type changed. </b>
<code>int *optlen</code> ➡️ <code>sockptr_t optlen</code>
</li>
</ul>
</details>
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
