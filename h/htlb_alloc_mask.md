# Function: <code>htlb_alloc_mask</code>

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
In mm/hugetlb.c (ffffffff811dad53)
Location: mm/hugetlb.c:867
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811fac4c)
Location: mm/hugetlb.c:889
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
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
In mm/hugetlb.c (ffffffff8120b74c)
Location: mm/hugetlb.c:889
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
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
In mm/hugetlb.c (ffffffff812154b1)
Location: mm/hugetlb.c:927
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
  - mm/hugetlb.c:alloc_fresh_huge_page
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
In mm/hugetlb.c (ffffffff81230081)
Location: mm/hugetlb.c:928
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
  - mm/hugetlb.c:alloc_fresh_huge_page
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
In mm/hugetlb.c (ffffffff812534d9)
Location: mm/hugetlb.c:920
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
  - mm/hugetlb.c:alloc_pool_huge_page
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
In mm/hugetlb.c (ffffffff81267419)
Location: mm/hugetlb.c:920
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
  - mm/hugetlb.c:alloc_pool_huge_page
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
In mm/hugetlb.c (ffffffff81282e7a)
Location: mm/hugetlb.c:930
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
  - mm/hugetlb.c:alloc_pool_huge_page
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
In mm/hugetlb.c (ffffffff8129299a)
Location: mm/hugetlb.c:931
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
  - mm/hugetlb.c:alloc_pool_huge_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812c7159)
Location: mm/hugetlb.c:1096
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:dequeue_huge_page_vma
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
In mm/hugetlb.c (ffffffff812cfa72)
Location: include/linux/hugetlb.h:696
Inline: True
Inline callers:
  - mm/hugetlb.c:allowed_mems_nr
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:dequeue_huge_page_vma
```
```
In mm/migrate.c (ffffffff812ed3d2)
Location: include/linux/hugetlb.h:696
Inline: True
Inline callers:
  - mm/migrate.c:alloc_migration_target
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
In mm/hugetlb.c (ffffffff812d9636)
Location: include/linux/hugetlb.h:798
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:alloc_pool_huge_page
```
```
In mm/migrate.c (ffffffff812f376d)
Location: include/linux/hugetlb.h:798
Inline: True
Inline callers:
  - mm/migrate.c:alloc_migration_target
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
In mm/hugetlb.c (ffffffff813200d9)
Location: include/linux/hugetlb.h:821
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:alloc_pool_huge_page
```
```
In mm/migrate.c (ffffffff8133dccf)
Location: include/linux/hugetlb.h:821
Inline: True
Inline callers:
  - mm/migrate.c:alloc_migration_target
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
In mm/hugetlb.c (ffffffff834901bf)
Location: include/linux/hugetlb.h:851
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:dequeue_huge_page_vma
```
```
In mm/migrate.c (ffffffff813b17bd)
Location: include/linux/hugetlb.h:851
Inline: True
Inline callers:
  - mm/migrate.c:alloc_migration_target
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
In mm/hugetlb.c (ffffffff83ec3172)
Location: include/linux/hugetlb.h:903
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:dequeue_huge_page_vma
```
```
In mm/migrate.c (ffffffff81432b23)
Location: include/linux/hugetlb.h:903
Inline: True
Inline callers:
  - mm/migrate.c:alloc_migration_target
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
In mm/hugetlb.c (ffffffff836e8252)
Location: include/linux/hugetlb.h:931
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:alloc_hugetlb_folio_vma
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:dequeue_hugetlb_folio_vma
```
```
In mm/migrate.c (ffffffff8146748e)
Location: include/linux/hugetlb.h:931
Inline: True
Inline callers:
  - mm/migrate.c:alloc_migration_target
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
In mm/hugetlb.c (ffffffff8147a279)
Location: include/linux/hugetlb.h:953
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:alloc_pool_huge_folio
  - mm/hugetlb.c:dequeue_hugetlb_folio_vma
```
```
In mm/mempolicy.c (ffffffff81485c5d)
Location: include/linux/hugetlb.h:953
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_migration_target_by_mpol
```
```
In mm/migrate.c (ffffffff81496618)
Location: include/linux/hugetlb.h:953
Inline: True
Inline callers:
  - mm/migrate.c:alloc_migration_target
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffff8000103302b0)
Location: mm/hugetlb.c:931
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
  - mm/hugetlb.c:alloc_pool_huge_page
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c000000000408e98)
Location: mm/hugetlb.c:931
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
  - mm/hugetlb.c:alloc_pool_huge_page
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
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:931
Inline: True
```
</details>
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
In mm/hugetlb.c (ffffffff8128af7a)
Location: mm/hugetlb.c:931
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
  - mm/hugetlb.c:alloc_pool_huge_page
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
In mm/hugetlb.c (ffffffff8127cdaa)
Location: mm/hugetlb.c:931
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
  - mm/hugetlb.c:alloc_pool_huge_page
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
In mm/hugetlb.c (ffffffff81288d8a)
Location: mm/hugetlb.c:931
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
  - mm/hugetlb.c:alloc_pool_huge_page
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
In mm/hugetlb.c (ffffffff81298b31)
Location: mm/hugetlb.c:931
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
  - mm/hugetlb.c:alloc_pool_huge_page
```
</details>
</li>
</ul>

## Differences
