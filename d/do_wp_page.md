# Function: <code>do_wp_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_wp_page(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, pte_t *page_table, pmd_t *pmd, spinlock_t *ptl, pte_t orig_pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811be030)
Location: mm/memory.c:2285
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
```
**Symbols:**

```
ffffffff811be030-ffffffff811be6ea: do_wp_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_wp_page(struct fault_env *fe, pte_t orig_pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811d82b0)
Location: mm/memory.c:2359
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff811d82b0-ffffffff811d8aa1: do_wp_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_wp_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811e8fc0)
Location: mm/memory.c:2377
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff811e8fc0-ffffffff811e9585: do_wp_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_wp_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f4200)
Location: mm/memory.c:2583
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff811f4200-ffffffff811f46f4: do_wp_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_wp_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8120bf10)
Location: mm/memory.c:2704
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff8120bf10-ffffffff8120c4ca: do_wp_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_wp_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122cad0)
Location: mm/memory.c:2746
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff8122cad0-ffffffff8122d035: do_wp_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
vm_fault_t do_wp_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81240020)
Location: mm/memory.c:2483
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff81240020-ffffffff812405d0: do_wp_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
vm_fault_t do_wp_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81252160)
Location: mm/memory.c:2539
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff81252160-ffffffff81252874: do_wp_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
vm_fault_t do_wp_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81260740)
Location: mm/memory.c:2564
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff81260740-ffffffff81260dd6: do_wp_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
vm_fault_t do_wp_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81290ec0)
Location: mm/memory.c:2906
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff81290ec0-ffffffff81291257: do_wp_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
vm_fault_t do_wp_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129b960)
Location: mm/memory.c:3086
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff8129b960-ffffffff8129bbc4: do_wp_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
vm_fault_t do_wp_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a0a50)
Location: mm/memory.c:3147
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff812a0a50-ffffffff812a0d3a: do_wp_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
vm_fault_t do_wp_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e1b70)
Location: mm/memory.c:3244
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff812e1b70-ffffffff812e1e4f: do_wp_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
vm_fault_t do_wp_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81342990)
Location: mm/memory.c:3353
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff81342990-ffffffff81342d97: do_wp_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
vm_fault_t do_wp_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813baa10)
Location: mm/memory.c:3336
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff813baa10-ffffffff813bad50: do_wp_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
vm_fault_t do_wp_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813ef520)
Location: mm/memory.c:3339
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff813ef520-ffffffff813ef866: do_wp_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
vm_fault_t do_wp_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81419980)
Location: mm/memory.c:3436
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff81419980-ffffffff81419e03: do_wp_page (STB_LOCAL)
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
vm_fault_t do_wp_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102f7a98)
Location: mm/memory.c:2564
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffff8000102f7a98-ffff8000102f8180: do_wp_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
vm_fault_t do_wp_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c051a26c)
Location: mm/memory.c:2564
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
c051a26c-c051a954: do_wp_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
vm_fault_t do_wp_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c09e0)
Location: mm/memory.c:2564
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
c0000000003c09e0-c0000000003c1498: do_wp_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
vm_fault_t do_wp_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe000208018)
Location: mm/memory.c:2564
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffe000208018-ffffffe000208746: do_wp_page (STB_LOCAL)
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
vm_fault_t do_wp_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81258d90)
Location: mm/memory.c:2564
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff81258d90-ffffffff81259426: do_wp_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
vm_fault_t do_wp_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124b240)
Location: mm/memory.c:2564
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff8124b240-ffffffff8124b8a4: do_wp_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
vm_fault_t do_wp_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81256b30)
Location: mm/memory.c:2564
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff81256b30-ffffffff812571c6: do_wp_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
vm_fault_t do_wp_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812665a0)
Location: mm/memory.c:2564
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff812665a0-ffffffff81266bb3: do_wp_page (STB_LOCAL)
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
<code>pte_t *page_table</code>
</li>
<li>
<b>Param removed. </b>
<code>pmd_t *pmd</code>
</li>
<li>
<b>Param removed. </b>
<code>spinlock_t *ptl</code>
</li>
<li>
<b>Param reordered. </b>
<code>mm, vma, address, page_table, pmd, ptl, orig_pte</code> ➡️ <code>fe, orig_pte</code>
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
