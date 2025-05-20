# Function: <code>phy_modify_paged_changed</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int phy_modify_paged_changed(struct phy_device *phydev, int page, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817ba750)
Location: drivers/net/phy/phy-core.c:834
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
```
**Symbols:**

```
ffffffff817ba750-ffffffff817ba7a5: phy_modify_paged_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int phy_modify_paged_changed(struct phy_device *phydev, int page, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81882245)
Location: drivers/net/phy/phy-core.c:852
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
```
**Symbols:**

```
ffffffff81882300-ffffffff818823aa: phy_modify_paged_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int phy_modify_paged_changed(struct phy_device *phydev, int page, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8189098e)
Location: drivers/net/phy/phy-core.c:899
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
```
**Symbols:**

```
ffffffff81890a30-ffffffff81890ada: phy_modify_paged_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int phy_modify_paged_changed(struct phy_device *phydev, int page, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8187328a)
Location: drivers/net/phy/phy-core.c:899
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
```
**Symbols:**

```
ffffffff81873320-ffffffff818733c7: phy_modify_paged_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int phy_modify_paged_changed(struct phy_device *phydev, int page, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81903a5a)
Location: drivers/net/phy/phy-core.c:900
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
```
**Symbols:**

```
ffffffff81903af0-ffffffff81903b97: phy_modify_paged_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int phy_modify_paged_changed(struct phy_device *phydev, int page, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81a5647d)
Location: drivers/net/phy/phy-core.c:895
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
```
**Symbols:**

```
ffffffff81a56520-ffffffff81a565d6: phy_modify_paged_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int phy_modify_paged_changed(struct phy_device *phydev, int page, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81be020d)
Location: drivers/net/phy/phy-core.c:978
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
```
**Symbols:**

```
ffffffff81be0120-ffffffff81be01d6: phy_modify_paged_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int phy_modify_paged_changed(struct phy_device *phydev, int page, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81c37afd)
Location: drivers/net/phy/phy-core.c:981
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
```
**Symbols:**

```
ffffffff81c37a10-ffffffff81c37ac6: phy_modify_paged_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int phy_modify_paged_changed(struct phy_device *phydev, int page, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81cecdbd)
Location: drivers/net/phy/phy-core.c:1119
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
```
**Symbols:**

```
ffffffff81cece70-ffffffff81cecf26: phy_modify_paged_changed (STB_GLOBAL)
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
int phy_modify_paged_changed(struct phy_device *phydev, int page, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffff8000109d2ee8)
Location: drivers/net/phy/phy-core.c:834
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
```
**Symbols:**

```
ffff8000109d2ee8-ffff8000109d2f68: phy_modify_paged_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int phy_modify_paged_changed(struct phy_device *phydev, int page, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (c0abaef0)
Location: drivers/net/phy/phy-core.c:834
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
```
**Symbols:**

```
c0abaef0-c0abaf4c: phy_modify_paged_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int phy_modify_paged_changed(struct phy_device *phydev, int page, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (c000000000a93280)
Location: drivers/net/phy/phy-core.c:834
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
```
**Symbols:**

```
c000000000a93280-c000000000a93318: phy_modify_paged_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int phy_modify_paged_changed(struct phy_device *phydev, int page, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffe00061f74c)
Location: drivers/net/phy/phy-core.c:834
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
```
**Symbols:**

```
ffffffe00061f74c-ffffffe00061f7b6: phy_modify_paged_changed (STB_GLOBAL)
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
int phy_modify_paged_changed(struct phy_device *phydev, int page, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8177f220)
Location: drivers/net/phy/phy-core.c:834
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
```
**Symbols:**

```
ffffffff8177f220-ffffffff8177f275: phy_modify_paged_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int phy_modify_paged_changed(struct phy_device *phydev, int page, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8175efc0)
Location: drivers/net/phy/phy-core.c:834
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
```
**Symbols:**

```
ffffffff8175efc0-ffffffff8175f015: phy_modify_paged_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int phy_modify_paged_changed(struct phy_device *phydev, int page, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817af5d0)
Location: drivers/net/phy/phy-core.c:834
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
```
**Symbols:**

```
ffffffff817af5d0-ffffffff817af625: phy_modify_paged_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int phy_modify_paged_changed(struct phy_device *phydev, int page, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817c9560)
Location: drivers/net/phy/phy-core.c:834
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
```
**Symbols:**

```
ffffffff817c9560-ffffffff817c95b5: phy_modify_paged_changed (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
