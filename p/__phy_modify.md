# Function: <code>__phy_modify</code>

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
int __phy_modify(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81736a60)
Location: drivers/net/phy/phy-core.c:337
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_modify
```
**Symbols:**

```
ffffffff81736a60-ffffffff81736ac9: __phy_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __phy_modify(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81759c00)
Location: drivers/net/phy/phy-core.c:508
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_modify
```
**Symbols:**

```
ffffffff81759c00-ffffffff81759c69: __phy_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int __phy_modify(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81796d01)
Location: drivers/net/phy/phy-core.c:511
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_modify
```
**Symbols:**

```
ffffffff81796a00-ffffffff81796a20: __phy_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __phy_modify(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817ba5fb)
Location: drivers/net/phy/phy-core.c:550
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify
```
**Symbols:**

```
ffffffff817ba490-ffffffff817ba4b0: __phy_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __phy_modify(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81881aae)
Location: drivers/net/phy/phy-core.c:562
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify
```
**Symbols:**

```
ffffffff81881a40-ffffffff81881a77: __phy_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __phy_modify(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff818901de)
Location: drivers/net/phy/phy-core.c:609
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify
```
**Symbols:**

```
ffffffff81890170-ffffffff818901a7: __phy_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __phy_modify(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81872ade)
Location: drivers/net/phy/phy-core.c:609
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify
```
**Symbols:**

```
ffffffff81872a70-ffffffff81872aa4: __phy_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __phy_modify(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff819031ee)
Location: drivers/net/phy/phy-core.c:610
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify
```
**Symbols:**

```
ffffffff81903180-ffffffff819031b4: __phy_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int __phy_modify(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81a55cee)
Location: drivers/net/phy/phy-core.c:605
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify
```
**Symbols:**

```
ffffffff81a55c70-ffffffff81a55cb1: __phy_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int __phy_modify(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81bdf80e)
Location: drivers/net/phy/phy-core.c:688
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify
```
**Symbols:**

```
ffffffff81bdf780-ffffffff81bdf7c1: __phy_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int __phy_modify(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81c370fe)
Location: drivers/net/phy/phy-core.c:691
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify
```
**Symbols:**

```
ffffffff81c37070-ffffffff81c370b1: __phy_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int __phy_modify(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81cebeae)
Location: drivers/net/phy/phy-core.c:829
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify
```
**Symbols:**

```
ffffffff81cebe20-ffffffff81cebe61: __phy_modify (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int __phy_modify(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffff8000109d2d5c)
Location: drivers/net/phy/phy-core.c:550
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify
```
**Symbols:**

```
ffff8000109d2ba0-ffff8000109d2bf4: __phy_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __phy_modify(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (c0abadbc)
Location: drivers/net/phy/phy-core.c:550
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify
```
**Symbols:**

```
c0abac60-c0abac80: __phy_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __phy_modify(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (c000000000a93050)
Location: drivers/net/phy/phy-core.c:550
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify
```
**Symbols:**

```
c000000000a92df0-c000000000a92e30: __phy_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __phy_modify(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffe00061f5ea)
Location: drivers/net/phy/phy-core.c:550
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify
```
**Symbols:**

```
ffffffe00061f452-ffffffe00061f4a0: __phy_modify (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int __phy_modify(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8177f0cb)
Location: drivers/net/phy/phy-core.c:550
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify
```
**Symbols:**

```
ffffffff8177ef60-ffffffff8177ef80: __phy_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __phy_modify(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8175ee6b)
Location: drivers/net/phy/phy-core.c:550
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify
```
**Symbols:**

```
ffffffff8175ed00-ffffffff8175ed20: __phy_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __phy_modify(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817af47b)
Location: drivers/net/phy/phy-core.c:550
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify
```
**Symbols:**

```
ffffffff817af310-ffffffff817af330: __phy_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __phy_modify(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817c940b)
Location: drivers/net/phy/phy-core.c:550
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify
```
**Symbols:**

```
ffffffff817c92a0-ffffffff817c92c0: __phy_modify (STB_GLOBAL)
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
