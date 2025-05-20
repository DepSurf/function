# Function: <code>of_mdio_parse_addr</code>

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
In drivers/net/phy/mdio_bus.c (ffff8000109d72a0)
Location: include/linux/of_mdio.h:34
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_scan
```
```
In drivers/of/of_mdio.c (ffff800010b75fd0)
Location: include/linux/of_mdio.h:34
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
In drivers/net/phy/mdio_bus.c (c0abea58)
Location: include/linux/of_mdio.h:34
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_scan
```
```
In drivers/of/of_mdio.c (c0c58394)
Location: include/linux/of_mdio.h:34
Inline: True
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
In drivers/net/phy/mdio_bus.c (c000000000a98c88)
Location: include/linux/of_mdio.h:34
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_scan
```
```
In drivers/of/of_mdio.c (c000000000c539dc)
Location: include/linux/of_mdio.h:34
Inline: True
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
In drivers/net/phy/mdio_bus.c (ffffffe000623078)
Location: include/linux/of_mdio.h:34
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_scan
```
```
In drivers/of/of_mdio.c (ffffffe0007294cc)
Location: include/linux/of_mdio.h:34
Inline: True
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
