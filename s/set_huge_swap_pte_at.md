# Function: <code>set_huge_swap_pte_at</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/rmap.c (0)
Location: include/linux/hugetlb.h:522
Inline: True
```
```
In mm/hugetlb.c (ffffffff812198ab)
Location: include/linux/hugetlb.h:522
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
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
In mm/rmap.c (0)
Location: include/linux/hugetlb.h:516
Inline: True
```
```
In mm/hugetlb.c (ffffffff81234927)
Location: include/linux/hugetlb.h:516
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
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
In mm/rmap.c (ffffffff8123f387)
Location: include/linux/hugetlb.h:529
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff81256f29)
Location: include/linux/hugetlb.h:529
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
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
In mm/rmap.c (ffffffff81253a97)
Location: include/linux/hugetlb.h:540
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff8126b59f)
Location: include/linux/hugetlb.h:540
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
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
In mm/rmap.c (ffffffff81265cc1)
Location: include/linux/hugetlb.h:565
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff8128685b)
Location: include/linux/hugetlb.h:565
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
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
In mm/rmap.c (ffffffff812745df)
Location: include/linux/hugetlb.h:565
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff8129644a)
Location: include/linux/hugetlb.h:565
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
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
In mm/rmap.c (ffffffff812a58b8)
Location: include/linux/hugetlb.h:728
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff812c99ed)
Location: include/linux/hugetlb.h:728
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
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
In mm/rmap.c (ffffffff812b0d12)
Location: include/linux/hugetlb.h:747
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff812d5665)
Location: include/linux/hugetlb.h:747
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
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
In mm/rmap.c (ffffffff812b6364)
Location: include/linux/hugetlb.h:849
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff812dc3c0)
Location: include/linux/hugetlb.h:849
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
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
In mm/rmap.c (ffffffff812f880c)
Location: include/linux/hugetlb.h:877
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff81323591)
Location: include/linux/hugetlb.h:877
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8135e6b1)
Location: include/linux/hugetlb.h:907
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff81391076)
Location: include/linux/hugetlb.h:907
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
</details>
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
<summary>In <code>arm64</code>: ✅</summary>

```c
void set_huge_swap_pte_at(struct mm_struct *mm, long unsigned int addr, pte_t *ptep, pte_t pte, long unsigned int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/hugetlbpage.c (ffff8000100b0d48)
Location: arch/arm64/mm/hugetlbpage.c:204
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
**Symbols:**

```
ffff8000100b0d48-ffff8000100b0df4: set_huge_swap_pte_at (STB_GLOBAL)
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
In mm/rmap.c (0)
Location: include/linux/hugetlb.h:739
Inline: True
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
In mm/rmap.c (c0000000003d9c44)
Location: include/linux/hugetlb.h:565
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (c00000000040fe78)
Location: include/linux/hugetlb.h:565
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
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
In mm/rmap.c (0)
Location: include/linux/hugetlb.h:565
Inline: True
```
```
In mm/hugetlb.c (ffffffe000230ee0)
Location: include/linux/hugetlb.h:565
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
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
In mm/rmap.c (ffffffff8126cc2f)
Location: include/linux/hugetlb.h:565
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff8128ea2a)
Location: include/linux/hugetlb.h:565
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
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
In mm/rmap.c (ffffffff8125ec80)
Location: include/linux/hugetlb.h:565
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff81280807)
Location: include/linux/hugetlb.h:565
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
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
In mm/rmap.c (ffffffff8126a9cf)
Location: include/linux/hugetlb.h:565
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff8128c83a)
Location: include/linux/hugetlb.h:565
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
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
In mm/rmap.c (ffffffff8127a349)
Location: include/linux/hugetlb.h:565
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff8129c618)
Location: include/linux/hugetlb.h:565
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
