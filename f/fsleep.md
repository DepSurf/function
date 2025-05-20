# Function: <code>fsleep</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817f3db2)
Location: include/linux/delay.h:69
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write
  - drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write
```
```
In drivers/net/phy/mdio_bus.c (ffffffff8189543f)
Location: include/linux/delay.h:69
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
```
```
In drivers/net/phy/mdio_device.c (ffffffff81895709)
Location: include/linux/delay.h:69
Inline: True
Inline callers:
  - drivers/net/phy/mdio_device.c:mdio_device_reset
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
In drivers/base/regmap/regmap.c (ffffffff817d8622)
Location: include/linux/delay.h:69
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write
  - drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81877a52)
Location: include/linux/delay.h:69
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
```
```
In drivers/net/phy/mdio_device.c (ffffffff81877f79)
Location: include/linux/delay.h:69
Inline: True
Inline callers:
  - drivers/net/phy/mdio_device.c:mdio_device_reset
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
In drivers/base/regmap/regmap.c (ffffffff81863d95)
Location: include/linux/delay.h:81
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write
  - drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write
```
```
In drivers/net/phy/mdio_bus.c (ffffffff819087ca)
Location: include/linux/delay.h:81
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
```
```
In drivers/net/phy/mdio_device.c (ffffffff81908df9)
Location: include/linux/delay.h:81
Inline: True
Inline callers:
  - drivers/net/phy/mdio_device.c:mdio_device_reset
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
In drivers/base/regmap/regmap.c (ffffffff819abf2e)
Location: include/linux/delay.h:81
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write
  - drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81a5bb0d)
Location: include/linux/delay.h:81
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
```
```
In drivers/net/phy/mdio_device.c (ffffffff81a5c375)
Location: include/linux/delay.h:81
Inline: True
Inline callers:
  - drivers/net/phy/mdio_device.c:mdio_device_reset
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
In drivers/base/regmap/regmap.c (ffffffff81b1f4fe)
Location: include/linux/delay.h:81
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write
  - drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81be659a)
Location: include/linux/delay.h:81
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
```
```
In drivers/net/phy/mdio_device.c (ffffffff81be6e05)
Location: include/linux/delay.h:81
Inline: True
Inline callers:
  - drivers/net/phy/mdio_device.c:mdio_device_reset
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
In drivers/base/regmap/regmap.c (ffffffff81b6e6fe)
Location: include/linux/delay.h:82
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write
  - drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81c3dd71)
Location: include/linux/delay.h:82
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
```
```
In drivers/net/phy/mdio_device.c (ffffffff81c3f165)
Location: include/linux/delay.h:82
Inline: True
Inline callers:
  - drivers/net/phy/mdio_device.c:mdio_device_reset
```
```
In drivers/md/dm-init.c (ffffffff83726573)
Location: include/linux/delay.h:82
Inline: True
Inline callers:
  - drivers/md/dm-init.c:dm_init_init
```
```
In drivers/md/dm.c (ffffffff81d77ba3)
Location: include/linux/delay.h:82
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In drivers/md/dm-kcopyd.c (ffffffff81d840ee)
Location: include/linux/delay.h:82
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:run_io_job
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
In drivers/base/regmap/regmap.c (ffffffff81bc22fe)
Location: include/linux/delay.h:82
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write
  - drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81cf326e)
Location: include/linux/delay.h:82
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
```
```
In drivers/net/phy/mdio_device.c (ffffffff81cf4724)
Location: include/linux/delay.h:82
Inline: True
Inline callers:
  - drivers/net/phy/mdio_device.c:mdio_device_reset
```
```
In drivers/md/dm-init.c (ffffffff8395a466)
Location: include/linux/delay.h:82
Inline: True
Inline callers:
  - drivers/md/dm-init.c:dm_init_init
```
```
In drivers/md/dm.c (ffffffff81e2edd3)
Location: include/linux/delay.h:82
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In drivers/md/dm-kcopyd.c (ffffffff81e3b7fe)
Location: include/linux/delay.h:82
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:run_io_job
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
