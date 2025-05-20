# Function: <code>__phy_modify_mmd_changed</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __phy_modify_mmd_changed(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81797000)
Location: drivers/net/phy/phy-core.c:557
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_mmd
  - drivers/net/phy/phy-core.c:phy_modify_mmd_changed
```
**Symbols:**

```
ffffffff81797000-ffffffff8179706e: __phy_modify_mmd_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __phy_modify_mmd_changed(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817baab0)
Location: drivers/net/phy/phy-core.c:596
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_mmd
  - drivers/net/phy/phy-core.c:phy_modify_mmd_changed
```
**Symbols:**

```
ffffffff817baab0-ffffffff817bab1e: __phy_modify_mmd_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __phy_modify_mmd_changed(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81882508)
Location: drivers/net/phy/phy-core.c:608
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify_mmd
  - drivers/net/phy/phy-core.c:phy_modify_mmd_changed
```
**Symbols:**

```
ffffffff81882030-ffffffff8188209e: __phy_modify_mmd_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __phy_modify_mmd_changed(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81890c38)
Location: drivers/net/phy/phy-core.c:655
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify_mmd
  - drivers/net/phy/phy-core.c:phy_modify_mmd_changed
```
**Symbols:**

```
ffffffff81890760-ffffffff818907ce: __phy_modify_mmd_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __phy_modify_mmd_changed(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81873527)
Location: drivers/net/phy/phy-core.c:655
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify_mmd
  - drivers/net/phy/phy-core.c:phy_modify_mmd_changed
```
**Symbols:**

```
ffffffff81873060-ffffffff818730ce: __phy_modify_mmd_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __phy_modify_mmd_changed(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81903cf7)
Location: drivers/net/phy/phy-core.c:656
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify_mmd
  - drivers/net/phy/phy-core.c:phy_modify_mmd_changed
```
**Symbols:**

```
ffffffff81903830-ffffffff8190389e: __phy_modify_mmd_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int __phy_modify_mmd_changed(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81a56747)
Location: drivers/net/phy/phy-core.c:651
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify_mmd
  - drivers/net/phy/phy-core.c:phy_modify_mmd_changed
```
**Symbols:**

```
ffffffff81a56210-ffffffff81a5629c: __phy_modify_mmd_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int __phy_modify_mmd_changed(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81be0447)
Location: drivers/net/phy/phy-core.c:734
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify_mmd
  - drivers/net/phy/phy-core.c:phy_modify_mmd_changed
```
**Symbols:**

```
ffffffff81bdfe90-ffffffff81bdff1c: __phy_modify_mmd_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int __phy_modify_mmd_changed(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81c37d57)
Location: drivers/net/phy/phy-core.c:737
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify_mmd
  - drivers/net/phy/phy-core.c:phy_modify_mmd_changed
```
**Symbols:**

```
ffffffff81c37800-ffffffff81c3788c: __phy_modify_mmd_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int __phy_modify_mmd_changed(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81ced0e7)
Location: drivers/net/phy/phy-core.c:875
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify_mmd
  - drivers/net/phy/phy-core.c:phy_modify_mmd_changed
```
**Symbols:**

```
ffffffff81cec9e0-ffffffff81ceca6c: __phy_modify_mmd_changed (STB_GLOBAL)
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
int __phy_modify_mmd_changed(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffff8000109d3350)
Location: drivers/net/phy/phy-core.c:596
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_mmd
  - drivers/net/phy/phy-core.c:phy_modify_mmd_changed
```
**Symbols:**

```
ffff8000109d3350-ffff8000109d33e8: __phy_modify_mmd_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __phy_modify_mmd_changed(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (c0abb284)
Location: drivers/net/phy/phy-core.c:596
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_mmd
  - drivers/net/phy/phy-core.c:phy_modify_mmd_changed
```
**Symbols:**

```
c0abb284-c0abb2f0: __phy_modify_mmd_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __phy_modify_mmd_changed(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (c000000000a93770)
Location: drivers/net/phy/phy-core.c:596
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_mmd
  - drivers/net/phy/phy-core.c:phy_modify_mmd_changed
```
**Symbols:**

```
c000000000a93770-c000000000a93848: __phy_modify_mmd_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __phy_modify_mmd_changed(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffe00061fb02)
Location: drivers/net/phy/phy-core.c:596
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_mmd
  - drivers/net/phy/phy-core.c:phy_modify_mmd_changed
```
**Symbols:**

```
ffffffe00061fb02-ffffffe00061fb78: __phy_modify_mmd_changed (STB_GLOBAL)
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
int __phy_modify_mmd_changed(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8177f580)
Location: drivers/net/phy/phy-core.c:596
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_mmd
  - drivers/net/phy/phy-core.c:phy_modify_mmd_changed
```
**Symbols:**

```
ffffffff8177f580-ffffffff8177f5ee: __phy_modify_mmd_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __phy_modify_mmd_changed(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8175f320)
Location: drivers/net/phy/phy-core.c:596
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_mmd
  - drivers/net/phy/phy-core.c:phy_modify_mmd_changed
```
**Symbols:**

```
ffffffff8175f320-ffffffff8175f38e: __phy_modify_mmd_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __phy_modify_mmd_changed(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817af930)
Location: drivers/net/phy/phy-core.c:596
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_mmd
  - drivers/net/phy/phy-core.c:phy_modify_mmd_changed
```
**Symbols:**

```
ffffffff817af930-ffffffff817af99e: __phy_modify_mmd_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __phy_modify_mmd_changed(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817c98c0)
Location: drivers/net/phy/phy-core.c:596
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_mmd
  - drivers/net/phy/phy-core.c:phy_modify_mmd_changed
```
**Symbols:**

```
ffffffff817c98c0-ffffffff817c992e: __phy_modify_mmd_changed (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
