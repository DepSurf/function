# Function: <code>follow_huge_pgd</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct page *follow_huge_pgd(struct mm_struct *mm, long unsigned int address, pgd_t *pgd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8121a460)
Location: mm/hugetlb.c:4695
Inline: False
```
**Symbols:**

```
ffffffff8121a460-ffffffff8121a49d: follow_huge_pgd (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct page *follow_huge_pgd(struct mm_struct *mm, long unsigned int address, pgd_t *pgd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812355c0)
Location: mm/hugetlb.c:4775
Inline: False
```
**Symbols:**

```
ffffffff812355c0-ffffffff8123560f: follow_huge_pgd (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct page *follow_huge_pgd(struct mm_struct *mm, long unsigned int address, pgd_t *pgd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812584f0)
Location: mm/hugetlb.c:4804
Inline: False
```
**Symbols:**

```
ffffffff812584f0-ffffffff81258544: follow_huge_pgd (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *follow_huge_pgd(struct mm_struct *mm, long unsigned int address, pgd_t *pgd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8126cbc0)
Location: mm/hugetlb.c:4893
Inline: False
```
**Symbols:**

```
ffffffff8126cbc0-ffffffff8126cc14: follow_huge_pgd (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *follow_huge_pgd(struct mm_struct *mm, long unsigned int address, pgd_t *pgd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81287ff0)
Location: mm/hugetlb.c:4998
Inline: False
```
**Symbols:**

```
ffffffff81287ff0-ffffffff81288049: follow_huge_pgd (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *follow_huge_pgd(struct mm_struct *mm, long unsigned int address, pgd_t *pgd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81297bf0)
Location: mm/hugetlb.c:5115
Inline: False
```
**Symbols:**

```
ffffffff81297bf0-ffffffff81297c49: follow_huge_pgd (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *follow_huge_pgd(struct mm_struct *mm, long unsigned int address, pgd_t *pgd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812cb290)
Location: mm/hugetlb.c:5614
Inline: False
```
**Symbols:**

```
ffffffff812cb290-ffffffff812cb303: follow_huge_pgd (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *follow_huge_pgd(struct mm_struct *mm, long unsigned int address, pgd_t *pgd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d6ea0)
Location: mm/hugetlb.c:5626
Inline: False
```
**Symbols:**

```
ffffffff812d6ea0-ffffffff812d6f13: follow_huge_pgd (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *follow_huge_pgd(struct mm_struct *mm, long unsigned int address, pgd_t *pgd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812de0c0)
Location: mm/hugetlb.c:5906
Inline: False
```
**Symbols:**

```
ffffffff812de0c0-ffffffff812de12d: follow_huge_pgd (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct page *follow_huge_pgd(struct mm_struct *mm, long unsigned int address, pgd_t *pgd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:6243
Inline: False
```
**Symbols:**

```
ffffffff81cc03f1-ffffffff81cc040f: follow_huge_pgd.cold (STB_LOCAL)
ffffffff813252d0-ffffffff81325353: follow_huge_pgd (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct page *follow_huge_pgd(struct mm_struct *mm, long unsigned int address, pgd_t *pgd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:6972
Inline: False
```
**Symbols:**

```
ffffffff81e727f0-ffffffff81e7280e: follow_huge_pgd.cold (STB_LOCAL)
ffffffff81393c30-ffffffff81393ccb: follow_huge_pgd (STB_WEAK)
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
<summary>In <code>arm64</code>: ✅</summary>

```c
struct page *follow_huge_pgd(struct mm_struct *mm, long unsigned int address, pgd_t *pgd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffff800010335f08)
Location: mm/hugetlb.c:5115
Inline: False
```
**Symbols:**

```
ffff800010335f08-ffff800010335f70: follow_huge_pgd (STB_WEAK)
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
struct page *follow_huge_pgd(struct mm_struct *mm, long unsigned int address, pgd_t *pgd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c0000000004106a0)
Location: mm/hugetlb.c:5115
Inline: False
Direct callers:
  - mm/gup.c:follow_page_mask
```
**Symbols:**

```
c0000000004106a0-c000000000410728: follow_huge_pgd (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct page *follow_huge_pgd(struct mm_struct *mm, long unsigned int address, pgd_t *pgd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffe000232042)
Location: mm/hugetlb.c:5115
Inline: False
```
**Symbols:**

```
ffffffe000232042-ffffffe0002320a0: follow_huge_pgd (STB_WEAK)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct page *follow_huge_pgd(struct mm_struct *mm, long unsigned int address, pgd_t *pgd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812901d0)
Location: mm/hugetlb.c:5115
Inline: False
```
**Symbols:**

```
ffffffff812901d0-ffffffff81290229: follow_huge_pgd (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *follow_huge_pgd(struct mm_struct *mm, long unsigned int address, pgd_t *pgd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81281e70)
Location: mm/hugetlb.c:5115
Inline: False
```
**Symbols:**

```
ffffffff81281e70-ffffffff81281ebf: follow_huge_pgd (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *follow_huge_pgd(struct mm_struct *mm, long unsigned int address, pgd_t *pgd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128dfe0)
Location: mm/hugetlb.c:5115
Inline: False
```
**Symbols:**

```
ffffffff8128dfe0-ffffffff8128e039: follow_huge_pgd (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *follow_huge_pgd(struct mm_struct *mm, long unsigned int address, pgd_t *pgd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8129dd80)
Location: mm/hugetlb.c:5115
Inline: False
```
**Symbols:**

```
ffffffff8129dd80-ffffffff8129ddd9: follow_huge_pgd (STB_WEAK)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
