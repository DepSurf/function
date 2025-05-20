# Function: <code>bus_find_device_by_acpi_dev</code>

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
In drivers/acpi/acpi_platform.c (ffffffff815eb9b1)
Location: include/linux/device.h:251
Inline: True
```
```
In drivers/spi/spi.c (ffffffff817b424e)
Location: include/linux/device.h:251
Inline: True
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff818720c5)
Location: include/linux/device.h:251
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
In drivers/acpi/acpi_platform.c (ffffffff81697421)
Location: include/linux/device/bus.h:237
Inline: True
```
```
In drivers/spi/spi.c (ffffffff8187b7fe)
Location: include/linux/device/bus.h:237
Inline: True
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81946504)
Location: include/linux/device/bus.h:237
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
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
In drivers/acpi/acpi_platform.c (ffffffff816b4574)
Location: include/linux/device/bus.h:237
Inline: True
```
```
In drivers/spi/spi.c (ffffffff8188a4c1)
Location: include/linux/device/bus.h:237
Inline: True
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff8194c45a)
Location: include/linux/device/bus.h:237
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
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
In drivers/acpi/acpi_platform.c (ffffffff816967a4)
Location: include/linux/device/bus.h:237
Inline: True
```
```
In drivers/spi/spi.c (ffffffff8186cea1)
Location: include/linux/device/bus.h:237
Inline: True
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff819303a0)
Location: include/linux/device/bus.h:237
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
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
In drivers/acpi/acpi_platform.c (ffffffff8170c544)
Location: include/linux/device/bus.h:237
Inline: True
```
```
In drivers/spi/spi.c (ffffffff818fcd51)
Location: include/linux/device/bus.h:237
Inline: True
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff819d3671)
Location: include/linux/device/bus.h:237
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
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
In drivers/acpi/acpi_platform.c (ffffffff8183ac00)
Location: include/linux/device/bus.h:241
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81a4e336)
Location: include/linux/device/bus.h:241
Inline: True
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81b35d54)
Location: include/linux/device/bus.h:241
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
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
In drivers/acpi/acpi_platform.c (ffffffff8197027d)
Location: include/linux/device/bus.h:241
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81bd88e5)
Location: include/linux/device/bus.h:241
Inline: True
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81ccafd1)
Location: include/linux/device/bus.h:241
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
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
In drivers/acpi/acpi_platform.c (ffffffff819b68bc)
Location: include/linux/device/bus.h:221
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81c2f2d4)
Location: include/linux/device/bus.h:221
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
In drivers/acpi/acpi_platform.c (ffffffff81a00e6c)
Location: include/linux/device/bus.h:216
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81ce1f44)
Location: include/linux/device/bus.h:216
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
In drivers/acpi/acpi_platform.c (ffff800010776e90)
Location: include/linux/device.h:251
Inline: True
```
```
In drivers/spi/spi.c (ffff8000109c4178)
Location: include/linux/device.h:251
Inline: True
```
```
In drivers/i2c/i2c-core-acpi.c (ffff800010ab59a8)
Location: include/linux/device.h:251
Inline: True
```
</details>
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_platform.c (ffffffff815dad91)
Location: include/linux/device.h:251
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81778d2e)
Location: include/linux/device.h:251
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
In drivers/acpi/acpi_platform.c (ffffffff815c63d1)
Location: include/linux/device.h:251
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81758ade)
Location: include/linux/device.h:251
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
In drivers/acpi/acpi_platform.c (ffffffff815dfc91)
Location: include/linux/device.h:251
Inline: True
```
```
In drivers/spi/spi.c (ffffffff817a90ce)
Location: include/linux/device.h:251
Inline: True
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81866255)
Location: include/linux/device.h:251
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
In drivers/acpi/acpi_platform.c (ffffffff815f9b51)
Location: include/linux/device.h:251
Inline: True
```
```
In drivers/spi/spi.c (ffffffff817c2f5e)
Location: include/linux/device.h:251
Inline: True
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81881505)
Location: include/linux/device.h:251
Inline: True
```
</details>
</li>
</ul>

## Differences
