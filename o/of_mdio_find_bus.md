# Function: <code>of_mdio_find_bus</code>

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
<summary>In <code>arm64</code>: ✅</summary>

```c
struct mii_bus *of_mdio_find_bus(struct device_node *mdio_bus_np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffff8000109d6d80)
Location: drivers/net/phy/mdio_bus.c:277
Inline: False
Direct callers:
  - drivers/net/phy/mdio-mux.c:mdio_mux_init
```
**Symbols:**

```
ffff8000109d6d80-ffff8000109d6ddc: of_mdio_find_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct mii_bus *of_mdio_find_bus(struct device_node *mdio_bus_np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (c0abe8b8)
Location: drivers/net/phy/mdio_bus.c:277
Inline: False
```
**Symbols:**

```
c0abe8b8-c0abe904: of_mdio_find_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct mii_bus *of_mdio_find_bus(struct device_node *mdio_bus_np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (c000000000a98960)
Location: drivers/net/phy/mdio_bus.c:277
Inline: False
```
**Symbols:**

```
c000000000a98960-c000000000a989e8: of_mdio_find_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct mii_bus *of_mdio_find_bus(struct device_node *mdio_bus_np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffe000622f16)
Location: drivers/net/phy/mdio_bus.c:277
Inline: False
```
**Symbols:**

```
ffffffe000622f16-ffffffe000622f66: of_mdio_find_bus (STB_GLOBAL)
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
<b>Arch</b>
<ul>
</ul>
