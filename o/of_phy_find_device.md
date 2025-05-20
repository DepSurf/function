# Function: <code>of_phy_find_device</code>

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
struct phy_device *of_phy_find_device(struct device_node *phy_np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/of_mdio.c (ffff800010b75ac0)
Location: drivers/of/of_mdio.c:291
Inline: False
Direct callers:
  - drivers/net/ethernet/freescale/fman/mac.c:mac_probe
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_config
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_config
  - drivers/of/of_mdio.c:of_phy_deregister_fixed_link
  - drivers/of/of_mdio.c:of_phy_attach
  - drivers/of/of_mdio.c:of_phy_connect
```
**Symbols:**

```
ffff800010b75ac0-ffff800010b75b30: of_phy_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct phy_device *of_phy_find_device(struct device_node *phy_np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/of_mdio.c (c0c57ea8)
Location: drivers/of/of_mdio.c:291
Inline: False
Direct callers:
  - drivers/of/of_mdio.c:of_phy_deregister_fixed_link
  - drivers/of/of_mdio.c:of_phy_attach
  - drivers/of/of_mdio.c:of_phy_connect
```
**Symbols:**

```
c0c57ea8-c0c57f14: of_phy_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct phy_device *of_phy_find_device(struct device_node *phy_np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/of_mdio.c (c000000000c531a0)
Location: drivers/of/of_mdio.c:291
Inline: False
Direct callers:
  - drivers/of/of_mdio.c:of_phy_deregister_fixed_link
  - drivers/of/of_mdio.c:of_phy_attach
  - drivers/of/of_mdio.c:of_phy_connect
```
**Symbols:**

```
c000000000c531a0-c000000000c5323c: of_phy_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct phy_device *of_phy_find_device(struct device_node *phy_np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/of_mdio.c (ffffffe0007290f4)
Location: drivers/of/of_mdio.c:291
Inline: False
Direct callers:
  - drivers/of/of_mdio.c:of_phy_deregister_fixed_link
  - drivers/of/of_mdio.c:of_phy_attach
  - drivers/of/of_mdio.c:of_phy_connect
```
**Symbols:**

```
ffffffe0007290f4-ffffffe000729156: of_phy_find_device (STB_GLOBAL)
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
