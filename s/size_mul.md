# Function: <code>size_mul</code>

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
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8344e538)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_type_init
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff8345e770)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
```
```
In arch/x86/kernel/crash.c (ffffffff81097a72)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_load_segments
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff83479e3c)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
```
```
In kernel/workqueue.c (ffffffff810f4205)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - kernel/workqueue.c:apply_wqattrs_prepare
```
```
In kernel/groups.c (ffffffff811062d0)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
```
```
In kernel/power/swap.c (ffffffff81157e1d)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/irq/devres.c (ffffffff811687e9)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
```
In kernel/irq/generic-chip.c (ffffffff81169197)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips
  - kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips
  - kernel/irq/generic-chip.c:irq_alloc_generic_chip
```
```
In kernel/irq/irqdomain.c (ffffffff8116a3c7)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/dma/swiotlb.c (ffffffff81188b8b)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init_late
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_init_remap
```
```
In kernel/module/sysfs.c (ffffffff81192358)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - kernel/module/sysfs.c:add_notes_attrs
  - kernel/module/sysfs.c:add_sect_attrs
```
```
In kernel/kexec_file.c (ffffffff811be715)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_purgatory_setup_sechdrs
```
```
In kernel/cgroup/cgroup.c (ffffffff811c8d32)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
```
```
In kernel/audit.c (0)
Location: include/linux/overflow.h:131
Inline: True
```
```
In kernel/auditfilter.c (0)
Location: include/linux/overflow.h:131
Inline: True
```
```
In kernel/audit_tree.c (ffffffff811ecab9)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/tracepoint.c (ffffffff81207d7d)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
```
```
In kernel/trace/tracing_map.c (ffffffff8122cf30)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
```
```
In kernel/trace/trace_eprobe.c (ffffffff81246bcb)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
```
```
In kernel/trace/trace_kprobe.c (ffffffff8125d044)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff81265b10)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:alloc_trace_uprobe
```
```
In kernel/bpf/core.c (ffffffff8126c0b0)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - kernel/bpf/core.c:alloc_new_pack
```
```
In kernel/bpf/verifier.c (ffffffff81294780)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
```
In kernel/bpf/local_storage.c (0)
Location: include/linux/overflow.h:131
Inline: True
```
```
In kernel/bpf/reuseport_array.c (ffffffff812c6147)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
```
In kernel/watch_queue.c (ffffffff812edc52)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_filter
```
```
In mm/percpu.c (ffffffff8348a694)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/list_lru.c (ffffffff81334d55)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_init_list_lru_one
```
```
In mm/madvise.c (0)
Location: include/linux/overflow.h:131
Inline: True
```
```
In mm/swapfile.c (ffffffff8137d945)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_swap_info
```
```
In mm/memcontrol.c (ffffffff813cab15)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
```
```
In mm/hugetlb_cgroup.c (ffffffff813d7033)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/select.c (ffffffff8140fa83)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/aio.c (ffffffff814619f7)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - fs/aio.c:ioctx_add_table
```
```
In fs/crypto/inline_crypt.c (ffffffff81471e55)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
```
```
In fs/verity/enable.c (0)
Location: include/linux/overflow.h:131
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff81489117)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In ipc/sem.c (ffffffff81598552)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - ipc/sem.c:newary
```
```
In security/selinux/ss/sidtab.c (0)
Location: include/linux/overflow.h:131
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/overflow.h:131
Inline: True
```
```
In security/apparmor/lib.c (0)
Location: include/linux/overflow.h:131
Inline: True
```
```
In security/apparmor/label.c (ffffffff8162b9f5)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
```
```
In security/landlock/ruleset.c (ffffffff81638e46)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:inherit_ruleset
  - security/landlock/ruleset.c:create_rule
  - security/landlock/ruleset.c:create_rule
```
```
In security/integrity/ima/ima_api.c (ffffffff81641369)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
```
```
In security/integrity/ima/ima_policy.c (ffffffff816424cf)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_alloc_rule_opt_list
```
```
In security/integrity/ima/ima_template.c (ffffffff81644fe5)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_template_data
```
```
In block/bio.c (ffffffff816713ac)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - block/bio.c:bio_kmalloc
```
```
In block/blk-map.c (ffffffff8167e24c)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - block/blk-map.c:bio_alloc_map_data
```
```
In block/partitions/core.c (0)
Location: include/linux/overflow.h:131
Inline: True
```
```
In block/blk-ia-ranges.c (ffffffff8169fcab)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - block/blk-ia-ranges.c:disk_alloc_independent_access_ranges
```
```
In block/blk-iocost.c (ffffffff816ac888)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_alloc
```
```
In block/bio-integrity.c (ffffffff816b5159)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_alloc
```
```
In io_uring/io_uring.c (ffffffff816ce226)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_register_pbuf_ring
  - io_uring/io_uring.c:io_register_restrictions
  - io_uring/io_uring.c:io_allocate_scq_urings
  - io_uring/io_uring.c:io_allocate_scq_urings
  - io_uring/io_uring.c:io_allocate_scq_urings
  - io_uring/io_uring.c:io_allocate_scq_urings
  - io_uring/io_uring.c:io_sqe_buffer_register
```
```
In io_uring/io-wq.c (ffffffff816db6da)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_create
```
```
In lib/rhashtable.c (ffffffff816e9717)
Location: include/linux/overflow.h:131
Inline: True
```
```
In lib/assoc_array.c (ffffffff816f89fd)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
```
```
In lib/stackdepot.c (ffffffff8176f6f9)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - lib/stackdepot.c:__stack_depot_save
  - lib/stackdepot.c:depot_alloc_stack
```
```
In drivers/gpio/gpiolib.c (ffffffff817a86f2)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff817acb40)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_create
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff81808da2)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:remove_conflicting_pci_framebuffers
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff8181155a)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: include/linux/overflow.h:131
Inline: True
```
```
In drivers/video/fbdev/efifb.c (0)
Location: include/linux/overflow.h:131
Inline: True
```
```
In drivers/acpi/prmt.c (ffffffff834ab51e)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - drivers/acpi/prmt.c:acpi_parse_prmt
  - drivers/acpi/prmt.c:acpi_parse_prmt
```
```
In drivers/reset/core.c (0)
Location: include/linux/overflow.h:131
Inline: True
```
```
In drivers/tty/vt/consolemap.c (ffffffff8190a506)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_set_unimap
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8192926b)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
```
```
In drivers/tty/serial/max310x.c (ffffffff8192aee8)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/char/virtio_console.c (ffffffff81936d8e)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:alloc_buf
```
```
In drivers/char/hpet.c (ffffffff8193accd)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
```
```
In drivers/char/tpm/eventlog/tpm2.c (0)
Location: include/linux/overflow.h:131
Inline: True
```
```
In drivers/iommu/intel/dmar.c (ffffffff8195653e)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/iommu/iommu.c (ffffffff819654cf)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_fwspec_add_ids
```
```
In drivers/block/xen-blkfront.c (ffffffff819b98ba)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:negotiate_mq
```
```
In drivers/nvdimm/region_devs.c (ffffffff819da732)
Location: include/linux/overflow.h:131
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff819f0625)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_list_alloc
```
```
In drivers/ata/libata-core.c (ffffffff81a26c75)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_config_cpr
```
```
In drivers/spi/spi.c (ffffffff81a4ab6f)
Location: include/linux/overflow.h:131
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a7a372)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_iova_build_caps
```
```
In drivers/usb/core/urb.c (ffffffff81a9c695)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_alloc_urb
```
```
In drivers/usb/core/config.c (ffffffff81ee1a28)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81ac0de9)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81ad22d4)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:itd_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81adc19d)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
```
In drivers/usb/host/xhci.c (ffffffff81af059d)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/input/input-mt.c (ffffffff81b195de)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_init_slots
```
```
In drivers/input/evdev.c (ffffffff81b1d5a5)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-stripe.c (ffffffff81b78760)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/md/dm-ioctl.c (ffffffff81b7bcf5)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
```
```
In drivers/md/dm-stats.c (ffffffff81b7fbd4)
Location: include/linux/overflow.h:131
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff834c3a99)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
```
In drivers/firmware/efi/efi.c (ffffffff834c6aac)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81bcd549)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff81bd0ff8)
Location: include/linux/overflow.h:131
Inline: True
```
```
In drivers/devfreq/devfreq.c (ffffffff81bd2f6d)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:trans_stat_store
  - drivers/devfreq/devfreq.c:trans_stat_store
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/interconnect/core.c (ffffffff81be329c)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - drivers/interconnect/core.c:path_find
```
```
In drivers/hte/hte.c (ffffffff81be4ce9)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - drivers/hte/hte.c:hte_register_chip
```
```
In net/core/flow_offload.c (ffffffff81c53258)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - net/core/flow_offload.c:offload_action_alloc
  - net/core/flow_offload.c:flow_rule_alloc
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/overflow.h:131
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffffffff81c912cb)
Location: include/linux/overflow.h:131
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81c9994b)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/netlink/policy.c (ffffffff81cb262a)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - net/netlink/policy.c:add_policy
  - net/netlink/policy.c:add_policy
```
```
In net/ethtool/ioctl.c (ffffffff81cbc1ac)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ethtool/ioctl.c:ethtool_get_strings
  - net/ethtool/ioctl.c:ethtool_get_strings
  - net/ethtool/ioctl.c:ethtool_self_test
  - net/ethtool/ioctl.c:ethtool_copy_validate_indir
  - net/ethtool/ioctl.c:ethtool_get_sset_info
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/overflow.h:131
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81d339dd)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
```
```
In net/ipv4/fib_semantics.c (ffffffff81d39f23)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/nexthop.c (ffffffff81d4be3c)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:nh_notifier_info_init
  - net/ipv4/nexthop.c:nh_notifier_mpath_info_init
```
```
In net/ipv6/mcast.c (ffffffff81dc67e7)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
```
```
In net/ipv6/exthdrs.c (ffffffff81dcf7c4)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/packet/af_packet.c (ffffffff81df1b34)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
```
```
In net/switchdev/switchdev.c (ffffffff81e0ccb5)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
```
```
In net/xdp/xsk_queue.c (0)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xskq_create
```
```
In net/xdp/xskmap.c (ffffffff81e19905)
Location: include/linux/overflow.h:131
Inline: True
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81e1af27)
Location: include/linux/overflow.h:131
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
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
In arch/x86/events/intel/uncore.c (ffffffff83e69afb)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_type_init
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff83e7f9a3)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
```
```
In arch/x86/kernel/crash.c (ffffffff810ade72)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_load_segments
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff83ea431e)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
```
```
In kernel/workqueue.c (ffffffff811164a6)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/workqueue.c:apply_wqattrs_prepare
```
```
In kernel/groups.c (ffffffff8112bf1d)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
```
```
In kernel/power/swap.c (ffffffff81188dce)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/irq/devres.c (ffffffff8119cf99)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
```
In kernel/irq/generic-chip.c (ffffffff8119da57)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips
  - kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips
  - kernel/irq/generic-chip.c:irq_alloc_generic_chip
```
```
In kernel/irq/irqdomain.c (ffffffff8119ef57)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_create
```
```
In kernel/dma/swiotlb.c (ffffffff811c4cf2)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init_late
  - kernel/dma/swiotlb.c:swiotlb_init_late
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_init_remap
  - kernel/dma/swiotlb.c:swiotlb_init_remap
```
```
In kernel/module/sysfs.c (ffffffff811cfad8)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/module/sysfs.c:add_notes_attrs
  - kernel/module/sysfs.c:add_sect_attrs
```
```
In kernel/kexec_file.c (ffffffff81200995)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_purgatory_setup_sechdrs
```
```
In kernel/cgroup/cgroup.c (ffffffff8120bdd2)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
```
```
In kernel/audit.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In kernel/auditfilter.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In kernel/audit_tree.c (ffffffff81233019)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/tracepoint.c (ffffffff812507ed)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
```
```
In kernel/trace/tracing_map.c (ffffffff81278bc0)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
```
```
In kernel/trace/trace_eprobe.c (ffffffff81293d15)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ac2e4)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff812b7450)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:alloc_trace_uprobe
```
```
In kernel/bpf/core.c (ffffffff812c12b0)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/bpf/core.c:alloc_new_pack
```
```
In kernel/bpf/verifier.c (ffffffff812ef338)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - kernel/bpf/verifier.c:push_jmp_history
  - kernel/bpf/verifier.c:realloc_array
```
```
In kernel/bpf/local_storage.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In kernel/bpf/reuseport_array.c (ffffffff8132b897)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
```
In kernel/watch_queue.c (ffffffff81358052)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_filter
```
```
In mm/percpu.c (ffffffff83ebb040)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/list_lru.c (ffffffff813ab6c5)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_init_list_lru_one
```
```
In mm/madvise.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In mm/swapfile.c (ffffffff813fac05)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_swap_info
```
```
In mm/memcontrol.c (ffffffff8144f5b5)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
```
```
In mm/hugetlb_cgroup.c (ffffffff8145ce93)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/select.c (ffffffff8149a6c3)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/aio.c (ffffffff814f1b87)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - fs/aio.c:ioctx_add_table
```
```
In fs/verity/enable.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff8151cd85)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In ipc/sem.c (ffffffff81641792)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - ipc/sem.c:newary
```
```
In security/selinux/ss/sidtab.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In security/apparmor/lib.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In security/apparmor/label.c (ffffffff816e02e3)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
```
```
In security/landlock/ruleset.c (ffffffff816f0366)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:inherit_ruleset
  - security/landlock/ruleset.c:create_rule
  - security/landlock/ruleset.c:create_rule
```
```
In security/integrity/ima/ima_api.c (ffffffff816f9339)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
```
```
In security/integrity/ima/ima_policy.c (ffffffff816faadf)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_alloc_rule_opt_list
```
```
In security/integrity/ima/ima_template.c (ffffffff816fd435)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_template_data
```
```
In block/bio.c (ffffffff8172cb5c)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - block/bio.c:bio_kmalloc
```
```
In block/blk-map.c (ffffffff8173b41c)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - block/blk-map.c:bio_alloc_map_data
```
```
In block/partitions/core.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In block/blk-ia-ranges.c (ffffffff8175e73b)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - block/blk-ia-ranges.c:disk_alloc_independent_access_ranges
```
```
In block/blk-iocost.c (ffffffff8176b388)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_alloc
```
```
In block/bio-integrity.c (ffffffff81774c89)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_alloc
```
```
In io_uring/io_uring.c (ffffffff81788d52)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_register_restrictions
  - io_uring/io_uring.c:io_allocate_scq_urings
  - io_uring/io_uring.c:io_allocate_scq_urings
  - io_uring/io_uring.c:io_allocate_scq_urings
  - io_uring/io_uring.c:io_allocate_scq_urings
```
```
In io_uring/kbuf.c (ffffffff8179fcb6)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_register_pbuf_ring
```
```
In io_uring/rsrc.c (ffffffff817a244f)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_sqe_buffer_register
```
```
In io_uring/io-wq.c (ffffffff817a77c6)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_create
```
```
In lib/rhashtable.c (ffffffff817d98a7)
Location: include/linux/overflow.h:187
Inline: True
```
```
In lib/assoc_array.c (ffffffff817eb29d)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
```
```
In lib/stackdepot.c (ffffffff8189f23e)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - lib/stackdepot.c:__stack_depot_save
  - lib/stackdepot.c:depot_alloc_stack
```
```
In drivers/gpio/gpiolib.c (ffffffff818c110b)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c5e20)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_create
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff8194047a)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In drivers/video/fbdev/efifb.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In drivers/acpi/prmt.c (ffffffff83ee3a09)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/acpi/prmt.c:acpi_parse_prmt
  - drivers/acpi/prmt.c:acpi_parse_prmt
```
```
In drivers/reset/core.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In drivers/tty/vt/consolemap.c (ffffffff81a64c28)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_set_unimap
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81a85c1b)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
```
```
In drivers/tty/serial/max310x.c (ffffffff81a8967a)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/char/virtio_console.c (ffffffff81a96c4e)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:alloc_buf
```
```
In drivers/char/hpet.c (ffffffff81a9b14e)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
```
```
In drivers/char/tpm/eventlog/tpm2.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In drivers/iommu/intel/dmar.c (ffffffff81abd33e)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/iommu/iommu.c (ffffffff81acecaf)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_fwspec_add_ids
```
```
In drivers/block/xen-blkfront.c (ffffffff81b2ecfa)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:negotiate_mq
```
```
In drivers/nvdimm/region_devs.c (ffffffff81b55b07)
Location: include/linux/overflow.h:187
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81b6e175)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_list_alloc
```
```
In drivers/ata/libata-core.c (ffffffff81ba8935)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_config_cpr
```
```
In drivers/spi/spi.c (ffffffff81bd1caf)
Location: include/linux/overflow.h:187
Inline: True
```
```
In drivers/usb/core/urb.c (ffffffff81c21615)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_alloc_urb
```
```
In drivers/usb/core/config.c (ffffffff81c2a6b4)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81c4a9db)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81c5ced8)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:itd_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81c6749e)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
```
In drivers/usb/host/xhci.c (ffffffff81c7d39d)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/input/input-mt.c (ffffffff81caaffe)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_init_slots
```
```
In drivers/input/evdev.c (ffffffff81caf585)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-stripe.c (ffffffff81d15da0)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/md/dm-ioctl.c (ffffffff81d19205)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
```
```
In drivers/md/dm-stats.c (ffffffff81d1d2e4)
Location: include/linux/overflow.h:187
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff83f03878)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
```
In drivers/firmware/efi/efi.c (ffffffff83f079fb)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d76bdf)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81d7c0b0)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff81d7c8ba)
Location: include/linux/overflow.h:187
Inline: True
```
```
In drivers/devfreq/devfreq.c (ffffffff81d7eddd)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:trans_stat_store
  - drivers/devfreq/devfreq.c:trans_stat_store
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/interconnect/core.c (ffffffff81d8eefc)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/interconnect/core.c:path_find
```
```
In drivers/hte/hte.c (ffffffff81d90df9)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/hte/hte.c:hte_register_chip
```
```
In net/core/flow_offload.c (ffffffff81e08878)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - net/core/flow_offload.c:offload_action_alloc
  - net/core/flow_offload.c:flow_rule_alloc
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffffffff81e4c81b)
Location: include/linux/overflow.h:187
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81e55c6b)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/netlink/policy.c (ffffffff81e7065a)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - net/netlink/policy.c:add_policy
  - net/netlink/policy.c:add_policy
```
```
In net/ethtool/ioctl.c (ffffffff81e7a79f)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_vzalloc_stats_array
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ethtool/ioctl.c:ethtool_self_test
  - net/ethtool/ioctl.c:ethtool_copy_validate_indir
  - net/ethtool/ioctl.c:ethtool_get_sset_info
```
```
In net/ethtool/common.c (ffffffff81e7c5ae)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - net/ethtool/common.c:ethtool_get_max_rxnfc_channel
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81efbd4b)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
```
```
In net/ipv4/fib_semantics.c (ffffffff81f02883)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/nexthop.c (ffffffff81f1544c)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:nh_notifier_info_init
  - net/ipv4/nexthop.c:nh_notifier_mpath_info_init
```
```
In net/ipv6/mcast.c (ffffffff81f97407)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
```
```
In net/ipv6/exthdrs.c (ffffffff81fa0b47)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/packet/af_packet.c (ffffffff81fc5b04)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
```
```
In net/switchdev/switchdev.c (ffffffff81fe2ea5)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
```
```
In net/xdp/xsk_queue.c (0)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xskq_create
```
```
In net/xdp/xskmap.c (ffffffff81ff0c95)
Location: include/linux/overflow.h:187
Inline: True
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ff2487)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
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
In arch/x86/events/intel/uncore.c (ffffffff8368a492)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_type_init
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff836a26f8)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
```
```
In arch/x86/kernel/crash.c (ffffffff810b0e72)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_load_segments
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff836c8664)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
```
```
In kernel/workqueue.c (ffffffff81123246)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/workqueue.c:apply_wqattrs_prepare
```
```
In kernel/groups.c (ffffffff81138d7d)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
```
```
In kernel/power/swap.c (ffffffff81199f82)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/irq/devres.c (ffffffff811aee19)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
```
In kernel/irq/generic-chip.c (ffffffff811af90a)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips
  - kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips
  - kernel/irq/generic-chip.c:irq_alloc_generic_chip
```
```
In kernel/irq/irqdomain.c (ffffffff811b0e37)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_create
```
```
In kernel/dma/swiotlb.c (ffffffff811d7a18)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init_late
  - kernel/dma/swiotlb.c:swiotlb_init_late
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_init_remap
  - kernel/dma/swiotlb.c:swiotlb_init_remap
```
```
In kernel/module/sysfs.c (ffffffff811e3c78)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/module/sysfs.c:add_notes_attrs
  - kernel/module/sysfs.c:add_sect_attrs
```
```
In kernel/kexec_file.c (ffffffff81215d95)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_purgatory_setup_sechdrs
```
```
In kernel/cgroup/cgroup.c (ffffffff812213ee)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
```
```
In kernel/pid_namespace.c (ffffffff81238b57)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In kernel/auditfilter.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In kernel/audit_tree.c (ffffffff81249cc9)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/tracepoint.c (ffffffff81267b8c)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
```
```
In kernel/trace/tracing_map.c (ffffffff81290600)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
```
```
In kernel/trace/trace_eprobe.c (ffffffff812b0e05)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
```
```
In kernel/trace/trace_events_synth.c (ffffffff812b4ef4)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:trace_string
```
```
In kernel/trace/trace_events_user.c (ffffffff812c6eec)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_events_ioctl_reg
```
```
In kernel/trace/trace_kprobe.c (ffffffff812cff24)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff812daab0)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:alloc_trace_uprobe
```
```
In kernel/trace/trace_fprobe.c (ffffffff812dfda0)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:alloc_trace_fprobe
```
```
In kernel/bpf/core.c (ffffffff812e8062)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/bpf/core.c:alloc_new_pack
```
```
In kernel/bpf/verifier.c (ffffffff8131bd1d)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - kernel/bpf/verifier.c:push_jmp_history
  - kernel/bpf/verifier.c:realloc_array
```
```
In kernel/bpf/local_storage.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In kernel/bpf/reuseport_array.c (ffffffff8135b955)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:reuseport_array_mem_usage
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
```
In kernel/watch_queue.c (ffffffff813898ea)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_filter
```
```
In mm/percpu.c (ffffffff836e3668)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/list_lru.c (ffffffff813dfa65)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_init_list_lru_one
```
```
In mm/madvise.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In mm/swapfile.c (ffffffff8142dc55)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_swap_info
```
```
In mm/memcontrol.c (ffffffff814850e5)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
```
```
In mm/hugetlb_cgroup.c (ffffffff81492ee3)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/select.c (ffffffff814cf773)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/splice.c (ffffffff814fa769)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - fs/splice.c:copy_splice_read
```
```
In fs/aio.c (ffffffff815280d3)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - fs/aio.c:ioctx_add_table
```
```
In fs/verity/enable.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff81554f31)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In ipc/sem.c (ffffffff81679d12)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - ipc/sem.c:newary
```
```
In security/selinux/ss/sidtab.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In security/apparmor/lib.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In security/apparmor/label.c (ffffffff8171991a)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
```
```
In security/landlock/ruleset.c (ffffffff8172a721)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:inherit_ruleset
  - security/landlock/ruleset.c:create_rule
  - security/landlock/ruleset.c:create_rule
```
```
In security/integrity/ima/ima_api.c (ffffffff81733494)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
```
```
In security/integrity/ima/ima_policy.c (ffffffff81734bdf)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_alloc_rule_opt_list
```
```
In security/integrity/ima/ima_template.c (ffffffff81737465)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_template_data
```
```
In block/bio.c (ffffffff81768edc)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - block/bio.c:bio_kmalloc
```
```
In block/blk-map.c (ffffffff81777b31)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - block/blk-map.c:bio_alloc_map_data
```
```
In block/partitions/core.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In block/blk-ia-ranges.c (ffffffff8179d642)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - block/blk-ia-ranges.c:disk_alloc_independent_access_ranges
```
```
In block/blk-iocost.c (ffffffff817aa473)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_alloc
```
```
In block/bio-integrity.c (ffffffff817b49a9)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_alloc
```
```
In io_uring/io_uring.c (ffffffff817c9721)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_register_restrictions
  - io_uring/io_uring.c:io_allocate_scq_urings
  - io_uring/io_uring.c:io_allocate_scq_urings
  - io_uring/io_uring.c:io_allocate_scq_urings
  - io_uring/io_uring.c:io_allocate_scq_urings
```
```
In io_uring/kbuf.c (ffffffff817e0de5)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_register_pbuf_ring
```
```
In io_uring/rsrc.c (ffffffff817e34d2)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_sqe_buffer_register
```
```
In lib/scatterlist.c (ffffffff8180e01f)
Location: include/linux/overflow.h:187
Inline: True
```
```
In lib/rhashtable.c (ffffffff81818c41)
Location: include/linux/overflow.h:187
Inline: True
```
```
In lib/assoc_array.c (ffffffff8182b436)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
```
```
In lib/stackdepot.c (ffffffff818e17f9)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - lib/stackdepot.c:__stack_depot_save
  - lib/stackdepot.c:depot_alloc_stack
```
```
In drivers/gpio/gpiolib.c (ffffffff819040b5)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff81908ed1)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_create
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff8198499f)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/acpi/prmt.c (ffffffff837094bd)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/acpi/prmt.c:acpi_parse_prmt
  - drivers/acpi/prmt.c:acpi_parse_prmt
```
```
In drivers/reset/core.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In drivers/tty/vt/consolemap.c (ffffffff81aaf2f2)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_set_unimap
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81ad1397)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
```
```
In drivers/tty/serial/max310x.c (ffffffff81ad4e33)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/char/virtio_console.c (ffffffff81ae245e)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:alloc_buf
```
```
In drivers/char/hpet.c (ffffffff81ae69de)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
```
```
In drivers/char/tpm/eventlog/tpm2.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b09c59)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/iommu/iommu.c (ffffffff81b1d61f)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_fwspec_add_ids
```
```
In drivers/block/xen-blkfront.c (ffffffff81b82163)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:negotiate_mq
```
```
In drivers/nvdimm/region_devs.c (ffffffff81ba9057)
Location: include/linux/overflow.h:187
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81bc1985)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_list_alloc
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81be3437)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
```
```
In drivers/ata/libata-core.c (ffffffff81c0004d)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_config_cpr
```
```
In drivers/spi/spi.c (ffffffff81c29505)
Location: include/linux/overflow.h:187
Inline: True
```
```
In drivers/usb/core/urb.c (ffffffff81c88595)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_alloc_urb
```
```
In drivers/usb/core/config.c (ffffffff81c91649)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81cb1f93)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81cc4557)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:itd_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81cce846)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
```
In drivers/usb/host/xhci.c (ffffffff81ce44d5)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81cea745)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_erst
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/input/input-mt.c (ffffffff81d125e2)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_init_slots
```
```
In drivers/input/evdev.c (ffffffff81d16b85)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-stripe.c (ffffffff81d7f011)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/md/dm-ioctl.c (ffffffff81d824fe)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
```
```
In drivers/md/dm-stats.c (ffffffff81d864d4)
Location: include/linux/overflow.h:187
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8372977d)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
```
In drivers/firmware/efi/efi.c (ffffffff8372dace)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de4b1f)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81dea276)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff81deaa7a)
Location: include/linux/overflow.h:187
Inline: True
```
```
In drivers/devfreq/devfreq.c (ffffffff81ded16d)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:trans_stat_store
  - drivers/devfreq/devfreq.c:trans_stat_store
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/interconnect/core.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In drivers/hte/hte.c (ffffffff81dff0ab)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/hte/hte.c:hte_register_chip
```
```
In net/core/flow_offload.c (ffffffff81e7b188)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - net/core/flow_offload.c:offload_action_alloc
  - net/core/flow_offload.c:flow_rule_alloc
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffffffff81ea7f5b)
Location: include/linux/overflow.h:187
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81eb150b)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/netlink/policy.c (ffffffff81ecc775)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - net/netlink/policy.c:add_policy
  - net/netlink/policy.c:add_policy
```
```
In net/ethtool/ioctl.c (ffffffff81ed768e)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ethtool/ioctl.c:ethtool_self_test
  - net/ethtool/ioctl.c:ethtool_copy_validate_indir
  - net/ethtool/ioctl.c:ethtool_get_sset_info
```
```
In net/ethtool/common.c (ffffffff81ed8946)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - net/ethtool/common.c:ethtool_get_max_rxnfc_channel
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81f5b784)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
```
```
In net/ipv4/fib_semantics.c (ffffffff81f6238f)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/nexthop.c (ffffffff81f750df)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:nh_notifier_info_init
  - net/ipv4/nexthop.c:nh_notifier_mpath_info_init
```
```
In net/ipv6/mcast.c (ffffffff81ff7dc1)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In net/packet/af_packet.c (ffffffff8202a04e)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
```
```
In net/switchdev/switchdev.c (ffffffff8205f1c5)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
```
```
In net/xdp/xsk_queue.c (ffffffff8206ca9e)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xskq_create
  - net/xdp/xsk_queue.c:xskq_create
```
```
In net/xdp/xskmap.c (ffffffff8206cd75)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_mem_usage
  - net/xdp/xskmap.c:xsk_map_alloc
```
```
In net/xdp/xsk_buff_pool.c (ffffffff8206e6b7)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
```
```
In net/handshake/request.c (0)
Location: include/linux/overflow.h:187
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
In arch/x86/events/intel/uncore.c (ffffffff838ba052)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_type_init
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff838d27ef)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
```
```
In arch/x86/kernel/crash.c (ffffffff810b792f)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:prepare_elf_headers
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff838f9264)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
```
```
In kernel/workqueue.c (ffffffff8112d2ef)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/workqueue.c:apply_wqattrs_prepare
```
```
In kernel/groups.c (ffffffff81143abd)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
```
```
In kernel/power/swap.c (ffffffff811a8fdf)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/irq/devres.c (ffffffff811bea19)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
```
In kernel/irq/generic-chip.c (ffffffff811bf439)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips
  - kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips
  - kernel/irq/generic-chip.c:irq_alloc_generic_chip
```
```
In kernel/irq/irqdomain.c (ffffffff811c0bb7)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_create
```
```
In kernel/dma/swiotlb.c (ffffffff811ec4e6)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_dyn_free
  - kernel/dma/swiotlb.c:swiotlb_alloc_pool
  - kernel/dma/swiotlb.c:swiotlb_alloc_pool
  - kernel/dma/swiotlb.c:swiotlb_init_late
  - kernel/dma/swiotlb.c:swiotlb_init_late
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_init_remap
  - kernel/dma/swiotlb.c:swiotlb_init_remap
```
```
In kernel/module/sysfs.c (ffffffff811f99d8)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/module/sysfs.c:add_notes_attrs
  - kernel/module/sysfs.c:add_sect_attrs
```
```
In kernel/kexec_file.c (ffffffff8122dd65)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_purgatory_setup_sechdrs
```
```
In kernel/cgroup/cgroup.c (ffffffff812390ce)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
```
```
In kernel/pid_namespace.c (ffffffff81252827)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In kernel/auditfilter.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In kernel/audit_tree.c (ffffffff81263bd9)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/tracepoint.c (ffffffff8128153c)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
```
```
In kernel/trace/trace.c (ffffffff8129c303)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
```
```
In kernel/trace/tracing_map.c (ffffffff812abbf0)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
```
```
In kernel/trace/trace_eprobe.c (ffffffff812cd3c5)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
```
```
In kernel/trace/trace_events_synth.c (ffffffff812d15c0)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:trace_string
```
```
In kernel/trace/trace_events_user.c (ffffffff812e38b0)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_events_ioctl_reg
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ed924)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff812f8d00)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:alloc_trace_uprobe
```
```
In kernel/trace/trace_fprobe.c (ffffffff812fde70)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:alloc_trace_fprobe
```
```
In kernel/bpf/core.c (ffffffff81307c72)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/bpf/core.c:alloc_new_pack
```
```
In kernel/bpf/verifier.c (ffffffff8133e0bc)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - kernel/bpf/verifier.c:push_jmp_history
  - kernel/bpf/verifier.c:realloc_array
```
```
In kernel/bpf/local_storage.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In kernel/bpf/reuseport_array.c (ffffffff813845e5)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:reuseport_array_mem_usage
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
```
In kernel/watch_queue.c (ffffffff813b333a)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_filter
```
```
In mm/percpu.c (ffffffff83915ef8)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/list_lru.c (ffffffff8140a175)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_init_list_lru_one
```
```
In mm/madvise.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In mm/swapfile.c (ffffffff81467715)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_swap_info
```
```
In mm/memcontrol.c (ffffffff814b71c5)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
```
```
In mm/hugetlb_cgroup.c (ffffffff814c28e3)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/select.c (ffffffff815020b3)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/splice.c (ffffffff8152f169)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - fs/splice.c:copy_splice_read
```
```
In fs/aio.c (ffffffff8155d1c1)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - fs/aio.c:ioctx_add_table
```
```
In fs/verity/enable.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff8158b5e7)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:ifs_alloc
```
```
In ipc/sem.c (ffffffff816b71d1)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:newary
```
```
In security/security.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In security/selinux/ss/sidtab.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In security/apparmor/lib.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In security/apparmor/label.c (ffffffff817583ba)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
```
```
In security/landlock/ruleset.c (ffffffff8176bdc1)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:inherit_ruleset
```
```
In security/integrity/ima/ima_api.c (ffffffff81773eb4)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
```
```
In security/integrity/ima/ima_policy.c (ffffffff817756ef)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_alloc_rule_opt_list
```
```
In security/integrity/ima/ima_template.c (ffffffff81777f55)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_template_data
```
```
In security/integrity/ima/ima_modsig.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In block/bio.c (ffffffff817aaf0c)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - block/bio.c:bio_kmalloc
```
```
In block/blk-map.c (ffffffff817b9d55)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - block/blk-map.c:bio_alloc_map_data
```
```
In block/partitions/core.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In block/blk-ia-ranges.c (ffffffff817e1092)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - block/blk-ia-ranges.c:disk_alloc_independent_access_ranges
```
```
In block/blk-iocost.c (ffffffff817ee223)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_alloc
```
```
In block/bio-integrity.c (ffffffff817f89d0)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_alloc
```
```
In io_uring/io_uring.c (ffffffff81816618)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_allocate_scq_urings
  - io_uring/io_uring.c:io_allocate_scq_urings
  - io_uring/io_uring.c:io_allocate_scq_urings
  - io_uring/io_uring.c:io_allocate_scq_urings
```
```
In io_uring/kbuf.c (ffffffff818253d4)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_register_pbuf_ring
```
```
In io_uring/rsrc.c (ffffffff81827577)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_sqe_buffer_register
```
```
In io_uring/register.c (ffffffff8182b0b1)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - io_uring/register.c:io_register_restrictions
```
```
In lib/scatterlist.c (ffffffff81853d2b)
Location: include/linux/overflow.h:187
Inline: True
```
```
In lib/rhashtable.c (ffffffff8185df71)
Location: include/linux/overflow.h:187
Inline: True
```
```
In lib/assoc_array.c (ffffffff8187cfe5)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
```
```
In lib/stackdepot.c (ffffffff81928861)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - lib/stackdepot.c:stack_depot_save_flags
  - lib/stackdepot.c:depot_alloc_stack
  - lib/stackdepot.c:depot_alloc_stack
```
```
In drivers/gpio/gpiolib.c (ffffffff8194bae7)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff81951a0d)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_create
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff819ce8c3)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/acpi/mipi-disco-img.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In drivers/acpi/prmt.c (ffffffff8393c94c)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/acpi/prmt.c:acpi_parse_prmt
  - drivers/acpi/prmt.c:acpi_parse_prmt
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In drivers/reset/core.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In drivers/tty/tty_buffer.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81b251f7)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
```
```
In drivers/tty/serial/max310x.c (ffffffff81b282f5)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/char/virtio_console.c (ffffffff81b3584e)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:alloc_buf
```
```
In drivers/char/hpet.c (ffffffff81b39d6e)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
```
```
In drivers/char/tpm/eventlog/tpm2.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b5dca9)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/iommu/iommu.c (ffffffff81b73cbf)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_fwspec_add_ids
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b7c163)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_init_fq
  - drivers/iommu/dma-iommu.c:iommu_dma_init_fq
```
```
In drivers/iommu/virtio-iommu.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff81bd6023)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:negotiate_mq
```
```
In drivers/nvdimm/region_devs.c (ffffffff81bfd397)
Location: include/linux/overflow.h:187
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81c16115)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_list_alloc
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81c38897)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
```
```
In drivers/ata/libata-core.c (ffffffff81c560bd)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_config_cpr
```
```
In drivers/spi/spi.c (ffffffff81cdbd45)
Location: include/linux/overflow.h:187
Inline: True
```
```
In drivers/usb/core/urb.c (ffffffff81d3cfe5)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_alloc_urb
```
```
In drivers/usb/core/config.c (ffffffff81d46209)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81d66ca3)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81d79447)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:itd_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81d83746)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
```
In drivers/usb/host/xhci.c (ffffffff81d930d3)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81d9d21e)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_interrupter
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/input/input-mt.c (ffffffff81dc81e2)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_init_slots
```
```
In drivers/input/evdev.c (ffffffff81dcc835)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-stripe.c (ffffffff81e36631)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/md/dm-ioctl.c (ffffffff81e39b85)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
```
```
In drivers/md/dm-stats.c (ffffffff81e3dc19)
Location: include/linux/overflow.h:187
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8395d70d)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
```
In drivers/firmware/efi/efi.c (ffffffff83961eae)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e9ac0f)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81ea04e5)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
```
```
In drivers/remoteproc/remoteproc_elf_loader.c (ffffffff81ea0cea)
Location: include/linux/overflow.h:187
Inline: True
```
```
In drivers/devfreq/devfreq.c (ffffffff81ea350d)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:trans_stat_store
  - drivers/devfreq/devfreq.c:trans_stat_store
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/interconnect/core.c (ffffffff81eb383c)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/interconnect/core.c:path_find
```
```
In drivers/hte/hte.c (ffffffff81eb639b)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - drivers/hte/hte.c:hte_register_chip
```
```
In net/core/flow_offload.c (ffffffff81f3b418)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - net/core/flow_offload.c:offload_action_alloc
  - net/core/flow_offload.c:flow_rule_alloc
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffffffff81f6aa0e)
Location: include/linux/overflow.h:187
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81f73faf)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/netlink/policy.c (ffffffff81f8ff47)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - net/netlink/policy.c:add_policy
  - net/netlink/policy.c:add_policy
```
```
In net/ethtool/ioctl.c (ffffffff81f9af5c)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ethtool/ioctl.c:ethtool_self_test
  - net/ethtool/ioctl.c:ethtool_copy_validate_indir
  - net/ethtool/ioctl.c:ethtool_get_sset_info
```
```
In net/ethtool/common.c (ffffffff81f9c766)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - net/ethtool/common.c:ethtool_get_max_rxnfc_channel
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff82021cc4)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
```
```
In net/ipv4/fib_semantics.c (ffffffff8202895f)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/nexthop.c (ffffffff8203ba1c)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:nh_notifier_info_init
  - net/ipv4/nexthop.c:nh_notifier_mpath_info_init
```
```
In net/ipv4/tcp_sigpool.c (ffffffff8204cbe1)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - net/ipv4/tcp_sigpool.c:sigpool_reserve_scratch
```
```
In net/ipv6/mcast.c (ffffffff820c5a11)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In net/packet/af_packet.c (ffffffff820f9b4d)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
```
```
In net/switchdev/switchdev.c (ffffffff82132115)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
```
```
In net/xdp/xsk_queue.c (ffffffff8214094a)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xskq_create
  - net/xdp/xsk_queue.c:xskq_create
```
```
In net/xdp/xskmap.c (ffffffff82140c15)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_mem_usage
  - net/xdp/xskmap.c:xsk_map_alloc
```
```
In net/xdp/xsk_buff_pool.c (ffffffff82142737)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
```
```
In net/handshake/request.c (0)
Location: include/linux/overflow.h:187
Inline: True
```
```
In arch/x86/pci/irq.c (ffffffff83971394)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_find_routing_table
```
```
In lib/objpool.c (ffffffff821919e9)
Location: include/linux/overflow.h:187
Inline: True
Inline callers:
  - lib/objpool.c:objpool_init_percpu_slots
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
