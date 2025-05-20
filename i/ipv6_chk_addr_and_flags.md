# Function: <code>ipv6_chk_addr_and_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ipv6_chk_addr_and_flags(struct net *net, const struct in6_addr *addr, const struct net_device *dev, int strict, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff817c9370)
Location: net/ipv6/addrconf.c:1647
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:ipv6_chk_addr
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/ndisc.c:ndisc_solicit
```
**Symbols:**

```
ffffffff817c9370-ffffffff817c9448: ipv6_chk_addr_and_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ipv6_chk_addr_and_flags(struct net *net, const struct in6_addr *addr, const struct net_device *dev, int strict, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81836530)
Location: net/ipv6/addrconf.c:1709
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:ipv6_chk_addr
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/ndisc.c:ndisc_solicit
```
**Symbols:**

```
ffffffff81836530-ffffffff81836602: ipv6_chk_addr_and_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ipv6_chk_addr_and_flags(struct net *net, const struct in6_addr *addr, const struct net_device *dev, int strict, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81868040)
Location: net/ipv6/addrconf.c:1757
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:ipv6_chk_addr
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/ndisc.c:ndisc_solicit
```
**Symbols:**

```
ffffffff81868040-ffffffff81868112: ipv6_chk_addr_and_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ipv6_chk_addr_and_flags(struct net *net, const struct in6_addr *addr, const struct net_device *dev, int strict, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8188c860)
Location: net/ipv6/addrconf.c:1799
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:ipv6_chk_addr
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/ndisc.c:ndisc_solicit
```
**Symbols:**

```
ffffffff8188c860-ffffffff8188c933: ipv6_chk_addr_and_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ipv6_chk_addr_and_flags(struct net *net, const struct in6_addr *addr, const struct net_device *dev, int strict, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8190d960)
Location: net/ipv6/addrconf.c:1843
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:ipv6_chk_addr
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/ndisc.c:ndisc_solicit
```
**Symbols:**

```
ffffffff8190d960-ffffffff8190da23: ipv6_chk_addr_and_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ipv6_chk_addr_and_flags(struct net *net, const struct in6_addr *addr, const struct net_device *dev, bool skip_dev_check, int strict, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81966ac0)
Location: net/ipv6/addrconf.c:1854
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:ipv6_chk_addr
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
```
**Symbols:**

```
ffffffff81966ac0-ffffffff81966c33: ipv6_chk_addr_and_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ipv6_chk_addr_and_flags(struct net *net, const struct in6_addr *addr, const struct net_device *dev, bool skip_dev_check, int strict, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8199c0e0)
Location: net/ipv6/addrconf.c:1870
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:ipv6_chk_addr
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
```
**Symbols:**

```
ffffffff8199c0e0-ffffffff8199c253: ipv6_chk_addr_and_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ipv6_chk_addr_and_flags(struct net *net, const struct in6_addr *addr, const struct net_device *dev, bool skip_dev_check, int strict, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a07f00)
Location: net/ipv6/addrconf.c:1903
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:ipv6_chk_addr
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
```
**Symbols:**

```
ffffffff81a07f00-ffffffff81a08067: ipv6_chk_addr_and_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ipv6_chk_addr_and_flags(struct net *net, const struct in6_addr *addr, const struct net_device *dev, bool skip_dev_check, int strict, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a3ea70)
Location: net/ipv6/addrconf.c:1905
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:ipv6_chk_addr
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
```
**Symbols:**

```
ffffffff81a3ea70-ffffffff81a3ebda: ipv6_chk_addr_and_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ipv6_chk_addr_and_flags(struct net *net, const struct in6_addr *addr, const struct net_device *dev, bool skip_dev_check, int strict, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b33ff0)
Location: net/ipv6/addrconf.c:1896
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:ipv6_chk_addr
  - net/ipv6/route.c:ip6_validate_gw
  - net/ipv6/route.c:ip6_validate_gw
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
```
**Symbols:**

```
ffffffff81b33ff0-ffffffff81b3415a: ipv6_chk_addr_and_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int ipv6_chk_addr_and_flags(struct net *net, const struct in6_addr *addr, const struct net_device *dev, bool skip_dev_check, int strict, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b42d49)
Location: net/ipv6/addrconf.c:1939
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_addr
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/route.c:ip6_validate_gw
  - net/ipv6/route.c:ip6_validate_gw
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
```
**Symbols:**

```
ffffffff81b42d20-ffffffff81b42d3c: ipv6_chk_addr_and_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int ipv6_chk_addr_and_flags(struct net *net, const struct in6_addr *addr, const struct net_device *dev, bool skip_dev_check, int strict, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b30cd9)
Location: net/ipv6/addrconf.c:1941
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_addr
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/route.c:ip6_validate_gw
  - net/ipv6/route.c:ip6_validate_gw
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
```
**Symbols:**

```
ffffffff81b30cb0-ffffffff81b30ccc: ipv6_chk_addr_and_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int ipv6_chk_addr_and_flags(struct net *net, const struct in6_addr *addr, const struct net_device *dev, bool skip_dev_check, int strict, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81bf71f9)
Location: net/ipv6/addrconf.c:1948
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_addr
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/route.c:ip6_validate_gw
  - net/ipv6/route.c:ip6_validate_gw
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
```
**Symbols:**

```
ffffffff81bf71d0-ffffffff81bf71ec: ipv6_chk_addr_and_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int ipv6_chk_addr_and_flags(struct net *net, const struct in6_addr *addr, const struct net_device *dev, bool skip_dev_check, int strict, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81d904c9)
Location: net/ipv6/addrconf.c:1953
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_addr
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/route.c:ip6_validate_gw
  - net/ipv6/route.c:ip6_validate_gw
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
```
**Symbols:**

```
ffffffff81d90490-ffffffff81d904be: ipv6_chk_addr_and_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int ipv6_chk_addr_and_flags(struct net *net, const struct in6_addr *addr, const struct net_device *dev, bool skip_dev_check, int strict, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81f5eaa9)
Location: net/ipv6/addrconf.c:1953
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_addr
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/route.c:ip6_validate_gw
  - net/ipv6/route.c:ip6_validate_gw
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
```
**Symbols:**

```
ffffffff81f5ea60-ffffffff81f5ea8e: ipv6_chk_addr_and_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int ipv6_chk_addr_and_flags(struct net *net, const struct in6_addr *addr, const struct net_device *dev, bool skip_dev_check, int strict, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81fbe789)
Location: net/ipv6/addrconf.c:1952
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_addr
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
```
**Symbols:**

```
ffffffff81fbe740-ffffffff81fbe76e: ipv6_chk_addr_and_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int ipv6_chk_addr_and_flags(struct net *net, const struct in6_addr *addr, const struct net_device *dev, bool skip_dev_check, int strict, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8208bc19)
Location: net/ipv6/addrconf.c:1980
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_addr
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
```
**Symbols:**

```
ffffffff8208bbd0-ffffffff8208bbfe: ipv6_chk_addr_and_flags (STB_GLOBAL)
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
int ipv6_chk_addr_and_flags(struct net *net, const struct in6_addr *addr, const struct net_device *dev, bool skip_dev_check, int strict, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffff800010cff8d8)
Location: net/ipv6/addrconf.c:1905
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:ipv6_chk_addr
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
```
**Symbols:**

```
ffff800010cff8d8-ffff800010cffa48: ipv6_chk_addr_and_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ipv6_chk_addr_and_flags(struct net *net, const struct in6_addr *addr, const struct net_device *dev, bool skip_dev_check, int strict, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c0e07e5c)
Location: net/ipv6/addrconf.c:1905
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:ipv6_chk_addr
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
```
**Symbols:**

```
c0e07e5c-c0e07ff8: ipv6_chk_addr_and_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ipv6_chk_addr_and_flags(struct net *net, const struct in6_addr *addr, const struct net_device *dev, bool skip_dev_check, int strict, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c000000000e29560)
Location: net/ipv6/addrconf.c:1905
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:ipv6_chk_addr
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
```
**Symbols:**

```
c000000000e29560-c000000000e29798: ipv6_chk_addr_and_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ipv6_chk_addr_and_flags(struct net *net, const struct in6_addr *addr, const struct net_device *dev, bool skip_dev_check, int strict, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffe00084a1be)
Location: net/ipv6/addrconf.c:1905
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:ipv6_chk_addr
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
```
**Symbols:**

```
ffffffe00084a1be-ffffffe00084a332: ipv6_chk_addr_and_flags (STB_GLOBAL)
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
int ipv6_chk_addr_and_flags(struct net *net, const struct in6_addr *addr, const struct net_device *dev, bool skip_dev_check, int strict, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819de100)
Location: net/ipv6/addrconf.c:1905
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:ipv6_chk_addr
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
```
**Symbols:**

```
ffffffff819de100-ffffffff819de26a: ipv6_chk_addr_and_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ipv6_chk_addr_and_flags(struct net *net, const struct in6_addr *addr, const struct net_device *dev, bool skip_dev_check, int strict, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8199aec0)
Location: net/ipv6/addrconf.c:1905
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:ipv6_chk_addr
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
```
**Symbols:**

```
ffffffff8199aec0-ffffffff8199b02a: ipv6_chk_addr_and_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ipv6_chk_addr_and_flags(struct net *net, const struct in6_addr *addr, const struct net_device *dev, bool skip_dev_check, int strict, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a48b80)
Location: net/ipv6/addrconf.c:1905
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:ipv6_chk_addr
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
```
**Symbols:**

```
ffffffff81a48b80-ffffffff81a48cea: ipv6_chk_addr_and_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ipv6_chk_addr_and_flags(struct net *net, const struct in6_addr *addr, const struct net_device *dev, bool skip_dev_check, int strict, u32 banned_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a54cf0)
Location: net/ipv6/addrconf.c:1905
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:ipv6_chk_addr
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
```
**Symbols:**

```
ffffffff81a54cf0-ffffffff81a54e69: ipv6_chk_addr_and_flags (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool skip_dev_check</code>
</li>
<li>
<b>Param reordered. </b>
<code>net, addr, dev, strict, banned_flags</code> ➡️ <code>net, addr, dev, skip_dev_check, strict, banned_flags</code>
</li>
</ul>
</details>
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
