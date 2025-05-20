# Function: <code>linkmode_copy</code>

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
In drivers/net/phy/phy.c (ffffffff81758605)
Location: include/linux/linkmode.h:13
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (ffffffff817596fd)
Location: include/linux/linkmode.h:13
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:gen10g_config_init
```
```
In drivers/net/phy/phy_device.c (ffffffff8175c5fe)
Location: include/linux/linkmode.h:13
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_remove_link_mode
  - drivers/net/phy/phy_device.c:phy_set_max_speed
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
In drivers/net/phy/phy.c (ffffffff81795425)
Location: include/linux/linkmode.h:13
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy_device.c (ffffffff817997ee)
Location: include/linux/linkmode.h:13
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
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
In drivers/net/phy/phy.c (ffffffff817b8d65)
Location: include/linux/linkmode.h:13
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy_device.c (ffffffff817bd30e)
Location: include/linux/linkmode.h:13
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
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
In drivers/net/phy/phy.c (ffffffff8187f2d5)
Location: include/linux/linkmode.h:13
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
```
```
In drivers/net/phy/phy_device.c (ffffffff81884dfe)
Location: include/linux/linkmode.h:13
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
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
In drivers/net/phy/phy.c (ffffffff8188db85)
Location: include/linux/linkmode.h:13
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
```
```
In drivers/net/phy/phy_device.c (ffffffff81893881)
Location: include/linux/linkmode.h:13
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
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
In drivers/net/phy/phy.c (ffffffff818704c9)
Location: include/linux/linkmode.h:13
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
```
```
In drivers/net/phy/phy_device.c (ffffffff81876461)
Location: include/linux/linkmode.h:13
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
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
In drivers/net/phy/phy.c (ffffffff81900f53)
Location: include/linux/linkmode.h:13
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
```
```
In drivers/net/phy/phy_device.c (ffffffff81907071)
Location: include/linux/linkmode.h:13
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
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
In drivers/net/phy/phy.c (ffffffff81a53a2b)
Location: include/linux/linkmode.h:13
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_speed_down
  - drivers/net/phy/phy.c:phy_speed_down
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
```
```
In drivers/net/phy/phy_device.c (ffffffff81a5a2fe)
Location: include/linux/linkmode.h:13
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
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
In drivers/net/phy/phy.c (ffffffff81bdd0ff)
Location: include/linux/linkmode.h:13
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_speed_down
  - drivers/net/phy/phy.c:phy_speed_down
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
```
```
In drivers/net/phy/phy_device.c (ffffffff81be5118)
Location: include/linux/linkmode.h:13
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_remove_link_mode
  - drivers/net/phy/phy_device.c:phy_remove_link_mode
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
In drivers/net/phy/phy.c (ffffffff81c328f5)
Location: include/linux/linkmode.h:13
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_speed_down
  - drivers/net/phy/phy.c:phy_speed_down
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
```
```
In drivers/net/phy/phy-c45.c (ffffffff81c368a9)
Location: include/linux/linkmode.h:13
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_ethtool_set_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
```
```
In drivers/net/phy/phy_device.c (ffffffff81c3c6b6)
Location: include/linux/linkmode.h:13
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_remove_link_mode
  - drivers/net/phy/phy_device.c:phy_remove_link_mode
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
In drivers/net/phy/phy.c (ffffffff81ce75e5)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_speed_down
  - drivers/net/phy/phy.c:phy_speed_down
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
```
```
In drivers/net/phy/phy-c45.c (ffffffff81ceb829)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_ethtool_set_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
```
```
In drivers/net/phy/phy_device.c (ffffffff81cf1ab6)
Location: include/linux/linkmode.h:18
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_remove_link_mode
  - drivers/net/phy/phy_device.c:phy_remove_link_mode
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
In drivers/net/phy/phy.c (ffff8000109d126c)
Location: include/linux/linkmode.h:13
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy_device.c (ffff8000109d62e0)
Location: include/linux/linkmode.h:13
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
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
In drivers/net/phy/phy.c (c0ab93e0)
Location: include/linux/linkmode.h:13
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy_device.c (c0abdc38)
Location: include/linux/linkmode.h:13
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
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
In drivers/net/phy/phy.c (c000000000a90f48)
Location: include/linux/linkmode.h:13
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy_device.c (c000000000a979a8)
Location: include/linux/linkmode.h:13
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
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
In drivers/net/phy/phy.c (ffffffe00061d1e8)
Location: include/linux/linkmode.h:13
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy_device.c (ffffffe0006225d6)
Location: include/linux/linkmode.h:13
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
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
In drivers/net/phy/phy.c (ffffffff8177d835)
Location: include/linux/linkmode.h:13
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy_device.c (ffffffff81781dde)
Location: include/linux/linkmode.h:13
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
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
In drivers/net/phy/phy.c (ffffffff8175d5f5)
Location: include/linux/linkmode.h:13
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy_device.c (ffffffff81761b6e)
Location: include/linux/linkmode.h:13
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
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
In drivers/net/phy/phy.c (ffffffff817adbe5)
Location: include/linux/linkmode.h:13
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy_device.c (ffffffff817b218e)
Location: include/linux/linkmode.h:13
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
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
In drivers/net/phy/phy.c (ffffffff817c7b75)
Location: include/linux/linkmode.h:13
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_get
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy_device.c (ffffffff817cc11e)
Location: include/linux/linkmode.h:13
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
```
</details>
</li>
</ul>

## Differences
