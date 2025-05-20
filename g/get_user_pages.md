# Function: <code>get_user_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int get_user_pages(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, int write, int force, struct page **pages, struct vm_area_struct **vmas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811bb4a0)
Location: mm/gup.c:855
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_resolve_fault
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_notify_resume
  - mm/memory.c:__access_remote_vm
  - mm/mempolicy.c:do_get_mempolicy
  - security/tomoyo/domain.c:tomoyo_dump_page
```
**Symbols:**

```
ffffffff811bb4a0-ffffffff811bb4f4: get_user_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, int write, int force, struct page **pages, struct vm_area_struct **vmas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811d5e00)
Location: mm/gup.c:978
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_resolve_fault
  - mm/mempolicy.c:do_get_mempolicy
```
**Symbols:**

```
ffffffff811d5e00-ffffffff811d5e69: get_user_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811e5f20)
Location: mm/gup.c:982
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - mm/mempolicy.c:SYSC_get_mempolicy
```
**Symbols:**

```
ffffffff811e5f20-ffffffff811e5f71: get_user_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811f0580)
Location: mm/gup.c:1063
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - mm/mempolicy.c:SYSC_get_mempolicy
```
**Symbols:**

```
ffffffff811f0580-ffffffff811f05c4: get_user_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812079c0)
Location: mm/gup.c:1088
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - mm/gup.c:get_user_pages_longterm
  - mm/gup.c:get_user_pages_longterm
  - mm/mempolicy.c:SYSC_get_mempolicy
```
**Symbols:**

```
ffffffff812079c0-ffffffff81207a04: get_user_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81228570)
Location: mm/gup.c:1094
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - mm/gup.c:get_user_pages_longterm
  - mm/gup.c:get_user_pages_longterm
  - mm/mempolicy.c:kernel_get_mempolicy
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
ffffffff81228570-ffffffff812285b4: get_user_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8123bd90)
Location: mm/gup.c:1119
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - mm/gup.c:get_user_pages_longterm
  - mm/gup.c:get_user_pages_longterm
```
**Symbols:**

```
ffffffff8123bd90-ffffffff8123bdd4: get_user_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8124dac0)
Location: mm/gup.c:1614
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - fs/io_uring.c:io_sqe_buffer_register
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
ffffffff8124dac0-ffffffff8124daf6: get_user_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8125bff0)
Location: mm/gup.c:1617
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - fs/io_uring.c:io_sqe_buffer_register
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
ffffffff8125bff0-ffffffff8125c026: get_user_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8128a4a0)
Location: mm/gup.c:1977
Inline: False
```
**Symbols:**

```
ffffffff8128a4a0-ffffffff8128a4e9: get_user_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81294040)
Location: mm/gup.c:1835
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
**Symbols:**

```
ffffffff81294040-ffffffff812940c6: get_user_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81299af0)
Location: mm/gup.c:1901
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
**Symbols:**

```
ffffffff81299af0-ffffffff81299b56: get_user_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812da490)
Location: mm/gup.c:1989
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
**Symbols:**

```
ffffffff812da490-ffffffff812da4e3: get_user_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81339eb0)
Location: mm/gup.c:2178
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
**Symbols:**

```
ffffffff81339eb0-ffffffff81339f39: get_user_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813b1b30)
Location: mm/gup.c:2215
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
**Symbols:**

```
ffffffff813b1b30-ffffffff813b1bbb: get_user_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813e5ac0)
Location: mm/gup.c:2361
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
**Symbols:**

```
ffffffff813e5ac0-ffffffff813e5dd7: get_user_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81410560)
Location: mm/gup.c:2379
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
**Symbols:**

```
ffffffff81410560-ffffffff8141090f: get_user_pages (STB_GLOBAL)
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
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffff8000102f33c0)
Location: mm/gup.c:1617
Inline: False
Direct callers:
  - virt/kvm/kvm_main.c:__gfn_to_pfn_memslot
  - fs/io_uring.c:io_sqe_buffer_register
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
ffff8000102f33c0-ffff8000102f3424: get_user_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (c0515720)
Location: mm/gup.c:1617
Inline: False
Direct callers:
  - fs/io_uring.c:io_sqe_buffer_register
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
c0515720-c0515778: get_user_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (c0000000003b9f30)
Location: mm/gup.c:1617
Inline: False
Direct callers:
  - arch/powerpc/mm/book3s64/iommu_api.c:mm_iommu_do_alloc
  - fs/io_uring.c:io_sqe_buffer_register
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
c0000000003b9f30-c0000000003b9f6c: get_user_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffe000205658)
Location: mm/gup.c:1617
Inline: False
Direct callers:
  - fs/io_uring.c:io_sqe_buffer_register
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
ffffffe000205658-ffffffe0002056aa: get_user_pages (STB_GLOBAL)
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
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81254640)
Location: mm/gup.c:1617
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - fs/io_uring.c:io_sqe_buffer_register
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
ffffffff81254640-ffffffff81254676: get_user_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81247290)
Location: mm/gup.c:1617
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - fs/io_uring.c:io_sqe_buffer_register
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
ffffffff81247290-ffffffff812472c6: get_user_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812523e0)
Location: mm/gup.c:1617
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - fs/io_uring.c:io_sqe_buffer_register
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
ffffffff812523e0-ffffffff81252416: get_user_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81261d90)
Location: mm/gup.c:1617
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - fs/io_uring.c:io_sqe_buffer_register
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
ffffffff81261d90-ffffffff81261dc6: get_user_pages (STB_GLOBAL)
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
<b>Param removed. </b>
<code>struct task_struct *tsk</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mm_struct *mm</code>
</li>
<li>
<b>Param reordered. </b>
<code>tsk, mm, start, nr_pages, write, force, pages, vmas</code> ➡️ <code>start, nr_pages, write, force, pages, vmas</code>
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
<code>unsigned int gup_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int write</code>
</li>
<li>
<b>Param removed. </b>
<code>int force</code>
</li>
<li>
<b>Param reordered. </b>
<code>start, nr_pages, write, force, pages, vmas</code> ➡️ <code>start, nr_pages, gup_flags, pages, vmas</code>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct **vmas</code>
</li>
</ul>
</details>
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
