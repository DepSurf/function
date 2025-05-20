# Function: <code>ethnl_parse_header_dev_put</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethtool/linkinfo.c (ffffffff81cc1731)
Location: net/ethtool/netlink.h:238
Inline: True
Inline callers:
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
```
```
In net/ethtool/linkmodes.c (ffffffff81cc20a8)
Location: net/ethtool/netlink.h:238
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
```
```
In net/ethtool/debug.c (ffffffff81cc2670)
Location: net/ethtool/netlink.h:238
Inline: True
Inline callers:
  - net/ethtool/debug.c:ethnl_set_debug
```
```
In net/ethtool/wol.c (ffffffff81cc29ef)
Location: net/ethtool/netlink.h:238
Inline: True
Inline callers:
  - net/ethtool/wol.c:ethnl_set_wol
```
```
In net/ethtool/features.c (ffffffff81cc3054)
Location: net/ethtool/netlink.h:238
Inline: True
Inline callers:
  - net/ethtool/features.c:ethnl_set_features
```
```
In net/ethtool/privflags.c (ffffffff81cc368b)
Location: net/ethtool/netlink.h:238
Inline: True
Inline callers:
  - net/ethtool/privflags.c:ethnl_set_privflags
```
```
In net/ethtool/rings.c (ffffffff81cc3c4d)
Location: net/ethtool/netlink.h:238
Inline: True
Inline callers:
  - net/ethtool/rings.c:ethnl_set_rings
```
```
In net/ethtool/channels.c (ffffffff81cc4286)
Location: net/ethtool/netlink.h:238
Inline: True
Inline callers:
  - net/ethtool/channels.c:ethnl_set_channels
```
```
In net/ethtool/coalesce.c (ffffffff81cc4cc3)
Location: net/ethtool/netlink.h:238
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:ethnl_set_coalesce
```
```
In net/ethtool/pause.c (ffffffff81cc51b1)
Location: net/ethtool/netlink.h:238
Inline: True
Inline callers:
  - net/ethtool/pause.c:ethnl_set_pause
```
```
In net/ethtool/eee.c (ffffffff81cc5639)
Location: net/ethtool/netlink.h:238
Inline: True
Inline callers:
  - net/ethtool/eee.c:ethnl_set_eee
```
```
In net/ethtool/cabletest.c (ffffffff81cc6688)
Location: net/ethtool/netlink.h:238
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr
  - net/ethtool/cabletest.c:ethnl_act_cable_test
```
```
In net/ethtool/tunnels.c (ffffffff81cc6dc5)
Location: net/ethtool/netlink.h:238
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_start
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
```
In net/ethtool/fec.c (ffffffff81cc7778)
Location: net/ethtool/netlink.h:238
Inline: True
Inline callers:
  - net/ethtool/fec.c:ethnl_set_fec
```
```
In net/ethtool/module.c (ffffffff81cc8b9f)
Location: net/ethtool/netlink.h:238
Inline: True
Inline callers:
  - net/ethtool/module.c:ethnl_set_module
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethtool/linkinfo.c (ffffffff81e804b1)
Location: net/ethtool/netlink.h:238
Inline: True
Inline callers:
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
```
```
In net/ethtool/linkmodes.c (ffffffff81e80e98)
Location: net/ethtool/netlink.h:238
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
```
```
In net/ethtool/debug.c (ffffffff81e81890)
Location: net/ethtool/netlink.h:238
Inline: True
Inline callers:
  - net/ethtool/debug.c:ethnl_set_debug
```
```
In net/ethtool/wol.c (ffffffff81e81cbc)
Location: net/ethtool/netlink.h:238
Inline: True
Inline callers:
  - net/ethtool/wol.c:ethnl_set_wol
```
```
In net/ethtool/features.c (ffffffff81e82354)
Location: net/ethtool/netlink.h:238
Inline: True
Inline callers:
  - net/ethtool/features.c:ethnl_set_features
```
```
In net/ethtool/privflags.c (ffffffff81e829eb)
Location: net/ethtool/netlink.h:238
Inline: True
Inline callers:
  - net/ethtool/privflags.c:ethnl_set_privflags
```
```
In net/ethtool/rings.c (ffffffff81e82fed)
Location: net/ethtool/netlink.h:238
Inline: True
Inline callers:
  - net/ethtool/rings.c:ethnl_set_rings
```
```
In net/ethtool/channels.c (ffffffff81e836bd)
Location: net/ethtool/netlink.h:238
Inline: True
Inline callers:
  - net/ethtool/channels.c:ethnl_set_channels
```
```
In net/ethtool/coalesce.c (ffffffff81e84199)
Location: net/ethtool/netlink.h:238
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:ethnl_set_coalesce
```
```
In net/ethtool/pause.c (ffffffff81e846c1)
Location: net/ethtool/netlink.h:238
Inline: True
Inline callers:
  - net/ethtool/pause.c:ethnl_set_pause
```
```
In net/ethtool/eee.c (ffffffff81e84b89)
Location: net/ethtool/netlink.h:238
Inline: True
Inline callers:
  - net/ethtool/eee.c:ethnl_set_eee
```
```
In net/ethtool/cabletest.c (ffffffff81e85cc8)
Location: net/ethtool/netlink.h:238
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr
  - net/ethtool/cabletest.c:ethnl_act_cable_test
```
```
In net/ethtool/tunnels.c (ffffffff81e86405)
Location: net/ethtool/netlink.h:238
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_start
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
```
In net/ethtool/fec.c (ffffffff81e86de8)
Location: net/ethtool/netlink.h:238
Inline: True
Inline callers:
  - net/ethtool/fec.c:ethnl_set_fec
```
```
In net/ethtool/module.c (ffffffff81e883af)
Location: net/ethtool/netlink.h:238
Inline: True
Inline callers:
  - net/ethtool/module.c:ethnl_set_module
```
```
In net/ethtool/pse-pd.c (ffffffff81e886fa)
Location: net/ethtool/netlink.h:238
Inline: True
Inline callers:
  - net/ethtool/pse-pd.c:ethnl_set_pse
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81ed950b)
Location: net/ethtool/netlink.h:264
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_set_doit
```
```
In net/ethtool/features.c (ffffffff81ede9b4)
Location: net/ethtool/netlink.h:264
Inline: True
Inline callers:
  - net/ethtool/features.c:ethnl_set_features
```
```
In net/ethtool/cabletest.c (ffffffff81ee25f8)
Location: net/ethtool/netlink.h:264
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr
  - net/ethtool/cabletest.c:ethnl_act_cable_test
```
```
In net/ethtool/tunnels.c (ffffffff81ee2de5)
Location: net/ethtool/netlink.h:264
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_start
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81f9d3db)
Location: net/ethtool/netlink.h:264
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_set_doit
```
```
In net/ethtool/features.c (ffffffff81fa2826)
Location: net/ethtool/netlink.h:264
Inline: True
Inline callers:
  - net/ethtool/features.c:ethnl_set_features
```
```
In net/ethtool/cabletest.c (ffffffff81fa6488)
Location: net/ethtool/netlink.h:264
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr
  - net/ethtool/cabletest.c:ethnl_act_cable_test
```
```
In net/ethtool/tunnels.c (ffffffff81fa6c75)
Location: net/ethtool/netlink.h:264
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_start
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
