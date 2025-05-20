# Function: <code>memtype_rb_insert</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat_rbtree.c (ffffffff81071efd)
Location: arch/x86/mm/pat_rbtree.c:169
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
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
In arch/x86/mm/pat_rbtree.c (ffffffff81072b80)
Location: arch/x86/mm/pat_rbtree.c:178
Inline: True
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
```
**Symbols:**

```
ffffffff81072b80-ffffffff81072c01: memtype_rb_insert.constprop.5 (STB_LOCAL)
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
In arch/x86/mm/pat_rbtree.c (ffffffff81076730)
Location: arch/x86/mm/pat_rbtree.c:178
Inline: True
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
```
**Symbols:**

```
ffffffff81076730-ffffffff810767b1: memtype_rb_insert.constprop.5 (STB_LOCAL)
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
In arch/x86/mm/pat_rbtree.c (ffffffff81074e30)
Location: arch/x86/mm/pat_rbtree.c:178
Inline: True
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
```
**Symbols:**

```
ffffffff81074e30-ffffffff81074eaf: memtype_rb_insert.constprop.5 (STB_LOCAL)
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
In arch/x86/mm/pat_rbtree.c (ffffffff8107b060)
Location: arch/x86/mm/pat_rbtree.c:179
Inline: True
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
```
**Symbols:**

```
ffffffff8107b060-ffffffff8107b0e3: memtype_rb_insert.constprop.5 (STB_LOCAL)
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
In arch/x86/mm/pat_rbtree.c (ffffffff8107de30)
Location: arch/x86/mm/pat_rbtree.c:179
Inline: True
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
```
**Symbols:**

```
ffffffff8107de30-ffffffff8107deb3: memtype_rb_insert.constprop.6 (STB_LOCAL)
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
In arch/x86/mm/pat_rbtree.c (ffffffff810849b0)
Location: arch/x86/mm/pat_rbtree.c:179
Inline: True
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
```
**Symbols:**

```
ffffffff810849b0-ffffffff81084a33: memtype_rb_insert.constprop.6 (STB_LOCAL)
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
In arch/x86/mm/pat_rbtree.c (ffffffff81088640)
Location: arch/x86/mm/pat_rbtree.c:179
Inline: True
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
```
**Symbols:**

```
ffffffff81088640-ffffffff810886d1: memtype_rb_insert.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat_rbtree.c (ffffffff810892b0)
Location: arch/x86/mm/pat_rbtree.c:166
Inline: True
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
```
**Symbols:**

```
ffffffff810892b0-ffffffff81089341: memtype_rb_insert.constprop.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat_rbtree.c (ffffffff81088270)
Location: arch/x86/mm/pat_rbtree.c:166
Inline: True
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
```
**Symbols:**

```
ffffffff81088270-ffffffff81088301: memtype_rb_insert.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat_rbtree.c (ffffffff81076ed0)
Location: arch/x86/mm/pat_rbtree.c:166
Inline: True
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
```
**Symbols:**

```
ffffffff81076ed0-ffffffff81076f61: memtype_rb_insert.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat_rbtree.c (ffffffff81088220)
Location: arch/x86/mm/pat_rbtree.c:166
Inline: True
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
```
**Symbols:**

```
ffffffff81088220-ffffffff810882b1: memtype_rb_insert.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat_rbtree.c (ffffffff8108a4c0)
Location: arch/x86/mm/pat_rbtree.c:166
Inline: True
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
```
**Symbols:**

```
ffffffff8108a4c0-ffffffff8108a551: memtype_rb_insert.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
