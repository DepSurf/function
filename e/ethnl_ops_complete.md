# Function: <code>ethnl_ops_complete</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethtool/strset.c (ffffffff81a88390)
Location: net/ethtool/netlink.h:257
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_prepare_data
  - net/ethtool/strset.c:strset_prepare_data
```
```
In net/ethtool/linkinfo.c (ffffffff81a889f6)
Location: net/ethtool/netlink.h:257
Inline: True
Inline callers:
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkinfo.c:linkinfo_prepare_data
```
```
In net/ethtool/linkmodes.c (ffffffff81a89189)
Location: net/ethtool/netlink.h:257
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
  - net/ethtool/linkmodes.c:linkmodes_prepare_data
```
```
In net/ethtool/linkstate.c (ffffffff81a893bb)
Location: net/ethtool/netlink.h:257
Inline: True
Inline callers:
  - net/ethtool/linkstate.c:linkstate_prepare_data
```
```
In net/ethtool/debug.c (ffffffff81a89705)
Location: net/ethtool/netlink.h:257
Inline: True
Inline callers:
  - net/ethtool/debug.c:ethnl_set_debug
  - net/ethtool/debug.c:debug_prepare_data
```
```
In net/ethtool/wol.c (ffffffff81a89b07)
Location: net/ethtool/netlink.h:257
Inline: True
Inline callers:
  - net/ethtool/wol.c:ethnl_set_wol
  - net/ethtool/wol.c:wol_prepare_data
```
```
In net/ethtool/privflags.c (ffffffff81a8a7d1)
Location: net/ethtool/netlink.h:257
Inline: True
Inline callers:
  - net/ethtool/privflags.c:ethnl_set_privflags
  - net/ethtool/privflags.c:privflags_prepare_data
```
```
In net/ethtool/rings.c (ffffffff81a8acb6)
Location: net/ethtool/netlink.h:257
Inline: True
Inline callers:
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:rings_prepare_data
```
```
In net/ethtool/channels.c (ffffffff81a8b25b)
Location: net/ethtool/netlink.h:257
Inline: True
Inline callers:
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:channels_prepare_data
```
```
In net/ethtool/coalesce.c (ffffffff81a8be8d)
Location: net/ethtool/netlink.h:257
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:coalesce_prepare_data
```
```
In net/ethtool/pause.c (ffffffff81a8c278)
Location: net/ethtool/netlink.h:257
Inline: True
Inline callers:
  - net/ethtool/pause.c:ethnl_set_pause
  - net/ethtool/pause.c:pause_prepare_data
```
```
In net/ethtool/eee.c (ffffffff81a8c7db)
Location: net/ethtool/netlink.h:257
Inline: True
Inline callers:
  - net/ethtool/eee.c:ethnl_set_eee
  - net/ethtool/eee.c:eee_prepare_data
```
```
In net/ethtool/tsinfo.c (ffffffff81a8cb40)
Location: net/ethtool/netlink.h:257
Inline: True
Inline callers:
  - net/ethtool/tsinfo.c:tsinfo_prepare_data
```
```
In net/ethtool/cabletest.c (ffffffff81a8d8bb)
Location: net/ethtool/netlink.h:257
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr
  - net/ethtool/cabletest.c:ethnl_act_cable_test
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethtool/strset.c (ffffffff81a91d4e)
Location: net/ethtool/netlink.h:258
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_prepare_data
  - net/ethtool/strset.c:strset_prepare_data
```
```
In net/ethtool/linkinfo.c (ffffffff81a922eb)
Location: net/ethtool/netlink.h:258
Inline: True
Inline callers:
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkinfo.c:linkinfo_prepare_data
```
```
In net/ethtool/linkmodes.c (ffffffff81a92a51)
Location: net/ethtool/netlink.h:258
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
  - net/ethtool/linkmodes.c:linkmodes_prepare_data
```
```
In net/ethtool/linkstate.c (ffffffff81a92cbb)
Location: net/ethtool/netlink.h:258
Inline: True
Inline callers:
  - net/ethtool/linkstate.c:linkstate_prepare_data
```
```
In net/ethtool/debug.c (ffffffff81a9302a)
Location: net/ethtool/netlink.h:258
Inline: True
Inline callers:
  - net/ethtool/debug.c:ethnl_set_debug
  - net/ethtool/debug.c:debug_prepare_data
```
```
In net/ethtool/wol.c (ffffffff81a93429)
Location: net/ethtool/netlink.h:258
Inline: True
Inline callers:
  - net/ethtool/wol.c:ethnl_set_wol
  - net/ethtool/wol.c:wol_prepare_data
```
```
In net/ethtool/privflags.c (ffffffff81a93ffa)
Location: net/ethtool/netlink.h:258
Inline: True
Inline callers:
  - net/ethtool/privflags.c:ethnl_set_privflags
  - net/ethtool/privflags.c:privflags_prepare_data
```
```
In net/ethtool/rings.c (ffffffff81a9445d)
Location: net/ethtool/netlink.h:258
Inline: True
Inline callers:
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:rings_prepare_data
```
```
In net/ethtool/channels.c (ffffffff81a949bf)
Location: net/ethtool/netlink.h:258
Inline: True
Inline callers:
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:channels_prepare_data
```
```
In net/ethtool/coalesce.c (ffffffff81a9549b)
Location: net/ethtool/netlink.h:258
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:coalesce_prepare_data
```
```
In net/ethtool/pause.c (ffffffff81a95a1a)
Location: net/ethtool/netlink.h:258
Inline: True
Inline callers:
  - net/ethtool/pause.c:ethnl_set_pause
  - net/ethtool/pause.c:pause_prepare_data
```
```
In net/ethtool/eee.c (ffffffff81a95f09)
Location: net/ethtool/netlink.h:258
Inline: True
Inline callers:
  - net/ethtool/eee.c:ethnl_set_eee
  - net/ethtool/eee.c:eee_prepare_data
```
```
In net/ethtool/tsinfo.c (ffffffff81a96250)
Location: net/ethtool/netlink.h:258
Inline: True
Inline callers:
  - net/ethtool/tsinfo.c:tsinfo_prepare_data
```
```
In net/ethtool/cabletest.c (ffffffff81a96fb1)
Location: net/ethtool/netlink.h:258
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr
  - net/ethtool/cabletest.c:ethnl_act_cable_test
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethtool/strset.c (ffffffff81a7b295)
Location: net/ethtool/netlink.h:258
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_prepare_data
  - net/ethtool/strset.c:strset_prepare_data
```
```
In net/ethtool/linkinfo.c (ffffffff81a7bafa)
Location: net/ethtool/netlink.h:258
Inline: True
Inline callers:
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkinfo.c:linkinfo_prepare_data
```
```
In net/ethtool/linkmodes.c (ffffffff81a7c3fd)
Location: net/ethtool/netlink.h:258
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
  - net/ethtool/linkmodes.c:linkmodes_prepare_data
```
```
In net/ethtool/linkstate.c (ffffffff81a7c6cb)
Location: net/ethtool/netlink.h:258
Inline: True
Inline callers:
  - net/ethtool/linkstate.c:linkstate_prepare_data
```
```
In net/ethtool/debug.c (ffffffff81a7ca3a)
Location: net/ethtool/netlink.h:258
Inline: True
Inline callers:
  - net/ethtool/debug.c:ethnl_set_debug
  - net/ethtool/debug.c:debug_prepare_data
```
```
In net/ethtool/wol.c (ffffffff81a7ce38)
Location: net/ethtool/netlink.h:258
Inline: True
Inline callers:
  - net/ethtool/wol.c:ethnl_set_wol
  - net/ethtool/wol.c:wol_prepare_data
```
```
In net/ethtool/privflags.c (ffffffff81a7da00)
Location: net/ethtool/netlink.h:258
Inline: True
Inline callers:
  - net/ethtool/privflags.c:ethnl_set_privflags
  - net/ethtool/privflags.c:privflags_prepare_data
```
```
In net/ethtool/rings.c (ffffffff81a7de72)
Location: net/ethtool/netlink.h:258
Inline: True
Inline callers:
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:rings_prepare_data
```
```
In net/ethtool/channels.c (ffffffff81a7e3dc)
Location: net/ethtool/netlink.h:258
Inline: True
Inline callers:
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:channels_prepare_data
```
```
In net/ethtool/coalesce.c (ffffffff81a7ef69)
Location: net/ethtool/netlink.h:258
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:coalesce_prepare_data
```
```
In net/ethtool/pause.c (ffffffff81a7f4aa)
Location: net/ethtool/netlink.h:258
Inline: True
Inline callers:
  - net/ethtool/pause.c:ethnl_set_pause
  - net/ethtool/pause.c:pause_prepare_data
```
```
In net/ethtool/eee.c (ffffffff81a7f98b)
Location: net/ethtool/netlink.h:258
Inline: True
Inline callers:
  - net/ethtool/eee.c:ethnl_set_eee
  - net/ethtool/eee.c:eee_prepare_data
```
```
In net/ethtool/tsinfo.c (ffffffff81a7fcd0)
Location: net/ethtool/netlink.h:258
Inline: True
Inline callers:
  - net/ethtool/tsinfo.c:tsinfo_prepare_data
```
```
In net/ethtool/cabletest.c (ffffffff81a80a3d)
Location: net/ethtool/netlink.h:258
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr
  - net/ethtool/cabletest.c:ethnl_act_cable_test
```
```
In net/ethtool/fec.c (ffffffff81a81aa1)
Location: net/ethtool/netlink.h:258
Inline: True
Inline callers:
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/fec.c:fec_prepare_data
```
```
In net/ethtool/eeprom.c (ffffffff81a8201b)
Location: net/ethtool/netlink.h:258
Inline: True
Inline callers:
  - net/ethtool/eeprom.c:eeprom_prepare_data
  - net/ethtool/eeprom.c:eeprom_prepare_data
```
```
In net/ethtool/stats.c (ffffffff81a824d1)
Location: net/ethtool/netlink.h:258
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_prepare_data
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ethnl_ops_complete(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81b33090)
Location: net/ethtool/netlink.c:63
Inline: False
Direct callers:
  - net/ethtool/strset.c:strset_prepare_data
  - net/ethtool/strset.c:strset_prepare_data
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkinfo.c:linkinfo_prepare_data
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
  - net/ethtool/linkmodes.c:linkmodes_prepare_data
  - net/ethtool/linkstate.c:linkstate_prepare_data
  - net/ethtool/debug.c:ethnl_set_debug
  - net/ethtool/debug.c:debug_prepare_data
  - net/ethtool/wol.c:ethnl_set_wol
  - net/ethtool/wol.c:wol_prepare_data
  - net/ethtool/privflags.c:ethnl_set_privflags
  - net/ethtool/privflags.c:privflags_prepare_data
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:rings_prepare_data
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:channels_prepare_data
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:coalesce_prepare_data
  - net/ethtool/pause.c:ethnl_set_pause
  - net/ethtool/pause.c:pause_prepare_data
  - net/ethtool/eee.c:ethnl_set_eee
  - net/ethtool/eee.c:eee_prepare_data
  - net/ethtool/tsinfo.c:tsinfo_prepare_data
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr
  - net/ethtool/cabletest.c:ethnl_act_cable_test
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/fec.c:fec_prepare_data
  - net/ethtool/eeprom.c:eeprom_prepare_data
  - net/ethtool/eeprom.c:eeprom_prepare_data
  - net/ethtool/eeprom.c:eeprom_prepare_data
  - net/ethtool/stats.c:stats_prepare_data
  - net/ethtool/phc_vclocks.c:phc_vclocks_prepare_data
```
**Symbols:**

```
ffffffff81b33090-ffffffff81b330d1: ethnl_ops_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ethnl_ops_complete(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81cbe260)
Location: net/ethtool/netlink.c:63
Inline: False
Direct callers:
  - net/ethtool/strset.c:strset_prepare_data
  - net/ethtool/strset.c:strset_prepare_data
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkinfo.c:linkinfo_prepare_data
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
  - net/ethtool/linkmodes.c:linkmodes_prepare_data
  - net/ethtool/linkstate.c:linkstate_prepare_data
  - net/ethtool/debug.c:ethnl_set_debug
  - net/ethtool/debug.c:debug_prepare_data
  - net/ethtool/wol.c:ethnl_set_wol
  - net/ethtool/wol.c:wol_prepare_data
  - net/ethtool/privflags.c:ethnl_set_privflags
  - net/ethtool/privflags.c:privflags_prepare_data
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:rings_prepare_data
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:channels_prepare_data
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:coalesce_prepare_data
  - net/ethtool/pause.c:ethnl_set_pause
  - net/ethtool/pause.c:pause_prepare_data
  - net/ethtool/eee.c:ethnl_set_eee
  - net/ethtool/eee.c:eee_prepare_data
  - net/ethtool/tsinfo.c:tsinfo_prepare_data
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr
  - net/ethtool/cabletest.c:ethnl_act_cable_test
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/fec.c:fec_prepare_data
  - net/ethtool/eeprom.c:eeprom_prepare_data
  - net/ethtool/eeprom.c:eeprom_prepare_data
  - net/ethtool/eeprom.c:eeprom_prepare_data
  - net/ethtool/stats.c:stats_prepare_data
  - net/ethtool/phc_vclocks.c:phc_vclocks_prepare_data
  - net/ethtool/module.c:ethnl_set_module
  - net/ethtool/module.c:ethnl_set_module
  - net/ethtool/module.c:module_prepare_data
```
**Symbols:**

```
ffffffff81cbe260-ffffffff81cbe2ab: ethnl_ops_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ethnl_ops_complete(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81e7cd10)
Location: net/ethtool/netlink.c:63
Inline: False
Direct callers:
  - net/ethtool/strset.c:strset_prepare_data
  - net/ethtool/strset.c:strset_prepare_data
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkinfo.c:linkinfo_prepare_data
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
  - net/ethtool/linkmodes.c:linkmodes_prepare_data
  - net/ethtool/rss.c:rss_prepare_data
  - net/ethtool/linkstate.c:linkstate_prepare_data
  - net/ethtool/debug.c:ethnl_set_debug
  - net/ethtool/debug.c:debug_prepare_data
  - net/ethtool/wol.c:ethnl_set_wol
  - net/ethtool/wol.c:wol_prepare_data
  - net/ethtool/privflags.c:ethnl_set_privflags
  - net/ethtool/privflags.c:privflags_prepare_data
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:rings_prepare_data
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:channels_prepare_data
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:coalesce_prepare_data
  - net/ethtool/pause.c:ethnl_set_pause
  - net/ethtool/pause.c:pause_prepare_data
  - net/ethtool/eee.c:ethnl_set_eee
  - net/ethtool/eee.c:eee_prepare_data
  - net/ethtool/tsinfo.c:tsinfo_prepare_data
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr
  - net/ethtool/cabletest.c:ethnl_act_cable_test
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/fec.c:fec_prepare_data
  - net/ethtool/eeprom.c:eeprom_prepare_data
  - net/ethtool/eeprom.c:eeprom_prepare_data
  - net/ethtool/eeprom.c:eeprom_prepare_data
  - net/ethtool/stats.c:stats_prepare_data
  - net/ethtool/phc_vclocks.c:phc_vclocks_prepare_data
  - net/ethtool/module.c:ethnl_set_module
  - net/ethtool/module.c:ethnl_set_module
  - net/ethtool/module.c:module_prepare_data
  - net/ethtool/pse-pd.c:ethnl_set_pse
  - net/ethtool/pse-pd.c:pse_prepare_data
```
**Symbols:**

```
ffffffff81e7cd10-ffffffff81e7cd5b: ethnl_ops_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void ethnl_ops_complete(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81ed94d3)
Location: net/ethtool/netlink.c:63
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_set_doit
Direct callers:
  - net/ethtool/strset.c:strset_prepare_data
  - net/ethtool/strset.c:strset_prepare_data
  - net/ethtool/linkinfo.c:linkinfo_prepare_data
  - net/ethtool/linkmodes.c:linkmodes_prepare_data
  - net/ethtool/rss.c:rss_prepare_data
  - net/ethtool/linkstate.c:linkstate_prepare_data
  - net/ethtool/debug.c:debug_prepare_data
  - net/ethtool/wol.c:wol_prepare_data
  - net/ethtool/privflags.c:privflags_prepare_data
  - net/ethtool/rings.c:rings_prepare_data
  - net/ethtool/channels.c:channels_prepare_data
  - net/ethtool/coalesce.c:coalesce_prepare_data
  - net/ethtool/pause.c:pause_prepare_data
  - net/ethtool/pause.c:pause_prepare_data
  - net/ethtool/eee.c:eee_prepare_data
  - net/ethtool/tsinfo.c:tsinfo_prepare_data
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr
  - net/ethtool/cabletest.c:ethnl_act_cable_test
  - net/ethtool/fec.c:fec_prepare_data
  - net/ethtool/eeprom.c:eeprom_prepare_data
  - net/ethtool/eeprom.c:eeprom_prepare_data
  - net/ethtool/eeprom.c:eeprom_prepare_data
  - net/ethtool/stats.c:stats_prepare_data
  - net/ethtool/stats.c:stats_prepare_data
  - net/ethtool/phc_vclocks.c:phc_vclocks_prepare_data
  - net/ethtool/mm.c:ethtool_dev_mm_supported
  - net/ethtool/mm.c:mm_prepare_data
  - net/ethtool/module.c:module_prepare_data
  - net/ethtool/pse-pd.c:pse_prepare_data
  - net/ethtool/plca.c:plca_get_status_prepare_data
  - net/ethtool/plca.c:plca_get_cfg_prepare_data
```
**Symbols:**

```
ffffffff81ed90d0-ffffffff81ed911b: ethnl_ops_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void ethnl_ops_complete(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81f9d3a3)
Location: net/ethtool/netlink.c:63
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_set_doit
Direct callers:
  - net/ethtool/strset.c:strset_prepare_data
  - net/ethtool/strset.c:strset_prepare_data
  - net/ethtool/linkinfo.c:linkinfo_prepare_data
  - net/ethtool/linkmodes.c:linkmodes_prepare_data
  - net/ethtool/rss.c:rss_prepare_data
  - net/ethtool/linkstate.c:linkstate_prepare_data
  - net/ethtool/debug.c:debug_prepare_data
  - net/ethtool/wol.c:wol_prepare_data
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/privflags.c:privflags_prepare_data
  - net/ethtool/rings.c:rings_prepare_data
  - net/ethtool/channels.c:channels_prepare_data
  - net/ethtool/coalesce.c:coalesce_prepare_data
  - net/ethtool/pause.c:pause_prepare_data
  - net/ethtool/pause.c:pause_prepare_data
  - net/ethtool/eee.c:eee_prepare_data
  - net/ethtool/tsinfo.c:tsinfo_prepare_data
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr
  - net/ethtool/cabletest.c:ethnl_act_cable_test
  - net/ethtool/fec.c:fec_prepare_data
  - net/ethtool/eeprom.c:eeprom_prepare_data
  - net/ethtool/eeprom.c:eeprom_prepare_data
  - net/ethtool/eeprom.c:eeprom_prepare_data
  - net/ethtool/stats.c:stats_prepare_data
  - net/ethtool/stats.c:stats_prepare_data
  - net/ethtool/phc_vclocks.c:phc_vclocks_prepare_data
  - net/ethtool/mm.c:ethtool_dev_mm_supported
  - net/ethtool/mm.c:mm_prepare_data
  - net/ethtool/module.c:module_prepare_data
  - net/ethtool/pse-pd.c:pse_prepare_data
  - net/ethtool/plca.c:plca_get_status_prepare_data
  - net/ethtool/plca.c:plca_get_cfg_prepare_data
```
**Symbols:**

```
ffffffff81f9cf90-ffffffff81f9cfdb: ethnl_ops_complete (STB_GLOBAL)
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
<b>Regular</b>
<ul>
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
