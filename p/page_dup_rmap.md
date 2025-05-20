# Function: <code>page_dup_rmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811c12d0)
Location: include/linux/rmap.h:166
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/hugetlb.c (ffffffff811de9c3)
Location: include/linux/rmap.h:166
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/migrate.c (ffffffff811f0db8)
Location: include/linux/rmap.h:166
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff811f5e54)
Location: include/linux/rmap.h:166
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811dcd38)
Location: include/linux/rmap.h:176
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/hugetlb.c (ffffffff811fd779)
Location: include/linux/rmap.h:176
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff81210030)
Location: include/linux/rmap.h:176
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81214c80)
Location: include/linux/rmap.h:176
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811ec830)
Location: include/linux/rmap.h:185
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/hugetlb.c (ffffffff8120e240)
Location: include/linux/rmap.h:185
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff81222158)
Location: include/linux/rmap.h:185
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81227268)
Location: include/linux/rmap.h:185
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f775d)
Location: include/linux/rmap.h:183
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/hugetlb.c (ffffffff81217805)
Location: include/linux/rmap.h:183
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff8122dfd4)
Location: include/linux/rmap.h:183
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812330a2)
Location: include/linux/rmap.h:183
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8120a8d0)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/hugetlb.c (ffffffff81232569)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff81249d2c)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812508a9)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122b6c9)
Location: include/linux/rmap.h:187
Inline: True
```
```
In mm/hugetlb.c (ffffffff81255562)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff8126d56d)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81274ebb)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8123ea9e)
Location: include/linux/rmap.h:187
Inline: True
```
```
In mm/hugetlb.c (ffffffff8126993d)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff81281c5d)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81289e5c)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81250850)
Location: include/linux/rmap.h:187
Inline: True
```
```
In mm/hugetlb.c (ffffffff81284a77)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff8129dd5d)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812a4a6b)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125ee00)
Location: include/linux/rmap.h:187
Inline: True
```
```
In mm/hugetlb.c (ffffffff81294617)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff812ad60d)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812b5f2b)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8128ee78)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/memory.c:copy_one_pte
  - mm/memory.c:copy_one_pte
```
```
In mm/hugetlb.c (ffffffff812c7a09)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff812e29b9)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812eb024)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812999e1)
Location: include/linux/rmap.h:186
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/hugetlb.c (ffffffff812d3579)
Location: include/linux/rmap.h:186
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff812edde4)
Location: include/linux/rmap.h:186
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812f869c)
Location: include/linux/rmap.h:186
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129ec69)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/hugetlb.c (ffffffff812da39c)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff812f3f93)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812feba5)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812dfeb4)
Location: include/linux/rmap.h:183
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/hugetlb.c (ffffffff81321291)
Location: include/linux/rmap.h:183
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff8133e9c4)
Location: include/linux/rmap.h:183
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff813487a5)
Location: include/linux/rmap.h:183
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
```
</details>
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102f6508)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/hugetlb.c (ffff80001033308c)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffff80001034f120)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffff800010356e8c)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
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
In mm/memory.c (c051866c)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003be4a8)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/hugetlb.c (c00000000040ee30)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (c000000000431374)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (c00000000043eb6c)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe000209e9e)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/hugetlb.c (ffffffe00022f5aa)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffe00023e1fe)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81257450)
Location: include/linux/rmap.h:187
Inline: True
```
```
In mm/hugetlb.c (ffffffff8128cbf7)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff812a5bed)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812ae50b)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81249d40)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/hugetlb.c (ffffffff8127ea19)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff812976bb)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff8129fb13)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812551f0)
Location: include/linux/rmap.h:187
Inline: True
```
```
In mm/hugetlb.c (ffffffff8128aa07)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff812a39fd)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812ac31b)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81264ca6)
Location: include/linux/rmap.h:187
Inline: True
```
```
In mm/hugetlb.c (ffffffff8129a7fc)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff812b420d)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812bc6ac)
Location: include/linux/rmap.h:187
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
```
</details>
</li>
</ul>

## Differences
