# Function: <code>kref_init</code>

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
In kernel/sched/auto_group.c (ffffffff810c4b32)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - kernel/sched/auto_group.c:sched_autogroup_create_attach
  - kernel/sched/auto_group.c:autogroup_init
```
```
In kernel/irq/manage.c (ffffffff810db4ce)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/time/posix-clock.c (ffffffff810f9de8)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - kernel/time/posix-clock.c:posix_clock_register
```
```
In kernel/cgroup.c (ffffffff81113834)
Location: include/linux/kref.h:31
Inline: True
```
```
In kernel/utsname.c (ffffffff8111dd30)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff8111fa1b)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/relay.c (ffffffff8113c420)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
  - kernel/relay.c:relay_open
```
```
In mm/zswap.c (ffffffff811d8036)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff811dc49f)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - mm/hugetlb.c:resv_map_alloc
```
```
In fs/eventfd.c (ffffffff812591ff)
Location: include/linux/kref.h:31
Inline: True
```
```
In fs/fuse/file.c (ffffffff81318e12)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
```
```
In security/apparmor/lib.c (ffffffff8137865a)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff813790d3)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/label.c (ffffffff81389963)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_alloc_proxy
  - security/apparmor/label.c:aa_label_init
```
```
In block/bsg.c (ffffffff813d55a8)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - block/bsg.c:bsg_register_queue
```
```
In lib/kobject.c (ffffffff813eb621)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - lib/kobject.c:kobject_init
  - lib/kobject.c:kset_register
```
```
In lib/cpu_rmap.c (ffffffff81415c97)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In drivers/pinctrl/core.c (ffffffff8141e623)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_get
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8145328e)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/acpi/ec.c (ffffffff81483a68)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/dma/dmaengine.c (ffffffff814bdba5)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
```
```
In drivers/tty/tty_io.c (ffffffff814e0940)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (ffffffff814eb029)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (ffffffff8151860a)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:add_port
```
```
In drivers/char/hw_random/core.c (ffffffff8151ab0a)
Location: include/linux/kref.h:31
Inline: True
```
```
In drivers/base/firmware_class.c (ffffffff8155f548)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
```
```
In drivers/nvdimm/dimm.c (ffffffff8159956a)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/nvdimm/dimm.c:nvdimm_probe
```
```
In drivers/dma-buf/fence.c (ffffffff815a3be2)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/dma-buf/fence.c:fence_init
```
```
In drivers/scsi/scsi_scan.c (ffffffff815b31c8)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sr.c (ffffffff815c093c)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff815c45b1)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/usb/core/hub.c (ffffffff8160bdf0)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff8160db8f)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_create_shared_hcd
```
```
In drivers/usb/core/urb.c (ffffffff8160fea3)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_alloc_urb
```
```
In drivers/usb/core/config.c (ffffffff81615c12)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff81617502)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_register_dev
```
```
In drivers/clk/clk.c (ffffffff816e88f8)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
```
```
In lib/klist.c (ffffffff818175af)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
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
In kernel/sched/auto_group.c (ffffffff810c87f2)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - kernel/sched/auto_group.c:sched_autogroup_create_attach
  - kernel/sched/auto_group.c:autogroup_init
```
```
In kernel/irq/manage.c (ffffffff810e0b6b)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/time/posix-clock.c (ffffffff81101088)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - kernel/time/posix-clock.c:posix_clock_register
```
```
In kernel/utsname.c (ffffffff81125c00)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff81127a19)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/relay.c (ffffffff81146129)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - kernel/relay.c:relay_open
  - kernel/relay.c:__relay_reset
```
```
In mm/zswap.c (ffffffff811f615f)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff811fa6eb)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - mm/hugetlb.c:resv_map_alloc
```
```
In fs/eventfd.c (ffffffff81281bdf)
Location: include/linux/kref.h:31
Inline: True
```
```
In fs/fuse/file.c (ffffffff8134d85e)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
```
```
In security/apparmor/apparmorfs.c (ffffffff813ab5e0)
Location: include/linux/kref.h:31
Inline: True
```
```
In security/apparmor/lib.c (ffffffff813b13ba)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff813b1e64)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/label.c (ffffffff813c4eed)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_init
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In block/bsg.c (ffffffff8141b268)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - block/bsg.c:bsg_register_queue
```
```
In lib/kobject.c (ffffffff814327c0)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init
```
```
In lib/cpu_rmap.c (ffffffff8145dac7)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In drivers/pinctrl/core.c (ffffffff81466d3b)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_get
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8149fb34)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/acpi/ec.c (ffffffff814d1fa6)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/dma/dmaengine.c (ffffffff8150d855)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
```
```
In drivers/tty/tty_io.c (ffffffff81534b8e)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (ffffffff8153beb9)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (ffffffff8156b32f)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:add_port
```
```
In drivers/char/hw_random/core.c (ffffffff8156d83a)
Location: include/linux/kref.h:31
Inline: True
```
```
In drivers/base/firmware_class.c (ffffffff815b40a9)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
```
```
In drivers/nvdimm/core.c (ffffffff815ec076)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm.c (ffffffff815ef04a)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/nvdimm/dimm.c:nvdimm_probe
```
```
In drivers/dma-buf/fence.c (ffffffff815facde)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/dma-buf/fence.c:fence_init
```
```
In drivers/dma-buf/sync_file.c (ffffffff815fd296)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_alloc
```
```
In drivers/scsi/scsi_scan.c (ffffffff8160b628)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sr.c (ffffffff816190e6)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff8161cdc1)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/usb/core/hub.c (ffffffff8166b97d)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff8166d75e)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_create_shared_hcd
```
```
In drivers/usb/core/urb.c (ffffffff8166fac2)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_alloc_urb
```
```
In drivers/usb/core/config.c (ffffffff81675b8b)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff81677650)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_register_dev
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff816ecb1d)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
```
In drivers/clk/clk.c (ffffffff8174ce04)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
```
```
In lib/klist.c (ffffffff8189105f)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
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
In kernel/sched/auto_group.c (ffffffff810ce7e2)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - kernel/sched/auto_group.c:sched_autogroup_create_attach
  - kernel/sched/auto_group.c:autogroup_init
```
```
In kernel/irq/manage.c (ffffffff810e757b)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/time/posix-clock.c (ffffffff81108d48)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - kernel/time/posix-clock.c:posix_clock_register
```
```
In kernel/utsname.c (ffffffff8112f640)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff811316d0)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/relay.c (ffffffff8114fe71)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - kernel/relay.c:relay_open
  - kernel/relay.c:__relay_reset
```
```
In mm/zswap.c (ffffffff81206b3b)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff8120b11b)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - mm/hugetlb.c:resv_map_alloc
```
```
In fs/eventfd.c (ffffffff8129570f)
Location: include/linux/kref.h:31
Inline: True
```
```
In fs/fuse/file.c (ffffffff8136316a)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
```
```
In security/apparmor/apparmorfs.c (ffffffff813c23b0)
Location: include/linux/kref.h:31
Inline: True
```
```
In security/apparmor/lib.c (ffffffff813c857a)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff813c9024)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/label.c (ffffffff813dc53d)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_init
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In block/bsg.c (ffffffff814367a8)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - block/bsg.c:bsg_register_queue
```
```
In block/bsg-lib.c (ffffffff8143810d)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_request_fn
```
```
In lib/kobject.c (ffffffff8144ea30)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init
```
```
In lib/cpu_rmap.c (ffffffff8147c587)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In drivers/pinctrl/core.c (ffffffff8148602b)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_get
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff814c16b4)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/acpi/ec.c (ffffffff814f4348)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/clk/clk.c (ffffffff81535671)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
```
```
In drivers/dma/dmaengine.c (ffffffff81539985)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
```
```
In drivers/tty/tty_io.c (ffffffff815612be)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (ffffffff81568519)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (ffffffff81597a9f)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:add_port
```
```
In drivers/char/hw_random/core.c (ffffffff81599f9e)
Location: include/linux/kref.h:31
Inline: True
```
```
In drivers/base/firmware_class.c (ffffffff815e3379)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
```
```
In drivers/nvdimm/core.c (ffffffff81618c66)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm.c (ffffffff8161c1f2)
Location: include/linux/kref.h:31
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81628fae)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_init
```
```
In drivers/dma-buf/sync_file.c (ffffffff8162b4bf)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_alloc
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8162c6dc)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi_scan.c (ffffffff8163aec8)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sr.c (ffffffff81649d76)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff8164d9d1)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/usb/core/hub.c (ffffffff816996bc)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff8169b45e)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_create_shared_hcd
```
```
In drivers/usb/core/urb.c (ffffffff8169d7a2)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_alloc_urb
```
```
In drivers/usb/core/config.c (ffffffff816a381f)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff816a5330)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_register_dev
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8171dbbd)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
```
In lib/klist.c (ffffffff818c57ef)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
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
In kernel/sched/autogroup.c (ffffffff810cdb92)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/irq/manage.c (ffffffff810e6167)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/time/posix-clock.c (ffffffff8110af68)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - kernel/time/posix-clock.c:posix_clock_register
```
```
In kernel/utsname.c (ffffffff81130bbe)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff81132cd7)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/relay.c (ffffffff8115247a)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - kernel/relay.c:relay_open
  - kernel/relay.c:__relay_reset
```
```
In mm/backing-dev.c (ffffffff811e17b7)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:default_bdi_init
```
```
In mm/zswap.c (ffffffff81212686)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff8121647b)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - mm/hugetlb.c:resv_map_alloc
```
```
In fs/eventfd.c (ffffffff812a29df)
Location: include/linux/kref.h:31
Inline: True
```
```
In fs/configfs/item.c (ffffffff812e1be5)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/fuse/file.c (ffffffff81377b07)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
```
```
In security/apparmor/apparmorfs.c (ffffffff813db2a9)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffff813ddd1a)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff813de6b4)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff813e6bd8)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/label.c (ffffffff813ed183)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In block/bsg.c (ffffffff81444027)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - block/bsg.c:bsg_register_queue
```
```
In block/bsg-lib.c (ffffffff81445921)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_request_fn
```
```
In lib/cpu_rmap.c (ffffffff814858b7)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In drivers/pinctrl/core.c (ffffffff8148fbb5)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff814cbce2)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/acpi/ec.c (ffffffff8150211a)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/clk/clk.c (ffffffff815489c8)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
```
```
In drivers/dma/dmaengine.c (ffffffff8154d145)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81561d1d)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (0)
Location: include/linux/kref.h:31
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81574eae)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (ffffffff8157bc51)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (ffffffff815aba62)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:add_port
```
```
In drivers/char/hw_random/core.c (ffffffff815adf78)
Location: include/linux/kref.h:31
Inline: True
```
```
In drivers/base/firmware_class.c (ffffffff815f7d33)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
```
```
In drivers/nvdimm/core.c (ffffffff8162cdb6)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm.c (ffffffff8163022b)
Location: include/linux/kref.h:31
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8163ec16)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_init
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81641c6c)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi_scan.c (ffffffff8164f5a5)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sr.c (ffffffff8165e856)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff816622d4)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/usb/core/hub.c (ffffffff816ae99d)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff816b07d6)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff816b2b63)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_init_urb
```
```
In drivers/usb/core/config.c (ffffffff816b88f2)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff816ba699)
Location: include/linux/kref.h:31
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81735ded)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
```
In lib/klist.c (ffffffff818edbd3)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
```
```
In lib/kobject.c (ffffffff818eec50)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init
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
In kernel/sched/autogroup.c (ffffffff810d5412)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/irq/manage.c (ffffffff810ee3fb)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/time/posix-clock.c (ffffffff811160c8)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - kernel/time/posix-clock.c:posix_clock_register
```
```
In kernel/utsname.c (ffffffff8113db0f)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff8113faa0)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/relay.c (ffffffff8115ecea)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - kernel/relay.c:relay_open
  - kernel/relay.c:__relay_reset
```
```
In mm/backing-dev.c (ffffffff811f77d7)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:default_bdi_init
```
```
In mm/zswap.c (ffffffff8122cd76)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff8123112b)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - mm/hugetlb.c:resv_map_alloc
```
```
In fs/eventfd.c (ffffffff812c5c8f)
Location: include/linux/kref.h:31
Inline: True
```
```
In fs/configfs/item.c (ffffffff81306515)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/fuse/file.c (ffffffff8139c8a6)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
```
```
In security/apparmor/apparmorfs.c (ffffffff81401d21)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffff814046ba)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff81405044)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff8140dd58)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/label.c (ffffffff81414b8f)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In block/bsg.c (ffffffff81470dd3)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - block/bsg.c:bsg_register_queue
```
```
In block/bsg-lib.c (ffffffff81472438)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_request_fn
```
```
In lib/cpu_rmap.c (ffffffff814c1ac6)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In drivers/pinctrl/core.c (ffffffff814cbd65)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8150c2b2)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/acpi/ec.c (ffffffff8154447a)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/clk/clk.c (ffffffff815abf8d)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
```
```
In drivers/dma/dmaengine.c (ffffffff815b06c5)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff815c5a8d)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (0)
Location: include/linux/kref.h:31
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff815d969e)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (ffffffff815e05e1)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (ffffffff81612402)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:add_port
```
```
In drivers/char/hw_random/core.c (ffffffff81614949)
Location: include/linux/kref.h:31
Inline: True
```
```
In drivers/base/firmware_class.c (ffffffff8165fd04)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
```
```
In drivers/nvdimm/core.c (ffffffff81695546)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm.c (ffffffff81698a4b)
Location: include/linux/kref.h:31
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff816a7a1d)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_init
```
```
In drivers/dma-buf/sw_sync.c (ffffffff816aa691)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi_scan.c (ffffffff816b8845)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sr.c (ffffffff816c7c66)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff816cb549)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/usb/core/hub.c (ffffffff81719fad)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff8171bde6)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff8171e233)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_init_urb
```
```
In drivers/usb/core/config.c (ffffffff81724203)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff81726051)
Location: include/linux/kref.h:31
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff817a7b67)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
```
In drivers/opp/core.c (ffffffff817d5795)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
  - drivers/opp/core.c:dev_pm_opp_get_opp_table
```
```
In lib/klist.c (ffffffff81973a87)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
```
```
In lib/kobject.c (ffffffff81974f10)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init
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
In kernel/sched/autogroup.c (ffffffff810dd3fa)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/irq/manage.c (ffffffff810f67fd)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/time/posix-clock.c (ffffffff81122965)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - kernel/time/posix-clock.c:posix_clock_register
```
```
In kernel/utsname.c (ffffffff8114c4a3)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff8114e2d8)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/relay.c (ffffffff8116c62c)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In mm/backing-dev.c (ffffffff81218c05)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:default_bdi_init
```
```
In mm/zswap.c (ffffffff8124f94e)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff81254027)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - mm/hugetlb.c:resv_map_alloc
```
```
In fs/eventfd.c (ffffffff812eeeb1)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/configfs/item.c (ffffffff813345a8)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/fuse/file.c (ffffffff813cbcbb)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
```
```
In security/apparmor/apparmorfs.c (ffffffff81432c81)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffff8143576a)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff81436131)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff8143f9c2)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/label.c (ffffffff81446f8f)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In block/bsg-lib.c (ffffffff814a6984)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_request_fn
```
```
In lib/cpu_rmap.c (ffffffff814f2a03)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In drivers/pinctrl/core.c (ffffffff814fccd0)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81541101)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/acpi/ec.c (ffffffff8157a315)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/clk/clk.c (ffffffff815e3f0e)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
```
```
In drivers/dma/dmaengine.c (ffffffff815e8adf)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff815fe17d)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff8160eb48)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_from_lookup
```
```
In drivers/tty/tty_io.c (ffffffff8161262b)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (ffffffff816198a2)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (ffffffff8164be3b)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:add_port
```
```
In drivers/char/hw_random/core.c (ffffffff8164e561)
Location: include/linux/kref.h:31
Inline: True
```
```
In drivers/base/core.c (ffffffff8167f04f)
Location: include/linux/kref.h:31
Inline: True
```
```
In drivers/base/firmware_loader/main.c (ffffffff8169a9aa)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/nvdimm/core.c (ffffffff816d1619)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm.c (ffffffff816d4cbf)
Location: include/linux/kref.h:31
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff816e3af9)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_init
```
```
In drivers/dma-buf/sw_sync.c (ffffffff816e6baa)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi_scan.c (ffffffff816f3990)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sr.c (ffffffff8170463a)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff81707f40)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffff8170c614)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/sfp-bus.c (ffffffff8173afb8)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/usb/core/hub.c (ffffffff81758d53)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff8175ab20)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff8175d6cf)
Location: include/linux/kref.h:31
Inline: True
```
```
In drivers/usb/core/config.c (ffffffff8176300b)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff81764def)
Location: include/linux/kref.h:31
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff817ef5b2)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
```
In drivers/opp/core.c (ffffffff8181e48f)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
  - drivers/opp/core.c:dev_pm_opp_get_opp_table
```
```
In lib/klist.c (ffffffff819cfe5d)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
```
```
In lib/kobject.c (ffffffff819d1448)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init
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
In kernel/sched/autogroup.c (ffffffff810e7b4a)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/irq/manage.c (ffffffff81101f6d)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/time/posix-clock.c (ffffffff8112e045)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - kernel/time/posix-clock.c:posix_clock_register
```
```
In kernel/utsname.c (ffffffff811590c3)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff8115afb8)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/relay.c (ffffffff8117a05c)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In mm/backing-dev.c (ffffffff8122b980)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:default_bdi_init
```
```
In mm/zswap.c (ffffffff81263c6e)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff81268407)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - mm/hugetlb.c:resv_map_alloc
```
```
In fs/eventfd.c (ffffffff81303841)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/configfs/item.c (ffffffff8134b8c8)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/fuse/file.c (ffffffff813e4d75)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
```
```
In security/apparmor/apparmorfs.c (ffffffff8144f931)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffff8145235a)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff81452d51)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff8145c8b2)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/label.c (ffffffff81463ebc)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In block/bsg-lib.c (ffffffff814c09b9)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In lib/cpu_rmap.c (ffffffff81506d33)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In drivers/pinctrl/core.c (ffffffff81511730)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81558461)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/acpi/ec.c (ffffffff81591b65)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/clk/clk.c (ffffffff815fe2fc)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
```
```
In drivers/dma/dmaengine.c (ffffffff8160292f)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8161924d)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff8162b338)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_from_lookup
```
```
In drivers/tty/tty_io.c (ffffffff8162f6cb)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (ffffffff81636b12)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (ffffffff81669fab)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:add_port
```
```
In drivers/char/hw_random/core.c (ffffffff8166c7f1)
Location: include/linux/kref.h:31
Inline: True
```
```
In drivers/base/core.c (ffffffff8169f48f)
Location: include/linux/kref.h:31
Inline: True
```
```
In drivers/base/firmware_loader/main.c (ffffffff816bb1a0)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/nvdimm/core.c (ffffffff816f2ca9)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm.c (ffffffff816f6a07)
Location: include/linux/kref.h:31
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81706d93)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_init
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81709dba)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi_scan.c (ffffffff8171752c)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sr.c (ffffffff81726aaa)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff81729050)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffff8172ea94)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/sfp-bus.c (ffffffff8175e598)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/usb/core/hub.c (ffffffff8177d2c3)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff8177f050)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff81781d0f)
Location: include/linux/kref.h:31
Inline: True
```
```
In drivers/usb/core/config.c (ffffffff8178764b)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff8178946f)
Location: include/linux/kref.h:31
Inline: True
```
```
In drivers/media/cec/cec-notifier.c (ffffffff81808d47)
Location: include/linux/kref.h:31
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8181b47f)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
```
In drivers/opp/core.c (ffffffff8184a28d)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
```
```
In drivers/nvmem/core.c (ffffffff818870e2)
Location: include/linux/kref.h:31
Inline: True
```
```
In lib/klist.c (ffffffff81a0949d)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
```
```
In lib/kobject.c (ffffffff81a0aa08)
Location: include/linux/kref.h:31
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init
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
In kernel/sched/autogroup.c (ffffffff810eeabf)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/sched/psi.c (ffffffff810f720f)
Location: include/linux/kref.h:29
Inline: True
```
```
In kernel/irq/manage.c (ffffffff8110b219)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/time/posix-clock.c (ffffffff81138a55)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/time/posix-clock.c:posix_clock_register
```
```
In kernel/utsname.c (ffffffff811657f8)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff81167668)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/relay.c (ffffffff81186e9d)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In mm/backing-dev.c (ffffffff8123b5f5)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:default_bdi_init
```
```
In mm/zswap.c (ffffffff8127ebf6)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff812836e8)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/hugetlb.c:resv_map_alloc
```
```
In mm/hmm.c (ffffffff812c420a)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/hmm.c:hmm_mirror_register
```
```
In fs/eventfd.c (ffffffff81324de5)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/configfs/item.c (ffffffff81374248)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/fuse/file.c (ffffffff81410678)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
```
```
In security/apparmor/apparmorfs.c (ffffffff8147d611)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffff8147fd1a)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff81480707)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff81489e3d)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/label.c (ffffffff81491172)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In block/bsg-lib.c (ffffffff814ef19d)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In lib/cpu_rmap.c (ffffffff81534f53)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In drivers/pinctrl/core.c (ffffffff8153fd33)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81588471)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/acpi/ec.c (ffffffff815c2a34)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/clk/clk.c (ffffffff8162f852)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffffffff81635148)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8164cf44)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff8165f2b3)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff8166358b)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (ffffffff8166ad62)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (ffffffff8169f79a)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:add_port
```
```
In drivers/char/hw_random/core.c (ffffffff816a242b)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff816d1bb6)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/base/core.c (ffffffff816d7b36)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/base/firmware_loader/main.c (ffffffff816f5a22)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/nvdimm/core.c (ffffffff8172c27f)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm.c (ffffffff81730307)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/dax/bus.c (ffffffff817404d0)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81741efb)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_init
```
```
In drivers/dma-buf/sw_sync.c (ffffffff817455ca)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi_scan.c (ffffffff8175221d)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sr.c (ffffffff817621dd)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff8176439e)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffff8176a284)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/sfp-bus.c (ffffffff8179bc18)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/usb/core/hub.c (ffffffff817bb83c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff817bc1bf)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff817bf9cf)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_init_urb
```
```
In drivers/usb/core/config.c (ffffffff817c60a4)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff817c791f)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/media/cec/cec-notifier.c (ffffffff8184a5d2)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8185d6c2)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
```
In drivers/opp/core.c (ffffffff8188d11b)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
```
```
In drivers/nvmem/core.c (ffffffff818d12c6)
Location: include/linux/kref.h:29
Inline: True
```
```
In lib/klist.c (ffffffff81a78e1e)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
```
```
In lib/kobject.c (ffffffff81a7a3b6)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init
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
In kernel/sched/autogroup.c (ffffffff810fa6bf)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/sched/psi.c (ffffffff81102f9f)
Location: include/linux/kref.h:29
Inline: True
```
```
In kernel/irq/manage.c (ffffffff81117c39)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/utsname.c (ffffffff811716b8)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff81173528)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/relay.c (ffffffff81192dbd)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In mm/backing-dev.c (ffffffff81249b15)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:default_bdi_init
```
```
In mm/zswap.c (ffffffff8128e636)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff81293288)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/hugetlb.c:resv_map_alloc
```
```
In fs/eventfd.c (ffffffff81337b75)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/configfs/item.c (ffffffff8138c4c8)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/fuse/file.c (ffffffff8142a288)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
```
```
In security/apparmor/apparmorfs.c (ffffffff814972e1)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffff81499a1a)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff8149a407)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff814a3cfd)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/label.c (ffffffff814ab022)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In block/bsg-lib.c (ffffffff8150864d)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In lib/cpu_rmap.c (ffffffff81555d63)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In drivers/pinctrl/core.c (ffffffff81560bd3)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff815a9e71)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/acpi/ec.c (ffffffff815e3de4)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/clk/clk.c (ffffffff81651c4f)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffffffff81656e58)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8166f684)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff816819ed)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81685bfb)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (ffffffff8168d432)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (ffffffff816c253a)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:add_port
```
```
In drivers/char/hw_random/core.c (ffffffff816c51cc)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff816f5aa6)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/base/core.c (ffffffff816fbc1b)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (ffffffff81719e22)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/nvdimm/core.c (ffffffff817504cf)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm.c (ffffffff81754397)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/dax/bus.c (ffffffff817646d0)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff817667db)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8176974a)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi_scan.c (ffffffff8177649d)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sr.c (ffffffff817861cd)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff8178838e)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffff8178e2e4)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/sfp-bus.c (ffffffff817bf6c8)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/vfio/vfio.c (ffffffff817d0670)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_fops_open
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817d775c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
```
In drivers/usb/core/hub.c (ffffffff817ec04a)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff817ec9ef)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff817f034f)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_init_urb
```
```
In drivers/usb/core/config.c (ffffffff817f6b58)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff817f843f)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/media/cec/cec-notifier.c (ffffffff8187bdc2)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/opp/core.c (ffffffff818bf35b)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff818f482a)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/nvmem/core.c (ffffffff819036c6)
Location: include/linux/kref.h:29
Inline: True
```
```
In lib/klist.c (ffffffff81ab01c2)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
```
```
In lib/kobject.c (ffffffff81ab1716)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/autogroup.c (ffffffff81104a9f)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/sched/psi.c (ffffffff8110cbb8)
Location: include/linux/kref.h:29
Inline: True
```
```
In kernel/irq/manage.c (ffffffff81122f39)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/time/namespace.c (ffffffff81159c0a)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/time/namespace.c:clone_time_ns
```
```
In kernel/utsname.c (ffffffff811832e5)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/pid_namespace.c (ffffffff81185007)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/relay.c (ffffffff811a7bfd)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/watch_queue.c (ffffffff8124d52c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_init
  - kernel/watch_queue.c:init_watch
```
```
In mm/backing-dev.c (ffffffff81277d73)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc
```
```
In mm/zswap.c (ffffffff812c12ea)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff812c6458)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/hugetlb.c:resv_map_alloc
```
```
In fs/eventfd.c (ffffffff813716e7)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/configfs/item.c (ffffffff813d7818)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/fuse/file.c (ffffffff8147a2e6)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
```
```
In security/apparmor/apparmorfs.c (ffffffff814eef71)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffff814f210a)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff814f2eb3)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff814feb64)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/label.c (ffffffff81509a24)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In block/bsg-lib.c (ffffffff8156973d)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In lib/cpu_rmap.c (ffffffff815df473)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In lib/klist.c (ffffffff815ea082)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
```
```
In lib/kobject.c (ffffffff815eb7e3)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/kobject.c:kset_create_and_add
  - lib/kobject.c:kobject_create_and_add
```
```
In drivers/pinctrl/core.c (ffffffff8160354a)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81652c91)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/acpi/ec.c (ffffffff8168f3c4)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/clk/clk.c (ffffffff81700cf6)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffffffff817071d8)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8171f4a4)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff81732929)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffff8173765b)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (ffffffff8173f4a2)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (ffffffff81776119)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/char/hw_random/core.c (ffffffff81779235)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_init
```
```
In drivers/lightnvm/core.c (ffffffff817ae5a6)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/base/core.c (ffffffff817b541e)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (ffffffff817d4f29)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/nvdimm/core.c (ffffffff8180ec51)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:alloc_nvdimm_map
```
```
In drivers/nvdimm/dimm.c (ffffffff81812f66)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/dax/bus.c (ffffffff81824240)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8182703b)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_init
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8182b99e)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_create
```
```
In drivers/scsi/scsi_scan.c (ffffffff818397a3)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sr.c (ffffffff8184acea)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff8184ed39)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_alloc
```
```
In drivers/ata/libata-core.c (ffffffff818524a4)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/sfp-bus.c (ffffffff818889d4)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/vfio/vfio.c (ffffffff8189b6b0)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_fops_open
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_create_group
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a3cf0)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_attach
```
```
In drivers/usb/core/hub.c (ffffffff818bb661)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff818bc4e4)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff818c0650)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_alloc_urb
```
```
In drivers/usb/core/config.c (ffffffff818c6e46)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff818c84d8)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/file.c:init_usb_class
```
```
In drivers/opp/core.c (ffffffff81990b4c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819ca95a)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/nvmem/core.c (ffffffff819db043)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff810656bb)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
```
```
In kernel/sched/autogroup.c (ffffffff8110311f)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/sched/psi.c (ffffffff81109d78)
Location: include/linux/kref.h:29
Inline: True
```
```
In kernel/irq/manage.c (ffffffff8111ef29)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/relay.c (ffffffff811a5fed)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/watch_queue.c (ffffffff8125799c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_init
  - kernel/watch_queue.c:init_watch
```
```
In mm/backing-dev.c (ffffffff81282387)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc
```
```
In mm/zswap.c (ffffffff812cce0a)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff812d2048)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/hugetlb.c:resv_map_alloc
```
```
In fs/eventfd.c (ffffffff8137f4a7)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/configfs/item.c (ffffffff813e94b8)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/fuse/file.c (ffffffff81494fe0)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
```
```
In security/apparmor/apparmorfs.c (ffffffff8150c3f1)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffff8150f30a)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff81510083)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff8151bdc4)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/label.c (ffffffff81526894)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In block/bsg-lib.c (ffffffff81583e8d)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In lib/cpu_rmap.c (ffffffff815fcc13)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In lib/klist.c (ffffffff8160e9c2)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
```
```
In lib/kobject.c (ffffffff81610103)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/kobject.c:kset_create_and_add
  - lib/kobject.c:kobject_create_and_add
```
```
In drivers/pinctrl/core.c (ffffffff8162845a)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81675651)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/acpi/ec.c (ffffffff816ad094)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/clk/clk.c (ffffffff8171e216)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffffffff81724617)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8173c404)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff8174eae9)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffff81753a1b)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (ffffffff8175b3d2)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (ffffffff81790e49)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/char/hw_random/core.c (ffffffff81793a41)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_init
```
```
In drivers/lightnvm/core.c (ffffffff817c3136)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/base/core.c (ffffffff817c9b0d)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (ffffffff817e9ff5)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/nvdimm/core.c (ffffffff8181d7c1)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:alloc_nvdimm_map
```
```
In drivers/nvdimm/dimm.c (ffffffff81822196)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/dax/bus.c (ffffffff818340ed)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81837ae1)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_init
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8183c803)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_create
```
```
In drivers/scsi/scsi_scan.c (ffffffff8184a023)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sr.c (ffffffff8185b0ec)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff8185f6b9)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_alloc
```
```
In drivers/ata/libata-core.c (ffffffff81862804)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81896c64)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/vfio/vfio.c (ffffffff818aa110)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_fops_open
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_create_group
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b2cc0)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_attach
```
```
In drivers/usb/core/hub.c (ffffffff81c1c18a)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff818c9244)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff818cc56c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_alloc_urb
```
```
In drivers/usb/core/config.c (ffffffff818d2a86)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff818d3688)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/file.c:init_usb_class
```
```
In drivers/opp/core.c (ffffffff819948ec)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c9e5a)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/nvmem/core.c (ffffffff819da684)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff81065d8b)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
```
```
In kernel/sched/autogroup.c (ffffffff8110545f)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/sched/psi.c (ffffffff8110ba77)
Location: include/linux/kref.h:29
Inline: True
```
```
In kernel/irq/manage.c (ffffffff8111f1a9)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/relay.c (ffffffff811a699d)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/watch_queue.c (ffffffff8125bdfc)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_init
  - kernel/watch_queue.c:init_watch
```
```
In mm/backing-dev.c (ffffffff81287497)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc
```
```
In mm/zswap.c (ffffffff812d39aa)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff812d89b8)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/hugetlb.c:resv_map_alloc
```
```
In fs/eventfd.c (ffffffff81386127)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/configfs/item.c (ffffffff813f0028)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/fuse/file.c (ffffffff8149a040)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
```
```
In security/apparmor/apparmorfs.c (ffffffff81512d71)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffff81515cfa)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff81516917)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff81522494)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/label.c (ffffffff8152c224)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In block/bsg-lib.c (ffffffff8158ac8d)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In lib/cpu_rmap.c (ffffffff815df982)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In lib/klist.c (ffffffff815f2152)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
```
```
In lib/kobject.c (ffffffff815f3843)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/kobject.c:kset_create_and_add
  - lib/kobject.c:kobject_create_and_add
```
```
In drivers/pinctrl/core.c (ffffffff8160bf3a)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81657b81)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/acpi/ec.c (ffffffff8168f6b4)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/clk/clk.c (ffffffff816ff269)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffffffff817058d7)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8171ff64)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff8173276d)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffff817378bb)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (ffffffff8173f272)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (ffffffff81773f19)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/char/hw_random/core.c (ffffffff81776bfa)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff817a64d6)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/base/core.c (ffffffff817ad306)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (ffffffff817ce705)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/nvdimm/core.c (ffffffff81800a31)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:alloc_nvdimm_map
```
```
In drivers/nvdimm/dimm.c (ffffffff818054a6)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/dax/bus.c (ffffffff818172d9)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8181a71f)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_init
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8181fb4a)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi_scan.c (ffffffff8182d7a3)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sr.c (ffffffff8183e0dc)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff818426b9)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_alloc
```
```
In drivers/ata/libata-core.c (ffffffff81845604)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81879115)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/vfio/vfio.c (ffffffff8188d660)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_fops_open
  - drivers/vfio/vfio.c:vfio_create_group
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff81897377)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
```
In drivers/usb/core/hub.c (ffffffff81c0e070)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff818ac7a4)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff818afa9b)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_alloc_urb
```
```
In drivers/usb/core/config.c (ffffffff818b6016)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff818b6bf7)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/opp/core.c (ffffffff8197981b)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
  - drivers/opp/core.c:_add_opp_table_indexed
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819aee6a)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/nvmem/core.c (ffffffff819c00bb)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff8106feab)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
```
```
In kernel/sched/autogroup.c (ffffffff811230cf)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/irq/manage.c (ffffffff8113f639)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/relay.c (ffffffff811d018d)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/watch_queue.c (ffffffff81297cac)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_init
  - kernel/watch_queue.c:init_watch
```
```
In mm/backing-dev.c (ffffffff812c6e17)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc
```
```
In mm/zswap.c (ffffffff8131962c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff8131ecc8)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/hugetlb.c:resv_map_alloc
```
```
In fs/eventfd.c (ffffffff813d33f7)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/configfs/item.c (ffffffff81441f18)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/fuse/file.c (ffffffff814f1a69)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
```
```
In security/apparmor/apparmorfs.c (ffffffff81570971)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffff81573cfa)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff81574917)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff815806e4)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/label.c (ffffffff8158a612)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In block/bsg-lib.c (ffffffff815efd5d)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In lib/cpu_rmap.c (ffffffff8164b5c2)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In lib/klist.c (ffffffff8165f4e4)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/klist.c:klist_add_before
  - lib/klist.c:klist_add_behind
  - lib/klist.c:klist_add_tail
  - lib/klist.c:klist_add_head
```
```
In lib/kobject.c (ffffffff81660a13)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/kobject.c:kset_create_and_add
  - lib/kobject.c:kobject_create_and_add
```
```
In drivers/pinctrl/core.c (ffffffff8167ac4a)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff816c9bb0)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/acpi/ec.c (ffffffff81705114)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/clk/clk.c (ffffffff81779b30)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffffffff81780e27)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8179f024)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff817b305f)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffff817b834b)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (ffffffff817bfa02)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (ffffffff817fa2f9)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/char/hw_random/core.c (ffffffff817fc5ca)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:set_current_rng
```
```
In drivers/base/core.c (ffffffff818365f2)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (ffffffff81858fb5)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/nvdimm/core.c (ffffffff8188ae31)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:alloc_nvdimm_map
```
```
In drivers/nvdimm/dimm.c (ffffffff8188fb36)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/dax/bus.c (ffffffff818a1929)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff818a49fb)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff818aa20a)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi_scan.c (ffffffff818b91f3)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sr.c (ffffffff818cab9b)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff818cf7c9)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_alloc
```
```
In drivers/ata/libata-core.c (ffffffff818d2094)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81909f65)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/vfio/vfio.c (ffffffff81920bc0)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_fops_open
  - drivers/vfio/vfio.c:vfio_create_group
```
```
In drivers/usb/core/hub.c (ffffffff81d1514a)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff819417f4)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff81944beb)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_alloc_urb
```
```
In drivers/usb/core/config.c (ffffffff8194b66d)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff8194c59a)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/opp/core.c (ffffffff81a2282b)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
  - drivers/opp/core.c:_add_opp_table_indexed
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81a5d46a)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/nvmem/core.c (ffffffff81a6f80b)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff8107d7bd)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
```
```
In kernel/sched/build_utility.c (ffffffff81144d4e)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:autogroup_init
```
```
In kernel/irq/manage.c (ffffffff811630cd)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/relay.c (ffffffff81205367)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/relay.c:relay_open
  - kernel/relay.c:__relay_reset
```
```
In kernel/watch_queue.c (ffffffff812edf8c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_init
  - kernel/watch_queue.c:init_watch
```
```
In mm/backing-dev.c (ffffffff81324206)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_init
```
```
In mm/madvise.c (ffffffff81377f50)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/madvise.c:anon_vma_name_alloc
```
```
In mm/zswap.c (ffffffff81384918)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff8138b4c7)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/hugetlb.c:resv_map_alloc
```
```
In fs/eventfd.c (ffffffff8145c9c5)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/configfs/item.c (ffffffff814bdb6c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/fuse/file.c (ffffffff815814d5)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
```
```
In security/apparmor/apparmorfs.c (ffffffff8160d2ad)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffff816115f9)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff816123f1)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff8161f8cb)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/label.c (ffffffff8162ba7c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In block/bsg-lib.c (ffffffff816a0d0a)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In lib/cpu_rmap.c (ffffffff81762022)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In lib/klist.c (ffffffff81778c17)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/klist.c:klist_add_before
  - lib/klist.c:klist_add_behind
  - lib/klist.c:klist_add_tail
  - lib/klist.c:klist_add_head
```
```
In lib/kobject.c (ffffffff8177a54b)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/kobject.c:kset_create_and_add
  - lib/kobject.c:kobject_create_and_add
```
```
In drivers/pinctrl/core.c (ffffffff81796308)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff817efe94)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/acpi/ec.c (ffffffff818331d4)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/clk/clk.c (ffffffff818afe6c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffffffff818b75c8)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff818d8c14)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff818eeaa6)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffff818f42e5)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (ffffffff818fc022)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (ffffffff819376cf)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/char/hw_random/core.c (ffffffff8193b225)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:set_current_rng
```
```
In drivers/base/core.c (ffffffff819785f2)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (ffffffff8199f7a1)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv
```
```
In drivers/nvdimm/core.c (ffffffff819d456d)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:alloc_nvdimm_map
```
```
In drivers/nvdimm/dimm.c (ffffffff819d9574)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/dax/bus.c (ffffffff819eb062)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-fence.c (ffffffff819ee60d)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff819f4a3a)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi_scan.c (ffffffff81a04e63)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sg.c (ffffffff81a1dfde)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_alloc
```
```
In drivers/ata/libata-core.c (ffffffff81a22614)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81a5d662)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/vfio/vfio.c (ffffffff81a772e0)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_fops_open
```
```
In drivers/usb/core/hub.c (ffffffff81edfcec)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff81a9a1f0)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff81a9c65f)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_init_urb
```
```
In drivers/usb/core/config.c (ffffffff81ee1a4d)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff81aa5093)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_register_dev
```
```
In drivers/opp/core.c (ffffffff81b8b8d9)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
  - drivers/opp/core.c:_add_opp_table_indexed
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81bcd59a)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/nvmem/core.c (ffffffff81be0bf3)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
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
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff8108ed1d)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
```
```
In kernel/sched/build_utility.c (ffffffff8117113e)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:autogroup_init
```
```
In kernel/irq/manage.c (ffffffff81196cdd)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/relay.c (ffffffff8124d438)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/relay.c:relay_open
  - kernel/relay.c:__relay_reset
```
```
In kernel/watch_queue.c (ffffffff813583bc)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_init
  - kernel/watch_queue.c:init_watch
```
```
In mm/backing-dev.c (ffffffff81398b06)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_init
```
```
In mm/madvise.c (ffffffff813f5850)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/madvise.c:anon_vma_name_alloc
```
```
In mm/zswap.c (ffffffff81402548)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff81408ba7)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/hugetlb.c:resv_map_alloc
```
```
In mm/memory-tiers.c (ffffffff83ec697e)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/memory-tiers.c:memory_tier_init
```
```
In fs/eventfd.c (ffffffff814ec0a5)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/configfs/item.c (ffffffff8155589c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/fuse/file.c (ffffffff81627335)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
```
```
In security/apparmor/apparmorfs.c (ffffffff816bf21d)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffff816c4299)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff816c50a1)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff816d2cdb)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/label.c (ffffffff816e035b)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In security/apparmor/notify.c (ffffffff816ea702)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_new_listener
  - security/apparmor/notify.c:aa_new_listener
```
```
In block/bsg-lib.c (ffffffff8175f8aa)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In lib/cpu_rmap.c (ffffffff818911e3)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In drivers/pinctrl/core.c (ffffffff818ab9be)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81918044)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/acpi/ec.c (ffffffff81966cb4)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/clk/clk.c (ffffffff819fc1bf)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffffffff81a044f8)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81a2b674)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff81a46706)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffff81a4cb54)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (ffffffff81a55592)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (ffffffff81a97bdf)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/char/hw_random/core.c (ffffffff81a9b8fc)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/base/core.c (ffffffff81ae4eac)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (ffffffff81b11241)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv
```
```
In drivers/nvdimm/core.c (ffffffff81b4edbd)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:alloc_nvdimm_map
```
```
In drivers/nvdimm/dimm.c (ffffffff81b54654)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/dax/bus.c (ffffffff81b67bc2)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81b6baad)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81b71e9a)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/hosts.c (ffffffff81b76e66)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_scan.c (ffffffff81b83b13)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sg.c (ffffffff81b9f30e)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_alloc
```
```
In drivers/ata/libata-core.c (ffffffff81ba3d54)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81be8212)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/pse-pd/pse_core.c (0)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81c1cb36)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff81c1e770)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff81c215cf)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_init_urb
```
```
In drivers/usb/core/config.c (ffffffff81c2a6d9)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff81c2ba33)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_register_dev
```
```
In drivers/opp/core.c (ffffffff81d2aff1)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
  - drivers/opp/core.c:_add_opp_table_indexed
```
```
In drivers/nvmem/core.c (ffffffff81d8c4dd)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
```
```
In lib/klist.c (ffffffff82021a07)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/klist.c:klist_add_before
  - lib/klist.c:klist_add_behind
  - lib/klist.c:klist_add_tail
  - lib/klist.c:klist_add_head
```
```
In lib/kobject.c (ffffffff820230ae)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
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
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff81091c0d)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
```
```
In kernel/sched/build_utility.c (ffffffff8118193e)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:autogroup_init
```
```
In kernel/irq/manage.c (ffffffff811a878d)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/relay.c (ffffffff812647b8)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/relay.c:relay_open
  - kernel/relay.c:__relay_reset
```
```
In kernel/watch_queue.c (ffffffff81389c4c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_init
  - kernel/watch_queue.c:init_watch
```
```
In mm/backing-dev.c (ffffffff813cba66)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_init
```
```
In mm/madvise.c (ffffffff814285a0)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/madvise.c:anon_vma_name_alloc
```
```
In mm/zswap.c (ffffffff81435401)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff8143c217)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/hugetlb.c:resv_map_alloc
```
```
In mm/memory-tiers.c (ffffffff836eb96e)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/memory-tiers.c:memory_tier_init
```
```
In fs/eventfd.c (ffffffff81523265)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/configfs/item.c (ffffffff8158d63c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/fuse/file.c (ffffffff8165f6f5)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
```
```
In security/apparmor/apparmorfs.c (ffffffff816f7d2d)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/audit.c (ffffffff816fa678)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_dup_audit_data
```
```
In security/apparmor/lib.c (ffffffff816fce69)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff816fdae7)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy.c (ffffffff8170614e)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_alloc_pdb
```
```
In security/apparmor/policy_unpack.c (ffffffff8170bcdb)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/label.c (ffffffff8171998c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In security/apparmor/notify.c (ffffffff817245a2)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_new_listener
  - security/apparmor/notify.c:aa_new_listener
```
```
In block/bsg-lib.c (ffffffff8179e78d)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In lib/cpu_rmap.c (ffffffff818d3443)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In drivers/pinctrl/core.c (ffffffff818ee8fe)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8195b666)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/acpi/ec.c (ffffffff819ad251)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/clk/clk.c (ffffffff81a44c64)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffffffff81a4d358)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81a74e14)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff81a908b7)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffff81a96e44)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (ffffffff81a9fb72)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (ffffffff81ae33f9)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/char/hw_random/core.c (ffffffff81ae7254)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/base/core.c (ffffffff81b3324e)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (ffffffff81b5f576)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv
```
```
In drivers/nvdimm/core.c (ffffffff81ba220d)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:alloc_nvdimm_map
```
```
In drivers/nvdimm/dimm.c (ffffffff81ba7ba4)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/dax/bus.c (ffffffff81bbad4a)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81bbf30f)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81bc559f)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_create
```
```
In drivers/scsi/hosts.c (ffffffff81bcaaf6)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_scan.c (ffffffff81bd786e)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sg.c (ffffffff81bf5a2e)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_alloc
```
```
In drivers/ata/libata-core.c (ffffffff81bfa454)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81c405b2)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/pse-pd/pse_core.c (0)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81c83a3a)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff81c85670)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff81c8854f)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_init_urb
```
```
In drivers/usb/core/config.c (ffffffff81c9166e)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff81c929e3)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_register_dev
```
```
In drivers/opp/core.c (ffffffff81d94276)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
  - drivers/opp/core.c:_add_opp_table_indexed
```
```
In drivers/nvmem/core.c (ffffffff81dfab70)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
```
```
In lib/klist.c (ffffffff820a1a47)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/klist.c:klist_add_before
  - lib/klist.c:klist_add_behind
  - lib/klist.c:klist_add_tail
  - lib/klist.c:klist_add_head
```
```
In lib/kobject.c (ffffffff820a311e)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
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
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff81098fec)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
```
```
In kernel/sched/build_utility.c (ffffffff8119021d)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:autogroup_init
```
```
In kernel/irq/manage.c (ffffffff811b820d)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/relay.c (ffffffff8127e5db)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/relay.c:relay_open
  - kernel/relay.c:__relay_reset
```
```
In kernel/watch_queue.c (ffffffff813b36cb)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_init
  - kernel/watch_queue.c:init_watch
```
```
In mm/backing-dev.c (ffffffff813f63a6)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_init
```
```
In mm/madvise.c (ffffffff81461e50)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/madvise.c:anon_vma_name_alloc
```
```
In mm/zswap.c (ffffffff8146e617)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff814769ce)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/hugetlb.c:resv_map_alloc
```
```
In mm/memory-tiers.c (ffffffff8149afa1)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/memory-tiers.c:alloc_memory_type
```
```
In fs/eventfd.c (ffffffff81557994)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/configfs/item.c (ffffffff815c637c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/fuse/file.c (ffffffff81699564)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
```
```
In fs/tracefs/event_inode.c (ffffffff816abe29)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/tracefs/event_inode.c:eventfs_create_events_dir
  - fs/tracefs/event_inode.c:eventfs_create_dir
```
```
In security/apparmor/apparmorfs.c (ffffffff81734a9d)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/audit.c (ffffffff81737288)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_dup_audit_data
```
```
In security/apparmor/lib.c (ffffffff8173a3c9)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff8173b075)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy.c (ffffffff81743a8a)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_alloc_pdb
```
```
In security/apparmor/policy_unpack.c (ffffffff817499ba)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/label.c (ffffffff8175842c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In security/apparmor/notify.c (ffffffff817658e9)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_new_listener
  - security/apparmor/notify.c:aa_new_listener
```
```
In block/bsg-lib.c (ffffffff817e2209)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In lib/cpu_rmap.c (ffffffff81925523)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In drivers/pinctrl/core.c (ffffffff819360bd)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff819a4c4a)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/acpi/ec.c (ffffffff819f76d0)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/clk/clk.c (ffffffff81a90774)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffffffff81a98ff8)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81ac6fa3)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff81ae3329)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffff81ae9864)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (ffffffff81af25c2)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (ffffffff81b367e8)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/char/hw_random/core.c (ffffffff81b3a624)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/base/core.c (ffffffff81b8ab8d)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (ffffffff81bb2f85)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv
```
```
In drivers/nvdimm/core.c (ffffffff81bf63cc)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:alloc_nvdimm_map
```
```
In drivers/nvdimm/dimm.c (ffffffff81bfbf33)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/dax/bus.c (ffffffff81c0f554)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81c13a8e)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81c19dbe)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_create
```
```
In drivers/scsi/hosts.c (ffffffff81c1f726)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_scan.c (ffffffff81c2c50e)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sg.c (ffffffff81c4b3cd)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_alloc
```
```
In drivers/ata/libata-core.c (ffffffff81c4fe74)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/gpu/drm/drm_atomic.c (ffffffff81c7b275)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_state_init
```
```
In drivers/gpu/drm/drm_auth.c (ffffffff81c7e897)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_auth.c:drm_master_create
```
```
In drivers/gpu/drm/drm_connector.c (ffffffff81c87331)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_connector.c:drm_mode_create_tile_group
```
```
In drivers/gpu/drm/drm_drv.c (ffffffff81c8b7e2)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_drv.c:drm_dev_init
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9b73c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem.c:drm_gem_private_object_init
```
```
In drivers/gpu/drm/drm_mode_object.c (ffffffff81ca3e70)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/gpu/drm/drm_syncobj.c (ffffffff81cafd80)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_create
```
```
In drivers/gpu/drm/drm_atomic_helper.c (ffffffff81cc3ed1)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_setup_commit
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81cf5c11)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/pse-pd/pse_core.c (0)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81d38419)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff81d3a2b4)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff81d3cf9f)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_init_urb
```
```
In drivers/usb/core/config.c (ffffffff81d4622e)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/opp/core.c (ffffffff81e4bd96)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
  - drivers/opp/core.c:_add_opp_table_indexed
```
```
In drivers/nvmem/core.c (ffffffff81eb1bef)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
```
```
In net/ipv4/tcp_sigpool.c (ffffffff8204cf53)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_alloc_ahash
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_alloc_ahash
```
```
In lib/klist.c (ffffffff82179ac7)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/klist.c:klist_add_before
  - lib/klist.c:klist_add_behind
  - lib/klist.c:klist_add_tail
  - lib/klist.c:klist_add_head
```
```
In lib/kobject.c (ffffffff8217b199)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
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
In virt/kvm/arm/vgic/vgic-init.c (ffff8000100dde00)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-init.c:kvm_vgic_vcpu_init
```
```
In virt/kvm/arm/vgic/vgic-its.c (ffff8000100e8780)
Location: include/linux/kref.h:29
Inline: True
```
```
In kernel/sched/autogroup.c (ffff80001015f0dc)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/sched/psi.c (ffff800010167e9c)
Location: include/linux/kref.h:29
Inline: True
```
```
In kernel/irq/manage.c (ffff800010179e8c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/utsname.c (ffff8000101e52d4)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffff8000101e785c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/relay.c (ffff80001020aa98)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In mm/backing-dev.c (ffff8000102df344)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:default_bdi_init
```
```
In mm/zswap.c (ffff80001032b2b4)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffff800010331020)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/hugetlb.c:resv_map_alloc
```
```
In fs/eventfd.c (ffff8000103f5dfc)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/configfs/item.c (ffff80001045df7c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/fuse/file.c (ffff80001050e288)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
```
```
In security/apparmor/apparmorfs.c (ffff80001058d04c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffff80001058f820)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffff8000105904d4)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffff800010599a74)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/label.c (ffff8000105a1fcc)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In block/bsg-lib.c (ffff80001060b120)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In lib/cpu_rmap.c (ffff8000106625a4)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In drivers/pinctrl/core.c (ffff80001068d5a8)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffff8000107131cc)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/acpi/ec.c (ffff80001076ffa0)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/clk/clk.c (ffff8000107c27a0)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffff8000107fcda8)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
```
```
In drivers/soc/qcom/smem_state.c (ffff80001081dab0)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/soc/qcom/smem_state.c:qcom_smem_state_register
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffff800010839efc)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffff80001084c3ec)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffff800010853678)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (ffff80001085ddf8)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (ffff8000108b5300)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:add_port
```
```
In drivers/char/hw_random/core.c (ffff8000108b71c8)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/lightnvm/core.c (ffff8000108dee94)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/base/core.c (ffff8000108e6558)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (ffff80001090d5a8)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/nvdimm/core.c (ffff80001094feec)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm.c (ffff800010954f0c)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/dax/bus.c (ffff800010964080)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-fence.c (ffff800010966400)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_init
```
```
In drivers/dma-buf/sw_sync.c (ffff80001096ae80)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi_scan.c (ffff80001097bb58)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sr.c (ffff80001098c894)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffff800010991720)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffff80001099700c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/sfp-bus.c (ffff8000109d9b50)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/usb/core/hub.c (ffff800010a1a1f0)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffff800010a1bcb0)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffff800010a1ff6c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_init_urb
```
```
In drivers/usb/core/config.c (ffff800010a27eb4)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffff800010a29110)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/media/cec/cec-notifier.c (ffff800010ac37a0)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/opp/core.c (ffff800010b1a66c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
  - drivers/opp/core.c:_opp_get_opp_table
  - drivers/opp/core.c:_opp_get_opp_table
```
```
In drivers/opp/of.c (ffff800010b1bf48)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (ffff800010b809b8)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/nvmem/core.c (ffff800010b9fb58)
Location: include/linux/kref.h:29
Inline: True
```
```
In lib/klist.c (ffff800010d89a34)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
```
```
In lib/kobject.c (ffff800010d8b174)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init
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
In arch/arm/mm/dma-mapping.c (c031e54c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - arch/arm/mm/dma-mapping.c:arm_iommu_create_mapping
```
```
In kernel/sched/autogroup.c (c03ab980)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/sched/psi.c (c03b312c)
Location: include/linux/kref.h:29
Inline: True
```
```
In kernel/irq/manage.c (c03ca84c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/utsname.c (c0425b7c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (c0427c5c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/relay.c (c0449684)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In mm/backing-dev.c (c050419c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:default_bdi_init
```
```
In mm/zswap.c (c0541540)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In fs/eventfd.c (c05cac88)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/configfs/item.c (c061ea6c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/fuse/file.c (c06c9948)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
```
```
In security/apparmor/apparmorfs.c (c073dcc4)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (c0740610)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (c07411dc)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (c074abec)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/label.c (c0752678)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In block/bsg-lib.c (c07b608c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In lib/cpu_rmap.c (c080b27c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In drivers/pinctrl/core.c (c082f62c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/clk/clk.c (c08ed3e4)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (c091e1b0)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
```
```
In drivers/soc/qcom/smem_state.c (c0938488)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/soc/qcom/smem_state.c:qcom_smem_state_register
```
```
In drivers/reset/core.c (c095874c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (c095dfe4)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (c096598c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (c09af41c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:add_port
```
```
In drivers/char/hw_random/core.c (c09b0e84)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/lightnvm/core.c (c09cdd64)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/base/core.c (c09d4b80)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (c09f65c4)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/dax/bus.c (c0a3b2cc)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (c0a3d318)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_init
```
```
In drivers/dma-buf/sw_sync.c (c0a40e44)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi_scan.c (c0a4e988)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sr.c (c0a5ee38)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (c0a61b58)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (c0a679c4)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/mtd/mtd_blkdevs.c (c0a97fe8)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/mtd/mtd_blkdevs.c:add_mtd_blktrans_dev
```
```
In drivers/net/phy/sfp-bus.c (c0ac076c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/usb/core/hub.c (c0af2428)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (c0af4c74)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (c0af7100)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_init_urb
```
```
In drivers/usb/core/config.c (c0afdf1c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (c0aff0f8)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/media/cec/cec-notifier.c (c0ba52b4)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/opp/core.c (c0bf521c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
  - drivers/opp/core.c:_opp_get_opp_table
  - drivers/opp/core.c:_opp_get_opp_table
```
```
In drivers/opp/of.c (c0bf6770)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (c0c63fbc)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/nvmem/core.c (c0c814c0)
Location: include/linux/kref.h:29
Inline: True
```
```
In lib/klist.c (c0e84ad8)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
```
```
In lib/kobject.c (c0e85ee8)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init
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
In arch/powerpc/platforms/powernv/pci.c (c0000000000d0f94)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci.c:pnv_pci_table_alloc
```
```
In arch/powerpc/platforms/pseries/iommu.c (c0000000000f0660)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/iommu.c:iommu_pseries_alloc_group
```
```
In arch/powerpc/platforms/pseries/vio.c (c000000000101868)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/vio.c:vio_register_device_node
```
```
In kernel/sched/autogroup.c (c0000000001b447c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/sched/psi.c (c0000000001bfd60)
Location: include/linux/kref.h:29
Inline: True
```
```
In kernel/irq/manage.c (c0000000001d31c8)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/utsname.c (c0000000002556e0)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (c000000000258154)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/relay.c (c000000000287e3c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In mm/backing-dev.c (c00000000039ed64)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:default_bdi_init
```
```
In mm/zswap.c (c0000000004032fc)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (c000000000409cac)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/hugetlb.c:resv_map_alloc
```
```
In fs/eventfd.c (c0000000004fdea8)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/configfs/item.c (c000000000579c18)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/fuse/file.c (c0000000006551d4)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
```
```
In security/apparmor/apparmorfs.c (c0000000006ff2d4)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (c000000000702b60)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (c000000000703b30)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (c000000000710d3c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/label.c (c00000000071cf68)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In block/bsg-lib.c (c0000000007a7780)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In lib/cpu_rmap.c (c000000000816728)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In drivers/pinctrl/core.c (c0000000008272e4)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/dma/dmaengine.c (c0000000008c8280)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
```
```
In drivers/reset/core.c (c0000000008eb98c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (c0000000008f2a00)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (c0000000008fd3b4)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (c00000000094e9dc)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:add_port
```
```
In drivers/char/hw_random/core.c (c000000000951534)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:set_current_rng
```
```
In drivers/lightnvm/core.c (c0000000009730c4)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/base/core.c (c00000000097c2b0)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (c0000000009adb18)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/nvdimm/core.c (c0000000009fcb64)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm.c (c000000000a02ba0)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/dax/bus.c (c000000000a1adbc)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-fence.c (c000000000a1e00c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_init
```
```
In drivers/dma-buf/sw_sync.c (c000000000a23c3c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi_scan.c (c000000000a3557c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sr.c (c000000000a4de9c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (c000000000a52dc0)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (c000000000a5a28c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/sfp-bus.c (c000000000a9ba28)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/vfio/vfio.c (c000000000ab0dc4)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_fops_open
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
```
```
In drivers/vfio/pci/vfio_pci.c (c000000000ab6c8c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
```
In drivers/usb/core/hub.c (c000000000ad393c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (c000000000ad559c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (c000000000ada0b8)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_init_urb
```
```
In drivers/usb/core/config.c (c000000000ae3cb0)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (c000000000ae545c)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/media/cec/cec-notifier.c (c000000000ba66d4)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/opp/core.c (c000000000c0c3e8)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
  - drivers/opp/core.c:_opp_get_opp_table
  - drivers/opp/core.c:_opp_get_opp_table
```
```
In drivers/opp/of.c (c000000000c0e4bc)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (c000000000c5d254)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/nvmem/core.c (c000000000c731fc)
Location: include/linux/kref.h:29
Inline: True
```
```
In lib/klist.c (c000000000ecb058)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
```
```
In lib/kobject.c (c000000000ecd19c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init
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
In kernel/sched/autogroup.c (ffffffe0001033d8)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/sched/psi.c (ffffffe0001096d2)
Location: include/linux/kref.h:29
Inline: True
```
```
In kernel/irq/manage.c (ffffffe0001138b0)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/utsname.c (ffffffe00015afb4)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffe00015cd0e)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/relay.c (ffffffe00016c4d8)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In mm/backing-dev.c (ffffffe0001f70be)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:default_bdi_init
```
```
In mm/zswap.c (ffffffe000229e80)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffe00022e1f2)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/hugetlb.c:resv_map_alloc
```
```
In fs/eventfd.c (ffffffe0002a672c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/configfs/item.c (ffffffe0002edd5c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/fuse/file.c (ffffffe000378f30)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
```
```
In security/apparmor/apparmorfs.c (ffffffe0003db2a4)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffe0003dd4b4)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffe0003ddf84)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffe0003e6174)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/label.c (ffffffe0003eca2a)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In block/bsg-lib.c (ffffffe0004442ee)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In lib/cpu_rmap.c (ffffffe00048ef26)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In drivers/pinctrl/core.c (ffffffe0004997a0)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/clk/clk.c (ffffffe000510280)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffffffe0005175da)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
```
```
In drivers/reset/core.c (ffffffe00052bca2)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffe00052ff22)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (ffffffe000536b2e)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (ffffffe000566932)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:add_port
```
```
In drivers/char/hw_random/core.c (ffffffe000567f2e)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffe000575444)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/base/core.c (ffffffe00057afa4)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (ffffffe000592042)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/nvdimm/core.c (ffffffe0005c02f4)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm.c (ffffffe0005c44f4)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/dax/bus.c (ffffffe0005d182e)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-fence.c (ffffffe0005d35da)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffe0005d6402)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi_scan.c (ffffffe0005e29b2)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sr.c (ffffffe0005f13be)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffe0005f38b2)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffe0005f8754)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/sfp-bus.c (ffffffe000624a5e)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/usb/core/hub.c (ffffffe00063ec36)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffe000640438)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffe000643a22)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_alloc_urb
```
```
In drivers/usb/core/config.c (ffffffe000649b0e)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffe00064ab0e)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/media/cec/cec-notifier.c (ffffffe0006c441a)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/opp/core.c (ffffffe000702d80)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
  - drivers/opp/core.c:_opp_get_opp_table
  - drivers/opp/core.c:_opp_get_opp_table
```
```
In drivers/opp/of.c (ffffffe0007040a8)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/nvmem/core.c (ffffffe000737c48)
Location: include/linux/kref.h:29
Inline: True
```
```
In lib/klist.c (ffffffe0008b3666)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
```
```
In lib/kobject.c (ffffffe0008b4b5a)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init
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
In kernel/sched/autogroup.c (ffffffff810f3a9f)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/sched/psi.c (ffffffff810fc2af)
Location: include/linux/kref.h:29
Inline: True
```
```
In kernel/irq/manage.c (ffffffff81110219)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/utsname.c (ffffffff81169cd8)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff8116bb48)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/relay.c (ffffffff8118b3dd)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In mm/backing-dev.c (ffffffff81242165)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:default_bdi_init
```
```
In mm/zswap.c (ffffffff81286c16)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff8128b868)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/hugetlb.c:resv_map_alloc
```
```
In fs/eventfd.c (ffffffff81330155)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/configfs/item.c (ffffffff81384aa8)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/fuse/file.c (ffffffff81422868)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
```
```
In security/apparmor/apparmorfs.c (ffffffff8148f8c1)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffff81491ffa)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff814929e7)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff8149c2dd)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/label.c (ffffffff814a3602)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In block/bsg-lib.c (ffffffff81500c2d)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In lib/cpu_rmap.c (ffffffff8154e343)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In drivers/pinctrl/core.c (ffffffff815591c3)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8159d641)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/acpi/ec.c (ffffffff815d5cd4)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/clk/clk.c (ffffffff81617caf)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffffffff8161ccf8)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81635744)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff8164746d)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff8164b67b)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (ffffffff81652eb2)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (ffffffff81687f8a)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:add_port
```
```
In drivers/char/hw_random/core.c (ffffffff8168ac1c)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff816bb296)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/base/core.c (ffffffff816c140b)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (ffffffff816e0152)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/nvdimm/core.c (ffffffff81704bbf)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm.c (ffffffff81708a87)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/dax/bus.c (ffffffff81718dc0)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8171aecb)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8171de3a)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi_scan.c (ffffffff8172ab8d)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sr.c (ffffffff8173a8bd)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff8173ca7e)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/nvme/host/core.c (ffffffff81746e60)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_alloc_ns
  - drivers/nvme/host/core.c:nvme_alloc_ns_head
  - drivers/nvme/host/core.c:nvme_init_subsystem
```
```
In drivers/ata/libata-core.c (ffffffff81753474)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81784198)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/usb/core/hub.c (ffffffff817a442a)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff817a4dcf)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff817a872f)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_init_urb
```
```
In drivers/usb/core/config.c (ffffffff817aef38)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff817b081f)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/media/cec/cec-notifier.c (ffffffff81824332)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/opp/core.c (ffffffff81863a7b)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81895b5a)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/nvmem/core.c (ffffffff818a2af6)
Location: include/linux/kref.h:29
Inline: True
```
```
In lib/klist.c (ffffffff81a4f012)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
```
```
In lib/kobject.c (ffffffff81a50566)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init
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
In kernel/sched/autogroup.c (ffffffff810e3bcf)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/sched/psi.c (ffffffff810ec4bf)
Location: include/linux/kref.h:29
Inline: True
```
```
In kernel/irq/manage.c (ffffffff81100f49)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/utsname.c (ffffffff8115ced8)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff8115ed48)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/relay.c (ffffffff8117e4dd)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In mm/backing-dev.c (ffffffff81235135)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:default_bdi_init
```
```
In mm/zswap.c (ffffffff81278a76)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff8127d698)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/hugetlb.c:resv_map_alloc
```
```
In fs/eventfd.c (ffffffff81320d75)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/configfs/item.c (ffffffff81375538)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/fuse/file.c (ffffffff814132e8)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
```
```
In security/apparmor/apparmorfs.c (ffffffff814802e1)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffff81482a1a)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff81483407)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff8148ccfd)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/label.c (ffffffff81494022)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In block/bsg-lib.c (ffffffff814f113d)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In lib/cpu_rmap.c (ffffffff8153e623)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In drivers/pinctrl/core.c (ffffffff81549683)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8158c7d1)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/acpi/ec.c (ffffffff815bf894)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/clk/clk.c (ffffffff8160c1df)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffffffff816113e8)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
```
```
In drivers/reset/core.c (ffffffff816278cd)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff8162bacb)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (ffffffff816332f2)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (ffffffff81665aaa)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:add_port
```
```
In drivers/char/hw_random/core.c (ffffffff8166861c)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/base/core.c (ffffffff8169c6bb)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (ffffffff816ba792)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/nvdimm/core.c (ffffffff816d863f)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm.c (ffffffff816dc507)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/dax/bus.c (ffffffff816f12f0)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff816f432b)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff816f729a)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi_scan.c (ffffffff81703fad)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sr.c (ffffffff8171c55d)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff8171e71e)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/nvme/host/core.c (ffffffff81728ae4)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_alloc_ns
  - drivers/nvme/host/core.c:nvme_alloc_ns_head
  - drivers/nvme/host/core.c:nvme_init_subsystem
```
```
In drivers/ata/libata-core.c (ffffffff81733314)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81763ae8)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/vfio/vfio.c (ffffffff8177a720)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_fops_open
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff8178180c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
```
In drivers/usb/core/hub.c (ffffffff81795f9b)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff817968df)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff8179a13f)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_init_urb
```
```
In drivers/usb/core/config.c (ffffffff817a0938)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff817a21e0)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_register_dev
```
```
In drivers/media/cec/cec-notifier.c (ffffffff817eb9d2)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/opp/core.c (ffffffff8182c72b)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
```
```
In drivers/nvmem/core.c (ffffffff8185e266)
Location: include/linux/kref.h:29
Inline: True
```
```
In lib/klist.c (ffffffff81a0c112)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
```
```
In lib/kobject.c (ffffffff81a0d666)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init
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
In kernel/sched/autogroup.c (ffffffff810f0bef)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/sched/psi.c (ffffffff810f946f)
Location: include/linux/kref.h:29
Inline: True
```
```
In kernel/irq/manage.c (ffffffff8110e109)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/utsname.c (ffffffff81167aa8)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff81169918)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/relay.c (ffffffff811891ad)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In mm/backing-dev.c (ffffffff8123ff05)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:default_bdi_init
```
```
In mm/zswap.c (ffffffff81284a26)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff81289678)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/hugetlb.c:resv_map_alloc
```
```
In fs/eventfd.c (ffffffff8132dc25)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/configfs/item.c (ffffffff81382578)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/fuse/file.c (ffffffff8141ea08)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
```
```
In security/apparmor/apparmorfs.c (ffffffff8148b961)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffff8148e09a)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff8148ea87)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff8149837d)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/label.c (ffffffff8149f6a2)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In block/bsg-lib.c (ffffffff814fccbd)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In lib/cpu_rmap.c (ffffffff8154a083)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In drivers/pinctrl/core.c (ffffffff81554f03)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8159dbc1)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/acpi/ec.c (ffffffff815d80c4)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/clk/clk.c (ffffffff81645a8f)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffffffff8164ac98)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff816634c4)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff8167582d)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81679a3b)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (ffffffff81681272)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (ffffffff816b626a)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:add_port
```
```
In drivers/char/hw_random/core.c (ffffffff816b8e8c)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff816e9766)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/base/core.c (ffffffff816ef8db)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (ffffffff8170d6cc)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/nvdimm/core.c (ffffffff8174398f)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm.c (ffffffff81747857)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/dax/bus.c (ffffffff81757b90)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81759c9b)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8175cc0a)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi_scan.c (ffffffff8176995d)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sr.c (ffffffff8177b04d)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff8177d20e)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffff81783164)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/sfp-bus.c (ffffffff817b4548)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/vfio/vfio.c (ffffffff817c54f0)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_fops_open
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817cc5dc)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
```
In drivers/usb/core/hub.c (ffffffff817e0eca)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff817e186f)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff817e51cf)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_init_urb
```
```
In drivers/usb/core/config.c (ffffffff817eb9d8)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff817ed2bf)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/media/cec/cec-notifier.c (ffffffff81871272)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/opp/core.c (ffffffff818b480b)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
```
```
In drivers/nvmem/core.c (ffffffff818f40e6)
Location: include/linux/kref.h:29
Inline: True
```
```
In lib/klist.c (ffffffff81abb402)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
```
```
In lib/kobject.c (ffffffff81abc956)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init
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
In kernel/sched/autogroup.c (ffffffff810fbc7f)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/sched/psi.c (ffffffff811045af)
Location: include/linux/kref.h:29
Inline: True
```
```
In kernel/irq/manage.c (ffffffff81119642)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/utsname.c (ffffffff81175188)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff81177038)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/relay.c (ffffffff81196afd)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In mm/backing-dev.c (ffffffff8124f665)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:default_bdi_init
```
```
In mm/zswap.c (ffffffff812946c6)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff81299458)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - mm/hugetlb.c:resv_map_alloc
```
```
In fs/eventfd.c (ffffffff81340a05)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/configfs/item.c (ffffffff81396098)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/fuse/file.c (ffffffff81435768)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
```
```
In security/apparmor/apparmorfs.c (ffffffff814a3741)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffff814a5faa)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff814a6997)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff814b04cd)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/label.c (ffffffff814b7cd2)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In block/bsg-lib.c (ffffffff81515d6d)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In lib/cpu_rmap.c (ffffffff81563ed3)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In drivers/pinctrl/core.c (ffffffff8156ed93)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff815b7ff1)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/acpi/ec.c (ffffffff815f1f84)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/clk/clk.c (ffffffff8166001f)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffffffff81665238)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8167da84)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff8168fe8d)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff8169409b)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (ffffffff8169b8c2)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (ffffffff816d085a)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:add_port
```
```
In drivers/char/hw_random/core.c (ffffffff816d345c)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff81703fa6)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/base/core.c (ffffffff8170a11b)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (ffffffff81728486)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/nvdimm/core.c (ffffffff8175eddf)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm.c (ffffffff81762c97)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/dax/bus.c (ffffffff81773030)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8177520b)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff817782aa)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi_scan.c (ffffffff817850ad)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sr.c (ffffffff81794bbd)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff81797035)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffff8179d024)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/sfp-bus.c (ffffffff817ce518)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/vfio/vfio.c (ffffffff817df790)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_fops_open
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817e687c)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
```
In drivers/usb/core/hub.c (ffffffff817fb1ba)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff817fbc5f)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff817ff42f)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_init_urb
```
```
In drivers/usb/core/config.c (ffffffff81805c18)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff818074ff)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/media/cec/cec-notifier.c (ffffffff8188b232)
Location: include/linux/kref.h:29
Inline: True
```
```
In drivers/opp/core.c (ffffffff818d0abb)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819062ba)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/nvmem/core.c (ffffffff81915186)
Location: include/linux/kref.h:29
Inline: True
```
```
In lib/klist.c (ffffffff81ac7872)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
```
```
In lib/kobject.c (ffffffff81ac8dd6)
Location: include/linux/kref.h:29
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init
```
</details>
</li>
</ul>

## Differences
