# Function: <code>madvise_free_page_range</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff811ee764)
Location: mm/madvise.c:395
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff811ff0b4)
Location: mm/madvise.c:396
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/madvise.c (ffffffff81209b20)
Location: mm/madvise.c:433
Inline: True
Direct callers:
  - mm/madvise.c:madvise_free_single_vma
```
**Symbols:**

```
ffffffff81209b20-ffffffff81209b86: madvise_free_page_range.isra.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/madvise.c (ffffffff81222c50)
Location: mm/madvise.c:443
Inline: True
Direct callers:
  - mm/madvise.c:madvise_free_single_vma
```
**Symbols:**

```
ffffffff81222c50-ffffffff81222cb6: madvise_free_page_range.isra.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/madvise.c (ffffffff81244a80)
Location: mm/madvise.c:443
Inline: True
Direct callers:
  - mm/madvise.c:madvise_free_single_vma
```
**Symbols:**

```
ffffffff81244a80-ffffffff81244ae6: madvise_free_page_range.isra.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/madvise.c (ffffffff81258e20)
Location: mm/madvise.c:443
Inline: True
Direct callers:
  - mm/madvise.c:madvise_free_single_vma
```
**Symbols:**

```
ffffffff81258e20-ffffffff81258e86: madvise_free_page_range.isra.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/madvise.c (ffffffff81274630)
Location: mm/madvise.c:443
Inline: True
Direct callers:
  - mm/madvise.c:madvise_free_single_vma
```
**Symbols:**

```
ffffffff81274630-ffffffff81274696: madvise_free_page_range.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
