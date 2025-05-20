# Function: <code>__ethtool_get_link_ksettings</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int __ethtool_get_link_ksettings(struct net_device *dev, struct ethtool_link_ksettings *link_ksettings);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff817888b0)
Location: net/core/ethtool.c:544
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff817888b0-ffffffff817889da: __ethtool_get_link_ksettings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int __ethtool_get_link_ksettings(struct net_device *dev, struct ethtool_link_ksettings *link_ksettings);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff817b5ff0)
Location: net/core/ethtool.c:555
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff817b5ff0-ffffffff817b611a: __ethtool_get_link_ksettings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __ethtool_get_link_ksettings(struct net_device *dev, struct ethtool_link_ksettings *link_ksettings);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff817d3de0)
Location: net/core/ethtool.c:558
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff817d3de0-ffffffff817d3f07: __ethtool_get_link_ksettings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __ethtool_get_link_ksettings(struct net_device *dev, struct ethtool_link_ksettings *link_ksettings);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff8184e2c0)
Location: net/core/ethtool.c:572
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff8184e2c0-ffffffff8184e3f3: __ethtool_get_link_ksettings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __ethtool_get_link_ksettings(struct net_device *dev, struct ethtool_link_ksettings *link_ksettings);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff81899420)
Location: net/core/ethtool.c:551
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81899420-ffffffff81899568: __ethtool_get_link_ksettings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __ethtool_get_link_ksettings(struct net_device *dev, struct ethtool_link_ksettings *link_ksettings);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff818bb800)
Location: net/core/ethtool.c:544
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff818bb800-ffffffff818bb8aa: __ethtool_get_link_ksettings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __ethtool_get_link_ksettings(struct net_device *dev, struct ethtool_link_ksettings *link_ksettings);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff819077f0)
Location: net/core/ethtool.c:543
Inline: False
Direct callers:
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff819077f0-ffffffff8190789d: __ethtool_get_link_ksettings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __ethtool_get_link_ksettings(struct net_device *dev, struct ethtool_link_ksettings *link_ksettings);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff81939da0)
Location: net/core/ethtool.c:544
Inline: False
Direct callers:
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81939da0-ffffffff81939e4d: __ethtool_get_link_ksettings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __ethtool_get_link_ksettings(struct net_device *dev, struct ethtool_link_ksettings *link_ksettings);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81a7f4f0)
Location: net/ethtool/ioctl.c:422
Inline: False
Direct callers:
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkinfo.c:linkinfo_prepare_data
  - net/ethtool/linkinfo.c:linkinfo_prepare_data
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
  - net/ethtool/linkmodes.c:linkmodes_prepare_data
  - net/packet/af_packet.c:init_prb_bdqc
```
**Symbols:**

```
ffffffff81a7f4f0-ffffffff81a7f59d: __ethtool_get_link_ksettings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __ethtool_get_link_ksettings(struct net_device *dev, struct ethtool_link_ksettings *link_ksettings);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81a89010)
Location: net/ethtool/ioctl.c:426
Inline: False
Direct callers:
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkinfo.c:linkinfo_prepare_data
  - net/ethtool/linkinfo.c:linkinfo_prepare_data
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
  - net/ethtool/linkmodes.c:linkmodes_prepare_data
  - net/packet/af_packet.c:init_prb_bdqc
```
**Symbols:**

```
ffffffff81a89010-ffffffff81a890bd: __ethtool_get_link_ksettings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __ethtool_get_link_ksettings(struct net_device *dev, struct ethtool_link_ksettings *link_ksettings);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81a726a0)
Location: net/ethtool/ioctl.c:426
Inline: False
Direct callers:
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkinfo.c:linkinfo_prepare_data
  - net/ethtool/linkinfo.c:linkinfo_prepare_data
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
  - net/ethtool/linkmodes.c:linkmodes_prepare_data
```
**Symbols:**

```
ffffffff81a726a0-ffffffff81a7274d: __ethtool_get_link_ksettings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __ethtool_get_link_ksettings(struct net_device *dev, struct ethtool_link_ksettings *link_ksettings);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/ioctl.c (0)
Location: net/ethtool/ioctl.c:428
Inline: False
Direct callers:
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkinfo.c:linkinfo_prepare_data
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
  - net/ethtool/linkmodes.c:linkmodes_prepare_data
```
**Symbols:**

```
ffffffff81d395e2-ffffffff81d395f6: __ethtool_get_link_ksettings.cold (STB_LOCAL)
ffffffff81b2dbd0-ffffffff81b2dc8f: __ethtool_get_link_ksettings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __ethtool_get_link_ksettings(struct net_device *dev, struct ethtool_link_ksettings *link_ksettings);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/ioctl.c (0)
Location: net/ethtool/ioctl.c:452
Inline: False
Direct callers:
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkinfo.c:linkinfo_prepare_data
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
  - net/ethtool/linkmodes.c:linkmodes_prepare_data
```
**Symbols:**

```
ffffffff81f05d47-ffffffff81f05d5c: __ethtool_get_link_ksettings.cold (STB_LOCAL)
ffffffff81cb8500-ffffffff81cb85d1: __ethtool_get_link_ksettings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __ethtool_get_link_ksettings(struct net_device *dev, struct ethtool_link_ksettings *link_ksettings);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/ioctl.c (0)
Location: net/ethtool/ioctl.c:432
Inline: False
Direct callers:
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkinfo.c:linkinfo_prepare_data
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
  - net/ethtool/linkmodes.c:linkmodes_prepare_data
```
**Symbols:**

```
ffffffff820ada62-ffffffff820ada77: __ethtool_get_link_ksettings.cold (STB_LOCAL)
ffffffff81e761f0-ffffffff81e762c1: __ethtool_get_link_ksettings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __ethtool_get_link_ksettings(struct net_device *dev, struct ethtool_link_ksettings *link_ksettings);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/ioctl.c (0)
Location: net/ethtool/ioctl.c:433
Inline: False
Direct callers:
  - drivers/net/net_failover.c:nfo_ethtool_get_link_ksettings
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkinfo.c:linkinfo_prepare_data
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
  - net/ethtool/linkmodes.c:linkmodes_prepare_data
```
**Symbols:**

```
ffffffff8212eca8-ffffffff8212ecbd: __ethtool_get_link_ksettings.cold (STB_LOCAL)
ffffffff81ed2570-ffffffff81ed2641: __ethtool_get_link_ksettings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __ethtool_get_link_ksettings(struct net_device *dev, struct ethtool_link_ksettings *link_ksettings);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/ioctl.c (0)
Location: net/ethtool/ioctl.c:436
Inline: False
Direct callers:
  - drivers/net/net_failover.c:nfo_ethtool_get_link_ksettings
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkinfo.c:linkinfo_prepare_data
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
  - net/ethtool/linkmodes.c:linkmodes_prepare_data
```
**Symbols:**

```
ffffffff82210a21-ffffffff82210a36: __ethtool_get_link_ksettings.cold (STB_LOCAL)
ffffffff81f95e80-ffffffff81f95f51: __ethtool_get_link_ksettings (STB_GLOBAL)
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
int __ethtool_get_link_ksettings(struct net_device *dev, struct ethtool_link_ksettings *link_ksettings);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffff800010bd8b68)
Location: net/core/ethtool.c:544
Inline: False
Direct callers:
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffff800010bd8b68-ffff800010bd8c0c: __ethtool_get_link_ksettings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __ethtool_get_link_ksettings(struct net_device *dev, struct ethtool_link_ksettings *link_ksettings);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (c0cf33d0)
Location: net/core/ethtool.c:544
Inline: False
Direct callers:
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
c0cf33d0-c0cf3480: __ethtool_get_link_ksettings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __ethtool_get_link_ksettings(struct net_device *dev, struct ethtool_link_ksettings *link_ksettings);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (c000000000cb85f0)
Location: net/core/ethtool.c:544
Inline: False
Direct callers:
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
c000000000cb85f0-c000000000cb86d8: __ethtool_get_link_ksettings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __ethtool_get_link_ksettings(struct net_device *dev, struct ethtool_link_ksettings *link_ksettings);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffe0007617e0)
Location: net/core/ethtool.c:544
Inline: False
Direct callers:
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffe0007617e0-ffffffe000761872: __ethtool_get_link_ksettings (STB_GLOBAL)
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
int __ethtool_get_link_ksettings(struct net_device *dev, struct ethtool_link_ksettings *link_ksettings);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff818d9d70)
Location: net/core/ethtool.c:544
Inline: False
Direct callers:
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff818d9d70-ffffffff818d9e1d: __ethtool_get_link_ksettings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __ethtool_get_link_ksettings(struct net_device *dev, struct ethtool_link_ksettings *link_ksettings);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff81893bb0)
Location: net/core/ethtool.c:544
Inline: False
Direct callers:
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81893bb0-ffffffff81893c5d: __ethtool_get_link_ksettings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __ethtool_get_link_ksettings(struct net_device *dev, struct ethtool_link_ksettings *link_ksettings);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff8192ada0)
Location: net/core/ethtool.c:544
Inline: False
Direct callers:
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff8192ada0-ffffffff8192ae4d: __ethtool_get_link_ksettings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __ethtool_get_link_ksettings(struct net_device *dev, struct ethtool_link_ksettings *link_ksettings);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff8194c470)
Location: net/core/ethtool.c:544
Inline: False
Direct callers:
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff8194c470-ffffffff8194c51d: __ethtool_get_link_ksettings (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
