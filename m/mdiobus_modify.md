# Function: <code>mdiobus_modify</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
int mdiobus_modify(struct mii_bus *bus, int addr, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81887250)
Location: drivers/net/phy/mdio_bus.c:985
Inline: False
```
**Symbols:**

```
ffffffff81887250-ffffffff8188730e: mdiobus_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mdiobus_modify(struct mii_bus *bus, int addr, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81895280)
Location: drivers/net/phy/mdio_bus.c:917
Inline: False
```
**Symbols:**

```
ffffffff81895280-ffffffff8189531e: mdiobus_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mdiobus_modify(struct mii_bus *bus, int addr, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81877e30)
Location: drivers/net/phy/mdio_bus.c:916
Inline: False
```
**Symbols:**

```
ffffffff81877e30-ffffffff81877ec2: mdiobus_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mdiobus_modify(struct mii_bus *bus, int addr, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81908c00)
Location: drivers/net/phy/mdio_bus.c:927
Inline: False
```
**Symbols:**

```
ffffffff81908c00-ffffffff81908c92: mdiobus_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mdiobus_modify(struct mii_bus *bus, int addr, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81a5c130)
Location: drivers/net/phy/mdio_bus.c:934
Inline: False
```
**Symbols:**

```
ffffffff81a5c130-ffffffff81a5c1ca: mdiobus_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mdiobus_modify(struct mii_bus *bus, int addr, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81be6bf0)
Location: drivers/net/phy/mdio_bus.c:939
Inline: False
```
**Symbols:**

```
ffffffff81be6bf0-ffffffff81be6c8a: mdiobus_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mdiobus_modify(struct mii_bus *bus, int addr, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81c3ea60)
Location: drivers/net/phy/mdio_bus.c:1222
Inline: False
```
**Symbols:**

```
ffffffff81c3ea60-ffffffff81c3eaff: mdiobus_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mdiobus_modify(struct mii_bus *bus, int addr, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81cf4500)
Location: drivers/net/phy/mdio_bus.c:1260
Inline: False
```
**Symbols:**

```
ffffffff81cf4500-ffffffff81cf459f: mdiobus_modify (STB_GLOBAL)
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
