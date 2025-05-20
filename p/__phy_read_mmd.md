# Function: <code>__phy_read_mmd</code>

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
int __phy_read_mmd(struct phy_device *phydev, int devad, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81796e40)
Location: drivers/net/phy/phy-core.c:336
Inline: True
Direct callers:
  - drivers/net/phy/phy-core.c:__phy_modify_mmd_changed
  - drivers/net/phy/phy-core.c:phy_read_mmd
```
**Symbols:**

```
ffffffff81796e40-ffffffff81796ee0: __phy_read_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __phy_read_mmd(struct phy_device *phydev, int devad, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817ba8f0)
Location: drivers/net/phy/phy-core.c:375
Inline: True
Direct callers:
  - drivers/net/phy/phy-core.c:__phy_modify_mmd_changed
  - drivers/net/phy/phy-core.c:phy_read_mmd
```
**Symbols:**

```
ffffffff817ba8f0-ffffffff817ba990: __phy_read_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __phy_read_mmd(struct phy_device *phydev, int devad, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81881f30)
Location: drivers/net/phy/phy-core.c:421
Inline: True
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_mmd
  - drivers/net/phy/phy-core.c:phy_modify_mmd_changed
  - drivers/net/phy/phy-core.c:phy_read_mmd
```
**Symbols:**

```
ffffffff81881f30-ffffffff81882029: __phy_read_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __phy_read_mmd(struct phy_device *phydev, int devad, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81890660)
Location: drivers/net/phy/phy-core.c:468
Inline: True
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_mmd
  - drivers/net/phy/phy-core.c:phy_modify_mmd_changed
  - drivers/net/phy/phy-core.c:phy_read_mmd
```
**Symbols:**

```
ffffffff81890660-ffffffff81890759: __phy_read_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __phy_read_mmd(struct phy_device *phydev, int devad, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81872f60)
Location: drivers/net/phy/phy-core.c:468
Inline: True
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_mmd
  - drivers/net/phy/phy-core.c:phy_modify_mmd_changed
  - drivers/net/phy/phy-core.c:phy_read_mmd
```
**Symbols:**

```
ffffffff81872f60-ffffffff81873059: __phy_read_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __phy_read_mmd(struct phy_device *phydev, int devad, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81903730)
Location: drivers/net/phy/phy-core.c:469
Inline: True
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_mmd
  - drivers/net/phy/phy-core.c:phy_modify_mmd_changed
  - drivers/net/phy/phy-core.c:phy_read_mmd
```
**Symbols:**

```
ffffffff81903730-ffffffff81903829: __phy_read_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int __phy_read_mmd(struct phy_device *phydev, int devad, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81a560f0)
Location: drivers/net/phy/phy-core.c:464
Inline: True
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_mmd
  - drivers/net/phy/phy-core.c:phy_modify_mmd_changed
  - drivers/net/phy/phy-core.c:phy_read_mmd
```
**Symbols:**

```
ffffffff81a560f0-ffffffff81a5620e: __phy_read_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int __phy_read_mmd(struct phy_device *phydev, int devad, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81bdfd60)
Location: drivers/net/phy/phy-core.c:547
Inline: True
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_mmd
  - drivers/net/phy/phy-core.c:phy_modify_mmd_changed
  - drivers/net/phy/phy-core.c:phy_read_mmd
```
**Symbols:**

```
ffffffff81bdfd60-ffffffff81bdfe7e: __phy_read_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int __phy_read_mmd(struct phy_device *phydev, int devad, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81c37650)
Location: drivers/net/phy/phy-core.c:550
Inline: True
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_mmd
  - drivers/net/phy/phy-core.c:phy_modify_mmd_changed
  - drivers/net/phy/phy-core.c:phy_read_mmd
```
**Symbols:**

```
ffffffff81c37650-ffffffff81c37765: __phy_read_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int __phy_read_mmd(struct phy_device *phydev, int devad, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81cec5f0)
Location: drivers/net/phy/phy-core.c:574
Inline: True
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_mmd
  - drivers/net/phy/phy-core.c:phy_modify_mmd_changed
  - drivers/net/phy/phy-core.c:phy_read_mmd
```
**Symbols:**

```
ffffffff81cec5f0-ffffffff81cec67d: __phy_read_mmd (STB_GLOBAL)
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
int __phy_read_mmd(struct phy_device *phydev, int devad, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffff8000109d3128)
Location: drivers/net/phy/phy-core.c:375
Inline: True
Direct callers:
  - drivers/net/phy/phy-core.c:__phy_modify_mmd_changed
  - drivers/net/phy/phy-core.c:phy_read_mmd
```
**Symbols:**

```
ffff8000109d3128-ffff8000109d31f8: __phy_read_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __phy_read_mmd(struct phy_device *phydev, int devad, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (c0abb0c8)
Location: drivers/net/phy/phy-core.c:375
Inline: True
Direct callers:
  - drivers/net/phy/phy-core.c:__phy_modify_mmd_changed
  - drivers/net/phy/phy-core.c:phy_read_mmd
```
**Symbols:**

```
c0abb0c8-c0abb174: __phy_read_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __phy_read_mmd(struct phy_device *phydev, int devad, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (c000000000a934e0)
Location: drivers/net/phy/phy-core.c:375
Inline: True
Direct callers:
  - drivers/net/phy/phy-core.c:__phy_modify_mmd_changed
  - drivers/net/phy/phy-core.c:phy_read_mmd
```
**Symbols:**

```
c000000000a934e0-c000000000a935d8: __phy_read_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __phy_read_mmd(struct phy_device *phydev, int devad, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffe00061f912)
Location: drivers/net/phy/phy-core.c:375
Inline: True
Direct callers:
  - drivers/net/phy/phy-core.c:__phy_modify_mmd_changed
  - drivers/net/phy/phy-core.c:phy_read_mmd
```
**Symbols:**

```
ffffffe00061f912-ffffffe00061f9d2: __phy_read_mmd (STB_GLOBAL)
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
int __phy_read_mmd(struct phy_device *phydev, int devad, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8177f3c0)
Location: drivers/net/phy/phy-core.c:375
Inline: True
Direct callers:
  - drivers/net/phy/phy-core.c:__phy_modify_mmd_changed
  - drivers/net/phy/phy-core.c:phy_read_mmd
```
**Symbols:**

```
ffffffff8177f3c0-ffffffff8177f460: __phy_read_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __phy_read_mmd(struct phy_device *phydev, int devad, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8175f160)
Location: drivers/net/phy/phy-core.c:375
Inline: True
Direct callers:
  - drivers/net/phy/phy-core.c:__phy_modify_mmd_changed
  - drivers/net/phy/phy-core.c:phy_read_mmd
```
**Symbols:**

```
ffffffff8175f160-ffffffff8175f200: __phy_read_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __phy_read_mmd(struct phy_device *phydev, int devad, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817af770)
Location: drivers/net/phy/phy-core.c:375
Inline: True
Direct callers:
  - drivers/net/phy/phy-core.c:__phy_modify_mmd_changed
  - drivers/net/phy/phy-core.c:phy_read_mmd
```
**Symbols:**

```
ffffffff817af770-ffffffff817af810: __phy_read_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __phy_read_mmd(struct phy_device *phydev, int devad, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817c9700)
Location: drivers/net/phy/phy-core.c:375
Inline: True
Direct callers:
  - drivers/net/phy/phy-core.c:__phy_modify_mmd_changed
  - drivers/net/phy/phy-core.c:phy_read_mmd
```
**Symbols:**

```
ffffffff817c9700-ffffffff817c97a0: __phy_read_mmd (STB_GLOBAL)
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
