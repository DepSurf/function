# Function: <code>__mdiobus_c45_write</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff818818c2)
Location: include/linux/mdio.h:347
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:__phy_write_mmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8188fff2)
Location: include/linux/mdio.h:348
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:__phy_write_mmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff818728f2)
Location: include/linux/mdio.h:361
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:__phy_write_mmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81903002)
Location: include/linux/mdio.h:364
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:__phy_write_mmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81a55abe)
Location: include/linux/mdio.h:472
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:__phy_write_mmd
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81bdf59e)
Location: include/linux/mdio.h:472
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:__phy_write_mmd
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __mdiobus_c45_write(struct mii_bus *bus, int addr, int devad, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81c3eb10)
Location: drivers/net/phy/mdio_bus.c:962
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:__phy_write_mmd
  - drivers/net/phy/mdio_bus.c:__mdiobus_c45_modify_changed
```
**Symbols:**

```
ffffffff81c3eb10-ffffffff81c3ecd3: __mdiobus_c45_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __mdiobus_c45_write(struct mii_bus *bus, int addr, int devad, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81cf35f0)
Location: drivers/net/phy/mdio_bus.c:980
Inline: False
Direct callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_c45_modify_changed
```
**Symbols:**

```
ffffffff81cf35f0-ffffffff81cf37b3: __mdiobus_c45_write (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
