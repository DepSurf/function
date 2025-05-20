# Function: <code>pfn_pmd</code>

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
In mm/migrate.c (ffffffff811f33af)
Location: arch/x86/include/asm/pgtable.h:360
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff811f4389)
Location: arch/x86/include/asm/pgtable.h:360
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
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
In mm/memory.c (ffffffff811da2ee)
Location: arch/x86/include/asm/pgtable.h:389
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/migrate.c (ffffffff812131a3)
Location: arch/x86/include/asm/pgtable.h:389
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff81216e11)
Location: arch/x86/include/asm/pgtable.h:389
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8121a706)
Location: arch/x86/include/asm/pgtable.h:389
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
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
In mm/memory.c (ffffffff811e9e16)
Location: arch/x86/include/asm/pgtable.h:389
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/migrate.c (ffffffff8122550b)
Location: arch/x86/include/asm/pgtable.h:389
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812293bb)
Location: arch/x86/include/asm/pgtable.h:389
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8122eb14)
Location: arch/x86/include/asm/pgtable.h:389
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/dax.c (ffffffff8129ceff)
Location: arch/x86/include/asm/pgtable.h:389
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
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
In mm/memory.c (ffffffff811f4f18)
Location: arch/x86/include/asm/pgtable.h:520
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/migrate.c (ffffffff81230be1)
Location: arch/x86/include/asm/pgtable.h:520
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812351e1)
Location: arch/x86/include/asm/pgtable.h:520
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812387e7)
Location: arch/x86/include/asm/pgtable.h:520
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff812abcfc)
Location: arch/x86/include/asm/pgtable.h:520
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
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
In mm/memory.c (ffffffff8120d012)
Location: arch/x86/include/asm/pgtable.h:535
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/migrate.c (ffffffff8124e960)
Location: arch/x86/include/asm/pgtable.h:535
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff81255c3d)
Location: arch/x86/include/asm/pgtable.h:535
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81259c4c)
Location: arch/x86/include/asm/pgtable.h:535
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/dax.c (ffffffff812cf5a7)
Location: arch/x86/include/asm/pgtable.h:535
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
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
In arch/x86/mm/pageattr.c (ffffffff8107798f)
Location: arch/x86/include/asm/pgtable.h:554
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
```
```
In arch/x86/mm/kmmio.c (ffffffff8107fe65)
Location: arch/x86/include/asm/pgtable.h:554
Inline: True
```
```
In mm/memory.c (ffffffff8122dbbc)
Location: arch/x86/include/asm/pgtable.h:554
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/pgtable-generic.c (ffffffff8123d933)
Location: arch/x86/include/asm/pgtable.h:554
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/migrate.c (ffffffff8127277c)
Location: arch/x86/include/asm/pgtable.h:554
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff81279acb)
Location: arch/x86/include/asm/pgtable.h:554
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8127c5b2)
Location: arch/x86/include/asm/pgtable.h:554
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff812f9744)
Location: arch/x86/include/asm/pgtable.h:554
Inline: True
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
In arch/x86/mm/pageattr.c (ffffffff8107e13f)
Location: arch/x86/include/asm/pgtable.h:556
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
```
```
In arch/x86/mm/kmmio.c (ffffffff810869a5)
Location: arch/x86/include/asm/pgtable.h:556
Inline: True
```
```
In mm/memory.c (ffffffff8124133f)
Location: arch/x86/include/asm/pgtable.h:556
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/pgtable-generic.c (ffffffff81251ee3)
Location: arch/x86/include/asm/pgtable.h:556
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/migrate.c (ffffffff81286d59)
Location: arch/x86/include/asm/pgtable.h:556
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff8128e0ab)
Location: arch/x86/include/asm/pgtable.h:556
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81290c65)
Location: arch/x86/include/asm/pgtable.h:556
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff8130e1f7)
Location: arch/x86/include/asm/pgtable.h:556
Inline: True
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
In arch/x86/mm/pageattr.c (ffffffff81081a3f)
Location: arch/x86/include/asm/pgtable.h:573
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a5bc)
Location: arch/x86/include/asm/pgtable.h:573
Inline: True
```
```
In mm/memory.c (ffffffff81253803)
Location: arch/x86/include/asm/pgtable.h:573
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/pgtable-generic.c (ffffffff812641c4)
Location: arch/x86/include/asm/pgtable.h:573
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/migrate.c (ffffffff812a12d4)
Location: arch/x86/include/asm/pgtable.h:573
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812a8a2d)
Location: arch/x86/include/asm/pgtable.h:573
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812aba4b)
Location: arch/x86/include/asm/pgtable.h:573
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff813346fa)
Location: arch/x86/include/asm/pgtable.h:573
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
In arch/x86/mm/pageattr.c (ffffffff81082aff)
Location: arch/x86/include/asm/pgtable.h:573
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
```
```
In arch/x86/mm/kmmio.c (ffffffff8108b22c)
Location: arch/x86/include/asm/pgtable.h:573
Inline: True
```
```
In mm/memory.c (ffffffff81261d63)
Location: arch/x86/include/asm/pgtable.h:573
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/pgtable-generic.c (ffffffff81272a34)
Location: arch/x86/include/asm/pgtable.h:573
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/migrate.c (ffffffff812b26f4)
Location: arch/x86/include/asm/pgtable.h:573
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812b9fad)
Location: arch/x86/include/asm/pgtable.h:573
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812bd25f)
Location: arch/x86/include/asm/pgtable.h:573
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff813482ca)
Location: arch/x86/include/asm/pgtable.h:573
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
In arch/x86/mm/pat/set_memory.c (ffffffff8108c21e)
Location: arch/x86/include/asm/pgtable.h:612
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
```
```
In arch/x86/mm/kmmio.c (ffffffff810924cf)
Location: arch/x86/include/asm/pgtable.h:612
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pmd_presence
```
```
In mm/memory.c (ffffffff8128c7e5)
Location: arch/x86/include/asm/pgtable.h:612
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
```
```
In mm/pgtable-generic.c (ffffffff812a37f6)
Location: arch/x86/include/asm/pgtable.h:612
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/migrate.c (ffffffff812e7c94)
Location: arch/x86/include/asm/pgtable.h:612
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812eeb8a)
Location: arch/x86/include/asm/pgtable.h:612
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812f2972)
Location: arch/x86/include/asm/pgtable.h:612
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff8138ed4a)
Location: arch/x86/include/asm/pgtable.h:612
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
In arch/x86/mm/pat/set_memory.c (ffffffff8108c4be)
Location: arch/x86/include/asm/pgtable.h:611
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
```
```
In arch/x86/mm/kmmio.c (ffffffff81091b70)
Location: arch/x86/include/asm/pgtable.h:611
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pmd_presence
```
```
In mm/memory.c (ffffffff81297a8d)
Location: arch/x86/include/asm/pgtable.h:611
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
```
```
In mm/pgtable-generic.c (ffffffff812af0d6)
Location: arch/x86/include/asm/pgtable.h:611
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/migrate.c (ffffffff812f3074)
Location: arch/x86/include/asm/pgtable.h:611
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812fa1ea)
Location: arch/x86/include/asm/pgtable.h:611
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812fcfa0)
Location: arch/x86/include/asm/pgtable.h:611
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff813a042e)
Location: arch/x86/include/asm/pgtable.h:611
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
In arch/x86/mm/pat/set_memory.c (ffffffff8108ceed)
Location: arch/x86/include/asm/pgtable.h:611
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
```
```
In arch/x86/mm/kmmio.c (ffffffff810926ad)
Location: arch/x86/include/asm/pgtable.h:611
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pmd_presence
```
```
In mm/memory.c (ffffffff812a182d)
Location: arch/x86/include/asm/pgtable.h:611
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
```
```
In mm/pgtable-generic.c (ffffffff812b4183)
Location: arch/x86/include/asm/pgtable.h:611
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_mkinvalid
```
```
In mm/migrate.c (ffffffff812f9406)
Location: arch/x86/include/asm/pgtable.h:611
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff81300fa6)
Location: arch/x86/include/asm/pgtable.h:611
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81303d12)
Location: arch/x86/include/asm/pgtable.h:611
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff813a6b1b)
Location: arch/x86/include/asm/pgtable.h:611
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
In arch/x86/mm/pat/set_memory.c (ffffffff8109c779)
Location: arch/x86/include/asm/pgtable.h:582
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
```
```
In arch/x86/mm/kmmio.c (ffffffff810a23cd)
Location: arch/x86/include/asm/pgtable.h:582
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pmd_presence
```
```
In mm/memory.c (ffffffff812e280c)
Location: arch/x86/include/asm/pgtable.h:582
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
```
```
In mm/pgtable-generic.c (ffffffff812f5d63)
Location: arch/x86/include/asm/pgtable.h:582
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_mkinvalid
```
```
In mm/huge_memory.c (ffffffff8134ac16)
Location: arch/x86/include/asm/pgtable.h:582
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8134da6c)
Location: arch/x86/include/asm/pgtable.h:582
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff813f65ab)
Location: arch/x86/include/asm/pgtable.h:582
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
In arch/x86/mm/pgtable.c (ffffffff810ad5ce)
Location: arch/x86/include/asm/pgtable.h:585
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_invalidate_ad
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810aff2c)
Location: arch/x86/include/asm/pgtable.h:585
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
```
```
In arch/x86/mm/kmmio.c (ffffffff810b6a51)
Location: arch/x86/include/asm/pgtable.h:585
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
```
In mm/memory.c (ffffffff81343014)
Location: arch/x86/include/asm/pgtable.h:585
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
```
```
In mm/pgtable-generic.c (ffffffff81359c93)
Location: arch/x86/include/asm/pgtable.h:585
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_mkinvalid
```
```
In mm/huge_memory.c (ffffffff813c1daf)
Location: arch/x86/include/asm/pgtable.h:585
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff813c6cb5)
Location: arch/x86/include/asm/pgtable.h:585
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff81468c9c)
Location: arch/x86/include/asm/pgtable.h:585
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
In arch/x86/mm/init_64.c (ffffffff820c6398)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/pgtable.c (ffffffff810c7711)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_invalidate_ad
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810ca5ae)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
```
```
In arch/x86/mm/kmmio.c (ffffffff810d1c9b)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
```
In mm/memory.c (ffffffff813bafb6)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
```
```
In mm/pgtable-generic.c (ffffffff813d4666)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_mkinvalid
```
```
In mm/huge_memory.c (ffffffff81443f90)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8144910b)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff814f9839)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - fs/dax.c:dax_pmd_load_hole
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
In arch/x86/mm/init_64.c (ffffffff8214a3e1)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/pgtable.c (ffffffff810cae71)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_invalidate_ad
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cdbee)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
```
```
In arch/x86/mm/kmmio.c (ffffffff810d514b)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
```
In mm/memory.c (ffffffff813efabc)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
```
```
In mm/pgtable-generic.c (ffffffff81409647)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/huge_memory.c (ffffffff81479511)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8147e8ef)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff81530cbc)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - fs/dax.c:dax_pmd_load_hole
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
In arch/x86/mm/init_64.c (ffffffff8222ce91)
Location: arch/x86/include/asm/pgtable.h:772
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/pgtable.c (ffffffff810d33c1)
Location: arch/x86/include/asm/pgtable.h:772
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_invalidate_ad
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d62ce)
Location: arch/x86/include/asm/pgtable.h:772
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
```
```
In arch/x86/mm/kmmio.c (ffffffff810dd853)
Location: arch/x86/include/asm/pgtable.h:772
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pmd_presence
```
```
In mm/memory.c (ffffffff8141b114)
Location: arch/x86/include/asm/pgtable.h:772
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
```
```
In mm/pgtable-generic.c (ffffffff81435e37)
Location: arch/x86/include/asm/pgtable.h:772
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/huge_memory.c (ffffffff814a8a91)
Location: arch/x86/include/asm/pgtable.h:772
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff814af583)
Location: arch/x86/include/asm/pgtable.h:772
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff81565b9c)
Location: arch/x86/include/asm/pgtable.h:772
Inline: True
Inline callers:
  - fs/dax.c:dax_pmd_load_hole
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
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
pmd_t pfn_pmd(long unsigned int pfn, pgprot_t pgprot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/book3s64/pgtable.c (c000000000090dc0)
Location: arch/powerpc/mm/book3s64/pgtable.c:128
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/pgtable.c:mk_pmd
Direct callers:
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
**Symbols:**

```
c000000000090d70-c000000000090dac: pfn_pmd (STB_GLOBAL)
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
In arch/riscv/mm/init.c (ffffffe000003840)
Location: arch/riscv/include/asm/pgtable-64.h:68
Inline: True
Inline callers:
  - arch/riscv/mm/init.c:create_pgd_mapping
  - arch/riscv/mm/init.c:create_pgd_mapping
  - arch/riscv/mm/init.c:setup_vm
  - arch/riscv/mm/init.c:setup_vm
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
In arch/x86/mm/pageattr.c (ffffffff81081aff)
Location: arch/x86/include/asm/pgtable.h:573
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a1ec)
Location: arch/x86/include/asm/pgtable.h:573
Inline: True
```
```
In mm/memory.c (ffffffff8125a3b3)
Location: arch/x86/include/asm/pgtable.h:573
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/pgtable-generic.c (ffffffff8126b084)
Location: arch/x86/include/asm/pgtable.h:573
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/migrate.c (ffffffff812aacd4)
Location: arch/x86/include/asm/pgtable.h:573
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812b258d)
Location: arch/x86/include/asm/pgtable.h:573
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812b583f)
Location: arch/x86/include/asm/pgtable.h:573
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff813408aa)
Location: arch/x86/include/asm/pgtable.h:573
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
In arch/x86/mm/pageattr.c (ffffffff810709b0)
Location: arch/x86/include/asm/pgtable.h:573
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
```
```
In arch/x86/mm/kmmio.c (ffffffff81078c59)
Location: arch/x86/include/asm/pgtable.h:573
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
```
In mm/memory.c (ffffffff8124c7d8)
Location: arch/x86/include/asm/pgtable.h:573
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/pgtable-generic.c (ffffffff8125d077)
Location: arch/x86/include/asm/pgtable.h:573
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/migrate.c (ffffffff8129c619)
Location: arch/x86/include/asm/pgtable.h:573
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812a3914)
Location: arch/x86/include/asm/pgtable.h:573
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812a6a43)
Location: arch/x86/include/asm/pgtable.h:573
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff81332fe8)
Location: arch/x86/include/asm/pgtable.h:573
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
In arch/x86/mm/pageattr.c (ffffffff81081aaf)
Location: arch/x86/include/asm/pgtable.h:573
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a19c)
Location: arch/x86/include/asm/pgtable.h:573
Inline: True
```
```
In mm/memory.c (ffffffff81258153)
Location: arch/x86/include/asm/pgtable.h:573
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/pgtable-generic.c (ffffffff81268e24)
Location: arch/x86/include/asm/pgtable.h:573
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/migrate.c (ffffffff812a8ae4)
Location: arch/x86/include/asm/pgtable.h:573
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812b039d)
Location: arch/x86/include/asm/pgtable.h:573
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812b364f)
Location: arch/x86/include/asm/pgtable.h:573
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff8133e37a)
Location: arch/x86/include/asm/pgtable.h:573
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
In arch/x86/mm/pageattr.c (ffffffff81083bcf)
Location: arch/x86/include/asm/pgtable.h:573
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
```
```
In arch/x86/mm/kmmio.c (ffffffff8108c43c)
Location: arch/x86/include/asm/pgtable.h:573
Inline: True
```
```
In mm/memory.c (ffffffff81267b3d)
Location: arch/x86/include/asm/pgtable.h:573
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/pgtable-generic.c (ffffffff812787b4)
Location: arch/x86/include/asm/pgtable.h:573
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/migrate.c (ffffffff812b8e04)
Location: arch/x86/include/asm/pgtable.h:573
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812c06dd)
Location: arch/x86/include/asm/pgtable.h:573
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812c3a9c)
Location: arch/x86/include/asm/pgtable.h:573
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff813526c0)
Location: arch/x86/include/asm/pgtable.h:573
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
