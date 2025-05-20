# Function: <code>unuse_pte_range</code>

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
In mm/swapfile.c (ffffffff811d4084)
Location: mm/swapfile.c:1195
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
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
In mm/swapfile.c (ffffffff811f1ec1)
Location: mm/swapfile.c:1185
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
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
In mm/swapfile.c (ffffffff812028b1)
Location: mm/swapfile.c:1205
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
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
In mm/swapfile.c (ffffffff8120d9e2)
Location: mm/swapfile.c:1617
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
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
In mm/swapfile.c (ffffffff81228b92)
Location: mm/swapfile.c:1829
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
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
In mm/swapfile.c (ffffffff8124a163)
Location: mm/swapfile.c:1829
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
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
In mm/swapfile.c (ffffffff8125e7a3)
Location: mm/swapfile.c:1801
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int unuse_pte_range(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int end, unsigned int type, bool frontswap, long unsigned int *fs_pages_to_unuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8127aff0)
Location: mm/swapfile.c:1909
Inline: False
Direct callers:
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffff8127aff0-ffffffff8127b3ba: unuse_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int unuse_pte_range(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int end, unsigned int type, bool frontswap, long unsigned int *fs_pages_to_unuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8128aad0)
Location: mm/swapfile.c:1909
Inline: False
Direct callers:
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffff8128aad0-ffffffff8128ae9a: unuse_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int unuse_pte_range(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int end, unsigned int type, bool frontswap, long unsigned int *fs_pages_to_unuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812bd800)
Location: mm/swapfile.c:1935
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_p4d_range
```
**Symbols:**

```
ffffffff812bd800-ffffffff812bdc0a: unuse_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int unuse_pte_range(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int end, unsigned int type, bool frontswap, long unsigned int *fs_pages_to_unuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812c9320)
Location: mm/swapfile.c:1951
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_p4d_range
```
**Symbols:**

```
ffffffff812c9320-ffffffff812c9724: unuse_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int unuse_pte_range(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int end, unsigned int type, bool frontswap, long unsigned int *fs_pages_to_unuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812cfea0)
Location: mm/swapfile.c:1951
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_vma
```
**Symbols:**

```
ffffffff812cfea0-ffffffff812d02b3: unuse_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int unuse_pte_range(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int end, unsigned int type, bool frontswap, long unsigned int *fs_pages_to_unuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813153a0)
Location: mm/swapfile.c:1938
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_vma
```
**Symbols:**

```
ffffffff813153a0-ffffffff813157d5: unuse_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int unuse_pte_range(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int end, unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81380950)
Location: mm/swapfile.c:1843
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_vma
```
**Symbols:**

```
ffffffff81380950-ffffffff81380dab: unuse_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int unuse_pte_range(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int end, unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813ff250)
Location: mm/swapfile.c:1839
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_vma
```
**Symbols:**

```
ffffffff813ff250-ffffffff813ff5eb: unuse_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int unuse_pte_range(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int end, unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81432170)
Location: mm/swapfile.c:1825
Inline: False
```
**Symbols:**

```
ffffffff81432170-ffffffff81432470: unuse_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int unuse_pte_range(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int end, unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8146b560)
Location: mm/swapfile.c:1833
Inline: False
```
**Symbols:**

```
ffffffff8146b560-ffffffff8146b885: unuse_pte_range (STB_LOCAL)
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
int unuse_pte_range(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int end, unsigned int type, bool frontswap, long unsigned int *fs_pages_to_unuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffff800010325d40)
Location: mm/swapfile.c:1909
Inline: False
Direct callers:
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffff800010325d40-ffff800010326324: unuse_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c053d608)
Location: mm/swapfile.c:1909
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int unuse_pte_range(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int end, unsigned int type, bool frontswap, long unsigned int *fs_pages_to_unuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c0000000003fc100)
Location: mm/swapfile.c:1909
Inline: False
Direct callers:
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
c0000000003fc100-c0000000003fc970: unuse_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int unuse_pte_range(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int end, unsigned int type, bool frontswap, long unsigned int *fs_pages_to_unuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffe000226148)
Location: mm/swapfile.c:1909
Inline: False
Direct callers:
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffe000226148-ffffffe0002265d0: unuse_pte_range (STB_LOCAL)
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
int unuse_pte_range(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int end, unsigned int type, bool frontswap, long unsigned int *fs_pages_to_unuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812830b0)
Location: mm/swapfile.c:1909
Inline: False
Direct callers:
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffff812830b0-ffffffff8128347a: unuse_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int unuse_pte_range(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int end, unsigned int type, bool frontswap, long unsigned int *fs_pages_to_unuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81274bd0)
Location: mm/swapfile.c:1909
Inline: False
Direct callers:
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffff81274bd0-ffffffff81275311: unuse_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int unuse_pte_range(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int end, unsigned int type, bool frontswap, long unsigned int *fs_pages_to_unuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81280ec0)
Location: mm/swapfile.c:1909
Inline: False
Direct callers:
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffff81280ec0-ffffffff8128128a: unuse_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int unuse_pte_range(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int end, unsigned int type, bool frontswap, long unsigned int *fs_pages_to_unuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81290bd0)
Location: mm/swapfile.c:1909
Inline: False
Direct callers:
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffff81290bd0-ffffffff81290f94: unuse_pte_range (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<b>Param removed. </b>
<code>bool frontswap</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int *fs_pages_to_unuse</code>
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
