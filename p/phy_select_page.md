# Function: <code>phy_select_page</code>

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
int phy_select_page(struct phy_device *phydev, int page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817368e0)
Location: drivers/net/phy/phy-core.c:410
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff817368e0-ffffffff8173694f: phy_select_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int phy_select_page(struct phy_device *phydev, int page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81759a80)
Location: drivers/net/phy/phy-core.c:581
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff81759a80-ffffffff81759aef: phy_select_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int phy_select_page(struct phy_device *phydev, int page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81796a60)
Location: drivers/net/phy/phy-core.c:687
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff81796a60-ffffffff81796ad3: phy_select_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int phy_select_page(struct phy_device *phydev, int page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817ba4f0)
Location: drivers/net/phy/phy-core.c:726
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged_changed
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff817ba4f0-ffffffff817ba563: phy_select_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int phy_select_page(struct phy_device *phydev, int page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81882245)
Location: drivers/net/phy/phy-core.c:744
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff81881be0-ffffffff81881c22: phy_select_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int phy_select_page(struct phy_device *phydev, int page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8189098e)
Location: drivers/net/phy/phy-core.c:791
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff81890310-ffffffff81890352: phy_select_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int phy_select_page(struct phy_device *phydev, int page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8187328a)
Location: drivers/net/phy/phy-core.c:791
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff81872c10-ffffffff81872c52: phy_select_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int phy_select_page(struct phy_device *phydev, int page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81903a5a)
Location: drivers/net/phy/phy-core.c:792
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff81903340-ffffffff81903382: phy_select_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int phy_select_page(struct phy_device *phydev, int page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81a5647d)
Location: drivers/net/phy/phy-core.c:787
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff81a55e40-ffffffff81a55e85: phy_select_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int phy_select_page(struct phy_device *phydev, int page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81be020d)
Location: drivers/net/phy/phy-core.c:870
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff81bdfa30-ffffffff81bdfa75: phy_select_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int phy_select_page(struct phy_device *phydev, int page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81c37afd)
Location: drivers/net/phy/phy-core.c:873
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff81c37320-ffffffff81c37365: phy_select_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int phy_select_page(struct phy_device *phydev, int page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81cecdbd)
Location: drivers/net/phy/phy-core.c:1011
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff81cec100-ffffffff81cec145: phy_select_page (STB_GLOBAL)
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
int phy_select_page(struct phy_device *phydev, int page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffff8000109d2c38)
Location: drivers/net/phy/phy-core.c:726
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged_changed
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffff8000109d2c38-ffff8000109d2cb4: phy_select_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int phy_select_page(struct phy_device *phydev, int page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (c0abacb8)
Location: drivers/net/phy/phy-core.c:726
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged_changed
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
c0abacb8-c0abad30: phy_select_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int phy_select_page(struct phy_device *phydev, int page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (c000000000a92ea0)
Location: drivers/net/phy/phy-core.c:726
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged_changed
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
c000000000a92ea0-c000000000a92f84: phy_select_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int phy_select_page(struct phy_device *phydev, int page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffe00061f4dc)
Location: drivers/net/phy/phy-core.c:726
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged_changed
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffe00061f4dc-ffffffe00061f552: phy_select_page (STB_GLOBAL)
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
int phy_select_page(struct phy_device *phydev, int page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8177efc0)
Location: drivers/net/phy/phy-core.c:726
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged_changed
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff8177efc0-ffffffff8177f033: phy_select_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int phy_select_page(struct phy_device *phydev, int page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8175ed60)
Location: drivers/net/phy/phy-core.c:726
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged_changed
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff8175ed60-ffffffff8175edd3: phy_select_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int phy_select_page(struct phy_device *phydev, int page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817af370)
Location: drivers/net/phy/phy-core.c:726
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged_changed
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff817af370-ffffffff817af3e3: phy_select_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int phy_select_page(struct phy_device *phydev, int page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817c9300)
Location: drivers/net/phy/phy-core.c:726
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged_changed
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff817c9300-ffffffff817c9373: phy_select_page (STB_GLOBAL)
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
