# Function: <code>ipv6_get_lladdr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ipv6_get_lladdr(struct net_device *dev, struct in6_addr *addr, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff817cf740)
Location: net/ipv6/addrconf.c:1611
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/mcast.c:igmp6_send
```
**Symbols:**

```
ffffffff817cf740-ffffffff817cf7eb: ipv6_get_lladdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ipv6_get_lladdr(struct net_device *dev, struct in6_addr *addr, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8183ce00)
Location: net/ipv6/addrconf.c:1673
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/mcast.c:igmp6_send
```
**Symbols:**

```
ffffffff8183ce00-ffffffff8183ceab: ipv6_get_lladdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ipv6_get_lladdr(struct net_device *dev, struct in6_addr *addr, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8186e8c0)
Location: net/ipv6/addrconf.c:1721
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/mcast.c:igmp6_send
```
**Symbols:**

```
ffffffff8186e8c0-ffffffff8186e96b: ipv6_get_lladdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ipv6_get_lladdr(struct net_device *dev, struct in6_addr *addr, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81893690)
Location: net/ipv6/addrconf.c:1763
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/mcast.c:igmp6_send
```
**Symbols:**

```
ffffffff81893690-ffffffff81893756: ipv6_get_lladdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ipv6_get_lladdr(struct net_device *dev, struct in6_addr *addr, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81914970)
Location: net/ipv6/addrconf.c:1807
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/mcast.c:igmp6_send
```
**Symbols:**

```
ffffffff81914970-ffffffff81914a36: ipv6_get_lladdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ipv6_get_lladdr(struct net_device *dev, struct in6_addr *addr, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8196bfa0)
Location: net/ipv6/addrconf.c:1808
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/mcast.c:igmp6_send
```
**Symbols:**

```
ffffffff8196bfa0-ffffffff8196c04b: ipv6_get_lladdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ipv6_get_lladdr(struct net_device *dev, struct in6_addr *addr, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819a1a40)
Location: net/ipv6/addrconf.c:1824
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/mcast.c:igmp6_send
```
**Symbols:**

```
ffffffff819a1a40-ffffffff819a1aeb: ipv6_get_lladdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ipv6_get_lladdr(struct net_device *dev, struct in6_addr *addr, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a0e010)
Location: net/ipv6/addrconf.c:1857
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/mcast.c:igmp6_send
```
**Symbols:**

```
ffffffff81a0e010-ffffffff81a0e0b0: ipv6_get_lladdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ipv6_get_lladdr(struct net_device *dev, struct in6_addr *addr, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a44d50)
Location: net/ipv6/addrconf.c:1859
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/mcast.c:igmp6_send
```
**Symbols:**

```
ffffffff81a44d50-ffffffff81a44df0: ipv6_get_lladdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ipv6_get_lladdr(struct net_device *dev, struct in6_addr *addr, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b3b890)
Location: net/ipv6/addrconf.c:1850
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/mcast.c:igmp6_send
```
**Symbols:**

```
ffffffff81b3b890-ffffffff81b3b932: ipv6_get_lladdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ipv6_get_lladdr(struct net_device *dev, struct in6_addr *addr, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b4a5a0)
Location: net/ipv6/addrconf.c:1850
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/mcast.c:igmp6_send
```
**Symbols:**

```
ffffffff81b4a5a0-ffffffff81b4a64b: ipv6_get_lladdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ipv6_get_lladdr(struct net_device *dev, struct in6_addr *addr, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b38120)
Location: net/ipv6/addrconf.c:1852
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/mcast.c:igmp6_send
```
**Symbols:**

```
ffffffff81b38120-ffffffff81b381cb: ipv6_get_lladdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ipv6_get_lladdr(struct net_device *dev, struct in6_addr *addr, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81bfe8c0)
Location: net/ipv6/addrconf.c:1859
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/mcast.c:igmp6_send
```
**Symbols:**

```
ffffffff81bfe8c0-ffffffff81bfe96b: ipv6_get_lladdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ipv6_get_lladdr(struct net_device *dev, struct in6_addr *addr, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81d982f0)
Location: net/ipv6/addrconf.c:1866
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/mcast.c:igmp6_send
```
**Symbols:**

```
ffffffff81d982f0-ffffffff81d983ab: ipv6_get_lladdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ipv6_get_lladdr(struct net_device *dev, struct in6_addr *addr, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81f66f90)
Location: net/ipv6/addrconf.c:1866
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/mcast.c:igmp6_send
```
**Symbols:**

```
ffffffff81f66f90-ffffffff81f6704b: ipv6_get_lladdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ipv6_get_lladdr(struct net_device *dev, struct in6_addr *addr, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81fc70a0)
Location: net/ipv6/addrconf.c:1865
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/mcast.c:igmp6_send
```
**Symbols:**

```
ffffffff81fc70a0-ffffffff81fc715b: ipv6_get_lladdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ipv6_get_lladdr(struct net_device *dev, struct in6_addr *addr, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff820947c0)
Location: net/ipv6/addrconf.c:1893
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/mcast.c:igmp6_send
```
**Symbols:**

```
ffffffff820947c0-ffffffff8209487b: ipv6_get_lladdr (STB_GLOBAL)
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
int ipv6_get_lladdr(struct net_device *dev, struct in6_addr *addr, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffff800010d07220)
Location: net/ipv6/addrconf.c:1859
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/mcast.c:igmp6_send
```
**Symbols:**

```
ffff800010d07220-ffff800010d0734c: ipv6_get_lladdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ipv6_get_lladdr(struct net_device *dev, struct in6_addr *addr, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c0e0dd8c)
Location: net/ipv6/addrconf.c:1859
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/mcast.c:igmp6_send
```
**Symbols:**

```
c0e0dd8c-c0e0ddec: ipv6_get_lladdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ipv6_get_lladdr(struct net_device *dev, struct in6_addr *addr, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c000000000e31640)
Location: net/ipv6/addrconf.c:1859
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/mcast.c:igmp6_send
```
**Symbols:**

```
c000000000e31640-c000000000e31734: ipv6_get_lladdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ipv6_get_lladdr(struct net_device *dev, struct in6_addr *addr, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffe00084f772)
Location: net/ipv6/addrconf.c:1859
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/mcast.c:igmp6_send
```
**Symbols:**

```
ffffffe00084f772-ffffffe00084f81a: ipv6_get_lladdr (STB_GLOBAL)
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
int ipv6_get_lladdr(struct net_device *dev, struct in6_addr *addr, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819e43e0)
Location: net/ipv6/addrconf.c:1859
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/mcast.c:igmp6_send
```
**Symbols:**

```
ffffffff819e43e0-ffffffff819e4480: ipv6_get_lladdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ipv6_get_lladdr(struct net_device *dev, struct in6_addr *addr, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819a11a0)
Location: net/ipv6/addrconf.c:1859
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/mcast.c:igmp6_send
```
**Symbols:**

```
ffffffff819a11a0-ffffffff819a1240: ipv6_get_lladdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ipv6_get_lladdr(struct net_device *dev, struct in6_addr *addr, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a4ee60)
Location: net/ipv6/addrconf.c:1859
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/mcast.c:igmp6_send
```
**Symbols:**

```
ffffffff81a4ee60-ffffffff81a4ef00: ipv6_get_lladdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ipv6_get_lladdr(struct net_device *dev, struct in6_addr *addr, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a5ae00)
Location: net/ipv6/addrconf.c:1859
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/mcast.c:igmp6_send
```
**Symbols:**

```
ffffffff81a5ae00-ffffffff81a5aead: ipv6_get_lladdr (STB_GLOBAL)
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
