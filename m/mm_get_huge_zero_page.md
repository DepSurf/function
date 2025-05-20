# Function: <code>mm_get_huge_zero_page</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct page *mm_get_huge_zero_page(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81226410)
Location: mm/huge_memory.c:98
Inline: True
Direct callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - fs/dax.c:dax_iomap_pmd_fault
```
**Symbols:**

```
ffffffff81226410-ffffffff81226504: mm_get_huge_zero_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct page *mm_get_huge_zero_page(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812322e0)
Location: mm/huge_memory.c:101
Inline: True
Direct callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - fs/dax.c:dax_iomap_fault
```
**Symbols:**

```
ffffffff812322e0-ffffffff812323b0: mm_get_huge_zero_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct page *mm_get_huge_zero_page(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8124f9a0)
Location: mm/huge_memory.c:101
Inline: True
Direct callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - fs/dax.c:dax_iomap_fault
```
**Symbols:**

```
ffffffff8124f9a0-ffffffff8124fa70: mm_get_huge_zero_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct page *mm_get_huge_zero_page(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81273f00)
Location: mm/huge_memory.c:101
Inline: True
Direct callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff81273f00-ffffffff81273fcc: mm_get_huge_zero_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct page *mm_get_huge_zero_page(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81288f20)
Location: mm/huge_memory.c:111
Inline: True
Direct callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff81288f20-ffffffff81288ff4: mm_get_huge_zero_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct page *mm_get_huge_zero_page(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a3bd0)
Location: mm/huge_memory.c:116
Inline: True
Direct callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff812a3bd0-ffffffff812a3ca7: mm_get_huge_zero_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct page *mm_get_huge_zero_page(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b50d0)
Location: mm/huge_memory.c:116
Inline: True
Direct callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff812b50d0-ffffffff812b51a7: mm_get_huge_zero_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct page *mm_get_huge_zero_page(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ea620)
Location: mm/huge_memory.c:116
Inline: True
Direct callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff812ea620-ffffffff812ea66d: mm_get_huge_zero_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct page *mm_get_huge_zero_page(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812f5a80)
Location: mm/huge_memory.c:116
Inline: True
Direct callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff812f5a80-ffffffff812f5acd: mm_get_huge_zero_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct page *mm_get_huge_zero_page(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812fbdd0)
Location: mm/huge_memory.c:128
Inline: True
Direct callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff812fbdd0-ffffffff812fbead: mm_get_huge_zero_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct page *mm_get_huge_zero_page(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81345c00)
Location: mm/huge_memory.c:128
Inline: True
Direct callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff81345c00-ffffffff81345ce1: mm_get_huge_zero_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct page *mm_get_huge_zero_page(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff813bbd70)
Location: mm/huge_memory.c:127
Inline: True
Direct callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff813bbd70-ffffffff813bbeb1: mm_get_huge_zero_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct page *mm_get_huge_zero_page(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8143e2c0)
Location: mm/huge_memory.c:190
Inline: False
Direct callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - fs/dax.c:dax_pmd_load_hole
```
**Symbols:**

```
ffffffff8143e2c0-ffffffff8143e3ff: mm_get_huge_zero_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct page *mm_get_huge_zero_page(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81473ac0)
Location: mm/huge_memory.c:191
Inline: False
Direct callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - fs/dax.c:dax_pmd_load_hole
```
**Symbols:**

```
ffffffff81473ac0-ffffffff81473bd3: mm_get_huge_zero_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct page *mm_get_huge_zero_page(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff814a2fd0)
Location: mm/huge_memory.c:229
Inline: False
Direct callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - fs/dax.c:dax_pmd_load_hole
```
**Symbols:**

```
ffffffff814a2fd0-ffffffff814a30e0: mm_get_huge_zero_page (STB_GLOBAL)
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
struct page *mm_get_huge_zero_page(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffff8000103563e0)
Location: mm/huge_memory.c:116
Inline: True
Direct callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffff8000103563e0-ffff8000103565f0: mm_get_huge_zero_page (STB_GLOBAL)
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
struct page *mm_get_huge_zero_page(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (c00000000043d680)
Location: mm/huge_memory.c:116
Inline: True
Direct callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
c00000000043d680-c00000000043d938: mm_get_huge_zero_page (STB_GLOBAL)
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
struct page *mm_get_huge_zero_page(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ad6b0)
Location: mm/huge_memory.c:116
Inline: True
Direct callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff812ad6b0-ffffffff812ad787: mm_get_huge_zero_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct page *mm_get_huge_zero_page(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8129ed30)
Location: mm/huge_memory.c:116
Inline: True
Direct callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff8129ed30-ffffffff8129ee07: mm_get_huge_zero_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct page *mm_get_huge_zero_page(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ab4c0)
Location: mm/huge_memory.c:116
Inline: True
Direct callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff812ab4c0-ffffffff812ab597: mm_get_huge_zero_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct page *mm_get_huge_zero_page(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812bb810)
Location: mm/huge_memory.c:116
Inline: True
Direct callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff812bb810-ffffffff812bb910: mm_get_huge_zero_page (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
