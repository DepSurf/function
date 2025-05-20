# Function: <code>in6_pton</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int in6_pton(const char *src, int srclen, u8 *dst, int delim, const char **end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff817300c0)
Location: net/core/utils.c:186
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
ffffffff817300c0-ffffffff817304a5: in6_pton (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int in6_pton(const char *src, int srclen, u8 *dst, int delim, const char **end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff8179a800)
Location: net/core/utils.c:186
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
ffffffff8179a800-ffffffff8179ac23: in6_pton (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int in6_pton(const char *src, int srclen, u8 *dst, int delim, const char **end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff817c85a0)
Location: net/core/utils.c:186
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
ffffffff817c85a0-ffffffff817c89c3: in6_pton (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int in6_pton(const char *src, int srclen, u8 *dst, int delim, const char **end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff817e6ed0)
Location: net/core/utils.c:188
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - net/core/utils.c:inet6_pton
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
ffffffff817e6ed0-ffffffff817e72aa: in6_pton (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int in6_pton(const char *src, int srclen, u8 *dst, int delim, const char **end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81861e10)
Location: net/core/utils.c:188
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - net/core/utils.c:inet6_pton
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
ffffffff81861e10-ffffffff818621ea: in6_pton (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int in6_pton(const char *src, int srclen, u8 *dst, int delim, const char **end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff818adac0)
Location: net/core/utils.c:188
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - net/core/utils.c:inet6_pton
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
ffffffff818adac0-ffffffff818ade65: in6_pton (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int in6_pton(const char *src, int srclen, u8 *dst, int delim, const char **end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff818d1d20)
Location: net/core/utils.c:188
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - net/core/utils.c:inet6_pton
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
ffffffff818d1d20-ffffffff818d20dd: in6_pton (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int in6_pton(const char *src, int srclen, u8 *dst, int delim, const char **end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff8191efb0)
Location: net/core/utils.c:184
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - net/core/utils.c:inet6_pton
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
ffffffff8191efb0-ffffffff8191f367: in6_pton (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int in6_pton(const char *src, int srclen, u8 *dst, int delim, const char **end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff819511f0)
Location: net/core/utils.c:184
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - net/core/utils.c:inet6_pton
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
ffffffff819511f0-ffffffff819515a7: in6_pton (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int in6_pton(const char *src, int srclen, u8 *dst, int delim, const char **end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81a22060)
Location: net/core/utils.c:184
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - net/core/utils.c:inet6_pton
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
ffffffff81a22060-ffffffff81a22417: in6_pton (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int in6_pton(const char *src, int srclen, u8 *dst, int delim, const char **end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81a223e0)
Location: net/core/utils.c:184
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - net/core/utils.c:inet6_pton
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
ffffffff81a223e0-ffffffff81a2279b: in6_pton (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int in6_pton(const char *src, int srclen, u8 *dst, int delim, const char **end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81a09720)
Location: net/core/utils.c:184
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - net/core/utils.c:inet6_pton
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
ffffffff81a09720-ffffffff81a09ac3: in6_pton (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int in6_pton(const char *src, int srclen, u8 *dst, int delim, const char **end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81abbc00)
Location: net/core/utils.c:184
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - net/core/utils.c:inet6_pton
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
ffffffff81abbc00-ffffffff81abbfa3: in6_pton (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int in6_pton(const char *src, int srclen, u8 *dst, int delim, const char **end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81c365a0)
Location: net/core/utils.c:184
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - net/core/utils.c:inet6_pton
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
ffffffff81c365a0-ffffffff81c369d5: in6_pton (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int in6_pton(const char *src, int srclen, u8 *dst, int delim, const char **end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81de9d20)
Location: net/core/utils.c:184
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - net/core/utils.c:inet6_pton
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
ffffffff81de9d20-ffffffff81dea156: in6_pton (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int in6_pton(const char *src, int srclen, u8 *dst, int delim, const char **end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81e5b530)
Location: net/core/utils.c:184
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - net/core/utils.c:inet6_pton
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
ffffffff81e5b530-ffffffff81e5b94a: in6_pton (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int in6_pton(const char *src, int srclen, u8 *dst, int delim, const char **end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81f1a8f0)
Location: net/core/utils.c:184
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - net/core/utils.c:inet6_pton
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
ffffffff81f1a8f0-ffffffff81f1ad0a: in6_pton (STB_GLOBAL)
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
int in6_pton(const char *src, int srclen, u8 *dst, int delim, const char **end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffff800010bf2f78)
Location: net/core/utils.c:184
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - net/core/utils.c:inet6_pton
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
ffff800010bf2f78-ffff800010bf32bc: in6_pton (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int in6_pton(const char *src, int srclen, u8 *dst, int delim, const char **end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (c0d0b6f8)
Location: net/core/utils.c:184
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - net/core/utils.c:inet6_pton
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
c0d0b6f8-c0d0bae4: in6_pton (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int in6_pton(const char *src, int srclen, u8 *dst, int delim, const char **end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (c000000000cd7d90)
Location: net/core/utils.c:184
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - net/core/utils.c:inet6_pton
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
c000000000cd7d90-c000000000cd8220: in6_pton (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int in6_pton(const char *src, int srclen, u8 *dst, int delim, const char **end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffe000774952)
Location: net/core/utils.c:184
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - net/core/utils.c:inet6_pton
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
ffffffe000774952-ffffffe000774c38: in6_pton (STB_GLOBAL)
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
int in6_pton(const char *src, int srclen, u8 *dst, int delim, const char **end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff818f11c0)
Location: net/core/utils.c:184
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - net/core/utils.c:inet6_pton
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
ffffffff818f11c0-ffffffff818f1577: in6_pton (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int in6_pton(const char *src, int srclen, u8 *dst, int delim, const char **end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff818ab000)
Location: net/core/utils.c:184
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - net/core/utils.c:inet6_pton
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
ffffffff818ab000-ffffffff818ab3b7: in6_pton (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int in6_pton(const char *src, int srclen, u8 *dst, int delim, const char **end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff819421f0)
Location: net/core/utils.c:184
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - net/core/utils.c:inet6_pton
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
ffffffff819421f0-ffffffff819425a7: in6_pton (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int in6_pton(const char *src, int srclen, u8 *dst, int delim, const char **end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81963af0)
Location: net/core/utils.c:184
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - net/core/utils.c:inet6_pton
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
ffffffff81963af0-ffffffff81963ea7: in6_pton (STB_GLOBAL)
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
