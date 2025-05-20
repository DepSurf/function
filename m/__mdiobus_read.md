# Function: <code>__mdiobus_read</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __mdiobus_read(struct mii_bus *bus, int addr, u32 regnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81739c90)
Location: drivers/net/phy/mdio_bus.c:541
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_read_paged
  - drivers/net/phy/phy-core.c:__phy_modify
```
**Symbols:**

```
ffffffff81739c90-ffffffff81739d5f: __mdiobus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __mdiobus_read(struct mii_bus *bus, int addr, u32 regnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff8175cf80)
Location: drivers/net/phy/mdio_bus.c:540
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_read_paged
  - drivers/net/phy/phy-core.c:__phy_modify
```
**Symbols:**

```
ffffffff8175cf80-ffffffff8175d04f: __mdiobus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __mdiobus_read(struct mii_bus *bus, int addr, u32 regnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff8179a400)
Location: drivers/net/phy/mdio_bus.c:557
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_read_paged
  - drivers/net/phy/phy-core.c:__phy_modify_changed
  - drivers/net/phy/phy-core.c:__phy_read_mmd
```
**Symbols:**

```
ffffffff8179a400-ffffffff8179a4c6: __mdiobus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __mdiobus_read(struct mii_bus *bus, int addr, u32 regnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff817bdf00)
Location: drivers/net/phy/mdio_bus.c:549
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_read_paged
  - drivers/net/phy/phy-core.c:__phy_modify_changed
  - drivers/net/phy/phy-core.c:__phy_read_mmd
```
**Symbols:**

```
ffffffff817bdf00-ffffffff817bdfc9: __mdiobus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __mdiobus_read(struct mii_bus *bus, int addr, u32 regnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81886ce0)
Location: drivers/net/phy/mdio_bus.c:795
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_read_paged
  - drivers/net/phy/mdio_bus.c:mdiobus_modify
  - drivers/net/phy/mdio_bus.c:mdiobus_read
  - drivers/net/phy/mdio_bus.c:mdiobus_read_nested
```
**Symbols:**

```
ffffffff81886ce0-ffffffff81886dcf: __mdiobus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __mdiobus_read(struct mii_bus *bus, int addr, u32 regnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81895090)
Location: drivers/net/phy/mdio_bus.c:739
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_read_paged
  - drivers/net/phy/mdio_bus.c:mdiobus_modify
```
**Symbols:**

```
ffffffff81895090-ffffffff81895162: __mdiobus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __mdiobus_read(struct mii_bus *bus, int addr, u32 regnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81877c70)
Location: drivers/net/phy/mdio_bus.c:738
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_read_paged
  - drivers/net/phy/mdio_bus.c:mdiobus_modify
```
**Symbols:**

```
ffffffff81877c70-ffffffff81877d1e: __mdiobus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __mdiobus_read(struct mii_bus *bus, int addr, u32 regnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81908a20)
Location: drivers/net/phy/mdio_bus.c:749
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_read_paged
  - drivers/net/phy/mdio_bus.c:mdiobus_modify
```
**Symbols:**

```
ffffffff81908a20-ffffffff81908ae9: __mdiobus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __mdiobus_read(struct mii_bus *bus, int addr, u32 regnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81a5b490)
Location: drivers/net/phy/mdio_bus.c:756
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_read_paged
  - drivers/net/phy/mdio_bus.c:mdiobus_modify_changed
  - drivers/net/phy/mdio_bus.c:mdiobus_modify
```
**Symbols:**

```
ffffffff81a5b490-ffffffff81a5b61e: __mdiobus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __mdiobus_read(struct mii_bus *bus, int addr, u32 regnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81be6810)
Location: drivers/net/phy/mdio_bus.c:761
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_read_paged
  - drivers/net/phy/mdio_bus.c:mdiobus_modify_changed
  - drivers/net/phy/mdio_bus.c:mdiobus_modify
```
**Symbols:**

```
ffffffff81be6810-ffffffff81be699e: __mdiobus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __mdiobus_read(struct mii_bus *bus, int addr, u32 regnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81c3e660)
Location: drivers/net/phy/mdio_bus.c:842
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_read_paged
  - drivers/net/phy/mdio_bus.c:mdiobus_modify_changed
  - drivers/net/phy/mdio_bus.c:mdiobus_modify
```
**Symbols:**

```
ffffffff81c3e660-ffffffff81c3e804: __mdiobus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __mdiobus_read(struct mii_bus *bus, int addr, u32 regnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81cf3bb0)
Location: drivers/net/phy/mdio_bus.c:860
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_read_paged
  - drivers/net/phy/phy-core.c:__phy_package_read_mmd
  - drivers/net/phy/mdio_bus.c:mdiobus_modify_changed
  - drivers/net/phy/mdio_bus.c:mdiobus_modify
```
**Symbols:**

```
ffffffff81cf3bb0-ffffffff81cf3d54: __mdiobus_read (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __mdiobus_read(struct mii_bus *bus, int addr, u32 regnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffff8000109d7820)
Location: drivers/net/phy/mdio_bus.c:549
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_read_paged
  - drivers/net/phy/phy-core.c:__phy_modify_changed
  - drivers/net/phy/phy-core.c:__phy_read_mmd
```
**Symbols:**

```
ffff8000109d7820-ffff8000109d7930: __mdiobus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __mdiobus_read(struct mii_bus *bus, int addr, u32 regnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (c0abf290)
Location: drivers/net/phy/mdio_bus.c:549
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_read_paged
  - drivers/net/phy/phy-core.c:__phy_modify_changed
  - drivers/net/phy/phy-core.c:__phy_read_mmd
```
**Symbols:**

```
c0abf290-c0abf3b8: __mdiobus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __mdiobus_read(struct mii_bus *bus, int addr, u32 regnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (c000000000a99790)
Location: drivers/net/phy/mdio_bus.c:549
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_read_paged
  - drivers/net/phy/phy-core.c:__phy_modify_changed
  - drivers/net/phy/phy-core.c:__phy_read_mmd
  - drivers/net/phy/mdio_bus.c:mdiobus_read
  - drivers/net/phy/mdio_bus.c:mdiobus_read_nested
```
**Symbols:**

```
c000000000a99790-c000000000a998f8: __mdiobus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __mdiobus_read(struct mii_bus *bus, int addr, u32 regnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffe000623842)
Location: drivers/net/phy/mdio_bus.c:549
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_read_paged
  - drivers/net/phy/phy-core.c:__phy_modify_changed
  - drivers/net/phy/phy-core.c:__phy_read_mmd
```
**Symbols:**

```
ffffffe000623842-ffffffe00062390c: __mdiobus_read (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int __mdiobus_read(struct mii_bus *bus, int addr, u32 regnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff817829d0)
Location: drivers/net/phy/mdio_bus.c:549
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_read_paged
  - drivers/net/phy/phy-core.c:__phy_modify_changed
  - drivers/net/phy/phy-core.c:__phy_read_mmd
```
**Symbols:**

```
ffffffff817829d0-ffffffff81782a99: __mdiobus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __mdiobus_read(struct mii_bus *bus, int addr, u32 regnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81762760)
Location: drivers/net/phy/mdio_bus.c:549
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_read_paged
  - drivers/net/phy/phy-core.c:__phy_modify_changed
  - drivers/net/phy/phy-core.c:__phy_read_mmd
```
**Symbols:**

```
ffffffff81762760-ffffffff81762829: __mdiobus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __mdiobus_read(struct mii_bus *bus, int addr, u32 regnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff817b2d80)
Location: drivers/net/phy/mdio_bus.c:549
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_read_paged
  - drivers/net/phy/phy-core.c:__phy_modify_changed
  - drivers/net/phy/phy-core.c:__phy_read_mmd
```
**Symbols:**

```
ffffffff817b2d80-ffffffff817b2e49: __mdiobus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __mdiobus_read(struct mii_bus *bus, int addr, u32 regnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff817ccd10)
Location: drivers/net/phy/mdio_bus.c:549
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_read_paged
  - drivers/net/phy/phy-core.c:__phy_modify_changed
  - drivers/net/phy/phy-core.c:__phy_read_mmd
```
**Symbols:**

```
ffffffff817ccd10-ffffffff817ccdf5: __mdiobus_read (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
