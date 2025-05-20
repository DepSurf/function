# Function: <code>bus_find_device_by_of_node</code>

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
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff817ac5c5)
Location: include/linux/device.h:200
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node
```
```
In drivers/nvmem/core.c (0)
Location: include/linux/device.h:200
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff818727c5)
Location: include/linux/device/bus.h:186
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff818812c9)
Location: include/linux/device/bus.h:186
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff81863b59)
Location: include/linux/device/bus.h:186
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff818f2e99)
Location: include/linux/device/bus.h:186
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff81a45539)
Location: include/linux/device/bus.h:190
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff81bcbe39)
Location: include/linux/device/bus.h:190
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff81c239b9)
Location: include/linux/device/bus.h:170
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff81cd5279)
Location: include/linux/device/bus.h:165
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node
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
In drivers/gpu/drm/drm_mipi_dsi.c (ffff8000109bdeb8)
Location: include/linux/device.h:200
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node
```
```
In drivers/spi/spi.c (ffff8000109c3638)
Location: include/linux/device.h:200
Inline: True
```
```
In drivers/i2c/i2c-core-of.c (ffff800010ab6948)
Location: include/linux/device.h:200
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-of.c:of_find_i2c_device_by_node
```
```
In drivers/of/platform.c (ffff800010b6d038)
Location: include/linux/device.h:200
Inline: True
```
```
In drivers/of/of_mdio.c (ffff800010b75adc)
Location: include/linux/device.h:200
Inline: True
Inline callers:
  - drivers/of/of_mdio.c:of_phy_find_device
```
```
In drivers/nvmem/core.c (ffff800010b9ee14)
Location: include/linux/device.h:200
Inline: True
Inline callers:
  - drivers/nvmem/core.c:__nvmem_device_get
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
In drivers/gpu/drm/drm_mipi_dsi.c (c0a8bdec)
Location: include/linux/device.h:200
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node
```
```
In drivers/spi/spi.c (c0ab051c)
Location: include/linux/device.h:200
Inline: True
```
```
In drivers/i2c/i2c-core-of.c (c0b96b94)
Location: include/linux/device.h:200
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-of.c:of_find_i2c_device_by_node
```
```
In drivers/of/platform.c (c0c4fff0)
Location: include/linux/device.h:200
Inline: True
```
```
In drivers/of/of_mdio.c (c0c57ec4)
Location: include/linux/device.h:200
Inline: True
Inline callers:
  - drivers/of/of_mdio.c:of_phy_find_device
```
```
In drivers/nvmem/core.c (c0c80ba0)
Location: include/linux/device.h:200
Inline: True
Inline callers:
  - drivers/nvmem/core.c:__nvmem_device_get
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
In drivers/gpu/drm/drm_mipi_dsi.c (c000000000a7f01c)
Location: include/linux/device.h:200
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node
```
```
In drivers/spi/spi.c (c000000000a86b1c)
Location: include/linux/device.h:200
Inline: True
```
```
In drivers/i2c/i2c-core-of.c (c000000000b997d4)
Location: include/linux/device.h:200
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-of.c:of_find_i2c_device_by_node
```
```
In drivers/of/platform.c (c000000000c4777c)
Location: include/linux/device.h:200
Inline: True
```
```
In drivers/of/of_mdio.c (c000000000c531c4)
Location: include/linux/device.h:200
Inline: True
Inline callers:
  - drivers/of/of_mdio.c:of_phy_find_device
```
```
In drivers/nvmem/core.c (c000000000c72168)
Location: include/linux/device.h:200
Inline: True
Inline callers:
  - drivers/nvmem/core.c:__nvmem_device_get
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
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffe000611ac0)
Location: include/linux/device.h:200
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node
```
```
In drivers/spi/spi.c (ffffffe0006169b8)
Location: include/linux/device.h:200
Inline: True
```
```
In drivers/i2c/i2c-core-of.c (ffffffe0006bc5a2)
Location: include/linux/device.h:200
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-of.c:of_find_i2c_device_by_node
```
```
In drivers/of/platform.c (ffffffe000721e6a)
Location: include/linux/device.h:200
Inline: True
```
```
In drivers/of/of_mdio.c (ffffffe00072910c)
Location: include/linux/device.h:200
Inline: True
Inline callers:
  - drivers/of/of_mdio.c:of_phy_find_device
```
```
In drivers/nvmem/core.c (ffffffe00073711a)
Location: include/linux/device.h:200
Inline: True
Inline callers:
  - drivers/nvmem/core.c:__nvmem_device_get
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
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff817710e5)
Location: include/linux/device.h:200
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node
```
```
In drivers/nvmem/core.c (0)
Location: include/linux/device.h:200
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
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff81750f35)
Location: include/linux/device.h:200
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node
```
```
In drivers/nvmem/core.c (0)
Location: include/linux/device.h:200
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
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff817a1445)
Location: include/linux/device.h:200
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node
```
```
In drivers/nvmem/core.c (0)
Location: include/linux/device.h:200
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
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff817bb2c5)
Location: include/linux/device.h:200
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node
```
```
In drivers/nvmem/core.c (0)
Location: include/linux/device.h:200
Inline: True
```
</details>
</li>
</ul>

## Differences
