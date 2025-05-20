# Function: <code>ipv6_add_addr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct inet6_ifaddr *ipv6_add_addr(struct inet6_dev *idev, const struct in6_addr *addr, const struct in6_addr *peer_addr, int pfxlen, int scope, u32 flags, u32 valid_lft, u32 prefered_lft);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff817ca480)
Location: net/ipv6/addrconf.c:899
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
**Symbols:**

```
ffffffff817ca480-ffffffff817ca87c: ipv6_add_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct inet6_ifaddr *ipv6_add_addr(struct inet6_dev *idev, const struct in6_addr *addr, const struct in6_addr *peer_addr, int pfxlen, int scope, u32 flags, u32 valid_lft, u32 prefered_lft);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81837650)
Location: net/ipv6/addrconf.c:913
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
```
**Symbols:**

```
ffffffff81837650-ffffffff81837aa1: ipv6_add_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct inet6_ifaddr *ipv6_add_addr(struct inet6_dev *idev, const struct in6_addr *addr, const struct in6_addr *peer_addr, int pfxlen, int scope, u32 flags, u32 valid_lft, u32 prefered_lft);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81869140)
Location: net/ipv6/addrconf.c:940
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
```
**Symbols:**

```
ffffffff81869140-ffffffff81869594: ipv6_add_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct inet6_ifaddr *ipv6_add_addr(struct inet6_dev *idev, const struct in6_addr *addr, const struct in6_addr *peer_addr, int pfxlen, int scope, u32 flags, u32 valid_lft, u32 prefered_lft);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8188fda0)
Location: net/ipv6/addrconf.c:959
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
```
**Symbols:**

```
ffffffff8188fda0-ffffffff81890302: ipv6_add_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct inet6_ifaddr *ipv6_add_addr(struct inet6_dev *idev, const struct in6_addr *addr, const struct in6_addr *peer_addr, int pfxlen, int scope, u32 flags, u32 valid_lft, u32 prefered_lft, bool can_block, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819114a0)
Location: net/ipv6/addrconf.c:1001
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
```
**Symbols:**

```
ffffffff819114a0-ffffffff81911a53: ipv6_add_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct inet6_ifaddr *ipv6_add_addr(struct inet6_dev *idev, struct ifa6_config *cfg, bool can_block, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81968890)
Location: net/ipv6/addrconf.c:989
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
```
**Symbols:**

```
ffffffff81968890-ffffffff81968e8a: ipv6_add_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct inet6_ifaddr *ipv6_add_addr(struct inet6_dev *idev, struct ifa6_config *cfg, bool can_block, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8199e1d0)
Location: net/ipv6/addrconf.c:1003
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
```
**Symbols:**

```
ffffffff8199e1d0-ffffffff8199e76e: ipv6_add_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct inet6_ifaddr *ipv6_add_addr(struct inet6_dev *idev, struct ifa6_config *cfg, bool can_block, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a0a2c0)
Location: net/ipv6/addrconf.c:1037
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
```
**Symbols:**

```
ffffffff81a0a2c0-ffffffff81a0a897: ipv6_add_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct inet6_ifaddr *ipv6_add_addr(struct inet6_dev *idev, struct ifa6_config *cfg, bool can_block, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a40f70)
Location: net/ipv6/addrconf.c:1037
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
```
**Symbols:**

```
ffffffff81a40f70-ffffffff81a4154a: ipv6_add_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct inet6_ifaddr *ipv6_add_addr(struct inet6_dev *idev, struct ifa6_config *cfg, bool can_block, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b36a40)
Location: net/ipv6/addrconf.c:1037
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
**Symbols:**

```
ffffffff81b36a40-ffffffff81b36fe3: ipv6_add_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct inet6_ifaddr *ipv6_add_addr(struct inet6_dev *idev, struct ifa6_config *cfg, bool can_block, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b45770)
Location: net/ipv6/addrconf.c:1037
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
**Symbols:**

```
ffffffff81b45770-ffffffff81b45d13: ipv6_add_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct inet6_ifaddr *ipv6_add_addr(struct inet6_dev *idev, struct ifa6_config *cfg, bool can_block, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b334b0)
Location: net/ipv6/addrconf.c:1039
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
**Symbols:**

```
ffffffff81b334b0-ffffffff81b33b82: ipv6_add_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct inet6_ifaddr *ipv6_add_addr(struct inet6_dev *idev, struct ifa6_config *cfg, bool can_block, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81bf9b20)
Location: net/ipv6/addrconf.c:1046
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
**Symbols:**

```
ffffffff81bf9b20-ffffffff81bfa1f2: ipv6_add_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct inet6_ifaddr *ipv6_add_addr(struct inet6_dev *idev, struct ifa6_config *cfg, bool can_block, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81d92f20)
Location: net/ipv6/addrconf.c:1055
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
**Symbols:**

```
ffffffff81d92f20-ffffffff81d935b4: ipv6_add_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct inet6_ifaddr *ipv6_add_addr(struct inet6_dev *idev, struct ifa6_config *cfg, bool can_block, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81f616b0)
Location: net/ipv6/addrconf.c:1055
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
**Symbols:**

```
ffffffff81f616b0-ffffffff81f61d3c: ipv6_add_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct inet6_ifaddr *ipv6_add_addr(struct inet6_dev *idev, struct ifa6_config *cfg, bool can_block, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81fc14e0)
Location: net/ipv6/addrconf.c:1054
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
**Symbols:**

```
ffffffff81fc14e0-ffffffff81fc1b2b: ipv6_add_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct inet6_ifaddr *ipv6_add_addr(struct inet6_dev *idev, struct ifa6_config *cfg, bool can_block, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8208e9c0)
Location: net/ipv6/addrconf.c:1073
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
**Symbols:**

```
ffffffff8208e9c0-ffffffff8208f092: ipv6_add_addr (STB_LOCAL)
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
struct inet6_ifaddr *ipv6_add_addr(struct inet6_dev *idev, struct ifa6_config *cfg, bool can_block, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffff800010d02a60)
Location: net/ipv6/addrconf.c:1037
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
```
**Symbols:**

```
ffff800010d02a60-ffff800010d02f6c: ipv6_add_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct inet6_ifaddr *ipv6_add_addr(struct inet6_dev *idev, struct ifa6_config *cfg, bool can_block, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c0e09714)
Location: net/ipv6/addrconf.c:1037
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
```
**Symbols:**

```
c0e09714-c0e09c78: ipv6_add_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct inet6_ifaddr *ipv6_add_addr(struct inet6_dev *idev, struct ifa6_config *cfg, bool can_block, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c000000000e2a3f0)
Location: net/ipv6/addrconf.c:1037
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
```
**Symbols:**

```
c000000000e2a3f0-c000000000e2aaf0: ipv6_add_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct inet6_ifaddr *ipv6_add_addr(struct inet6_dev *idev, struct ifa6_config *cfg, bool can_block, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffe00084bdd2)
Location: net/ipv6/addrconf.c:1037
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
```
**Symbols:**

```
ffffffe00084bdd2-ffffffe00084c2d6: ipv6_add_addr (STB_LOCAL)
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
struct inet6_ifaddr *ipv6_add_addr(struct inet6_dev *idev, struct ifa6_config *cfg, bool can_block, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819e0600)
Location: net/ipv6/addrconf.c:1037
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
```
**Symbols:**

```
ffffffff819e0600-ffffffff819e0bda: ipv6_add_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct inet6_ifaddr *ipv6_add_addr(struct inet6_dev *idev, struct ifa6_config *cfg, bool can_block, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8199d3c0)
Location: net/ipv6/addrconf.c:1037
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
```
**Symbols:**

```
ffffffff8199d3c0-ffffffff8199d99a: ipv6_add_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct inet6_ifaddr *ipv6_add_addr(struct inet6_dev *idev, struct ifa6_config *cfg, bool can_block, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a4b080)
Location: net/ipv6/addrconf.c:1037
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
```
**Symbols:**

```
ffffffff81a4b080-ffffffff81a4b65a: ipv6_add_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct inet6_ifaddr *ipv6_add_addr(struct inet6_dev *idev, struct ifa6_config *cfg, bool can_block, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a56fe0)
Location: net/ipv6/addrconf.c:1037
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
```
**Symbols:**

```
ffffffff81a56fe0-ffffffff81a575cf: ipv6_add_addr (STB_LOCAL)
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
<code>bool can_block</code>
</li>
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
<code>const struct in6_addr *addr</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct in6_addr *peer_addr</code>
</li>
<li>
<b>Param removed. </b>
<code>int pfxlen</code>
</li>
<li>
<b>Param removed. </b>
<code>int scope</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 flags</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 valid_lft</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 prefered_lft</code>
</li>
<li>
<b>Param reordered. </b>
<code>idev, addr, peer_addr, pfxlen, scope, flags, valid_lft, prefered_lft, can_block, extack</code> ➡️ <code>idev, cfg, can_block, extack</code>
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
