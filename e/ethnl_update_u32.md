# Function: <code>ethnl_update_u32</code>

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
In net/ethtool/linkmodes.c (ffffffff81a88e42)
Location: net/ethtool/netlink.h:72
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
```
```
In net/ethtool/rings.c (ffffffff81a8abe4)
Location: net/ethtool/netlink.h:72
Inline: True
Inline callers:
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
```
```
In net/ethtool/channels.c (ffffffff81a8b164)
Location: net/ethtool/netlink.h:72
Inline: True
Inline callers:
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
```
```
In net/ethtool/coalesce.c (ffffffff81a8bb74)
Location: net/ethtool/netlink.h:72
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
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
In net/ethtool/linkmodes.c (ffffffff81a9272a)
Location: net/ethtool/netlink.h:73
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
```
```
In net/ethtool/rings.c (ffffffff81a943a1)
Location: net/ethtool/netlink.h:73
Inline: True
Inline callers:
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
```
```
In net/ethtool/channels.c (ffffffff81a94883)
Location: net/ethtool/netlink.h:73
Inline: True
Inline callers:
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
```
```
In net/ethtool/coalesce.c (ffffffff81a95211)
Location: net/ethtool/netlink.h:73
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
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
In net/ethtool/linkmodes.c (ffffffff81a7bfa1)
Location: net/ethtool/netlink.h:73
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
```
```
In net/ethtool/rings.c (ffffffff81a7ddb1)
Location: net/ethtool/netlink.h:73
Inline: True
Inline callers:
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
```
```
In net/ethtool/channels.c (ffffffff81a7e293)
Location: net/ethtool/netlink.h:73
Inline: True
Inline callers:
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
```
```
In net/ethtool/coalesce.c (ffffffff81a7ecc2)
Location: net/ethtool/netlink.h:73
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
```
```
In net/ethtool/eee.c (ffffffff81a7f948)
Location: net/ethtool/netlink.h:73
Inline: True
Inline callers:
  - net/ethtool/eee.c:ethnl_set_eee
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethtool/linkmodes.c (ffffffff81b36321)
Location: net/ethtool/netlink.h:73
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
```
```
In net/ethtool/rings.c (ffffffff81b37f15)
Location: net/ethtool/netlink.h:73
Inline: True
Inline callers:
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
```
```
In net/ethtool/channels.c (ffffffff81b383a6)
Location: net/ethtool/netlink.h:73
Inline: True
Inline callers:
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
```
```
In net/ethtool/coalesce.c (ffffffff81b38c1c)
Location: net/ethtool/netlink.h:73
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
```
```
In net/ethtool/eee.c (ffffffff81b397ad)
Location: net/ethtool/netlink.h:73
Inline: True
Inline callers:
  - net/ethtool/eee.c:ethnl_set_eee
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethtool/linkmodes.c (ffffffff81cc1c51)
Location: net/ethtool/netlink.h:73
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
```
```
In net/ethtool/rings.c (ffffffff81cc3b3b)
Location: net/ethtool/netlink.h:73
Inline: True
Inline callers:
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
```
```
In net/ethtool/channels.c (ffffffff81cc4116)
Location: net/ethtool/netlink.h:73
Inline: True
Inline callers:
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
```
```
In net/ethtool/coalesce.c (ffffffff81cc49ca)
Location: net/ethtool/netlink.h:73
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
```
```
In net/ethtool/eee.c (ffffffff81cc55dd)
Location: net/ethtool/netlink.h:73
Inline: True
Inline callers:
  - net/ethtool/eee.c:ethnl_set_eee
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
In net/ethtool/linkmodes.c (ffffffff81e80a21)
Location: net/ethtool/netlink.h:73
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
```
```
In net/ethtool/rings.c (ffffffff81e82edb)
Location: net/ethtool/netlink.h:73
Inline: True
Inline callers:
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
```
```
In net/ethtool/channels.c (ffffffff81e834ff)
Location: net/ethtool/netlink.h:73
Inline: True
Inline callers:
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
```
```
In net/ethtool/coalesce.c (ffffffff81e83ea0)
Location: net/ethtool/netlink.h:73
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/coalesce.c:ethnl_set_coalesce
```
```
In net/ethtool/eee.c (ffffffff81e84b2d)
Location: net/ethtool/netlink.h:73
Inline: True
Inline callers:
  - net/ethtool/eee.c:ethnl_set_eee
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
In net/ethtool/linkmodes.c (ffffffff81edd261)
Location: net/ethtool/netlink.h:73
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
```
```
In net/ethtool/rings.c (ffffffff81edf6b1)
Location: net/ethtool/netlink.h:73
Inline: True
Inline callers:
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
```
```
In net/ethtool/channels.c (ffffffff81edfc5e)
Location: net/ethtool/netlink.h:73
Inline: True
Inline callers:
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
```
```
In net/ethtool/coalesce.c (ffffffff81ee01c1)
Location: net/ethtool/netlink.h:73
Inline: True
```
```
In net/ethtool/eee.c (ffffffff81ee1493)
Location: net/ethtool/netlink.h:73
Inline: True
Inline callers:
  - net/ethtool/eee.c:ethnl_set_eee
```
```
In net/ethtool/mm.c (ffffffff81ee54c5)
Location: net/ethtool/netlink.h:73
Inline: True
Inline callers:
  - net/ethtool/mm.c:ethnl_set_mm
  - net/ethtool/mm.c:ethnl_set_mm
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
In net/ethtool/linkmodes.c (ffffffff81fa1031)
Location: net/ethtool/netlink.h:73
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
```
```
In net/ethtool/rings.c (ffffffff81fa3531)
Location: net/ethtool/netlink.h:73
Inline: True
Inline callers:
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
```
```
In net/ethtool/channels.c (ffffffff81fa3afe)
Location: net/ethtool/netlink.h:73
Inline: True
Inline callers:
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
```
```
In net/ethtool/coalesce.c (ffffffff81fa4051)
Location: net/ethtool/netlink.h:73
Inline: True
```
```
In net/ethtool/eee.c (ffffffff81fa5323)
Location: net/ethtool/netlink.h:73
Inline: True
Inline callers:
  - net/ethtool/eee.c:ethnl_set_eee
```
```
In net/ethtool/mm.c (ffffffff81fa92a5)
Location: net/ethtool/netlink.h:73
Inline: True
Inline callers:
  - net/ethtool/mm.c:ethnl_set_mm
  - net/ethtool/mm.c:ethnl_set_mm
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
