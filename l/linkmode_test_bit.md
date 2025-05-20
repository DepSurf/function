# Function: <code>linkmode_test_bit</code>

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
In drivers/net/phy/phy.c (ffffffff8175825d)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start_aneg
```
```
In drivers/net/phy/phy-core.c (ffffffff81759857)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (ffffffff8175a165)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_validate_pause
  - drivers/net/phy/phy_device.c:phy_validate_pause
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
In drivers/net/phy/phy.c (ffffffff8179470b)
Location: include/linux/linkmode.h:74
Inline: True
```
```
In drivers/net/phy/phy-c45.c (ffffffff81796300)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffffffff81796df1)
Location: include/linux/linkmode.h:74
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff81799805)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
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
In drivers/net/phy/phy.c (ffffffff817b82ab)
Location: include/linux/linkmode.h:74
Inline: True
```
```
In drivers/net/phy/phy-c45.c (ffffffff817b9cc0)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffffffff817ba8a1)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (ffffffff817bd325)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
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
In drivers/net/phy/phy.c (ffffffff8187ef92)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_print_status
  - drivers/net/phy/phy.c:phy_print_status
```
```
In drivers/net/phy/phy-c45.c (ffffffff818813a0)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffffffff81881da1)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (ffffffff81884e15)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
```
```
In drivers/net/phy/linkmode.c (ffffffff81886093)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
```
```
In drivers/net/phy/bcm84881.c (ffffffff8188940c)
Location: include/linux/linkmode.h:74
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
In drivers/net/phy/phy.c (ffffffff8188d832)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_print_status
  - drivers/net/phy/phy.c:phy_print_status
```
```
In drivers/net/phy/phy-c45.c (ffffffff8188fad0)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffffffff81890566)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (ffffffff81893898)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
```
```
In drivers/net/phy/linkmode.c (ffffffff818944f3)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
```
```
In drivers/net/phy/bcm84881.c (ffffffff8189767c)
Location: include/linux/linkmode.h:74
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
In drivers/net/phy/phy.c (ffffffff81870172)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_print_status
  - drivers/net/phy/phy.c:phy_print_status
```
```
In drivers/net/phy/phy-c45.c (ffffffff81872380)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffffffff81872e26)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (ffffffff81876478)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
```
```
In drivers/net/phy/linkmode.c (ffffffff81876df3)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
```
```
In drivers/net/phy/bcm84881.c (ffffffff81879f3d)
Location: include/linux/linkmode.h:74
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
In drivers/net/phy/phy.c (ffffffff81900752)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_print_status
  - drivers/net/phy/phy.c:phy_print_status
```
```
In drivers/net/phy/phy-c45.c (ffffffff81902a90)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffffffff8190357f)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (ffffffff81907088)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
```
```
In drivers/net/phy/linkmode.c (ffffffff81907a03)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
```
```
In drivers/net/phy/bcm84881.c (ffffffff8190afe2)
Location: include/linux/linkmode.h:74
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
In drivers/net/phy/phy.c (ffffffff81a51fad)
Location: include/linux/linkmode.h:69
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_print_status
  - drivers/net/phy/phy.c:phy_print_status
```
```
In drivers/net/phy/phy-c45.c (ffffffff81a546b2)
Location: include/linux/linkmode.h:69
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_fast_retrain
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffffffff81a55ff9)
Location: include/linux/linkmode.h:69
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (ffffffff81a5a313)
Location: include/linux/linkmode.h:69
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:__genphy_config_aneg
  - drivers/net/phy/phy_device.c:__genphy_config_aneg
  - drivers/net/phy/phy_device.c:__genphy_config_aneg
  - drivers/net/phy/phy_device.c:__genphy_config_aneg
  - drivers/net/phy/phy_device.c:__genphy_config_aneg
  - drivers/net/phy/phy_device.c:__genphy_config_aneg
  - drivers/net/phy/phy_device.c:__genphy_config_aneg
  - drivers/net/phy/phy_device.c:__genphy_config_aneg
```
```
In drivers/net/phy/linkmode.c (ffffffff81a5aaa3)
Location: include/linux/linkmode.h:69
Inline: True
```
```
In drivers/net/phy/bcm84881.c (ffffffff81a5e4ed)
Location: include/linux/linkmode.h:69
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
In drivers/net/phy/phy.c (ffffffff81bdbb36)
Location: include/linux/linkmode.h:69
Inline: True
```
```
In drivers/net/phy/phy-c45.c (ffffffff81bde411)
Location: include/linux/linkmode.h:69
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffffffff81bdfb65)
Location: include/linux/linkmode.h:69
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff81be5120)
Location: include/linux/linkmode.h:69
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_validate_pause
  - drivers/net/phy/phy_device.c:phy_validate_pause
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
```
```
In drivers/net/phy/linkmode.c (ffffffff81be5343)
Location: include/linux/linkmode.h:69
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
```
```
In drivers/net/phy/bcm84881.c (ffffffff81be922c)
Location: include/linux/linkmode.h:69
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
In drivers/net/phy/phy.c (ffffffff81c33f78)
Location: include/linux/linkmode.h:69
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_set_plca_cfg
```
```
In drivers/net/phy/phy-c45.c (ffffffff81c361ec)
Location: include/linux/linkmode.h:69
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_read_eee_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_eee_adv
  - drivers/net/phy/phy-c45.c:genphy_c45_write_eee_adv
  - drivers/net/phy/phy-c45.c:genphy_c45_write_eee_adv
  - drivers/net/phy/phy-c45.c:genphy_c45_write_eee_adv
  - drivers/net/phy/phy-c45.c:genphy_c45_write_eee_adv
  - drivers/net/phy/phy-c45.c:genphy_c45_write_eee_adv
  - drivers/net/phy/phy-c45.c:genphy_c45_write_eee_adv
  - drivers/net/phy/phy-c45.c:genphy_c45_write_eee_adv
  - drivers/net/phy/phy-c45.c:genphy_c45_write_eee_adv
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffffffff81c37455)
Location: include/linux/linkmode.h:69
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff81c3c6cd)
Location: include/linux/linkmode.h:69
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_validate_pause
  - drivers/net/phy/phy_device.c:phy_validate_pause
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
```
```
In drivers/net/phy/linkmode.c (ffffffff81c3cdd3)
Location: include/linux/linkmode.h:69
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
```
```
In drivers/net/phy/bcm84881.c (ffffffff81c41655)
Location: include/linux/linkmode.h:69
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
In drivers/net/phy/phy.c (ffffffff81ce9237)
Location: include/linux/linkmode.h:65
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_set_plca_cfg
```
```
In drivers/net/phy/phy-c45.c (ffffffff81ceb16c)
Location: include/linux/linkmode.h:65
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_read_eee_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_eee_adv
  - drivers/net/phy/phy-c45.c:genphy_c45_write_eee_adv
  - drivers/net/phy/phy-c45.c:genphy_c45_write_eee_adv
  - drivers/net/phy/phy-c45.c:genphy_c45_write_eee_adv
  - drivers/net/phy/phy-c45.c:genphy_c45_write_eee_adv
  - drivers/net/phy/phy-c45.c:genphy_c45_write_eee_adv
  - drivers/net/phy/phy-c45.c:genphy_c45_write_eee_adv
  - drivers/net/phy/phy-c45.c:genphy_c45_write_eee_adv
  - drivers/net/phy/phy-c45.c:genphy_c45_write_eee_adv
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffffffff81cec235)
Location: include/linux/linkmode.h:65
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff81cf1acd)
Location: include/linux/linkmode.h:65
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_validate_pause
  - drivers/net/phy/phy_device.c:phy_validate_pause
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:genphy_config_advert
```
```
In drivers/net/phy/linkmode.c (ffffffff81cf21d3)
Location: include/linux/linkmode.h:65
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
```
```
In drivers/net/phy/bcm84881.c (ffffffff81cf6ce5)
Location: include/linux/linkmode.h:65
Inline: True
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
In drivers/net/phy/phy.c (ffff8000109d0af0)
Location: include/linux/linkmode.h:74
Inline: True
```
```
In drivers/net/phy/phy-c45.c (ffff8000109d1e24)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffff8000109d30e0)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (ffff8000109d62ec)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
```
```
In drivers/net/ethernet/freescale/fman/mac.c (ffff8000109f30e8)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/mac.c:fman_get_pause_cfg
  - drivers/net/ethernet/freescale/fman/mac.c:fman_get_pause_cfg
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
In drivers/net/phy/phy.c (c0ab8cc0)
Location: include/linux/linkmode.h:74
Inline: True
```
```
In drivers/net/phy/phy-c45.c (c0aba058)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (c0abb084)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (c0abdc50)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
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
In drivers/net/phy/phy.c (c000000000a900ac)
Location: include/linux/linkmode.h:74
Inline: True
```
```
In drivers/net/phy/phy-c45.c (c000000000a91b28)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (c000000000a93480)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (c000000000a979b8)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
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
In drivers/net/phy/phy.c (ffffffe00061d792)
Location: include/linux/linkmode.h:74
Inline: True
```
```
In drivers/net/phy/phy-c45.c (ffffffe00061e86e)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffffffe00061f8ea)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (ffffffe0006225e4)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
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
In drivers/net/phy/phy.c (ffffffff8177cd7b)
Location: include/linux/linkmode.h:74
Inline: True
```
```
In drivers/net/phy/phy-c45.c (ffffffff8177e790)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffffffff8177f371)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (ffffffff81781df5)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
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
In drivers/net/phy/phy.c (ffffffff8175cb2b)
Location: include/linux/linkmode.h:74
Inline: True
```
```
In drivers/net/phy/phy-c45.c (ffffffff8175e530)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffffffff8175f111)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (ffffffff81761b85)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
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
In drivers/net/phy/phy.c (ffffffff817ad12b)
Location: include/linux/linkmode.h:74
Inline: True
```
```
In drivers/net/phy/phy-c45.c (ffffffff817aeb40)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffffffff817af721)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (ffffffff817b21a5)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
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
In drivers/net/phy/phy.c (ffffffff817c70bb)
Location: include/linux/linkmode.h:74
Inline: True
```
```
In drivers/net/phy/phy-c45.c (ffffffff817c8ad0)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffffffff817c96b1)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (ffffffff817cc135)
Location: include/linux/linkmode.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
```
</details>
</li>
</ul>

## Differences
