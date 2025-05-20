# Function: <code>__ab_c_size</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff826d28d3)
Location: include/linux/overflow.h:281
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_type_init
```
```
In kernel/workqueue.c (ffffffff810ae715)
Location: include/linux/overflow.h:281
Inline: True
Inline callers:
  - kernel/workqueue.c:apply_wqattrs_prepare
```
```
In kernel/module.c (ffffffff81130a6b)
Location: include/linux/overflow.h:281
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
```
```
In kernel/cgroup/cgroup.c (ffffffff81142706)
Location: include/linux/overflow.h:281
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
```
```
In drivers/gpio/gpiolib.c (ffffffff8150af6d)
Location: include/linux/overflow.h:281
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
```
In drivers/reset/core.c (0)
Location: include/linux/overflow.h:281
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff8164a6b1)
Location: include/linux/overflow.h:281
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:alloc_buf
```
```
In drivers/input/input-mt.c (ffffffff817c0d15)
Location: include/linux/overflow.h:281
Inline: True
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
In arch/x86/events/intel/uncore.c (ffffffff82888bf6)
Location: include/linux/overflow.h:281
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_type_init
```
```
In kernel/workqueue.c (ffffffff810b7875)
Location: include/linux/overflow.h:281
Inline: True
Inline callers:
  - kernel/workqueue.c:apply_wqattrs_prepare
```
```
In kernel/module.c (ffffffff8113c333)
Location: include/linux/overflow.h:281
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
```
```
In kernel/cgroup/cgroup.c (ffffffff8114e188)
Location: include/linux/overflow.h:281
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
```
```
In drivers/gpio/gpiolib.c (ffffffff8151fc0c)
Location: include/linux/overflow.h:281
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
```
In drivers/reset/core.c (0)
Location: include/linux/overflow.h:281
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff8166888e)
Location: include/linux/overflow.h:281
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:alloc_buf
```
```
In drivers/input/input-mt.c (ffffffff817e8205)
Location: include/linux/overflow.h:281
Inline: True
```
```
In net/xdp/xsk_queue.c (ffffffff81a065af)
Location: include/linux/overflow.h:281
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
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
In arch/x86/events/intel/uncore.c (ffffffff8289fdc8)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_types_init
```
```
In arch/x86/kernel/crash.c (ffffffff81070967)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_load_segments
```
```
In kernel/workqueue.c (ffffffff810bd2f5)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/workqueue.c:apply_wqattrs_prepare
```
```
In kernel/irq/devres.c (ffffffff81110065)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
```
In kernel/module.c (ffffffff8114794b)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
```
```
In kernel/cgroup/cgroup.c (ffffffff8115788a)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
```
```
In kernel/tracepoint.c (ffffffff8118a380)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/tracepoint.c:allocate_probes
```
```
In mm/swapfile.c (ffffffff8127c4f6)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/memcontrol.c (ffffffff812af167)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
```
```
In fs/select.c (ffffffff812e44ed)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/io_uring.c (ffffffff81330eab)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
```
In ipc/sem.c (ffffffff81420b56)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - ipc/sem.c:newary
```
```
In block/bio.c (ffffffff814c7183)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
```
```
In block/genhd.c (ffffffff814e0c2f)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - block/genhd.c:disk_expand_part_tbl
```
```
In block/bio-integrity.c (ffffffff814f8403)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_alloc
```
```
In lib/rhashtable.c (ffffffff8150ce10)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff8154dd4e)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
```
In drivers/reset/core.c (0)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff81693075)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/char/virtio_console.c (ffffffff8169f58d)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:alloc_buf
```
```
In drivers/char/hpet.c (ffffffff816a17bd)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
```
```
In drivers/iommu/dmar.c (ffffffff816c3bdd)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/spi/spi.c (ffffffff817907b5)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
```
In drivers/usb/core/urb.c (ffffffff817bf9f5)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_alloc_urb
```
```
In drivers/usb/core/config.c (ffffffff817c60ca)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817dc572)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/xhci.c (ffffffff81806485)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/input/input-mt.c (ffffffff81828d62)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/input/evdev.c (ffffffff8182ba0f)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In net/core/flow_offload.c (ffffffff819315f5)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_rule_alloc
```
```
In net/ipv4/fib_semantics.c (ffffffff819c8ea8)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/xdp/xsk_queue.c (ffffffff81a75f1d)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
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
In arch/x86/events/intel/uncore.c (ffffffff828a2e9a)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_types_init
```
```
In arch/x86/kernel/crash.c (ffffffff81071967)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_load_segments
```
```
In kernel/workqueue.c (ffffffff810c3975)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/workqueue.c:apply_wqattrs_prepare
```
```
In kernel/irq/devres.c (ffffffff8111c2e5)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
```
In kernel/module.c (ffffffff81153786)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
```
```
In kernel/cgroup/cgroup.c (ffffffff811634fa)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
```
```
In kernel/tracepoint.c (ffffffff81196290)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/tracepoint.c:allocate_probes
```
```
In mm/percpu.c (ffffffff828db11b)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_alloc_info
```
```
In mm/swapfile.c (ffffffff8128bfd6)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/memcontrol.c (ffffffff812c0bc7)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
```
```
In fs/select.c (ffffffff812f5f29)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/io_uring.c (ffffffff81344cb6)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:ring_pages
```
```
In ipc/sem.c (ffffffff8143a946)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - ipc/sem.c:newary
```
```
In security/integrity/ima/ima_api.c (ffffffff814b8308)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
```
```
In security/integrity/ima/ima_template.c (ffffffff814baa80)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/bio.c (ffffffff814e0002)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
```
```
In block/genhd.c (ffffffff814fa05f)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - block/genhd.c:disk_expand_part_tbl
```
```
In block/bio-integrity.c (ffffffff81516186)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_alloc
```
```
In lib/rhashtable.c (ffffffff8152ac60)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff8156ef4e)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
```
In drivers/reset/core.c (0)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff816b5c15)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/char/virtio_console.c (ffffffff816c231d)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:alloc_buf
```
```
In drivers/char/hpet.c (ffffffff816c455d)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
```
```
In drivers/iommu/dmar.c (ffffffff816e6b32)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/nvdimm/region_devs.c (ffffffff81755911)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/spi/spi.c (ffffffff817b4395)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
```
In drivers/usb/core/urb.c (ffffffff817f0375)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_alloc_urb
```
```
In drivers/usb/core/config.c (ffffffff817f6b7e)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8180d495)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/xhci.c (ffffffff81837335)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/input/input-mt.c (ffffffff8185a2d2)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/input/evdev.c (ffffffff8185d38f)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-stats.c (ffffffff818b52da)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff818f770b)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_elf_loader.c:find_table
```
```
In net/core/flow_offload.c (ffffffff81963905)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_rule_alloc
```
```
In net/core/drop_monitor.c (ffffffff81975125)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_reset_per_cpu_data
```
```
In net/ipv4/fib_semantics.c (ffffffff819ffa68)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/xdp/xsk_queue.c (ffffffff81aacddd)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
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
In arch/x86/events/intel/uncore.c (ffffffff82cc8f31)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_type_init
```
```
In arch/x86/kernel/crash.c (ffffffff8107827b)
Location: include/linux/overflow.h:291
Inline: True
```
```
In kernel/workqueue.c (ffffffff810cb275)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/workqueue.c:apply_wqattrs_prepare
```
```
In kernel/irq/devres.c (ffffffff81128615)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
```
In kernel/module.c (ffffffff81161fb4)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/module.c:add_notes_attrs
  - kernel/module.c:add_sect_attrs
```
```
In kernel/cgroup/cgroup.c (ffffffff81174781)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
```
```
In kernel/tracepoint.c (ffffffff811ab2e4)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_remove_func
  - kernel/tracepoint.c:func_add
```
```
In kernel/watch_queue.c (ffffffff8124d1fd)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_filter
```
```
In mm/percpu.c (ffffffff82cf9151)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_alloc_info
```
```
In mm/swapfile.c (ffffffff812bb595)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_swap_info
```
```
In mm/memcontrol.c (ffffffff812f726e)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
```
```
In fs/select.c (ffffffff8132f049)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/io_uring.c (ffffffff8137c6c2)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - fs/io_uring.c:io_allocate_scq_urings
  - fs/io_uring.c:ring_pages
```
```
In ipc/sem.c (ffffffff8148ad86)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - ipc/sem.c:newary
```
```
In security/integrity/ima/ima_api.c (ffffffff81517ec9)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
```
```
In security/integrity/ima/ima_template.c (ffffffff8151ab15)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_template_data
```
```
In block/blk-map.c (ffffffff815499ac)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - block/blk-map.c:bio_alloc_map_data
```
```
In block/genhd.c (ffffffff8155af2b)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - block/genhd.c:disk_expand_part_tbl
```
```
In block/bio-integrity.c (ffffffff81576681)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_alloc
```
```
In lib/rhashtable.c (ffffffff8158e270)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff8161340e)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
```
In drivers/reset/core.c (0)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff81769235)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/char/virtio_console.c (ffffffff81774aad)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:alloc_buf
```
```
In drivers/char/hpet.c (ffffffff81778c0d)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
```
```
In drivers/char/tpm/eventlog/tpm2.c (ffffffff81788a8c)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
```
```
In drivers/iommu/iommu.c (ffffffff8178d9cf)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_fwspec_add_ids
```
```
In drivers/iommu/intel/dmar.c (ffffffff8179d3c2)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/block/xen-blkfront.c (ffffffff817ebaf6)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:negotiate_mq
```
```
In drivers/nvdimm/region_devs.c (ffffffff818137e1)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/spi/spi.c (ffffffff818798e5)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
```
In drivers/usb/core/urb.c (ffffffff818c0615)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_alloc_urb
```
```
In drivers/usb/core/config.c (ffffffff818c6e69)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818de2e5)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/xhci.c (ffffffff81909b35)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/input/input-mt.c (ffffffff8192cee5)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/input/evdev.c (ffffffff8193155d)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-stripe.c (ffffffff8197f913)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/md/dm-ioctl.c (ffffffff81980a86)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:retrieve_deps
```
```
In drivers/md/dm-stats.c (ffffffff81986072)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/firmware/efi/efi.c (ffffffff82d29c6b)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819ca901)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff819cd975)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/interconnect/core.c (ffffffff819dc6a4)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/interconnect/core.c:path_find
```
```
In net/core/flow_offload.c (ffffffff81a36dd5)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_rule_alloc
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/overflow.h:291
Inline: True
```
```
In net/netlink/policy.c (ffffffff81a7d75d)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - net/netlink/policy.c:add_policy
```
```
In net/ipv4/fib_semantics.c (ffffffff81aef073)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/xdp/xsk_queue.c (ffffffff81ba8da2)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xskq_create
  - net/xdp/xsk_queue.c:xskq_create
```
```
In net/xdp/xskmap.c (ffffffff81ba8fb1)
Location: include/linux/overflow.h:291
Inline: True
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ba9b35)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_create
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
In arch/x86/events/intel/uncore.c (ffffffff82fb4d58)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_type_init
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff82fc19f8)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
```
```
In arch/x86/kernel/crash.c (ffffffff8107827b)
Location: include/linux/overflow.h:301
Inline: True
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff82fd8d73)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
```
```
In kernel/workqueue.c (ffffffff810c63a5)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - kernel/workqueue.c:apply_wqattrs_prepare
```
```
In kernel/irq/devres.c (ffffffff81123f59)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
```
In kernel/module.c (ffffffff8115e1a4)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - kernel/module.c:add_notes_attrs
  - kernel/module.c:add_sect_attrs
```
```
In kernel/cgroup/cgroup.c (ffffffff81171451)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
```
```
In kernel/audit_tree.c (ffffffff8118fb79)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/tracepoint.c (ffffffff811a90b2)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - kernel/tracepoint.c:func_remove
  - kernel/tracepoint.c:func_add
```
```
In kernel/watch_queue.c (ffffffff8125765d)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_filter
```
```
In mm/percpu.c (ffffffff82fe5c39)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_alloc_alloc_info
```
```
In mm/swapfile.c (ffffffff812c7035)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_swap_info
```
```
In mm/memcontrol.c (ffffffff813026ce)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
```
```
In fs/select.c (ffffffff8133a929)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/io_uring.c (ffffffff8138abf2)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - fs/io_uring.c:io_allocate_scq_urings
  - fs/io_uring.c:ring_pages
```
```
In fs/crypto/inline_crypt.c (ffffffff813a7744)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
```
```
In fs/iomap/buffered-io.c (ffffffff813bcc06)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In ipc/sem.c (ffffffff814a83a5)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - ipc/sem.c:newary
```
```
In security/integrity/ima/ima_api.c (ffffffff81534e99)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
```
```
In security/integrity/ima/ima_policy.c (ffffffff81535ac3)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_alloc_rule_opt_list
```
```
In security/integrity/ima/ima_template.c (ffffffff81537a75)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_template_data
```
```
In block/bio.c (ffffffff8155ba1d)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - block/bio.c:bio_alloc_bioset
```
```
In block/blk-map.c (ffffffff81565a3c)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - block/blk-map.c:bio_alloc_map_data
```
```
In block/genhd.c (ffffffff815771b8)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - block/genhd.c:disk_expand_part_tbl
```
```
In block/blk-iocost.c (ffffffff8158c38a)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_alloc
```
```
In block/bio-integrity.c (ffffffff8159357f)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_alloc
```
```
In lib/rhashtable.c (ffffffff815aad88)
Location: include/linux/overflow.h:301
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff816382dc)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8163afd5)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_create
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff81688216)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:remove_conflicting_pci_framebuffers
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: include/linux/overflow.h:301
Inline: True
```
```
In drivers/video/fbdev/efifb.c (0)
Location: include/linux/overflow.h:301
Inline: True
```
```
In drivers/video/fbdev/simplefb.c (0)
Location: include/linux/overflow.h:301
Inline: True
```
```
In drivers/reset/core.c (0)
Location: include/linux/overflow.h:301
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff81784061)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/char/virtio_console.c (ffffffff8178f80d)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:alloc_buf
```
```
In drivers/char/hpet.c (ffffffff817936dd)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
```
```
In drivers/char/tpm/eventlog/tpm2.c (ffffffff8179fa1c)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
```
```
In drivers/iommu/intel/dmar.c (ffffffff817ab0f2)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/iommu/iommu.c (ffffffff817b973f)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_fwspec_add_ids
```
```
In drivers/block/xen-blkfront.c (ffffffff81800426)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:negotiate_mq
```
```
In drivers/nvdimm/region_devs.c (ffffffff818229d1)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81838ec5)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_list_alloc
```
```
In drivers/spi/spi.c (ffffffff81888285)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
```
In drivers/usb/core/urb.c (ffffffff818cc535)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_alloc_urb
```
```
In drivers/usb/core/config.c (ffffffff818d2aa9)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818e8157)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/xhci.c (ffffffff8191250a)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/input/input-mt.c (ffffffff819343a5)
Location: include/linux/overflow.h:301
Inline: True
```
```
In drivers/input/evdev.c (ffffffff81938803)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-stripe.c (ffffffff81983d03)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/md/dm-ioctl.c (ffffffff819850a6)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:retrieve_deps
```
```
In drivers/md/dm-stats.c (ffffffff8198a0d2)
Location: include/linux/overflow.h:301
Inline: True
```
```
In drivers/firmware/efi/efi.c (ffffffff83018390)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c9e01)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff819cd0c5)
Location: include/linux/overflow.h:301
Inline: True
```
```
In drivers/interconnect/core.c (ffffffff819dbd04)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/interconnect/core.c:path_find
```
```
In net/core/flow_offload.c (ffffffff81a39188)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_rule_alloc
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/overflow.h:301
Inline: True
```
```
In net/netlink/policy.c (ffffffff81a86c83)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - net/netlink/policy.c:add_policy
```
```
In net/ipv4/tcp_input.c (ffffffff81abafeb)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/fib_semantics.c (ffffffff81afbfc1)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/nexthop.c (ffffffff81b0aeb3)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
```
```
In net/ipv6/exthdrs.c (ffffffff81b7b6a2)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/packet/af_packet.c (ffffffff81b9aabc)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
```
```
In net/xdp/xsk_queue.c (0)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xskq_create
  - net/xdp/xsk_queue.c:xskq_create
```
```
In net/xdp/xskmap.c (ffffffff81bb8812)
Location: include/linux/overflow.h:301
Inline: True
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81bb9945)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
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
In arch/x86/events/intel/uncore.c (ffffffff831bf2d2)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_type_init
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff831cc04c)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
```
```
In arch/x86/kernel/crash.c (ffffffff81079872)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_load_segments
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff831e35f0)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
```
```
In kernel/workqueue.c (ffffffff810c7d35)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - kernel/workqueue.c:apply_wqattrs_prepare
```
```
In kernel/groups.c (ffffffff810d7af4)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
```
```
In kernel/irq/devres.c (ffffffff811242a9)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
```
In kernel/dma/swiotlb.c (ffffffff8113b7ab)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_exit
```
```
In kernel/module.c (ffffffff8115f1d4)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - kernel/module.c:add_notes_attrs
  - kernel/module.c:add_sect_attrs
```
```
In kernel/cgroup/cgroup.c (ffffffff811720b1)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
```
```
In kernel/audit_tree.c (ffffffff81190ab9)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/tracepoint.c (ffffffff811a9714)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
```
```
In kernel/watch_queue.c (ffffffff8125badd)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_filter
```
```
In mm/percpu.c (ffffffff831f04bf)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/swapfile.c (ffffffff812cd975)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_swap_info
```
```
In mm/memcontrol.c (ffffffff81308d83)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
```
```
In fs/select.c (ffffffff81340e23)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/io_uring.c (ffffffff81399cdb)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/crypto/inline_crypt.c (ffffffff813ae786)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
```
```
In fs/iomap/buffered-io.c (ffffffff813c3d1a)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In ipc/sem.c (ffffffff814ae2f1)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - ipc/sem.c:newary
```
```
In security/landlock/ruleset.c (ffffffff81538277)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:create_rule
```
```
In security/integrity/ima/ima_api.c (ffffffff8153d4c9)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
```
```
In security/integrity/ima/ima_policy.c (ffffffff8153e133)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_alloc_rule_opt_list
```
```
In security/integrity/ima/ima_template.c (ffffffff81540065)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_template_data
```
```
In block/bio.c (ffffffff81563ad7)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - block/bio.c:bio_kmalloc
```
```
In block/blk-map.c (ffffffff8156e06c)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - block/blk-map.c:bio_alloc_map_data
```
```
In block/blk-iocost.c (ffffffff8159324a)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_alloc
```
```
In block/bio-integrity.c (ffffffff8159a38c)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_alloc
```
```
In lib/rhashtable.c (ffffffff815b5898)
Location: include/linux/overflow.h:301
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff8161be1f)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8161e638)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_create
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8166af86)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:remove_conflicting_pci_framebuffers
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: include/linux/overflow.h:301
Inline: True
```
```
In drivers/video/fbdev/efifb.c (0)
Location: include/linux/overflow.h:301
Inline: True
```
```
In drivers/video/fbdev/simplefb.c (0)
Location: include/linux/overflow.h:301
Inline: True
```
```
In drivers/reset/core.c (0)
Location: include/linux/overflow.h:301
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff8176794e)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/char/virtio_console.c (ffffffff8177239d)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:alloc_buf
```
```
In drivers/char/hpet.c (ffffffff817763dd)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
```
```
In drivers/char/tpm/eventlog/tpm2.c (ffffffff817826cc)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
```
```
In drivers/iommu/intel/dmar.c (ffffffff8178da5e)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/iommu/iommu.c (ffffffff8179c94f)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_fwspec_add_ids
```
```
In drivers/block/xen-blkfront.c (ffffffff817e514a)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:negotiate_mq
```
```
In drivers/nvdimm/region_devs.c (ffffffff81805981)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8181c185)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_list_alloc
```
```
In drivers/spi/spi.c (ffffffff8186aed5)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81890039)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_get_info
```
```
In drivers/usb/core/urb.c (ffffffff818afa55)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_alloc_urb
```
```
In drivers/usb/core/config.c (ffffffff818b6039)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818cce63)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/xhci.c (ffffffff818f5b0b)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/input/input-mt.c (ffffffff81917715)
Location: include/linux/overflow.h:301
Inline: True
```
```
In drivers/input/evdev.c (ffffffff8191c072)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-stripe.c (ffffffff819680f3)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/md/dm-ioctl.c (ffffffff8196af8e)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
```
```
In drivers/md/dm-stats.c (ffffffff8196e6a2)
Location: include/linux/overflow.h:301
Inline: True
```
```
In drivers/firmware/efi/efi.c (ffffffff83223268)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819aee11)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff819b22d9)
Location: include/linux/overflow.h:301
Inline: True
```
```
In drivers/interconnect/core.c (ffffffff819c1fb4)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - drivers/interconnect/core.c:path_find
```
```
In net/core/flow_offload.c (ffffffff81a20438)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_rule_alloc
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/overflow.h:301
Inline: True
```
```
In net/netlink/policy.c (ffffffff81a6fd64)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - net/netlink/policy.c:add_policy
```
```
In net/ipv4/tcp_input.c (ffffffff81aa5fab)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae779c)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/nexthop.c (ffffffff81af6554)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:nh_notifier_res_table_info_init
  - net/ipv4/nexthop.c:nh_notifier_mpath_info_init
```
```
In net/ipv6/exthdrs.c (ffffffff81b6a165)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/packet/af_packet.c (ffffffff81b899eb)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
```
```
In net/xdp/xsk_queue.c (0)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xskq_create
  - net/xdp/xsk_queue.c:xskq_create
```
```
In net/xdp/xskmap.c (ffffffff81ba7a42)
Location: include/linux/overflow.h:301
Inline: True
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ba8925)
Location: include/linux/overflow.h:301
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
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
In arch/x86/events/intel/uncore.c (ffffffff8329f742)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_type_init
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff832ad8b0)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
```
```
In arch/x86/kernel/crash.c (ffffffff810878d2)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_load_segments
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff832c7027)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
```
```
In kernel/workqueue.c (ffffffff810daac5)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - kernel/workqueue.c:apply_wqattrs_prepare
```
```
In kernel/groups.c (ffffffff810eb3a4)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
```
```
In kernel/irq/devres.c (ffffffff811448a9)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
```
In kernel/irq/generic-chip.c (ffffffff81144e9a)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips
  - kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips
  - kernel/irq/generic-chip.c:irq_alloc_generic_chip
```
```
In kernel/irq/irqdomain.c (ffffffff81146124)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/module.c (ffffffff81184534)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - kernel/module.c:add_notes_attrs
  - kernel/module.c:add_sect_attrs
```
```
In kernel/cgroup/cgroup.c (ffffffff81198ba1)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
```
```
In kernel/audit_tree.c (ffffffff811b9999)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/tracepoint.c (ffffffff811d3304)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
```
```
In kernel/trace/trace.c (0)
Location: include/linux/overflow.h:169
Inline: True
```
```
In kernel/trace/trace_eprobe.c (ffffffff8120ab94)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
```
```
In kernel/trace/trace_kprobe.c (ffffffff8121da74)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff81225ad0)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:alloc_trace_uprobe
```
```
In kernel/watch_queue.c (ffffffff8129798a)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_filter
```
```
In mm/percpu.c (ffffffff832d5dd4)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/swapfile.c (ffffffff81312d15)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_swap_info
```
```
In mm/memcontrol.c (ffffffff81354fa3)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
```
```
In fs/select.c (ffffffff8138e7e3)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/io_uring.c (ffffffff813e8db8)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/io-wq.c (ffffffff813f2b7e)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_create
```
```
In fs/crypto/inline_crypt.c (ffffffff813fe326)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
```
```
In fs/iomap/buffered-io.c (ffffffff81412fba)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In ipc/sem.c (ffffffff81506781)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - ipc/sem.c:newary
```
```
In security/landlock/ruleset.c (ffffffff8159693d)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:create_rule
```
```
In security/integrity/ima/ima_api.c (ffffffff8159c349)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
```
```
In security/integrity/ima/ima_policy.c (ffffffff8159d243)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_alloc_rule_opt_list
```
```
In security/integrity/ima/ima_template.c (ffffffff8159f855)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_template_data
```
```
In block/bio.c (ffffffff815c742b)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - block/bio.c:bio_kmalloc
```
```
In block/blk-map.c (ffffffff815d252c)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - block/blk-map.c:bio_alloc_map_data
```
```
In block/blk-iocost.c (ffffffff815fa4fa)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_alloc
```
```
In block/bio-integrity.c (ffffffff816024ec)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_alloc
```
```
In lib/rhashtable.c (ffffffff8161bd28)
Location: include/linux/overflow.h:169
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff8168b35c)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8168dfe5)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_create
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff816ded42)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:remove_conflicting_pci_framebuffers
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: include/linux/overflow.h:169
Inline: True
```
```
In drivers/video/fbdev/efifb.c (0)
Location: include/linux/overflow.h:169
Inline: True
```
```
In drivers/acpi/prmt.c (ffffffff832f33e2)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - drivers/acpi/prmt.c:acpi_parse_prmt
  - drivers/acpi/prmt.c:acpi_parse_prmt
```
```
In drivers/reset/core.c (0)
Location: include/linux/overflow.h:169
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff817ec360)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/char/virtio_console.c (ffffffff817f846d)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:alloc_buf
```
```
In drivers/char/hpet.c (ffffffff817fc16d)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
```
```
In drivers/char/tpm/eventlog/tpm2.c (ffffffff8180908c)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_next
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_bios_measurements_start
```
```
In drivers/iommu/intel/dmar.c (ffffffff818152de)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/iommu/iommu.c (ffffffff8182565f)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_fwspec_add_ids
```
```
In drivers/block/xen-blkfront.c (ffffffff8187185a)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:negotiate_mq
```
```
In drivers/nvdimm/region_devs.c (ffffffff81890a31)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/dma-buf/dma-resv.c (ffffffff818a6615)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_list_alloc
```
```
In drivers/spi/spi.c (ffffffff818fa075)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81923c23)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_get_info
```
```
In drivers/usb/core/urb.c (ffffffff81944ba5)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_alloc_urb
```
```
In drivers/usb/core/config.c (ffffffff8194b6ac)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81966c3b)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/xhci.c (ffffffff81993aa7)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/input/input-mt.c (ffffffff819b9985)
Location: include/linux/overflow.h:169
Inline: True
```
```
In drivers/input/evdev.c (ffffffff819be762)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-stripe.c (ffffffff81a10503)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/md/dm-ioctl.c (ffffffff81a1344e)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
```
```
In drivers/md/dm-stats.c (ffffffff81a16f0e)
Location: include/linux/overflow.h:169
Inline: True
```
```
In drivers/firmware/efi/efi.c (ffffffff8330cfe9)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81a5d411)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff81a60a69)
Location: include/linux/overflow.h:169
Inline: True
```
```
In drivers/interconnect/core.c (ffffffff81a71834)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - drivers/interconnect/core.c:path_find
```
```
In net/core/flow_offload.c (ffffffff81ad46a8)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_rule_alloc
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/overflow.h:169
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffffffff81b0ac6d)
Location: include/linux/overflow.h:169
Inline: True
```
```
In net/netlink/policy.c (ffffffff81b294b4)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - net/netlink/policy.c:add_policy
```
```
In net/ipv4/tcp_input.c (ffffffff81b6238b)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/igmp.c (ffffffff81ba1307)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba7607)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/nexthop.c (ffffffff81bb802e)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:nh_notifier_info_init
  - net/ipv4/nexthop.c:nh_notifier_mpath_info_init
```
```
In net/ipv6/mcast.c (ffffffff81c293d9)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
```
```
In net/ipv6/exthdrs.c (ffffffff81c31fc5)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/packet/af_packet.c (ffffffff81c55afb)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
```
```
In net/xdp/xsk_queue.c (0)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xskq_create
  - net/xdp/xsk_queue.c:xskq_create
```
```
In net/xdp/xskmap.c (ffffffff81c756d2)
Location: include/linux/overflow.h:169
Inline: True
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81c76675)
Location: include/linux/overflow.h:169
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In virt/kvm/kvm_main.c (ffff8000100bf8dc)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:kvm_io_bus_unregister_dev
  - virt/kvm/kvm_main.c:kvm_io_bus_register_dev
```
```
In virt/kvm/irqchip.c (0)
Location: include/linux/overflow.h:291
Inline: True
```
```
In kernel/workqueue.c (ffff800010121720)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/workqueue.c:apply_wqattrs_prepare
```
```
In kernel/irq/devres.c (ffff8000101809c4)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
```
In kernel/module.c (ffff8000101c2014)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
```
```
In kernel/cgroup/cgroup.c (ffff8000101d4ce8)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
```
```
In kernel/tracepoint.c (ffff80001020e6dc)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
```
```
In mm/percpu.c (ffff800011453e28)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_alloc_info
```
```
In mm/swapfile.c (ffff8000103276f4)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/memcontrol.c (ffff800010362d50)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
```
```
In fs/select.c (ffff8000103a30ec)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/io_uring.c (0)
Location: include/linux/overflow.h:291
Inline: True
```
```
In ipc/sem.c (ffff8000105227f0)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - ipc/sem.c:newary
```
```
In security/integrity/ima/ima_api.c (ffff8000105b0584)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
```
```
In security/integrity/ima/ima_template.c (ffff8000105b2f44)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/bio.c (ffff8000105dcbd8)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
```
```
In block/genhd.c (ffff8000105fbbbc)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - block/genhd.c:disk_expand_part_tbl
```
```
In block/bio-integrity.c (ffff80001061d09c)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_alloc
```
```
In lib/rhashtable.c (ffff800010635db0)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/irqchip/qcom-irq-combiner.c (ffff8000114762c8)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/irqchip/qcom-irq-combiner.c:combiner_probe
```
```
In drivers/gpio/gpiolib.c (ffff8000106c4e8c)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
```
In drivers/clk/bcm/clk-iproc-pll.c (ffff8000107cc6dc)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/clk/bcm/clk-iproc-pll.c:iproc_pll_clk_setup
```
```
In drivers/clk/bcm/clk-iproc-asiu.c (ffff800011484ce8)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/clk/bcm/clk-iproc-asiu.c:iproc_asiu_setup
```
```
In drivers/clk/bcm/clk-bcm2835.c (0)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/clk/bcm/clk-bcm2835-aux.c (0)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/clk/imx/clk-imx8qxp.c (0)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/clk/imx/clk-imx8qxp-lpcg.c (ffff8000107e1594)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/clk/imx/clk-imx8qxp-lpcg.c:imx8qxp_lpcg_clk_probe
```
```
In drivers/clk/mvebu/armada-37xx-tbg.c (0)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/clk/mvebu/armada-37xx-periph.c (ffff8000107e910c)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/clk/mvebu/armada-37xx-periph.c:armada_3700_periph_clock_probe
```
```
In drivers/clk/renesas/renesas-cpg-mssr.c (ffff8000114888fc)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_common_init
```
```
In drivers/clk/renesas/clk-div6.c (ffff800011488e58)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/clk/renesas/clk-div6.c:cpg_div6_register
```
```
In drivers/clk/zynqmp/clkc.c (ffff8000107fbea4)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/clk/zynqmp/clkc.c:zynqmp_clock_probe
```
```
In drivers/dma/bcm2835-dma.c (ffff800010803ee4)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_create_cb_chain
```
```
In drivers/soc/actions/owl-sps.c (ffff80001080da58)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/soc/actions/owl-sps.c:owl_sps_probe
```
```
In drivers/soc/rockchip/pm_domains.c (ffff80001081f398)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_domain_probe
```
```
In drivers/reset/core.c (ffff80001084ccbc)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/reset/core.c:of_reset_control_array_get
```
```
In drivers/tty/serial/max310x.c (ffff800010899538)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/char/virtio_console.c (ffff8000108b4570)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:alloc_buf
```
```
In drivers/iommu/qcom_iommu.c (0)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/misc/vexpress-syscfg.c (ffff80001092bbc0)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/misc/vexpress-syscfg.c:vexpress_syscfg_regmap_init
```
```
In drivers/nvdimm/region_devs.c (ffff800010956ba4)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/spi/spi.c (ffff8000109c3884)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
```
In drivers/usb/core/urb.c (ffff800010a1ffcc)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_alloc_urb
```
```
In drivers/usb/core/config.c (ffff800010a27ed4)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/dwc2/hcd.c (ffff800010a45ea0)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/xhci.c (ffff800010a75344)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/input/input-mt.c (ffff800010a9a2fc)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/input/evdev.c (ffff800010a9e288)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/rtc/rtc-sun6i.c (0)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/md/dm-stats.c (ffff800010b0d10c)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (ffff800010b83b30)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_elf_loader.c:find_table
```
```
In net/core/flow_offload.c (ffff800010c07e60)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_rule_alloc
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/overflow.h:291
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffff800010cb8040)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/xdp/xsk_queue.c (0)
Location: include/linux/overflow.h:291
Inline: True
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
In kernel/workqueue.c (0)
Location: include/linux/overflow.h:291
Inline: True
```
```
In kernel/irq/devres.c (c03d07c4)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
```
In kernel/module.c (c0409af4)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
```
```
In kernel/cgroup/cgroup.c (c041782c)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
```
```
In kernel/tracepoint.c (c044d228)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
```
```
In mm/percpu.c (c152eb80)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_alloc_info
```
```
In mm/swapfile.c (0)
Location: include/linux/overflow.h:291
Inline: True
```
```
In mm/memcontrol.c (c055547c)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
```
```
In fs/select.c (c0585908)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/io_uring.c (c05d64d8)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:ring_pages
```
```
In ipc/sem.c (c06dd408)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - ipc/sem.c:newary
```
```
In security/integrity/ima/ima_api.c (c075fc9c)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
```
```
In security/integrity/ima/ima_template.c (c0762568)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/bio.c (c078a060)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
```
```
In block/genhd.c (c07a6c6c)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - block/genhd.c:disk_expand_part_tbl
```
```
In block/bio-integrity.c (c07c4f70)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_alloc
```
```
In lib/rhashtable.c (c07dbca8)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - lib/rhashtable.c:bucket_table_alloc
```
```
In drivers/pinctrl/uniphier/pinctrl-uniphier-core.c (c0857adc)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/gpio/gpiolib.c (c0863220)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
```
In drivers/clk/clk-aspeed.c (0)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/clk/clk-ast2600.c (0)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/clk/clk-milbeaut.c (0)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/clk/clk-npcm7xx.c (0)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/clk/berlin/bg2.c (0)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/clk/berlin/bg2q.c (0)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/clk/imx/clk-imx6q.c (0)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/clk/imx/clk-imx6sl.c (0)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/clk/imx/clk-imx6sll.c (0)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/clk/imx/clk-imx6sx.c (0)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/clk/imx/clk-imx6ul.c (0)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/clk/imx/clk-imx7d.c (0)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/clk/imx/clk-imx7ulp.c (0)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/clk/renesas/renesas-cpg-mssr.c (c1581760)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_common_init
```
```
In drivers/clk/renesas/clk-mstp.c (0)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/clk/renesas/clk-div6.c (c1582078)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/clk/renesas/clk-div6.c:cpg_div6_register
```
```
In drivers/clk/samsung/clk-exynos-clkout.c (0)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/dma/tegra20-apb-dma.c (c092a508)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_probe
```
```
In drivers/dma/ti/edma.c (c0930374)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/dma/ti/edma.c:edma_prep_dma_cyclic
  - drivers/dma/ti/edma.c:edma_prep_slave_sg
```
```
In drivers/dma/ti/omap-dma.c (c0931bb4)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/dma/ti/omap-dma.c:omap_dma_prep_slave_sg
```
```
In drivers/soc/actions/owl-sps.c (c09339d0)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/soc/actions/owl-sps.c:owl_sps_probe
```
```
In drivers/soc/rockchip/pm_domains.c (c093999c)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_domain_probe
```
```
In drivers/reset/core.c (c0959148)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/reset/core.c:of_reset_control_array_get
```
```
In drivers/tty/serial/max310x.c (c099386c)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/char/virtio_console.c (c09af204)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:alloc_buf
```
```
In drivers/iommu/qcom_iommu.c (0)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/misc/vexpress-syscfg.c (0)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/mfd/sm501.c (0)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/spi/spi.c (c0ab16f4)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
```
In drivers/usb/core/urb.c (c0af7138)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_alloc_urb
```
```
In drivers/usb/core/config.c (c0afdf3c)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/dwc2/hcd.c (c0b185fc)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/xhci.c (c0b48c18)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/input/input-mt.c (c0b7bf30)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/input/evdev.c (c0b7f258)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-stats.c (c0beb248)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (c0c66d8c)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_elf_loader.c:find_table
```
```
In sound/core/control.c (c0c863ec)
Location: include/linux/overflow.h:291
Inline: True
```
```
In sound/core/vmaster.c (c0c8ac50)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - sound/core/vmaster.c:_snd_ctl_add_slave
```
```
In sound/soc/soc-dapm.c (c0cab59c)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - sound/soc/soc-dapm.c:snd_soc_dapm_dai_get_connected_widgets
  - sound/soc/soc-dapm.c:dapm_create_or_share_kcontrol
```
```
In net/core/flow_offload.c (c0d20cd4)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_rule_alloc
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/overflow.h:291
Inline: True
```
```
In net/ipv4/fib_semantics.c (c0dc3424)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/xdp/xsk_queue.c (c0e7bc98)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
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
In kernel/workqueue.c (c00000000016adb0)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/workqueue.c:apply_wqattrs_prepare
```
```
In kernel/irq/devres.c (c0000000001db5f4)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
```
In kernel/module.c (c0000000002291b4)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
```
```
In kernel/cgroup/cgroup.c (c000000000243fe8)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
```
```
In kernel/tracepoint.c (c00000000028c954)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/tracepoint.c:allocate_probes
```
```
In mm/percpu.c (c00000000137c5a4)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_alloc_info
```
```
In mm/swapfile.c (c0000000003fe3b0)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/memcontrol.c (c00000000044ed6c)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
```
```
In fs/select.c (c00000000049cda0)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/io_uring.c (c00000000050f9ac)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:ring_pages
```
```
In ipc/sem.c (c00000000066be90)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - ipc/sem.c:newary
```
```
In security/integrity/ima/ima_api.c (c0000000007301ec)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
```
```
In security/integrity/ima/ima_template.c (c000000000735598)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/bio.c (c00000000076df20)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
```
```
In block/genhd.c (c000000000794ebc)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - block/genhd.c:disk_expand_part_tbl
```
```
In block/bio-integrity.c (c0000000007bc100)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_alloc
```
```
In lib/rhashtable.c (c0000000007dc320)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/gpio/gpiolib.c (c0000000008419d0)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
```
In drivers/reset/core.c (c0000000008ebd10)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/reset/core.c:of_reset_control_array_get
```
```
In drivers/tty/serial/max310x.c (c00000000093c024)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/char/virtio_console.c (c00000000094e61c)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:alloc_buf
```
```
In drivers/nvdimm/region_devs.c (c000000000a048f0)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/spi/spi.c (c000000000a88f7c)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
```
In drivers/usb/core/urb.c (c000000000ada10c)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_alloc_urb
```
```
In drivers/usb/core/config.c (c000000000ae3cd0)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/dwc2/hcd.c (c000000000b09fa0)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/xhci.c (c000000000b4b5d4)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/input/input-mt.c (c000000000b7a33c)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/input/evdev.c (c000000000b7e964)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-stats.c (c000000000bff9b8)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (c000000000c612dc)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_elf_loader.c:find_table
```
```
In net/core/flow_offload.c (c000000000cf2220)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_rule_alloc
```
```
In net/core/drop_monitor.c (c000000000d0bab8)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_reset_per_cpu_data
```
```
In net/ipv4/fib_semantics.c (c000000000dd08b4)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/xdp/xsk_queue.c (c000000000ec1640)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
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
In kernel/workqueue.c (0)
Location: include/linux/overflow.h:291
Inline: True
```
```
In kernel/irq/devres.c (ffffffe00011896e)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
```
In kernel/module.c (ffffffe000143d06)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
```
```
In kernel/cgroup/cgroup.c (ffffffe00014e098)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
```
```
In kernel/tracepoint.c (ffffffe00016f458)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
```
```
In mm/percpu.c (ffffffe0000130ba)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_alloc_info
```
```
In mm/swapfile.c (0)
Location: include/linux/overflow.h:291
Inline: True
```
```
In mm/memcontrol.c (ffffffe00024259e)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
```
```
In fs/select.c (ffffffe00026b0fc)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/io_uring.c (ffffffe0002b086a)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:ring_pages
```
```
In ipc/sem.c (ffffffe000387d7a)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - ipc/sem.c:newary
```
```
In security/integrity/ima/ima_api.c (ffffffe0003f8214)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
```
```
In security/integrity/ima/ima_template.c (ffffffe0003fa5f8)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/bio.c (ffffffe00041fe8e)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
```
```
In block/genhd.c (ffffffe000437c5c)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - block/genhd.c:disk_expand_part_tbl
```
```
In block/bio-integrity.c (ffffffe00044ff56)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_alloc
```
```
In lib/rhashtable.c (ffffffe000463b3e)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffe0004a94d8)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
```
In drivers/reset/core.c (ffffffe00052c520)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/reset/core.c:of_reset_control_array_get
```
```
In drivers/tty/serial/max310x.c (ffffffe00055af52)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/char/virtio_console.c (ffffffe000565408)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/nvdimm/region_devs.c (ffffffe0005c5d34)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/spi/spi.c (ffffffe000616bec)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
```
In drivers/usb/core/urb.c (ffffffe0006439f4)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_alloc_urb
```
```
In drivers/usb/core/config.c (ffffffe000649b26)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/dwc2/hcd.c (ffffffe0006628d2)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/xhci.c (ffffffe00068d2c0)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/input/input-mt.c (ffffffe0006aac5a)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/input/evdev.c (ffffffe0006adf32)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-stats.c (ffffffe0006fa7de)
Location: include/linux/overflow.h:291
Inline: True
```
```
In net/core/flow_offload.c (ffffffe000785f0a)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_rule_alloc
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/overflow.h:291
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffe00080f076)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/xdp/xsk_queue.c (0)
Location: include/linux/overflow.h:291
Inline: True
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
In arch/x86/events/intel/uncore.c (ffffffff82890e9a)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_types_init
```
```
In arch/x86/kernel/crash.c (ffffffff81070967)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_load_segments
```
```
In kernel/workqueue.c (ffffffff810bdce5)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/workqueue.c:apply_wqattrs_prepare
```
```
In kernel/irq/devres.c (ffffffff811148c5)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
```
In kernel/module.c (ffffffff8114bda6)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
```
```
In kernel/cgroup/cgroup.c (ffffffff8115bb1a)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
```
```
In kernel/tracepoint.c (ffffffff8118e8b0)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/tracepoint.c:allocate_probes
```
```
In mm/percpu.c (ffffffff828c3fcf)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_alloc_info
```
```
In mm/swapfile.c (ffffffff812845b6)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/memcontrol.c (ffffffff812b91a7)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
```
```
In fs/select.c (ffffffff812ee509)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/io_uring.c (ffffffff8133d296)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:ring_pages
```
```
In ipc/sem.c (ffffffff81432f26)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - ipc/sem.c:newary
```
```
In security/integrity/ima/ima_api.c (ffffffff814b08e8)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
```
```
In security/integrity/ima/ima_template.c (ffffffff814b3060)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/bio.c (ffffffff814d85e2)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
```
```
In block/genhd.c (ffffffff814f263f)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - block/genhd.c:disk_expand_part_tbl
```
```
In block/bio-integrity.c (ffffffff8150e766)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_alloc
```
```
In lib/rhashtable.c (ffffffff81523240)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff8156470e)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
```
In drivers/reset/core.c (0)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff8167b675)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/char/virtio_console.c (ffffffff81687d6d)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:alloc_buf
```
```
In drivers/char/hpet.c (ffffffff81689fad)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
```
```
In drivers/iommu/dmar.c (ffffffff816ac612)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/nvdimm/region_devs.c (ffffffff8170a001)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/spi/spi.c (ffffffff81778e75)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
```
In drivers/usb/core/urb.c (ffffffff817a8755)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_alloc_urb
```
```
In drivers/usb/core/config.c (ffffffff817aef5e)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817c5875)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/xhci.c (ffffffff817ef6e5)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/input/input-mt.c (ffffffff8180f2e2)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/input/evdev.c (ffffffff8181239f)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-stats.c (ffffffff8185b15a)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff81898a3b)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_elf_loader.c:find_table
```
```
In net/core/flow_offload.c (ffffffff819038d5)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_rule_alloc
```
```
In net/core/drop_monitor.c (ffffffff819150f5)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_reset_per_cpu_data
```
```
In net/ipv4/fib_semantics.c (ffffffff8199f808)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/xdp/xsk_queue.c (ffffffff81a4c16d)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
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
In arch/x86/events/intel/uncore.c (ffffffff8288ed7f)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_types_init
```
```
In arch/x86/kernel/crash.c (ffffffff81060977)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_load_segments
```
```
In kernel/workqueue.c (ffffffff810ac515)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/workqueue.c:apply_wqattrs_prepare
```
```
In kernel/irq/devres.c (ffffffff811055d5)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
```
In kernel/module.c (ffffffff8113f056)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
```
```
In kernel/cgroup/cgroup.c (ffffffff8114ee0a)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
```
```
In kernel/tracepoint.c (ffffffff81181a30)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/tracepoint.c:allocate_probes
```
```
In mm/percpu.c (ffffffff828bc6f4)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_alloc_info
```
```
In mm/swapfile.c (ffffffff81276426)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/memcontrol.c (ffffffff812aa437)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
```
```
In fs/select.c (ffffffff812df139)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/io_uring.c (ffffffff8132df56)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:ring_pages
```
```
In ipc/sem.c (ffffffff814239a6)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - ipc/sem.c:newary
```
```
In security/integrity/ima/ima_api.c (ffffffff814a1308)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
```
```
In security/integrity/ima/ima_template.c (ffffffff814a3a80)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/bio.c (ffffffff814c8f92)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
```
```
In block/genhd.c (ffffffff814e2b6f)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - block/genhd.c:disk_expand_part_tbl
```
```
In block/bio-integrity.c (ffffffff814feb96)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_alloc
```
```
In lib/rhashtable.c (ffffffff81513520)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff8155555e)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
```
In drivers/reset/core.c (0)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff8165a765)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/char/virtio_console.c (ffffffff816658f8)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/char/hpet.c (ffffffff816679cd)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
```
```
In drivers/iommu/dmar.c (ffffffff81689f72)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/nvdimm/region_devs.c (ffffffff816dda81)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/spi/spi.c (ffffffff81758c25)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
```
In drivers/usb/core/urb.c (ffffffff8179a165)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_alloc_urb
```
```
In drivers/usb/core/config.c (ffffffff817a095e)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/host/xhci.c (ffffffff817b47f5)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/input/input-mt.c (ffffffff817d6a32)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/input/evdev.c (ffffffff817d9adf)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-stats.c (ffffffff8182272a)
Location: include/linux/overflow.h:291
Inline: True
```
```
In net/core/flow_offload.c (ffffffff818bd705)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_rule_alloc
```
```
In net/core/drop_monitor.c (ffffffff818ceea5)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_reset_per_cpu_data
```
```
In net/ipv4/fib_semantics.c (ffffffff819592c8)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/xdp/xsk_queue.c (ffffffff81a08d5d)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
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
In arch/x86/events/intel/uncore.c (ffffffff828a3e9a)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_types_init
```
```
In arch/x86/kernel/crash.c (ffffffff81070967)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_load_segments
```
```
In kernel/workqueue.c (ffffffff810bd245)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/workqueue.c:apply_wqattrs_prepare
```
```
In kernel/irq/devres.c (ffffffff811127b5)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
```
In kernel/module.c (ffffffff81149c56)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
```
```
In kernel/cgroup/cgroup.c (ffffffff811598ea)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
```
```
In kernel/tracepoint.c (ffffffff8118c680)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/tracepoint.c:allocate_probes
```
```
In mm/percpu.c (ffffffff828d6d4f)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_alloc_info
```
```
In mm/swapfile.c (ffffffff812823c6)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/memcontrol.c (ffffffff812b6fb7)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
```
```
In fs/select.c (ffffffff812ec319)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/io_uring.c (ffffffff8133ad66)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:ring_pages
```
```
In ipc/sem.c (ffffffff8142f0c6)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - ipc/sem.c:newary
```
```
In security/integrity/ima/ima_api.c (ffffffff814ac978)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
```
```
In security/integrity/ima/ima_template.c (ffffffff814af0f0)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/bio.c (ffffffff814d4672)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
```
```
In block/genhd.c (ffffffff814ee6cf)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - block/genhd.c:disk_expand_part_tbl
```
```
In block/bio-integrity.c (ffffffff8150a7f6)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_alloc
```
```
In lib/rhashtable.c (ffffffff8151f2d0)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff8156327e)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
```
In drivers/reset/core.c (0)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff816a9a55)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/char/virtio_console.c (ffffffff816b60a8)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/char/hpet.c (ffffffff816b821d)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
```
```
In drivers/iommu/dmar.c (ffffffff816da7f2)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/nvdimm/region_devs.c (ffffffff81748dd1)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81772ed8)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
```
```
In drivers/spi/spi.c (ffffffff817a9215)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
```
In drivers/usb/core/urb.c (ffffffff817e51f5)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_alloc_urb
```
```
In drivers/usb/core/config.c (ffffffff817eb9fe)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81802315)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/xhci.c (ffffffff8182c1b5)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/input/input-mt.c (ffffffff8184e462)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/input/evdev.c (ffffffff8185151f)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-stats.c (ffffffff818aa78a)
Location: include/linux/overflow.h:291
Inline: True
```
```
In net/core/flow_offload.c (ffffffff81954905)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_rule_alloc
```
```
In net/core/drop_monitor.c (ffffffff81966125)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_reset_per_cpu_data
```
```
In net/ipv4/fib_semantics.c (ffffffff81a0a0a8)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/xdp/xsk_queue.c (ffffffff81ab801d)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
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
In arch/x86/events/intel/uncore.c (ffffffff828a3eae)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_types_init
```
```
In arch/x86/kernel/crash.c (ffffffff81072977)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_load_segments
```
```
In kernel/workqueue.c (ffffffff810c55c5)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/workqueue.c:apply_wqattrs_prepare
```
```
In kernel/irq/devres.c (ffffffff8111ddd5)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
```
In kernel/module.c (ffffffff81156916)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
```
```
In kernel/cgroup/cgroup.c (ffffffff8116695a)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
```
```
In kernel/tracepoint.c (ffffffff8119a010)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - kernel/tracepoint.c:allocate_probes
```
```
In mm/percpu.c (ffffffff828dc170)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_alloc_info
```
```
In mm/swapfile.c (ffffffff812920b6)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/memcontrol.c (ffffffff812c7897)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
```
```
In fs/select.c (ffffffff812fd319)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/io_uring.c (ffffffff8134df16)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:ring_pages
```
```
In ipc/sem.c (ffffffff81446236)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - ipc/sem.c:newary
```
```
In security/integrity/ima/ima_api.c (ffffffff814c53c8)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
```
```
In security/integrity/ima/ima_template.c (ffffffff814c7b70)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/bio.c (ffffffff814ed222)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
```
```
In block/genhd.c (ffffffff8150776f)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - block/genhd.c:disk_expand_part_tbl
```
```
In block/bio-integrity.c (ffffffff81523e96)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_alloc
```
```
In lib/rhashtable.c (ffffffff81538cf0)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff8157d19e)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
```
In drivers/reset/core.c (0)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff816c3eb5)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/char/virtio_console.c (ffffffff816d064d)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:alloc_buf
```
```
In drivers/char/hpet.c (ffffffff816d27ed)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
```
```
In drivers/iommu/dmar.c (ffffffff816f4da2)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/nvdimm/region_devs.c (ffffffff81764251)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/spi/spi.c (ffffffff817c30a5)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
```
In drivers/usb/core/urb.c (ffffffff817ff455)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_alloc_urb
```
```
In drivers/usb/core/config.c (ffffffff81805c3e)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8181c425)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/xhci.c (ffffffff8184619e)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/input/input-mt.c (ffffffff81869632)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/input/evdev.c (ffffffff8186c33f)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-stats.c (ffffffff818c63c4)
Location: include/linux/overflow.h:291
Inline: True
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff8190919b)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_elf_loader.c:find_table
```
```
In net/core/flow_offload.c (ffffffff819765b5)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_rule_alloc
```
```
In net/core/drop_monitor.c (ffffffff819883b5)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_reset_per_cpu_data
```
```
In net/ipv4/fib_semantics.c (ffffffff81a14888)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/xdp/xsk_queue.c (ffffffff81ac443d)
Location: include/linux/overflow.h:291
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
```
</details>
</li>
</ul>

## Differences
