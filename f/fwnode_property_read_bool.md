# Function: <code>fwnode_property_read_bool</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/soundwire/mipi_disco.c (ffffffff818c3095)
Location: include/linux/property.h:168
Inline: True
Inline callers:
  - drivers/soundwire/mipi_disco.c:sdw_slave_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_slave_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_slave_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_master_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_master_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_master_read_prop
```
</details>
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817ef0e5)
Location: include/linux/property.h:182
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_get_val_endian
  - drivers/base/regmap/regmap.c:regmap_get_val_endian
  - drivers/base/regmap/regmap.c:regmap_get_val_endian
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
In drivers/dma/lgm/lgm-dma.c (ffffffff81707b94)
Location: include/linux/property.h:182
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_cfg_init
  - drivers/dma/lgm/lgm-dma.c:ldma_cfg_init
  - drivers/dma/lgm/lgm-dma.c:ldma_cfg_init
```
```
In drivers/base/regmap/regmap.c (ffffffff817d3975)
Location: include/linux/property.h:182
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_get_val_endian
  - drivers/base/regmap/regmap.c:regmap_get_val_endian
  - drivers/base/regmap/regmap.c:regmap_get_val_endian
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
In drivers/dma/lgm/lgm-dma.c (ffffffff81783464)
Location: include/linux/property.h:182
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_cfg_init
  - drivers/dma/lgm/lgm-dma.c:ldma_cfg_init
  - drivers/dma/lgm/lgm-dma.c:ldma_cfg_init
```
```
In drivers/base/regmap/regmap.c (ffffffff8185eb15)
Location: include/linux/property.h:182
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_get_val_endian
  - drivers/base/regmap/regmap.c:regmap_get_val_endian
  - drivers/base/regmap/regmap.c:regmap_get_val_endian
```
```
In drivers/net/mdio/fwnode_mdio.c (ffffffff8190b82c)
Location: include/linux/property.h:182
Inline: True
Inline callers:
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
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
In drivers/dma/lgm/lgm-dma.c (ffffffff818ba084)
Location: include/linux/property.h:188
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_cfg_init
  - drivers/dma/lgm/lgm-dma.c:ldma_cfg_init
  - drivers/dma/lgm/lgm-dma.c:ldma_cfg_init
```
```
In drivers/base/regmap/regmap.c (ffffffff819a64f1)
Location: include/linux/property.h:188
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_get_val_endian
  - drivers/base/regmap/regmap.c:regmap_get_val_endian
  - drivers/base/regmap/regmap.c:regmap_get_val_endian
```
```
In drivers/net/mdio/fwnode_mdio.c (ffffffff81a5f0db)
Location: include/linux/property.h:188
Inline: True
Inline callers:
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
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
In drivers/dma/lgm/lgm-dma.c (ffffffff81a08ab4)
Location: include/linux/property.h:202
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_parse_dt
  - drivers/dma/lgm/lgm-dma.c:ldma_parse_dt
  - drivers/dma/lgm/lgm-dma.c:ldma_parse_dt
```
```
In drivers/base/regmap/regmap.c (ffffffff81b18bf1)
Location: include/linux/property.h:202
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_get_val_endian
  - drivers/base/regmap/regmap.c:regmap_get_val_endian
  - drivers/base/regmap/regmap.c:regmap_get_val_endian
```
```
In drivers/net/mdio/fwnode_mdio.c (ffffffff81bea46b)
Location: include/linux/property.h:202
Inline: True
Inline callers:
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
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
In drivers/dma/lgm/lgm-dma.c (ffffffff81a51934)
Location: include/linux/property.h:213
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_parse_dt
  - drivers/dma/lgm/lgm-dma.c:ldma_parse_dt
  - drivers/dma/lgm/lgm-dma.c:ldma_parse_dt
```
```
In drivers/base/regmap/regmap.c (ffffffff81b679e1)
Location: include/linux/property.h:213
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_get_val_endian
  - drivers/base/regmap/regmap.c:regmap_get_val_endian
  - drivers/base/regmap/regmap.c:regmap_get_val_endian
```
```
In drivers/net/mdio/fwnode_mdio.c (ffffffff81c4289b)
Location: include/linux/property.h:213
Inline: True
Inline callers:
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
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
In drivers/dma/lgm/lgm-dma.c (ffffffff81a9d684)
Location: include/linux/property.h:253
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_parse_dt
  - drivers/dma/lgm/lgm-dma.c:ldma_parse_dt
  - drivers/dma/lgm/lgm-dma.c:ldma_parse_dt
```
```
In drivers/base/regmap/regmap.c (ffffffff81bbb801)
Location: include/linux/property.h:253
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_get_val_endian
  - drivers/base/regmap/regmap.c:regmap_get_val_endian
  - drivers/base/regmap/regmap.c:regmap_get_val_endian
```
```
In drivers/net/mdio/fwnode_mdio.c (ffffffff81cf7f5b)
Location: include/linux/property.h:253
Inline: True
Inline callers:
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
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
