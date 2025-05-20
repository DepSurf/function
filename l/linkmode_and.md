# Function: <code>linkmode_and</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81758d88)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-core.c (ffffffff8175984a)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (ffffffff8175a7b0)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
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
In drivers/net/phy/phy.c (ffffffff81794a45)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (ffffffff817962cc)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffffffff81796da7)
Location: include/linux/linkmode.h:18
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff817983ab)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
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
In drivers/net/phy/phy.c (ffffffff817b85e5)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (ffffffff817b9c8c)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffffffff817bada7)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (ffffffff817bc74b)
Location: include/linux/linkmode.h:18
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8187fe83)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
```
```
In drivers/net/phy/phy-c45.c (ffffffff8188137c)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffffffff81882657)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_check_downshift
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (ffffffff81883f9c)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_config_advert
```
```
In drivers/net/phy/linkmode.c (ffffffff8188608e)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
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
In drivers/net/phy/phy.c (ffffffff8188e733)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
```
```
In drivers/net/phy/phy-c45.c (ffffffff8188faac)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffffffff81890d87)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_check_downshift
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (ffffffff818926cc)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_config_advert
```
```
In drivers/net/phy/linkmode.c (ffffffff818944ee)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
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
In drivers/net/phy/phy.c (ffffffff81870ff4)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
```
```
In drivers/net/phy/phy-c45.c (ffffffff8187234c)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffffffff81873667)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_check_downshift
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (ffffffff81874e8c)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_config_advert
```
```
In drivers/net/phy/linkmode.c (ffffffff81876dee)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
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
In drivers/net/phy/phy.c (ffffffff819016d4)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
```
```
In drivers/net/phy/phy-c45.c (ffffffff81902a5c)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffffffff81903f10)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_check_downshift
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (ffffffff8190595c)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_config_advert
```
```
In drivers/net/phy/linkmode.c (ffffffff819079fe)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
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
In drivers/net/phy/phy.c (ffffffff81a53025)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
```
```
In drivers/net/phy/phy-c45.c (ffffffff81a5505f)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffffffff81a569a0)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_check_downshift
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (ffffffff81a5a6ab)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:__genphy_config_aneg
```
```
In drivers/net/phy/linkmode.c (ffffffff81a5aa9e)
Location: include/linux/linkmode.h:18
Inline: True
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
In drivers/net/phy/phy.c (ffffffff81bdc185)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
```
```
In drivers/net/phy/phy-c45.c (ffffffff81bde3df)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffffffff81be0702)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_check_downshift
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (ffffffff81be460b)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_config_advert
```
```
In drivers/net/phy/linkmode.c (ffffffff81be533e)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
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
In drivers/net/phy/phy.c (ffffffff81c332d6)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
```
```
In drivers/net/phy/phy-c45.c (ffffffff81c3620c)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_read_eee_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffffffff81c38012)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_check_downshift
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (ffffffff81c3c848)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:genphy_config_advert
```
```
In drivers/net/phy/linkmode.c (ffffffff81c3cdce)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
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
In drivers/net/phy/phy.c (ffffffff81ce7fc6)
Location: include/linux/linkmode.h:23
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
```
```
In drivers/net/phy/phy-c45.c (ffffffff81ceb18c)
Location: include/linux/linkmode.h:23
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_read_eee_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffffffff81ced3a2)
Location: include/linux/linkmode.h:23
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_check_downshift
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (ffffffff81cf1c48)
Location: include/linux/linkmode.h:23
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:genphy_config_advert
```
```
In drivers/net/phy/linkmode.c (ffffffff81cf21ce)
Location: include/linux/linkmode.h:23
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
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
In drivers/net/phy/phy.c (ffff8000109d1a14)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (ffff8000109d1e04)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffff8000109d38b4)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (ffff8000109d5790)
Location: include/linux/linkmode.h:18
Inline: True
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
In drivers/net/phy/phy.c (c0ab9bf8)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (c0ab9fdc)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (c0abb71c)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (c0abd280)
Location: include/linux/linkmode.h:18
Inline: True
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
In drivers/net/phy/phy.c (c000000000a90c78)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (c000000000a91afc)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (c000000000a93db0)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (c000000000a966bc)
Location: include/linux/linkmode.h:18
Inline: True
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
In drivers/net/phy/phy.c (ffffffe00061e3f0)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (ffffffe00061e852)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffffffe00061ff62)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (ffffffe000621920)
Location: include/linux/linkmode.h:18
Inline: True
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
In drivers/net/phy/phy.c (ffffffff8177d0b5)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (ffffffff8177e75c)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffffffff8177f877)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (ffffffff8178121b)
Location: include/linux/linkmode.h:18
Inline: True
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
In drivers/net/phy/phy.c (ffffffff8175ce65)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (ffffffff8175e4fc)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffffffff8175f617)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (ffffffff81760fab)
Location: include/linux/linkmode.h:18
Inline: True
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
In drivers/net/phy/phy.c (ffffffff817ad465)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (ffffffff817aeb0c)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffffffff817afc27)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (ffffffff817b15cb)
Location: include/linux/linkmode.h:18
Inline: True
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
In drivers/net/phy/phy.c (ffffffff817c73f5)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (ffffffff817c8a9c)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffffffff817c9bb7)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (ffffffff817cb55b)
Location: include/linux/linkmode.h:18
Inline: True
```
</details>
</li>
</ul>

## Differences
