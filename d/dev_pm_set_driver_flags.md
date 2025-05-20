# Function: <code>dev_pm_set_driver_flags</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff81648135)
Location: include/linux/device.h:1077
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_probe_device
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
In drivers/pci/pcie/portdrv_pci.c (ffffffff81530b34)
Location: include/linux/device.h:1122
Inline: True
```
```
In drivers/base/dd.c (ffffffff8168364f)
Location: include/linux/device.h:1122
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff817dba12)
Location: include/linux/device.h:1122
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
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
In drivers/pwm/pwm-lpss-platform.c (ffffffff8152824d)
Location: include/linux/device.h:1175
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff815480c4)
Location: include/linux/device.h:1175
Inline: True
```
```
In drivers/base/dd.c (ffffffff816a334a)
Location: include/linux/device.h:1175
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81802dbb)
Location: include/linux/device.h:1175
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
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
In drivers/pwm/pwm-lpss-platform.c (ffffffff815574da)
Location: include/linux/device.h:1208
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff81578147)
Location: include/linux/device.h:1208
Inline: True
```
```
In drivers/base/dd.c (ffffffff816dc17a)
Location: include/linux/device.h:1208
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff818441c3)
Location: include/linux/device.h:1208
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
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
In drivers/pwm/pwm-lpss-platform.c (ffffffff81578b0a)
Location: include/linux/device.h:1450
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff815998cf)
Location: include/linux/device.h:1450
Inline: True
```
```
In drivers/base/dd.c (ffffffff817001b6)
Location: include/linux/device.h:1450
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81875b39)
Location: include/linux/device.h:1450
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
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
In drivers/pwm/pwm-lpss-platform.c (ffffffff8161db1a)
Location: include/linux/device.h:757
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff816390af)
Location: include/linux/device.h:757
Inline: True
```
```
In drivers/base/dd.c (ffffffff817b904e)
Location: include/linux/device.h:757
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:really_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8194a472)
Location: include/linux/device.h:757
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
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
In drivers/pwm/pwm-lpss-platform.c (ffffffff8164435c)
Location: include/linux/device.h:725
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff8165fb85)
Location: include/linux/device.h:725
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
```
```
In drivers/base/dd.c (ffffffff817cddd7)
Location: include/linux/device.h:725
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:really_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81950002)
Location: include/linux/device.h:725
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
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
In drivers/pwm/pwm-lpss-platform.c (ffffffff816270bc)
Location: include/linux/device.h:731
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff8164206e)
Location: include/linux/device.h:731
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
```
```
In drivers/base/dd.c (ffffffff817b17dc)
Location: include/linux/device.h:731
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:really_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81933eb4)
Location: include/linux/device.h:731
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
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
In drivers/pwm/pwm-lpss-platform.c (ffffffff8169698a)
Location: include/linux/device.h:748
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff816b2d40)
Location: include/linux/device.h:748
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
```
```
In drivers/base/dd.c (ffffffff8183aa7b)
Location: include/linux/device.h:748
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:really_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff819d72b4)
Location: include/linux/device.h:748
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
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
In drivers/pwm/pwm-lpss-platform.c (ffffffff817b78b4)
Location: include/linux/device.h:823
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff817d676a)
Location: include/linux/device.h:823
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
```
```
In drivers/base/dd.c (ffffffff8197cc31)
Location: include/linux/device.h:823
Inline: True
Inline callers:
  - drivers/base/dd.c:device_unbind_cleanup
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81b3a01e)
Location: include/linux/device.h:823
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
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
In drivers/pwm/pwm-lpss-platform.c (ffffffff818d207f)
Location: include/linux/device.h:820
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/pcie/portdrv.c (ffffffff818f7b5a)
Location: include/linux/device.h:820
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
```
```
In drivers/base/dd.c (ffffffff81ae9e41)
Location: include/linux/device.h:820
Inline: True
Inline callers:
  - drivers/base/dd.c:device_unbind_cleanup
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81ccf99e)
Location: include/linux/device.h:820
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
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
In drivers/pwm/pwm-lpss-platform.c (ffffffff8191507f)
Location: include/linux/device.h:946
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/pcie/portdrv.c (ffffffff8193afb3)
Location: include/linux/device.h:946
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
```
```
In drivers/base/dd.c (ffffffff81b381c1)
Location: include/linux/device.h:946
Inline: True
Inline callers:
  - drivers/base/dd.c:device_unbind_cleanup
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81d37a97)
Location: include/linux/device.h:946
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
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
In drivers/pwm/pwm-lpss-platform.c (ffffffff8195cfef)
Location: include/linux/device.h:978
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/pcie/portdrv.c (ffffffff81983e46)
Location: include/linux/device.h:978
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
```
```
In drivers/base/dd.c (ffffffff81b8fc61)
Location: include/linux/device.h:978
Inline: True
Inline callers:
  - drivers/base/dd.c:device_unbind_cleanup
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81dedd17)
Location: include/linux/device.h:978
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
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
In drivers/pci/pcie/portdrv_pci.c (ffff800010701024)
Location: include/linux/device.h:1450
Inline: True
```
```
In drivers/base/dd.c (ffff8000108eb4dc)
Location: include/linux/device.h:1450
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffff800010aba97c)
Location: include/linux/device.h:1450
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
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
In drivers/pci/pcie/portdrv_pci.c (c0898dc4)
Location: include/linux/device.h:1450
Inline: True
```
```
In drivers/base/dd.c (c09d95dc)
Location: include/linux/device.h:1450
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (c0b99ed0)
Location: include/linux/device.h:1450
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
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
In drivers/base/dd.c (c000000000982b38)
Location: include/linux/device.h:1450
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (c000000000b9de4c)
Location: include/linux/device.h:1450
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
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
In drivers/pci/pcie/portdrv_pci.c (ffffffe0004cfe34)
Location: include/linux/device.h:1450
Inline: True
```
```
In drivers/base/dd.c (ffffffe00057f118)
Location: include/linux/device.h:1450
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffe0006bf2f2)
Location: include/linux/device.h:1450
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
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
In drivers/pci/pcie/portdrv_pci.c (ffffffff8158d75f)
Location: include/linux/device.h:1450
Inline: True
```
```
In drivers/base/dd.c (ffffffff816c59a6)
Location: include/linux/device.h:1450
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
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
In drivers/pci/pcie/portdrv_pci.c (ffffffff8157c29f)
Location: include/linux/device.h:1450
Inline: True
```
```
In drivers/base/dd.c (ffffffff816a0c26)
Location: include/linux/device.h:1450
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
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
In drivers/pwm/pwm-lpss-platform.c (ffffffff8156c85a)
Location: include/linux/device.h:1450
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff8158d61f)
Location: include/linux/device.h:1450
Inline: True
```
```
In drivers/base/dd.c (ffffffff816f3e76)
Location: include/linux/device.h:1450
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8186afe9)
Location: include/linux/device.h:1450
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
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
In drivers/pwm/pwm-lpss-platform.c (ffffffff81586d5a)
Location: include/linux/device.h:1450
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff815a7acf)
Location: include/linux/device.h:1450
Inline: True
```
```
In drivers/base/dd.c (ffffffff8170e6a6)
Location: include/linux/device.h:1450
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81884f79)
Location: include/linux/device.h:1450
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
</details>
</li>
</ul>

## Differences
