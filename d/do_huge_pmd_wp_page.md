# Function: <code>do_huge_pmd_wp_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_huge_pmd_wp_page(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, pmd_t *pmd, pmd_t orig_pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff811f8540)
Location: mm/huge_memory.c:1151
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
```
**Symbols:**

```
ffffffff811f8540-ffffffff811f90a3: do_huge_pmd_wp_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_huge_pmd_wp_page(struct fault_env *fe, pmd_t orig_pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81216a00)
Location: mm/huge_memory.c:936
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
```
**Symbols:**

```
ffffffff81216a00-ffffffff8121783f: do_huge_pmd_wp_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_huge_pmd_wp_page(struct vm_fault *vmf, pmd_t orig_pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81228fc0)
Location: mm/huge_memory.c:1015
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
```
**Symbols:**

```
ffffffff81228fc0-ffffffff81229de9: do_huge_pmd_wp_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_huge_pmd_wp_page(struct vm_fault *vmf, pmd_t orig_pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81234ca0)
Location: mm/huge_memory.c:1218
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff81234ca0-ffffffff81235968: do_huge_pmd_wp_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_huge_pmd_wp_page(struct vm_fault *vmf, pmd_t orig_pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812531f0)
Location: mm/huge_memory.c:1242
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff812531f0-ffffffff8125437d: do_huge_pmd_wp_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_huge_pmd_wp_page(struct vm_fault *vmf, pmd_t orig_pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81277690)
Location: mm/huge_memory.c:1239
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff81277690-ffffffff81278210: do_huge_pmd_wp_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_wp_page(struct vm_fault *vmf, pmd_t orig_pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8128bcb0)
Location: mm/huge_memory.c:1253
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff8128bcb0-ffffffff8128c843: do_huge_pmd_wp_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_wp_page(struct vm_fault *vmf, pmd_t orig_pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a6900)
Location: mm/huge_memory.c:1309
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff812a6900-ffffffff812a7522: do_huge_pmd_wp_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_wp_page(struct vm_fault *vmf, pmd_t orig_pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b7dd0)
Location: mm/huge_memory.c:1315
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff812b7dd0-ffffffff812b89d0: do_huge_pmd_wp_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_wp_page(struct vm_fault *vmf, pmd_t orig_pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ed1d0)
Location: mm/huge_memory.c:1255
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff812ed1d0-ffffffff812ed52e: do_huge_pmd_wp_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_wp_page(struct vm_fault *vmf, pmd_t orig_pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812f88f0)
Location: mm/huge_memory.c:1275
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff812f88f0-ffffffff812f8c48: do_huge_pmd_wp_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_wp_page(struct vm_fault *vmf, pmd_t orig_pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812fee30)
Location: mm/huge_memory.c:1281
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff812fee30-ffffffff812ff1b1: do_huge_pmd_wp_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_wp_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81348a20)
Location: mm/huge_memory.c:1283
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff81348a20-ffffffff81348da4: do_huge_pmd_wp_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_wp_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff813beb80)
Location: mm/huge_memory.c:1260
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff813beb80-ffffffff813bf201: do_huge_pmd_wp_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_wp_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff814413e0)
Location: mm/huge_memory.c:1309
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff814413e0-ffffffff814417b7: do_huge_pmd_wp_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_wp_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81476dc0)
Location: mm/huge_memory.c:1294
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff81476dc0-ffffffff81477181: do_huge_pmd_wp_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_wp_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff814a6510)
Location: mm/huge_memory.c:1511
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff814a6510-ffffffff814a690b: do_huge_pmd_wp_page (STB_GLOBAL)
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
vm_fault_t do_huge_pmd_wp_page(struct vm_fault *vmf, pmd_t orig_pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffff8000103585e8)
Location: mm/huge_memory.c:1315
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffff8000103585e8-ffff800010359084: do_huge_pmd_wp_page (STB_GLOBAL)
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
vm_fault_t do_huge_pmd_wp_page(struct vm_fault *vmf, pmd_t orig_pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (c000000000441020)
Location: mm/huge_memory.c:1315
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
c000000000441020-c0000000004422b0: do_huge_pmd_wp_page (STB_GLOBAL)
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
vm_fault_t do_huge_pmd_wp_page(struct vm_fault *vmf, pmd_t orig_pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b03b0)
Location: mm/huge_memory.c:1315
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff812b03b0-ffffffff812b0fb0: do_huge_pmd_wp_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_wp_page(struct vm_fault *vmf, pmd_t orig_pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a1850)
Location: mm/huge_memory.c:1315
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff812a1850-ffffffff812a23a5: do_huge_pmd_wp_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_wp_page(struct vm_fault *vmf, pmd_t orig_pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ae1c0)
Location: mm/huge_memory.c:1315
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff812ae1c0-ffffffff812aedc0: do_huge_pmd_wp_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_wp_page(struct vm_fault *vmf, pmd_t orig_pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812be520)
Location: mm/huge_memory.c:1315
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff812be520-ffffffff812bf110: do_huge_pmd_wp_page (STB_GLOBAL)
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
<b>Param reordered. </b>
<code>mm, vma, address, pmd, orig_pmd</code> ➡️ <code>fe, orig_pmd</code>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>pmd_t orig_pmd</code>
</li>
</ul>
</details>
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
