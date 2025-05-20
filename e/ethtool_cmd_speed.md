# Function: <code>ethtool_cmd_speed</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff815e9b75)
Location: include/uapi/linux/ethtool.h:121
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In net/core/net-sysfs.c (0)
Location: include/uapi/linux/ethtool.h:121
Inline: True
```
```
In net/packet/af_packet.c (ffffffff8180576f)
Location: include/uapi/linux/ethtool.h:121
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81648395)
Location: include/uapi/linux/ethtool.h:127
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/virtio_net.c (ffffffff81650b42)
Location: include/uapi/linux/ethtool.h:127
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_set_settings
```
```
In net/core/ethtool.c (ffffffff81787c57)
Location: include/uapi/linux/ethtool.h:127
Inline: True
Inline callers:
  - net/core/ethtool.c:convert_legacy_settings_to_link_ksettings
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81679505)
Location: include/uapi/linux/ethtool.h:126
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In net/core/ethtool.c (ffffffff817b5217)
Location: include/uapi/linux/ethtool.h:126
Inline: True
Inline callers:
  - net/core/ethtool.c:convert_legacy_settings_to_link_ksettings
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8168e805)
Location: include/uapi/linux/ethtool.h:126
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In net/core/ethtool.c (ffffffff817d3d67)
Location: include/uapi/linux/ethtool.h:126
Inline: True
Inline callers:
  - net/core/ethtool.c:convert_legacy_settings_to_link_ksettings
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff816f82f5)
Location: include/uapi/linux/ethtool.h:127
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In net/core/ethtool.c (ffffffff8184e279)
Location: include/uapi/linux/ethtool.h:127
Inline: True
Inline callers:
  - net/core/ethtool.c:convert_legacy_settings_to_link_ksettings
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff817354e5)
Location: include/uapi/linux/ethtool.h:127
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In net/core/ethtool.c (ffffffff818993da)
Location: include/uapi/linux/ethtool.h:127
Inline: True
Inline callers:
  - net/core/ethtool.c:convert_legacy_settings_to_link_ksettings
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff817589d6)
Location: include/uapi/linux/ethtool.h:123
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In net/core/ethtool.c (ffffffff818bc954)
Location: include/uapi/linux/ethtool.h:123
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_settings
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff817956fb)
Location: include/uapi/linux/ethtool.h:123
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In net/core/ethtool.c (ffffffff819092d7)
Location: include/uapi/linux/ethtool.h:123
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_settings
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff817b911b)
Location: include/uapi/linux/ethtool.h:123
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In net/core/ethtool.c (ffffffff8193ba17)
Location: include/uapi/linux/ethtool.h:123
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_settings
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81a855aa)
Location: include/uapi/linux/ethtool.h:123
Inline: True
Inline callers:
  - net/ethtool/common.c:convert_legacy_settings_to_link_ksettings
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81a8ef3a)
Location: include/uapi/linux/ethtool.h:123
Inline: True
Inline callers:
  - net/ethtool/common.c:convert_legacy_settings_to_link_ksettings
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81a7863a)
Location: include/uapi/linux/ethtool.h:132
Inline: True
Inline callers:
  - net/ethtool/common.c:convert_legacy_settings_to_link_ksettings
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81b3272a)
Location: include/uapi/linux/ethtool.h:132
Inline: True
Inline callers:
  - net/ethtool/common.c:convert_legacy_settings_to_link_ksettings
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81cbdc8a)
Location: include/uapi/linux/ethtool.h:132
Inline: True
Inline callers:
  - net/ethtool/common.c:convert_legacy_settings_to_link_ksettings
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81e7c46a)
Location: include/uapi/linux/ethtool.h:132
Inline: True
Inline callers:
  - net/ethtool/common.c:convert_legacy_settings_to_link_ksettings
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81ed880a)
Location: include/uapi/linux/ethtool.h:132
Inline: True
Inline callers:
  - net/ethtool/common.c:convert_legacy_settings_to_link_ksettings
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81f9c61a)
Location: include/uapi/linux/ethtool.h:132
Inline: True
Inline callers:
  - net/ethtool/common.c:convert_legacy_settings_to_link_ksettings
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/mii.c (ffff8000109cfb08)
Location: include/uapi/linux/ethtool.h:123
Inline: True
Inline callers:
  - drivers/net/mii.c:mii_ethtool_sset
```
```
In drivers/net/phy/phy.c (ffff8000109d15b4)
Location: include/uapi/linux/ethtool.h:123
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In net/core/ethtool.c (ffff800010bd9c60)
Location: include/uapi/linux/ethtool.h:123
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_settings
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (c0ab977c)
Location: include/uapi/linux/ethtool.h:123
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In net/core/ethtool.c (c0cf4cd8)
Location: include/uapi/linux/ethtool.h:123
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_settings
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (c000000000a91364)
Location: include/uapi/linux/ethtool.h:123
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In net/core/ethtool.c (c000000000cba134)
Location: include/uapi/linux/ethtool.h:123
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_settings
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffe00061dc66)
Location: include/uapi/linux/ethtool.h:123
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In net/core/ethtool.c (ffffffe0007619fa)
Location: include/uapi/linux/ethtool.h:123
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_settings
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8177dbeb)
Location: include/uapi/linux/ethtool.h:123
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In net/core/ethtool.c (ffffffff818db9e7)
Location: include/uapi/linux/ethtool.h:123
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_settings
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8175d9ab)
Location: include/uapi/linux/ethtool.h:123
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In net/core/ethtool.c (ffffffff81895827)
Location: include/uapi/linux/ethtool.h:123
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_settings
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff817adf9b)
Location: include/uapi/linux/ethtool.h:123
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In net/core/ethtool.c (ffffffff8192ca17)
Location: include/uapi/linux/ethtool.h:123
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_settings
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff817c7f2b)
Location: include/uapi/linux/ethtool.h:123
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In net/core/ethtool.c (ffffffff8194e0e7)
Location: include/uapi/linux/ethtool.h:123
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_settings
```
</details>
</li>
</ul>

## Differences
