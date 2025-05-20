# Function: <code>icmpv6_flow_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void icmpv6_flow_init(struct sock *sk, struct flowi6 *fl6, u8 type, const struct in6_addr *saddr, const struct in6_addr *daddr, int oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff817e8a50)
Location: net/ipv6/icmp.c:821
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_send
```
**Symbols:**

```
ffffffff817e8a50-ffffffff817e8abf: icmpv6_flow_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void icmpv6_flow_init(struct sock *sk, struct flowi6 *fl6, u8 type, const struct in6_addr *saddr, const struct in6_addr *daddr, int oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81857290)
Location: net/ipv6/icmp.c:896
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
**Symbols:**

```
ffffffff81857290-ffffffff818572ff: icmpv6_flow_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void icmpv6_flow_init(struct sock *sk, struct flowi6 *fl6, u8 type, const struct in6_addr *saddr, const struct in6_addr *daddr, int oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81889090)
Location: net/ipv6/icmp.c:901
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
**Symbols:**

```
ffffffff81889090-ffffffff818890ff: icmpv6_flow_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void icmpv6_flow_init(struct sock *sk, struct flowi6 *fl6, u8 type, const struct in6_addr *saddr, const struct in6_addr *daddr, int oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff818af710)
Location: net/ipv6/icmp.c:927
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
**Symbols:**

```
ffffffff818af710-ffffffff818af783: icmpv6_flow_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void icmpv6_flow_init(struct sock *sk, struct flowi6 *fl6, u8 type, const struct in6_addr *saddr, const struct in6_addr *daddr, int oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81932430)
Location: net/ipv6/icmp.c:936
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
**Symbols:**

```
ffffffff81932430-ffffffff819324a3: icmpv6_flow_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void icmpv6_flow_init(struct sock *sk, struct flowi6 *fl6, u8 type, const struct in6_addr *saddr, const struct in6_addr *daddr, int oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff8198aef0)
Location: net/ipv6/icmp.c:938
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
**Symbols:**

```
ffffffff8198aef0-ffffffff8198af5f: icmpv6_flow_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void icmpv6_flow_init(struct sock *sk, struct flowi6 *fl6, u8 type, const struct in6_addr *saddr, const struct in6_addr *daddr, int oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff819c1810)
Location: net/ipv6/icmp.c:940
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
**Symbols:**

```
ffffffff819c1810-ffffffff819c187f: icmpv6_flow_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void icmpv6_flow_init(struct sock *sk, struct flowi6 *fl6, u8 type, const struct in6_addr *saddr, const struct in6_addr *daddr, int oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81a30620)
Location: net/ipv6/icmp.c:957
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
**Symbols:**

```
ffffffff81a30620-ffffffff81a3068f: icmpv6_flow_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void icmpv6_flow_init(struct sock *sk, struct flowi6 *fl6, u8 type, const struct in6_addr *saddr, const struct in6_addr *daddr, int oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81a67170)
Location: net/ipv6/icmp.c:957
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
**Symbols:**

```
ffffffff81a67170-ffffffff81a671df: icmpv6_flow_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void icmpv6_flow_init(struct sock *sk, struct flowi6 *fl6, u8 type, const struct in6_addr *saddr, const struct in6_addr *daddr, int oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81b5fba0)
Location: net/ipv6/icmp.c:988
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
**Symbols:**

```
ffffffff81b5fba0-ffffffff81b5fc0e: icmpv6_flow_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void icmpv6_flow_init(struct sock *sk, struct flowi6 *fl6, u8 type, const struct in6_addr *saddr, const struct in6_addr *daddr, int oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81b6e340)
Location: net/ipv6/icmp.c:998
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
**Symbols:**

```
ffffffff81b6e340-ffffffff81b6e3ae: icmpv6_flow_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void icmpv6_flow_init(struct sock *sk, struct flowi6 *fl6, u8 type, const struct in6_addr *saddr, const struct in6_addr *daddr, int oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81b5c720)
Location: net/ipv6/icmp.c:1002
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
**Symbols:**

```
ffffffff81b5c720-ffffffff81b5c78e: icmpv6_flow_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void icmpv6_flow_init(struct sock *sk, struct flowi6 *fl6, u8 type, const struct in6_addr *saddr, const struct in6_addr *daddr, int oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81c23f70)
Location: net/ipv6/icmp.c:1021
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
**Symbols:**

```
ffffffff81c23f70-ffffffff81c23fde: icmpv6_flow_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void icmpv6_flow_init(struct sock *sk, struct flowi6 *fl6, u8 type, const struct in6_addr *saddr, const struct in6_addr *daddr, int oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81dc0e00)
Location: net/ipv6/icmp.c:1020
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
**Symbols:**

```
ffffffff81dc0e00-ffffffff81dc0e88: icmpv6_flow_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void icmpv6_flow_init(struct sock *sk, struct flowi6 *fl6, u8 type, const struct in6_addr *saddr, const struct in6_addr *daddr, int oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81f91500)
Location: net/ipv6/icmp.c:1020
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
**Symbols:**

```
ffffffff81f91500-ffffffff81f91588: icmpv6_flow_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void icmpv6_flow_init(struct sock *sk, struct flowi6 *fl6, u8 type, const struct in6_addr *saddr, const struct in6_addr *daddr, int oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81ff1e10)
Location: net/ipv6/icmp.c:1037
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
**Symbols:**

```
ffffffff81ff1e10-ffffffff81ff1e98: icmpv6_flow_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void icmpv6_flow_init(const struct sock *sk, struct flowi6 *fl6, u8 type, const struct in6_addr *saddr, const struct in6_addr *daddr, int oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff820bfa10)
Location: net/ipv6/icmp.c:1037
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
**Symbols:**

```
ffffffff820bfa10-ffffffff820bfa98: icmpv6_flow_init (STB_GLOBAL)
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
void icmpv6_flow_init(struct sock *sk, struct flowi6 *fl6, u8 type, const struct in6_addr *saddr, const struct in6_addr *daddr, int oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffff800010d2d0a8)
Location: net/ipv6/icmp.c:957
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
**Symbols:**

```
ffff800010d2d0a8-ffff800010d2d138: icmpv6_flow_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void icmpv6_flow_init(struct sock *sk, struct flowi6 *fl6, u8 type, const struct in6_addr *saddr, const struct in6_addr *daddr, int oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (c0e30fb4)
Location: net/ipv6/icmp.c:957
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
**Symbols:**

```
c0e30fb4-c0e3102c: icmpv6_flow_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void icmpv6_flow_init(struct sock *sk, struct flowi6 *fl6, u8 type, const struct in6_addr *saddr, const struct in6_addr *daddr, int oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (c000000000e5ed50)
Location: net/ipv6/icmp.c:957
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
**Symbols:**

```
c000000000e5ed50-c000000000e5ee1c: icmpv6_flow_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void icmpv6_flow_init(struct sock *sk, struct flowi6 *fl6, u8 type, const struct in6_addr *saddr, const struct in6_addr *daddr, int oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffe00086d256)
Location: net/ipv6/icmp.c:957
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
**Symbols:**

```
ffffffe00086d256-ffffffe00086d2f4: icmpv6_flow_init (STB_GLOBAL)
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
void icmpv6_flow_init(struct sock *sk, struct flowi6 *fl6, u8 type, const struct in6_addr *saddr, const struct in6_addr *daddr, int oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81a06800)
Location: net/ipv6/icmp.c:957
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
**Symbols:**

```
ffffffff81a06800-ffffffff81a0686f: icmpv6_flow_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void icmpv6_flow_init(struct sock *sk, struct flowi6 *fl6, u8 type, const struct in6_addr *saddr, const struct in6_addr *daddr, int oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff819c35c0)
Location: net/ipv6/icmp.c:957
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
**Symbols:**

```
ffffffff819c35c0-ffffffff819c362f: icmpv6_flow_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void icmpv6_flow_init(struct sock *sk, struct flowi6 *fl6, u8 type, const struct in6_addr *saddr, const struct in6_addr *daddr, int oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81a71280)
Location: net/ipv6/icmp.c:957
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
**Symbols:**

```
ffffffff81a71280-ffffffff81a712ef: icmpv6_flow_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void icmpv6_flow_init(struct sock *sk, struct flowi6 *fl6, u8 type, const struct in6_addr *saddr, const struct in6_addr *daddr, int oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81a7d890)
Location: net/ipv6/icmp.c:957
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
**Symbols:**

```
ffffffff81a7d890-ffffffff81a7d8ff: icmpv6_flow_init (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct sock *sk</code> ➡️ <code>const struct sock *sk</code>
</li>
</ul>
</details>
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
