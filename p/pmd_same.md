# Function: <code>pmd_same</code>

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
In arch/x86/mm/pgtable.c (ffffffff81070f8d)
Location: include/asm-generic/pgtable.h:267
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_set_access_flags
```
```
In mm/migrate.c (ffffffff811f336c)
Location: include/asm-generic/pgtable.h:267
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff811f606d)
Location: include/asm-generic/pgtable.h:267
Inline: True
Inline callers:
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
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
In arch/x86/mm/pgtable.c (ffffffff81070ec6)
Location: include/asm-generic/pgtable.h:272
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_set_access_flags
```
```
In mm/migrate.c (ffffffff81213146)
Location: include/asm-generic/pgtable.h:272
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812151a3)
Location: include/asm-generic/pgtable.h:272
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
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
In arch/x86/mm/pgtable.c (ffffffff81074a46)
Location: include/asm-generic/pgtable.h:296
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_set_access_flags
```
```
In mm/migrate.c (ffffffff812254b2)
Location: include/asm-generic/pgtable.h:296
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812277af)
Location: include/asm-generic/pgtable.h:296
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
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
In arch/x86/mm/pgtable.c (ffffffff81073f96)
Location: include/asm-generic/pgtable.h:371
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_set_access_flags
```
```
In mm/migrate.c (ffffffff81230b90)
Location: include/asm-generic/pgtable.h:371
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff8123398f)
Location: include/asm-generic/pgtable.h:371
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
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
In arch/x86/mm/pgtable.c (ffffffff810799c6)
Location: include/asm-generic/pgtable.h:372
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_set_access_flags
```
```
In mm/migrate.c (ffffffff8124e916)
Location: include/asm-generic/pgtable.h:372
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812512a0)
Location: include/asm-generic/pgtable.h:372
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
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
In arch/x86/mm/pgtable.c (ffffffff8107c595)
Location: include/asm-generic/pgtable.h:379
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_set_access_flags
```
```
In mm/migrate.c (ffffffff81272728)
Location: include/asm-generic/pgtable.h:379
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff81275774)
Location: include/asm-generic/pgtable.h:379
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:huge_pmd_set_accessed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pmd_same(pmd_t pmd_a, pmd_t pmd_b);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107a7a2)
Location: include/asm-generic/pgtable.h:378
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/pgtable.c (ffffffff81082f85)
Location: include/asm-generic/pgtable.h:378
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_set_access_flags
```
```
In mm/migrate.c (ffffffff81286d07)
Location: include/asm-generic/pgtable.h:378
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff8128a6d4)
Location: include/asm-generic/pgtable.h:378
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:huge_pmd_set_accessed
```
**Symbols:**

```
ffffffff8107a7a2-ffffffff8107a7c5: pmd_same (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pmd_same(pmd_t pmd_a, pmd_t pmd_b);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107e4f9)
Location: include/asm-generic/pgtable.h:378
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/pgtable.c (ffffffff81086bf5)
Location: include/asm-generic/pgtable.h:378
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_set_access_flags
```
```
In mm/migrate.c (ffffffff812a1298)
Location: include/asm-generic/pgtable.h:378
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812a52f4)
Location: include/asm-generic/pgtable.h:378
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:huge_pmd_set_accessed
```
**Symbols:**

```
ffffffff8107e4f9-ffffffff8107e51c: pmd_same (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pmd_same(pmd_t pmd_a, pmd_t pmd_b);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107f589)
Location: include/asm-generic/pgtable.h:378
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/pgtable.c (ffffffff810878e5)
Location: include/asm-generic/pgtable.h:378
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_set_access_flags
```
```
In mm/migrate.c (ffffffff812b26b8)
Location: include/asm-generic/pgtable.h:378
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812b67b4)
Location: include/asm-generic/pgtable.h:378
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:huge_pmd_set_accessed
```
**Symbols:**

```
ffffffff8107f589-ffffffff8107f5ac: pmd_same (STB_LOCAL)
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
In arch/x86/mm/init_64.c (ffffffff81bc4530)
Location: include/linux/pgtable.h:537
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/pgtable.c (ffffffff81089d05)
Location: include/linux/pgtable.h:537
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_set_access_flags
```
```
In mm/migrate.c (ffffffff812e7c58)
Location: include/linux/pgtable.h:537
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812ecfeb)
Location: include/linux/pgtable.h:537
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
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
In arch/x86/mm/init_64.c (ffffffff81c3d429)
Location: include/linux/pgtable.h:592
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/pgtable.c (ffffffff81089f89)
Location: include/linux/pgtable.h:592
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_set_access_flags
```
```
In mm/migrate.c (ffffffff812f3038)
Location: include/linux/pgtable.h:592
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812f825d)
Location: include/linux/pgtable.h:592
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
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
In arch/x86/mm/init_64.c (ffffffff81c2f837)
Location: include/linux/pgtable.h:592
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/pgtable.c (ffffffff8108abe9)
Location: include/linux/pgtable.h:592
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_set_access_flags
```
```
In mm/migrate.c (ffffffff812f93c7)
Location: include/linux/pgtable.h:592
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812fe7de)
Location: include/linux/pgtable.h:592
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
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
In arch/x86/mm/init_64.c (ffffffff81d4df86)
Location: include/linux/pgtable.h:611
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/pgtable.c (ffffffff8109a189)
Location: include/linux/pgtable.h:611
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_set_access_flags
```
```
In mm/huge_memory.c (ffffffff81348380)
Location: include/linux/pgtable.h:611
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
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
In arch/x86/mm/init_64.c (ffffffff81f1dd2a)
Location: include/linux/pgtable.h:644
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/pgtable.c (ffffffff810ad289)
Location: include/linux/pgtable.h:644
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_set_access_flags
```
```
In mm/huge_memory.c (ffffffff813bcf1f)
Location: include/linux/pgtable.h:644
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
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
In arch/x86/mm/init_64.c (ffffffff820c62a9)
Location: include/linux/pgtable.h:680
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/pgtable.c (ffffffff810c7354)
Location: include/linux/pgtable.h:680
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_set_access_flags
```
```
In mm/huge_memory.c (ffffffff8143f570)
Location: include/linux/pgtable.h:680
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
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
In arch/x86/mm/init_64.c (ffffffff8214a2f7)
Location: include/linux/pgtable.h:692
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/pgtable.c (ffffffff810caaa4)
Location: include/linux/pgtable.h:692
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_set_access_flags
```
```
In mm/pgtable-generic.c (ffffffff81409ac7)
Location: include/linux/pgtable.h:692
Inline: True
Inline callers:
  - mm/pgtable-generic.c:__pte_offset_map_lock
```
```
In mm/huge_memory.c (ffffffff81475f77)
Location: include/linux/pgtable.h:692
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
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
In arch/x86/mm/init_64.c (ffffffff8222cda7)
Location: include/linux/pgtable.h:820
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/pgtable.c (ffffffff810d2ff4)
Location: include/linux/pgtable.h:820
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_set_access_flags
```
```
In mm/pgtable-generic.c (ffffffff814362e7)
Location: include/linux/pgtable.h:820
Inline: True
Inline callers:
  - mm/pgtable-generic.c:__pte_offset_map_lock
```
```
In mm/huge_memory.c (ffffffff814a496b)
Location: include/linux/pgtable.h:820
Inline: True
Inline callers:
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
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
In mm/migrate.c (0)
Location: include/asm-generic/pgtable.h:378
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/asm-generic/pgtable.h:378
Inline: True
```
</details>
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
In arch/powerpc/mm/book3s64/pgtable.c (c000000000090944)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1222
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/pgtable.c:pmdp_set_access_flags
```
```
In mm/migrate.c (c000000000439a98)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1222
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (c00000000043f524)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1222
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:huge_pmd_set_accessed
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
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pmd_same(pmd_t pmd_a, pmd_t pmd_b);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107e589)
Location: include/asm-generic/pgtable.h:378
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/pgtable.c (ffffffff810868e5)
Location: include/asm-generic/pgtable.h:378
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_set_access_flags
```
```
In mm/migrate.c (ffffffff812aac98)
Location: include/asm-generic/pgtable.h:378
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812aed94)
Location: include/asm-generic/pgtable.h:378
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:huge_pmd_set_accessed
```
**Symbols:**

```
ffffffff8107e589-ffffffff8107e5ac: pmd_same (STB_LOCAL)
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
In arch/x86/mm/init_64.c (0)
Location: include/asm-generic/pgtable.h:378
Inline: True
```
```
In arch/x86/mm/pgtable.c (0)
Location: include/asm-generic/pgtable.h:378
Inline: True
```
```
In mm/migrate.c (0)
Location: include/asm-generic/pgtable.h:378
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/asm-generic/pgtable.h:378
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pmd_same(pmd_t pmd_a, pmd_t pmd_b);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107e539)
Location: include/asm-generic/pgtable.h:378
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/pgtable.c (ffffffff81086895)
Location: include/asm-generic/pgtable.h:378
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_set_access_flags
```
```
In mm/migrate.c (ffffffff812a8aa8)
Location: include/asm-generic/pgtable.h:378
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812acba4)
Location: include/asm-generic/pgtable.h:378
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:huge_pmd_set_accessed
```
**Symbols:**

```
ffffffff8107e539-ffffffff8107e55c: pmd_same (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pmd_same(pmd_t pmd_a, pmd_t pmd_b);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81080629)
Location: include/asm-generic/pgtable.h:378
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/pgtable.c (ffffffff810889c5)
Location: include/asm-generic/pgtable.h:378
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_set_access_flags
```
```
In mm/migrate.c (ffffffff812b8dc8)
Location: include/asm-generic/pgtable.h:378
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812bcf24)
Location: include/asm-generic/pgtable.h:378
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:huge_pmd_set_accessed
```
**Symbols:**

```
ffffffff81080629-ffffffff8108064c: pmd_same (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
