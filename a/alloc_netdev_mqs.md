# Function: <code>alloc_netdev_mqs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct net_device *alloc_netdev_mqs(int sizeof_priv, const char *name, unsigned char name_assign_type, void (*setup)(struct net_device *), unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8171b9d0)
Location: net/core/dev.c:7062
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/core/rtnetlink.c:rtnl_create_link
  - net/ethernet/eth.c:alloc_etherdev_mqs
  - net/802/fc.c:alloc_fcdev
  - net/802/fddi.c:alloc_fddidev
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff8171b9d0-ffffffff8171be09: alloc_netdev_mqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct net_device *alloc_netdev_mqs(int sizeof_priv, const char *name, unsigned char name_assign_type, void (*setup)(struct net_device *), unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81784280)
Location: net/core/dev.c:7579
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/core/rtnetlink.c:rtnl_create_link
  - net/ethernet/eth.c:alloc_etherdev_mqs
  - net/802/fc.c:alloc_fcdev
  - net/802/fddi.c:alloc_fddidev
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff81784280-ffffffff81784693: alloc_netdev_mqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct net_device *alloc_netdev_mqs(int sizeof_priv, const char *name, unsigned char name_assign_type, void (*setup)(struct net_device *), unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817b1890)
Location: net/core/dev.c:7749
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/core/rtnetlink.c:rtnl_create_link
  - net/ethernet/eth.c:alloc_etherdev_mqs
  - net/802/fc.c:alloc_fcdev
  - net/802/fddi.c:alloc_fddidev
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff817b1890-ffffffff817b1c8d: alloc_netdev_mqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct net_device *alloc_netdev_mqs(int sizeof_priv, const char *name, unsigned char name_assign_type, void (*setup)(struct net_device *), unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817cb600)
Location: net/core/dev.c:7938
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/core/rtnetlink.c:rtnl_create_link
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
  - net/802/fc.c:alloc_fcdev
  - net/802/fddi.c:alloc_fddidev
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff817cb600-ffffffff817cb9be: alloc_netdev_mqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct net_device *alloc_netdev_mqs(int sizeof_priv, const char *name, unsigned char name_assign_type, void (*setup)(struct net_device *), unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81844e50)
Location: net/core/dev.c:8117
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/core/rtnetlink.c:rtnl_create_link
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
  - net/802/fc.c:alloc_fcdev
  - net/802/fddi.c:alloc_fddidev
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff81844e50-ffffffff8184520d: alloc_netdev_mqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct net_device *alloc_netdev_mqs(int sizeof_priv, const char *name, unsigned char name_assign_type, void (*setup)(struct net_device *), unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8380
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/core/rtnetlink.c:rtnl_create_link
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
  - net/802/fc.c:alloc_fcdev
  - net/802/fddi.c:alloc_fddidev
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff81898fe7-ffffffff8189900d: alloc_netdev_mqs.cold.157 (STB_LOCAL)
ffffffff818910b0-ffffffff81891497: alloc_netdev_mqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct net_device *alloc_netdev_mqs(int sizeof_priv, const char *name, unsigned char name_assign_type, void (*setup)(struct net_device *), unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9010
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/core/rtnetlink.c:rtnl_create_link
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
  - net/802/fc.c:alloc_fcdev
  - net/802/fddi.c:alloc_fddidev
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff818bb43f-ffffffff818bb465: alloc_netdev_mqs.cold.165 (STB_LOCAL)
ffffffff818b16e0-ffffffff818b1abf: alloc_netdev_mqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct net_device *alloc_netdev_mqs(int sizeof_priv, const char *name, unsigned char name_assign_type, void (*setup)(struct net_device *), unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9115
Inline: False
Direct callers:
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/core/rtnetlink.c:rtnl_create_link
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
  - net/802/fc.c:alloc_fcdev
  - net/802/fddi.c:alloc_fddidev
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff8190733d-ffffffff81907363: alloc_netdev_mqs.cold (STB_LOCAL)
ffffffff818fe480-ffffffff818fe85f: alloc_netdev_mqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct net_device *alloc_netdev_mqs(int sizeof_priv, const char *name, unsigned char name_assign_type, void (*setup)(struct net_device *), unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9453
Inline: False
Direct callers:
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/core/rtnetlink.c:rtnl_create_link
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
  - net/802/fc.c:alloc_fcdev
  - net/802/fddi.c:alloc_fddidev
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff8193998a-ffffffff819399b0: alloc_netdev_mqs.cold (STB_LOCAL)
ffffffff819307b0-ffffffff81930b9c: alloc_netdev_mqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct net_device *alloc_netdev_mqs(int sizeof_priv, const char *name, unsigned char name_assign_type, void (*setup)(struct net_device *), unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9909
Inline: False
Direct callers:
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/loopback.c:loopback_net_init
  - net/core/rtnetlink.c:rtnl_create_link
  - net/ethernet/eth.c:alloc_etherdev_mqs
  - net/802/fc.c:alloc_fcdev
  - net/802/fddi.c:alloc_fddidev
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:mif6_add
```
**Symbols:**

```
ffffffff81a0eed6-ffffffff81a0eefe: alloc_netdev_mqs.cold (STB_LOCAL)
ffffffff81a043e0-ffffffff81a0471f: alloc_netdev_mqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct net_device *alloc_netdev_mqs(int sizeof_priv, const char *name, unsigned char name_assign_type, void (*setup)(struct net_device *), unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:10603
Inline: False
Direct callers:
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/loopback.c:loopback_net_init
  - net/core/rtnetlink.c:rtnl_create_link
  - net/ethernet/eth.c:alloc_etherdev_mqs
  - net/802/fc.c:alloc_fcdev
  - net/802/fddi.c:alloc_fddidev
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:mif6_add
```
**Symbols:**

```
ffffffff81c3121c-ffffffff81c31250: alloc_netdev_mqs.cold (STB_LOCAL)
ffffffff81a06440-ffffffff81a06795: alloc_netdev_mqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct net_device *alloc_netdev_mqs(int sizeof_priv, const char *name, unsigned char name_assign_type, void (*setup)(struct net_device *), unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:10775
Inline: False
Direct callers:
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/loopback.c:loopback_net_init
  - net/core/rtnetlink.c:rtnl_create_link
  - net/ethernet/eth.c:alloc_etherdev_mqs
  - net/802/fc.c:alloc_fcdev
  - net/802/fddi.c:alloc_fddidev
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:mif6_add
```
**Symbols:**

```
ffffffff81c23516-ffffffff81c23548: alloc_netdev_mqs.cold (STB_LOCAL)
ffffffff819ecf90-ffffffff819ed3a6: alloc_netdev_mqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct net_device *alloc_netdev_mqs(int sizeof_priv, const char *name, unsigned char name_assign_type, void (*setup)(struct net_device *), unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:10782
Inline: False
Direct callers:
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/loopback.c:loopback_net_init
  - drivers/net/wwan/wwan_core.c:wwan_rtnl_alloc
  - net/core/rtnetlink.c:rtnl_create_link
  - net/ethernet/eth.c:alloc_etherdev_mqs
  - net/802/fc.c:alloc_fcdev
  - net/802/fddi.c:alloc_fddidev
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:mif6_add
```
**Symbols:**

```
ffffffff81d3626b-ffffffff81d362a9: alloc_netdev_mqs.cold (STB_LOCAL)
ffffffff81a9e1a0-ffffffff81a9e5c7: alloc_netdev_mqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct net_device *alloc_netdev_mqs(int sizeof_priv, const char *name, unsigned char name_assign_type, void (*setup)(struct net_device *), unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:10555
Inline: False
Direct callers:
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/loopback.c:loopback_net_init
  - drivers/net/wwan/wwan_core.c:wwan_rtnl_alloc
  - net/core/rtnetlink.c:rtnl_create_link
  - net/ethernet/eth.c:alloc_etherdev_mqs
  - net/802/fc.c:alloc_fcdev
  - net/802/fddi.c:alloc_fddidev
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:mif6_add
```
**Symbols:**

```
ffffffff81f027d6-ffffffff81f02804: alloc_netdev_mqs.cold (STB_LOCAL)
ffffffff81c129c0-ffffffff81c12dfa: alloc_netdev_mqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct net_device *alloc_netdev_mqs(int sizeof_priv, const char *name, unsigned char name_assign_type, void (*setup)(struct net_device *), unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc2ae0)
Location: net/core/dev.c:10550
Inline: False
Direct callers:
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/loopback.c:loopback_net_init
  - drivers/net/wwan/wwan_core.c:wwan_rtnl_alloc
  - net/core/rtnetlink.c:rtnl_create_link
  - net/ethernet/eth.c:alloc_etherdev_mqs
  - net/802/fc.c:alloc_fcdev
  - net/802/fddi.c:alloc_fddidev
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:mif6_add
```
**Symbols:**

```
ffffffff81dc2ae0-ffffffff81dc2f49: alloc_netdev_mqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct net_device *alloc_netdev_mqs(int sizeof_priv, const char *name, unsigned char name_assign_type, void (*setup)(struct net_device *), unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e31f90)
Location: net/core/dev.c:10564
Inline: False
Direct callers:
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/loopback.c:loopback_net_init
  - drivers/net/wwan/wwan_core.c:wwan_rtnl_alloc
  - net/core/rtnetlink.c:rtnl_create_link
  - net/ethernet/eth.c:alloc_etherdev_mqs
  - net/802/fc.c:alloc_fcdev
  - net/802/fddi.c:alloc_fddidev
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:mif6_add
```
**Symbols:**

```
ffffffff81e31f90-ffffffff81e323ee: alloc_netdev_mqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct net_device *alloc_netdev_mqs(int sizeof_priv, const char *name, unsigned char name_assign_type, void (*setup)(struct net_device *), unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef0410)
Location: net/core/dev.c:10774
Inline: False
Direct callers:
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/loopback.c:loopback_net_init
  - net/core/rtnetlink.c:rtnl_create_link
  - net/ethernet/eth.c:alloc_etherdev_mqs
  - net/802/fc.c:alloc_fcdev
  - net/802/fddi.c:alloc_fddidev
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:mif6_add
```
**Symbols:**

```
ffffffff81ef0410-ffffffff81ef08a1: alloc_netdev_mqs (STB_GLOBAL)
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
struct net_device *alloc_netdev_mqs(int sizeof_priv, const char *name, unsigned char name_assign_type, void (*setup)(struct net_device *), unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bcc6d8)
Location: net/core/dev.c:9453
Inline: False
Direct callers:
  - drivers/net/loopback.c:blackhole_netdev_init
  - net/core/rtnetlink.c:rtnl_create_link
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
  - net/802/fc.c:alloc_fcdev
  - net/802/fddi.c:alloc_fddidev
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffff800010bcc6d8-ffff800010bcca5c: alloc_netdev_mqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct net_device *alloc_netdev_mqs(int sizeof_priv, const char *name, unsigned char name_assign_type, void (*setup)(struct net_device *), unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce6ab0)
Location: net/core/dev.c:9453
Inline: False
Direct callers:
  - drivers/net/loopback.c:blackhole_netdev_init
  - net/core/rtnetlink.c:rtnl_create_link
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
  - net/802/fc.c:alloc_fcdev
  - net/802/fddi.c:alloc_fddidev
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
c0ce6ab0-c0ce6df4: alloc_netdev_mqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct net_device *alloc_netdev_mqs(int sizeof_priv, const char *name, unsigned char name_assign_type, void (*setup)(struct net_device *), unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cab9e0)
Location: net/core/dev.c:9453
Inline: False
Direct callers:
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/loopback.c:loopback_net_init
  - net/core/rtnetlink.c:rtnl_create_link
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
  - net/802/fc.c:alloc_fcdev
  - net/802/fddi.c:alloc_fddidev
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
c000000000cab9e0-c000000000cabec8: alloc_netdev_mqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct net_device *alloc_netdev_mqs(int sizeof_priv, const char *name, unsigned char name_assign_type, void (*setup)(struct net_device *), unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000758166)
Location: net/core/dev.c:9453
Inline: False
Direct callers:
  - drivers/net/loopback.c:blackhole_netdev_init
  - net/core/rtnetlink.c:rtnl_create_link
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
  - net/802/fc.c:alloc_fcdev
  - net/802/fddi.c:alloc_fddidev
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffe000758166-ffffffe000758476: alloc_netdev_mqs (STB_GLOBAL)
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
struct net_device *alloc_netdev_mqs(int sizeof_priv, const char *name, unsigned char name_assign_type, void (*setup)(struct net_device *), unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9453
Inline: False
Direct callers:
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/core/rtnetlink.c:rtnl_create_link
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
  - net/802/fc.c:alloc_fcdev
  - net/802/fddi.c:alloc_fddidev
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff818d995a-ffffffff818d9980: alloc_netdev_mqs.cold (STB_LOCAL)
ffffffff818d07b0-ffffffff818d0b9c: alloc_netdev_mqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct net_device *alloc_netdev_mqs(int sizeof_priv, const char *name, unsigned char name_assign_type, void (*setup)(struct net_device *), unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9453
Inline: False
Direct callers:
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/core/rtnetlink.c:rtnl_create_link
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
  - net/802/fddi.c:alloc_fddidev
  - net/ipv4/ip_tunnel.c:__ip_tunnel_create
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff8189379a-ffffffff818937c0: alloc_netdev_mqs.cold (STB_LOCAL)
ffffffff8188a690-ffffffff8188aa7c: alloc_netdev_mqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct net_device *alloc_netdev_mqs(int sizeof_priv, const char *name, unsigned char name_assign_type, void (*setup)(struct net_device *), unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9453
Inline: False
Direct callers:
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/core/rtnetlink.c:rtnl_create_link
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
  - net/802/fc.c:alloc_fcdev
  - net/802/fddi.c:alloc_fddidev
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff8192a98a-ffffffff8192a9b0: alloc_netdev_mqs.cold (STB_LOCAL)
ffffffff819217b0-ffffffff81921b9c: alloc_netdev_mqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct net_device *alloc_netdev_mqs(int sizeof_priv, const char *name, unsigned char name_assign_type, void (*setup)(struct net_device *), unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9453
Inline: False
Direct callers:
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/core/rtnetlink.c:rtnl_create_link
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
  - net/802/fc.c:alloc_fcdev
  - net/802/fddi.c:alloc_fddidev
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff8194bfd3-ffffffff8194bff9: alloc_netdev_mqs.cold (STB_LOCAL)
ffffffff81940180-ffffffff8194056c: alloc_netdev_mqs (STB_GLOBAL)
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
