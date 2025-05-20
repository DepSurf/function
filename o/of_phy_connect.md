# Function: <code>of_phy_connect</code>

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
struct phy_device *of_phy_connect(struct net_device *dev, struct device_node *phy_np, void (*hndlr)(struct net_device *), u32 flags, phy_interface_t iface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/of_mdio.c (ffff800010b75b30)
Location: drivers/of/of_mdio.c:323
Inline: False
Direct callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mii_probe
  - drivers/of/of_mdio.c:of_phy_get_and_connect
```
**Symbols:**

```
ffff800010b75b30-ffff800010b75bcc: of_phy_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct phy_device *of_phy_connect(struct net_device *dev, struct device_node *phy_np, void (*hndlr)(struct net_device *), u32 flags, phy_interface_t iface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/of_mdio.c (c0c57f14)
Location: drivers/of/of_mdio.c:323
Inline: False
Direct callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mii_probe
  - drivers/net/ethernet/ti/cpsw.c:cpsw_slave_open
  - drivers/of/of_mdio.c:of_phy_get_and_connect
```
**Symbols:**

```
c0c57f14-c0c57f84: of_phy_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct phy_device *of_phy_connect(struct net_device *dev, struct device_node *phy_np, void (*hndlr)(struct net_device *), u32 flags, phy_interface_t iface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/of_mdio.c (c000000000c53240)
Location: drivers/of/of_mdio.c:323
Inline: False
Direct callers:
  - drivers/of/of_mdio.c:of_phy_get_and_connect
```
**Symbols:**

```
c000000000c53240-c000000000c5331c: of_phy_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct phy_device *of_phy_connect(struct net_device *dev, struct device_node *phy_np, void (*hndlr)(struct net_device *), u32 flags, phy_interface_t iface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/of_mdio.c (ffffffe000729156)
Location: drivers/of/of_mdio.c:323
Inline: False
Direct callers:
  - drivers/of/of_mdio.c:of_phy_get_and_connect
```
**Symbols:**

```
ffffffe000729156-ffffffe0007291c6: of_phy_connect (STB_GLOBAL)
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
