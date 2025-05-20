# Function: <code>of_get_phy_id</code>

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
int of_get_phy_id(struct device_node *device, u32 *phy_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/of_mdio.c (ffff800010b757f8)
Location: drivers/of/of_mdio.c:30
Inline: False
Direct callers:
  - drivers/of/of_mdio.c:of_mdiobus_register_phy
```
**Symbols:**

```
ffff800010b757f8-ffff800010b758d8: of_get_phy_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_get_phy_id(struct device_node *device, u32 *phy_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/of_mdio.c (c0c57bf4)
Location: drivers/of/of_mdio.c:30
Inline: False
Direct callers:
  - drivers/of/of_mdio.c:of_mdiobus_register_phy
```
**Symbols:**

```
c0c57bf4-c0c57cc4: of_get_phy_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_get_phy_id(struct device_node *device, u32 *phy_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/of_mdio.c (c000000000c52dd0)
Location: drivers/of/of_mdio.c:30
Inline: False
Direct callers:
  - drivers/of/of_mdio.c:of_mdiobus_register_phy
```
**Symbols:**

```
c000000000c52dd0-c000000000c52ef4: of_get_phy_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_get_phy_id(struct device_node *device, u32 *phy_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/of_mdio.c (ffffffe000728eb4)
Location: drivers/of/of_mdio.c:30
Inline: False
Direct callers:
  - drivers/of/of_mdio.c:of_mdiobus_register_phy
```
**Symbols:**

```
ffffffe000728eb4-ffffffe000728f58: of_get_phy_id (STB_LOCAL)
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
