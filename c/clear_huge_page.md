# Function: <code>clear_huge_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void clear_huge_page(struct page *page, long unsigned int addr, unsigned int pages_per_huge_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811c2040)
Location: mm/memory.c:3828
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff811c2040-ffffffff811c220d: clear_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void clear_huge_page(struct page *page, long unsigned int addr, unsigned int pages_per_huge_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811ddb80)
Location: mm/memory.c:4023
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff811ddb80-ffffffff811ddd39: clear_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void clear_huge_page(struct page *page, long unsigned int addr, unsigned int pages_per_huge_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811ed9d0)
Location: mm/memory.c:4104
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff811ed9d0-ffffffff811edb5b: clear_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void clear_huge_page(struct page *page, long unsigned int addr, unsigned int pages_per_huge_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f8980)
Location: mm/memory.c:4394
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff811f8980-ffffffff811f8acd: clear_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void clear_huge_page(struct page *page, long unsigned int addr_hint, unsigned int pages_per_huge_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81210b90)
Location: mm/memory.c:4570
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff81210b90-ffffffff81210e15: clear_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void clear_huge_page(struct page *page, long unsigned int addr_hint, unsigned int pages_per_huge_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81231560)
Location: mm/memory.c:4677
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff81231560-ffffffff81231760: clear_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void clear_huge_page(struct page *page, long unsigned int addr_hint, unsigned int pages_per_huge_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81244d30)
Location: mm/memory.c:4467
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff81244d30-ffffffff81244f33: clear_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void clear_huge_page(struct page *page, long unsigned int addr_hint, unsigned int pages_per_huge_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81256cf0)
Location: mm/memory.c:4522
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff81256cf0-ffffffff81256f0c: clear_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void clear_huge_page(struct page *page, long unsigned int addr_hint, unsigned int pages_per_huge_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81265280)
Location: mm/memory.c:4547
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff81265280-ffffffff8126549c: clear_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void clear_huge_page(struct page *page, long unsigned int addr_hint, unsigned int pages_per_huge_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81295650)
Location: mm/memory.c:4912
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff81295650-ffffffff8129588f: clear_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void clear_huge_page(struct page *page, long unsigned int addr_hint, unsigned int pages_per_huge_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a0540)
Location: mm/memory.c:5139
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff812a0540-ffffffff812a071b: clear_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void clear_huge_page(struct page *page, long unsigned int addr_hint, unsigned int pages_per_huge_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a5e80)
Location: mm/memory.c:5206
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff812a5e80-ffffffff812a605c: clear_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void clear_huge_page(struct page *page, long unsigned int addr_hint, unsigned int pages_per_huge_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e7300)
Location: mm/memory.c:5352
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff812e7300-ffffffff812e74ec: clear_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void clear_huge_page(struct page *page, long unsigned int addr_hint, unsigned int pages_per_huge_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813485b0)
Location: mm/memory.c:5651
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff813485b0-ffffffff8134879d: clear_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void clear_huge_page(struct page *page, long unsigned int addr_hint, unsigned int pages_per_huge_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813c0ac0)
Location: mm/memory.c:5731
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff813c0ac0-ffffffff813c0c74: clear_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void clear_huge_page(struct page *page, long unsigned int addr_hint, unsigned int pages_per_huge_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813f5840)
Location: mm/memory.c:5947
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff813f5840-ffffffff813f59ff: clear_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void clear_huge_page(struct page *page, long unsigned int addr_hint, unsigned int pages_per_huge_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8141f520)
Location: mm/memory.c:6171
Inline: False
Direct callers:
  - mm/memory.c:alloc_anon_folio
  - mm/hugetlb.c:hugetlb_no_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff8141f520-ffffffff8141f6df: clear_huge_page (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void clear_huge_page(struct page *page, long unsigned int addr_hint, unsigned int pages_per_huge_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102fbcc8)
Location: mm/memory.c:4547
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffff8000102fbcc8-ffff8000102fbec8: clear_huge_page (STB_GLOBAL)
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
void clear_huge_page(struct page *page, long unsigned int addr_hint, unsigned int pages_per_huge_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c7260)
Location: mm/memory.c:4547
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
c0000000003c7260-c0000000003c7568: clear_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void clear_huge_page(struct page *page, long unsigned int addr_hint, unsigned int pages_per_huge_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe00020b2a6)
Location: mm/memory.c:4547
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_no_page
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffe00020b2a6-ffffffe00020b4c2: clear_huge_page (STB_GLOBAL)
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
void clear_huge_page(struct page *page, long unsigned int addr_hint, unsigned int pages_per_huge_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125d8d0)
Location: mm/memory.c:4547
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff8125d8d0-ffffffff8125daec: clear_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void clear_huge_page(struct page *page, long unsigned int addr_hint, unsigned int pages_per_huge_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124fd20)
Location: mm/memory.c:4547
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff8124fd20-ffffffff8124ff3c: clear_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void clear_huge_page(struct page *page, long unsigned int addr_hint, unsigned int pages_per_huge_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125b670)
Location: mm/memory.c:4547
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff8125b670-ffffffff8125b88c: clear_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void clear_huge_page(struct page *page, long unsigned int addr_hint, unsigned int pages_per_huge_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8126b050)
Location: mm/memory.c:4547
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff8126b050-ffffffff8126b254: clear_huge_page (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int addr_hint</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int addr</code>
</li>
</ul>
</details>
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
