# Function: <code>class_find_device_by_of_node</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/leds/led-class.c (0)
Location: include/linux/device/class.h:140
Inline: True
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
In drivers/leds/led-class.c (0)
Location: include/linux/device/class.h:140
Inline: True
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
In drivers/leds/led-class.c (0)
Location: include/linux/device/class.h:140
Inline: True
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
In drivers/leds/led-class.c (0)
Location: include/linux/device/class.h:140
Inline: True
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
In drivers/leds/led-class.c (0)
Location: include/linux/device/class.h:140
Inline: True
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
In drivers/leds/led-class.c (0)
Location: include/linux/device/class.h:140
Inline: True
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
In drivers/leds/led-class.c (0)
Location: include/linux/device/class.h:120
Inline: True
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
In drivers/leds/led-class.c (0)
Location: include/linux/device/class.h:118
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
In drivers/regulator/of_regulator.c (ffff80001084bf20)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/regulator/of_regulator.c:of_parse_coupled_regulator
```
```
In drivers/spi/spi.c (ffff8000109c4290)
Location: include/linux/device.h:659
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (ffff8000109d6d9c)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:of_mdio_find_bus
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
In drivers/regulator/of_regulator.c (c0955424)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/regulator/of_regulator.c:of_parse_coupled_regulator
```
```
In drivers/spi/spi.c (c0ab0f68)
Location: include/linux/device.h:659
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (c0abe8d4)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:of_mdio_find_bus
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
In drivers/regulator/of_regulator.c (c0000000008ea434)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/regulator/of_regulator.c:of_parse_coupled_regulator
```
```
In drivers/spi/spi.c (c000000000a88c80)
Location: include/linux/device.h:659
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (c000000000a98984)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:of_mdio_find_bus
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
In drivers/regulator/of_regulator.c (ffffffe00052b82c)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/regulator/of_regulator.c:of_parse_coupled_regulator
```
```
In drivers/spi/spi.c (ffffffe000618654)
Location: include/linux/device.h:659
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (ffffffe000622f2e)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:of_mdio_find_bus
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
