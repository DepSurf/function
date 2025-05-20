# Function: <code>memtype_rb_lowest_match</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat_rbtree.c (ffffffff81071de0)
Location: arch/x86/mm/pat_rbtree.c:76
Inline: True
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_lookup
```
**Symbols:**

```
ffffffff81071de0-ffffffff81071e45: memtype_rb_lowest_match.constprop.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat_rbtree.c (ffffffff81072c10)
Location: arch/x86/mm/pat_rbtree.c:75
Inline: True
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_lookup
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
```
**Symbols:**

```
ffffffff81072c10-ffffffff81072c75: memtype_rb_lowest_match.constprop.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat_rbtree.c (ffffffff810767c0)
Location: arch/x86/mm/pat_rbtree.c:75
Inline: True
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_lookup
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
```
**Symbols:**

```
ffffffff810767c0-ffffffff81076825: memtype_rb_lowest_match.constprop.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat_rbtree.c (ffffffff810756a5)
Location: arch/x86/mm/pat_rbtree.c:75
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_lookup
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat_rbtree.c (ffffffff8107b8e5)
Location: arch/x86/mm/pat_rbtree.c:76
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_lookup
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat_rbtree.c (ffffffff8107e66d)
Location: arch/x86/mm/pat_rbtree.c:76
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_lookup
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
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
In arch/x86/mm/pat_rbtree.c (ffffffff810851ed)
Location: arch/x86/mm/pat_rbtree.c:76
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_lookup
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
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
In arch/x86/mm/pat_rbtree.c (ffffffff81088dfd)
Location: arch/x86/mm/pat_rbtree.c:76
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_lookup
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
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
In arch/x86/mm/pat_rbtree.c (ffffffff81089a6d)
Location: arch/x86/mm/pat_rbtree.c:63
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_lookup
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
```
</details>
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat_rbtree.c (ffffffff81088a2d)
Location: arch/x86/mm/pat_rbtree.c:63
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_lookup
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
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
In arch/x86/mm/pat_rbtree.c (ffffffff8107768d)
Location: arch/x86/mm/pat_rbtree.c:63
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_lookup
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
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
In arch/x86/mm/pat_rbtree.c (ffffffff810889dd)
Location: arch/x86/mm/pat_rbtree.c:63
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_lookup
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
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
In arch/x86/mm/pat_rbtree.c (ffffffff8108ac7d)
Location: arch/x86/mm/pat_rbtree.c:63
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_lookup
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
```
</details>
</li>
</ul>

## Differences
