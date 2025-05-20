# Function: <code>mem_map_next</code>

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
In mm/memory.c (ffffffff811c2115)
Location: mm/internal.h:339
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
```
```
In mm/hugetlb.c (ffffffff811da9ed)
Location: mm/internal.h:339
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:prep_compound_gigantic_page
```
```
In mm/migrate.c (ffffffff811f1b2a)
Location: mm/internal.h:339
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
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
In mm/memory.c (ffffffff811dde44)
Location: mm/internal.h:359
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
```
```
In mm/hugetlb.c (ffffffff811f9165)
Location: mm/internal.h:359
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/migrate.c (ffffffff812104f7)
Location: mm/internal.h:359
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
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
In mm/memory.c (ffffffff811edcf7)
Location: mm/internal.h:362
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
```
```
In mm/hugetlb.c (ffffffff81209d63)
Location: mm/internal.h:362
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/migrate.c (ffffffff8122262e)
Location: mm/internal.h:362
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
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
In mm/memory.c (ffffffff811f8c01)
Location: mm/internal.h:379
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
```
```
In mm/hugetlb.c (ffffffff81215302)
Location: mm/internal.h:379
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/migrate.c (ffffffff8122e4c4)
Location: mm/internal.h:379
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
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
In mm/memory.c (ffffffff81210f57)
Location: mm/internal.h:380
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
```
```
In mm/hugetlb.c (ffffffff8122fe45)
Location: mm/internal.h:380
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/migrate.c (ffffffff8124a718)
Location: mm/internal.h:380
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
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
In mm/memory.c (ffffffff8123194a)
Location: mm/internal.h:380
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
```
```
In mm/hugetlb.c (ffffffff812522c3)
Location: mm/internal.h:380
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/migrate.c (ffffffff8126da57)
Location: mm/internal.h:380
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
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
In mm/memory.c (ffffffff8124512a)
Location: mm/internal.h:380
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
```
```
In mm/hugetlb.c (ffffffff81266531)
Location: mm/internal.h:380
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/migrate.c (ffffffff8128205d)
Location: mm/internal.h:380
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
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
In mm/memory.c (ffffffff81257103)
Location: mm/internal.h:388
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
```
```
In mm/hugetlb.c (ffffffff812817cd)
Location: mm/internal.h:388
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/migrate.c (ffffffff8129e179)
Location: mm/internal.h:388
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
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
In mm/memory.c (ffffffff81265693)
Location: mm/internal.h:409
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
```
```
In mm/hugetlb.c (ffffffff81290b2d)
Location: mm/internal.h:409
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/migrate.c (ffffffff812ada29)
Location: mm/internal.h:409
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
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
In mm/memory.c (ffffffff81295a89)
Location: mm/internal.h:450
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
```
```
In mm/hugetlb.c (ffffffff812c3c71)
Location: mm/internal.h:450
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:destroy_compound_gigantic_page
  - mm/hugetlb.c:destroy_compound_gigantic_page
```
```
In mm/migrate.c (ffffffff812e24fb)
Location: mm/internal.h:450
Inline: True
Inline callers:
  - mm/migrate.c:__copy_gigantic_page
  - mm/migrate.c:__copy_gigantic_page
  - mm/migrate.c:__copy_gigantic_page
  - mm/migrate.c:__copy_gigantic_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory.c (ffffffff812a0b57)
Location: mm/internal.h:454
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
```
```
In mm/hugetlb.c (ffffffff812cf8ba)
Location: mm/internal.h:454
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
Direct callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/migrate.c (ffffffff812ed92b)
Location: mm/internal.h:454
Inline: True
Inline callers:
  - mm/migrate.c:__copy_gigantic_page
  - mm/migrate.c:__copy_gigantic_page
  - mm/migrate.c:__copy_gigantic_page
  - mm/migrate.c:__copy_gigantic_page
```
**Symbols:**

```
ffffffff812cf380-ffffffff812cf417: mem_map_next.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory.c (ffffffff812a6497)
Location: mm/internal.h:481
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
```
```
In mm/hugetlb.c (ffffffff812d610a)
Location: mm/internal.h:481
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
Direct callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/migrate.c (ffffffff812f4468)
Location: mm/internal.h:481
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
**Symbols:**

```
ffffffff812d6010-ffffffff812d60a7: mem_map_next.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory.c (ffffffff812e7957)
Location: mm/internal.h:477
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
```
```
In mm/hugetlb.c (ffffffff8131ca33)
Location: mm/internal.h:477
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
Direct callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
```
**Symbols:**

```
ffffffff81cbf1d2-ffffffff81cbf20c: mem_map_next.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory.c (ffffffff81348b0b)
Location: mm/internal.h:658
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
```
```
In mm/hugetlb.c (ffffffff813883c1)
Location: mm/internal.h:658
Inline: True
Inline callers:
  - mm/hugetlb.c:__prep_compound_gigantic_page
  - mm/hugetlb.c:__prep_compound_gigantic_page
  - mm/hugetlb.c:__prep_compound_gigantic_page
  - mm/hugetlb.c:__destroy_compound_gigantic_page
Direct callers:
  - mm/hugetlb.c:__prep_compound_gigantic_page
  - mm/hugetlb.c:__prep_compound_gigantic_page
  - mm/hugetlb.c:__prep_compound_gigantic_page
  - mm/hugetlb.c:__destroy_compound_gigantic_page
```
**Symbols:**

```
ffffffff81388190-ffffffff8138826a: mem_map_next.part.0 (STB_LOCAL)
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102fc0d0)
Location: mm/internal.h:409
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
```
```
In mm/hugetlb.c (ffff80001032e1bc)
Location: mm/internal.h:409
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/migrate.c (ffff80001034fa28)
Location: mm/internal.h:409
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
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
In mm/migrate.c (0)
Location: mm/internal.h:409
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
In mm/memory.c (c0000000003c7834)
Location: mm/internal.h:409
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
```
```
In mm/hugetlb.c (c000000000406bf8)
Location: mm/internal.h:409
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
```
```
In mm/migrate.c (c000000000432448)
Location: mm/internal.h:409
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
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
In mm/memory.c (ffffffe00020b612)
Location: mm/internal.h:409
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
```
```
In mm/hugetlb.c (ffffffe00022c416)
Location: mm/internal.h:409
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/migrate.c (ffffffe00023e7e6)
Location: mm/internal.h:409
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
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
In mm/memory.c (ffffffff8125dce3)
Location: mm/internal.h:409
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
```
```
In mm/hugetlb.c (ffffffff8128910d)
Location: mm/internal.h:409
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/migrate.c (ffffffff812a6009)
Location: mm/internal.h:409
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
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
In mm/memory.c (ffffffff81250133)
Location: mm/internal.h:409
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
```
```
In mm/hugetlb.c (ffffffff8127afad)
Location: mm/internal.h:409
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/migrate.c (ffffffff81297ab9)
Location: mm/internal.h:409
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
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
In mm/memory.c (ffffffff8125ba83)
Location: mm/internal.h:409
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
```
```
In mm/hugetlb.c (ffffffff81286f1d)
Location: mm/internal.h:409
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/migrate.c (ffffffff812a3e19)
Location: mm/internal.h:409
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
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
In mm/memory.c (ffffffff8126b455)
Location: mm/internal.h:409
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
```
```
In mm/hugetlb.c (ffffffff812975ed)
Location: mm/internal.h:409
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/migrate.c (ffffffff812b46df)
Location: mm/internal.h:409
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
</details>
</li>
</ul>

## Differences
