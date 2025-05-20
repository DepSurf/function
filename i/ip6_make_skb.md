# Function: <code>ip6_make_skb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sk_buff *ip6_make_skb(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, int hlimit, int tclass, struct ipv6_txoptions *opt, struct flowi6 *fl6, struct rt6_info *rt, unsigned int flags, int dontfrag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff817c8320)
Location: net/ipv6/ip6_output.c:1749
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff817c8320-ffffffff817c84fe: ip6_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sk_buff *ip6_make_skb(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm6_cookie *ipc6, struct flowi6 *fl6, struct rt6_info *rt, unsigned int flags, const struct sockcm_cookie *sockc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81835430)
Location: net/ipv6/ip6_output.c:1753
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff81835430-ffffffff81835624: ip6_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sk_buff *ip6_make_skb(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm6_cookie *ipc6, struct flowi6 *fl6, struct rt6_info *rt, unsigned int flags, const struct sockcm_cookie *sockc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81866f60)
Location: net/ipv6/ip6_output.c:1780
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff81866f60-ffffffff81867154: ip6_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sk_buff *ip6_make_skb(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm6_cookie *ipc6, struct flowi6 *fl6, struct rt6_info *rt, unsigned int flags, const struct sockcm_cookie *sockc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff8188b710)
Location: net/ipv6/ip6_output.c:1783
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff8188b710-ffffffff8188b8da: ip6_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sk_buff *ip6_make_skb(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm6_cookie *ipc6, struct flowi6 *fl6, struct rt6_info *rt, unsigned int flags, const struct sockcm_cookie *sockc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff8190c9b0)
Location: net/ipv6/ip6_output.c:1732
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff8190c9b0-ffffffff8190cba3: ip6_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sk_buff *ip6_make_skb(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm6_cookie *ipc6, struct flowi6 *fl6, struct rt6_info *rt, unsigned int flags, struct inet_cork_full *cork, const struct sockcm_cookie *sockc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81963dd0)
Location: net/ipv6/ip6_output.c:1744
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff81963dd0-ffffffff81963f7a: ip6_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sk_buff *ip6_make_skb(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm6_cookie *ipc6, struct flowi6 *fl6, struct rt6_info *rt, unsigned int flags, struct inet_cork_full *cork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81998d70)
Location: net/ipv6/ip6_output.c:1775
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff81998d70-ffffffff81998f05: ip6_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sk_buff *ip6_make_skb(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm6_cookie *ipc6, struct flowi6 *fl6, struct rt6_info *rt, unsigned int flags, struct inet_cork_full *cork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a04bc0)
Location: net/ipv6/ip6_output.c:1839
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff81a04bc0-ffffffff81a04d58: ip6_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sk_buff *ip6_make_skb(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm6_cookie *ipc6, struct flowi6 *fl6, struct rt6_info *rt, unsigned int flags, struct inet_cork_full *cork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a3b7c0)
Location: net/ipv6/ip6_output.c:1843
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff81a3b7c0-ffffffff81a3b958: ip6_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *ip6_make_skb(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm6_cookie *ipc6, struct flowi6 *fl6, struct rt6_info *rt, unsigned int flags, struct inet_cork_full *cork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b30d90)
Location: net/ipv6/ip6_output.c:1913
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff81b30d90-ffffffff81b30f22: ip6_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *ip6_make_skb(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm6_cookie *ipc6, struct flowi6 *fl6, struct rt6_info *rt, unsigned int flags, struct inet_cork_full *cork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b3f9c0)
Location: net/ipv6/ip6_output.c:1952
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff81b3f9c0-ffffffff81b3fb52: ip6_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *ip6_make_skb(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm6_cookie *ipc6, struct flowi6 *fl6, struct rt6_info *rt, unsigned int flags, struct inet_cork_full *cork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b2d850)
Location: net/ipv6/ip6_output.c:1984
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff81b2d850-ffffffff81b2d9e0: ip6_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct sk_buff *ip6_make_skb(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm6_cookie *ipc6, struct flowi6 *fl6, struct rt6_info *rt, unsigned int flags, struct inet_cork_full *cork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (0)
Location: net/ipv6/ip6_output.c:1966
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff81d3f655-ffffffff81d3f685: ip6_make_skb.cold (STB_LOCAL)
ffffffff81bf3a90-ffffffff81bf3c2d: ip6_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct sk_buff *ip6_make_skb(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, size_t length, int transhdrlen, struct ipcm6_cookie *ipc6, struct rt6_info *rt, unsigned int flags, struct inet_cork_full *cork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (0)
Location: net/ipv6/ip6_output.c:1997
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff81f0bffd-ffffffff81f0c033: ip6_make_skb.cold (STB_LOCAL)
ffffffff81d8c680-ffffffff81d8c87f: ip6_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct sk_buff *ip6_make_skb(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, size_t length, int transhdrlen, struct ipcm6_cookie *ipc6, struct rt6_info *rt, unsigned int flags, struct inet_cork_full *cork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (0)
Location: net/ipv6/ip6_output.c:2035
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff820b3832-ffffffff820b3868: ip6_make_skb.cold (STB_LOCAL)
ffffffff81f5a670-ffffffff81f5a86f: ip6_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct sk_buff *ip6_make_skb(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, size_t length, int transhdrlen, struct ipcm6_cookie *ipc6, struct rt6_info *rt, unsigned int flags, struct inet_cork_full *cork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (0)
Location: net/ipv6/ip6_output.c:2059
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff82134938-ffffffff82134961: ip6_make_skb.cold (STB_LOCAL)
ffffffff81fba3d0-ffffffff81fba5cb: ip6_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *ip6_make_skb(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, size_t length, int transhdrlen, struct ipcm6_cookie *ipc6, struct rt6_info *rt, unsigned int flags, struct inet_cork_full *cork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff82087820)
Location: net/ipv6/ip6_output.c:2006
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff82087820-ffffffff820879f9: ip6_make_skb (STB_GLOBAL)
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
struct sk_buff *ip6_make_skb(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm6_cookie *ipc6, struct flowi6 *fl6, struct rt6_info *rt, unsigned int flags, struct inet_cork_full *cork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffff800010cfc988)
Location: net/ipv6/ip6_output.c:1843
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffff800010cfc988-ffff800010cfcb3c: ip6_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *ip6_make_skb(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm6_cookie *ipc6, struct flowi6 *fl6, struct rt6_info *rt, unsigned int flags, struct inet_cork_full *cork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (c0e03e64)
Location: net/ipv6/ip6_output.c:1843
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
c0e03e64-c0e04010: ip6_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *ip6_make_skb(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm6_cookie *ipc6, struct flowi6 *fl6, struct rt6_info *rt, unsigned int flags, struct inet_cork_full *cork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (c000000000e24650)
Location: net/ipv6/ip6_output.c:1843
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
c000000000e24650-c000000000e24890: ip6_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sk_buff *ip6_make_skb(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm6_cookie *ipc6, struct flowi6 *fl6, struct rt6_info *rt, unsigned int flags, struct inet_cork_full *cork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffe0008471ba)
Location: net/ipv6/ip6_output.c:1843
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffe0008471ba-ffffffe000847300: ip6_make_skb (STB_GLOBAL)
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
struct sk_buff *ip6_make_skb(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm6_cookie *ipc6, struct flowi6 *fl6, struct rt6_info *rt, unsigned int flags, struct inet_cork_full *cork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff819dae50)
Location: net/ipv6/ip6_output.c:1843
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff819dae50-ffffffff819dafe8: ip6_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sk_buff *ip6_make_skb(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm6_cookie *ipc6, struct flowi6 *fl6, struct rt6_info *rt, unsigned int flags, struct inet_cork_full *cork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81997c10)
Location: net/ipv6/ip6_output.c:1843
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff81997c10-ffffffff81997da8: ip6_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sk_buff *ip6_make_skb(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm6_cookie *ipc6, struct flowi6 *fl6, struct rt6_info *rt, unsigned int flags, struct inet_cork_full *cork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a458d0)
Location: net/ipv6/ip6_output.c:1843
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff81a458d0-ffffffff81a45a68: ip6_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sk_buff *ip6_make_skb(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm6_cookie *ipc6, struct flowi6 *fl6, struct rt6_info *rt, unsigned int flags, struct inet_cork_full *cork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a515a0)
Location: net/ipv6/ip6_output.c:1843
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff81a515a0-ffffffff81a51738: ip6_make_skb (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ipcm6_cookie *ipc6</code>
</li>
<li>
<b>Param added. </b>
<code>const struct sockcm_cookie *sockc</code>
</li>
<li>
<b>Param removed. </b>
<code>int hlimit</code>
</li>
<li>
<b>Param removed. </b>
<code>int tclass</code>
</li>
<li>
<b>Param removed. </b>
<code>struct ipv6_txoptions *opt</code>
</li>
<li>
<b>Param removed. </b>
<code>int dontfrag</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, getfrag, from, length, transhdrlen, hlimit, tclass, opt, fl6, rt, flags, dontfrag</code> ➡️ <code>sk, getfrag, from, length, transhdrlen, ipc6, fl6, rt, flags, sockc</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct inet_cork_full *cork</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, getfrag, from, length, transhdrlen, ipc6, fl6, rt, flags, sockc</code> ➡️ <code>sk, getfrag, from, length, transhdrlen, ipc6, fl6, rt, flags, cork, sockc</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>const struct sockcm_cookie *sockc</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct flowi6 *fl6</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, getfrag, from, length, transhdrlen, ipc6, fl6, rt, flags, cork</code> ➡️ <code>sk, getfrag, from, length, transhdrlen, ipc6, rt, flags, cork</code>
</li>
<li>
<b>Param type changed. </b>
<code>int length</code> ➡️ <code>size_t length</code>
</li>
</ul>
</details>
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
