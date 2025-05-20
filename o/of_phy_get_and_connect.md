# Function: <code>of_phy_get_and_connect</code>

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
struct phy_device *of_phy_get_and_connect(struct net_device *dev, struct device_node *np, void (*hndlr)(struct net_device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/of_mdio.c (ffff800010b76390)
Location: drivers/of/of_mdio.c:356
Inline: False
```
**Symbols:**

```
ffff800010b76390-ffff800010b76474: of_phy_get_and_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct phy_device *of_phy_get_and_connect(struct net_device *dev, struct device_node *np, void (*hndlr)(struct net_device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/of_mdio.c (c0c58750)
Location: drivers/of/of_mdio.c:356
Inline: False
```
**Symbols:**

```
c0c58750-c0c58824: of_phy_get_and_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct phy_device *of_phy_get_and_connect(struct net_device *dev, struct device_node *np, void (*hndlr)(struct net_device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/of_mdio.c (c000000000c54010)
Location: drivers/of/of_mdio.c:356
Inline: False
```
**Symbols:**

```
c000000000c54010-c000000000c54148: of_phy_get_and_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct phy_device *of_phy_get_and_connect(struct net_device *dev, struct device_node *np, void (*hndlr)(struct net_device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/of_mdio.c (ffffffe000729826)
Location: drivers/of/of_mdio.c:356
Inline: False
```
**Symbols:**

```
ffffffe000729826-ffffffe0007298e0: of_phy_get_and_connect (STB_GLOBAL)
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
