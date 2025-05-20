# Function: <code>register_netdevice</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int register_netdevice(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8171e870)
Location: net/core/dev.c:6619
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/core/dev.c:register_netdev
  - net/core/rtnetlink.c:rtnl_newlink
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff8171e870-ffffffff8171ece1: register_netdevice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int register_netdevice(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81787110)
Location: net/core/dev.c:7115
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - net/core/dev.c:register_netdev
  - net/core/rtnetlink.c:rtnl_newlink
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff81787110-ffffffff81787610: register_netdevice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int register_netdevice(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817b46d0)
Location: net/core/dev.c:7285
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - net/core/dev.c:register_netdev
  - net/core/rtnetlink.c:rtnl_newlink
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff817b46d0-ffffffff817b4bd0: register_netdevice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int register_netdevice(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817d3300)
Location: net/core/dev.c:7470
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - net/core/dev.c:register_netdev
  - net/core/rtnetlink.c:rtnl_newlink
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff817d3300-ffffffff817d376f: register_netdevice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int register_netdevice(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8184d6f0)
Location: net/core/dev.c:7643
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - net/core/dev.c:register_netdev
  - net/core/rtnetlink.c:rtnl_newlink
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff8184d6f0-ffffffff8184dc3c: register_netdevice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int register_netdevice(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81898570)
Location: net/core/dev.c:7907
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - net/core/dev.c:register_netdev
  - net/core/rtnetlink.c:rtnl_newlink
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff81898570-ffffffff81898aa0: register_netdevice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int register_netdevice(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818ba9d0)
Location: net/core/dev.c:8534
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - net/core/dev.c:register_netdev
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff818ba9d0-ffffffff818baf00: register_netdevice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int register_netdevice(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819062f0)
Location: net/core/dev.c:8637
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - net/core/dev.c:register_netdev
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff819062f0-ffffffff81906865: register_netdevice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int register_netdevice(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819389e0)
Location: net/core/dev.c:8973
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - net/core/dev.c:register_netdev
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff819389e0-ffffffff81938f5e: register_netdevice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int register_netdevice(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0daa0)
Location: net/core/dev.c:9411
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - net/core/dev.c:register_netdev
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:mif6_add
```
**Symbols:**

```
ffffffff81a0daa0-ffffffff81a0e10a: register_netdevice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int register_netdevice(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0e880)
Location: net/core/dev.c:10041
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - net/core/dev.c:register_netdev
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:mif6_add
```
**Symbols:**

```
ffffffff81a0e880-ffffffff81a0ef1a: register_netdevice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int register_netdevice(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819f5650)
Location: net/core/dev.c:10206
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - net/core/dev.c:register_netdev
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:mif6_add
```
**Symbols:**

```
ffffffff819f5650-ffffffff819f5c5e: register_netdevice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int register_netdevice(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:10213
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - drivers/net/wwan/wwan_core.c:wwan_rtnl_newlink
  - net/core/dev.c:register_netdev
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:mif6_add
```
**Symbols:**

```
ffffffff81d36864-ffffffff81d3688d: register_netdevice.cold (STB_LOCAL)
ffffffff81aa7020-ffffffff81aa7654: register_netdevice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int register_netdevice(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9948
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - drivers/net/wwan/wwan_core.c:wwan_rtnl_newlink
  - net/core/dev.c:register_netdev
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:mif6_add
  - net/mctp/device.c:mctp_register_netdev
```
**Symbols:**

```
ffffffff81f030d2-ffffffff81f030fb: register_netdevice.cold (STB_LOCAL)
ffffffff81c1ef00-ffffffff81c1f579: register_netdevice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int register_netdevice(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9935
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - drivers/net/wwan/wwan_core.c:wwan_rtnl_newlink
  - net/core/dev.c:register_netdev
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:mif6_add
  - net/mctp/device.c:mctp_register_netdev
```
**Symbols:**

```
ffffffff820aba05-ffffffff820aba43: register_netdevice.cold (STB_LOCAL)
ffffffff81dd12f0-ffffffff81dd19e8: register_netdevice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int register_netdevice(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9947
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - drivers/net/wwan/wwan_core.c:wwan_rtnl_newlink
  - net/core/dev.c:register_netdev
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:mif6_add
  - net/mctp/device.c:mctp_register_netdev
```
**Symbols:**

```
ffffffff8212d142-ffffffff8212d180: register_netdevice.cold (STB_LOCAL)
ffffffff81e41ee0-ffffffff81e425cc: register_netdevice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int register_netdevice(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:10132
Inline: False
Direct callers:
  - drivers/net/netkit.c:netkit_new_link
  - drivers/net/netkit.c:netkit_new_link
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - net/core/dev.c:register_netdev
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:mif6_add
  - net/mctp/device.c:mctp_register_netdev
```
**Symbols:**

```
ffffffff8220ee6f-ffffffff8220eeac: register_netdevice.cold (STB_LOCAL)
ffffffff81f00940-ffffffff81f011ff: register_netdevice (STB_GLOBAL)
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
int register_netdevice(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd7400)
Location: net/core/dev.c:8973
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - net/core/dev.c:register_netdev
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffff800010bd7400-ffff800010bd7848: register_netdevice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int register_netdevice(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0cf240c)
Location: net/core/dev.c:8973
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - net/core/dev.c:register_netdev
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
c0cf240c-c0cf2908: register_netdevice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int register_netdevice(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cb72d0)
Location: net/core/dev.c:8973
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - net/core/dev.c:register_netdev
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
c000000000cb72d0-c000000000cb7828: register_netdevice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int register_netdevice(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000760a7a)
Location: net/core/dev.c:8973
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - net/core/dev.c:register_netdev
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffe000760a7a-ffffffe000760e38: register_netdevice (STB_GLOBAL)
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
int register_netdevice(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d89b0)
Location: net/core/dev.c:8973
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - net/core/dev.c:register_netdev
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff818d89b0-ffffffff818d8f2e: register_netdevice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int register_netdevice(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818927f0)
Location: net/core/dev.c:8973
Inline: False
Direct callers:
  - drivers/net/vxlan.c:__vxlan_dev_create
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - net/core/dev.c:register_netdev
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/ipv4/ip_tunnel.c:ip_tunnel_newlink
  - net/ipv4/ip_tunnel.c:__ip_tunnel_create
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff818927f0-ffffffff81892d6e: register_netdevice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int register_netdevice(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819299e0)
Location: net/core/dev.c:8973
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - net/core/dev.c:register_netdev
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff819299e0-ffffffff81929f5e: register_netdevice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int register_netdevice(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8194b0b0)
Location: net/core/dev.c:8973
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - net/core/dev.c:register_netdev
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff8194b0b0-ffffffff8194b629: register_netdevice (STB_GLOBAL)
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
