# Function: <code>follow_huge_pmd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct page *follow_huge_pmd(struct mm_struct *mm, long unsigned int address, pmd_t *pmd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811df790)
Location: mm/hugetlb.c:4337
Inline: False
Direct callers:
  - mm/gup.c:follow_page_mask
```
**Symbols:**

```
ffffffff811df790-ffffffff811df8f5: follow_huge_pmd (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct page *follow_huge_pmd(struct mm_struct *mm, long unsigned int address, pmd_t *pmd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811fde10)
Location: mm/hugetlb.c:4359
Inline: False
Direct callers:
  - mm/gup.c:follow_page_mask
```
**Symbols:**

```
ffffffff811fde10-ffffffff811fdfa2: follow_huge_pmd (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct page *follow_huge_pmd(struct mm_struct *mm, long unsigned int address, pmd_t *pmd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8120e900)
Location: mm/hugetlb.c:4472
Inline: False
Direct callers:
  - mm/gup.c:follow_page_mask
```
**Symbols:**

```
ffffffff8120e900-ffffffff8120ea84: follow_huge_pmd (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct page *follow_huge_pmd(struct mm_struct *mm, long unsigned int address, pmd_t *pmd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8121a2d0)
Location: mm/hugetlb.c:4648
Inline: False
```
**Symbols:**

```
ffffffff8121a2d0-ffffffff8121a411: follow_huge_pmd (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct page *follow_huge_pmd(struct mm_struct *mm, long unsigned int address, pmd_t *pmd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812353f0)
Location: mm/hugetlb.c:4728
Inline: False
Direct callers:
  - mm/gup.c:follow_pmd_mask
```
**Symbols:**

```
ffffffff812353f0-ffffffff81235568: follow_huge_pmd (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct page *follow_huge_pmd(struct mm_struct *mm, long unsigned int address, pmd_t *pmd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81258330)
Location: mm/hugetlb.c:4757
Inline: False
```
**Symbols:**

```
ffffffff81258330-ffffffff8125848b: follow_huge_pmd (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *follow_huge_pmd(struct mm_struct *mm, long unsigned int address, pmd_t *pmd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8126ca00)
Location: mm/hugetlb.c:4846
Inline: False
```
**Symbols:**

```
ffffffff8126ca00-ffffffff8126cb5b: follow_huge_pmd (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *follow_huge_pmd(struct mm_struct *mm, long unsigned int address, pmd_t *pmd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81287e20)
Location: mm/hugetlb.c:4951
Inline: False
```
**Symbols:**

```
ffffffff81287e20-ffffffff81287f82: follow_huge_pmd (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *follow_huge_pmd(struct mm_struct *mm, long unsigned int address, pmd_t *pmd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81297a20)
Location: mm/hugetlb.c:5068
Inline: False
```
**Symbols:**

```
ffffffff81297a20-ffffffff81297b82: follow_huge_pmd (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *follow_huge_pmd(struct mm_struct *mm, long unsigned int address, pmd_t *pmd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812cb0b0)
Location: mm/hugetlb.c:5551
Inline: False
```
**Symbols:**

```
ffffffff812cb0b0-ffffffff812cb224: follow_huge_pmd (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *follow_huge_pmd(struct mm_struct *mm, long unsigned int address, pmd_t *pmd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d6cc0)
Location: mm/hugetlb.c:5563
Inline: False
```
**Symbols:**

```
ffffffff812d6cc0-ffffffff812d6e32: follow_huge_pmd (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *follow_huge_pmd(struct mm_struct *mm, long unsigned int address, pmd_t *pmd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812ddef0)
Location: mm/hugetlb.c:5843
Inline: False
```
**Symbols:**

```
ffffffff812ddef0-ffffffff812de05c: follow_huge_pmd (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct page *follow_huge_pmd(struct mm_struct *mm, long unsigned int address, pmd_t *pmd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81325100)
Location: mm/hugetlb.c:6180
Inline: False
```
**Symbols:**

```
ffffffff81325100-ffffffff8132526c: follow_huge_pmd (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct page *follow_huge_pmd(struct mm_struct *mm, long unsigned int address, pmd_t *pmd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81393a50)
Location: mm/hugetlb.c:6907
Inline: False
```
**Symbols:**

```
ffffffff81393a50-ffffffff81393bbd: follow_huge_pmd (STB_WEAK)
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
struct page *follow_huge_pmd(struct mm_struct *mm, long unsigned int address, pmd_t *pmd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffff800010335d38)
Location: mm/hugetlb.c:5068
Inline: False
Direct callers:
  - mm/gup.c:follow_pmd_mask
```
**Symbols:**

```
ffff800010335d38-ffff800010335ea0: follow_huge_pmd (STB_WEAK)
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
struct page *follow_huge_pmd(struct mm_struct *mm, long unsigned int address, pmd_t *pmd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c0000000004103f0)
Location: mm/hugetlb.c:5068
Inline: False
Direct callers:
  - mm/gup.c:follow_pmd_mask
```
**Symbols:**

```
c0000000004103f0-c000000000410618: follow_huge_pmd (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct page *follow_huge_pmd(struct mm_struct *mm, long unsigned int address, pmd_t *pmd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffe000231e9e)
Location: mm/hugetlb.c:5068
Inline: False
```
**Symbols:**

```
ffffffe000231e9e-ffffffe000231fe4: follow_huge_pmd (STB_WEAK)
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
struct page *follow_huge_pmd(struct mm_struct *mm, long unsigned int address, pmd_t *pmd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81290000)
Location: mm/hugetlb.c:5068
Inline: False
```
**Symbols:**

```
ffffffff81290000-ffffffff81290162: follow_huge_pmd (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *follow_huge_pmd(struct mm_struct *mm, long unsigned int address, pmd_t *pmd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81281cb0)
Location: mm/hugetlb.c:5068
Inline: False
Direct callers:
  - mm/gup.c:follow_pmd_mask
```
**Symbols:**

```
ffffffff81281cb0-ffffffff81281e12: follow_huge_pmd (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *follow_huge_pmd(struct mm_struct *mm, long unsigned int address, pmd_t *pmd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128de10)
Location: mm/hugetlb.c:5068
Inline: False
```
**Symbols:**

```
ffffffff8128de10-ffffffff8128df72: follow_huge_pmd (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *follow_huge_pmd(struct mm_struct *mm, long unsigned int address, pmd_t *pmd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8129dbc0)
Location: mm/hugetlb.c:5068
Inline: False
```
**Symbols:**

```
ffffffff8129dbc0-ffffffff8129dd1f: follow_huge_pmd (STB_WEAK)
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
