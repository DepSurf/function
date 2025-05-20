# Function: <code>__collapse_huge_page_swapin</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff81219ae3)
Location: mm/khugepaged.c:871
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool __collapse_huge_page_swapin(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, pmd_t *pmd, int referenced);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8122bf60)
Location: mm/khugepaged.c:873
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff8122bf60-ffffffff8122c322: __collapse_huge_page_swapin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool __collapse_huge_page_swapin(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, pmd_t *pmd, int referenced);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff81237a90)
Location: mm/khugepaged.c:872
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff81237a90-ffffffff81237e8d: __collapse_huge_page_swapin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool __collapse_huge_page_swapin(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, pmd_t *pmd, int referenced);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff81256e20)
Location: mm/khugepaged.c:878
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff81256e20-ffffffff81257293: __collapse_huge_page_swapin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool __collapse_huge_page_swapin(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, pmd_t *pmd, int referenced);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8127adf0)
Location: mm/khugepaged.c:878
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff8127adf0-ffffffff8127b208: __collapse_huge_page_swapin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool __collapse_huge_page_swapin(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, pmd_t *pmd, int referenced);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8128f400)
Location: mm/khugepaged.c:878
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff8128f400-ffffffff8128f818: __collapse_huge_page_swapin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool __collapse_huge_page_swapin(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, pmd_t *pmd, int referenced);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812aa490)
Location: mm/khugepaged.c:878
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff812aa490-ffffffff812aa895: __collapse_huge_page_swapin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool __collapse_huge_page_swapin(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, pmd_t *pmd, int referenced);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812bba00)
Location: mm/khugepaged.c:890
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff812bba00-ffffffff812bbe05: __collapse_huge_page_swapin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool __collapse_huge_page_swapin(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, pmd_t *pmd, int referenced);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812f0ce0)
Location: mm/khugepaged.c:975
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff812f0ce0-ffffffff812f1093: __collapse_huge_page_swapin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool __collapse_huge_page_swapin(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, pmd_t *pmd, int referenced);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812fc3e0)
Location: mm/khugepaged.c:1002
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff812fc3e0-ffffffff812fc6e3: __collapse_huge_page_swapin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool __collapse_huge_page_swapin(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int haddr, pmd_t *pmd, int referenced);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff813028e0)
Location: mm/khugepaged.c:1000
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff813028e0-ffffffff81302b8b: __collapse_huge_page_swapin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool __collapse_huge_page_swapin(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int haddr, pmd_t *pmd, int referenced);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8134c8e0)
Location: mm/khugepaged.c:1004
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff8134c8e0-ffffffff8134cb82: __collapse_huge_page_swapin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool __collapse_huge_page_swapin(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int haddr, pmd_t *pmd, int referenced);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff813c62d0)
Location: mm/khugepaged.c:979
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff813c62d0-ffffffff813c65c4: __collapse_huge_page_swapin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __collapse_huge_page_swapin(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int haddr, pmd_t *pmd, int referenced);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff81446ed0)
Location: mm/khugepaged.c:905
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff81446ed0-ffffffff81447205: __collapse_huge_page_swapin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __collapse_huge_page_swapin(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int haddr, pmd_t *pmd, int referenced);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8147c650)
Location: mm/khugepaged.c:992
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff8147c650-ffffffff8147c8ec: __collapse_huge_page_swapin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __collapse_huge_page_swapin(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int haddr, pmd_t *pmd, int referenced);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff814abd30)
Location: mm/khugepaged.c:986
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff814abd30-ffffffff814abfac: __collapse_huge_page_swapin (STB_LOCAL)
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
bool __collapse_huge_page_swapin(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, pmd_t *pmd, int referenced);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffff80001035ccc8)
Location: mm/khugepaged.c:890
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffff80001035ccc8-ffff80001035d130: __collapse_huge_page_swapin (STB_LOCAL)
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
bool __collapse_huge_page_swapin(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, pmd_t *pmd, int referenced);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (c000000000446e90)
Location: mm/khugepaged.c:890
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
c000000000446e90-c0000000004474a0: __collapse_huge_page_swapin (STB_LOCAL)
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
bool __collapse_huge_page_swapin(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, pmd_t *pmd, int referenced);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812b3fe0)
Location: mm/khugepaged.c:890
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff812b3fe0-ffffffff812b43e5: __collapse_huge_page_swapin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool __collapse_huge_page_swapin(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, pmd_t *pmd, int referenced);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812a5070)
Location: mm/khugepaged.c:890
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff812a5070-ffffffff812a5464: __collapse_huge_page_swapin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool __collapse_huge_page_swapin(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, pmd_t *pmd, int referenced);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812b1df0)
Location: mm/khugepaged.c:890
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff812b1df0-ffffffff812b21f5: __collapse_huge_page_swapin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool __collapse_huge_page_swapin(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, pmd_t *pmd, int referenced);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812c21b0)
Location: mm/khugepaged.c:890
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff812c21b0-ffffffff812c25f8: __collapse_huge_page_swapin (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int haddr</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int address</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
