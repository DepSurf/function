# Function: <code>phy_save_page</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int phy_save_page(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817368e5)
Location: drivers/net/phy/phy-core.c:392
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_select_page
```
**Symbols:**

```
ffffffff817368a0-ffffffff817368d6: phy_save_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int phy_save_page(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81759a85)
Location: drivers/net/phy/phy-core.c:563
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_select_page
```
**Symbols:**

```
ffffffff81759a40-ffffffff81759a76: phy_save_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int phy_save_page(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81796a65)
Location: drivers/net/phy/phy-core.c:669
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_select_page
```
**Symbols:**

```
ffffffff81796a20-ffffffff81796a59: phy_save_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int phy_save_page(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817ba4f5)
Location: drivers/net/phy/phy-core.c:708
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_select_page
```
**Symbols:**

```
ffffffff817ba4b0-ffffffff817ba4e9: phy_save_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int phy_save_page(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81881b00)
Location: drivers/net/phy/phy-core.c:726
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff81881b00-ffffffff81881b72: phy_save_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int phy_save_page(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81890230)
Location: drivers/net/phy/phy-core.c:773
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff81890230-ffffffff818902a2: phy_save_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int phy_save_page(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81872b30)
Location: drivers/net/phy/phy-core.c:773
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff81872b30-ffffffff81872ba2: phy_save_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int phy_save_page(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy-core.c (0)
Location: drivers/net/phy/phy-core.c:774
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff81d10243-ffffffff81d10258: phy_save_page.cold (STB_LOCAL)
ffffffff81903240-ffffffff819032c1: phy_save_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int phy_save_page(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy-core.c (0)
Location: drivers/net/phy/phy-core.c:769
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff81edafe1-ffffffff81edaff5: phy_save_page.cold (STB_LOCAL)
ffffffff81a55d50-ffffffff81a55dcc: phy_save_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int phy_save_page(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy-core.c (0)
Location: drivers/net/phy/phy-core.c:852
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff8209d4f9-ffffffff8209d50d: phy_save_page.cold (STB_LOCAL)
ffffffff81bdf920-ffffffff81bdf99c: phy_save_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int phy_save_page(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy-core.c (0)
Location: drivers/net/phy/phy-core.c:855
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff8211e3d9-ffffffff8211e3ed: phy_save_page.cold (STB_LOCAL)
ffffffff81c37210-ffffffff81c3728c: phy_save_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int phy_save_page(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy-core.c (0)
Location: drivers/net/phy/phy-core.c:993
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff821ffa02-ffffffff821ffa16: phy_save_page.cold (STB_LOCAL)
ffffffff81cebff0-ffffffff81cec06c: phy_save_page (STB_GLOBAL)
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
int phy_save_page(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffff8000109d2c58)
Location: drivers/net/phy/phy-core.c:708
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_select_page
```
**Symbols:**

```
ffff8000109d2bf8-ffff8000109d2c38: phy_save_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int phy_save_page(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (c0abaccc)
Location: drivers/net/phy/phy-core.c:708
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_select_page
```
**Symbols:**

```
c0abac80-c0abacb8: phy_save_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int phy_save_page(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (c000000000a92ec8)
Location: drivers/net/phy/phy-core.c:708
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_select_page
```
**Symbols:**

```
c000000000a92e30-c000000000a92e94: phy_save_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int phy_save_page(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffe00061f4f8)
Location: drivers/net/phy/phy-core.c:708
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_select_page
```
**Symbols:**

```
ffffffe00061f4a0-ffffffe00061f4dc: phy_save_page (STB_GLOBAL)
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
int phy_save_page(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8177efc5)
Location: drivers/net/phy/phy-core.c:708
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_select_page
```
**Symbols:**

```
ffffffff8177ef80-ffffffff8177efb9: phy_save_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int phy_save_page(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8175ed65)
Location: drivers/net/phy/phy-core.c:708
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_select_page
```
**Symbols:**

```
ffffffff8175ed20-ffffffff8175ed59: phy_save_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int phy_save_page(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817af375)
Location: drivers/net/phy/phy-core.c:708
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_select_page
```
**Symbols:**

```
ffffffff817af330-ffffffff817af369: phy_save_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int phy_save_page(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817c9305)
Location: drivers/net/phy/phy-core.c:708
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_select_page
```
**Symbols:**

```
ffffffff817c92c0-ffffffff817c92f9: phy_save_page (STB_GLOBAL)
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
