# Function: <code>ipv6_dev_get_saddr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ipv6_dev_get_saddr(struct net *net, const struct net_device *dst_dev, const struct in6_addr *daddr, unsigned int prefs, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff817ce3e0)
Location: net/ipv6/addrconf.c:1520
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_get_saddr
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/fib6_rules.c:fib6_rule_action
```
**Symbols:**

```
ffffffff817ce3e0-ffffffff817ce614: ipv6_dev_get_saddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ipv6_dev_get_saddr(struct net *net, const struct net_device *dst_dev, const struct in6_addr *daddr, unsigned int prefs, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8183b9e0)
Location: net/ipv6/addrconf.c:1556
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/fib6_rules.c:fib6_rule_action
```
**Symbols:**

```
ffffffff8183b9e0-ffffffff8183bcf7: ipv6_dev_get_saddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ipv6_dev_get_saddr(struct net *net, const struct net_device *dst_dev, const struct in6_addr *daddr, unsigned int prefs, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8186d3e0)
Location: net/ipv6/addrconf.c:1604
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
**Symbols:**

```
ffffffff8186d3e0-ffffffff8186d6f7: ipv6_dev_get_saddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ipv6_dev_get_saddr(struct net *net, const struct net_device *dst_dev, const struct in6_addr *daddr, unsigned int prefs, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81892210)
Location: net/ipv6/addrconf.c:1646
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
**Symbols:**

```
ffffffff81892210-ffffffff81892567: ipv6_dev_get_saddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ipv6_dev_get_saddr(struct net *net, const struct net_device *dst_dev, const struct in6_addr *daddr, unsigned int prefs, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8190f560)
Location: net/ipv6/addrconf.c:1690
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
**Symbols:**

```
ffffffff8190f560-ffffffff8190f899: ipv6_dev_get_saddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ipv6_dev_get_saddr(struct net *net, const struct net_device *dst_dev, const struct in6_addr *daddr, unsigned int prefs, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81966650)
Location: net/ipv6/addrconf.c:1691
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
**Symbols:**

```
ffffffff81966650-ffffffff81966953: ipv6_dev_get_saddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ipv6_dev_get_saddr(struct net *net, const struct net_device *dst_dev, const struct in6_addr *daddr, unsigned int prefs, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8199bc70)
Location: net/ipv6/addrconf.c:1707
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
**Symbols:**

```
ffffffff8199bc70-ffffffff8199bf73: ipv6_dev_get_saddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ipv6_dev_get_saddr(struct net *net, const struct net_device *dst_dev, const struct in6_addr *daddr, unsigned int prefs, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a07a50)
Location: net/ipv6/addrconf.c:1740
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
**Symbols:**

```
ffffffff81a07a50-ffffffff81a07c9e: ipv6_dev_get_saddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ipv6_dev_get_saddr(struct net *net, const struct net_device *dst_dev, const struct in6_addr *daddr, unsigned int prefs, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a3e5c0)
Location: net/ipv6/addrconf.c:1742
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
**Symbols:**

```
ffffffff81a3e5c0-ffffffff81a3e80e: ipv6_dev_get_saddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ipv6_dev_get_saddr(struct net *net, const struct net_device *dst_dev, const struct in6_addr *daddr, unsigned int prefs, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b33470)
Location: net/ipv6/addrconf.c:1733
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
**Symbols:**

```
ffffffff81b33470-ffffffff81b336ac: ipv6_dev_get_saddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ipv6_dev_get_saddr(struct net *net, const struct net_device *dst_dev, const struct in6_addr *daddr, unsigned int prefs, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b41da0)
Location: net/ipv6/addrconf.c:1733
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
**Symbols:**

```
ffffffff81b41da0-ffffffff81b41fe6: ipv6_dev_get_saddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ipv6_dev_get_saddr(struct net *net, const struct net_device *dst_dev, const struct in6_addr *daddr, unsigned int prefs, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b2fa90)
Location: net/ipv6/addrconf.c:1735
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
**Symbols:**

```
ffffffff81b2fa90-ffffffff81b2fcd6: ipv6_dev_get_saddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ipv6_dev_get_saddr(struct net *net, const struct net_device *dst_dev, const struct in6_addr *daddr, unsigned int prefs, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81bf5e00)
Location: net/ipv6/addrconf.c:1742
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
**Symbols:**

```
ffffffff81bf5e00-ffffffff81bf6095: ipv6_dev_get_saddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ipv6_dev_get_saddr(struct net *net, const struct net_device *dst_dev, const struct in6_addr *daddr, unsigned int prefs, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81d8eff0)
Location: net/ipv6/addrconf.c:1749
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/fib6_rules.c:fib6_rule_saddr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
```
**Symbols:**

```
ffffffff81d8eff0-ffffffff81d8f346: ipv6_dev_get_saddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ipv6_dev_get_saddr(struct net *net, const struct net_device *dst_dev, const struct in6_addr *daddr, unsigned int prefs, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81f5ceb0)
Location: net/ipv6/addrconf.c:1749
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/fib6_rules.c:fib6_rule_saddr
  - net/ipv6/seg6_iptunnel.c:set_tun_src
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
```
**Symbols:**

```
ffffffff81f5ceb0-ffffffff81f5d206: ipv6_dev_get_saddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ipv6_dev_get_saddr(struct net *net, const struct net_device *dst_dev, const struct in6_addr *daddr, unsigned int prefs, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81fbcbd0)
Location: net/ipv6/addrconf.c:1748
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/fib6_rules.c:fib6_rule_saddr
  - net/ipv6/seg6_iptunnel.c:set_tun_src
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
```
**Symbols:**

```
ffffffff81fbcbd0-ffffffff81fbcf26: ipv6_dev_get_saddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ipv6_dev_get_saddr(struct net *net, const struct net_device *dst_dev, const struct in6_addr *daddr, unsigned int prefs, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8208a000)
Location: net/ipv6/addrconf.c:1776
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/fib6_rules.c:fib6_rule_saddr
  - net/ipv6/seg6_iptunnel.c:set_tun_src
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
```
**Symbols:**

```
ffffffff8208a000-ffffffff8208a35c: ipv6_dev_get_saddr (STB_GLOBAL)
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
int ipv6_dev_get_saddr(struct net *net, const struct net_device *dst_dev, const struct in6_addr *daddr, unsigned int prefs, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffff800010cff5b8)
Location: net/ipv6/addrconf.c:1742
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
**Symbols:**

```
ffff800010cff5b8-ffff800010cff7e0: ipv6_dev_get_saddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ipv6_dev_get_saddr(struct net *net, const struct net_device *dst_dev, const struct in6_addr *daddr, unsigned int prefs, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c0e07adc)
Location: net/ipv6/addrconf.c:1742
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
**Symbols:**

```
c0e07adc-c0e07d4c: ipv6_dev_get_saddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ipv6_dev_get_saddr(struct net *net, const struct net_device *dst_dev, const struct in6_addr *daddr, unsigned int prefs, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c000000000e28c90)
Location: net/ipv6/addrconf.c:1742
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
**Symbols:**

```
c000000000e28c90-c000000000e28f8c: ipv6_dev_get_saddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ipv6_dev_get_saddr(struct net *net, const struct net_device *dst_dev, const struct in6_addr *daddr, unsigned int prefs, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffe000849ea4)
Location: net/ipv6/addrconf.c:1742
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
**Symbols:**

```
ffffffe000849ea4-ffffffe00084a076: ipv6_dev_get_saddr (STB_GLOBAL)
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
int ipv6_dev_get_saddr(struct net *net, const struct net_device *dst_dev, const struct in6_addr *daddr, unsigned int prefs, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819ddc50)
Location: net/ipv6/addrconf.c:1742
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
**Symbols:**

```
ffffffff819ddc50-ffffffff819dde9e: ipv6_dev_get_saddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ipv6_dev_get_saddr(struct net *net, const struct net_device *dst_dev, const struct in6_addr *daddr, unsigned int prefs, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8199aa10)
Location: net/ipv6/addrconf.c:1742
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
**Symbols:**

```
ffffffff8199aa10-ffffffff8199ac5e: ipv6_dev_get_saddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ipv6_dev_get_saddr(struct net *net, const struct net_device *dst_dev, const struct in6_addr *daddr, unsigned int prefs, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a486d0)
Location: net/ipv6/addrconf.c:1742
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
**Symbols:**

```
ffffffff81a486d0-ffffffff81a4891e: ipv6_dev_get_saddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ipv6_dev_get_saddr(struct net *net, const struct net_device *dst_dev, const struct in6_addr *daddr, unsigned int prefs, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a54600)
Location: net/ipv6/addrconf.c:1742
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
**Symbols:**

```
ffffffff81a54600-ffffffff81a548f7: ipv6_dev_get_saddr (STB_GLOBAL)
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
