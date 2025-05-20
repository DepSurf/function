# Function: <code>__phy_write_page</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81736971)
Location: drivers/net/phy/phy-core.c:379
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_restore_page
  - drivers/net/phy/phy-core.c:phy_select_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81759b11)
Location: drivers/net/phy/phy-core.c:550
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_restore_page
  - drivers/net/phy/phy-core.c:phy_select_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81796bd2)
Location: drivers/net/phy/phy-core.c:656
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_restore_page
  - drivers/net/phy/phy-core.c:phy_select_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817ba662)
Location: drivers/net/phy/phy-core.c:695
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_restore_page
  - drivers/net/phy/phy-core.c:phy_select_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __phy_write_page(struct phy_device *phydev, int page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81881b80)
Location: drivers/net/phy/phy-core.c:710
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff81881b80-ffffffff81881bd2: __phy_write_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __phy_write_page(struct phy_device *phydev, int page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff818902b0)
Location: drivers/net/phy/phy-core.c:757
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff818902b0-ffffffff81890302: __phy_write_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __phy_write_page(struct phy_device *phydev, int page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81872bb0)
Location: drivers/net/phy/phy-core.c:757
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff81872bb0-ffffffff81872c02: __phy_write_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __phy_write_page(struct phy_device *phydev, int page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy-core.c (0)
Location: drivers/net/phy/phy-core.c:758
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff819032d0-ffffffff81903333: __phy_write_page (STB_LOCAL)
ffffffff81d10258-ffffffff81d1026c: __phy_write_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __phy_write_page(struct phy_device *phydev, int page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy-core.c (0)
Location: drivers/net/phy/phy-core.c:753
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff81a55dd0-ffffffff81a55e33: __phy_write_page (STB_LOCAL)
ffffffff81edaff5-ffffffff81edb009: __phy_write_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __phy_write_page(struct phy_device *phydev, int page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy-core.c (0)
Location: drivers/net/phy/phy-core.c:836
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff81bdf9b0-ffffffff81bdfa13: __phy_write_page (STB_LOCAL)
ffffffff8209d50d-ffffffff8209d521: __phy_write_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __phy_write_page(struct phy_device *phydev, int page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy-core.c (0)
Location: drivers/net/phy/phy-core.c:839
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff81c372a0-ffffffff81c37303: __phy_write_page (STB_LOCAL)
ffffffff8211e3ed-ffffffff8211e401: __phy_write_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __phy_write_page(struct phy_device *phydev, int page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy-core.c (0)
Location: drivers/net/phy/phy-core.c:977
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_write_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
  - drivers/net/phy/phy-core.c:phy_read_paged
```
**Symbols:**

```
ffffffff81cec080-ffffffff81cec0e3: __phy_write_page (STB_LOCAL)
ffffffff821ffa16-ffffffff821ffa2a: __phy_write_page.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffff8000109d2dc0)
Location: drivers/net/phy/phy-core.c:695
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_restore_page
  - drivers/net/phy/phy-core.c:phy_select_page
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (c0abae0c)
Location: drivers/net/phy/phy-core.c:695
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_restore_page
  - drivers/net/phy/phy-core.c:phy_select_page
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (c000000000a930e0)
Location: drivers/net/phy/phy-core.c:695
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_restore_page
  - drivers/net/phy/phy-core.c:phy_select_page
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffe00061f64a)
Location: drivers/net/phy/phy-core.c:695
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_restore_page
  - drivers/net/phy/phy-core.c:phy_select_page
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8177f132)
Location: drivers/net/phy/phy-core.c:695
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_restore_page
  - drivers/net/phy/phy-core.c:phy_select_page
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8175eed2)
Location: drivers/net/phy/phy-core.c:695
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_restore_page
  - drivers/net/phy/phy-core.c:phy_select_page
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817af4e2)
Location: drivers/net/phy/phy-core.c:695
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_restore_page
  - drivers/net/phy/phy-core.c:phy_select_page
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817c9472)
Location: drivers/net/phy/phy-core.c:695
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_restore_page
  - drivers/net/phy/phy-core.c:phy_select_page
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
