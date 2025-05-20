# Function: <code>fwnode_mdiobus_phy_device_register</code>

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
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fwnode_mdiobus_phy_device_register(struct mii_bus *mdio, struct phy_device *phy, struct fwnode_handle *child, u32 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/mdio/fwnode_mdio.c (0)
Location: drivers/net/mdio/fwnode_mdio.c:39
Inline: False
```
**Symbols:**

```
ffffffff81d10930-ffffffff81d10946: fwnode_mdiobus_phy_device_register.cold (STB_LOCAL)
ffffffff8190b7c0-ffffffff8190b93c: fwnode_mdiobus_phy_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fwnode_mdiobus_phy_device_register(struct mii_bus *mdio, struct phy_device *phy, struct fwnode_handle *child, u32 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/mdio/fwnode_mdio.c (0)
Location: drivers/net/mdio/fwnode_mdio.c:39
Inline: False
```
**Symbols:**

```
ffffffff81edb6e3-ffffffff81edb6fc: fwnode_mdiobus_phy_device_register.cold (STB_LOCAL)
ffffffff81a5f080-ffffffff81a5f255: fwnode_mdiobus_phy_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int fwnode_mdiobus_phy_device_register(struct mii_bus *mdio, struct phy_device *phy, struct fwnode_handle *child, u32 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/mdio/fwnode_mdio.c (0)
Location: drivers/net/mdio/fwnode_mdio.c:60
Inline: False
```
**Symbols:**

```
ffffffff8209d697-ffffffff8209d6b0: fwnode_mdiobus_phy_device_register.cold (STB_LOCAL)
ffffffff81bea410-ffffffff81bea5ef: fwnode_mdiobus_phy_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int fwnode_mdiobus_phy_device_register(struct mii_bus *mdio, struct phy_device *phy, struct fwnode_handle *child, u32 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/mdio/fwnode_mdio.c (0)
Location: drivers/net/mdio/fwnode_mdio.c:60
Inline: False
```
**Symbols:**

```
ffffffff8211e5a1-ffffffff8211e5ba: fwnode_mdiobus_phy_device_register.cold (STB_LOCAL)
ffffffff81c42840-ffffffff81c42a1f: fwnode_mdiobus_phy_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fwnode_mdiobus_phy_device_register(struct mii_bus *mdio, struct phy_device *phy, struct fwnode_handle *child, u32 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/mdio/fwnode_mdio.c (0)
Location: drivers/net/mdio/fwnode_mdio.c:61
Inline: False
```
**Symbols:**

```
ffffffff821ffbf4-ffffffff821ffc0d: fwnode_mdiobus_phy_device_register.cold (STB_LOCAL)
ffffffff81cf7f00-ffffffff81cf80df: fwnode_mdiobus_phy_device_register (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
