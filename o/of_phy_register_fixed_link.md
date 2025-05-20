# Function: <code>of_phy_register_fixed_link</code>

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
int of_phy_register_fixed_link(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/of_mdio.c (ffff800010b75c58)
Location: drivers/of/of_mdio.c:453
Inline: False
Direct callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fman/mac.c:mac_probe
  - drivers/of/of_mdio.c:of_phy_get_and_connect
```
**Symbols:**

```
ffff800010b75c58-ffff800010b75e00: of_phy_register_fixed_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_phy_register_fixed_link(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/of_mdio.c (c0c57ff0)
Location: drivers/of/of_mdio.c:453
Inline: False
Direct callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe_dt
  - drivers/of/of_mdio.c:of_phy_get_and_connect
```
**Symbols:**

```
c0c57ff0-c0c581bc: of_phy_register_fixed_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_phy_register_fixed_link(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/of_mdio.c (c000000000c533f0)
Location: drivers/of/of_mdio.c:453
Inline: False
Direct callers:
  - drivers/of/of_mdio.c:of_phy_get_and_connect
```
**Symbols:**

```
c000000000c533f0-c000000000c5375c: of_phy_register_fixed_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_phy_register_fixed_link(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/of_mdio.c (ffffffe00072922c)
Location: drivers/of/of_mdio.c:453
Inline: False
Direct callers:
  - drivers/of/of_mdio.c:of_phy_get_and_connect
```
**Symbols:**

```
ffffffe00072922c-ffffffe000729398: of_phy_register_fixed_link (STB_GLOBAL)
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
