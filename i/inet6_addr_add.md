# Function: <code>inet6_addr_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int inet6_addr_add(struct net *net, int ifindex, const struct in6_addr *pfx, const struct in6_addr *peer_pfx, unsigned int plen, __u32 ifa_flags, __u32 prefered_lft, __u32 valid_lft);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff817cf280)
Location: net/ipv6/addrconf.c:2633
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
```
**Symbols:**

```
ffffffff817cf280-ffffffff817cf4ae: inet6_addr_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int inet6_addr_add(struct net *net, int ifindex, const struct in6_addr *pfx, const struct in6_addr *peer_pfx, unsigned int plen, __u32 ifa_flags, __u32 prefered_lft, __u32 valid_lft);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8183c940)
Location: net/ipv6/addrconf.c:2713
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
```
**Symbols:**

```
ffffffff8183c940-ffffffff8183cb65: inet6_addr_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int inet6_addr_add(struct net *net, int ifindex, const struct in6_addr *pfx, const struct in6_addr *peer_pfx, unsigned int plen, __u32 ifa_flags, __u32 prefered_lft, __u32 valid_lft);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8186e400)
Location: net/ipv6/addrconf.c:2728
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
```
**Symbols:**

```
ffffffff8186e400-ffffffff8186e625: inet6_addr_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int inet6_addr_add(struct net *net, int ifindex, const struct in6_addr *pfx, const struct in6_addr *peer_pfx, unsigned int plen, __u32 ifa_flags, __u32 prefered_lft, __u32 valid_lft);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff818931c0)
Location: net/ipv6/addrconf.c:2783
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
```
**Symbols:**

```
ffffffff818931c0-ffffffff818933e8: inet6_addr_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int inet6_addr_add(struct net *net, int ifindex, const struct in6_addr *pfx, const struct in6_addr *peer_pfx, unsigned int plen, __u32 ifa_flags, __u32 prefered_lft, __u32 valid_lft, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81914490)
Location: net/ipv6/addrconf.c:2808
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
```
**Symbols:**

```
ffffffff81914490-ffffffff819146c2: inet6_addr_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int inet6_addr_add(struct net *net, int ifindex, struct ifa6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8196bcd0)
Location: net/ipv6/addrconf.c:2838
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
```
**Symbols:**

```
ffffffff8196bcd0-ffffffff8196bf2d: inet6_addr_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int inet6_addr_add(struct net *net, int ifindex, struct ifa6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819a1760)
Location: net/ipv6/addrconf.c:2854
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
```
**Symbols:**

```
ffffffff819a1760-ffffffff819a19c6: inet6_addr_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int inet6_addr_add(struct net *net, int ifindex, struct ifa6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a0d950)
Location: net/ipv6/addrconf.c:2894
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
```
**Symbols:**

```
ffffffff81a0d950-ffffffff81a0dbd9: inet6_addr_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int inet6_addr_add(struct net *net, int ifindex, struct ifa6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a44630)
Location: net/ipv6/addrconf.c:2896
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
```
**Symbols:**

```
ffffffff81a44630-ffffffff81a448b9: inet6_addr_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int inet6_addr_add(struct net *net, int ifindex, struct ifa6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b3aeb0)
Location: net/ipv6/addrconf.c:2857
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
```
**Symbols:**

```
ffffffff81b3aeb0-ffffffff81b3b1ac: inet6_addr_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int inet6_addr_add(struct net *net, int ifindex, struct ifa6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b49bb0)
Location: net/ipv6/addrconf.c:2884
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
```
**Symbols:**

```
ffffffff81b49bb0-ffffffff81b49eb4: inet6_addr_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int inet6_addr_add(struct net *net, int ifindex, struct ifa6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b377d0)
Location: net/ipv6/addrconf.c:2886
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
```
**Symbols:**

```
ffffffff81b377d0-ffffffff81b37aa5: inet6_addr_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int inet6_addr_add(struct net *net, int ifindex, struct ifa6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:2906
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
```
**Symbols:**

```
ffffffff81bfdfb0-ffffffff81bfe294: inet6_addr_add (STB_LOCAL)
ffffffff81d3f9de-ffffffff81d3f9f3: inet6_addr_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int inet6_addr_add(struct net *net, int ifindex, struct ifa6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:2910
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
```
**Symbols:**

```
ffffffff81d979a0-ffffffff81d97c7a: inet6_addr_add (STB_LOCAL)
ffffffff81f0c351-ffffffff81f0c366: inet6_addr_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int inet6_addr_add(struct net *net, int ifindex, struct ifa6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:2910
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
```
**Symbols:**

```
ffffffff81f66610-ffffffff81f668ea: inet6_addr_add (STB_LOCAL)
ffffffff820b3b37-ffffffff820b3b4c: inet6_addr_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int inet6_addr_add(struct net *net, int ifindex, struct ifa6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:2915
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
```
**Symbols:**

```
ffffffff81fc6720-ffffffff81fc69fa: inet6_addr_add (STB_LOCAL)
ffffffff82134c28-ffffffff82134c3d: inet6_addr_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int inet6_addr_add(struct net *net, int ifindex, struct ifa6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:2947
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
```
**Symbols:**

```
ffffffff82093da0-ffffffff82094111: inet6_addr_add (STB_LOCAL)
ffffffff822166ec-ffffffff82216701: inet6_addr_add.cold (STB_LOCAL)
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
int inet6_addr_add(struct net *net, int ifindex, struct ifa6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffff800010d06a50)
Location: net/ipv6/addrconf.c:2896
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
```
**Symbols:**

```
ffff800010d06a50-ffff800010d06cc8: inet6_addr_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int inet6_addr_add(struct net *net, int ifindex, struct ifa6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c0e0d5d4)
Location: net/ipv6/addrconf.c:2896
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
```
**Symbols:**

```
c0e0d5d4-c0e0d89c: inet6_addr_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int inet6_addr_add(struct net *net, int ifindex, struct ifa6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c000000000e30d10)
Location: net/ipv6/addrconf.c:2896
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
```
**Symbols:**

```
c000000000e30d10-c000000000e31084: inet6_addr_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int inet6_addr_add(struct net *net, int ifindex, struct ifa6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffe00084ef18)
Location: net/ipv6/addrconf.c:2896
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
```
**Symbols:**

```
ffffffe00084ef18-ffffffe00084f172: inet6_addr_add (STB_LOCAL)
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
int inet6_addr_add(struct net *net, int ifindex, struct ifa6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819e3cc0)
Location: net/ipv6/addrconf.c:2896
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
```
**Symbols:**

```
ffffffff819e3cc0-ffffffff819e3f49: inet6_addr_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int inet6_addr_add(struct net *net, int ifindex, struct ifa6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819a0a80)
Location: net/ipv6/addrconf.c:2896
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
```
**Symbols:**

```
ffffffff819a0a80-ffffffff819a0d09: inet6_addr_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int inet6_addr_add(struct net *net, int ifindex, struct ifa6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a4e740)
Location: net/ipv6/addrconf.c:2896
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
```
**Symbols:**

```
ffffffff81a4e740-ffffffff81a4e9c9: inet6_addr_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int inet6_addr_add(struct net *net, int ifindex, struct ifa6_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a5a6e0)
Location: net/ipv6/addrconf.c:2896
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
```
**Symbols:**

```
ffffffff81a5a6e0-ffffffff81a5a969: inet6_addr_add (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netlink_ext_ack *extack</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ifa6_config *cfg</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct in6_addr *pfx</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct in6_addr *peer_pfx</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int plen</code>
</li>
<li>
<b>Param removed. </b>
<code>__u32 ifa_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>__u32 prefered_lft</code>
</li>
<li>
<b>Param removed. </b>
<code>__u32 valid_lft</code>
</li>
<li>
<b>Param reordered. </b>
<code>net, ifindex, pfx, peer_pfx, plen, ifa_flags, prefered_lft, valid_lft, extack</code> ➡️ <code>net, ifindex, cfg, extack</code>
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
