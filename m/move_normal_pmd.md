# Function: <code>move_normal_pmd</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff8124f16c)
Location: mm/mremap.c:195
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
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
In mm/mremap.c (ffffffff812614c8)
Location: mm/mremap.c:195
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
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
In mm/mremap.c (ffffffff8126fc82)
Location: mm/mremap.c:195
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool move_normal_pmd(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int old_end, pmd_t *old_pmd, pmd_t *new_pmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff8129fd80)
Location: mm/mremap.c:195
Inline: False
Direct callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff8129fd80-ffffffff8129ff24: move_normal_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mremap.c (ffffffff812ab220)
Location: mm/mremap.c:214
Inline: True
Direct callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff812ab220-ffffffff812ab395: move_normal_pmd.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mremap.c (ffffffff812b0620)
Location: mm/mremap.c:213
Inline: True
Direct callers:
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff812b0620-ffffffff812b0794: move_normal_pmd.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mremap.c (ffffffff812f1f40)
Location: mm/mremap.c:223
Inline: True
Direct callers:
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff812f1f40-ffffffff812f212f: move_normal_pmd.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mremap.c (ffffffff81355cb0)
Location: mm/mremap.c:223
Inline: True
Direct callers:
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff81355cb0-ffffffff81355ec5: move_normal_pmd.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mremap.c (ffffffff813d02d0)
Location: mm/mremap.c:225
Inline: True
Direct callers:
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff813d02d0-ffffffff813d04e7: move_normal_pmd.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mremap.c (ffffffff81405040)
Location: mm/mremap.c:236
Inline: True
Direct callers:
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff81405040-ffffffff8140525d: move_normal_pmd.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mremap.c (ffffffff81431520)
Location: mm/mremap.c:236
Inline: True
Direct callers:
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff81431520-ffffffff8143173d: move_normal_pmd.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In mm/mremap.c (ffffffff812682d2)
Location: mm/mremap.c:195
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
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
In mm/mremap.c (ffffffff8125a41f)
Location: mm/mremap.c:195
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
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
In mm/mremap.c (ffffffff81266072)
Location: mm/mremap.c:195
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
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
In mm/mremap.c (ffffffff81275a03)
Location: mm/mremap.c:195
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
