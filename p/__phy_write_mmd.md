# Function: <code>__phy_write_mmd</code>

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
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int __phy_write_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81796f40)
Location: drivers/net/phy/phy-core.c:393
Inline: True
Direct callers:
  - drivers/net/phy/phy-core.c:__phy_modify_mmd_changed
  - drivers/net/phy/phy-core.c:phy_write_mmd
```
**Symbols:**

```
ffffffff81796f40-ffffffff81796ff7: __phy_write_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __phy_write_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817ba9f0)
Location: drivers/net/phy/phy-core.c:432
Inline: True
Direct callers:
  - drivers/net/phy/phy-core.c:__phy_modify_mmd_changed
  - drivers/net/phy/phy-core.c:phy_write_mmd
```
**Symbols:**

```
ffffffff817ba9f0-ffffffff817baaa7: __phy_write_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __phy_write_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81881850)
Location: drivers/net/phy/phy-core.c:477
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_mmd
  - drivers/net/phy/phy-core.c:phy_modify_mmd_changed
  - drivers/net/phy/phy-core.c:phy_write_mmd
```
**Symbols:**

```
ffffffff81881850-ffffffff81881956: __phy_write_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __phy_write_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8188ff80)
Location: drivers/net/phy/phy-core.c:524
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_mmd
  - drivers/net/phy/phy-core.c:phy_modify_mmd_changed
  - drivers/net/phy/phy-core.c:phy_write_mmd
```
**Symbols:**

```
ffffffff8188ff80-ffffffff81890086: __phy_write_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __phy_write_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81872880)
Location: drivers/net/phy/phy-core.c:524
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_mmd
  - drivers/net/phy/phy-core.c:phy_modify_mmd_changed
  - drivers/net/phy/phy-core.c:phy_write_mmd
```
**Symbols:**

```
ffffffff81872880-ffffffff81872986: __phy_write_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __phy_write_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81902f90)
Location: drivers/net/phy/phy-core.c:525
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_mmd
  - drivers/net/phy/phy-core.c:phy_modify_mmd_changed
  - drivers/net/phy/phy-core.c:phy_write_mmd
```
**Symbols:**

```
ffffffff81902f90-ffffffff81903096: __phy_write_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __phy_write_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81a55a40)
Location: drivers/net/phy/phy-core.c:520
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_mmd
  - drivers/net/phy/phy-core.c:phy_modify_mmd_changed
  - drivers/net/phy/phy-core.c:phy_write_mmd
```
**Symbols:**

```
ffffffff81a55a40-ffffffff81a55b75: __phy_write_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __phy_write_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81bdf520)
Location: drivers/net/phy/phy-core.c:603
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_mmd
  - drivers/net/phy/phy-core.c:phy_modify_mmd_changed
  - drivers/net/phy/phy-core.c:phy_write_mmd
```
**Symbols:**

```
ffffffff81bdf520-ffffffff81bdf655: __phy_write_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __phy_write_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81c36e10)
Location: drivers/net/phy/phy-core.c:606
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_mmd
  - drivers/net/phy/phy-core.c:phy_modify_mmd_changed
  - drivers/net/phy/phy-core.c:phy_write_mmd
```
**Symbols:**

```
ffffffff81c36e10-ffffffff81c36f48: __phy_write_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __phy_write_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81cec8b0)
Location: drivers/net/phy/phy-core.c:618
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_mmd
  - drivers/net/phy/phy-core.c:phy_modify_mmd_changed
  - drivers/net/phy/phy-core.c:phy_write_mmd
```
**Symbols:**

```
ffffffff81cec8b0-ffffffff81cec94d: __phy_write_mmd (STB_GLOBAL)
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
int __phy_write_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffff8000109d3260)
Location: drivers/net/phy/phy-core.c:432
Inline: True
Direct callers:
  - drivers/net/phy/phy-core.c:__phy_modify_mmd_changed
  - drivers/net/phy/phy-core.c:phy_write_mmd
```
**Symbols:**

```
ffff8000109d3260-ffff8000109d3350: __phy_write_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __phy_write_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (c0abb1c8)
Location: drivers/net/phy/phy-core.c:432
Inline: True
Direct callers:
  - drivers/net/phy/phy-core.c:__phy_modify_mmd_changed
  - drivers/net/phy/phy-core.c:phy_write_mmd
```
**Symbols:**

```
c0abb1c8-c0abb284: __phy_write_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __phy_write_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (c000000000a93660)
Location: drivers/net/phy/phy-core.c:432
Inline: True
Direct callers:
  - drivers/net/phy/phy-core.c:__phy_modify_mmd_changed
  - drivers/net/phy/phy-core.c:phy_write_mmd
```
**Symbols:**

```
c000000000a93660-c000000000a93768: __phy_write_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __phy_write_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffe00061fa30)
Location: drivers/net/phy/phy-core.c:432
Inline: True
Direct callers:
  - drivers/net/phy/phy-core.c:__phy_modify_mmd_changed
  - drivers/net/phy/phy-core.c:phy_write_mmd
```
**Symbols:**

```
ffffffe00061fa30-ffffffe00061fb02: __phy_write_mmd (STB_GLOBAL)
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
int __phy_write_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8177f4c0)
Location: drivers/net/phy/phy-core.c:432
Inline: True
Direct callers:
  - drivers/net/phy/phy-core.c:__phy_modify_mmd_changed
  - drivers/net/phy/phy-core.c:phy_write_mmd
```
**Symbols:**

```
ffffffff8177f4c0-ffffffff8177f577: __phy_write_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __phy_write_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8175f260)
Location: drivers/net/phy/phy-core.c:432
Inline: True
Direct callers:
  - drivers/net/phy/phy-core.c:__phy_modify_mmd_changed
  - drivers/net/phy/phy-core.c:phy_write_mmd
```
**Symbols:**

```
ffffffff8175f260-ffffffff8175f317: __phy_write_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __phy_write_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817af870)
Location: drivers/net/phy/phy-core.c:432
Inline: True
Direct callers:
  - drivers/net/phy/phy-core.c:__phy_modify_mmd_changed
  - drivers/net/phy/phy-core.c:phy_write_mmd
```
**Symbols:**

```
ffffffff817af870-ffffffff817af927: __phy_write_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __phy_write_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817c9800)
Location: drivers/net/phy/phy-core.c:432
Inline: True
Direct callers:
  - drivers/net/phy/phy-core.c:__phy_modify_mmd_changed
  - drivers/net/phy/phy-core.c:phy_write_mmd
```
**Symbols:**

```
ffffffff817c9800-ffffffff817c98b7: __phy_write_mmd (STB_GLOBAL)
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
