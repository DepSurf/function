# Function: <code>remap_pfn_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int remap_pfn_range(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811c0850)
Location: mm/memory.c:1694
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/entry/vdso/vma.c:map_vdso
  - mm/memory.c:vm_iomap_memory
  - fs/proc/vmcore.c:remap_oldmem_pfn_range
  - fs/proc/vmcore.c:mmap_vmcore
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap
  - drivers/char/mem.c:mmap_mem
  - drivers/char/agp/frontend.c:agp_mmap
  - drivers/base/dma-mapping.c:dma_common_mmap
  - arch/x86/pci/i386.c:pci_mmap_page_range
```
**Symbols:**

```
ffffffff811c0850-ffffffff811c0c77: remap_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int remap_pfn_range(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811dc240)
Location: mm/memory.c:1756
Inline: False
Direct callers:
  - mm/memory.c:vm_iomap_memory
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:remap_oldmem_pfn_range
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap
  - drivers/char/mem.c:mmap_mem
  - drivers/char/agp/frontend.c:agp_mmap
  - drivers/base/dma-mapping.c:dma_common_mmap
  - drivers/usb/core/devio.c:usbdev_mmap
  - arch/x86/pci/i386.c:pci_mmap_page_range
```
**Symbols:**

```
ffffffff811dc240-ffffffff811dc670: remap_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int remap_pfn_range(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811ebd50)
Location: mm/memory.c:1756
Inline: False
Direct callers:
  - mm/memory.c:vm_iomap_memory
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:remap_oldmem_pfn_range
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap
  - drivers/char/mem.c:mmap_mem
  - drivers/char/agp/frontend.c:agp_mmap
  - drivers/base/dma-mapping.c:dma_common_mmap
  - drivers/usb/core/devio.c:usbdev_mmap
  - arch/x86/pci/i386.c:pci_mmap_page_range
```
**Symbols:**

```
ffffffff811ebd50-ffffffff811ec17e: remap_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int remap_pfn_range(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f6c50)
Location: mm/memory.c:1942
Inline: False
Direct callers:
  - mm/memory.c:vm_iomap_memory
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:remap_oldmem_pfn_range
  - drivers/pci/mmap.c:pci_mmap_resource_range
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap
  - drivers/char/mem.c:mmap_mem
  - drivers/char/agp/frontend.c:agp_mmap
  - drivers/base/dma-mapping.c:dma_common_mmap
  - drivers/usb/core/devio.c:usbdev_mmap
```
**Symbols:**

```
ffffffff811f6c50-ffffffff811f7094: remap_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int remap_pfn_range(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8120f180)
Location: mm/memory.c:2059
Inline: False
Direct callers:
  - mm/memory.c:vm_iomap_memory
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:remap_oldmem_pfn_range
  - drivers/pci/mmap.c:pci_mmap_resource_range
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap
  - drivers/char/mem.c:mmap_mem
  - drivers/char/agp/frontend.c:agp_mmap
  - drivers/base/dma-mapping.c:dma_common_mmap
  - drivers/usb/core/devio.c:usbdev_mmap
```
**Symbols:**

```
ffffffff8120f180-ffffffff8120f638: remap_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int remap_pfn_range(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122ef10)
Location: mm/memory.c:2101
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_common_mmap
  - mm/memory.c:vm_iomap_memory
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:remap_oldmem_pfn_range
  - drivers/pci/mmap.c:pci_mmap_resource_range
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap
  - drivers/char/mem.c:mmap_mem
  - drivers/char/agp/frontend.c:agp_mmap
  - drivers/usb/core/devio.c:usbdev_mmap
  - net/xdp/xsk.c:xsk_mmap
```
**Symbols:**

```
ffffffff8122ef10-ffffffff8122f3d4: remap_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int remap_pfn_range(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81243290)
Location: mm/memory.c:1837
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
  - kernel/dma/mapping.c:dma_common_mmap
  - mm/memory.c:vm_iomap_memory
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:remap_oldmem_pfn_range
  - drivers/pci/mmap.c:pci_mmap_resource_range
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap
  - drivers/char/mem.c:mmap_mem
  - drivers/char/agp/frontend.c:agp_mmap
  - drivers/usb/core/devio.c:usbdev_mmap
  - net/xdp/xsk.c:xsk_mmap
```
**Symbols:**

```
ffffffff81243290-ffffffff8124376b: remap_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int remap_pfn_range(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812550c0)
Location: mm/memory.c:1892
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
  - kernel/dma/mapping.c:dma_common_mmap
  - kernel/dma/coherent.c:__dma_mmap_from_coherent
  - mm/memory.c:vm_iomap_memory
  - fs/io_uring.c:io_uring_mmap
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:remap_oldmem_pfn_range
  - drivers/pci/mmap.c:pci_mmap_resource_range
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap
  - drivers/char/mem.c:mmap_mem
  - drivers/char/agp/frontend.c:agp_mmap
  - drivers/usb/core/devio.c:usbdev_mmap
  - net/xdp/xsk.c:xsk_mmap
```
**Symbols:**

```
ffffffff812550c0-ffffffff812555b7: remap_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int remap_pfn_range(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81263630)
Location: mm/memory.c:1897
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
  - kernel/dma/mapping.c:dma_common_mmap
  - mm/memory.c:vm_iomap_memory
  - fs/io_uring.c:io_uring_mmap
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:remap_oldmem_pfn_range
  - drivers/pci/mmap.c:pci_mmap_resource_range
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap
  - drivers/char/mem.c:mmap_mem
  - drivers/char/agp/frontend.c:agp_mmap
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap
  - drivers/usb/core/devio.c:usbdev_mmap
  - net/xdp/xsk.c:xsk_mmap
```
**Symbols:**

```
ffffffff81263630-ffffffff81263b27: remap_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int remap_pfn_range(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812938a0)
Location: mm/memory.c:2096
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
  - kernel/dma/mapping.c:dma_common_mmap
  - kernel/dma/direct.c:dma_direct_mmap
  - mm/memory.c:vm_iomap_memory
  - fs/io_uring.c:io_uring_mmap
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:remap_oldmem_pfn_range
  - security/selinux/selinuxfs.c:sel_mmap_handle_status
  - drivers/pci/mmap.c:pci_mmap_resource_range
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap
  - drivers/char/mem.c:mmap_mem
  - drivers/char/agp/frontend.c:agp_mmap
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap_fault
  - drivers/usb/core/devio.c:usbdev_mmap
  - net/xdp/xsk.c:xsk_mmap
```
**Symbols:**

```
ffffffff812938a0-ffffffff81293cc9: remap_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int remap_pfn_range(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129e190)
Location: mm/memory.c:2270
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
  - kernel/dma/direct.c:dma_direct_mmap
  - kernel/dma/ops_helpers.c:dma_common_mmap
  - mm/memory.c:vm_iomap_memory
  - fs/io_uring.c:io_uring_mmap
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:remap_oldmem_pfn_range
  - security/selinux/selinuxfs.c:sel_mmap_handle_status
  - drivers/pci/mmap.c:pci_mmap_resource_range
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap
  - drivers/char/mem.c:mmap_mem
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
  - drivers/dma-buf/heaps/system_heap.c:system_heap_mmap
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap_fault
  - drivers/usb/core/devio.c:usbdev_mmap
  - net/xdp/xsk.c:xsk_mmap
```
**Symbols:**

```
ffffffff8129e190-ffffffff8129e5e9: remap_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int remap_pfn_range(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a3df0)
Location: mm/memory.c:2345
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
  - kernel/dma/mapping.c:dma_mmap_pages
  - kernel/dma/direct.c:dma_direct_mmap
  - kernel/dma/ops_helpers.c:dma_common_mmap
  - mm/memory.c:vm_iomap_memory
  - fs/io_uring.c:io_uring_mmap
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:remap_oldmem_pfn_range
  - security/selinux/selinuxfs.c:sel_mmap_handle_status
  - drivers/pci/mmap.c:pci_mmap_resource_range
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap
  - drivers/char/mem.c:mmap_mem
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
  - drivers/dma-buf/heaps/system_heap.c:system_heap_mmap
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap_fault
  - drivers/usb/core/devio.c:usbdev_mmap
  - net/xdp/xsk.c:xsk_mmap
```
**Symbols:**

```
ffffffff812a3df0-ffffffff812a3e89: remap_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int remap_pfn_range(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e5110)
Location: mm/memory.c:2440
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
  - kernel/dma/mapping.c:dma_mmap_pages
  - kernel/dma/direct.c:dma_direct_mmap
  - kernel/dma/ops_helpers.c:dma_common_mmap
  - mm/memory.c:vm_iomap_memory
  - fs/io_uring.c:io_uring_mmap
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:remap_oldmem_pfn_range
  - security/selinux/selinuxfs.c:sel_mmap_handle_status
  - drivers/pci/mmap.c:pci_mmap_resource_range
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap
  - drivers/char/mem.c:mmap_mem
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
  - drivers/dma-buf/heaps/system_heap.c:system_heap_mmap
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_mmap_fault
  - drivers/usb/core/devio.c:usbdev_mmap
  - net/xdp/xsk.c:xsk_mmap
```
**Symbols:**

```
ffffffff812e5110-ffffffff812e51a9: remap_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int remap_pfn_range(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81346ab0)
Location: mm/memory.c:2533
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
  - kernel/dma/mapping.c:dma_mmap_pages
  - kernel/dma/direct.c:dma_direct_mmap
  - kernel/dma/ops_helpers.c:dma_common_mmap
  - mm/memory.c:vm_iomap_memory
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:remap_oldmem_pfn_range
  - security/selinux/selinuxfs.c:sel_mmap_handle_status
  - io_uring/io_uring.c:io_uring_mmap
  - drivers/pci/mmap.c:pci_mmap_resource_range
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap
  - drivers/char/mem.c:mmap_mem
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
  - drivers/dma-buf/heaps/system_heap.c:system_heap_mmap
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_mmap_fault
  - drivers/usb/core/devio.c:usbdev_mmap
  - net/xdp/xsk.c:xsk_mmap
```
**Symbols:**

```
ffffffff81346ab0-ffffffff81346b67: remap_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int remap_pfn_range(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813beea0)
Location: mm/memory.c:2504
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
  - kernel/dma/mapping.c:dma_mmap_pages
  - kernel/dma/direct.c:dma_direct_mmap
  - kernel/dma/ops_helpers.c:dma_common_mmap
  - mm/memory.c:vm_iomap_memory
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:remap_oldmem_pfn_range
  - security/selinux/selinuxfs.c:sel_mmap_handle_status
  - io_uring/io_uring.c:io_uring_mmap
  - drivers/pci/mmap.c:pci_mmap_resource_range
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap
  - drivers/char/mem.c:mmap_mem
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
  - drivers/dma-buf/heaps/system_heap.c:system_heap_mmap
  - drivers/usb/core/devio.c:usbdev_mmap
  - net/xdp/xsk.c:xsk_mmap
```
**Symbols:**

```
ffffffff813beea0-ffffffff813bef57: remap_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int remap_pfn_range(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813f3b10)
Location: mm/memory.c:2504
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
  - kernel/dma/mapping.c:dma_mmap_pages
  - kernel/dma/direct.c:dma_direct_mmap
  - kernel/dma/ops_helpers.c:dma_common_mmap
  - mm/memory.c:vm_iomap_memory
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:remap_oldmem_pfn_range
  - security/selinux/selinuxfs.c:sel_mmap_handle_status
  - io_uring/io_uring.c:io_uring_mmap
  - drivers/pci/mmap.c:pci_mmap_resource_range
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap
  - drivers/char/mem.c:mmap_mem
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
  - drivers/dma-buf/heaps/system_heap.c:system_heap_mmap
  - drivers/usb/core/devio.c:usbdev_mmap
```
**Symbols:**

```
ffffffff813f3b10-ffffffff813f3bcc: remap_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int remap_pfn_range(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8141e7a0)
Location: mm/memory.c:2527
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
  - kernel/dma/mapping.c:dma_mmap_pages
  - kernel/dma/direct.c:dma_direct_mmap
  - kernel/dma/ops_helpers.c:dma_common_mmap
  - mm/memory.c:vm_iomap_memory
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:remap_oldmem_pfn_range
  - security/selinux/selinuxfs.c:sel_mmap_handle_status
  - io_uring/io_uring.c:io_uring_mmap
  - drivers/pci/mmap.c:pci_mmap_resource_range
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap
  - drivers/char/mem.c:mmap_mem
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
  - drivers/dma-buf/heaps/system_heap.c:system_heap_mmap
  - drivers/usb/core/devio.c:usbdev_mmap
```
**Symbols:**

```
ffffffff8141e7a0-ffffffff8141e85c: remap_pfn_range (STB_GLOBAL)
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
int remap_pfn_range(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102fa850)
Location: mm/memory.c:1897
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_common_mmap
  - kernel/dma/coherent.c:__dma_mmap_from_coherent
  - mm/memory.c:vm_iomap_memory
  - fs/io_uring.c:io_uring_mmap
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:remap_oldmem_pfn_range
  - drivers/pci/mmap.c:pci_mmap_resource_range
  - drivers/video/fbdev/amba-clcd.c:clcdfb_of_vram_mmap
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap
  - drivers/char/mem.c:mmap_mem
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
  - drivers/usb/core/devio.c:usbdev_mmap
  - net/xdp/xsk.c:xsk_mmap
```
**Symbols:**

```
ffff8000102fa850-ffff8000102fac00: remap_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int remap_pfn_range(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0517950)
Location: mm/memory.c:1897
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_common_mmap
  - kernel/dma/coherent.c:__dma_mmap_from_coherent
  - mm/memory.c:vm_iomap_memory
  - fs/io_uring.c:io_uring_mmap
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:remap_oldmem_pfn_range
  - drivers/pci/mmap.c:pci_mmap_resource_range
  - drivers/video/fbdev/amba-clcd.c:clcdfb_of_vram_mmap
  - drivers/char/mem.c:mmap_mem
  - drivers/usb/core/devio.c:usbdev_mmap
  - net/xdp/xsk.c:xsk_mmap
```
**Symbols:**

```
c0517950-c0517bb0: remap_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int remap_pfn_range(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c4ea0)
Location: mm/memory.c:1897
Inline: False
Direct callers:
  - arch/powerpc/kernel/proc_powerpc.c:page_map_mmap
  - arch/powerpc/kernel/pci-common.c:pci_mmap_legacy_page_range
  - kernel/dma/mapping.c:dma_common_mmap
  - kernel/dma/coherent.c:__dma_mmap_from_coherent
  - mm/memory.c:vm_iomap_memory
  - fs/io_uring.c:io_uring_mmap
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:remap_oldmem_pfn_range
  - security/selinux/selinuxfs.c:sel_mmap_handle_status
  - drivers/pci/mmap.c:pci_mmap_resource_range
  - drivers/char/mem.c:mmap_mem
  - drivers/char/agp/frontend.c:agp_mmap
  - drivers/char/agp/frontend.c:agp_mmap
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap
  - drivers/vfio/pci/vfio_pci_nvlink2.c:vfio_pci_npu2_mmap
  - drivers/usb/core/devio.c:usbdev_mmap
  - net/xdp/xsk.c:xsk_mmap
```
**Symbols:**

```
c0000000003c4ea0-c0000000003c5510: remap_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int remap_pfn_range(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe00020a316)
Location: mm/memory.c:1897
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_common_mmap
  - kernel/dma/coherent.c:__dma_mmap_from_coherent
  - mm/memory.c:vm_iomap_memory
  - fs/io_uring.c:io_uring_mmap
  - drivers/char/mem.c:mmap_mem
  - drivers/usb/core/devio.c:usbdev_mmap
  - net/xdp/xsk.c:xsk_mmap
```
**Symbols:**

```
ffffffe00020a316-ffffffe00020a58a: remap_pfn_range (STB_GLOBAL)
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
int remap_pfn_range(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125bc80)
Location: mm/memory.c:1897
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
  - kernel/dma/mapping.c:dma_common_mmap
  - mm/memory.c:vm_iomap_memory
  - fs/io_uring.c:io_uring_mmap
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:remap_oldmem_pfn_range
  - drivers/pci/mmap.c:pci_mmap_resource_range
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap
  - drivers/char/mem.c:mmap_mem
  - drivers/char/agp/frontend.c:agp_mmap
  - drivers/usb/core/devio.c:usbdev_mmap
  - net/xdp/xsk.c:xsk_mmap
```
**Symbols:**

```
ffffffff8125bc80-ffffffff8125c177: remap_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int remap_pfn_range(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124e240)
Location: mm/memory.c:1897
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
  - kernel/dma/mapping.c:dma_common_mmap
  - mm/memory.c:vm_iomap_memory
  - fs/io_uring.c:io_uring_mmap
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:remap_oldmem_pfn_range
  - drivers/pci/mmap.c:pci_mmap_resource_range
  - drivers/char/mem.c:mmap_mem
  - drivers/char/agp/frontend.c:agp_mmap
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap
  - drivers/usb/core/devio.c:usbdev_mmap
  - net/xdp/xsk.c:xsk_mmap
```
**Symbols:**

```
ffffffff8124e240-ffffffff8124e704: remap_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int remap_pfn_range(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81259a20)
Location: mm/memory.c:1897
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
  - kernel/dma/mapping.c:dma_common_mmap
  - mm/memory.c:vm_iomap_memory
  - fs/io_uring.c:io_uring_mmap
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:remap_oldmem_pfn_range
  - drivers/pci/mmap.c:pci_mmap_resource_range
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap
  - drivers/char/mem.c:mmap_mem
  - drivers/char/agp/frontend.c:agp_mmap
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap
  - drivers/usb/core/devio.c:usbdev_mmap
  - net/xdp/xsk.c:xsk_mmap
```
**Symbols:**

```
ffffffff81259a20-ffffffff81259f17: remap_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int remap_pfn_range(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81269420)
Location: mm/memory.c:1897
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
  - kernel/dma/mapping.c:dma_common_mmap
  - mm/memory.c:vm_iomap_memory
  - fs/io_uring.c:io_uring_mmap
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:remap_oldmem_pfn_range
  - drivers/pci/mmap.c:pci_mmap_resource_range
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap
  - drivers/char/mem.c:mmap_mem
  - drivers/char/agp/frontend.c:agp_mmap
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap
  - drivers/usb/core/devio.c:usbdev_mmap
  - net/xdp/xsk.c:xsk_mmap
```
**Symbols:**

```
ffffffff81269420-ffffffff81269915: remap_pfn_range (STB_GLOBAL)
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
