# Function: <code>linkmode_mod_bit</code>

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
In drivers/net/phy/phy.c (ffffffff817583c6)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
```
In drivers/net/phy/phy-c45.c (ffffffff8175958f)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy_device.c (ffffffff8175c086)
Location: include/linux/linkmode.h:60
Inline: True
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
In drivers/net/phy/phy.c (ffffffff81794eb3)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (ffffffff81796080)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy_device.c (ffffffff817973ad)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
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
In drivers/net/phy/phy.c (ffffffff817b89b5)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (ffffffff817b9a40)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy_device.c (ffffffff817baedd)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
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
In drivers/net/phy/phy.c (ffffffff8187fb02)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
```
```
In drivers/net/phy/phy-c45.c (ffffffff81880f40)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy_device.c (ffffffff818852ad)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
```
```
In drivers/net/phy/linkmode.c (ffffffff81886025)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/bcm84881.c (ffffffff818892a8)
Location: include/linux/linkmode.h:60
Inline: True
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
In drivers/net/phy/phy.c (ffffffff8188e3b2)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
```
```
In drivers/net/phy/phy-c45.c (ffffffff8188f670)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy_device.c (ffffffff81893b5d)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
```
```
In drivers/net/phy/linkmode.c (ffffffff81894485)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/bcm84881.c (ffffffff81897518)
Location: include/linux/linkmode.h:60
Inline: True
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
In drivers/net/phy/phy.c (ffffffff81870bea)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
```
```
In drivers/net/phy/phy-c45.c (ffffffff81871f45)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy_device.c (ffffffff818766a4)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
```
```
In drivers/net/phy/linkmode.c (ffffffff81876d85)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/bcm84881.c (ffffffff81879d33)
Location: include/linux/linkmode.h:60
Inline: True
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
In drivers/net/phy/phy.c (ffffffff81900ff5)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
```
In drivers/net/phy/phy-c45.c (ffffffff81902545)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy_device.c (ffffffff819072b4)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
```
```
In drivers/net/phy/linkmode.c (ffffffff81907995)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/bcm84881.c (ffffffff8190adba)
Location: include/linux/linkmode.h:60
Inline: True
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
In drivers/net/phy/phy.c (ffffffff81a53874)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
```
In drivers/net/phy/phy-c45.c (ffffffff81a54356)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
```
```
In drivers/net/phy/phy_device.c (ffffffff81a59404)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
```
```
In drivers/net/phy/linkmode.c (ffffffff81a5aa15)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/bcm84881.c (ffffffff81a5e767)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
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
In drivers/net/phy/phy.c (ffffffff81bdd254)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
```
In drivers/net/phy/phy-c45.c (ffffffff81bdeae6)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
```
```
In drivers/net/phy/phy_device.c (ffffffff81be4029)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
```
```
In drivers/net/phy/linkmode.c (ffffffff81be52a5)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/bcm84881.c (ffffffff81be9507)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
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
In drivers/net/phy/phy.c (ffffffff81c3335e)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
```
In drivers/net/phy/phy-c45.c (ffffffff81c36198)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_eee_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_eee_adv
```
```
In drivers/net/phy/phy_device.c (ffffffff81c3bb39)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
```
```
In drivers/net/phy/linkmode.c (ffffffff81c3cd35)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/bcm84881.c (ffffffff81c4191f)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
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
In drivers/net/phy/phy.c (ffffffff81ce804e)
Location: include/linux/linkmode.h:56
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
```
In drivers/net/phy/phy-c45.c (ffffffff81ceb118)
Location: include/linux/linkmode.h:56
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_ext_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_ext_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_ext_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_ext_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_ext_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_ext_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_ext_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_ext_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_ext_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_ext_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_ext_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_ext_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_baset1_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_baset1_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_baset1_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_baset1_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_eee_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_eee_adv
```
```
In drivers/net/phy/phy_device.c (ffffffff81cf0f39)
Location: include/linux/linkmode.h:56
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
```
```
In drivers/net/phy/linkmode.c (ffffffff81cf2135)
Location: include/linux/linkmode.h:56
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/bcm84881.c (ffffffff81cf6faf)
Location: include/linux/linkmode.h:56
Inline: True
Inline callers:
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
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
In drivers/net/phy/phy.c (ffff8000109d1038)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (ffff8000109d2460)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy_device.c (ffff8000109d5ca8)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
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
In drivers/net/phy/phy.c (c0ab9264)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (c0aba5cc)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy_device.c (c0abd6d0)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
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
In drivers/net/phy/phy.c (c000000000a90830)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (c000000000a92440)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy_device.c (c000000000a969fc)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
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
In drivers/net/phy/phy.c (ffffffe00061e012)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (ffffffe00061ed50)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy_device.c (ffffffe000621ff8)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
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
In drivers/net/phy/phy.c (ffffffff8177d485)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (ffffffff8177e510)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy_device.c (ffffffff8177f9ad)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
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
In drivers/net/phy/phy.c (ffffffff8175d245)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (ffffffff8175e2b0)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy_device.c (ffffffff8175f74d)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
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
In drivers/net/phy/phy.c (ffffffff817ad835)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (ffffffff817ae8c0)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy_device.c (ffffffff817afd5d)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
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
In drivers/net/phy/phy.c (ffffffff817c77c5)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (ffffffff817c8850)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy_device.c (ffffffff817c9ced)
Location: include/linux/linkmode.h:60
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
```
</details>
</li>
</ul>

## Differences
