# Function: <code>migrate_misplaced_transhuge_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int migrate_misplaced_transhuge_page(struct mm_struct *mm, struct vm_area_struct *vma, pmd_t *pmd, pmd_t entry, long unsigned int address, struct page *page, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff811f3200)
Location: mm/migrate.c:1731
Inline: False
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff811f3200-ffffffff811f38c2: migrate_misplaced_transhuge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int migrate_misplaced_transhuge_page(struct mm_struct *mm, struct vm_area_struct *vma, pmd_t *pmd, pmd_t entry, long unsigned int address, struct page *page, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81212fa0)
Location: mm/migrate.c:1913
Inline: False
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff81212fa0-ffffffff81213813: migrate_misplaced_transhuge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int migrate_misplaced_transhuge_page(struct mm_struct *mm, struct vm_area_struct *vma, pmd_t *pmd, pmd_t entry, long unsigned int address, struct page *page, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81225310)
Location: mm/migrate.c:1922
Inline: False
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff81225310-ffffffff81225b78: migrate_misplaced_transhuge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int migrate_misplaced_transhuge_page(struct mm_struct *mm, struct vm_area_struct *vma, pmd_t *pmd, pmd_t entry, long unsigned int address, struct page *page, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81230a00)
Location: mm/migrate.c:1901
Inline: False
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff81230a00-ffffffff812310d2: migrate_misplaced_transhuge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int migrate_misplaced_transhuge_page(struct mm_struct *mm, struct vm_area_struct *vma, pmd_t *pmd, pmd_t entry, long unsigned int address, struct page *page, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8124e780)
Location: mm/migrate.c:1999
Inline: False
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff8124e780-ffffffff8124ef22: migrate_misplaced_transhuge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int migrate_misplaced_transhuge_page(struct mm_struct *mm, struct vm_area_struct *vma, pmd_t *pmd, pmd_t entry, long unsigned int address, struct page *page, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81272590)
Location: mm/migrate.c:2011
Inline: False
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff81272590-ffffffff81272d9a: migrate_misplaced_transhuge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int migrate_misplaced_transhuge_page(struct mm_struct *mm, struct vm_area_struct *vma, pmd_t *pmd, pmd_t entry, long unsigned int address, struct page *page, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81286ba0)
Location: mm/migrate.c:1996
Inline: False
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff81286ba0-ffffffff8128730d: migrate_misplaced_transhuge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int migrate_misplaced_transhuge_page(struct mm_struct *mm, struct vm_area_struct *vma, pmd_t *pmd, pmd_t entry, long unsigned int address, struct page *page, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/migrate.c (0)
Location: mm/migrate.c:1991
Inline: False
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff812a18be-ffffffff812a18d1: migrate_misplaced_transhuge_page.cold (STB_LOCAL)
ffffffff812a1140-ffffffff812a18be: migrate_misplaced_transhuge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int migrate_misplaced_transhuge_page(struct mm_struct *mm, struct vm_area_struct *vma, pmd_t *pmd, pmd_t entry, long unsigned int address, struct page *page, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812b2550)
Location: mm/migrate.c:2024
Inline: False
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff812b2550-ffffffff812b2ccc: migrate_misplaced_transhuge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int migrate_misplaced_transhuge_page(struct mm_struct *mm, struct vm_area_struct *vma, pmd_t *pmd, pmd_t entry, long unsigned int address, struct page *page, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812e7af0)
Location: mm/migrate.c:2031
Inline: False
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff812e7af0-ffffffff812e826d: migrate_misplaced_transhuge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int migrate_misplaced_transhuge_page(struct mm_struct *mm, struct vm_area_struct *vma, pmd_t *pmd, pmd_t entry, long unsigned int address, struct page *page, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812f2ec0)
Location: mm/migrate.c:2177
Inline: False
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff812f2ec0-ffffffff812f36c1: migrate_misplaced_transhuge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int migrate_misplaced_transhuge_page(struct mm_struct *mm, struct vm_area_struct *vma, pmd_t *pmd, pmd_t entry, long unsigned int address, struct page *page, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812f9260)
Location: mm/migrate.c:2150
Inline: False
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff812f9260-ffffffff812f99c1: migrate_misplaced_transhuge_page (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: ✅</summary>

```c
int migrate_misplaced_transhuge_page(struct mm_struct *mm, struct vm_area_struct *vma, pmd_t *pmd, pmd_t entry, long unsigned int address, struct page *page, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffff800010352d70)
Location: mm/migrate.c:2024
Inline: False
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffff800010352d70-ffff8000103535b8: migrate_misplaced_transhuge_page (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int migrate_misplaced_transhuge_page(struct mm_struct *mm, struct vm_area_struct *vma, pmd_t *pmd, pmd_t entry, long unsigned int address, struct page *page, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c0000000004398c0)
Location: mm/migrate.c:2024
Inline: False
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
c0000000004398c0-c00000000043a4d0: migrate_misplaced_transhuge_page (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int migrate_misplaced_transhuge_page(struct mm_struct *mm, struct vm_area_struct *vma, pmd_t *pmd, pmd_t entry, long unsigned int address, struct page *page, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812aab30)
Location: mm/migrate.c:2024
Inline: False
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff812aab30-ffffffff812ab2ac: migrate_misplaced_transhuge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int migrate_misplaced_transhuge_page(struct mm_struct *mm, struct vm_area_struct *vma, pmd_t *pmd, pmd_t entry, long unsigned int address, struct page *page, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8129c490)
Location: mm/migrate.c:2024
Inline: False
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff8129c490-ffffffff8129cba1: migrate_misplaced_transhuge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int migrate_misplaced_transhuge_page(struct mm_struct *mm, struct vm_area_struct *vma, pmd_t *pmd, pmd_t entry, long unsigned int address, struct page *page, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a8940)
Location: mm/migrate.c:2024
Inline: False
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff812a8940-ffffffff812a90bc: migrate_misplaced_transhuge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int migrate_misplaced_transhuge_page(struct mm_struct *mm, struct vm_area_struct *vma, pmd_t *pmd, pmd_t entry, long unsigned int address, struct page *page, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812b8c60)
Location: mm/migrate.c:2024
Inline: False
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff812b8c60-ffffffff812b93d6: migrate_misplaced_transhuge_page (STB_GLOBAL)
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
