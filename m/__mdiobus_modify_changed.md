# Function: <code>__mdiobus_modify_changed</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __mdiobus_modify_changed(struct mii_bus *bus, int addr, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81887299)
Location: drivers/net/phy/mdio_bus.c:849
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_modify
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_modify
  - drivers/net/phy/phy-core.c:phy_modify_changed
```
**Symbols:**

```
ffffffff81886dd0-ffffffff81886e3e: __mdiobus_modify_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __mdiobus_modify_changed(struct mii_bus *bus, int addr, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff818952b4)
Location: drivers/net/phy/mdio_bus.c:793
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_modify
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_modify
  - drivers/net/phy/phy-core.c:phy_modify_changed
```
**Symbols:**

```
ffffffff81895170-ffffffff818951de: __mdiobus_modify_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __mdiobus_modify_changed(struct mii_bus *bus, int addr, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81877e64)
Location: drivers/net/phy/mdio_bus.c:792
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_modify
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_modify
  - drivers/net/phy/phy-core.c:phy_modify_changed
```
**Symbols:**

```
ffffffff81877d20-ffffffff81877d8e: __mdiobus_modify_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __mdiobus_modify_changed(struct mii_bus *bus, int addr, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81908c34)
Location: drivers/net/phy/mdio_bus.c:803
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_modify
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_modify
  - drivers/net/phy/phy-core.c:phy_modify_changed
```
**Symbols:**

```
ffffffff81908af0-ffffffff81908b5e: __mdiobus_modify_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int __mdiobus_modify_changed(struct mii_bus *bus, int addr, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81a5c0b4)
Location: drivers/net/phy/mdio_bus.c:810
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_modify_changed
  - drivers/net/phy/mdio_bus.c:mdiobus_modify
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_modify
  - drivers/net/phy/phy-core.c:phy_modify_changed
```
**Symbols:**

```
ffffffff81a5bf30-ffffffff81a5bfbc: __mdiobus_modify_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int __mdiobus_modify_changed(struct mii_bus *bus, int addr, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81be6b64)
Location: drivers/net/phy/mdio_bus.c:815
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_modify_changed
  - drivers/net/phy/mdio_bus.c:mdiobus_modify
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_modify
  - drivers/net/phy/phy-core.c:phy_modify_changed
```
**Symbols:**

```
ffffffff81be69b0-ffffffff81be6a3c: __mdiobus_modify_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int __mdiobus_modify_changed(struct mii_bus *bus, int addr, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81c3e9d4)
Location: drivers/net/phy/mdio_bus.c:902
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_modify_changed
  - drivers/net/phy/mdio_bus.c:mdiobus_modify
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_modify
  - drivers/net/phy/phy-core.c:phy_modify_changed
```
**Symbols:**

```
ffffffff81c3e820-ffffffff81c3e8ac: __mdiobus_modify_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int __mdiobus_modify_changed(struct mii_bus *bus, int addr, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81cf4474)
Location: drivers/net/phy/mdio_bus.c:920
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_modify_changed
  - drivers/net/phy/mdio_bus.c:mdiobus_modify
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_modify
  - drivers/net/phy/phy-core.c:phy_modify_changed
```
**Symbols:**

```
ffffffff81cf3d70-ffffffff81cf3dfc: __mdiobus_modify_changed (STB_GLOBAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
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
