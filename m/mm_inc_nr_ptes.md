# Function: <code>mm_inc_nr_ptes</code>

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
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8120d26a)
Location: include/linux/mm.h:1714
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff81250974)
Location: include/linux/mm.h:1714
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
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
In mm/memory.c (ffffffff8122de3c)
Location: include/linux/mm.h:1801
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff81274db1)
Location: include/linux/mm.h:1801
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
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
In mm/memory.c (ffffffff8124149e)
Location: include/linux/mm.h:1879
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff81289d54)
Location: include/linux/mm.h:1879
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
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
In mm/memory.c (ffffffff81253610)
Location: include/linux/mm.h:1874
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff812a4963)
Location: include/linux/mm.h:1874
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In fs/dax.c (0)
Location: include/linux/mm.h:1874
Inline: True
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
In mm/memory.c (ffffffff81261b70)
Location: include/linux/mm.h:1846
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff812b5e23)
Location: include/linux/mm.h:1846
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In fs/dax.c (0)
Location: include/linux/mm.h:1846
Inline: True
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
In mm/memory.c (ffffffff8128e0cc)
Location: include/linux/mm.h:2078
Inline: True
Inline callers:
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff812eaf1a)
Location: include/linux/mm.h:2078
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In fs/dax.c (0)
Location: include/linux/mm.h:2078
Inline: True
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
In mm/memory.c (ffffffff81298d6c)
Location: include/linux/mm.h:2123
Inline: True
Inline callers:
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff812f8581)
Location: include/linux/mm.h:2123
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In fs/dax.c (0)
Location: include/linux/mm.h:2123
Inline: True
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
In mm/filemap.c (ffffffff8125fa92)
Location: include/linux/mm.h:2131
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/memory.c (ffffffff812a1bce)
Location: include/linux/mm.h:2131
Inline: True
Inline callers:
  - mm/memory.c:finish_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff812fea74)
Location: include/linux/mm.h:2131
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In fs/dax.c (0)
Location: include/linux/mm.h:2131
Inline: True
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
In mm/filemap.c (ffffffff8129c402)
Location: include/linux/mm.h:2160
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/memory.c (ffffffff812e2b9e)
Location: include/linux/mm.h:2160
Inline: True
Inline callers:
  - mm/memory.c:finish_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff81348671)
Location: include/linux/mm.h:2160
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In fs/dax.c (0)
Location: include/linux/mm.h:2160
Inline: True
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
In mm/memory.c (ffffffff8133f8b9)
Location: include/linux/mm.h:2238
Inline: True
Inline callers:
  - mm/memory.c:pmd_install
```
```
In mm/huge_memory.c (ffffffff813be819)
Location: include/linux/mm.h:2238
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In fs/dax.c (0)
Location: include/linux/mm.h:2238
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813b77e9)
Location: include/linux/mm.h:2402
Inline: True
Inline callers:
  - mm/memory.c:pmd_install
```
```
In mm/huge_memory.c (ffffffff81441097)
Location: include/linux/mm.h:2402
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In fs/dax.c (0)
Location: include/linux/mm.h:2402
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813ec589)
Location: include/linux/mm.h:2722
Inline: True
Inline callers:
  - mm/memory.c:pmd_install
```
```
In mm/huge_memory.c (ffffffff81476959)
Location: include/linux/mm.h:2722
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In fs/dax.c (0)
Location: include/linux/mm.h:2722
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81417dc9)
Location: include/linux/mm.h:2763
Inline: True
Inline callers:
  - mm/memory.c:pmd_install
```
```
In mm/huge_memory.c (ffffffff814a61bf)
Location: include/linux/mm.h:2763
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In fs/dax.c (0)
Location: include/linux/mm.h:2763
Inline: True
```
</details>
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
In mm/memory.c (ffff8000102f8f98)
Location: include/linux/mm.h:1846
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffff800010356eb4)
Location: include/linux/mm.h:1846
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
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
In mm/memory.c (c051b498)
Location: include/linux/mm.h:1846
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
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
In mm/memory.c (c0000000003c298c)
Location: include/linux/mm.h:1846
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (c00000000043ea94)
Location: include/linux/mm.h:1846
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In fs/dax.c (c000000000514580)
Location: include/linux/mm.h:1846
Inline: True
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
In mm/memory.c (ffffffe00020908e)
Location: include/linux/mm.h:1846
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
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
In mm/memory.c (ffffffff8125a1c0)
Location: include/linux/mm.h:1846
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff812ae403)
Location: include/linux/mm.h:1846
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In fs/dax.c (0)
Location: include/linux/mm.h:1846
Inline: True
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
In mm/memory.c (ffffffff8124c5d1)
Location: include/linux/mm.h:1846
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff8129fbe2)
Location: include/linux/mm.h:1846
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In fs/dax.c (0)
Location: include/linux/mm.h:1846
Inline: True
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
In mm/memory.c (ffffffff81257f60)
Location: include/linux/mm.h:1846
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff812ac213)
Location: include/linux/mm.h:1846
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In fs/dax.c (0)
Location: include/linux/mm.h:1846
Inline: True
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
In mm/memory.c (ffffffff8126794c)
Location: include/linux/mm.h:1846
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff812bc5a1)
Location: include/linux/mm.h:1846
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In fs/dax.c (0)
Location: include/linux/mm.h:1846
Inline: True
```
</details>
</li>
</ul>

## Differences
