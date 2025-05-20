# Function: <code>memparse</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long long unsigned int memparse(const char *ptr, char **retptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff813e9080)
Location: lib/cmdline.c:127
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:parse_reservelow
  - arch/x86/kernel/e820.c:parse_memopt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_chunk_size_opt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_gran_size_opt
  - arch/x86/kernel/mpparse.c:parse_alloc_mptable_opt
  - arch/x86/kernel/check.c:set_corruption_check_size
  - arch/x86/mm/hugetlbpage.c:setup_hugepagesz
  - kernel/printk/printk.c:log_buf_len_setup
  - kernel/trace/trace.c:set_buf_size
  - kernel/crash_dump.c:setup_elfcorehdr
  - kernel/crash_dump.c:setup_elfcorehdr
  - mm/page_alloc.c:cmdline_parse_movablecore
  - mm/page_alloc.c:cmdline_parse_kernelcore
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/hugetlb.c:hugetlb_default_setup
  - mm/page_counter.c:page_counter_memparse
  - security/integrity/ima/ima_crypto.c:param_set_bufsize
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/xen-balloon.c:store_target
```
**Symbols:**

```
ffffffff813e9080-ffffffff813e9106: memparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long long unsigned int memparse(const char *ptr, char **retptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff8142f280)
Location: lib/cmdline.c:127
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:parse_reservelow
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memopt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_gran_size_opt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_chunk_size_opt
  - arch/x86/kernel/mpparse.c:parse_alloc_mptable_opt
  - arch/x86/kernel/check.c:set_corruption_check_size
  - arch/x86/mm/hugetlbpage.c:setup_hugepagesz
  - kernel/printk/printk.c:log_buf_len_setup
  - kernel/trace/trace.c:set_buf_size
  - kernel/crash_dump.c:setup_elfcorehdr
  - kernel/crash_dump.c:setup_elfcorehdr
  - mm/page_alloc.c:cmdline_parse_movablecore
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/hugetlb.c:hugetlb_default_setup
  - mm/page_counter.c:page_counter_memparse
  - security/integrity/ima/ima_crypto.c:param_set_bufsize
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/xen-balloon.c:store_target
```
**Symbols:**

```
ffffffff8142f280-ffffffff8142f306: memparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long long unsigned int memparse(const char *ptr, char **retptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff8144b3f0)
Location: lib/cmdline.c:127
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:parse_reservelow
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memopt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_gran_size_opt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_chunk_size_opt
  - arch/x86/kernel/mpparse.c:parse_alloc_mptable_opt
  - arch/x86/kernel/check.c:set_corruption_check_size
  - arch/x86/mm/hugetlbpage.c:setup_hugepagesz
  - kernel/printk/printk.c:log_buf_len_setup
  - kernel/trace/trace.c:set_buf_size
  - kernel/crash_dump.c:setup_elfcorehdr
  - kernel/crash_dump.c:setup_elfcorehdr
  - mm/page_alloc.c:cmdline_parse_movablecore
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/hugetlb.c:hugetlb_default_setup
  - mm/page_counter.c:page_counter_memparse
  - security/integrity/ima/ima_crypto.c:param_set_bufsize
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/xen-balloon.c:store_target
```
**Symbols:**

```
ffffffff8144b3f0-ffffffff8144b476: memparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long long unsigned int memparse(const char *ptr, char **retptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff818eb940)
Location: lib/cmdline.c:128
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:parse_reservelow
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memopt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_gran_size_opt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_chunk_size_opt
  - arch/x86/kernel/mpparse.c:parse_alloc_mptable_opt
  - arch/x86/kernel/check.c:set_corruption_check_size
  - arch/x86/mm/hugetlbpage.c:setup_hugepagesz
  - kernel/printk/printk.c:log_buf_len_setup
  - kernel/trace/trace.c:set_buf_size
  - kernel/crash_dump.c:setup_elfcorehdr
  - kernel/crash_dump.c:setup_elfcorehdr
  - mm/page_alloc.c:cmdline_parse_movablecore
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/hugetlb.c:hugetlb_default_setup
  - mm/page_counter.c:page_counter_memparse
  - security/integrity/ima/ima_crypto.c:param_set_bufsize
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/xen-balloon.c:store_target
```
**Symbols:**

```
ffffffff818eb940-ffffffff818eb9c6: memparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long long unsigned int memparse(const char *ptr, char **retptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff81971900)
Location: lib/cmdline.c:128
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:parse_reservelow
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memopt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_gran_size_opt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_chunk_size_opt
  - arch/x86/kernel/mpparse.c:parse_alloc_mptable_opt
  - arch/x86/kernel/check.c:set_corruption_check_size
  - arch/x86/mm/hugetlbpage.c:setup_hugepagesz
  - kernel/printk/printk.c:log_buf_len_setup
  - kernel/trace/trace.c:set_buf_size
  - kernel/crash_dump.c:setup_elfcorehdr
  - kernel/crash_dump.c:setup_elfcorehdr
  - mm/page_alloc.c:cmdline_parse_movablecore
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/hugetlb.c:hugetlb_default_setup
  - mm/page_counter.c:page_counter_memparse
  - security/integrity/ima/ima_crypto.c:param_set_bufsize
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/xen-balloon.c:store_target
```
**Symbols:**

```
ffffffff81971900-ffffffff8197198c: memparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long long unsigned int memparse(const char *ptr, char **retptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff819cdcd0)
Location: lib/cmdline.c:128
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:parse_reservelow
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memopt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_gran_size_opt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_chunk_size_opt
  - arch/x86/kernel/mpparse.c:parse_alloc_mptable_opt
  - arch/x86/kernel/check.c:set_corruption_check_size
  - arch/x86/mm/hugetlbpage.c:setup_hugepagesz
  - kernel/printk/printk.c:log_buf_len_setup
  - kernel/trace/trace.c:set_buf_size
  - kernel/crash_dump.c:setup_elfcorehdr
  - kernel/crash_dump.c:setup_elfcorehdr
  - mm/page_alloc.c:cmdline_parse_core
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/hugetlb.c:hugetlb_default_setup
  - mm/page_counter.c:page_counter_memparse
  - security/integrity/ima/ima_crypto.c:param_set_bufsize
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/xen-balloon.c:store_target
```
**Symbols:**

```
ffffffff819cdcd0-ffffffff819cdd5c: memparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long long unsigned int memparse(const char *ptr, char **retptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff81a07160)
Location: lib/cmdline.c:128
Inline: False
Direct callers:
  - init/do_mounts_initrd.c:early_initrd
  - init/do_mounts_initrd.c:early_initrd
  - arch/x86/kernel/setup.c:parse_reservelow
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memopt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_gran_size_opt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_chunk_size_opt
  - arch/x86/kernel/mpparse.c:parse_alloc_mptable_opt
  - arch/x86/kernel/check.c:set_corruption_check_size
  - arch/x86/mm/hugetlbpage.c:setup_hugepagesz
  - kernel/printk/printk.c:log_buf_len_setup
  - kernel/trace/trace.c:set_buf_size
  - kernel/crash_dump.c:setup_elfcorehdr
  - kernel/crash_dump.c:setup_elfcorehdr
  - mm/page_alloc.c:cmdline_parse_core
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/hugetlb.c:hugetlb_default_setup
  - mm/page_counter.c:page_counter_memparse
  - security/integrity/ima/ima_crypto.c:param_set_bufsize
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/xen-balloon.c:store_target
```
**Symbols:**

```
ffffffff81a07160-ffffffff81a0721e: memparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long long unsigned int memparse(const char *ptr, char **retptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff81a76ac0)
Location: lib/cmdline.c:125
Inline: False
Direct callers:
  - init/do_mounts_initrd.c:early_initrd
  - init/do_mounts_initrd.c:early_initrd
  - arch/x86/xen/time.c:parse_xen_timer_slop
  - arch/x86/kernel/setup.c:parse_reservelow
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memopt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_gran_size_opt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_chunk_size_opt
  - arch/x86/kernel/mpparse.c:parse_alloc_mptable_opt
  - arch/x86/kernel/check.c:set_corruption_check_size
  - arch/x86/mm/hugetlbpage.c:setup_hugepagesz
  - kernel/printk/printk.c:log_buf_len_setup
  - kernel/trace/trace.c:set_buf_size
  - kernel/crash_dump.c:setup_elfcorehdr
  - kernel/crash_dump.c:setup_elfcorehdr
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/page_alloc.c:cmdline_parse_core
  - mm/hugetlb.c:hugetlb_default_setup
  - mm/page_counter.c:page_counter_memparse
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - security/integrity/ima/ima_crypto.c:param_set_bufsize
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/xen-balloon.c:store_target
```
**Symbols:**

```
ffffffff81a76ac0-ffffffff81a76b82: memparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long long unsigned int memparse(const char *ptr, char **retptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff81aaded0)
Location: lib/cmdline.c:125
Inline: False
Direct callers:
  - init/do_mounts_initrd.c:early_initrd
  - init/do_mounts_initrd.c:early_initrd
  - arch/x86/xen/time.c:parse_xen_timer_slop
  - arch/x86/kernel/setup.c:parse_reservelow
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memopt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_gran_size_opt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_chunk_size_opt
  - arch/x86/kernel/mpparse.c:parse_alloc_mptable_opt
  - arch/x86/kernel/apic/x2apic_uv_x.c:parse_mem_block_size
  - arch/x86/kernel/check.c:set_corruption_check_size
  - arch/x86/mm/hugetlbpage.c:setup_hugepagesz
  - kernel/printk/printk.c:log_buf_len_setup
  - kernel/trace/trace.c:set_buf_size
  - kernel/crash_dump.c:setup_elfcorehdr
  - kernel/crash_dump.c:setup_elfcorehdr
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - mm/page_alloc.c:cmdline_parse_core
  - mm/hugetlb.c:hugetlb_default_setup
  - mm/page_counter.c:page_counter_memparse
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - security/integrity/ima/ima_crypto.c:param_set_bufsize
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/xen-balloon.c:store_target
```
**Symbols:**

```
ffffffff81aaded0-ffffffff81aadf92: memparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long long unsigned int memparse(const char *ptr, char **retptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff815e7ab0)
Location: lib/cmdline.c:125
Inline: False
Direct callers:
  - init/do_mounts_initrd.c:early_initrdmem
  - init/do_mounts_initrd.c:early_initrdmem
  - arch/x86/xen/time.c:parse_xen_timer_slop
  - arch/x86/kernel/setup.c:parse_reservelow
  - arch/x86/kernel/e820.c:parse_memopt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_gran_size_opt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_chunk_size_opt
  - arch/x86/kernel/mpparse.c:parse_alloc_mptable_opt
  - arch/x86/kernel/apic/x2apic_uv_x.c:parse_mem_block_size
  - arch/x86/kernel/check.c:set_corruption_check_size
  - kernel/printk/printk.c:log_buf_len_setup
  - kernel/dma/pool.c:early_coherent_pool
  - kernel/crash_core.c:parse_crashkernel_suffix
  - kernel/crash_core.c:parse_crashkernel_mem
  - kernel/crash_core.c:parse_crashkernel_mem
  - kernel/crash_core.c:parse_crashkernel_mem
  - kernel/crash_core.c:parse_crashkernel_mem
  - kernel/trace/trace.c:set_buf_size
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/crash_dump.c:setup_elfcorehdr
  - kernel/crash_dump.c:setup_elfcorehdr
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - mm/page_alloc.c:cmdline_parse_core
  - mm/hugetlb.c:default_hugepagesz_setup
  - mm/hugetlb.c:hugepagesz_setup
  - mm/page_counter.c:page_counter_memparse
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - security/integrity/ima/ima_crypto.c:param_set_bufsize
  - block/cmdline-parser.c:parse_subpart
  - block/cmdline-parser.c:parse_subpart
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/xen-balloon.c:store_target
```
**Symbols:**

```
ffffffff815e7ab0-ffffffff815e7b6b: memparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long long unsigned int memparse(const char *ptr, char **retptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff8160cc40)
Location: lib/cmdline.c:137
Inline: False
Direct callers:
  - init/do_mounts_initrd.c:early_initrdmem
  - init/do_mounts_initrd.c:early_initrdmem
  - arch/x86/xen/time.c:parse_xen_timer_slop
  - arch/x86/kernel/setup.c:parse_reservelow
  - arch/x86/kernel/e820.c:parse_memopt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_gran_size_opt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_chunk_size_opt
  - arch/x86/kernel/mpparse.c:parse_alloc_mptable_opt
  - arch/x86/kernel/apic/x2apic_uv_x.c:parse_mem_block_size
  - arch/x86/kernel/check.c:set_corruption_check_size
  - kernel/printk/printk.c:log_buf_len_setup
  - kernel/dma/pool.c:early_coherent_pool
  - kernel/crash_core.c:parse_crashkernel_suffix
  - kernel/crash_core.c:parse_crashkernel_mem
  - kernel/crash_core.c:parse_crashkernel_mem
  - kernel/crash_core.c:parse_crashkernel_mem
  - kernel/crash_core.c:parse_crashkernel_mem
  - kernel/trace/trace.c:set_buf_size
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/crash_dump.c:setup_elfcorehdr
  - kernel/crash_dump.c:setup_elfcorehdr
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - mm/page_alloc.c:cmdline_parse_core
  - mm/hugetlb.c:default_hugepagesz_setup
  - mm/hugetlb.c:hugepagesz_setup
  - mm/page_counter.c:page_counter_memparse
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - security/integrity/ima/ima_crypto.c:param_set_bufsize
  - block/cmdline-parser.c:parse_subpart
  - block/cmdline-parser.c:parse_subpart
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/xen-balloon.c:store_target
```
**Symbols:**

```
ffffffff8160cc40-ffffffff8160ccfb: memparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long long unsigned int memparse(const char *ptr, char **retptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff815f0300)
Location: lib/cmdline.c:150
Inline: False
Direct callers:
  - init/do_mounts_initrd.c:early_initrdmem
  - init/do_mounts_initrd.c:early_initrdmem
  - arch/x86/xen/time.c:parse_xen_timer_slop
  - arch/x86/kernel/setup.c:parse_reservelow
  - arch/x86/kernel/e820.c:parse_memopt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_gran_size_opt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_chunk_size_opt
  - arch/x86/kernel/mpparse.c:parse_alloc_mptable_opt
  - arch/x86/kernel/apic/x2apic_uv_x.c:parse_mem_block_size
  - arch/x86/kernel/check.c:set_corruption_check_size
  - kernel/printk/printk.c:log_buf_len_setup
  - kernel/dma/pool.c:early_coherent_pool
  - kernel/crash_core.c:parse_crashkernel_suffix
  - kernel/crash_core.c:parse_crashkernel_mem
  - kernel/crash_core.c:parse_crashkernel_mem
  - kernel/crash_core.c:parse_crashkernel_mem
  - kernel/crash_core.c:parse_crashkernel_mem
  - kernel/trace/trace.c:set_buf_size
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/crash_dump.c:setup_elfcorehdr
  - kernel/crash_dump.c:setup_elfcorehdr
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - mm/page_alloc.c:cmdline_parse_core
  - mm/hugetlb.c:default_hugepagesz_setup
  - mm/hugetlb.c:hugepagesz_setup
  - mm/page_counter.c:page_counter_memparse
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - security/integrity/ima/ima_crypto.c:param_set_bufsize
  - block/cmdline-parser.c:parse_subpart
  - block/cmdline-parser.c:parse_subpart
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/xen-balloon.c:store_target
```
**Symbols:**

```
ffffffff815f0300-ffffffff815f03c1: memparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long long unsigned int memparse(const char *ptr, char **retptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff8165d3e0)
Location: lib/cmdline.c:150
Inline: False
Direct callers:
  - init/do_mounts_initrd.c:early_initrdmem
  - init/do_mounts_initrd.c:early_initrdmem
  - arch/x86/xen/time.c:parse_xen_timer_slop
  - arch/x86/kernel/e820.c:parse_memopt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_gran_size_opt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_chunk_size_opt
  - arch/x86/kernel/mpparse.c:parse_alloc_mptable_opt
  - arch/x86/kernel/apic/x2apic_uv_x.c:parse_mem_block_size
  - arch/x86/kernel/check.c:set_corruption_check_size
  - kernel/printk/printk.c:log_buf_len_setup
  - kernel/dma/pool.c:early_coherent_pool
  - kernel/crash_core.c:parse_crashkernel_suffix
  - kernel/crash_core.c:parse_crashkernel_mem
  - kernel/crash_core.c:parse_crashkernel_mem
  - kernel/crash_core.c:parse_crashkernel_mem
  - kernel/crash_core.c:parse_crashkernel_mem
  - kernel/trace/trace.c:set_buf_size
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/crash_dump.c:setup_elfcorehdr
  - kernel/crash_dump.c:setup_elfcorehdr
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - mm/page_alloc.c:cmdline_parse_core
  - mm/hugetlb.c:default_hugepagesz_setup
  - mm/hugetlb.c:hugepagesz_setup
  - mm/page_counter.c:page_counter_memparse
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - security/integrity/ima/ima_crypto.c:param_set_bufsize
  - block/partitions/cmdline.c:parse_subpart
  - block/partitions/cmdline.c:parse_subpart
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/xen-balloon.c:target_store
```
**Symbols:**

```
ffffffff8165d3e0-ffffffff8165d4a1: memparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long long unsigned int memparse(const char *ptr, char **retptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff817768b0)
Location: lib/cmdline.c:150
Inline: False
Direct callers:
  - init/do_mounts_initrd.c:early_initrdmem
  - init/do_mounts_initrd.c:early_initrdmem
  - arch/x86/xen/time.c:parse_xen_timer_slop
  - arch/x86/kernel/e820.c:parse_memopt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_gran_size_opt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_chunk_size_opt
  - arch/x86/kernel/mpparse.c:parse_alloc_mptable_opt
  - arch/x86/kernel/apic/x2apic_uv_x.c:parse_mem_block_size
  - arch/x86/kernel/check.c:set_corruption_check_size
  - kernel/printk/printk.c:log_buf_len_setup
  - kernel/dma/pool.c:early_coherent_pool
  - kernel/crash_core.c:parse_crashkernel_suffix
  - kernel/crash_core.c:parse_crashkernel_mem
  - kernel/crash_core.c:parse_crashkernel_mem
  - kernel/crash_core.c:parse_crashkernel_mem
  - kernel/crash_core.c:parse_crashkernel_mem
  - kernel/trace/trace.c:set_buf_size
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/crash_dump.c:setup_elfcorehdr
  - kernel/crash_dump.c:setup_elfcorehdr
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - mm/page_alloc.c:cmdline_parse_core
  - mm/hugetlb.c:default_hugepagesz_setup
  - mm/hugetlb.c:hugepagesz_setup
  - mm/hugetlb.c:demote_size_store
  - mm/page_counter.c:page_counter_memparse
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - security/integrity/ima/ima_crypto.c:param_set_bufsize
  - block/partitions/cmdline.c:parse_subpart
  - block/partitions/cmdline.c:parse_subpart
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/xen-balloon.c:target_store
```
**Symbols:**

```
ffffffff817768b0-ffffffff81776989: memparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long long unsigned int memparse(const char *ptr, char **retptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff8201f330)
Location: lib/cmdline.c:150
Inline: False
Direct callers:
  - init/do_mounts_initrd.c:early_initrd
  - init/do_mounts_initrd.c:early_initrd
  - arch/x86/xen/time.c:parse_xen_timer_slop
  - arch/x86/kernel/e820.c:parse_memopt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_gran_size_opt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_chunk_size_opt
  - arch/x86/kernel/mpparse.c:parse_alloc_mptable_opt
  - arch/x86/kernel/apic/x2apic_uv_x.c:parse_mem_block_size
  - arch/x86/kernel/check.c:set_corruption_check_size
  - kernel/printk/printk.c:log_buf_len_setup
  - kernel/dma/pool.c:early_coherent_pool
  - kernel/crash_core.c:parse_crashkernel_suffix
  - kernel/crash_core.c:parse_crashkernel_mem
  - kernel/crash_core.c:parse_crashkernel_mem
  - kernel/crash_core.c:parse_crashkernel_mem
  - kernel/crash_core.c:parse_crashkernel_mem
  - kernel/trace/trace.c:set_buf_size
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/crash_dump.c:setup_elfcorehdr
  - kernel/crash_dump.c:setup_elfcorehdr
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - mm/page_alloc.c:cmdline_parse_movablecore
  - mm/hugetlb.c:default_hugepagesz_setup
  - mm/hugetlb.c:hugepagesz_setup
  - mm/hugetlb.c:demote_size_store
  - mm/page_counter.c:page_counter_memparse
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - security/integrity/ima/ima_crypto.c:param_set_bufsize
  - block/partitions/cmdline.c:parse_subpart
  - block/partitions/cmdline.c:parse_subpart
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/xen-balloon.c:target_store
```
**Symbols:**

```
ffffffff8201f330-ffffffff8201f409: memparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long long unsigned int memparse(const char *ptr, char **retptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff8209f340)
Location: lib/cmdline.c:150
Inline: False
Direct callers:
  - init/do_mounts_initrd.c:early_initrd
  - init/do_mounts_initrd.c:early_initrd
  - arch/x86/xen/time.c:parse_xen_timer_slop
  - arch/x86/kernel/e820.c:parse_memopt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_gran_size_opt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_chunk_size_opt
  - arch/x86/kernel/mpparse.c:parse_alloc_mptable_opt
  - arch/x86/kernel/apic/x2apic_uv_x.c:parse_mem_block_size
  - arch/x86/kernel/check.c:set_corruption_check_size
  - kernel/printk/printk.c:log_buf_len_setup
  - kernel/dma/pool.c:early_coherent_pool
  - kernel/crash_core.c:parse_crashkernel_suffix
  - kernel/crash_core.c:parse_crashkernel_mem
  - kernel/crash_core.c:parse_crashkernel_mem
  - kernel/crash_core.c:parse_crashkernel_mem
  - kernel/crash_core.c:parse_crashkernel_mem
  - kernel/trace/trace.c:set_buf_size
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/crash_dump.c:setup_elfcorehdr
  - kernel/crash_dump.c:setup_elfcorehdr
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - mm/mm_init.c:cmdline_parse_movablecore
  - mm/hugetlb.c:default_hugepagesz_setup
  - mm/hugetlb.c:hugepagesz_setup
  - mm/hugetlb.c:demote_size_store
  - mm/page_counter.c:page_counter_memparse
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - security/integrity/ima/ima_crypto.c:param_set_bufsize
  - block/partitions/cmdline.c:parse_subpart
  - block/partitions/cmdline.c:parse_subpart
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/xen-balloon.c:target_store
```
**Symbols:**

```
ffffffff8209f340-ffffffff8209f413: memparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long long unsigned int memparse(const char *ptr, char **retptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff82177340)
Location: lib/cmdline.c:150
Inline: False
Direct callers:
  - init/do_mounts_initrd.c:early_initrd
  - init/do_mounts_initrd.c:early_initrd
  - arch/x86/xen/time.c:parse_xen_timer_slop
  - arch/x86/kernel/e820.c:parse_memopt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_gran_size_opt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_chunk_size_opt
  - arch/x86/kernel/mpparse.c:parse_alloc_mptable_opt
  - arch/x86/kernel/apic/x2apic_uv_x.c:parse_mem_block_size
  - arch/x86/kernel/check.c:set_corruption_check_size
  - kernel/printk/printk.c:log_buf_len_setup
  - kernel/dma/pool.c:early_coherent_pool
  - kernel/crash_core.c:__parse_crashkernel
  - kernel/crash_core.c:__parse_crashkernel
  - kernel/crash_core.c:parse_crashkernel_suffix
  - kernel/crash_core.c:parse_crashkernel_mem
  - kernel/crash_core.c:parse_crashkernel_mem
  - kernel/crash_core.c:parse_crashkernel_mem
  - kernel/crash_core.c:parse_crashkernel_mem
  - kernel/trace/trace.c:set_buf_size
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/crash_dump.c:setup_elfcorehdr
  - kernel/crash_dump.c:setup_elfcorehdr
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - mm/mm_init.c:cmdline_parse_movablecore
  - mm/hugetlb.c:default_hugepagesz_setup
  - mm/hugetlb.c:hugepagesz_setup
  - mm/hugetlb.c:demote_size_store
  - mm/page_counter.c:page_counter_memparse
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - security/integrity/ima/ima_crypto.c:param_set_bufsize
  - block/partitions/cmdline.c:parse_subpart
  - block/partitions/cmdline.c:parse_subpart
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/xen-balloon.c:target_store
```
**Symbols:**

```
ffffffff82177340-ffffffff82177413: memparse (STB_GLOBAL)
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
long long unsigned int memparse(const char *ptr, char **retptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffff800010d84168)
Location: lib/cmdline.c:125
Inline: False
Direct callers:
  - init/do_mounts_initrd.c:early_initrd
  - init/do_mounts_initrd.c:early_initrd
  - arch/arm64/mm/init.c:early_mem
  - arch/arm64/mm/hugetlbpage.c:setup_hugepagesz
  - kernel/printk/printk.c:log_buf_len_setup
  - kernel/dma/contiguous.c:early_cma
  - kernel/dma/contiguous.c:early_cma
  - kernel/dma/contiguous.c:early_cma
  - kernel/dma/remap.c:early_coherent_pool
  - kernel/trace/trace.c:set_buf_size
  - kernel/crash_dump.c:setup_elfcorehdr
  - kernel/crash_dump.c:setup_elfcorehdr
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - mm/page_alloc.c:cmdline_parse_core
  - mm/hugetlb.c:hugetlb_default_setup
  - mm/page_counter.c:page_counter_memparse
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - security/integrity/ima/ima_crypto.c:param_set_bufsize
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/xen-balloon.c:store_target
```
**Symbols:**

```
ffff800010d84168-ffff800010d84270: memparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long long unsigned int memparse(const char *ptr, char **retptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (c0e7f604)
Location: lib/cmdline.c:125
Inline: False
Direct callers:
  - init/do_mounts_initrd.c:early_initrd
  - init/do_mounts_initrd.c:early_initrd
  - arch/arm/kernel/setup.c:early_mem
  - arch/arm/kernel/setup.c:early_mem
  - arch/arm/mm/dma-mapping.c:early_coherent_pool
  - arch/arm/mm/mmu.c:early_vmalloc
  - kernel/printk/printk.c:log_buf_len_setup
  - kernel/dma/contiguous.c:early_cma
  - kernel/dma/contiguous.c:early_cma
  - kernel/dma/contiguous.c:early_cma
  - kernel/trace/trace.c:set_buf_size
  - kernel/crash_dump.c:setup_elfcorehdr
  - kernel/crash_dump.c:setup_elfcorehdr
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - mm/page_counter.c:page_counter_memparse
  - security/integrity/ima/ima_crypto.c:param_set_bufsize
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/mtd/parsers/cmdlinepart.c:newpart
  - drivers/mtd/parsers/cmdlinepart.c:newpart
```
**Symbols:**

```
c0e7f604-c0e7f790: memparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long long unsigned int memparse(const char *ptr, char **retptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (c000000000ec3210)
Location: lib/cmdline.c:125
Inline: False
Direct callers:
  - init/do_mounts_initrd.c:early_initrd
  - init/do_mounts_initrd.c:early_initrd
  - arch/powerpc/kernel/prom.c:early_parse_mem
  - arch/powerpc/kernel/fadump.c:early_fadump_reserve_mem
  - arch/powerpc/mm/numa.c:fake_numa_create_new_node
  - arch/powerpc/mm/hugetlbpage.c:hugepage_setup_sz
  - kernel/printk/printk.c:log_buf_len_setup
  - kernel/trace/trace.c:set_buf_size
  - kernel/crash_dump.c:setup_elfcorehdr
  - kernel/crash_dump.c:setup_elfcorehdr
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - mm/page_alloc.c:cmdline_parse_core
  - mm/hugetlb.c:hugetlb_default_setup
  - mm/page_counter.c:page_counter_memparse
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - security/integrity/ima/ima_crypto.c:param_set_bufsize
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
**Symbols:**

```
c000000000ec3210-c000000000ec33a0: memparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long long unsigned int memparse(const char *ptr, char **retptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffe0008ae7e0)
Location: lib/cmdline.c:125
Inline: False
Direct callers:
  - init/do_mounts_initrd.c:early_initrd
  - init/do_mounts_initrd.c:early_initrd
  - arch/riscv/mm/hugetlbpage.c:setup_hugepagesz
  - kernel/printk/printk.c:log_buf_len_setup
  - kernel/dma/contiguous.c:early_cma
  - kernel/dma/contiguous.c:early_cma
  - kernel/dma/contiguous.c:early_cma
  - kernel/trace/trace.c:set_buf_size
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - mm/page_alloc.c:cmdline_parse_core
  - mm/hugetlb.c:hugetlb_default_setup
  - mm/page_counter.c:page_counter_memparse
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - security/integrity/ima/ima_crypto.c:param_set_bufsize
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
**Symbols:**

```
ffffffe0008ae7e0-ffffffe0008ae848: memparse (STB_GLOBAL)
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
long long unsigned int memparse(const char *ptr, char **retptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff81a4cd20)
Location: lib/cmdline.c:125
Inline: False
Direct callers:
  - init/do_mounts_initrd.c:early_initrd
  - init/do_mounts_initrd.c:early_initrd
  - arch/x86/xen/time.c:parse_xen_timer_slop
  - arch/x86/kernel/setup.c:parse_reservelow
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memopt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_gran_size_opt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_chunk_size_opt
  - arch/x86/kernel/mpparse.c:parse_alloc_mptable_opt
  - arch/x86/kernel/check.c:set_corruption_check_size
  - arch/x86/mm/hugetlbpage.c:setup_hugepagesz
  - kernel/printk/printk.c:log_buf_len_setup
  - kernel/dma/contiguous.c:early_cma
  - kernel/dma/contiguous.c:early_cma
  - kernel/dma/contiguous.c:early_cma
  - kernel/trace/trace.c:set_buf_size
  - kernel/crash_dump.c:setup_elfcorehdr
  - kernel/crash_dump.c:setup_elfcorehdr
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - mm/page_alloc.c:cmdline_parse_core
  - mm/hugetlb.c:hugetlb_default_setup
  - mm/page_counter.c:page_counter_memparse
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - security/integrity/ima/ima_crypto.c:param_set_bufsize
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
**Symbols:**

```
ffffffff81a4cd20-ffffffff81a4cde2: memparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long long unsigned int memparse(const char *ptr, char **retptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff81a09e50)
Location: lib/cmdline.c:125
Inline: False
Direct callers:
  - init/do_mounts_initrd.c:early_initrd
  - init/do_mounts_initrd.c:early_initrd
  - arch/x86/kernel/setup.c:parse_reservelow
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memopt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_gran_size_opt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_chunk_size_opt
  - arch/x86/kernel/mpparse.c:parse_alloc_mptable_opt
  - arch/x86/kernel/check.c:set_corruption_check_size
  - arch/x86/mm/hugetlbpage.c:setup_hugepagesz
  - kernel/printk/printk.c:log_buf_len_setup
  - kernel/trace/trace.c:set_buf_size
  - kernel/crash_dump.c:setup_elfcorehdr
  - kernel/crash_dump.c:setup_elfcorehdr
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - mm/page_alloc.c:cmdline_parse_core
  - mm/hugetlb.c:hugetlb_default_setup
  - mm/page_counter.c:page_counter_memparse
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - security/integrity/ima/ima_crypto.c:param_set_bufsize
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
**Symbols:**

```
ffffffff81a09e50-ffffffff81a09f12: memparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long long unsigned int memparse(const char *ptr, char **retptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff81ab9110)
Location: lib/cmdline.c:125
Inline: False
Direct callers:
  - init/do_mounts_initrd.c:early_initrd
  - init/do_mounts_initrd.c:early_initrd
  - arch/x86/xen/time.c:parse_xen_timer_slop
  - arch/x86/kernel/setup.c:parse_reservelow
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memopt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_gran_size_opt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_chunk_size_opt
  - arch/x86/kernel/mpparse.c:parse_alloc_mptable_opt
  - arch/x86/kernel/check.c:set_corruption_check_size
  - arch/x86/mm/hugetlbpage.c:setup_hugepagesz
  - kernel/printk/printk.c:log_buf_len_setup
  - kernel/trace/trace.c:set_buf_size
  - kernel/crash_dump.c:setup_elfcorehdr
  - kernel/crash_dump.c:setup_elfcorehdr
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - mm/page_alloc.c:cmdline_parse_core
  - mm/hugetlb.c:hugetlb_default_setup
  - mm/page_counter.c:page_counter_memparse
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - security/integrity/ima/ima_crypto.c:param_set_bufsize
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/xen-balloon.c:store_target
```
**Symbols:**

```
ffffffff81ab9110-ffffffff81ab91d2: memparse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long long unsigned int memparse(const char *ptr, char **retptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff81ac5560)
Location: lib/cmdline.c:125
Inline: False
Direct callers:
  - init/do_mounts_initrd.c:early_initrd
  - init/do_mounts_initrd.c:early_initrd
  - arch/x86/xen/time.c:parse_xen_timer_slop
  - arch/x86/kernel/setup.c:parse_reservelow
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memopt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_gran_size_opt
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_chunk_size_opt
  - arch/x86/kernel/mpparse.c:parse_alloc_mptable_opt
  - arch/x86/kernel/apic/x2apic_uv_x.c:parse_mem_block_size
  - arch/x86/kernel/check.c:set_corruption_check_size
  - arch/x86/mm/hugetlbpage.c:setup_hugepagesz
  - kernel/printk/printk.c:log_buf_len_setup
  - kernel/trace/trace.c:set_buf_size
  - kernel/crash_dump.c:setup_elfcorehdr
  - kernel/crash_dump.c:setup_elfcorehdr
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - mm/page_alloc.c:cmdline_parse_core
  - mm/hugetlb.c:hugetlb_default_setup
  - mm/page_counter.c:page_counter_memparse
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - security/integrity/ima/ima_crypto.c:param_set_bufsize
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:pci_setup
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/xen-balloon.c:store_target
```
**Symbols:**

```
ffffffff81ac5560-ffffffff81ac5622: memparse (STB_GLOBAL)
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
