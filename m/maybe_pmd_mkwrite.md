# Function: <code>maybe_pmd_mkwrite</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff811f57df)
Location: mm/huge_memory.c:699
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
Direct callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
**Symbols:**

```
ffffffff811f5aa0-ffffffff811f5ac2: maybe_pmd_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81216ffb)
Location: mm/huge_memory.c:445
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
Direct callers:
  - mm/memory.c:alloc_set_pte
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff812141d0-ffffffff812141f3: maybe_pmd_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812295ab)
Location: mm/huge_memory.c:475
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
Direct callers:
  - mm/memory.c:alloc_set_pte
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff81226610-ffffffff81226633: maybe_pmd_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81235355)
Location: mm/huge_memory.c:477
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
Direct callers:
  - mm/memory.c:alloc_set_pte
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff812324b0-ffffffff812324d4: maybe_pmd_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81255cee)
Location: mm/huge_memory.c:477
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
Direct callers:
  - mm/memory.c:alloc_set_pte
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff8124fb70-ffffffff8124fb8a: maybe_pmd_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81279b44)
Location: mm/huge_memory.c:477
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
Direct callers:
  - mm/memory.c:alloc_set_pte
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff812740d0-ffffffff812740ea: maybe_pmd_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8128e121)
Location: mm/huge_memory.c:487
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
Direct callers:
  - mm/memory.c:alloc_set_pte
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff81289100-ffffffff8128911a: maybe_pmd_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a8b63)
Location: mm/huge_memory.c:492
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
Direct callers:
  - mm/memory.c:alloc_set_pte
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff812a3db0-ffffffff812a3dca: maybe_pmd_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ba0e3)
Location: mm/huge_memory.c:484
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
Direct callers:
  - mm/memory.c:alloc_set_pte
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff812b52b0-ffffffff812b52ca: maybe_pmd_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812eecc2)
Location: mm/huge_memory.c:484
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
Direct callers:
  - mm/memory.c:do_set_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff812ea750-ffffffff812ea76a: maybe_pmd_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812fa312)
Location: mm/huge_memory.c:477
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
Direct callers:
  - mm/memory.c:do_set_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff812f5bb0-ffffffff812f5bca: maybe_pmd_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff813010e1)
Location: mm/huge_memory.c:494
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
Direct callers:
  - mm/memory.c:do_set_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff812fbf90-ffffffff812fbfaa: maybe_pmd_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8134ad51)
Location: mm/huge_memory.c:494
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
Direct callers:
  - mm/memory.c:do_set_pmd
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff81345de0-ffffffff81345dfa: maybe_pmd_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff813c1fed)
Location: mm/huge_memory.c:493
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
Direct callers:
  - mm/memory.c:do_set_pmd
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff813bbfe0-ffffffff813bc002: maybe_pmd_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff814442bd)
Location: mm/huge_memory.c:554
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
Direct callers:
  - mm/memory.c:do_set_pmd
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff8143e560-ffffffff8143e582: maybe_pmd_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81476f85)
Location: mm/huge_memory.c:551
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
Direct callers:
  - mm/memory.c:do_set_pmd
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff81473d40-ffffffff81473d62: maybe_pmd_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff814a6675)
Location: mm/huge_memory.c:762
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
Direct callers:
  - mm/memory.c:do_set_pmd
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff814a3240-ffffffff814a326a: maybe_pmd_mkwrite (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffff800010358a78)
Location: mm/huge_memory.c:484
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
Direct callers:
  - mm/memory.c:alloc_set_pte
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffff8000103567d0-ffff80001035680c: maybe_pmd_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (c000000000444560)
Location: mm/huge_memory.c:484
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
Direct callers:
  - mm/memory.c:alloc_set_pte
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
c00000000043db30-c00000000043db50: maybe_pmd_mkwrite (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b26c3)
Location: mm/huge_memory.c:484
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
Direct callers:
  - mm/memory.c:alloc_set_pte
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff812ad890-ffffffff812ad8aa: maybe_pmd_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a3a42)
Location: mm/huge_memory.c:484
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
Direct callers:
  - mm/memory.c:alloc_set_pte
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff8129ef10-ffffffff8129ef2a: maybe_pmd_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b04d3)
Location: mm/huge_memory.c:484
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
Direct callers:
  - mm/memory.c:alloc_set_pte
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff812ab6a0-ffffffff812ab6ba: maybe_pmd_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812c0813)
Location: mm/huge_memory.c:484
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
Direct callers:
  - mm/memory.c:alloc_set_pte
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff812bba10-ffffffff812bba2a: maybe_pmd_mkwrite (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
