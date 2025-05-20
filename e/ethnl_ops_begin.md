# Function: <code>ethnl_ops_begin</code>

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
In net/ethtool/strset.c (ffffffff81a882a9)
Location: net/ethtool/netlink.h:249
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_prepare_data
```
```
In net/ethtool/linkinfo.c (ffffffff81a888fc)
Location: net/ethtool/netlink.h:249
Inline: True
Inline callers:
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkinfo.c:linkinfo_prepare_data
```
```
In net/ethtool/linkmodes.c (ffffffff81a890c6)
Location: net/ethtool/netlink.h:249
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
  - net/ethtool/linkmodes.c:linkmodes_prepare_data
```
```
In net/ethtool/linkstate.c (ffffffff81a89320)
Location: net/ethtool/netlink.h:249
Inline: True
Inline callers:
  - net/ethtool/linkstate.c:linkstate_prepare_data
```
```
In net/ethtool/debug.c (ffffffff81a89641)
Location: net/ethtool/netlink.h:249
Inline: True
Inline callers:
  - net/ethtool/debug.c:ethnl_set_debug
  - net/ethtool/debug.c:debug_prepare_data
```
```
In net/ethtool/wol.c (ffffffff81a89a22)
Location: net/ethtool/netlink.h:249
Inline: True
Inline callers:
  - net/ethtool/wol.c:ethnl_set_wol
  - net/ethtool/wol.c:wol_prepare_data
```
```
In net/ethtool/privflags.c (ffffffff81a8a6ea)
Location: net/ethtool/netlink.h:249
Inline: True
Inline callers:
  - net/ethtool/privflags.c:ethnl_set_privflags
  - net/ethtool/privflags.c:privflags_prepare_data
```
```
In net/ethtool/rings.c (ffffffff81a8ab74)
Location: net/ethtool/netlink.h:249
Inline: True
Inline callers:
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:rings_prepare_data
```
```
In net/ethtool/channels.c (ffffffff81a8b0d2)
Location: net/ethtool/netlink.h:249
Inline: True
Inline callers:
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:channels_prepare_data
```
```
In net/ethtool/coalesce.c (ffffffff81a8bac9)
Location: net/ethtool/netlink.h:249
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:coalesce_prepare_data
```
```
In net/ethtool/pause.c (ffffffff81a8c163)
Location: net/ethtool/netlink.h:249
Inline: True
Inline callers:
  - net/ethtool/pause.c:ethnl_set_pause
  - net/ethtool/pause.c:pause_prepare_data
```
```
In net/ethtool/eee.c (ffffffff81a8c66e)
Location: net/ethtool/netlink.h:249
Inline: True
Inline callers:
  - net/ethtool/eee.c:ethnl_set_eee
  - net/ethtool/eee.c:eee_prepare_data
```
```
In net/ethtool/tsinfo.c (ffffffff81a8cb06)
Location: net/ethtool/netlink.h:249
Inline: True
Inline callers:
  - net/ethtool/tsinfo.c:tsinfo_prepare_data
```
```
In net/ethtool/cabletest.c (ffffffff81a8d870)
Location: net/ethtool/netlink.h:249
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
In net/ethtool/strset.c (ffffffff81a91c59)
Location: net/ethtool/netlink.h:250
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_prepare_data
```
```
In net/ethtool/linkinfo.c (ffffffff81a921e6)
Location: net/ethtool/netlink.h:250
Inline: True
Inline callers:
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkinfo.c:linkinfo_prepare_data
```
```
In net/ethtool/linkmodes.c (ffffffff81a9297d)
Location: net/ethtool/netlink.h:250
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
  - net/ethtool/linkmodes.c:linkmodes_prepare_data
```
```
In net/ethtool/linkstate.c (ffffffff81a92c23)
Location: net/ethtool/netlink.h:250
Inline: True
Inline callers:
  - net/ethtool/linkstate.c:linkstate_prepare_data
```
```
In net/ethtool/debug.c (ffffffff81a92f64)
Location: net/ethtool/netlink.h:250
Inline: True
Inline callers:
  - net/ethtool/debug.c:ethnl_set_debug
  - net/ethtool/debug.c:debug_prepare_data
```
```
In net/ethtool/wol.c (ffffffff81a932f4)
Location: net/ethtool/netlink.h:250
Inline: True
Inline callers:
  - net/ethtool/wol.c:ethnl_set_wol
  - net/ethtool/wol.c:wol_prepare_data
```
```
In net/ethtool/privflags.c (ffffffff81a93f12)
Location: net/ethtool/netlink.h:250
Inline: True
Inline callers:
  - net/ethtool/privflags.c:ethnl_set_privflags
  - net/ethtool/privflags.c:privflags_prepare_data
```
```
In net/ethtool/rings.c (ffffffff81a9432f)
Location: net/ethtool/netlink.h:250
Inline: True
Inline callers:
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:rings_prepare_data
```
```
In net/ethtool/channels.c (ffffffff81a94806)
Location: net/ethtool/netlink.h:250
Inline: True
Inline callers:
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:channels_prepare_data
```
```
In net/ethtool/coalesce.c (ffffffff81a95157)
Location: net/ethtool/netlink.h:250
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:coalesce_prepare_data
```
```
In net/ethtool/pause.c (ffffffff81a95903)
Location: net/ethtool/netlink.h:250
Inline: True
Inline callers:
  - net/ethtool/pause.c:ethnl_set_pause
  - net/ethtool/pause.c:pause_prepare_data
```
```
In net/ethtool/eee.c (ffffffff81a95da4)
Location: net/ethtool/netlink.h:250
Inline: True
Inline callers:
  - net/ethtool/eee.c:ethnl_set_eee
  - net/ethtool/eee.c:eee_prepare_data
```
```
In net/ethtool/tsinfo.c (ffffffff81a96216)
Location: net/ethtool/netlink.h:250
Inline: True
Inline callers:
  - net/ethtool/tsinfo.c:tsinfo_prepare_data
```
```
In net/ethtool/cabletest.c (ffffffff81a96f68)
Location: net/ethtool/netlink.h:250
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
In net/ethtool/strset.c (ffffffff81a7b1f9)
Location: net/ethtool/netlink.h:250
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_prepare_data
```
```
In net/ethtool/linkinfo.c (ffffffff81a7b9f6)
Location: net/ethtool/netlink.h:250
Inline: True
Inline callers:
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkinfo.c:linkinfo_prepare_data
```
```
In net/ethtool/linkmodes.c (ffffffff81a7c384)
Location: net/ethtool/netlink.h:250
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
  - net/ethtool/linkmodes.c:linkmodes_prepare_data
```
```
In net/ethtool/linkstate.c (ffffffff81a7c633)
Location: net/ethtool/netlink.h:250
Inline: True
Inline callers:
  - net/ethtool/linkstate.c:linkstate_prepare_data
```
```
In net/ethtool/debug.c (ffffffff81a7c974)
Location: net/ethtool/netlink.h:250
Inline: True
Inline callers:
  - net/ethtool/debug.c:ethnl_set_debug
  - net/ethtool/debug.c:debug_prepare_data
```
```
In net/ethtool/wol.c (ffffffff81a7cd04)
Location: net/ethtool/netlink.h:250
Inline: True
Inline callers:
  - net/ethtool/wol.c:ethnl_set_wol
  - net/ethtool/wol.c:wol_prepare_data
```
```
In net/ethtool/privflags.c (ffffffff81a7d914)
Location: net/ethtool/netlink.h:250
Inline: True
Inline callers:
  - net/ethtool/privflags.c:ethnl_set_privflags
  - net/ethtool/privflags.c:privflags_prepare_data
```
```
In net/ethtool/rings.c (ffffffff81a7dd3f)
Location: net/ethtool/netlink.h:250
Inline: True
Inline callers:
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:rings_prepare_data
```
```
In net/ethtool/channels.c (ffffffff81a7e216)
Location: net/ethtool/netlink.h:250
Inline: True
Inline callers:
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:channels_prepare_data
```
```
In net/ethtool/coalesce.c (ffffffff81a7ebb6)
Location: net/ethtool/netlink.h:250
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:coalesce_prepare_data
```
```
In net/ethtool/pause.c (ffffffff81a7f393)
Location: net/ethtool/netlink.h:250
Inline: True
Inline callers:
  - net/ethtool/pause.c:ethnl_set_pause
  - net/ethtool/pause.c:pause_prepare_data
```
```
In net/ethtool/eee.c (ffffffff81a7f834)
Location: net/ethtool/netlink.h:250
Inline: True
Inline callers:
  - net/ethtool/eee.c:ethnl_set_eee
  - net/ethtool/eee.c:eee_prepare_data
```
```
In net/ethtool/tsinfo.c (ffffffff81a7fc96)
Location: net/ethtool/netlink.h:250
Inline: True
Inline callers:
  - net/ethtool/tsinfo.c:tsinfo_prepare_data
```
```
In net/ethtool/cabletest.c (ffffffff81a809eb)
Location: net/ethtool/netlink.h:250
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr
  - net/ethtool/cabletest.c:ethnl_act_cable_test
```
```
In net/ethtool/fec.c (ffffffff81a818fc)
Location: net/ethtool/netlink.h:250
Inline: True
Inline callers:
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/fec.c:fec_prepare_data
```
```
In net/ethtool/eeprom.c (ffffffff81a81f72)
Location: net/ethtool/netlink.h:250
Inline: True
Inline callers:
  - net/ethtool/eeprom.c:eeprom_prepare_data
```
```
In net/ethtool/stats.c (ffffffff81a8234f)
Location: net/ethtool/netlink.h:250
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
int ethnl_ops_begin(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81b32fe0)
Location: net/ethtool/netlink.c:33
Inline: False
Direct callers:
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
  - net/ethtool/stats.c:stats_prepare_data
  - net/ethtool/phc_vclocks.c:phc_vclocks_prepare_data
```
**Symbols:**

```
ffffffff81b32fe0-ffffffff81b33086: ethnl_ops_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ethnl_ops_begin(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81cbe1a0)
Location: net/ethtool/netlink.c:33
Inline: False
Direct callers:
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
  - net/ethtool/stats.c:stats_prepare_data
  - net/ethtool/phc_vclocks.c:phc_vclocks_prepare_data
  - net/ethtool/module.c:ethnl_set_module
  - net/ethtool/module.c:module_prepare_data
```
**Symbols:**

```
ffffffff81cbe1a0-ffffffff81cbe25e: ethnl_ops_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ethnl_ops_begin(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81e7cc40)
Location: net/ethtool/netlink.c:33
Inline: False
Direct callers:
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
  - net/ethtool/stats.c:stats_prepare_data
  - net/ethtool/phc_vclocks.c:phc_vclocks_prepare_data
  - net/ethtool/module.c:ethnl_set_module
  - net/ethtool/module.c:module_prepare_data
  - net/ethtool/pse-pd.c:ethnl_set_pse
  - net/ethtool/pse-pd.c:pse_prepare_data
```
**Symbols:**

```
ffffffff81e7cc40-ffffffff81e7ccfe: ethnl_ops_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ethnl_ops_begin(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81ed9000)
Location: net/ethtool/netlink.c:33
Inline: False
Direct callers:
  - net/ethtool/netlink.c:ethnl_default_set_doit
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
  - net/ethtool/eee.c:eee_prepare_data
  - net/ethtool/tsinfo.c:tsinfo_prepare_data
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr
  - net/ethtool/cabletest.c:ethnl_act_cable_test
  - net/ethtool/fec.c:fec_prepare_data
  - net/ethtool/eeprom.c:eeprom_prepare_data
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
ffffffff81ed9000-ffffffff81ed90be: ethnl_ops_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ethnl_ops_begin(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81f9ceb0)
Location: net/ethtool/netlink.c:33
Inline: False
Direct callers:
  - net/ethtool/netlink.c:ethnl_default_set_doit
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
  - net/ethtool/eee.c:eee_prepare_data
  - net/ethtool/tsinfo.c:tsinfo_prepare_data
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr
  - net/ethtool/cabletest.c:ethnl_act_cable_test
  - net/ethtool/fec.c:fec_prepare_data
  - net/ethtool/eeprom.c:eeprom_prepare_data
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
ffffffff81f9ceb0-ffffffff81f9cf74: ethnl_ops_begin (STB_GLOBAL)
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
