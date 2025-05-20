# Function: <code>alloc_new_pud</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mremap.c (ffffffff812ab120)
Location: mm/mremap.c:70
Inline: True
Direct callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff812ab120-ffffffff812ab217: alloc_new_pud.constprop.0 (STB_LOCAL)
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
In mm/mremap.c (ffffffff812b0480)
Location: mm/mremap.c:69
Inline: True
Direct callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff812b0480-ffffffff812b053c: alloc_new_pud.constprop.0 (STB_LOCAL)
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
In mm/mremap.c (0)
Location: mm/mremap.c:70
Inline: True
Direct callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff812f1cd0-ffffffff812f1da1: alloc_new_pud.constprop.0 (STB_LOCAL)
ffffffff81cbcabb-ffffffff81cbcad4: alloc_new_pud.constprop.0.cold (STB_LOCAL)
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
In mm/mremap.c (0)
Location: mm/mremap.c:70
Inline: True
Direct callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff81355a10-ffffffff81355afb: alloc_new_pud.constprop.0 (STB_LOCAL)
ffffffff81e6e654-ffffffff81e6e66d: alloc_new_pud.constprop.0.cold (STB_LOCAL)
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
In mm/mremap.c (0)
Location: mm/mremap.c:72
Inline: True
Direct callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff813d0010-ffffffff813d00fb: alloc_new_pud.constprop.0 (STB_LOCAL)
ffffffff82064565-ffffffff8206457e: alloc_new_pud.constprop.0.cold (STB_LOCAL)
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
In mm/mremap.c (0)
Location: mm/mremap.c:72
Inline: True
Direct callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff81404d70-ffffffff81404e5e: alloc_new_pud.isra.0 (STB_LOCAL)
ffffffff820e3c40-ffffffff820e3c59: alloc_new_pud.isra.0.cold (STB_LOCAL)
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
In mm/mremap.c (0)
Location: mm/mremap.c:72
Inline: True
Direct callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff81431370-ffffffff8143145e: alloc_new_pud.isra.0 (STB_LOCAL)
ffffffff821c07e9-ffffffff821c0802: alloc_new_pud.isra.0.cold (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
