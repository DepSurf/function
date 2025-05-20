# Function: <code>vmemmap_alloc_block_zero</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff8198f231)
Location: mm/sparse-vmemmap.c:190
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
**Symbols:**

```
ffffffff8198f231-ffffffff8198f25a: vmemmap_alloc_block_zero.constprop.9 (STB_LOCAL)
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
In mm/sparse-vmemmap.c (ffffffff819eba73)
Location: mm/sparse-vmemmap.c:168
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
**Symbols:**

```
ffffffff819eba73-ffffffff819eba9c: vmemmap_alloc_block_zero.constprop.6 (STB_LOCAL)
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
In mm/sparse-vmemmap.c (ffffffff81a26cf4)
Location: mm/sparse-vmemmap.c:157
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
**Symbols:**

```
ffffffff81a26cf4-ffffffff81a26d1d: vmemmap_alloc_block_zero.constprop.6 (STB_LOCAL)
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
In mm/sparse-vmemmap.c (ffffffff81a97597)
Location: mm/sparse-vmemmap.c:157
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
**Symbols:**

```
ffffffff81a97597-ffffffff81a975c0: vmemmap_alloc_block_zero.constprop.0 (STB_LOCAL)
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
In mm/sparse-vmemmap.c (ffffffff81acee79)
Location: mm/sparse-vmemmap.c:157
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
**Symbols:**

```
ffffffff81acee79-ffffffff81aceea2: vmemmap_alloc_block_zero.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81bc783a)
Location: mm/sparse-vmemmap.c:156
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
**Symbols:**

```
ffffffff81bc783a-ffffffff81bc7863: vmemmap_alloc_block_zero.constprop.0 (STB_LOCAL)
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
In mm/sparse-vmemmap.c (ffffffff81c4056f)
Location: mm/sparse-vmemmap.c:160
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
**Symbols:**

```
ffffffff81c4056f-ffffffff81c40598: vmemmap_alloc_block_zero.constprop.0 (STB_LOCAL)
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
In mm/sparse-vmemmap.c (ffffffff81c32617)
Location: mm/sparse-vmemmap.c:160
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
**Symbols:**

```
ffffffff81c32617-ffffffff81c32640: vmemmap_alloc_block_zero.constprop.0 (STB_LOCAL)
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
In mm/sparse-vmemmap.c (ffffffff81d51177)
Location: mm/sparse-vmemmap.c:514
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
**Symbols:**

```
ffffffff81d51177-ffffffff81d511a0: vmemmap_alloc_block_zero.constprop.0 (STB_LOCAL)
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
In mm/sparse-vmemmap.c (ffffffff81f213ab)
Location: mm/sparse-vmemmap.c:575
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
**Symbols:**

```
ffffffff81f213ab-ffffffff81f213e0: vmemmap_alloc_block_zero.constprop.0 (STB_LOCAL)
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
In mm/sparse-vmemmap.c (ffffffff820cb290)
Location: mm/sparse-vmemmap.c:176
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
**Symbols:**

```
ffffffff820cb290-ffffffff820cb2e7: vmemmap_alloc_block_zero.constprop.0 (STB_LOCAL)
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
In mm/sparse-vmemmap.c (ffffffff8214f520)
Location: mm/sparse-vmemmap.c:176
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
**Symbols:**

```
ffffffff8214f520-ffffffff8214f577: vmemmap_alloc_block_zero.constprop.0 (STB_LOCAL)
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
In mm/sparse-vmemmap.c (ffffffff822323f0)
Location: mm/sparse-vmemmap.c:176
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
**Symbols:**

```
ffffffff822323f0-ffffffff82232447: vmemmap_alloc_block_zero.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/sparse-vmemmap.c (ffff800010da0ab4)
Location: mm/sparse-vmemmap.c:157
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
**Symbols:**

```
ffff800010da0ab4-ffff800010da0af0: vmemmap_alloc_block_zero.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/sparse-vmemmap.c (c000000000eed89c)
Location: mm/sparse-vmemmap.c:157
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
**Symbols:**

```
c000000000eed89c-c000000000eed8f0: vmemmap_alloc_block_zero.constprop.0 (STB_LOCAL)
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
In mm/sparse-vmemmap.c (ffffffe00004908a)
Location: mm/sparse-vmemmap.c:157
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
</details>
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
In mm/sparse-vmemmap.c (ffffffff81a6dce9)
Location: mm/sparse-vmemmap.c:157
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
**Symbols:**

```
ffffffff81a6dce9-ffffffff81a6dd12: vmemmap_alloc_block_zero.constprop.0 (STB_LOCAL)
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
In mm/sparse-vmemmap.c (ffffffff81a2a230)
Location: mm/sparse-vmemmap.c:157
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
**Symbols:**

```
ffffffff81a2a230-ffffffff81a2a259: vmemmap_alloc_block_zero.constprop.0 (STB_LOCAL)
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
In mm/sparse-vmemmap.c (ffffffff81ada0f9)
Location: mm/sparse-vmemmap.c:157
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
**Symbols:**

```
ffffffff81ada0f9-ffffffff81ada122: vmemmap_alloc_block_zero.constprop.0 (STB_LOCAL)
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
In mm/sparse-vmemmap.c (ffffffff81ae65af)
Location: mm/sparse-vmemmap.c:157
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
**Symbols:**

```
ffffffff81ae65af-ffffffff81ae65d8: vmemmap_alloc_block_zero.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
