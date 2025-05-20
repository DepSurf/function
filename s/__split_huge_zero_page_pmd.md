# Function: <code>__split_huge_zero_page_pmd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff811f8374)
Location: mm/huge_memory.c:2933
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8121641d)
Location: mm/huge_memory.c:1477
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812289d0)
Location: mm/huge_memory.c:1602
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81232036)
Location: mm/huge_memory.c:1924
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81252e69)
Location: mm/huge_memory.c:2036
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81277387)
Location: mm/huge_memory.c:2024
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81288b97)
Location: mm/huge_memory.c:2044
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a37fb)
Location: mm/huge_memory.c:2101
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b4cfb)
Location: mm/huge_memory.c:2106
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __split_huge_zero_page_pmd(struct vm_area_struct *vma, long unsigned int haddr, pmd_t *pmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812e8b60)
Location: mm/huge_memory.c:1979
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
**Symbols:**

```
ffffffff812e8b60-ffffffff812e8d13: __split_huge_zero_page_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __split_huge_zero_page_pmd(struct vm_area_struct *vma, long unsigned int haddr, pmd_t *pmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812f3fd0)
Location: mm/huge_memory.c:1994
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
**Symbols:**

```
ffffffff812f3fd0-ffffffff812f4181: __split_huge_zero_page_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __split_huge_zero_page_pmd(struct vm_area_struct *vma, long unsigned int haddr, pmd_t *pmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812fa290)
Location: mm/huge_memory.c:2001
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
**Symbols:**

```
ffffffff812fa290-ffffffff812fa43e: __split_huge_zero_page_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __split_huge_zero_page_pmd(struct vm_area_struct *vma, long unsigned int haddr, pmd_t *pmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff813440f0)
Location: mm/huge_memory.c:1924
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
**Symbols:**

```
ffffffff813440f0-ffffffff8134429e: __split_huge_zero_page_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __split_huge_zero_page_pmd(struct vm_area_struct *vma, long unsigned int haddr, pmd_t *pmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff813b9610)
Location: mm/huge_memory.c:1950
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
**Symbols:**

```
ffffffff813b9610-ffffffff813b97d1: __split_huge_zero_page_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __split_huge_zero_page_pmd(struct vm_area_struct *vma, long unsigned int haddr, pmd_t *pmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8143b8f0)
Location: mm/huge_memory.c:2044
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
**Symbols:**

```
ffffffff8143b8f0-ffffffff8143bac6: __split_huge_zero_page_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __split_huge_zero_page_pmd(struct vm_area_struct *vma, long unsigned int haddr, pmd_t *pmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81471250)
Location: mm/huge_memory.c:2033
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
**Symbols:**

```
ffffffff81471250-ffffffff8147142a: __split_huge_zero_page_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __split_huge_zero_page_pmd(struct vm_area_struct *vma, long unsigned int haddr, pmd_t *pmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff814a0de0)
Location: mm/huge_memory.c:2368
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
**Symbols:**

```
ffffffff814a0de0-ffffffff814a0ffc: __split_huge_zero_page_pmd (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffff800010356114)
Location: mm/huge_memory.c:2106
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (c00000000043c900)
Location: mm/huge_memory.c:2106
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ad2db)
Location: mm/huge_memory.c:2106
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8129e20d)
Location: mm/huge_memory.c:2106
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ab0eb)
Location: mm/huge_memory.c:2106
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812bb43b)
Location: mm/huge_memory.c:2106
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
