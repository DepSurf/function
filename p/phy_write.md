# Function: <code>phy_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff815eb641)
Location: include/linux/phy.h:663
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_setup_forced
  - drivers/net/phy/phy_device.c:genphy_restart_aneg
  - drivers/net/phy/phy_device.c:genphy_suspend
  - drivers/net/phy/phy_device.c:genphy_resume
  - drivers/net/phy/phy_device.c:genphy_soft_reset
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8164a482)
Location: include/linux/phy.h:658
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_resume
  - drivers/net/phy/phy_device.c:genphy_suspend
  - drivers/net/phy/phy_device.c:genphy_soft_reset
  - drivers/net/phy/phy_device.c:genphy_restart_aneg
  - drivers/net/phy/phy_device.c:genphy_setup_forced
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8167b8e2)
Location: include/linux/phy.h:693
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_resume
  - drivers/net/phy/phy_device.c:genphy_suspend
  - drivers/net/phy/phy_device.c:genphy_soft_reset
  - drivers/net/phy/phy_device.c:genphy_config_aneg
  - drivers/net/phy/phy_device.c:genphy_config_aneg
  - drivers/net/phy/phy_device.c:genphy_restart_aneg
  - drivers/net/phy/phy_device.c:genphy_setup_forced
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8169081c)
Location: include/linux/phy.h:705
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/phy_device.c:genphy_resume
  - drivers/net/phy/phy_device.c:genphy_suspend
  - drivers/net/phy/phy_device.c:genphy_soft_reset
  - drivers/net/phy/phy_device.c:genphy_config_aneg
  - drivers/net/phy/phy_device.c:genphy_config_aneg
  - drivers/net/phy/phy_device.c:genphy_restart_aneg
  - drivers/net/phy/phy_device.c:genphy_setup_forced
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff816fa62c)
Location: include/linux/phy.h:727
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/phy_device.c:genphy_resume
  - drivers/net/phy/phy_device.c:genphy_suspend
  - drivers/net/phy/phy_device.c:genphy_soft_reset
  - drivers/net/phy/phy_device.c:genphy_config_aneg
  - drivers/net/phy/phy_device.c:genphy_config_aneg
  - drivers/net/phy/phy_device.c:genphy_restart_aneg
  - drivers/net/phy/phy_device.c:genphy_setup_forced
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81737bd5)
Location: include/linux/phy.h:744
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_soft_reset
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8175b743)
Location: include/linux/phy.h:735
Inline: True
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In drivers/net/ethernet/freescale/fman/fman_dtsec.c (ffff8000109f60a8)
Location: include/linux/phy.h:723
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_init
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_init
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_init
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_init
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_init
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_restart_autoneg
```
```
In drivers/net/ethernet/freescale/fman/fman_memac.c (ffff8000109f6484)
Location: include/linux/phy.h:723
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
In arch/arm/mach-imx/mach-imx6q.c (c0333c54)
Location: include/linux/phy.h:723
Inline: True
Inline callers:
  - arch/arm/mach-imx/mach-imx6q.c:ar8035_phy_fixup
  - arch/arm/mach-imx/mach-imx6q.c:ar8035_phy_fixup
  - arch/arm/mach-imx/mach-imx6q.c:ar8035_phy_fixup
  - arch/arm/mach-imx/mach-imx6q.c:ar8035_phy_fixup
  - arch/arm/mach-imx/mach-imx6q.c:ar8035_phy_fixup
  - arch/arm/mach-imx/mach-imx6q.c:ar8031_phy_fixup
  - arch/arm/mach-imx/mach-imx6q.c:ar8031_phy_fixup
  - arch/arm/mach-imx/mach-imx6q.c:ar8031_phy_fixup
  - arch/arm/mach-imx/mach-imx6q.c:ar8031_phy_fixup
  - arch/arm/mach-imx/mach-imx6q.c:ar8031_phy_fixup
  - arch/arm/mach-imx/mach-imx6q.c:ar8031_phy_fixup
  - arch/arm/mach-imx/mach-imx6q.c:ksz9021rn_phy_fixup
  - arch/arm/mach-imx/mach-imx6q.c:ksz9021rn_phy_fixup
  - arch/arm/mach-imx/mach-imx6q.c:ksz9021rn_phy_fixup
  - arch/arm/mach-imx/mach-imx6q.c:ksz9021rn_phy_fixup
  - arch/arm/mach-imx/mach-imx6q.c:ksz9021rn_phy_fixup
```
```
In arch/arm/mach-imx/mach-imx6sx.c (c0333f30)
Location: include/linux/phy.h:723
Inline: True
Inline callers:
  - arch/arm/mach-imx/mach-imx6sx.c:ar8031_phy_fixup
  - arch/arm/mach-imx/mach-imx6sx.c:ar8031_phy_fixup
  - arch/arm/mach-imx/mach-imx6sx.c:ar8031_phy_fixup
  - arch/arm/mach-imx/mach-imx6sx.c:ar8031_phy_fixup
```
```
In arch/arm/mach-imx/mach-imx6ul.c (c0333fd8)
Location: include/linux/phy.h:723
Inline: True
```
```
In arch/arm/mach-imx/mach-imx7d.c (c033404c)
Location: include/linux/phy.h:723
Inline: True
Inline callers:
  - arch/arm/mach-imx/mach-imx7d.c:bcm54220_phy_fixup
  - arch/arm/mach-imx/mach-imx7d.c:bcm54220_phy_fixup
  - arch/arm/mach-imx/mach-imx7d.c:bcm54220_phy_fixup
  - arch/arm/mach-imx/mach-imx7d.c:bcm54220_phy_fixup
  - arch/arm/mach-imx/mach-imx7d.c:ar8031_phy_fixup
  - arch/arm/mach-imx/mach-imx7d.c:ar8031_phy_fixup
  - arch/arm/mach-imx/mach-imx7d.c:ar8031_phy_fixup
  - arch/arm/mach-imx/mach-imx7d.c:ar8031_phy_fixup
  - arch/arm/mach-imx/mach-imx7d.c:ar8031_phy_fixup
  - arch/arm/mach-imx/mach-imx7d.c:ar8031_phy_fixup
```
</details>
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
