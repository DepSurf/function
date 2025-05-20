# Function: <code>__mdiobus_write</code>

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
int __mdiobus_write(struct mii_bus *bus, int addr, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81739860)
Location: drivers/net/phy/mdio_bus.c:566
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:__phy_modify
  - drivers/net/phy/phy-core.c:mmd_phy_indirect
  - drivers/net/phy/phy-core.c:mmd_phy_indirect
  - drivers/net/phy/phy-core.c:mmd_phy_indirect
```
**Symbols:**

```
ffffffff81739860-ffffffff8173992d: __mdiobus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __mdiobus_write(struct mii_bus *bus, int addr, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff8175d390)
Location: drivers/net/phy/mdio_bus.c:565
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:__phy_modify
  - drivers/net/phy/phy-core.c:mmd_phy_indirect
  - drivers/net/phy/phy-core.c:mmd_phy_indirect
  - drivers/net/phy/phy-core.c:mmd_phy_indirect
```
**Symbols:**

```
ffffffff8175d390-ffffffff8175d45d: __mdiobus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __mdiobus_write(struct mii_bus *bus, int addr, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff8179a920)
Location: drivers/net/phy/mdio_bus.c:582
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:__phy_modify_changed
  - drivers/net/phy/phy-core.c:__phy_write_mmd
  - drivers/net/phy/phy-core.c:mmd_phy_indirect
  - drivers/net/phy/phy-core.c:mmd_phy_indirect
  - drivers/net/phy/phy-core.c:mmd_phy_indirect
```
**Symbols:**

```
ffffffff8179a920-ffffffff8179a9e6: __mdiobus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __mdiobus_write(struct mii_bus *bus, int addr, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff817be3e0)
Location: drivers/net/phy/mdio_bus.c:574
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:__phy_modify_changed
  - drivers/net/phy/phy-core.c:__phy_write_mmd
  - drivers/net/phy/phy-core.c:mmd_phy_indirect
  - drivers/net/phy/phy-core.c:mmd_phy_indirect
  - drivers/net/phy/phy-core.c:mmd_phy_indirect
```
**Symbols:**

```
ffffffff817be3e0-ffffffff817be4a9: __mdiobus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __mdiobus_write(struct mii_bus *bus, int addr, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81886ae0)
Location: drivers/net/phy/mdio_bus.c:821
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:__phy_write_mmd
  - drivers/net/phy/phy-core.c:__phy_write_mmd
  - drivers/net/phy/phy-core.c:__phy_write_mmd
  - drivers/net/phy/phy-core.c:__phy_write_mmd
  - drivers/net/phy/phy-core.c:__phy_write_mmd
  - drivers/net/phy/mdio_bus.c:mdiobus_modify
  - drivers/net/phy/mdio_bus.c:mdiobus_write
  - drivers/net/phy/mdio_bus.c:mdiobus_write_nested
```
**Symbols:**

```
ffffffff81886ae0-ffffffff81886bd4: __mdiobus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __mdiobus_write(struct mii_bus *bus, int addr, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81894f00)
Location: drivers/net/phy/mdio_bus.c:765
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:__phy_write_mmd
  - drivers/net/phy/phy-core.c:__phy_write_mmd
  - drivers/net/phy/phy-core.c:__phy_write_mmd
  - drivers/net/phy/phy-core.c:__phy_write_mmd
  - drivers/net/phy/phy-core.c:__phy_write_mmd
  - drivers/net/phy/mdio_bus.c:mdiobus_modify
```
**Symbols:**

```
ffffffff81894f00-ffffffff81894fce: __mdiobus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __mdiobus_write(struct mii_bus *bus, int addr, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff818777d0)
Location: drivers/net/phy/mdio_bus.c:764
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:__phy_write_mmd
  - drivers/net/phy/phy-core.c:__phy_write_mmd
  - drivers/net/phy/phy-core.c:__phy_write_mmd
  - drivers/net/phy/phy-core.c:__phy_write_mmd
  - drivers/net/phy/phy-core.c:__phy_write_mmd
  - drivers/net/phy/mdio_bus.c:mdiobus_modify
```
**Symbols:**

```
ffffffff818777d0-ffffffff81877877: __mdiobus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __mdiobus_write(struct mii_bus *bus, int addr, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81908510)
Location: drivers/net/phy/mdio_bus.c:775
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:__phy_write_mmd
  - drivers/net/phy/phy-core.c:__phy_write_mmd
  - drivers/net/phy/phy-core.c:__phy_write_mmd
  - drivers/net/phy/phy-core.c:__phy_write_mmd
  - drivers/net/phy/phy-core.c:__phy_write_mmd
  - drivers/net/phy/mdio_bus.c:mdiobus_modify
```
**Symbols:**

```
ffffffff81908510-ffffffff819085ce: __mdiobus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __mdiobus_write(struct mii_bus *bus, int addr, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81a5bd70)
Location: drivers/net/phy/mdio_bus.c:782
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:__phy_write_mmd
  - drivers/net/phy/phy-core.c:__phy_write_mmd
  - drivers/net/phy/phy-core.c:__phy_write_mmd
  - drivers/net/phy/phy-core.c:__phy_write_mmd
  - drivers/net/phy/phy-core.c:__phy_write_mmd
  - drivers/net/phy/mdio_bus.c:mdiobus_modify_changed
  - drivers/net/phy/mdio_bus.c:mdiobus_modify
```
**Symbols:**

```
ffffffff81a5bd70-ffffffff81a5bf24: __mdiobus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __mdiobus_write(struct mii_bus *bus, int addr, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81be61a0)
Location: drivers/net/phy/mdio_bus.c:787
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:__phy_write_mmd
  - drivers/net/phy/phy-core.c:__phy_write_mmd
  - drivers/net/phy/phy-core.c:__phy_write_mmd
  - drivers/net/phy/phy-core.c:__phy_write_mmd
  - drivers/net/phy/phy-core.c:__phy_write_mmd
  - drivers/net/phy/mdio_bus.c:mdiobus_modify_changed
  - drivers/net/phy/mdio_bus.c:mdiobus_modify
```
**Symbols:**

```
ffffffff81be61a0-ffffffff81be6354: __mdiobus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __mdiobus_write(struct mii_bus *bus, int addr, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81c3e3a0)
Location: drivers/net/phy/mdio_bus.c:871
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:__phy_write_mmd
  - drivers/net/phy/phy-core.c:__phy_write_mmd
  - drivers/net/phy/phy-core.c:__phy_write_mmd
  - drivers/net/phy/phy-core.c:__phy_write_mmd
  - drivers/net/phy/mdio_bus.c:mdiobus_modify_changed
  - drivers/net/phy/mdio_bus.c:mdiobus_modify
```
**Symbols:**

```
ffffffff81c3e3a0-ffffffff81c3e562: __mdiobus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __mdiobus_write(struct mii_bus *bus, int addr, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81cf38f0)
Location: drivers/net/phy/mdio_bus.c:889
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:__phy_package_read_mmd
  - drivers/net/phy/phy-core.c:__phy_package_read_mmd
  - drivers/net/phy/phy-core.c:__phy_package_read_mmd
  - drivers/net/phy/mdio_bus.c:mdiobus_modify_changed
  - drivers/net/phy/mdio_bus.c:mdiobus_modify
```
**Symbols:**

```
ffffffff81cf38f0-ffffffff81cf3ab2: __mdiobus_write (STB_GLOBAL)
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
int __mdiobus_write(struct mii_bus *bus, int addr, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffff8000109d7a20)
Location: drivers/net/phy/mdio_bus.c:574
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:__phy_modify_changed
  - drivers/net/phy/phy-core.c:__phy_write_mmd
  - drivers/net/phy/phy-core.c:mmd_phy_indirect
  - drivers/net/phy/phy-core.c:mmd_phy_indirect
  - drivers/net/phy/phy-core.c:mmd_phy_indirect
```
**Symbols:**

```
ffff8000109d7a20-ffff8000109d7b38: __mdiobus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __mdiobus_write(struct mii_bus *bus, int addr, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (c0abee00)
Location: drivers/net/phy/mdio_bus.c:574
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:__phy_modify_changed
  - drivers/net/phy/phy-core.c:__phy_write_mmd
  - drivers/net/phy/phy-core.c:mmd_phy_indirect
  - drivers/net/phy/phy-core.c:mmd_phy_indirect
  - drivers/net/phy/phy-core.c:mmd_phy_indirect
```
**Symbols:**

```
c0abee00-c0abef2c: __mdiobus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __mdiobus_write(struct mii_bus *bus, int addr, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (c000000000a99190)
Location: drivers/net/phy/mdio_bus.c:574
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:__phy_modify_changed
  - drivers/net/phy/phy-core.c:__phy_write_mmd
  - drivers/net/phy/phy-core.c:mmd_phy_indirect
  - drivers/net/phy/phy-core.c:mmd_phy_indirect
  - drivers/net/phy/phy-core.c:mmd_phy_indirect
  - drivers/net/phy/mdio_bus.c:mdiobus_write
  - drivers/net/phy/mdio_bus.c:mdiobus_write_nested
```
**Symbols:**

```
c000000000a99190-c000000000a99308: __mdiobus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __mdiobus_write(struct mii_bus *bus, int addr, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffe000623398)
Location: drivers/net/phy/mdio_bus.c:574
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:__phy_modify_changed
  - drivers/net/phy/phy-core.c:__phy_write_mmd
  - drivers/net/phy/phy-core.c:mmd_phy_indirect
  - drivers/net/phy/phy-core.c:mmd_phy_indirect
  - drivers/net/phy/phy-core.c:mmd_phy_indirect
```
**Symbols:**

```
ffffffe000623398-ffffffe00062345e: __mdiobus_write (STB_GLOBAL)
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
int __mdiobus_write(struct mii_bus *bus, int addr, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81782eb0)
Location: drivers/net/phy/mdio_bus.c:574
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:__phy_modify_changed
  - drivers/net/phy/phy-core.c:__phy_write_mmd
  - drivers/net/phy/phy-core.c:mmd_phy_indirect
  - drivers/net/phy/phy-core.c:mmd_phy_indirect
  - drivers/net/phy/phy-core.c:mmd_phy_indirect
```
**Symbols:**

```
ffffffff81782eb0-ffffffff81782f79: __mdiobus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __mdiobus_write(struct mii_bus *bus, int addr, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81762c40)
Location: drivers/net/phy/mdio_bus.c:574
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:__phy_modify_changed
  - drivers/net/phy/phy-core.c:__phy_write_mmd
  - drivers/net/phy/phy-core.c:mmd_phy_indirect
  - drivers/net/phy/phy-core.c:mmd_phy_indirect
  - drivers/net/phy/phy-core.c:mmd_phy_indirect
```
**Symbols:**

```
ffffffff81762c40-ffffffff81762d09: __mdiobus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __mdiobus_write(struct mii_bus *bus, int addr, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff817b3260)
Location: drivers/net/phy/mdio_bus.c:574
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:__phy_modify_changed
  - drivers/net/phy/phy-core.c:__phy_write_mmd
  - drivers/net/phy/phy-core.c:mmd_phy_indirect
  - drivers/net/phy/phy-core.c:mmd_phy_indirect
  - drivers/net/phy/phy-core.c:mmd_phy_indirect
```
**Symbols:**

```
ffffffff817b3260-ffffffff817b3329: __mdiobus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __mdiobus_write(struct mii_bus *bus, int addr, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff817cd210)
Location: drivers/net/phy/mdio_bus.c:574
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:__phy_modify_changed
  - drivers/net/phy/phy-core.c:__phy_write_mmd
  - drivers/net/phy/phy-core.c:mmd_phy_indirect
  - drivers/net/phy/phy-core.c:mmd_phy_indirect
  - drivers/net/phy/phy-core.c:mmd_phy_indirect
```
**Symbols:**

```
ffffffff817cd210-ffffffff817cd2f1: __mdiobus_write (STB_GLOBAL)
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
