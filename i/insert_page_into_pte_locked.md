# Function: <code>insert_page_into_pte_locked</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81292f34)
Location: mm/memory.c:1461
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129d7cf)
Location: mm/memory.c:1635
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a2e80)
Location: mm/memory.c:1653
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_page
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
In mm/memory.c (ffffffff812de200)
Location: mm/memory.c:1748
Inline: True
Direct callers:
  - mm/memory.c:vm_insert_page
```
**Symbols:**

```
ffffffff812de200-ffffffff812de29c: insert_page_into_pte_locked.constprop.0 (STB_LOCAL)
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
In mm/memory.c (ffffffff8133f2c0)
Location: mm/memory.c:1842
Inline: True
Direct callers:
  - mm/memory.c:vm_insert_page
  - mm/memory.c:insert_pages
```
**Symbols:**

```
ffffffff8133f2c0-ffffffff8133f3c5: insert_page_into_pte_locked.constprop.0 (STB_LOCAL)
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
In mm/memory.c (ffffffff813b5a80)
Location: mm/memory.c:1813
Inline: True
Direct callers:
  - mm/memory.c:vm_insert_page
  - mm/memory.c:insert_pages
```
**Symbols:**

```
ffffffff813b5a80-ffffffff813b5bac: insert_page_into_pte_locked.constprop.0 (STB_LOCAL)
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
In mm/memory.c (ffffffff813ea520)
Location: mm/memory.c:1829
Inline: True
Direct callers:
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_pages
```
**Symbols:**

```
ffffffff813ea520-ffffffff813ea6c1: insert_page_into_pte_locked.isra.0 (STB_LOCAL)
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
In mm/memory.c (ffffffff814160b0)
Location: mm/memory.c:1865
Inline: True
Direct callers:
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_pages
```
**Symbols:**

```
ffffffff814160b0-ffffffff81416274: insert_page_into_pte_locked.isra.0 (STB_LOCAL)
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
