# Function: <code>handle_userfault</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int handle_userfault(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, long unsigned int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff8125abe0)
Location: fs/userfaultfd.c:260
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff8125abe0-ffffffff8125b0c0: handle_userfault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int handle_userfault(struct fault_env *fe, long unsigned int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81283790)
Location: fs/userfaultfd.c:260
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff81283790-ffffffff81283c8a: handle_userfault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int handle_userfault(struct vm_fault *vmf, long unsigned int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff812972b0)
Location: fs/userfaultfd.c:267
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff812972b0-ffffffff812978f1: handle_userfault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int handle_userfault(struct vm_fault *vmf, long unsigned int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff812a4af0)
Location: fs/userfaultfd.c:336
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff812a4af0-ffffffff812a516c: handle_userfault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int handle_userfault(struct vm_fault *vmf, long unsigned int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff812c7f60)
Location: fs/userfaultfd.c:336
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff812c7f60-ffffffff812c8671: handle_userfault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int handle_userfault(struct vm_fault *vmf, long unsigned int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff812f1290)
Location: fs/userfaultfd.c:343
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff812f1290-ffffffff812f1973: handle_userfault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
vm_fault_t handle_userfault(struct vm_fault *vmf, long unsigned int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81305c50)
Location: fs/userfaultfd.c:342
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff81305c50-ffffffff81306333: handle_userfault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
vm_fault_t handle_userfault(struct vm_fault *vmf, long unsigned int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff813271d0)
Location: fs/userfaultfd.c:352
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff813271d0-ffffffff813278bf: handle_userfault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
vm_fault_t handle_userfault(struct vm_fault *vmf, long unsigned int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81339fb0)
Location: fs/userfaultfd.c:352
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff81339fb0-ffffffff8133a69f: handle_userfault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
vm_fault_t handle_userfault(struct vm_fault *vmf, long unsigned int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81374180)
Location: fs/userfaultfd.c:381
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_wp_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff81374180-ffffffff813746f6: handle_userfault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
vm_fault_t handle_userfault(struct vm_fault *vmf, long unsigned int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/userfaultfd.c (0)
Location: fs/userfaultfd.c:368
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_wp_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff81beac26-ffffffff81beac43: handle_userfault.cold (STB_LOCAL)
ffffffff81382140-ffffffff813825a1: handle_userfault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
vm_fault_t handle_userfault(struct vm_fault *vmf, long unsigned int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/userfaultfd.c (0)
Location: fs/userfaultfd.c:366
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_wp_page
  - mm/hugetlb.c:hugetlb_handle_userfault
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff81bdcc53-ffffffff81bdcc70: handle_userfault.cold (STB_LOCAL)
ffffffff813891c0-ffffffff81389627: handle_userfault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
vm_fault_t handle_userfault(struct vm_fault *vmf, long unsigned int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/userfaultfd.c (0)
Location: fs/userfaultfd.c:367
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_wp_page
  - mm/hugetlb.c:hugetlb_handle_userfault
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff81cc56ba-ffffffff81cc5714: handle_userfault.cold (STB_LOCAL)
ffffffff813d64c0-ffffffff813d690d: handle_userfault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
vm_fault_t handle_userfault(struct vm_fault *vmf, long unsigned int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/userfaultfd.c (0)
Location: fs/userfaultfd.c:376
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_wp_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_handle_userfault
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff81e780a5-ffffffff81e780fa: handle_userfault.cold (STB_LOCAL)
ffffffff8145fe00-ffffffff81460204: handle_userfault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
vm_fault_t handle_userfault(struct vm_fault *vmf, long unsigned int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/userfaultfd.c (0)
Location: fs/userfaultfd.c:392
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_wp_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_handle_userfault
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff8206a007-ffffffff8206a030: handle_userfault.cold (STB_LOCAL)
ffffffff814efc80-ffffffff814f006b: handle_userfault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
vm_fault_t handle_userfault(struct vm_fault *vmf, long unsigned int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/userfaultfd.c (0)
Location: fs/userfaultfd.c:415
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_wp_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_handle_userfault
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff820e9f95-ffffffff820e9fcc: handle_userfault.cold (STB_LOCAL)
ffffffff81526a20-ffffffff81526ed3: handle_userfault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
vm_fault_t handle_userfault(struct vm_fault *vmf, long unsigned int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/userfaultfd.c (0)
Location: fs/userfaultfd.c:416
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_wp_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_handle_userfault
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff821c6a85-ffffffff821c6aae: handle_userfault.cold (STB_LOCAL)
ffffffff8155b7a0-ffffffff8155bbfc: handle_userfault (STB_GLOBAL)
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
vm_fault_t handle_userfault(struct vm_fault *vmf, long unsigned int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffff8000103f9220)
Location: fs/userfaultfd.c:352
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffff8000103f9220-ffff8000103f96e8: handle_userfault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
vm_fault_t handle_userfault(struct vm_fault *vmf, long unsigned int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (c05cd110)
Location: fs/userfaultfd.c:352
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
```
**Symbols:**

```
c05cd110-c05cd630: handle_userfault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
vm_fault_t handle_userfault(struct vm_fault *vmf, long unsigned int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (c000000000501410)
Location: fs/userfaultfd.c:352
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
c000000000501410-c000000000501d50: handle_userfault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
vm_fault_t handle_userfault(struct vm_fault *vmf, long unsigned int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffe0002a85ae)
Location: fs/userfaultfd.c:352
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/hugetlb.c:hugetlb_no_page
```
**Symbols:**

```
ffffffe0002a85ae-ffffffe0002a8a0c: handle_userfault (STB_GLOBAL)
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
vm_fault_t handle_userfault(struct vm_fault *vmf, long unsigned int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81332590)
Location: fs/userfaultfd.c:352
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff81332590-ffffffff81332c7f: handle_userfault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
vm_fault_t handle_userfault(struct vm_fault *vmf, long unsigned int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81323150)
Location: fs/userfaultfd.c:352
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff81323150-ffffffff813237cf: handle_userfault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
vm_fault_t handle_userfault(struct vm_fault *vmf, long unsigned int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81330060)
Location: fs/userfaultfd.c:352
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff81330060-ffffffff8133074f: handle_userfault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
vm_fault_t handle_userfault(struct vm_fault *vmf, long unsigned int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff813429c0)
Location: fs/userfaultfd.c:352
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff813429c0-ffffffff8134309d: handle_userfault (STB_GLOBAL)
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
<code>struct vm_area_struct *vma</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int address</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>vma, address, flags, reason</code> ➡️ <code>fe, reason</code>
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
