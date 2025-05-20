# Function: <code>page_ref_unfreeze</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811b8948)
Location: include/linux/page_ref.h:172
Inline: True
Inline callers:
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/migrate.c (ffffffff81211b07)
Location: include/linux/page_ref.h:172
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff8121aec0)
Location: include/linux/page_ref.h:172
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
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
In mm/vmscan.c (ffffffff811c8f78)
Location: include/linux/page_ref.h:172
Inline: True
Inline callers:
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/migrate.c (ffffffff81223cd5)
Location: include/linux/page_ref.h:172
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff8122c830)
Location: include/linux/page_ref.h:172
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
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
In mm/vmscan.c (ffffffff811d2daa)
Location: include/linux/page_ref.h:172
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/migrate.c (ffffffff81230c7e)
Location: include/linux/page_ref.h:172
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff81239034)
Location: include/linux/page_ref.h:172
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
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
In mm/vmscan.c (ffffffff811e8011)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/migrate.c (ffffffff8124e9d4)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff81257736)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
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
In mm/vmscan.c (ffffffff812094b7)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/migrate.c (ffffffff8127280a)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff81278a2e)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff8127b89c)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
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
In mm/vmscan.c (ffffffff8121c199)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/migrate.c (ffffffff81286dc2)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff8128d0de)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff8128fcaa)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
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
In mm/vmscan.c (ffffffff8122bef0)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/ksm.c (ffffffff81292c08)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
```
```
In mm/migrate.c (ffffffff812a134f)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812a23c0)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/khugepaged.c (ffffffff812aad46)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
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
In mm/vmscan.c (ffffffff81239dba)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/ksm.c (ffffffff812a2988)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
```
```
In mm/migrate.c (ffffffff812b276f)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812b38bd)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/khugepaged.c (ffffffff812bc317)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
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
In mm/vmscan.c (ffffffff81266276)
Location: include/linux/page_ref.h:182
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/ksm.c (ffffffff812d7108)
Location: include/linux/page_ref.h:182
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
```
```
In mm/migrate.c (ffffffff812e7d0e)
Location: include/linux/page_ref.h:182
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812e8905)
Location: include/linux/page_ref.h:182
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page_tail
```
```
In mm/khugepaged.c (ffffffff812f1853)
Location: include/linux/page_ref.h:182
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
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
In mm/vmscan.c (ffffffff81270c72)
Location: include/linux/page_ref.h:182
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/migrate.c (ffffffff812f30fa)
Location: include/linux/page_ref.h:182
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812f3d20)
Location: include/linux/page_ref.h:182
Inline: True
```
```
In mm/khugepaged.c (ffffffff812fdda8)
Location: include/linux/page_ref.h:182
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
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
In mm/vmscan.c (ffffffff8127575b)
Location: include/linux/page_ref.h:182
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/migrate.c (ffffffff812f9493)
Location: include/linux/page_ref.h:182
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812fa180)
Location: include/linux/page_ref.h:182
Inline: True
```
```
In mm/khugepaged.c (ffffffff81304f17)
Location: include/linux/page_ref.h:182
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
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
In mm/vmscan.c (ffffffff812b4bea)
Location: include/linux/page_ref.h:182
Inline: True
Inline callers:
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/migrate.c (ffffffff81342a42)
Location: include/linux/page_ref.h:182
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff81343ea0)
Location: include/linux/page_ref.h:182
Inline: True
```
```
In mm/khugepaged.c (ffffffff8134ecaa)
Location: include/linux/page_ref.h:182
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
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
In mm/vmscan.c (ffffffff81313400)
Location: include/linux/page_ref.h:330
Inline: True
Inline callers:
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/migrate.c (ffffffff813b4f49)
Location: include/linux/page_ref.h:330
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff813b9bbf)
Location: include/linux/page_ref.h:330
Inline: True
```
```
In mm/khugepaged.c (ffffffff813c58dc)
Location: include/linux/page_ref.h:330
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
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
In mm/vmscan.c (ffffffff81386850)
Location: include/linux/page_ref.h:330
Inline: True
Inline callers:
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/hugetlb.c (ffffffff81412b65)
Location: include/linux/page_ref.h:330
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:__remove_hugetlb_folio
```
```
In mm/migrate.c (ffffffff814340d1)
Location: include/linux/page_ref.h:330
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff8143c667)
Location: include/linux/page_ref.h:330
Inline: True
```
```
In mm/khugepaged.c (ffffffff8144a23f)
Location: include/linux/page_ref.h:330
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
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
In mm/vmscan.c (ffffffff813b6ce0)
Location: include/linux/page_ref.h:330
Inline: True
Inline callers:
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/hugetlb.c (ffffffff8143e04b)
Location: include/linux/page_ref.h:330
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_free_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio_nodemask
  - mm/hugetlb.c:__remove_hugetlb_folio
  - mm/hugetlb.c:dequeue_hugetlb_folio_nodemask
```
```
In mm/migrate.c (ffffffff81469a11)
Location: include/linux/page_ref.h:330
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff81471cad)
Location: include/linux/page_ref.h:330
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
In mm/vmscan.c (ffffffff813dfba0)
Location: include/linux/page_ref.h:330
Inline: True
Inline callers:
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/hugetlb.c (ffffffff81477cdc)
Location: include/linux/page_ref.h:330
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_free_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio_nodemask
  - mm/hugetlb.c:__remove_hugetlb_folio
  - mm/hugetlb.c:dequeue_hugetlb_folio_nodemask
```
```
In mm/migrate.c (ffffffff81498982)
Location: include/linux/page_ref.h:330
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff814a243c)
Location: include/linux/page_ref.h:330
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
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
In mm/vmscan.c (ffff8000102caed8)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/ksm.c (ffff8000103423d8)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
```
```
In mm/migrate.c (ffff800010352fd0)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffff80001035494c)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/khugepaged.c (ffff80001035d490)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c04f5048)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/ksm.c (c0548130)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
```
```
In mm/migrate.c (c05526cc)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
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
In mm/vmscan.c (c00000000038783c)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/ksm.c (c00000000041fdc0)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
```
```
In mm/migrate.c (c000000000439b6c)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (c00000000043b95c)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/khugepaged.c (c000000000448f8c)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
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
In mm/vmscan.c (ffffffe0001e9ba2)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/ksm.c (ffffffe0002365f2)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
```
```
In mm/migrate.c (ffffffe00023f95e)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
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
In mm/vmscan.c (ffffffff8123240a)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/ksm.c (ffffffff8129af68)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
```
```
In mm/migrate.c (ffffffff812aad4f)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812abe9d)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/khugepaged.c (ffffffff812b48f7)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
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
In mm/vmscan.c (ffffffff812254b6)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/ksm.c (ffffffff8128cb28)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
```
```
In mm/migrate.c (ffffffff8129c689)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff8129da0d)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/khugepaged.c (ffffffff812a595a)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
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
In mm/vmscan.c (ffffffff812301aa)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/ksm.c (ffffffff81298d78)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
```
```
In mm/migrate.c (ffffffff812a8b5f)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812a9cad)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/khugepaged.c (ffffffff812b2707)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
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
In mm/vmscan.c (ffffffff8123f5f3)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/ksm.c (ffffffff812a8b58)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
```
```
In mm/migrate.c (ffffffff812b8e7f)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812b9f2d)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/khugepaged.c (ffffffff812c2ddc)
Location: include/linux/page_ref.h:173
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
</details>
</li>
</ul>

## Differences
