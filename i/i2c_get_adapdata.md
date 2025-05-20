# Function: <code>i2c_get_adapdata</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-common.c (0)
Location: include/linux/i2c.h:599
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-master.c (0)
Location: include/linux/i2c.h:599
Inline: True
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
In drivers/i2c/busses/i2c-designware-common.c (0)
Location: include/linux/i2c.h:601
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8179828b)
Location: include/linux/i2c.h:601
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
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
In drivers/i2c/busses/i2c-designware-common.c (ffffffff817da305)
Location: include/linux/i2c.h:690
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_func
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff817db415)
Location: include/linux/i2c.h:690
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/i2c/busses/i2c-amd-platdrv.c (ffffffff817dd3c9)
Location: include/linux/i2c.h:690
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_xfer
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
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81801725)
Location: include/linux/i2c.h:698
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_func
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff818027c5)
Location: include/linux/i2c.h:698
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
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
In drivers/i2c/busses/i2c-designware-common.c (ffffffff818429d5)
Location: include/linux/i2c.h:717
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_func
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff818436a5)
Location: include/linux/i2c.h:717
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
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
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81874355)
Location: include/linux/i2c.h:717
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_func
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81875025)
Location: include/linux/i2c.h:717
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
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
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81948a15)
Location: include/linux/i2c.h:719
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_func
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81949ef5)
Location: include/linux/i2c.h:719
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
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
In drivers/i2c/busses/i2c-designware-common.c (ffffffff8194e815)
Location: include/linux/i2c.h:727
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_func
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8194fbb5)
Location: include/linux/i2c.h:727
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
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
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81932375)
Location: include/linux/i2c.h:735
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_func
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81933a75)
Location: include/linux/i2c.h:735
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
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
In drivers/i2c/busses/i2c-designware-common.c (ffffffff819d5725)
Location: include/linux/i2c.h:744
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_func
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff819d6e45)
Location: include/linux/i2c.h:744
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
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
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81b381c5)
Location: include/linux/i2c.h:753
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_func
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81b399a5)
Location: include/linux/i2c.h:753
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
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
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81ccd855)
Location: include/linux/i2c.h:755
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_func
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81ccf0e5)
Location: include/linux/i2c.h:755
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
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
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81d35605)
Location: include/linux/i2c.h:761
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_func
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81d36dd5)
Location: include/linux/i2c.h:761
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
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
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81deb795)
Location: include/linux/i2c.h:754
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_func
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81decfe5)
Location: include/linux/i2c.h:754
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
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
In drivers/i2c/busses/i2c-designware-common.c (ffff800010ab92a8)
Location: include/linux/i2c.h:717
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_func
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffff800010ab9de0)
Location: include/linux/i2c.h:717
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/i2c/busses/i2c-omap.c (ffff800010abb2b8)
Location: include/linux/i2c.h:717
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_unprepare_recovery
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_prepare_recovery
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_set_scl
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_get_sda
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_get_scl
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_common
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg
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
In drivers/i2c/busses/i2c-designware-common.c (c0b98900)
Location: include/linux/i2c.h:717
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_func
```
```
In drivers/i2c/busses/i2c-designware-master.c (c0b9949c)
Location: include/linux/i2c.h:717
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/i2c/busses/i2c-imx.c (c0b9b2dc)
Location: include/linux/i2c.h:717
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_xfer
```
```
In drivers/i2c/busses/i2c-omap.c (c0b9c6cc)
Location: include/linux/i2c.h:717
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_unprepare_recovery
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_prepare_recovery
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_set_scl
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_get_sda
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_get_scl
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_common
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg
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
In drivers/i2c/busses/i2c-designware-common.c (c000000000b9c3d8)
Location: include/linux/i2c.h:717
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_func
```
```
In drivers/i2c/busses/i2c-designware-master.c (c000000000b9d9b0)
Location: include/linux/i2c.h:717
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
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
In drivers/i2c/busses/i2c-designware-common.c (ffffffe0006be0e0)
Location: include/linux/i2c.h:717
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_func
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffe0006befb8)
Location: include/linux/i2c.h:717
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
</details>
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
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-amd-mp2-plat.c (ffffffff81868e35)
Location: include/linux/i2c.h:717
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_xfer
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81869805)
Location: include/linux/i2c.h:717
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_func
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8186a4d5)
Location: include/linux/i2c.h:717
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
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
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81883795)
Location: include/linux/i2c.h:717
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_func
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81884465)
Location: include/linux/i2c.h:717
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
</details>
</li>
</ul>

## Differences
