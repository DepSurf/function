# Function: <code>pmd_mkhuge</code>

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
In mm/migrate.c (ffffffff811f33e3)
Location: arch/x86/include/asm/pgtable.h:287
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff811f43d3)
Location: arch/x86/include/asm/pgtable.h:287
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
In mm/memory.c (ffffffff811da313)
Location: arch/x86/include/asm/pgtable.h:316
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/migrate.c (ffffffff812131c4)
Location: arch/x86/include/asm/pgtable.h:316
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff81216e36)
Location: arch/x86/include/asm/pgtable.h:316
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8121a72b)
Location: arch/x86/include/asm/pgtable.h:316
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
In mm/memory.c (ffffffff811e9e3b)
Location: arch/x86/include/asm/pgtable.h:316
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/migrate.c (ffffffff8122552c)
Location: arch/x86/include/asm/pgtable.h:316
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812293e0)
Location: arch/x86/include/asm/pgtable.h:316
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8122eb35)
Location: arch/x86/include/asm/pgtable.h:316
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/dax.c (ffffffff8129cf1b)
Location: arch/x86/include/asm/pgtable.h:316
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
In mm/memory.c (ffffffff811f4f34)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/migrate.c (ffffffff81230bfd)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812351fd)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81238803)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff812abd18)
Location: arch/x86/include/asm/pgtable.h:373
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
In mm/memory.c (ffffffff8120d034)
Location: arch/x86/include/asm/pgtable.h:388
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/pgtable.h:388
Inline: True
```
```
In mm/huge_memory.c (ffffffff8124f7c1)
Location: arch/x86/include/asm/pgtable.h:388
Inline: True
```
```
In mm/khugepaged.c (0)
Location: arch/x86/include/asm/pgtable.h:388
Inline: True
```
```
In fs/dax.c (ffffffff812cf5c4)
Location: arch/x86/include/asm/pgtable.h:388
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
In arch/x86/mm/pageattr.c (ffffffff810779d2)
Location: arch/x86/include/asm/pgtable.h:398
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
```
```
In mm/memory.c (ffffffff8122dbf5)
Location: arch/x86/include/asm/pgtable.h:398
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/pgtable.h:398
Inline: True
```
```
In mm/huge_memory.c (ffffffff812735ac)
Location: arch/x86/include/asm/pgtable.h:398
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In mm/khugepaged.c (0)
Location: arch/x86/include/asm/pgtable.h:398
Inline: True
```
```
In fs/dax.c (ffffffff812f9794)
Location: arch/x86/include/asm/pgtable.h:398
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
In arch/x86/mm/pageattr.c (ffffffff8107e182)
Location: arch/x86/include/asm/pgtable.h:400
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
```
```
In mm/memory.c (ffffffff81241378)
Location: arch/x86/include/asm/pgtable.h:400
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/pgtable.h:400
Inline: True
```
```
In mm/huge_memory.c (ffffffff81287cd3)
Location: arch/x86/include/asm/pgtable.h:400
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In mm/khugepaged.c (0)
Location: arch/x86/include/asm/pgtable.h:400
Inline: True
```
```
In fs/dax.c (ffffffff8130e235)
Location: arch/x86/include/asm/pgtable.h:400
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
In arch/x86/mm/pageattr.c (ffffffff81081a6f)
Location: arch/x86/include/asm/pgtable.h:417
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
```
```
In mm/memory.c (ffffffff8125383f)
Location: arch/x86/include/asm/pgtable.h:417
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/pgtable.h:417
Inline: True
```
```
In mm/huge_memory.c (ffffffff812a28aa)
Location: arch/x86/include/asm/pgtable.h:417
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In mm/khugepaged.c (0)
Location: arch/x86/include/asm/pgtable.h:417
Inline: True
```
```
In fs/dax.c (ffffffff81334734)
Location: arch/x86/include/asm/pgtable.h:417
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
In arch/x86/mm/pageattr.c (ffffffff81082b2f)
Location: arch/x86/include/asm/pgtable.h:417
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
```
```
In mm/memory.c (ffffffff81261d9f)
Location: arch/x86/include/asm/pgtable.h:417
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/pgtable.h:417
Inline: True
```
```
In mm/huge_memory.c (ffffffff812b3d9a)
Location: arch/x86/include/asm/pgtable.h:417
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In mm/khugepaged.c (0)
Location: arch/x86/include/asm/pgtable.h:417
Inline: True
```
```
In fs/dax.c (ffffffff81348304)
Location: arch/x86/include/asm/pgtable.h:417
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
In arch/x86/mm/pat/set_memory.c (ffffffff8108c24e)
Location: arch/x86/include/asm/pgtable.h:456
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
```
```
In mm/memory.c (ffffffff8128c831)
Location: arch/x86/include/asm/pgtable.h:456
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/pgtable.h:456
Inline: True
```
```
In mm/huge_memory.c (ffffffff812e9a91)
Location: arch/x86/include/asm/pgtable.h:456
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
```
```
In mm/khugepaged.c (0)
Location: arch/x86/include/asm/pgtable.h:456
Inline: True
```
```
In fs/dax.c (ffffffff8138ed84)
Location: arch/x86/include/asm/pgtable.h:456
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
In arch/x86/mm/pat/set_memory.c (ffffffff8108c4ee)
Location: arch/x86/include/asm/pgtable.h:455
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
```
```
In mm/memory.c (ffffffff81297ac3)
Location: arch/x86/include/asm/pgtable.h:455
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/pgtable.h:455
Inline: True
```
```
In mm/huge_memory.c (ffffffff812f5861)
Location: arch/x86/include/asm/pgtable.h:455
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
```
```
In mm/khugepaged.c (0)
Location: arch/x86/include/asm/pgtable.h:455
Inline: True
```
```
In fs/dax.c (ffffffff813a0476)
Location: arch/x86/include/asm/pgtable.h:455
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
In arch/x86/mm/pat/set_memory.c (ffffffff8108cf2a)
Location: arch/x86/include/asm/pgtable.h:455
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
```
```
In mm/memory.c (ffffffff812a1875)
Location: arch/x86/include/asm/pgtable.h:455
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/pgtable.h:455
Inline: True
```
```
In mm/huge_memory.c (ffffffff812fc2f1)
Location: arch/x86/include/asm/pgtable.h:455
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (0)
Location: arch/x86/include/asm/pgtable.h:455
Inline: True
```
```
In fs/dax.c (ffffffff813a6b3b)
Location: arch/x86/include/asm/pgtable.h:455
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
In arch/x86/mm/pat/set_memory.c (ffffffff8109c7b6)
Location: arch/x86/include/asm/pgtable.h:426
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
```
```
In mm/memory.c (ffffffff812e285f)
Location: arch/x86/include/asm/pgtable.h:426
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
```
```
In mm/huge_memory.c (ffffffff813447d2)
Location: arch/x86/include/asm/pgtable.h:426
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (0)
Location: arch/x86/include/asm/pgtable.h:426
Inline: True
```
```
In fs/dax.c (ffffffff813f65cb)
Location: arch/x86/include/asm/pgtable.h:426
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
In arch/x86/mm/pat/set_memory.c (ffffffff810aff5e)
Location: arch/x86/include/asm/pgtable.h:429
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
```
```
In mm/memory.c (ffffffff81343045)
Location: arch/x86/include/asm/pgtable.h:429
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
```
```
In mm/huge_memory.c (ffffffff813badf8)
Location: arch/x86/include/asm/pgtable.h:429
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (0)
Location: arch/x86/include/asm/pgtable.h:429
Inline: True
```
```
In fs/dax.c (ffffffff81468cc8)
Location: arch/x86/include/asm/pgtable.h:429
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
In arch/x86/mm/pat/set_memory.c (ffffffff810ca5e1)
Location: arch/x86/include/asm/pgtable.h:446
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
```
```
In mm/memory.c (ffffffff813bafe8)
Location: arch/x86/include/asm/pgtable.h:446
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
```
```
In mm/huge_memory.c (ffffffff81443fbe)
Location: arch/x86/include/asm/pgtable.h:446
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (0)
Location: arch/x86/include/asm/pgtable.h:446
Inline: True
```
```
In fs/dax.c (ffffffff814f9862)
Location: arch/x86/include/asm/pgtable.h:446
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
In arch/x86/mm/pat/set_memory.c (ffffffff810cdc12)
Location: arch/x86/include/asm/pgtable.h:447
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
```
```
In mm/memory.c (ffffffff813efaee)
Location: arch/x86/include/asm/pgtable.h:447
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
```
```
In mm/huge_memory.c (ffffffff8147954f)
Location: arch/x86/include/asm/pgtable.h:447
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8147e91c)
Location: arch/x86/include/asm/pgtable.h:447
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff81530ce6)
Location: arch/x86/include/asm/pgtable.h:447
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
In arch/x86/mm/pat/set_memory.c (ffffffff810d62f2)
Location: arch/x86/include/asm/pgtable.h:584
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
```
```
In mm/memory.c (ffffffff8141b145)
Location: arch/x86/include/asm/pgtable.h:584
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
```
```
In mm/huge_memory.c (ffffffff814a8acf)
Location: arch/x86/include/asm/pgtable.h:584
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff814af5b0)
Location: arch/x86/include/asm/pgtable.h:584
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff81565bc6)
Location: arch/x86/include/asm/pgtable.h:584
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
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c2564)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1229
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/migrate.c (c000000000439afc)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1229
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (c000000000444424)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1229
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (c000000000447a54)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1229
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (c0000000005145c0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1229
Inline: True
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In arch/x86/mm/pageattr.c (ffffffff81081b2f)
Location: arch/x86/include/asm/pgtable.h:417
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
```
```
In mm/memory.c (ffffffff8125a3ef)
Location: arch/x86/include/asm/pgtable.h:417
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/pgtable.h:417
Inline: True
```
```
In mm/huge_memory.c (ffffffff812ac37a)
Location: arch/x86/include/asm/pgtable.h:417
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In mm/khugepaged.c (0)
Location: arch/x86/include/asm/pgtable.h:417
Inline: True
```
```
In fs/dax.c (ffffffff813408e4)
Location: arch/x86/include/asm/pgtable.h:417
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
In arch/x86/mm/pageattr.c (ffffffff810709d5)
Location: arch/x86/include/asm/pgtable.h:417
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
```
```
In mm/memory.c (ffffffff8124c813)
Location: arch/x86/include/asm/pgtable.h:417
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/pgtable.h:417
Inline: True
```
```
In mm/huge_memory.c (ffffffff8129d787)
Location: arch/x86/include/asm/pgtable.h:417
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In mm/khugepaged.c (0)
Location: arch/x86/include/asm/pgtable.h:417
Inline: True
```
```
In fs/dax.c (ffffffff81333021)
Location: arch/x86/include/asm/pgtable.h:417
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
In arch/x86/mm/pageattr.c (ffffffff81081adf)
Location: arch/x86/include/asm/pgtable.h:417
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
```
```
In mm/memory.c (ffffffff8125818f)
Location: arch/x86/include/asm/pgtable.h:417
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/pgtable.h:417
Inline: True
```
```
In mm/huge_memory.c (ffffffff812aa18a)
Location: arch/x86/include/asm/pgtable.h:417
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In mm/khugepaged.c (0)
Location: arch/x86/include/asm/pgtable.h:417
Inline: True
```
```
In fs/dax.c (ffffffff8133e3b4)
Location: arch/x86/include/asm/pgtable.h:417
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
In arch/x86/mm/pageattr.c (ffffffff81083bff)
Location: arch/x86/include/asm/pgtable.h:417
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
```
```
In mm/memory.c (ffffffff81267b79)
Location: arch/x86/include/asm/pgtable.h:417
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/pgtable.h:417
Inline: True
```
```
In mm/huge_memory.c (ffffffff812ba4ab)
Location: arch/x86/include/asm/pgtable.h:417
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In mm/khugepaged.c (0)
Location: arch/x86/include/asm/pgtable.h:417
Inline: True
```
```
In fs/dax.c (ffffffff81352719)
Location: arch/x86/include/asm/pgtable.h:417
Inline: True
```
</details>
</li>
</ul>

## Differences
