# Function: <code>do_swap_page</code>

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
In mm/memory.c (ffffffff811bf4e6)
Location: mm/memory.c:2446
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_swap_page(struct fault_env *fe, pte_t orig_pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811d9a50)
Location: mm/memory.c:2516
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff811d9a50-ffffffff811da1c7: do_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_swap_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811e9590)
Location: mm/memory.c:2534
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff811e9590-ffffffff811e9cf4: do_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_swap_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f4700)
Location: mm/memory.c:2740
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff811f4700-ffffffff811f4df9: do_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_swap_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8120c4d0)
Location: mm/memory.c:2861
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff8120c4d0-ffffffff8120cefa: do_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_swap_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122d1a0)
Location: mm/memory.c:2922
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff8122d1a0-ffffffff8122dab6: do_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
vm_fault_t do_swap_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81240730)
Location: mm/memory.c:2659
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff81240730-ffffffff812410e1: do_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
vm_fault_t do_swap_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812529e0)
Location: mm/memory.c:2727
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff812529e0-ffffffff812533c7: do_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
vm_fault_t do_swap_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81260f40)
Location: mm/memory.c:2752
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff81260f40-ffffffff8126192a: do_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
vm_fault_t do_swap_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812913b0)
Location: mm/memory.c:3100
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff812913b0-ffffffff81291ba7: do_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
vm_fault_t do_swap_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129bd20)
Location: mm/memory.c:3263
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff8129bd20-ffffffff8129c479: do_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
vm_fault_t do_swap_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a0fc0)
Location: mm/memory.c:3354
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff812a0fc0-ffffffff812a172f: do_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
vm_fault_t do_swap_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e1f70)
Location: mm/memory.c:3480
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff812e1f70-ffffffff812e26fa: do_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
vm_fault_t do_swap_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81343bf0)
Location: mm/memory.c:3711
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff81343bf0-ffffffff81344454: do_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
vm_fault_t do_swap_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813bbc70)
Location: mm/memory.c:3690
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff813bbc70-ffffffff813bc59f: do_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
vm_fault_t do_swap_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813f0680)
Location: mm/memory.c:3715
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff813f0680-ffffffff813f0f54: do_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
vm_fault_t do_swap_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8141ffc0)
Location: mm/memory.c:3796
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff8141ffc0-ffffffff814209c6: do_swap_page (STB_GLOBAL)
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
vm_fault_t do_swap_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102f8308)
Location: mm/memory.c:2752
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffff8000102f8308-ffff8000102f8be4: do_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
vm_fault_t do_swap_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c051aadc)
Location: mm/memory.c:2752
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
```
**Symbols:**

```
c051aadc-c051b2e0: do_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
vm_fault_t do_swap_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c1650)
Location: mm/memory.c:2752
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
c0000000003c1650-c0000000003c22cc: do_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
vm_fault_t do_swap_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe000208898)
Location: mm/memory.c:2752
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffe000208898-ffffffe000208f26: do_swap_page (STB_GLOBAL)
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
vm_fault_t do_swap_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81259590)
Location: mm/memory.c:2752
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff81259590-ffffffff81259f7a: do_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
vm_fault_t do_swap_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124ba10)
Location: mm/memory.c:2752
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff8124ba10-ffffffff8124c3a7: do_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
vm_fault_t do_swap_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81257330)
Location: mm/memory.c:2752
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff81257330-ffffffff81257d1a: do_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
vm_fault_t do_swap_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81266d20)
Location: mm/memory.c:2752
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff81266d20-ffffffff81267703: do_swap_page (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
<b>Param removed. </b>
<code>pte_t orig_pte</code>
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
