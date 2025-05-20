# Function: <code>of_mdiobus_register</code>

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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int of_mdiobus_register(struct mii_bus *mdio, struct device_node *np);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/of/of_mdio.c (ffff800010b75f20)
Location: drivers/of/of_mdio.c:199
Inline: True
Direct callers:
  - drivers/net/phy/mdio-mux.c:mdio_mux_init
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_probe
```
**Symbols:**

```
ffff800010b75f20-ffff800010b76200: of_mdiobus_register.part.0 (STB_LOCAL)
ffff800010b76200-ffff800010b762bc: of_mdiobus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int of_mdiobus_register(struct mii_bus *mdio, struct device_node *np);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/of/of_mdio.c (c0c582d4)
Location: drivers/of/of_mdio.c:199
Inline: True
Direct callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_probe
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_probe
```
**Symbols:**

```
c0c582d4-c0c585c8: of_mdiobus_register.part.0 (STB_LOCAL)
c0c585c8-c0c5867c: of_mdiobus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int of_mdiobus_register(struct mii_bus *mdio, struct device_node *np);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/of/of_mdio.c (c000000000c538d0)
Location: drivers/of/of_mdio.c:199
Inline: True
```
**Symbols:**

```
c000000000c538d0-c000000000c53cec: of_mdiobus_register.part.0 (STB_LOCAL)
c000000000c53cf0-c000000000c53dec: of_mdiobus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int of_mdiobus_register(struct mii_bus *mdio, struct device_node *np);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/of/of_mdio.c (ffffffe000729482)
Location: drivers/of/of_mdio.c:199
Inline: True
```
**Symbols:**

```
ffffffe000729482-ffffffe0007296dc: of_mdiobus_register.part.0 (STB_LOCAL)
ffffffe0007296dc-ffffffe000729786: of_mdiobus_register (STB_GLOBAL)
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
