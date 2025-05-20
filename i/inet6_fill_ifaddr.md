# Function: <code>inet6_fill_ifaddr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int inet6_fill_ifaddr(struct sk_buff *skb, struct inet6_ifaddr *ifa, u32 portid, u32 seq, int event, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff817cc190)
Location: net/ipv6/addrconf.c:4299
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
```
**Symbols:**

```
ffffffff817cc190-ffffffff817cc3b8: inet6_fill_ifaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int inet6_fill_ifaddr(struct sk_buff *skb, struct inet6_ifaddr *ifa, u32 portid, u32 seq, int event, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81838be0)
Location: net/ipv6/addrconf.c:4551
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff81838be0-ffffffff81838e08: inet6_fill_ifaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int inet6_fill_ifaddr(struct sk_buff *skb, struct inet6_ifaddr *ifa, u32 portid, u32 seq, int event, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8186a600)
Location: net/ipv6/addrconf.c:4594
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff8186a600-ffffffff8186a828: inet6_fill_ifaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int inet6_fill_ifaddr(struct sk_buff *skb, struct inet6_ifaddr *ifa, u32 portid, u32 seq, int event, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8188eb60)
Location: net/ipv6/addrconf.c:4672
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff8188eb60-ffffffff8188ed6c: inet6_fill_ifaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int inet6_fill_ifaddr(struct sk_buff *skb, struct inet6_ifaddr *ifa, u32 portid, u32 seq, int event, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819101b0)
Location: net/ipv6/addrconf.c:4676
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff819101b0-ffffffff819103bc: inet6_fill_ifaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int inet6_fill_ifaddr(struct sk_buff *skb, struct inet6_ifaddr *ifa, u32 portid, u32 seq, int event, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819675c0)
Location: net/ipv6/addrconf.c:4798
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff819675c0-ffffffff819677f4: inet6_fill_ifaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int inet6_fill_ifaddr(struct sk_buff *skb, struct inet6_ifaddr *ifa, struct inet6_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8199cc40)
Location: net/ipv6/addrconf.c:4836
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:in6_dump_addrs
```
**Symbols:**

```
ffffffff8199cc40-ffffffff8199ceab: inet6_fill_ifaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int inet6_fill_ifaddr(struct sk_buff *skb, struct inet6_ifaddr *ifa, struct inet6_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:4872
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:in6_dump_addrs
```
**Symbols:**

```
ffffffff81a08e20-ffffffff81a0908e: inet6_fill_ifaddr (STB_LOCAL)
ffffffff81a11264-ffffffff81a1127f: inet6_fill_ifaddr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int inet6_fill_ifaddr(struct sk_buff *skb, struct inet6_ifaddr *ifa, struct inet6_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a3fad0)
Location: net/ipv6/addrconf.c:4901
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:in6_dump_addrs
```
**Symbols:**

```
ffffffff81a3fad0-ffffffff81a3fd3e: inet6_fill_ifaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int inet6_fill_ifaddr(struct sk_buff *skb, struct inet6_ifaddr *ifa, struct inet6_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b35500)
Location: net/ipv6/addrconf.c:4918
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_ifa_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:in6_dump_addrs
```
**Symbols:**

```
ffffffff81b35500-ffffffff81b357e0: inet6_fill_ifaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int inet6_fill_ifaddr(struct sk_buff *skb, struct inet6_ifaddr *ifa, struct inet6_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b43ff0)
Location: net/ipv6/addrconf.c:4945
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_ifa_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:in6_dump_addrs
```
**Symbols:**

```
ffffffff81b43ff0-ffffffff81b442d0: inet6_fill_ifaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int inet6_fill_ifaddr(struct sk_buff *skb, struct inet6_ifaddr *ifa, struct inet6_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b31bc0)
Location: net/ipv6/addrconf.c:4949
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:in6_dump_addrs
```
**Symbols:**

```
ffffffff81b31bc0-ffffffff81b31e9f: inet6_fill_ifaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int inet6_fill_ifaddr(struct sk_buff *skb, struct inet6_ifaddr *ifa, struct inet6_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81bf7c70)
Location: net/ipv6/addrconf.c:4985
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:in6_dump_addrs
```
**Symbols:**

```
ffffffff81bf7c70-ffffffff81bf7f63: inet6_fill_ifaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int inet6_fill_ifaddr(struct sk_buff *skb, struct inet6_ifaddr *ifa, struct inet6_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81d90fb0)
Location: net/ipv6/addrconf.c:4998
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:in6_dump_addrs
```
**Symbols:**

```
ffffffff81d90fb0-ffffffff81d91306: inet6_fill_ifaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int inet6_fill_ifaddr(struct sk_buff *skb, struct inet6_ifaddr *ifa, struct inet6_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81f5f700)
Location: net/ipv6/addrconf.c:5011
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:in6_dump_addrs
```
**Symbols:**

```
ffffffff81f5f700-ffffffff81f5fa56: inet6_fill_ifaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int inet6_fill_ifaddr(struct sk_buff *skb, struct inet6_ifaddr *ifa, struct inet6_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81fbf430)
Location: net/ipv6/addrconf.c:5017
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:in6_dump_addrs
```
**Symbols:**

```
ffffffff81fbf430-ffffffff81fbf786: inet6_fill_ifaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int inet6_fill_ifaddr(struct sk_buff *skb, struct inet6_ifaddr *ifa, struct inet6_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8208c8d0)
Location: net/ipv6/addrconf.c:5072
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:in6_dump_addrs
```
**Symbols:**

```
ffffffff8208c8d0-ffffffff8208cc29: inet6_fill_ifaddr (STB_LOCAL)
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
int inet6_fill_ifaddr(struct sk_buff *skb, struct inet6_ifaddr *ifa, struct inet6_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffff800010d00d88)
Location: net/ipv6/addrconf.c:4901
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:in6_dump_addrs
```
**Symbols:**

```
ffff800010d00d88-ffff800010d00fe4: inet6_fill_ifaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int inet6_fill_ifaddr(struct sk_buff *skb, struct inet6_ifaddr *ifa, struct inet6_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c0e08868)
Location: net/ipv6/addrconf.c:4901
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:in6_dump_addrs
```
**Symbols:**

```
c0e08868-c0e08b08: inet6_fill_ifaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int inet6_fill_ifaddr(struct sk_buff *skb, struct inet6_ifaddr *ifa, struct inet6_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c000000000e2aaf0)
Location: net/ipv6/addrconf.c:4901
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:in6_dump_addrs
```
**Symbols:**

```
c000000000e2aaf0-c000000000e2ae54: inet6_fill_ifaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int inet6_fill_ifaddr(struct sk_buff *skb, struct inet6_ifaddr *ifa, struct inet6_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffe00084ad8c)
Location: net/ipv6/addrconf.c:4901
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:in6_dump_addrs
```
**Symbols:**

```
ffffffe00084ad8c-ffffffe00084af88: inet6_fill_ifaddr (STB_LOCAL)
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
int inet6_fill_ifaddr(struct sk_buff *skb, struct inet6_ifaddr *ifa, struct inet6_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819df160)
Location: net/ipv6/addrconf.c:4901
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:in6_dump_addrs
```
**Symbols:**

```
ffffffff819df160-ffffffff819df3ce: inet6_fill_ifaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int inet6_fill_ifaddr(struct sk_buff *skb, struct inet6_ifaddr *ifa, struct inet6_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8199bf20)
Location: net/ipv6/addrconf.c:4901
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:in6_dump_addrs
```
**Symbols:**

```
ffffffff8199bf20-ffffffff8199c18e: inet6_fill_ifaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int inet6_fill_ifaddr(struct sk_buff *skb, struct inet6_ifaddr *ifa, struct inet6_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a49be0)
Location: net/ipv6/addrconf.c:4901
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:in6_dump_addrs
```
**Symbols:**

```
ffffffff81a49be0-ffffffff81a49e4e: inet6_fill_ifaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int inet6_fill_ifaddr(struct sk_buff *skb, struct inet6_ifaddr *ifa, struct inet6_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a55b20)
Location: net/ipv6/addrconf.c:4901
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:in6_dump_addrs
```
**Symbols:**

```
ffffffff81a55b20-ffffffff81a55d8f: inet6_fill_ifaddr (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct inet6_fill_args *args</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 portid</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 seq</code>
</li>
<li>
<b>Param removed. </b>
<code>int event</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int flags</code>
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
