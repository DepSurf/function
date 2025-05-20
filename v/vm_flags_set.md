# Function: <code>vm_flags_set</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff81091b66)
Location: include/linux/mm.h:797
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_mmap
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81097dac)
Location: include/linux/mm.h:797
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_mmap
```
```
In arch/x86/mm/pat/memtype.c (ffffffff810d2d96)
Location: include/linux/mm.h:797
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
```
```
In kernel/relay.c (ffffffff81262efb)
Location: include/linux/mm.h:797
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_mmap
```
```
In kernel/events/core.c (ffffffff81374a61)
Location: include/linux/mm.h:797
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/shmem.c (ffffffff813bce5e)
Location: include/linux/mm.h:797
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mmap
```
```
In mm/memory.c (ffffffff813f39a2)
Location: include/linux/mm.h:797
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_pages
```
```
In mm/mmap.c (ffffffff813fefe2)
Location: include/linux/mm.h:797
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
```
```
In mm/mremap.c (ffffffff81405fc9)
Location: include/linux/mm.h:797
Inline: True
Inline callers:
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
```
```
In mm/vmalloc.c (ffffffff814182de)
Location: include/linux/mm.h:797
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
```
```
In mm/ksm.c (ffffffff81452890)
Location: include/linux/mm.h:797
Inline: True
```
```
In mm/secretmem.c (ffffffff8149fca4)
Location: include/linux/mm.h:797
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_mmap
```
```
In fs/aio.c (ffffffff81527ac5)
Location: include/linux/mm.h:797
Inline: True
Inline callers:
  - fs/aio.c:aio_ring_mmap
```
```
In fs/ext4/file.c (ffffffff815a2716)
Location: include/linux/mm.h:797
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_mmap
```
```
In fs/hugetlbfs/inode.c (ffffffff8162e2d2)
Location: include/linux/mm.h:797
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fuse/dax.c (ffffffff8166b1a1)
Location: include/linux/mm.h:797
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_mmap
```
```
In security/selinux/selinuxfs.c (ffffffff816b5c09)
Location: include/linux/mm.h:797
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff819823c2)
Location: include/linux/mm.h:797
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mmap
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mmap
```
```
In drivers/scsi/sg.c (ffffffff81bf1773)
Location: include/linux/mm.h:797
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_mmap
```
```
In drivers/usb/core/devio.c (ffffffff81c99430)
Location: include/linux/mm.h:797
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In net/ipv4/tcp.c (ffffffff81f0a737)
Location: include/linux/mm.h:797
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_mmap
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
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff81098f16)
Location: include/linux/mm.h:838
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_mmap
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff8109f31c)
Location: include/linux/mm.h:838
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_mmap
```
```
In arch/x86/mm/pat/memtype.c (ffffffff810db526)
Location: include/linux/mm.h:838
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
```
```
In kernel/relay.c (ffffffff8127d11b)
Location: include/linux/mm.h:838
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_mmap
```
```
In kernel/events/core.c (ffffffff8139dd91)
Location: include/linux/mm.h:838
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/shmem.c (ffffffff813e7cae)
Location: include/linux/mm.h:838
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mmap
```
```
In mm/memory.c (ffffffff8141e294)
Location: include/linux/mm.h:838
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_pages
```
```
In mm/mmap.c (ffffffff8142b4f3)
Location: include/linux/mm.h:838
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
```
```
In mm/mremap.c (ffffffff81432602)
Location: include/linux/mm.h:838
Inline: True
Inline callers:
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
```
```
In mm/vmalloc.c (ffffffff81444e2e)
Location: include/linux/mm.h:838
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
```
```
In mm/ksm.c (ffffffff8148ce80)
Location: include/linux/mm.h:838
Inline: True
```
```
In mm/secretmem.c (ffffffff814cf3f4)
Location: include/linux/mm.h:838
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_mmap
```
```
In fs/aio.c (ffffffff8155c855)
Location: include/linux/mm.h:838
Inline: True
Inline callers:
  - fs/aio.c:aio_ring_mmap
```
```
In fs/ext4/file.c (ffffffff815db226)
Location: include/linux/mm.h:838
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_mmap
```
```
In fs/hugetlbfs/inode.c (ffffffff81667782)
Location: include/linux/mm.h:838
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fuse/dax.c (ffffffff816a54e1)
Location: include/linux/mm.h:838
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_mmap
```
```
In security/selinux/selinuxfs.c (ffffffff816f2799)
Location: include/linux/mm.h:838
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff819c9b49)
Location: include/linux/mm.h:838
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mmap
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mmap
```
```
In drivers/scsi/sg.c (ffffffff81c47033)
Location: include/linux/mm.h:838
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_mmap
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9d094)
Location: include/linux/mm.h:838
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem.c:drm_gem_mmap_obj
```
```
In drivers/gpu/drm/drm_gem_shmem_helper.c (ffffffff81cbe4b6)
Location: include/linux/mm.h:838
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff81d4e19f)
Location: include/linux/mm.h:838
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In net/ipv4/tcp.c (ffffffff81fce7b7)
Location: include/linux/mm.h:838
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_mmap
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
