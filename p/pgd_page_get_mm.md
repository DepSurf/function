# Function: <code>pgd_page_get_mm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct mm_struct *pgd_page_get_mm(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81070d80)
Location: arch/x86/mm/pgtable.c:111
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:sync_global_pgds
```
**Symbols:**

```
ffffffff81070d80-ffffffff81070d8f: pgd_page_get_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct mm_struct *pgd_page_get_mm(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81070c90)
Location: arch/x86/mm/pgtable.c:111
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:sync_global_pgds
```
**Symbols:**

```
ffffffff81070c90-ffffffff81070c9f: pgd_page_get_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct mm_struct *pgd_page_get_mm(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81074820)
Location: arch/x86/mm/pgtable.c:111
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:sync_global_pgds
```
**Symbols:**

```
ffffffff81074820-ffffffff8107482f: pgd_page_get_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct mm_struct *pgd_page_get_mm(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81073d70)
Location: arch/x86/mm/pgtable.c:119
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:sync_global_pgds
```
**Symbols:**

```
ffffffff81073d70-ffffffff81073d7f: pgd_page_get_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct mm_struct *pgd_page_get_mm(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81079760)
Location: arch/x86/mm/pgtable.c:120
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:sync_global_pgds
```
**Symbols:**

```
ffffffff81079760-ffffffff8107976f: pgd_page_get_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct mm_struct *pgd_page_get_mm(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8107c330)
Location: arch/x86/mm/pgtable.c:125
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
```
**Symbols:**

```
ffffffff8107c330-ffffffff8107c33f: pgd_page_get_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct mm_struct *pgd_page_get_mm(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81082cb0)
Location: arch/x86/mm/pgtable.c:127
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
```
**Symbols:**

```
ffffffff81082cb0-ffffffff81082cbf: pgd_page_get_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct mm_struct *pgd_page_get_mm(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810868e0)
Location: arch/x86/mm/pgtable.c:111
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
```
**Symbols:**

```
ffffffff810868e0-ffffffff810868ef: pgd_page_get_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct mm_struct *pgd_page_get_mm(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810875d0)
Location: arch/x86/mm/pgtable.c:111
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
```
**Symbols:**

```
ffffffff810875d0-ffffffff810875df: pgd_page_get_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct mm_struct *pgd_page_get_mm(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81089b10)
Location: arch/x86/mm/pgtable.c:118
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
```
**Symbols:**

```
ffffffff81089b10-ffffffff81089b1f: pgd_page_get_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct mm_struct *pgd_page_get_mm(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81089d90)
Location: arch/x86/mm/pgtable.c:118
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
```
**Symbols:**

```
ffffffff81089d90-ffffffff81089d9f: pgd_page_get_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct mm_struct *pgd_page_get_mm(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8108a9e0)
Location: arch/x86/mm/pgtable.c:118
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
```
**Symbols:**

```
ffffffff8108a9e0-ffffffff8108a9ef: pgd_page_get_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct mm_struct *pgd_page_get_mm(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81099f60)
Location: arch/x86/mm/pgtable.c:118
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
```
**Symbols:**

```
ffffffff81099f60-ffffffff81099f6f: pgd_page_get_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct mm_struct *pgd_page_get_mm(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810ad000)
Location: arch/x86/mm/pgtable.c:118
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
```
**Symbols:**

```
ffffffff810ad000-ffffffff810ad015: pgd_page_get_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct mm_struct *pgd_page_get_mm(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810c70e0)
Location: arch/x86/mm/pgtable.c:118
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
```
**Symbols:**

```
ffffffff810c70e0-ffffffff810c70f5: pgd_page_get_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct mm_struct *pgd_page_get_mm(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810ca830)
Location: arch/x86/mm/pgtable.c:118
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
```
**Symbols:**

```
ffffffff810ca830-ffffffff810ca845: pgd_page_get_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct mm_struct *pgd_page_get_mm(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810d2d80)
Location: arch/x86/mm/pgtable.c:121
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
```
**Symbols:**

```
ffffffff810d2d80-ffffffff810d2d95: pgd_page_get_mm (STB_GLOBAL)
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
In <code>ppc64el</code>: Absent ⚠️
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
struct mm_struct *pgd_page_get_mm(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810865d0)
Location: arch/x86/mm/pgtable.c:111
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
```
**Symbols:**

```
ffffffff810865d0-ffffffff810865df: pgd_page_get_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct mm_struct *pgd_page_get_mm(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810752f0)
Location: arch/x86/mm/pgtable.c:111
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
```
**Symbols:**

```
ffffffff810752f0-ffffffff810752ff: pgd_page_get_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct mm_struct *pgd_page_get_mm(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81086580)
Location: arch/x86/mm/pgtable.c:111
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
```
**Symbols:**

```
ffffffff81086580-ffffffff8108658f: pgd_page_get_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct mm_struct *pgd_page_get_mm(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810886c0)
Location: arch/x86/mm/pgtable.c:111
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
```
**Symbols:**

```
ffffffff810886c0-ffffffff810886cf: pgd_page_get_mm (STB_GLOBAL)
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
