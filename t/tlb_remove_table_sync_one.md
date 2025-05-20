# Function: <code>tlb_remove_table_sync_one</code>

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
In mm/mmu_gather.c (ffffffff8129dad3)
Location: mm/mmu_gather.c:142
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_remove_table
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
In mm/mmu_gather.c (ffffffff812a8e53)
Location: mm/mmu_gather.c:142
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_remove_table
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
In mm/mmu_gather.c (ffffffff812ae303)
Location: mm/mmu_gather.c:142
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_remove_table
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff812efaa3)
Location: mm/mmu_gather.c:142
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_remove_table
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff81352fc5)
Location: mm/mmu_gather.c:155
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_remove_table
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void tlb_remove_table_sync_one();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff813cd218)
Location: mm/mmu_gather.c:194
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_remove_table
Direct callers:
  - mm/khugepaged.c:collapse_and_free_pmd
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff813cd000-ffffffff813cd028: tlb_remove_table_sync_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void tlb_remove_table_sync_one();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff81401b78)
Location: mm/mmu_gather.c:194
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_remove_table
Direct callers:
  - mm/khugepaged.c:collapse_and_free_pmd
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff81401960-ffffffff81401988: tlb_remove_table_sync_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void tlb_remove_table_sync_one();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff8142e20a)
Location: mm/mmu_gather.c:195
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_remove_table
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff8142e020-ffffffff8142e048: tlb_remove_table_sync_one (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
