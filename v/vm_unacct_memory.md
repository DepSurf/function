# Function: <code>vm_unacct_memory</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8107fbda)
Location: include/linux/mman.h:28
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In mm/shmem.c (ffffffff811a7fcf)
Location: include/linux/mman.h:28
Inline: True
Inline callers:
  - mm/shmem.c:__shmem_file_setup
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
```
```
In mm/mmap.c (ffffffff811c4a2a)
Location: include/linux/mman.h:28
Inline: True
Inline callers:
  - mm/mmap.c:__vm_enough_memory
  - mm/mmap.c:do_munmap
  - mm/mmap.c:do_brk
  - mm/mmap.c:mmap_region
  - mm/mmap.c:exit_mmap
```
```
In mm/mprotect.c (ffffffff811c8e3e)
Location: include/linux/mman.h:28
Inline: True
Inline callers:
  - mm/mprotect.c:mprotect_fixup
```
```
In mm/mremap.c (ffffffff811c9c94)
Location: include/linux/mman.h:28
Inline: True
Inline callers:
  - mm/mremap.c:move_vma
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:SyS_mremap
```
```
In mm/swapfile.c (ffffffff811d5cf5)
Location: include/linux/mman.h:28
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapoff
```
```
In mm/frontswap.c (ffffffff811d796b)
Location: include/linux/mman.h:28
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_shrink
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81081039)
Location: include/linux/mman.h:28
Inline: True
```
```
In mm/shmem.c (ffffffff811bf030)
Location: include/linux/mman.h:28
Inline: True
Inline callers:
  - mm/shmem.c:__shmem_file_setup
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
```
In mm/util.c (ffffffff811c4f31)
Location: include/linux/mman.h:28
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
```
```
In mm/mmap.c (ffffffff811e253e)
Location: include/linux/mman.h:28
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_brk
  - mm/mmap.c:do_munmap
  - mm/mmap.c:mmap_region
```
```
In mm/mprotect.c (ffffffff811e513f)
Location: include/linux/mman.h:28
Inline: True
Inline callers:
  - mm/mprotect.c:mprotect_fixup
```
```
In mm/mremap.c (ffffffff811e62de)
Location: include/linux/mman.h:28
Inline: True
Inline callers:
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:move_vma
```
```
In mm/swapfile.c (ffffffff811f3dbc)
Location: include/linux/mman.h:28
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapoff
```
```
In mm/frontswap.c (ffffffff811f5abb)
Location: include/linux/mman.h:28
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_shrink
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81085a3f)
Location: include/linux/mman.h:28
Inline: True
```
```
In mm/shmem.c (ffffffff811cec90)
Location: include/linux/mman.h:28
Inline: True
Inline callers:
  - mm/shmem.c:__shmem_file_setup
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
```
In mm/util.c (ffffffff811d5041)
Location: include/linux/mman.h:28
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
```
```
In mm/mmap.c (ffffffff811f250e)
Location: include/linux/mman.h:28
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_brk
  - mm/mmap.c:do_munmap
  - mm/mmap.c:mmap_region
```
```
In mm/mprotect.c (ffffffff811f5193)
Location: include/linux/mman.h:28
Inline: True
Inline callers:
  - mm/mprotect.c:mprotect_fixup
```
```
In mm/mremap.c (ffffffff811f65be)
Location: include/linux/mman.h:28
Inline: True
Inline callers:
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:move_vma
```
```
In mm/swapfile.c (ffffffff812048ec)
Location: include/linux/mman.h:28
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapoff
```
```
In mm/frontswap.c (ffffffff812065eb)
Location: include/linux/mman.h:28
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_shrink
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810830b2)
Location: include/linux/mman.h:28
Inline: True
```
```
In mm/shmem.c (ffffffff811dcd01)
Location: include/linux/mman.h:28
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mcopy_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
```
In mm/util.c (ffffffff811dde91)
Location: include/linux/mman.h:28
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
```
```
In mm/mmap.c (ffffffff811fd4b6)
Location: include/linux/mman.h:28
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_munmap
  - mm/mmap.c:mmap_region
```
```
In mm/mprotect.c (ffffffff811fffaa)
Location: include/linux/mman.h:28
Inline: True
Inline callers:
  - mm/mprotect.c:mprotect_fixup
```
```
In mm/mremap.c (ffffffff812017d5)
Location: include/linux/mman.h:28
Inline: True
Inline callers:
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:move_vma
```
```
In mm/swapfile.c (ffffffff8120ff9c)
Location: include/linux/mman.h:28
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapoff
```
```
In mm/frontswap.c (ffffffff81211d7c)
Location: include/linux/mman.h:28
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_shrink
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81089209)
Location: include/linux/mman.h:71
Inline: True
```
```
In mm/shmem.c (ffffffff811eed3d)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
```
In mm/util.c (ffffffff811f3911)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
```
```
In mm/mmap.c (ffffffff81215a31)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_munmap
  - mm/mmap.c:mmap_region
```
```
In mm/mprotect.c (ffffffff8121874a)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/mprotect.c:mprotect_fixup
```
```
In mm/mremap.c (ffffffff8121a195)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:move_vma
```
```
In mm/swapfile.c (ffffffff8122b75a)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/swapfile.c:SYSC_swapoff
```
```
In mm/frontswap.c (ffffffff8122c749)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_shrink
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108bbbc)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - kernel/fork.c:copy_mm
```
```
In mm/shmem.c (ffffffff8120f855)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
```
In mm/util.c (ffffffff81214c37)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
```
```
In mm/mmap.c (ffffffff81236872)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_munmap
  - mm/mmap.c:mmap_region
```
```
In mm/mprotect.c (ffffffff8123a1e1)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/mprotect.c:mprotect_fixup
```
```
In mm/mremap.c (ffffffff8123b8af)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:mremap_to
  - mm/mremap.c:move_vma
```
```
In mm/swapfile.c (ffffffff8124c9a4)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffffffff8124f209)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_shrink
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81095669)
Location: include/linux/mman.h:71
Inline: True
```
```
In mm/shmem.c (ffffffff812229b9)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
```
In mm/util.c (ffffffff81227b13)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
```
```
In mm/mmap.c (ffffffff8124a142)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:mmap_region
```
```
In mm/mprotect.c (ffffffff8124e351)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/mprotect.c:mprotect_fixup
```
```
In mm/mremap.c (ffffffff8124fc15)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:mremap_to
  - mm/mremap.c:move_vma
```
```
In mm/swapfile.c (ffffffff81260ed1)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffffffff812636a9)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_shrink
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810979b4)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/shmem.c (ffffffff81231fba)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
```
In mm/util.c (ffffffff8123783a)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
```
```
In mm/mmap.c (ffffffff8125c444)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:mmap_region
```
```
In mm/mprotect.c (ffffffff81260699)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/mprotect.c:mprotect_fixup
```
```
In mm/mremap.c (ffffffff81261f0d)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:mremap_to
  - mm/mremap.c:move_vma
```
```
In mm/swapfile.c (ffffffff8127be24)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffffffff8127e683)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_shrink
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109e074)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/shmem.c (ffffffff8124007a)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
```
In mm/util.c (ffffffff81245a8a)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
```
```
In mm/mmap.c (ffffffff8126aba4)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:mmap_region
```
```
In mm/mprotect.c (ffffffff8126ee44)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/mprotect.c:mprotect_fixup
```
```
In mm/mremap.c (ffffffff812706dd)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:mremap_to
  - mm/mremap.c:move_vma
```
```
In mm/swapfile.c (ffffffff8128b904)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffffffff8128e0e3)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_shrink
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void vm_unacct_memory(long int pages);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a57e9)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/shmem.c (ffffffff8126e734)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
```
In mm/util.c (ffffffff812737d0)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
```
```
In mm/mmap.c (ffffffff8129cdc9)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:mmap_region
Direct callers:
  - mm/mmap.c:do_brk_flags
```
```
In mm/mprotect.c (ffffffff8129f419)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/mprotect.c:mprotect_fixup
```
```
In mm/mremap.c (ffffffff812a1267)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:mremap_to
  - mm/mremap.c:move_vma
```
```
In mm/swapfile.c (ffffffff812be7f4)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffffffff812c0a81)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_shrink
```
**Symbols:**

```
ffffffff812986d0-ffffffff812986ee: vm_unacct_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void vm_unacct_memory(long int pages);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a0fe1)
Location: include/linux/mman.h:75
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/shmem.c (ffffffff8127912f)
Location: include/linux/mman.h:75
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
```
In mm/util.c (ffffffff8127e060)
Location: include/linux/mman.h:75
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
```
```
In mm/mmap.c (ffffffff812a8179)
Location: include/linux/mman.h:75
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:mmap_region
Direct callers:
  - mm/mmap.c:do_brk_flags
```
```
In mm/mprotect.c (ffffffff812aa7d9)
Location: include/linux/mman.h:75
Inline: True
Inline callers:
  - mm/mprotect.c:mprotect_fixup
```
```
In mm/mremap.c (ffffffff812aca8e)
Location: include/linux/mman.h:75
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:mremap_to
Direct callers:
  - mm/mremap.c:move_vma
```
```
In mm/swapfile.c (ffffffff812ca3d4)
Location: include/linux/mman.h:75
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffffffff812cc4a1)
Location: include/linux/mman.h:75
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_shrink
```
**Symbols:**

```
ffffffff812a3850-ffffffff812a386e: vm_unacct_memory (STB_LOCAL)
ffffffff812aaeb0-ffffffff812aaece: vm_unacct_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void vm_unacct_memory(long int pages);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a1d58)
Location: include/linux/mman.h:75
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/shmem.c (ffffffff8127e0dd)
Location: include/linux/mman.h:75
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
```
In mm/util.c (ffffffff812831cd)
Location: include/linux/mman.h:75
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
```
```
In mm/mmap.c (ffffffff812abb87)
Location: include/linux/mman.h:75
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:mmap_region
Direct callers:
  - mm/mmap.c:do_brk_flags
```
```
In mm/mprotect.c (ffffffff812afc1b)
Location: include/linux/mman.h:75
Inline: True
Inline callers:
  - mm/mprotect.c:mprotect_fixup
```
```
In mm/mremap.c (ffffffff812b1dd5)
Location: include/linux/mman.h:75
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:mremap_to
Direct callers:
  - mm/mremap.c:move_vma
```
```
In mm/swapfile.c (ffffffff812d0f01)
Location: include/linux/mman.h:75
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffffffff812d32b1)
Location: include/linux/mman.h:75
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_shrink
```
**Symbols:**

```
ffffffff812a9080-ffffffff812a909e: vm_unacct_memory (STB_LOCAL)
ffffffff812b02c0-ffffffff812b02de: vm_unacct_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void vm_unacct_memory(long int pages);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810b3930)
Location: include/linux/mman.h:78
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/shmem.c (ffffffff812c0094)
Location: include/linux/mman.h:78
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
```
In mm/util.c (ffffffff812c138d)
Location: include/linux/mman.h:78
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
```
```
In mm/mmap.c (ffffffff812ed26e)
Location: include/linux/mman.h:78
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:mmap_region
Direct callers:
  - mm/mmap.c:do_brk_flags
```
```
In mm/mprotect.c (ffffffff812f146b)
Location: include/linux/mman.h:78
Inline: True
Inline callers:
  - mm/mprotect.c:mprotect_fixup
```
```
In mm/mremap.c (ffffffff812f39b0)
Location: include/linux/mman.h:78
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:mremap_to
Direct callers:
  - mm/mremap.c:move_vma
```
```
In mm/swapfile.c (ffffffff813165f2)
Location: include/linux/mman.h:78
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffffffff81318d48)
Location: include/linux/mman.h:78
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_shrink
```
**Symbols:**

```
ffffffff812ea6f0-ffffffff812ea70e: vm_unacct_memory (STB_LOCAL)
ffffffff812f1940-ffffffff812f195e: vm_unacct_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void vm_unacct_memory(long int pages);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810c9b7b)
Location: include/linux/mman.h:78
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/shmem.c (ffffffff8131c8ff)
Location: include/linux/mman.h:78
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
```
In mm/util.c (ffffffff8131e379)
Location: include/linux/mman.h:78
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
```
```
In mm/mmap.c (ffffffff8135060e)
Location: include/linux/mman.h:78
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:mmap_region
Direct callers:
  - mm/mmap.c:do_brk_flags
```
```
In mm/mprotect.c (ffffffff81355128)
Location: include/linux/mman.h:78
Inline: True
Inline callers:
  - mm/mprotect.c:mprotect_fixup
```
```
In mm/mremap.c (ffffffff81357842)
Location: include/linux/mman.h:78
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:move_vma
```
```
In mm/swapfile.c (ffffffff813817a2)
Location: include/linux/mman.h:78
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffffffff8134d340-ffffffff8134d368: vm_unacct_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810e6f3f)
Location: include/linux/mman.h:78
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/shmem.c (ffffffff813905ad)
Location: include/linux/mman.h:78
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
```
In mm/util.c (ffffffff81391e08)
Location: include/linux/mman.h:78
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
```
```
In mm/mmap.c (ffffffff813ca1fa)
Location: include/linux/mman.h:78
Inline: True
Inline callers:
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_mas_align_munmap
```
```
In mm/mprotect.c (ffffffff813cf640)
Location: include/linux/mman.h:78
Inline: True
Inline callers:
  - mm/mprotect.c:mprotect_fixup
```
```
In mm/mremap.c (ffffffff813d1dcf)
Location: include/linux/mman.h:78
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:move_vma
```
```
In mm/swapfile.c (ffffffff813fff2c)
Location: include/linux/mman.h:78
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f29ff)
Location: include/linux/mman.h:78
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/shmem.c (ffffffff813c2ee3)
Location: include/linux/mman.h:78
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
```
In mm/util.c (ffffffff813c4808)
Location: include/linux/mman.h:78
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
```
```
In mm/mmap.c (ffffffff813fe771)
Location: include/linux/mman.h:78
Inline: True
Inline callers:
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_vmi_align_munmap
```
```
In mm/mprotect.c (ffffffff81404033)
Location: include/linux/mman.h:78
Inline: True
Inline callers:
  - mm/mprotect.c:mprotect_fixup
```
```
In mm/mremap.c (ffffffff81406c17)
Location: include/linux/mman.h:78
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:move_vma
```
```
In mm/swapfile.c (ffffffff81432ddb)
Location: include/linux/mman.h:78
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810fb6b5)
Location: include/linux/mman.h:82
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/shmem.c (ffffffff813ec3d2)
Location: include/linux/mman.h:82
Inline: True
Inline callers:
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_inode_unacct_blocks
  - mm/shmem.c:shmem_inode_acct_blocks
```
```
In mm/util.c (ffffffff813ef288)
Location: include/linux/mman.h:82
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
```
```
In mm/mmap.c (ffffffff8142abe7)
Location: include/linux/mman.h:82
Inline: True
Inline callers:
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_vmi_align_munmap
```
```
In mm/mprotect.c (ffffffff81430572)
Location: include/linux/mman.h:82
Inline: True
Inline callers:
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
```
```
In mm/mremap.c (ffffffff814332c4)
Location: include/linux/mman.h:82
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:move_vma
```
```
In mm/swapfile.c (ffffffff8146c1fb)
Location: include/linux/mman.h:82
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f2c20)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/shmem.c (ffff8000102d3334)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
```
In mm/util.c (ffff8000102d911c)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
```
```
In mm/mmap.c (ffff8000103022d4)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:mmap_region
```
```
In mm/mprotect.c (ffff800010305960)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/mprotect.c:mprotect_fixup
```
```
In mm/mremap.c (ffff800010306aa4)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/mremap.c:__arm64_sys_mremap
  - mm/mremap.c:__arm64_sys_mremap
  - mm/mremap.c:move_vma
```
```
In mm/swapfile.c (ffff800010326cb4)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffff80001032a3d4)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_shrink
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c035155c)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/shmem.c (c04fb350)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
```
In mm/util.c (c05002e8)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
```
```
In mm/mmap.c (c05209e8)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:mmap_region
```
```
In mm/mprotect.c (c052389c)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/mprotect.c:mprotect_fixup
```
```
In mm/mremap.c (c0524738)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/mremap.c:__se_sys_mremap
  - mm/mremap.c:__se_sys_mremap
  - mm/mremap.c:move_vma
```
```
In mm/swapfile.c (c053e408)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (c0540c44)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_shrink
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c0000000001388bc)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/shmem.c (c000000000392010)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
```
In mm/util.c (c000000000398ca4)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
```
```
In mm/mmap.c (c0000000003ce6c0)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:mmap_region
```
```
In mm/mprotect.c (c0000000003d2ec0)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/mprotect.c:mprotect_fixup
```
```
In mm/mremap.c (c0000000003d4918)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/mremap.c:__se_sys_mremap
  - mm/mremap.c:__se_sys_mremap
  - mm/mremap.c:move_vma
```
```
In mm/swapfile.c (c0000000003fd840)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (c000000000401610)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_shrink
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000bf83c)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/shmem.c (ffffffe0001ee596)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
```
In mm/util.c (ffffffe0001f352e)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
```
```
In mm/mmap.c (ffffffe00020f296)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:mmap_region
```
```
In mm/mprotect.c (ffffffe0002116e4)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/mprotect.c:mprotect_fixup
```
```
In mm/mremap.c (ffffffe000212100)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/mremap.c:__se_sys_mremap
  - mm/mremap.c:__se_sys_mremap
  - mm/mremap.c:move_vma
```
```
In mm/swapfile.c (ffffffe000226d4c)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffffffe0002298e8)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_shrink
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81097994)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/shmem.c (ffffffff812386ca)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
```
In mm/util.c (ffffffff8123e0da)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
```
```
In mm/mmap.c (ffffffff812631f4)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:mmap_region
```
```
In mm/mprotect.c (ffffffff81267494)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/mprotect.c:mprotect_fixup
```
```
In mm/mremap.c (ffffffff81268d2d)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:mremap_to
  - mm/mremap.c:move_vma
```
```
In mm/swapfile.c (ffffffff81283ee4)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffffffff812866c3)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_shrink
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81086414)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/shmem.c (ffffffff8122b6de)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
```
In mm/util.c (ffffffff812310da)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
```
```
In mm/mmap.c (ffffffff81255614)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:mmap_region
```
```
In mm/mprotect.c (ffffffff812597e4)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/mprotect.c:mprotect_fixup
```
```
In mm/mremap.c (ffffffff8125b01d)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:mremap_to
  - mm/mremap.c:move_vma
```
```
In mm/swapfile.c (ffffffff81275d74)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffffffff81278523)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_shrink
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81097944)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/shmem.c (ffffffff8123646a)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
```
In mm/util.c (ffffffff8123be7a)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
```
```
In mm/mmap.c (ffffffff81260f94)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:mmap_region
```
```
In mm/mprotect.c (ffffffff81265234)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/mprotect.c:mprotect_fixup
```
```
In mm/mremap.c (ffffffff81266acd)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:mremap_to
  - mm/mremap.c:move_vma
```
```
In mm/swapfile.c (ffffffff81281cf4)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffffffff812844d3)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_shrink
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109f544)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/shmem.c (ffffffff81246755)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
```
In mm/util.c (ffffffff8124b58a)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
```
```
In mm/mmap.c (ffffffff81270964)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:mmap_region
```
```
In mm/mprotect.c (ffffffff81274be4)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/mprotect.c:mprotect_fixup
```
```
In mm/mremap.c (ffffffff8127646d)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:mremap_to
  - mm/mremap.c:move_vma
```
```
In mm/swapfile.c (ffffffff81291a02)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffffffff8129408d)
Location: include/linux/mman.h:71
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_shrink
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
