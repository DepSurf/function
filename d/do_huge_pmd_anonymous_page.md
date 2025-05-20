# Function: <code>do_huge_pmd_anonymous_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_huge_pmd_anonymous_page(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, pmd_t *pmd, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff811f7960)
Location: mm/huge_memory.c:808
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
```
**Symbols:**

```
ffffffff811f7960-ffffffff811f7edf: do_huge_pmd_anonymous_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_huge_pmd_anonymous_page(struct fault_env *fe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81214230)
Location: mm/huge_memory.c:581
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
```
**Symbols:**

```
ffffffff81214230-ffffffff81214849: do_huge_pmd_anonymous_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_huge_pmd_anonymous_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81226780)
Location: mm/huge_memory.c:654
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
```
**Symbols:**

```
ffffffff81226780-ffffffff81226dd4: do_huge_pmd_anonymous_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_huge_pmd_anonymous_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81232620)
Location: mm/huge_memory.c:669
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff81232620-ffffffff81232c87: do_huge_pmd_anonymous_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_huge_pmd_anonymous_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8124fce0)
Location: mm/huge_memory.c:669
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff8124fce0-ffffffff812503e5: do_huge_pmd_anonymous_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_huge_pmd_anonymous_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81274250)
Location: mm/huge_memory.c:666
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff81274250-ffffffff812749f8: do_huge_pmd_anonymous_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_anonymous_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81289280)
Location: mm/huge_memory.c:685
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff81289280-ffffffff812899b1: do_huge_pmd_anonymous_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_anonymous_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a3e00)
Location: mm/huge_memory.c:701
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff812a3e00-ffffffff812a45d9: do_huge_pmd_anonymous_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_anonymous_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b5300)
Location: mm/huge_memory.c:707
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff812b5300-ffffffff812b5a9f: do_huge_pmd_anonymous_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_anonymous_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ea7a0)
Location: mm/huge_memory.c:716
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff812ea7a0-ffffffff812eab33: do_huge_pmd_anonymous_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_anonymous_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812f5c00)
Location: mm/huge_memory.c:709
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff812f5c00-ffffffff812f608e: do_huge_pmd_anonymous_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_anonymous_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812fc070)
Location: mm/huge_memory.c:724
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff812fc070-ffffffff812fc435: do_huge_pmd_anonymous_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_anonymous_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81345ec0)
Location: mm/huge_memory.c:724
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff81345ec0-ffffffff813462a7: do_huge_pmd_anonymous_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_anonymous_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff813bc100)
Location: mm/huge_memory.c:719
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff813bc100-ffffffff813bc457: do_huge_pmd_anonymous_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_anonymous_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8143e6c0)
Location: mm/huge_memory.c:779
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff8143e6c0-ffffffff8143e9d9: do_huge_pmd_anonymous_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_anonymous_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81473ea0)
Location: mm/huge_memory.c:779
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff81473ea0-ffffffff814741ca: do_huge_pmd_anonymous_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_anonymous_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff814a33a0)
Location: mm/huge_memory.c:994
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff814a33a0-ffffffff814a374d: do_huge_pmd_anonymous_page (STB_GLOBAL)
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
vm_fault_t do_huge_pmd_anonymous_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffff800010356848)
Location: mm/huge_memory.c:707
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffff800010356848-ffff800010356c24: do_huge_pmd_anonymous_page (STB_GLOBAL)
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
vm_fault_t do_huge_pmd_anonymous_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (c00000000043db70)
Location: mm/huge_memory.c:707
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
c00000000043db70-c00000000043e690: do_huge_pmd_anonymous_page (STB_GLOBAL)
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
vm_fault_t do_huge_pmd_anonymous_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ad8e0)
Location: mm/huge_memory.c:707
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff812ad8e0-ffffffff812ae07f: do_huge_pmd_anonymous_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_anonymous_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8129ef60)
Location: mm/huge_memory.c:707
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff8129ef60-ffffffff8129f6d9: do_huge_pmd_anonymous_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_anonymous_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ab6f0)
Location: mm/huge_memory.c:707
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff812ab6f0-ffffffff812abe8f: do_huge_pmd_anonymous_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_anonymous_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812bba60)
Location: mm/huge_memory.c:707
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff812bba60-ffffffff812bc1f2: do_huge_pmd_anonymous_page (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fault_env *fe</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mm_struct *mm</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct *vma</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int address</code>
</li>
<li>
<b>Param removed. </b>
<code>pmd_t *pmd</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int flags</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vm_fault *vmf</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fault_env *fe</code>
</li>
</ul>
</details>
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
