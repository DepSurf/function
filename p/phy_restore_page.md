# Function: <code>phy_restore_page</code>

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
int phy_restore_page(struct phy_device *phydev, int oldpage, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81736950)
Location: drivers/net/phy/phy-core.c:444
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff81736950-ffffffff817369a7: phy_restore_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int phy_restore_page(struct phy_device *phydev, int oldpage, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81759af0)
Location: drivers/net/phy/phy-core.c:615
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff81759af0-ffffffff81759b47: phy_restore_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int phy_restore_page(struct phy_device *phydev, int oldpage, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81796bb0)
Location: drivers/net/phy/phy-core.c:721
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff81796bb0-ffffffff81796c09: phy_restore_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int phy_restore_page(struct phy_device *phydev, int oldpage, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817ba640)
Location: drivers/net/phy/phy-core.c:760
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged_changed
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff817ba640-ffffffff817ba699: phy_restore_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int phy_restore_page(struct phy_device *phydev, int oldpage, int ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8188229e)
Location: drivers/net/phy/phy-core.c:778
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff81881c30-ffffffff81881c7e: phy_restore_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int phy_restore_page(struct phy_device *phydev, int oldpage, int ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff818909ce)
Location: drivers/net/phy/phy-core.c:825
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff81890360-ffffffff818903ae: phy_restore_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int phy_restore_page(struct phy_device *phydev, int oldpage, int ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff818732d2)
Location: drivers/net/phy/phy-core.c:825
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff81872c60-ffffffff81872cac: phy_restore_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int phy_restore_page(struct phy_device *phydev, int oldpage, int ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81903aa2)
Location: drivers/net/phy/phy-core.c:826
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff81903390-ffffffff819033dc: phy_restore_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int phy_restore_page(struct phy_device *phydev, int oldpage, int ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81a564bd)
Location: drivers/net/phy/phy-core.c:821
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff81a55e90-ffffffff81a55ee3: phy_restore_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int phy_restore_page(struct phy_device *phydev, int oldpage, int ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81be024d)
Location: drivers/net/phy/phy-core.c:904
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff81bdfa90-ffffffff81bdfae3: phy_restore_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int phy_restore_page(struct phy_device *phydev, int oldpage, int ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81c37b3d)
Location: drivers/net/phy/phy-core.c:907
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff81c37380-ffffffff81c373d3: phy_restore_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int phy_restore_page(struct phy_device *phydev, int oldpage, int ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81cecdfd)
Location: drivers/net/phy/phy-core.c:1045
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff81cec160-ffffffff81cec1b3: phy_restore_page (STB_GLOBAL)
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
int phy_restore_page(struct phy_device *phydev, int oldpage, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffff8000109d2d98)
Location: drivers/net/phy/phy-core.c:760
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged_changed
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffff8000109d2d98-ffff8000109d2e00: phy_restore_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int phy_restore_page(struct phy_device *phydev, int oldpage, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (c0abade8)
Location: drivers/net/phy/phy-core.c:760
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged_changed
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
c0abade8-c0abae48: phy_restore_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int phy_restore_page(struct phy_device *phydev, int oldpage, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (c000000000a930a0)
Location: drivers/net/phy/phy-core.c:760
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged_changed
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
c000000000a930a0-c000000000a93170: phy_restore_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int phy_restore_page(struct phy_device *phydev, int oldpage, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffe00061f628)
Location: drivers/net/phy/phy-core.c:760
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged_changed
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffe00061f628-ffffffe00061f684: phy_restore_page (STB_GLOBAL)
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
int phy_restore_page(struct phy_device *phydev, int oldpage, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8177f110)
Location: drivers/net/phy/phy-core.c:760
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged_changed
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff8177f110-ffffffff8177f169: phy_restore_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int phy_restore_page(struct phy_device *phydev, int oldpage, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8175eeb0)
Location: drivers/net/phy/phy-core.c:760
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged_changed
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff8175eeb0-ffffffff8175ef09: phy_restore_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int phy_restore_page(struct phy_device *phydev, int oldpage, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817af4c0)
Location: drivers/net/phy/phy-core.c:760
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged_changed
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff817af4c0-ffffffff817af519: phy_restore_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int phy_restore_page(struct phy_device *phydev, int oldpage, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817c9450)
Location: drivers/net/phy/phy-core.c:760
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged_changed
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff817c9450-ffffffff817c94a9: phy_restore_page (STB_GLOBAL)
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
