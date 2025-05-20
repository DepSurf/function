# Function: <code>pmdp_set_access_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pmdp_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp, pmd_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81070f80)
Location: arch/x86/mm/pgtable.c:424
Inline: False
Direct callers:
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff81070f80-ffffffff81070fc9: pmdp_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pmdp_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp, pmd_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81070ec0)
Location: arch/x86/mm/pgtable.c:428
Inline: False
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:touch_pmd
```
**Symbols:**

```
ffffffff81070ec0-ffffffff81070efa: pmdp_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pmdp_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp, pmd_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81074a40)
Location: arch/x86/mm/pgtable.c:428
Inline: False
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:touch_pmd
```
**Symbols:**

```
ffffffff81074a40-ffffffff81074a7a: pmdp_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pmdp_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp, pmd_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81073f90)
Location: arch/x86/mm/pgtable.c:438
Inline: False
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:touch_pmd
```
**Symbols:**

```
ffffffff81073f90-ffffffff81073fca: pmdp_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pmdp_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp, pmd_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810799c0)
Location: arch/x86/mm/pgtable.c:438
Inline: False
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:touch_pmd
```
**Symbols:**

```
ffffffff810799c0-ffffffff810799fa: pmdp_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pmdp_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp, pmd_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8107c590)
Location: arch/x86/mm/pgtable.c:443
Inline: False
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:touch_pmd
```
**Symbols:**

```
ffffffff8107c590-ffffffff8107c5ca: pmdp_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pmdp_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp, pmd_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81082f80)
Location: arch/x86/mm/pgtable.c:509
Inline: False
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:touch_pmd
```
**Symbols:**

```
ffffffff81082f80-ffffffff81082fc5: pmdp_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pmdp_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp, pmd_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81086bf0)
Location: arch/x86/mm/pgtable.c:496
Inline: False
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:touch_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
**Symbols:**

```
ffffffff81086bf0-ffffffff81086c3d: pmdp_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pmdp_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp, pmd_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810878e0)
Location: arch/x86/mm/pgtable.c:492
Inline: False
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:touch_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
**Symbols:**

```
ffffffff810878e0-ffffffff8108792d: pmdp_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pmdp_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp, pmd_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81089d00)
Location: arch/x86/mm/pgtable.c:499
Inline: False
Direct callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
```
**Symbols:**

```
ffffffff81089d00-ffffffff81089d58: pmdp_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pmdp_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp, pmd_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81089f80)
Location: arch/x86/mm/pgtable.c:499
Inline: False
Direct callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
```
**Symbols:**

```
ffffffff81089f80-ffffffff81089fd8: pmdp_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pmdp_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp, pmd_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8108abe0)
Location: arch/x86/mm/pgtable.c:499
Inline: False
Direct callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:follow_devmap_pmd
```
**Symbols:**

```
ffffffff8108abe0-ffffffff8108ac38: pmdp_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pmdp_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp, pmd_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8109a180)
Location: arch/x86/mm/pgtable.c:499
Inline: False
Direct callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
```
**Symbols:**

```
ffffffff8109a180-ffffffff8109a1d8: pmdp_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pmdp_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp, pmd_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810ad280)
Location: arch/x86/mm/pgtable.c:499
Inline: False
Direct callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
```
**Symbols:**

```
ffffffff810ad280-ffffffff810ad300: pmdp_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pmdp_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp, pmd_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810c7340)
Location: arch/x86/mm/pgtable.c:503
Inline: False
Direct callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
```
**Symbols:**

```
ffffffff810c7340-ffffffff810c73d0: pmdp_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pmdp_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp, pmd_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810caa90)
Location: arch/x86/mm/pgtable.c:503
Inline: False
Direct callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
**Symbols:**

```
ffffffff810caa90-ffffffff810cab20: pmdp_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pmdp_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp, pmd_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810d2fe0)
Location: arch/x86/mm/pgtable.c:515
Inline: False
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
**Symbols:**

```
ffffffff810d2fe0-ffffffff810d3070: pmdp_set_access_flags (STB_GLOBAL)
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
In mm/huge_memory.c (ffff800010358a78)
Location: arch/arm64/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:touch_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
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
int pmdp_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp, pmd_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/book3s64/pgtable.c (c000000000090920)
Location: arch/powerpc/mm/book3s64/pgtable.c:35
Inline: False
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:touch_pmd
  - mm/huge_memory.c:touch_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
**Symbols:**

```
c000000000090920-c000000000090a18: pmdp_set_access_flags (STB_GLOBAL)
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
int pmdp_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp, pmd_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810868e0)
Location: arch/x86/mm/pgtable.c:492
Inline: False
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:touch_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
**Symbols:**

```
ffffffff810868e0-ffffffff8108692d: pmdp_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pmdp_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp, pmd_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810755b0)
Location: arch/x86/mm/pgtable.c:492
Inline: False
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:touch_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
**Symbols:**

```
ffffffff810755b0-ffffffff810755d5: pmdp_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pmdp_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp, pmd_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81086890)
Location: arch/x86/mm/pgtable.c:492
Inline: False
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:touch_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
**Symbols:**

```
ffffffff81086890-ffffffff810868dd: pmdp_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pmdp_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp, pmd_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810889c0)
Location: arch/x86/mm/pgtable.c:492
Inline: False
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:touch_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
**Symbols:**

```
ffffffff810889c0-ffffffff81088a0d: pmdp_set_access_flags (STB_GLOBAL)
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
