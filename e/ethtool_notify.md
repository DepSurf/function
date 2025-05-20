# Function: <code>ethtool_notify</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
void ethtool_notify(struct net_device *dev, unsigned int cmd, const void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81a85850)
Location: net/ethtool/netlink.c:646
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:ethtool_set_channels
  - net/ethtool/ioctl.c:ethtool_set_ringparam
  - net/ethtool/ioctl.c:ethtool_set_coalesce
  - net/ethtool/ioctl.c:ethtool_set_settings
  - net/ethtool/ioctl.c:ethtool_set_settings
  - net/ethtool/ioctl.c:ethtool_set_link_ksettings
  - net/ethtool/ioctl.c:ethtool_set_link_ksettings
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
  - net/ethtool/debug.c:ethnl_set_debug
  - net/ethtool/debug.c:ethnl_set_debug
  - net/ethtool/wol.c:ethnl_set_wol
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/privflags.c:ethnl_set_privflags
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/pause.c:ethnl_set_pause
  - net/ethtool/eee.c:ethnl_set_eee
```
**Symbols:**

```
ffffffff81a85850-ffffffff81a85922: ethtool_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ethtool_notify(struct net_device *dev, unsigned int cmd, const void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81a8f1c0)
Location: net/ethtool/netlink.c:648
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:ethtool_set_channels
  - net/ethtool/ioctl.c:ethtool_set_ringparam
  - net/ethtool/ioctl.c:ethtool_set_coalesce
  - net/ethtool/ioctl.c:ethtool_set_settings
  - net/ethtool/ioctl.c:ethtool_set_settings
  - net/ethtool/ioctl.c:ethtool_set_link_ksettings
  - net/ethtool/ioctl.c:ethtool_set_link_ksettings
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
  - net/ethtool/debug.c:ethnl_set_debug
  - net/ethtool/debug.c:ethnl_set_debug
  - net/ethtool/wol.c:ethnl_set_wol
  - net/ethtool/privflags.c:ethnl_set_privflags
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/pause.c:ethnl_set_pause
  - net/ethtool/eee.c:ethnl_set_eee
```
**Symbols:**

```
ffffffff81a8f1c0-ffffffff81a8f292: ethtool_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ethtool_notify(struct net_device *dev, unsigned int cmd, const void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81a788c0)
Location: net/ethtool/netlink.c:654
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:ethtool_set_channels
  - net/ethtool/ioctl.c:ethtool_set_coalesce
  - net/ethtool/ioctl.c:ethtool_set_settings
  - net/ethtool/ioctl.c:ethtool_set_settings
  - net/ethtool/ioctl.c:ethtool_set_link_ksettings
  - net/ethtool/ioctl.c:ethtool_set_link_ksettings
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
  - net/ethtool/debug.c:ethnl_set_debug
  - net/ethtool/debug.c:ethnl_set_debug
  - net/ethtool/wol.c:ethnl_set_wol
  - net/ethtool/privflags.c:ethnl_set_privflags
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/pause.c:ethnl_set_pause
  - net/ethtool/eee.c:ethnl_set_eee
  - net/ethtool/fec.c:ethnl_set_fec
```
**Symbols:**

```
ffffffff81a788c0-ffffffff81a78992: ethtool_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ethtool_notify(struct net_device *dev, unsigned int cmd, const void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/netlink.c (0)
Location: net/ethtool/netlink.c:692
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:ethtool_set_channels
  - net/ethtool/ioctl.c:ethtool_set_coalesce
  - net/ethtool/ioctl.c:ethtool_set_settings
  - net/ethtool/ioctl.c:ethtool_set_settings
  - net/ethtool/ioctl.c:ethtool_set_link_ksettings
  - net/ethtool/ioctl.c:ethtool_set_link_ksettings
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
  - net/ethtool/debug.c:ethnl_set_debug
  - net/ethtool/wol.c:ethnl_set_wol
  - net/ethtool/privflags.c:ethnl_set_privflags
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/pause.c:ethnl_set_pause
  - net/ethtool/eee.c:ethnl_set_eee
  - net/ethtool/fec.c:ethnl_set_fec
```
**Symbols:**

```
ffffffff81d3965b-ffffffff81d39697: ethtool_notify.cold (STB_LOCAL)
ffffffff81b32a30-ffffffff81b32b66: ethtool_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ethtool_notify(struct net_device *dev, unsigned int cmd, const void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/netlink.c (0)
Location: net/ethtool/netlink.c:696
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:ethtool_set_channels
  - net/ethtool/ioctl.c:ethtool_set_coalesce
  - net/ethtool/ioctl.c:ethtool_set_settings
  - net/ethtool/ioctl.c:ethtool_set_settings
  - net/ethtool/ioctl.c:ethtool_set_link_ksettings
  - net/ethtool/ioctl.c:ethtool_set_link_ksettings
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
  - net/ethtool/debug.c:ethnl_set_debug
  - net/ethtool/wol.c:ethnl_set_wol
  - net/ethtool/privflags.c:ethnl_set_privflags
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/pause.c:ethnl_set_pause
  - net/ethtool/eee.c:ethnl_set_eee
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/module.c:ethnl_set_module
```
**Symbols:**

```
ffffffff81f05dc5-ffffffff81f05e04: ethtool_notify.cold (STB_LOCAL)
ffffffff81cbdfe0-ffffffff81cbe129: ethtool_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ethtool_notify(struct net_device *dev, unsigned int cmd, const void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/netlink.c (0)
Location: net/ethtool/netlink.c:701
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:ethtool_set_channels
  - net/ethtool/ioctl.c:ethtool_set_coalesce
  - net/ethtool/ioctl.c:ethtool_set_settings
  - net/ethtool/ioctl.c:ethtool_set_settings
  - net/ethtool/ioctl.c:ethtool_set_link_ksettings
  - net/ethtool/ioctl.c:ethtool_set_link_ksettings
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
  - net/ethtool/debug.c:ethnl_set_debug
  - net/ethtool/wol.c:ethnl_set_wol
  - net/ethtool/privflags.c:ethnl_set_privflags
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/pause.c:ethnl_set_pause
  - net/ethtool/eee.c:ethnl_set_eee
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/module.c:ethnl_set_module
```
**Symbols:**

```
ffffffff820adae0-ffffffff820adb1f: ethtool_notify.cold (STB_LOCAL)
ffffffff81e7ca50-ffffffff81e7cb99: ethtool_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ethtool_notify(struct net_device *dev, unsigned int cmd, const void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/netlink.c (0)
Location: net/ethtool/netlink.c:771
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:ethtool_set_channels
  - net/ethtool/ioctl.c:ethtool_set_coalesce
  - net/ethtool/ioctl.c:ethtool_set_settings
  - net/ethtool/ioctl.c:ethtool_set_settings
  - net/ethtool/ioctl.c:ethtool_set_link_ksettings
  - net/ethtool/ioctl.c:ethtool_set_link_ksettings
  - net/ethtool/netlink.c:ethnl_default_set_doit
```
**Symbols:**

```
ffffffff8212ed26-ffffffff8212ed65: ethtool_notify.cold (STB_LOCAL)
ffffffff81ed8e10-ffffffff81ed8f59: ethtool_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ethtool_notify(struct net_device *dev, unsigned int cmd, const void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/netlink.c (0)
Location: net/ethtool/netlink.c:742
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:ethtool_set_channels
  - net/ethtool/ioctl.c:ethtool_set_coalesce
  - net/ethtool/ioctl.c:ethtool_set_settings
  - net/ethtool/ioctl.c:ethtool_set_settings
  - net/ethtool/ioctl.c:ethtool_set_link_ksettings
  - net/ethtool/ioctl.c:ethtool_set_link_ksettings
  - net/ethtool/netlink.c:ethnl_default_set_doit
```
**Symbols:**

```
ffffffff82210ab4-ffffffff82210af3: ethtool_notify.cold (STB_LOCAL)
ffffffff81f9ccb0-ffffffff81f9ce0c: ethtool_notify (STB_GLOBAL)
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
