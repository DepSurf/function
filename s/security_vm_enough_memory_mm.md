# Function: <code>security_vm_enough_memory_mm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_vm_enough_memory_mm(struct mm_struct *mm, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133cfa0)
Location: security/security.c:216
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - mm/shmem.c:__shmem_file_setup
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_setattr
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:do_brk
  - mm/mmap.c:mmap_region
  - mm/mmap.c:insert_vm_struct
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:vma_to_resize
  - mm/swapfile.c:SyS_swapoff
  - mm/frontswap.c:frontswap_shrink
```
**Symbols:**

```
ffffffff8133cfa0-ffffffff8133cffa: security_vm_enough_memory_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_vm_enough_memory_mm(struct mm_struct *mm, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813725d0)
Location: security/security.c:217
Inline: False
Direct callers:
  - mm/shmem.c:__shmem_file_setup
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_charge
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_brk
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:vma_to_resize
  - mm/swapfile.c:SyS_swapoff
  - mm/frontswap.c:frontswap_shrink
```
**Symbols:**

```
ffffffff813725d0-ffffffff8137262a: security_vm_enough_memory_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_vm_enough_memory_mm(struct mm_struct *mm, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81388f00)
Location: security/security.c:217
Inline: False
Direct callers:
  - mm/shmem.c:__shmem_file_setup
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_charge
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_brk
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:vma_to_resize
  - mm/swapfile.c:SyS_swapoff
  - mm/frontswap.c:frontswap_shrink
```
**Symbols:**

```
ffffffff81388f00-ffffffff81388f5a: security_vm_enough_memory_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_vm_enough_memory_mm(struct mm_struct *mm, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139e270)
Location: security/security.c:788
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mcopy_atomic_pte
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_charge
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:vma_to_resize
  - mm/swapfile.c:SyS_swapoff
  - mm/frontswap.c:frontswap_shrink
```
**Symbols:**

```
ffffffff8139e270-ffffffff8139e2ca: security_vm_enough_memory_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_vm_enough_memory_mm(struct mm_struct *mm, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c3c30)
Location: security/security.c:738
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_charge
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:vma_to_resize
  - mm/swapfile.c:SYSC_swapoff
  - mm/frontswap.c:frontswap_shrink
```
**Symbols:**

```
ffffffff813c3c30-ffffffff813c3c90: security_vm_enough_memory_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_vm_enough_memory_mm(struct mm_struct *mm, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f4290)
Location: security/security.c:315
Inline: False
Direct callers:
  - kernel/fork.c:copy_mm
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_charge
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:vma_to_resize
  - mm/swapfile.c:__do_sys_swapoff
  - mm/frontswap.c:frontswap_shrink
```
**Symbols:**

```
ffffffff813f4290-ffffffff813f42e8: security_vm_enough_memory_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_vm_enough_memory_mm(struct mm_struct *mm, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8140f670)
Location: security/security.c:797
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_charge
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:vma_to_resize
  - mm/swapfile.c:__do_sys_swapoff
  - mm/frontswap.c:frontswap_shrink
```
**Symbols:**

```
ffffffff8140f670-ffffffff8140f6c8: security_vm_enough_memory_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_vm_enough_memory_mm(struct mm_struct *mm, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143cb30)
Location: security/security.c:796
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_charge
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:vma_to_resize
  - mm/swapfile.c:__do_sys_swapoff
  - mm/frontswap.c:frontswap_shrink
```
**Symbols:**

```
ffffffff8143cb30-ffffffff8143cb88: security_vm_enough_memory_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_vm_enough_memory_mm(struct mm_struct *mm, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81456630)
Location: security/security.c:830
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_charge
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:vma_to_resize
  - mm/swapfile.c:__do_sys_swapoff
  - mm/frontswap.c:frontswap_shrink
```
**Symbols:**

```
ffffffff81456630-ffffffff81456688: security_vm_enough_memory_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_vm_enough_memory_mm(struct mm_struct *mm, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a93f0)
Location: security/security.c:973
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_charge
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:vma_to_resize
  - mm/swapfile.c:__do_sys_swapoff
  - mm/frontswap.c:frontswap_shrink
```
**Symbols:**

```
ffffffff814a93f0-ffffffff814a9448: security_vm_enough_memory_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_vm_enough_memory_mm(struct mm_struct *mm, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c69f0)
Location: security/security.c:975
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_charge
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:vma_to_resize
  - mm/mremap.c:move_vma
  - mm/swapfile.c:__do_sys_swapoff
  - mm/frontswap.c:frontswap_shrink
```
**Symbols:**

```
ffffffff814c69f0-ffffffff814c6a48: security_vm_enough_memory_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_vm_enough_memory_mm(struct mm_struct *mm, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ccae0)
Location: security/security.c:999
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_charge
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:vma_to_resize
  - mm/mremap.c:move_vma
  - mm/swapfile.c:__do_sys_swapoff
  - mm/frontswap.c:frontswap_shrink
```
**Symbols:**

```
ffffffff814ccae0-ffffffff814ccb38: security_vm_enough_memory_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_vm_enough_memory_mm(struct mm_struct *mm, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81525c60)
Location: security/security.c:999
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_charge
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:vma_to_resize
  - mm/mremap.c:move_vma
  - mm/swapfile.c:__do_sys_swapoff
  - mm/frontswap.c:frontswap_shrink
```
**Symbols:**

```
ffffffff81525c60-ffffffff81525cb8: security_vm_enough_memory_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_vm_enough_memory_mm(struct mm_struct *mm, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815b9f40)
Location: security/security.c:998
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_charge
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:move_vma
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffffffff815b9f40-ffffffff815b9fa2: security_vm_enough_memory_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_vm_enough_memory_mm(struct mm_struct *mm, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816657d0)
Location: security/security.c:996
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_charge
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:expand_downwards
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:move_vma
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffffffff816657d0-ffffffff81665832: security_vm_enough_memory_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_vm_enough_memory_mm(struct mm_struct *mm, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169dd50)
Location: security/security.c:1156
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_charge
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:expand_downwards
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:move_vma
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffffffff8169dd50-ffffffff8169ddb2: security_vm_enough_memory_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_vm_enough_memory_mm(struct mm_struct *mm, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816da680)
Location: security/security.c:1199
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_inode_acct_blocks
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:expand_downwards
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:move_vma
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffffffff816da680-ffffffff816da6e2: security_vm_enough_memory_mm (STB_GLOBAL)
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
int security_vm_enough_memory_mm(struct mm_struct *mm, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010541ee0)
Location: security/security.c:830
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_charge
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:vma_to_resize
  - mm/swapfile.c:__do_sys_swapoff
  - mm/frontswap.c:frontswap_shrink
```
**Symbols:**

```
ffff800010541ee0-ffff800010541f70: security_vm_enough_memory_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_vm_enough_memory_mm(struct mm_struct *mm, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f7ea8)
Location: security/security.c:830
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_charge
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:vma_to_resize
  - mm/swapfile.c:__do_sys_swapoff
  - mm/frontswap.c:frontswap_shrink
```
**Symbols:**

```
c06f7ea8-c06f7f1c: security_vm_enough_memory_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_vm_enough_memory_mm(struct mm_struct *mm, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000694ca0)
Location: security/security.c:830
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_charge
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:vma_to_resize
  - mm/swapfile.c:__do_sys_swapoff
  - mm/frontswap.c:frontswap_shrink
```
**Symbols:**

```
c000000000694ca0-c000000000694d80: security_vm_enough_memory_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_vm_enough_memory_mm(struct mm_struct *mm, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039e9b8)
Location: security/security.c:830
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_charge
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:vma_to_resize
  - mm/swapfile.c:__do_sys_swapoff
  - mm/frontswap.c:frontswap_shrink
```
**Symbols:**

```
ffffffe00039e9b8-ffffffe00039ea10: security_vm_enough_memory_mm (STB_GLOBAL)
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
int security_vm_enough_memory_mm(struct mm_struct *mm, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144ec10)
Location: security/security.c:830
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_charge
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:vma_to_resize
  - mm/swapfile.c:__do_sys_swapoff
  - mm/frontswap.c:frontswap_shrink
```
**Symbols:**

```
ffffffff8144ec10-ffffffff8144ec68: security_vm_enough_memory_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_vm_enough_memory_mm(struct mm_struct *mm, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143f660)
Location: security/security.c:830
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_charge
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:vma_to_resize
  - mm/swapfile.c:__do_sys_swapoff
  - mm/frontswap.c:frontswap_shrink
```
**Symbols:**

```
ffffffff8143f660-ffffffff8143f6b8: security_vm_enough_memory_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_vm_enough_memory_mm(struct mm_struct *mm, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144acb0)
Location: security/security.c:830
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_charge
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:vma_to_resize
  - mm/swapfile.c:__do_sys_swapoff
  - mm/frontswap.c:frontswap_shrink
```
**Symbols:**

```
ffffffff8144acb0-ffffffff8144ad08: security_vm_enough_memory_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_vm_enough_memory_mm(struct mm_struct *mm, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81462080)
Location: security/security.c:830
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_charge
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:vma_to_resize
  - mm/swapfile.c:__do_sys_swapoff
  - mm/frontswap.c:frontswap_shrink
```
**Symbols:**

```
ffffffff81462080-ffffffff814620d8: security_vm_enough_memory_mm (STB_GLOBAL)
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
