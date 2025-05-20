# Function: <code>find_mergeable_vma</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct vm_area_struct *find_mergeable_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff811e45d0)
Location: mm/ksm.c:411
Inline: False
Direct callers:
  - mm/ksm.c:break_cow
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:ksm_scan_thread
```
**Symbols:**

```
ffffffff811e45d0-ffffffff811e460e: find_mergeable_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct vm_area_struct *find_mergeable_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81202f00)
Location: mm/ksm.c:417
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:break_cow
```
**Symbols:**

```
ffffffff81202f00-ffffffff81202f3e: find_mergeable_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct vm_area_struct *find_mergeable_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81214de0)
Location: mm/ksm.c:428
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:break_cow
```
**Symbols:**

```
ffffffff81214de0-ffffffff81214e1e: find_mergeable_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct vm_area_struct *find_mergeable_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81220460)
Location: mm/ksm.c:500
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:break_cow
```
**Symbols:**

```
ffffffff81220460-ffffffff8122049e: find_mergeable_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct vm_area_struct *find_mergeable_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8123b6a0)
Location: mm/ksm.c:500
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:break_cow
```
**Symbols:**

```
ffffffff8123b6a0-ffffffff8123b6de: find_mergeable_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct vm_area_struct *find_mergeable_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8125eb90)
Location: mm/ksm.c:519
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:break_cow
```
**Symbols:**

```
ffffffff8125eb90-ffffffff8125ebce: find_mergeable_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct vm_area_struct *find_mergeable_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812733c0)
Location: mm/ksm.c:520
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:break_cow
```
**Symbols:**

```
ffffffff812733c0-ffffffff812733fe: find_mergeable_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct vm_area_struct *find_mergeable_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8128ebc0)
Location: mm/ksm.c:519
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:break_cow
```
**Symbols:**

```
ffffffff8128ebc0-ffffffff8128ebfe: find_mergeable_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct vm_area_struct *find_mergeable_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8129e9a0)
Location: mm/ksm.c:519
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:break_cow
```
**Symbols:**

```
ffffffff8129e9a0-ffffffff8129e9de: find_mergeable_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct vm_area_struct *find_mergeable_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812d2fb0)
Location: mm/ksm.c:519
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:break_cow
```
**Symbols:**

```
ffffffff812d2fb0-ffffffff812d2ff4: find_mergeable_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct vm_area_struct *find_mergeable_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812de960)
Location: mm/ksm.c:520
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:break_cow
```
**Symbols:**

```
ffffffff812de960-ffffffff812de9a4: find_mergeable_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct vm_area_struct *find_mergeable_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812e6140)
Location: mm/ksm.c:518
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:break_cow
```
**Symbols:**

```
ffffffff812e6140-ffffffff812e6184: find_mergeable_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct vm_area_struct *find_mergeable_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8132dfa0)
Location: mm/ksm.c:518
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:break_cow
```
**Symbols:**

```
ffffffff8132dfa0-ffffffff8132dfe4: find_mergeable_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct vm_area_struct *find_mergeable_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8139e240)
Location: mm/ksm.c:519
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:break_cow
```
**Symbols:**

```
ffffffff8139e240-ffffffff8139e29c: find_mergeable_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff814221c6)
Location: mm/ksm.c:515
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:break_cow
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81456e7e)
Location: mm/ksm.c:548
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:break_cow
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8149197c)
Location: mm/ksm.c:738
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:break_cow
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
struct vm_area_struct *find_mergeable_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffff80001033e178)
Location: mm/ksm.c:519
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:break_cow
```
**Symbols:**

```
ffff80001033e178-ffff80001033e1d8: find_mergeable_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct vm_area_struct *find_mergeable_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (c0544510)
Location: mm/ksm.c:519
Inline: False
Direct callers:
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:break_cow
```
**Symbols:**

```
c0544510-c054456c: find_mergeable_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct vm_area_struct *find_mergeable_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (c000000000419ab0)
Location: mm/ksm.c:519
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:break_cow
```
**Symbols:**

```
c000000000419ab0-c000000000419b58: find_mergeable_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct vm_area_struct *find_mergeable_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffe0002334fa)
Location: mm/ksm.c:519
Inline: False
Direct callers:
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:break_cow
```
**Symbols:**

```
ffffffe0002334fa-ffffffe00023354a: find_mergeable_vma (STB_LOCAL)
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
struct vm_area_struct *find_mergeable_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81296f80)
Location: mm/ksm.c:519
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:break_cow
```
**Symbols:**

```
ffffffff81296f80-ffffffff81296fbe: find_mergeable_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct vm_area_struct *find_mergeable_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81288b90)
Location: mm/ksm.c:519
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:break_cow
```
**Symbols:**

```
ffffffff81288b90-ffffffff81288bce: find_mergeable_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct vm_area_struct *find_mergeable_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81294d90)
Location: mm/ksm.c:519
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:break_cow
```
**Symbols:**

```
ffffffff81294d90-ffffffff81294dce: find_mergeable_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct vm_area_struct *find_mergeable_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812a4c00)
Location: mm/ksm.c:519
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:break_cow
```
**Symbols:**

```
ffffffff812a4c00-ffffffff812a4c3e: find_mergeable_vma (STB_LOCAL)
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
