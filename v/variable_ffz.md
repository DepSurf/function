# Function: <code>variable_ffz</code>

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
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In arch/x86/mm/pkeys.c (ffffffff810d4710)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In kernel/sysctl.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In kernel/signal.c (ffffffff811008b8)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
```
```
In kernel/irq/manage.c (ffffffff81198470)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/events/uprobes.c (ffffffff81352219)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
Inline callers:
  - kernel/events/uprobes.c:pre_ssout
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In mm/mprotect.c (ffffffff813cd838)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
Inline callers:
  - mm/mprotect.c:__do_sys_pkey_alloc
```
```
In fs/file.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In fs/binfmt_elf.c (ffffffff8150f5be)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81512296)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In fs/squashfs/super.c (ffffffff815f0fa7)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In security/landlock/fs.c (ffffffff816f1806)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
Inline callers:
  - security/landlock/fs.c:is_access_to_paths_allowed
  - security/landlock/fs.c:is_access_to_paths_allowed
```
```
In block/blk-flush.c (ffffffff81738b39)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In io_uring/filetable.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In lib/bitmap.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In lib/sbitmap.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81923228)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_next_free_bar
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff81923f49)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_add_vepf
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In drivers/acpi/numa/srat.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff81a89a0f)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/char/agp/generic.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In drivers/iommu/amd/iommu.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81aba0a5)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:first_pte_l7
```
```
In drivers/iommu/intel/iommu.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In drivers/scsi/sr.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In drivers/net/wwan/wwan_core.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In drivers/md/md-bitmap.c (ffffffff81d0698e)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
```
```
In net/core/sock.c (ffffffff81d997bf)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
Inline callers:
  - net/core/sock.c:proto_register
```
```
In net/core/dev.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In net/netlink/genetlink.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81ef10f6)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/fib_frontend.c (ffffffff81efdbaa)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
```
```
In net/ncsi/ncsi-manage.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In net/mptcp/pm_netlink.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In net/mptcp/pm_userspace.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In lib/idr.c (ffffffff820214d8)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
```
```
In lib/vsprintf.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
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
In arch/x86/kernel/idt.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In arch/x86/mm/pkeys.c (ffffffff810d7c38)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In kernel/sysctl.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In kernel/signal.c (ffffffff8110c9ba)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
```
```
In kernel/sched/core.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In kernel/irq/manage.c (ffffffff811a9e64)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/trace/trace.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In kernel/bpf/cpumask.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff81383429)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
Inline callers:
  - kernel/events/uprobes.c:pre_ssout
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In mm/mprotect.c (ffffffff8140219b)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
Inline callers:
  - mm/mprotect.c:__do_sys_pkey_alloc
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In fs/file.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In fs/binfmt_elf.c (ffffffff81546eaa)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81549c91)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In fs/squashfs/super.c (ffffffff81629008)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In security/landlock/fs.c (ffffffff8172bc23)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
Inline callers:
  - security/landlock/fs.c:is_access_to_paths_allowed
  - security/landlock/fs.c:is_access_to_paths_allowed
```
```
In block/blk-flush.c (ffffffff81775170)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In io_uring/filetable.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In lib/bitmap.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In lib/sbitmap.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81966f08)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_first_free_bar
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff81967b59)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_add_vepf
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In drivers/acpi/numa/srat.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff81ad51cf)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/char/agp/generic.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In drivers/iommu/amd/iommu.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81b06645)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:first_pte_l7
```
```
In drivers/iommu/intel/iommu.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In drivers/scsi/sr.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In drivers/net/wwan/wwan_core.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In drivers/md/md-bitmap.c (ffffffff81d6fc5a)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
```
```
In drivers/firmware/efi/unaccepted_memory.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In net/core/sock.c (ffffffff81e07adf)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
Inline callers:
  - net/core/sock.c:proto_register
```
```
In net/core/dev.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In net/netlink/genetlink.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81f50c92)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5d627)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
```
```
In net/ncsi/ncsi-manage.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In net/mptcp/pm_netlink.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In net/mptcp/pm_userspace.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
```
```
In lib/idr.c (ffffffff820a1508)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
```
```
In lib/vsprintf.c (0)
Location: arch/x86/include/asm/bitops.h:269
Inline: True
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
In arch/x86/kernel/idt.c (0)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
```
```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
```
```
In arch/x86/mm/pkeys.c (ffffffff810e04b8)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In kernel/sysctl.c (0)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
```
```
In kernel/signal.c (ffffffff8111639a)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
```
```
In kernel/sched/core.c (0)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
```
```
In kernel/irq/manage.c (ffffffff811b9c69)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/trace/trace.c (0)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
```
```
In kernel/bpf/cpumask.c (0)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff813ac843)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
Inline callers:
  - kernel/events/uprobes.c:pre_ssout
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
```
```
In mm/mprotect.c (ffffffff8142e7cb)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
Inline callers:
  - mm/mprotect.c:__do_sys_pkey_alloc
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
```
```
In fs/file.c (0)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
```
```
In fs/binfmt_elf.c (ffffffff8157c2ca)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff8157ef11)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
```
```
In fs/squashfs/super.c (ffffffff81662257)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In security/landlock/fs.c (ffffffff8176ccf0)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
Inline callers:
  - security/landlock/fs.c:scope_to_request
```
```
In block/blk-flush.c (ffffffff817b7463)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In io_uring/filetable.c (0)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
```
```
In lib/bitmap.c (0)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
```
```
In lib/sbitmap.c (0)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff819b0638)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_first_free_bar
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff819b12b9)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_add_vepf
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
```
```
In drivers/acpi/numa/srat.c (0)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff81b28548)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/char/agp/generic.c (0)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
```
```
In drivers/iommu/amd/iommu.c (0)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81b5a465)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:first_pte_l7
```
```
In drivers/iommu/intel/iommu.c (0)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
```
```
In drivers/scsi/sr.c (0)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
```
```
In drivers/md/md-bitmap.c (ffffffff81e26d5a)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
```
```
In drivers/firmware/efi/unaccepted_memory.c (0)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
```
```
In net/core/sock.c (ffffffff81ec451f)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
Inline callers:
  - net/core/sock.c:proto_register
```
```
In net/core/dev.c (0)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
```
```
In net/netlink/genetlink.c (0)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff82016f12)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/fib_frontend.c (ffffffff82023be6)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
```
```
In net/ncsi/ncsi-manage.c (0)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
```
```
In net/mptcp/pm_netlink.c (0)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
```
```
In net/mptcp/pm_userspace.c (0)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
```
```
In lib/idr.c (ffffffff821794f8)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
```
```
In lib/vsprintf.c (0)
Location: arch/x86/include/asm/bitops.h:268
Inline: True
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
