# Function: <code>of_node_test_and_set_flag</code>

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
In drivers/spi/spi.c (ffff8000109c7b18)
Location: include/linux/of.h:193
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/i2c/i2c-core-of.c (ffff800010ab6d68)
Location: include/linux/of.h:193
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-of.c:of_i2c_register_devices
```
```
In drivers/of/platform.c (ffff800010b6da3c)
Location: include/linux/of.h:193
Inline: True
Inline callers:
  - drivers/of/platform.c:of_platform_bus_create
  - drivers/of/platform.c:of_platform_device_create_pdata
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
In drivers/spi/spi.c (c0ab0c20)
Location: include/linux/of.h:193
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/i2c/i2c-core-of.c (c0b96ec4)
Location: include/linux/of.h:193
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-of.c:of_i2c_register_devices
```
```
In drivers/of/platform.c (c0c508dc)
Location: include/linux/of.h:193
Inline: True
Inline callers:
  - drivers/of/platform.c:of_platform_bus_create
  - drivers/of/platform.c:of_platform_device_create_pdata
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
In drivers/spi/spi.c (c000000000a88620)
Location: include/linux/of.h:193
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/i2c/i2c-core-of.c (c000000000b99d70)
Location: include/linux/of.h:193
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-of.c:of_i2c_register_devices
```
```
In drivers/of/platform.c (c000000000c47e3c)
Location: include/linux/of.h:193
Inline: True
Inline callers:
  - drivers/of/platform.c:of_platform_device_create_pdata
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
In drivers/spi/spi.c (ffffffe00061828e)
Location: include/linux/of.h:193
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/i2c/i2c-core-of.c (ffffffe0006bc8da)
Location: include/linux/of.h:193
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-of.c:of_i2c_register_devices
```
```
In drivers/of/platform.c (ffffffe0007222e6)
Location: include/linux/of.h:193
Inline: True
Inline callers:
  - drivers/of/platform.c:of_platform_device_create_pdata
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
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
