# Function: <code>linkmode_set_bit</code>

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
In drivers/net/phy/phy.c (ffffffff817580b6)
Location: include/linux/linkmode.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_speed_up
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
In drivers/net/phy/phy-c45.c (ffffffff817596f1)
Location: include/linux/linkmode.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:gen10g_config_init
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
In drivers/net/phy/phy_device.c (ffffffff828e855f)
Location: include/linux/linkmode.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8175edb2)
Location: include/linux/linkmode.h:41
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
In drivers/net/phy/phy.c (ffffffff817948fe)
Location: include/linux/linkmode.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_speed_up
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
In drivers/net/phy/phy-c45.c (ffffffff817960bd)
Location: include/linux/linkmode.h:41
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
```
```
In drivers/net/phy/phy_device.c (ffffffff82902e8b)
Location: include/linux/linkmode.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
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
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8179c3f1)
Location: include/linux/linkmode.h:41
Inline: True
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
In drivers/net/phy/phy.c (ffffffff817b849e)
Location: include/linux/linkmode.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
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
In drivers/net/phy/phy-c45.c (ffffffff817b9a7d)
Location: include/linux/linkmode.h:41
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
```
```
In drivers/net/phy/phy_device.c (ffffffff8290c088)
Location: include/linux/linkmode.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
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
  - drivers/net/phy/phy_device.c:genphy_read_abilities
```
```
In drivers/net/phy/fixed_phy.c (ffffffff817bfea5)
Location: include/linux/linkmode.h:41
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
In drivers/net/phy/phy.c (ffffffff8187f02e)
Location: include/linux/linkmode.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
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
In drivers/net/phy/phy-c45.c (ffffffff81880f80)
Location: include/linux/linkmode.h:41
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
```
```
In drivers/net/phy/phy_device.c (ffffffff81884e86)
Location: include/linux/linkmode.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
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
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
```
```
In drivers/net/phy/linkmode.c (ffffffff8188602d)
Location: include/linux/linkmode.h:41
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/bcm84881.c (ffffffff818892b1)
Location: include/linux/linkmode.h:41
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (ffffffff81889945)
Location: include/linux/linkmode.h:41
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
In drivers/net/phy/phy.c (ffffffff8188d8ce)
Location: include/linux/linkmode.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
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
In drivers/net/phy/phy-c45.c (ffffffff8188f6b0)
Location: include/linux/linkmode.h:41
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
```
```
In drivers/net/phy/phy_device.c (ffffffff81893909)
Location: include/linux/linkmode.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
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
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
```
```
In drivers/net/phy/linkmode.c (ffffffff8189448d)
Location: include/linux/linkmode.h:41
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/bcm84881.c (ffffffff81897521)
Location: include/linux/linkmode.h:41
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (ffffffff81897bb5)
Location: include/linux/linkmode.h:41
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
In drivers/net/phy/phy.c (ffffffff8187020e)
Location: include/linux/linkmode.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
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
In drivers/net/phy/phy-c45.c (ffffffff81871f78)
Location: include/linux/linkmode.h:41
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
```
```
In drivers/net/phy/phy_device.c (ffffffff818764f1)
Location: include/linux/linkmode.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
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
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
```
```
In drivers/net/phy/linkmode.c (ffffffff81876d8d)
Location: include/linux/linkmode.h:41
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/bcm84881.c (ffffffff81879d3c)
Location: include/linux/linkmode.h:41
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8187a43f)
Location: include/linux/linkmode.h:41
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
In drivers/net/phy/phy.c (ffffffff819007ee)
Location: include/linux/linkmode.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
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
In drivers/net/phy/phy-c45.c (ffffffff81902578)
Location: include/linux/linkmode.h:41
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
```
```
In drivers/net/phy/phy_device.c (ffffffff81907101)
Location: include/linux/linkmode.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
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
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
```
```
In drivers/net/phy/linkmode.c (ffffffff8190799d)
Location: include/linux/linkmode.h:41
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/bcm84881.c (ffffffff8190adc3)
Location: include/linux/linkmode.h:41
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8190b53f)
Location: include/linux/linkmode.h:41
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
In drivers/net/phy/phy.c (ffffffff81a525ee)
Location: include/linux/linkmode.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
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
In drivers/net/phy/phy-c45.c (ffffffff81a54396)
Location: include/linux/linkmode.h:41
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
```
```
In drivers/net/phy/phy_device.c (ffffffff81a5a380)
Location: include/linux/linkmode.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
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
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
```
```
In drivers/net/phy/linkmode.c (ffffffff81a5aa1d)
Location: include/linux/linkmode.h:41
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/bcm84881.c (ffffffff81a5e770)
Location: include/linux/linkmode.h:41
Inline: True
Inline callers:
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
```
```
In drivers/net/phy/fixed_phy.c (ffffffff81a5ed6e)
Location: include/linux/linkmode.h:41
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
In drivers/net/phy/phy.c (ffffffff81bdbf35)
Location: include/linux/linkmode.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
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
In drivers/net/phy/phy-c45.c (ffffffff81bdeb26)
Location: include/linux/linkmode.h:41
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
```
```
In drivers/net/phy/phy_device.c (ffffffff81be51b8)
Location: include/linux/linkmode.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
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
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
```
```
In drivers/net/phy/linkmode.c (ffffffff81be52ad)
Location: include/linux/linkmode.h:41
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/bcm84881.c (ffffffff81be9510)
Location: include/linux/linkmode.h:41
Inline: True
Inline callers:
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
```
```
In drivers/net/phy/fixed_phy.c (ffffffff81be9bee)
Location: include/linux/linkmode.h:41
Inline: True
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
In drivers/net/phy/phy.c (ffffffff81c33432)
Location: include/linux/linkmode.h:41
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
In drivers/net/phy/phy-c45.c (ffffffff81c361a0)
Location: include/linux/linkmode.h:41
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
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_eee_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_eee_adv
```
```
In drivers/net/phy/phy_device.c (ffffffff81c3c876)
Location: include/linux/linkmode.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
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
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
```
```
In drivers/net/phy/linkmode.c (ffffffff81c3cd3d)
Location: include/linux/linkmode.h:41
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/bcm84881.c (ffffffff81c41928)
Location: include/linux/linkmode.h:41
Inline: True
Inline callers:
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
```
```
In drivers/net/phy/fixed_phy.c (ffffffff81c4201e)
Location: include/linux/linkmode.h:41
Inline: True
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
In drivers/net/phy/phy.c (ffffffff81ce8122)
Location: include/linux/linkmode.h:46
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
In drivers/net/phy/phy-c45.c (ffffffff81ceb120)
Location: include/linux/linkmode.h:46
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
In drivers/net/phy/phy_device.c (ffffffff81cf1c76)
Location: include/linux/linkmode.h:46
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
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
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
```
```
In drivers/net/phy/linkmode.c (ffffffff81cf213d)
Location: include/linux/linkmode.h:46
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/bcm84881.c (ffffffff81cf6fb8)
Location: include/linux/linkmode.h:46
Inline: True
Inline callers:
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
```
```
In drivers/net/phy/fixed_phy.c (ffffffff81cf76de)
Location: include/linux/linkmode.h:46
Inline: True
```
```
In net/ethtool/common.c (ffffffff81f9c44e)
Location: include/linux/linkmode.h:46
Inline: True
Inline callers:
  - net/ethtool/common.c:ethtool_forced_speed_maps_init
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
In drivers/net/phy/phy.c (ffff8000109d11ec)
Location: include/linux/linkmode.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
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
In drivers/net/phy/phy-c45.c (ffff8000109d2464)
Location: include/linux/linkmode.h:41
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
In drivers/net/phy/phy_device.c (ffff8000109d6364)
Location: include/linux/linkmode.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
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
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
```
```
In drivers/net/phy/fixed_phy.c (ffff8000109da3c0)
Location: include/linux/linkmode.h:41
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
In drivers/net/phy/phy.c (c0ab8f0c)
Location: include/linux/linkmode.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
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
In drivers/net/phy/phy-c45.c (c0aba5a8)
Location: include/linux/linkmode.h:41
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
In drivers/net/phy/phy_device.c (c0abdcbc)
Location: include/linux/linkmode.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
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
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
```
```
In drivers/net/phy/fixed_phy.c (c0ac0f94)
Location: include/linux/linkmode.h:41
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
In drivers/net/phy/phy.c (c000000000a90a7c)
Location: include/linux/linkmode.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
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
In drivers/net/phy/phy-c45.c (c000000000a924a0)
Location: include/linux/linkmode.h:41
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
In drivers/net/phy/phy_device.c (c000000000a97a38)
Location: include/linux/linkmode.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
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
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
```
```
In drivers/net/phy/fixed_phy.c (c000000000a9c340)
Location: include/linux/linkmode.h:41
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
In drivers/net/phy/phy.c (ffffffe00061d47c)
Location: include/linux/linkmode.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
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
In drivers/net/phy/phy-c45.c (ffffffe00061ed90)
Location: include/linux/linkmode.h:41
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
In drivers/net/phy/phy_device.c (ffffffe00062265c)
Location: include/linux/linkmode.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
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
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
```
```
In drivers/net/phy/fixed_phy.c (ffffffe0006251ca)
Location: include/linux/linkmode.h:41
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
In drivers/net/phy/phy.c (ffffffff8177cf6e)
Location: include/linux/linkmode.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
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
In drivers/net/phy/phy-c45.c (ffffffff8177e54d)
Location: include/linux/linkmode.h:41
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
```
```
In drivers/net/phy/phy_device.c (ffffffff828f3a45)
Location: include/linux/linkmode.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
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
  - drivers/net/phy/phy_device.c:genphy_read_abilities
```
```
In drivers/net/phy/fixed_phy.c (ffffffff81784975)
Location: include/linux/linkmode.h:41
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
In drivers/net/phy/phy.c (ffffffff8175cd1e)
Location: include/linux/linkmode.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
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
In drivers/net/phy/phy-c45.c (ffffffff8175e2ed)
Location: include/linux/linkmode.h:41
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
```
```
In drivers/net/phy/phy_device.c (ffffffff828eaef0)
Location: include/linux/linkmode.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
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
  - drivers/net/phy/phy_device.c:genphy_read_abilities
```
```
In drivers/net/phy/fixed_phy.c (ffffffff817642c5)
Location: include/linux/linkmode.h:41
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
In drivers/net/phy/phy.c (ffffffff817ad31e)
Location: include/linux/linkmode.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
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
In drivers/net/phy/phy-c45.c (ffffffff817ae8fd)
Location: include/linux/linkmode.h:41
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
```
```
In drivers/net/phy/phy_device.c (ffffffff82907483)
Location: include/linux/linkmode.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
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
  - drivers/net/phy/phy_device.c:genphy_read_abilities
```
```
In drivers/net/phy/fixed_phy.c (ffffffff817b4d25)
Location: include/linux/linkmode.h:41
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
In drivers/net/phy/phy.c (ffffffff817c72ae)
Location: include/linux/linkmode.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
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
In drivers/net/phy/phy-c45.c (ffffffff817c888d)
Location: include/linux/linkmode.h:41
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
```
```
In drivers/net/phy/phy_device.c (ffffffff8290d0ea)
Location: include/linux/linkmode.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
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
  - drivers/net/phy/phy_device.c:genphy_read_abilities
```
```
In drivers/net/phy/fixed_phy.c (ffffffff817cecf5)
Location: include/linux/linkmode.h:41
Inline: True
```
</details>
</li>
</ul>

## Differences
