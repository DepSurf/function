# Function: <code>hugetlb_no_page</code>

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
In mm/hugetlb.c (ffffffff811dee8a)
Location: mm/hugetlb.c:3521
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
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
In mm/hugetlb.c (ffffffff811fd37b)
Location: mm/hugetlb.c:3536
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
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
In mm/hugetlb.c (ffffffff8120de4a)
Location: mm/hugetlb.c:3650
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int hugetlb_no_page(struct mm_struct *mm, struct vm_area_struct *vma, struct address_space *mapping, long unsigned int idx, long unsigned int address, pte_t *ptep, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81218760)
Location: mm/hugetlb.c:3636
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
```
**Symbols:**

```
ffffffff81218760-ffffffff81218ce7: hugetlb_no_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int hugetlb_no_page(struct mm_struct *mm, struct vm_area_struct *vma, struct address_space *mapping, long unsigned int idx, long unsigned int address, pte_t *ptep, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81233690)
Location: mm/hugetlb.c:3657
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
```
**Symbols:**

```
ffffffff81233690-ffffffff81233c98: hugetlb_no_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int hugetlb_no_page(struct mm_struct *mm, struct vm_area_struct *vma, struct address_space *mapping, long unsigned int idx, long unsigned int address, pte_t *ptep, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:3686
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
```
**Symbols:**

```
ffffffff81256690-ffffffff81256c5e: hugetlb_no_page (STB_LOCAL)
ffffffff81258926-ffffffff8125894c: hugetlb_no_page.cold.82 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
vm_fault_t hugetlb_no_page(struct mm_struct *mm, struct vm_area_struct *vma, struct address_space *mapping, long unsigned int idx, long unsigned int address, pte_t *ptep, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:3719
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
```
**Symbols:**

```
ffffffff8126abd0-ffffffff8126b1cc: hugetlb_no_page (STB_LOCAL)
ffffffff8126d00a-ffffffff8126d030: hugetlb_no_page.cold.81 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
vm_fault_t hugetlb_no_page(struct mm_struct *mm, struct vm_area_struct *vma, struct address_space *mapping, long unsigned int idx, long unsigned int address, pte_t *ptep, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:3790
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
```
**Symbols:**

```
ffffffff81285d60-ffffffff8128649f: hugetlb_no_page (STB_LOCAL)
ffffffff81288463-ffffffff8128848d: hugetlb_no_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
vm_fault_t hugetlb_no_page(struct mm_struct *mm, struct vm_area_struct *vma, struct address_space *mapping, long unsigned int idx, long unsigned int address, pte_t *ptep, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:3907
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
```
**Symbols:**

```
ffffffff81295940-ffffffff8129607f: hugetlb_no_page (STB_LOCAL)
ffffffff8129805a-ffffffff81298084: hugetlb_no_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
vm_fault_t hugetlb_no_page(struct mm_struct *mm, struct vm_area_struct *vma, struct address_space *mapping, long unsigned int idx, long unsigned int address, pte_t *ptep, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:4329
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
```
**Symbols:**

```
ffffffff812c8f60-ffffffff812c95b5: hugetlb_no_page (STB_LOCAL)
ffffffff812cb771-ffffffff812cb797: hugetlb_no_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
vm_fault_t hugetlb_no_page(struct mm_struct *mm, struct vm_area_struct *vma, struct address_space *mapping, long unsigned int idx, long unsigned int address, pte_t *ptep, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:4319
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
```
**Symbols:**

```
ffffffff812d4b90-ffffffff812d51d1: hugetlb_no_page (STB_LOCAL)
ffffffff81be8ac7-ffffffff81be8aed: hugetlb_no_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
vm_fault_t hugetlb_no_page(struct mm_struct *mm, struct vm_area_struct *vma, struct address_space *mapping, long unsigned int idx, long unsigned int address, pte_t *ptep, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:4573
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
```
**Symbols:**

```
ffffffff812dba10-ffffffff812dbfd6: hugetlb_no_page (STB_LOCAL)
ffffffff81bdaaf3-ffffffff81bdab19: hugetlb_no_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
vm_fault_t hugetlb_no_page(struct mm_struct *mm, struct vm_area_struct *vma, struct address_space *mapping, long unsigned int idx, long unsigned int address, pte_t *ptep, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:4878
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
```
**Symbols:**

```
ffffffff81322bf0-ffffffff8132314c: hugetlb_no_page (STB_LOCAL)
ffffffff81cbfdd0-ffffffff81cbfe86: hugetlb_no_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
vm_fault_t hugetlb_no_page(struct mm_struct *mm, struct vm_area_struct *vma, struct address_space *mapping, long unsigned int idx, long unsigned int address, pte_t *ptep, pte_t old_pte, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:5496
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
```
**Symbols:**

```
ffffffff81390360-ffffffff813909b7: hugetlb_no_page (STB_LOCAL)
ffffffff81e72153-ffffffff81e7220b: hugetlb_no_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
vm_fault_t hugetlb_no_page(struct mm_struct *mm, struct vm_area_struct *vma, struct address_space *mapping, long unsigned int idx, long unsigned int address, pte_t *ptep, pte_t old_pte, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:5748
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
```
**Symbols:**

```
ffffffff81410b60-ffffffff8141127c: hugetlb_no_page (STB_LOCAL)
ffffffff82066ce6-ffffffff82066daa: hugetlb_no_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
vm_fault_t hugetlb_no_page(struct mm_struct *mm, struct vm_area_struct *vma, struct address_space *mapping, long unsigned int idx, long unsigned int address, pte_t *ptep, pte_t old_pte, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:5847
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
```
**Symbols:**

```
ffffffff81443fa0-ffffffff814446f2: hugetlb_no_page (STB_LOCAL)
ffffffff820e6555-ffffffff820e65f6: hugetlb_no_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
vm_fault_t hugetlb_no_page(struct mm_struct *mm, struct vm_area_struct *vma, struct address_space *mapping, long unsigned int idx, long unsigned int address, pte_t *ptep, pte_t old_pte, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:6115
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
```
**Symbols:**

```
ffffffff8147e060-ffffffff8147e7bd: hugetlb_no_page (STB_LOCAL)
ffffffff821c3712-ffffffff821c3801: hugetlb_no_page.cold (STB_LOCAL)
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
vm_fault_t hugetlb_no_page(struct mm_struct *mm, struct vm_area_struct *vma, struct address_space *mapping, long unsigned int idx, long unsigned int address, pte_t *ptep, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffff800010334618)
Location: mm/hugetlb.c:3907
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
```
**Symbols:**

```
ffff800010334618-ffff800010334d1c: hugetlb_no_page (STB_LOCAL)
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
vm_fault_t hugetlb_no_page(struct mm_struct *mm, struct vm_area_struct *vma, struct address_space *mapping, long unsigned int idx, long unsigned int address, pte_t *ptep, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c00000000040d850)
Location: mm/hugetlb.c:3907
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
```
**Symbols:**

```
c00000000040d850-c00000000040e2d4: hugetlb_no_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
vm_fault_t hugetlb_no_page(struct mm_struct *mm, struct vm_area_struct *vma, struct address_space *mapping, long unsigned int idx, long unsigned int address, pte_t *ptep, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffe0002305e0)
Location: mm/hugetlb.c:3907
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
```
**Symbols:**

```
ffffffe0002305e0-ffffffe000230c0a: hugetlb_no_page (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
vm_fault_t hugetlb_no_page(struct mm_struct *mm, struct vm_area_struct *vma, struct address_space *mapping, long unsigned int idx, long unsigned int address, pte_t *ptep, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:3907
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
```
**Symbols:**

```
ffffffff8128df20-ffffffff8128e65f: hugetlb_no_page (STB_LOCAL)
ffffffff8129063a-ffffffff81290664: hugetlb_no_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
vm_fault_t hugetlb_no_page(struct mm_struct *mm, struct vm_area_struct *vma, struct address_space *mapping, long unsigned int idx, long unsigned int address, pte_t *ptep, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:3907
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
```
**Symbols:**

```
ffffffff8127fca0-ffffffff8128041a: hugetlb_no_page (STB_LOCAL)
ffffffff812822ca-ffffffff812822f0: hugetlb_no_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
vm_fault_t hugetlb_no_page(struct mm_struct *mm, struct vm_area_struct *vma, struct address_space *mapping, long unsigned int idx, long unsigned int address, pte_t *ptep, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:3907
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
```
**Symbols:**

```
ffffffff8128bd30-ffffffff8128c46f: hugetlb_no_page (STB_LOCAL)
ffffffff8128e44a-ffffffff8128e474: hugetlb_no_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
vm_fault_t hugetlb_no_page(struct mm_struct *mm, struct vm_area_struct *vma, struct address_space *mapping, long unsigned int idx, long unsigned int address, pte_t *ptep, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:3907
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
```
**Symbols:**

```
ffffffff8129bb20-ffffffff8129c252: hugetlb_no_page (STB_LOCAL)
ffffffff8129e1db-ffffffff8129e205: hugetlb_no_page.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>vm_fault_t</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>pte_t old_pte</code>
</li>
<li>
<b>Param reordered. </b>
<code>mm, vma, mapping, idx, address, ptep, flags</code> ➡️ <code>mm, vma, mapping, idx, address, ptep, old_pte, flags</code>
</li>
</ul>
</details>
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
