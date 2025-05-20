# Function: <code>kcalloc</code>

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
In arch/x86/xen/grant-table.c (ffffffff81f63a83)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:xen_pvh_gnttab_setup
  - arch/x86/xen/grant-table.c:xen_pvh_gnttab_setup
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103f63f)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cache_get_priv_group
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104d5ad)
Location: include/linux/slab.h:557
Inline: True
```
```
In kernel/sched/core.c (ffffffff810a5e69)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - kernel/sched/core.c:register_sched_domain_sysctl
  - kernel/sched/core.c:register_sched_domain_sysctl
  - kernel/sched/core.c:register_sched_domain_sysctl
```
```
In kernel/sched/cpupri.c (ffffffff810c42bd)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/cpudeadline.c (ffffffff810c4869)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_init
```
```
In kernel/auditfilter.c (ffffffff81f823c1)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_register_class
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_rule_change
```
```
In kernel/trace/ftrace.c (ffffffff81142582)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:alloc_ftrace_hash
```
```
In kernel/trace/trace.c (ffffffff8115014d)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:create_trace_option_files
```
```
In kernel/trace/trace_syscalls.c (ffffffff81f854d7)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:init_ftrace_syscalls
```
```
In kernel/trace/trace_events_filter.c (ffffffff81163aed)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:replace_preds
  - kernel/trace/trace_events_filter.c:replace_preds
```
```
In kernel/bpf/verifier.c (ffffffff81176724)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/events/hw_breakpoint.c (ffffffff81f864b6)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
```
```
In mm/vmalloc.c (ffffffff811cda95)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
```
```
In mm/ksm.c (ffffffff811e4ded)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - mm/ksm.c:merge_across_nodes_store
```
```
In mm/zsmalloc.c (ffffffff81205705)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_create_pool
```
```
In fs/pipe.c (ffffffff8121619b)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
```
```
In fs/splice.c (ffffffff8123e3fc)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:iter_file_splice_write
```
```
In fs/aio.c (ffffffff8125cc25)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - fs/aio.c:SyS_io_setup
```
```
In fs/fuse/file.c (ffffffff81315a4c)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages
```
```
In security/selinux/hooks.c (ffffffff81341cd7)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_parse_opts_str
  - security/selinux/hooks.c:selinux_parse_opts_str
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
```
```
In security/selinux/ss/services.c (ffffffff81355807)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:security_get_classes
  - security/selinux/ss/services.c:security_get_permissions
```
```
In security/smack/smack_lsm.c (ffffffff81360899)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff813af620)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In block/bio.c (ffffffff813b265c)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
```
```
In block/partitions/aix.c (ffffffff813cf2fb)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In drivers/gpio/gpiolib.c (ffffffff81425216)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add
```
```
In drivers/rapidio/rio.c (ffffffff8145999f)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/acpi/acpi_lpat.c (ffffffff8148b438)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table
```
```
In drivers/xen/grant-table.c (ffffffff814c549d)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
```
```
In drivers/xen/events/events_base.c (ffffffff81fa496d)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/mcelog.c (ffffffff816f445c)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:bind_virq_for_mce
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff814d5bcb)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:push_cxx_to_hypervisor
  - drivers/xen/xen-acpi-processor.c:push_pxx_to_hypervisor
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
```
```
In drivers/tty/tty_io.c (ffffffff814e096b)
Location: include/linux/slab.h:557
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff815013c7)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
```
In drivers/iommu/dmar.c (ffffffff81533d46)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_alloc_dev_scope
```
```
In drivers/iommu/intel-iommu.c (ffffffff81539414)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_init_domains
  - drivers/iommu/intel-iommu.c:init_dmars
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816f4d61)
Location: include/linux/slab.h:557
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff81543a5f)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_register
```
```
In drivers/lightnvm/sysblk.c (ffffffff81544b2a)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - drivers/lightnvm/sysblk.c:nvm_write_and_verify
  - drivers/lightnvm/sysblk.c:nvm_dev_factory
```
```
In drivers/base/property.c (ffffffff81551312)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:device_add_property_set
  - drivers/base/property.c:device_add_property_set
```
```
In drivers/base/cacheinfo.c (ffffffff815525eb)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:detect_cache_attributes
  - drivers/base/cacheinfo.c:cache_add_dev
```
```
In drivers/block/xen-blkfront.c (ffffffff81573674)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
```
In drivers/mfd/mfd-core.c (ffffffff8158adb9)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_devices
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8159daa9)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
```
In drivers/nvdimm/label.c (ffffffff815a0340)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/dma-buf/fence.c (ffffffff815a4450)
Location: include/linux/slab.h:557
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff815fc6f6)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:talk_to_netback
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81637bd2)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8164a1ce)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81653456)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
```
```
In drivers/input/input.c (ffffffff81667b75)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/input/input-mt.c (ffffffff8166ad15)
Location: include/linux/slab.h:557
Inline: True
```
```
In drivers/input/ff-core.c (ffffffff8166b1e9)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/evdev.c (ffffffff8166e5bd)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_do_ioctl
```
```
In drivers/thermal/power_allocator.c (ffffffff81689e14)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:power_allocator_throttle
```
```
In drivers/clk/clk.c (ffffffff816e6375)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
```
```
In net/core/ethtool.c (ffffffff8171fbba)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_set_channels
  - net/core/ethtool.c:ethtool_set_rxfh_indir
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/rtnetlink.c (ffffffff8172b592)
Location: include/linux/slab.h:557
Inline: True
```
```
In net/core/filter.c (ffffffff81730fae)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - net/core/filter.c:bpf_convert_filter
```
```
In net/sched/sch_mq.c (ffffffff817423f9)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_init
```
```
In net/netlink/af_netlink.c (ffffffff8174d7a6)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_setsockopt
```
```
In net/ipv4/route.c (ffffffff81753816)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_acct_proc_show
  - net/ipv4/route.c:ip_rt_init
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81fbd935)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
```
```
In net/packet/af_packet.c (ffffffff81805451)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff81fbeabb)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_init
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81fbebf8)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff8181059f)
Location: include/linux/slab.h:557
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
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
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103f43d)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cache_get_priv_group
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104d598)
Location: include/linux/slab.h:591
Inline: True
```
```
In kernel/sched/cpupri.c (ffffffff810c7fad)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/cpudeadline.c (ffffffff810c8529)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_init
```
```
In kernel/sched/debug.c (ffffffff810cb379)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/auditfilter.c (ffffffff8112c921)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_register_class
```
```
In kernel/trace/ftrace.c (ffffffff8114a1e1)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:alloc_ftrace_hash
```
```
In kernel/trace/trace.c (ffffffff8115b88c)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - kernel/trace/trace.c:create_trace_option_files
  - kernel/trace/trace.c:__tracing_open
```
```
In kernel/trace/tracing_map.c (ffffffff8115fc97)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_elt_alloc
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_syscalls.c (ffffffff81faeade)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:init_ftrace_syscalls
```
```
In kernel/trace/trace_events_filter.c (ffffffff8116ef49)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:replace_preds
  - kernel/trace/trace_events_filter.c:replace_preds
```
```
In kernel/bpf/verifier.c (ffffffff811851c5)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/events/core.c (ffffffff81190ab4)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/hw_breakpoint.c (ffffffff81fafbfc)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
```
```
In mm/slab_common.c (ffffffff811cdc5a)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In mm/vmalloc.c (ffffffff811eb82d)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
```
```
In mm/ksm.c (ffffffff8120394f)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - mm/ksm.c:merge_across_nodes_store
```
```
In mm/zsmalloc.c (ffffffff8122a695)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_create_pool
```
```
In fs/pipe.c (ffffffff8123cfec)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/splice.c (ffffffff812667ff)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:iter_file_splice_write
```
```
In fs/aio.c (ffffffff81284fb3)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/squashfs/block.c (ffffffff81320c01)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/cache.c (ffffffff81321baf)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
```
```
In fs/squashfs/file.c (ffffffff81322dba)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
```
```
In fs/fuse/file.c (ffffffff8134a382)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages
```
```
In security/selinux/hooks.c (ffffffff8137f6c8)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_parse_opts_str
  - security/selinux/hooks.c:selinux_parse_opts_str
```
```
In security/selinux/ss/services.c (ffffffff8138fee4)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
```
```
In security/smack/smack_lsm.c (ffffffff81397832)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff813f3665)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
```
In block/bio.c (ffffffff813f5cd2)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
```
```
In block/partitions/aix.c (ffffffff8141465c)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In drivers/gpio/gpiolib.c (ffffffff8147080e)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data
```
```
In drivers/pwm/core.c (ffffffff814781de)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_add_with_polarity
```
```
In drivers/pci/pci.c (ffffffff814846eb)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_add_dma_alias
```
```
In drivers/rapidio/rio.c (ffffffff814a78eb)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/acpi/acpi_lpat.c (ffffffff814da26c)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table
```
```
In drivers/acpi/processor_idle.c (ffffffff814fbbf7)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
```
```
In drivers/xen/grant-table.c (ffffffff81516741)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
```
```
In drivers/xen/events/events_base.c (ffffffff81fd0f27)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/mcelog.c (ffffffff817594bc)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:bind_virq_for_mce
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff8152734c)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:push_pxx_to_hypervisor
  - drivers/xen/xen-acpi-processor.c:push_cxx_to_hypervisor
```
```
In drivers/xen/xlate_mmu.c (ffffffff81fd1cef)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
```
In drivers/tty/tty_io.c (ffffffff81532dd7)
Location: include/linux/slab.h:591
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff81551f29)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
```
In drivers/char/random.c (ffffffff81567dcb)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/char/random.c:rand_initialize
```
```
In drivers/iommu/dmar.c (ffffffff815885e3)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_alloc_dev_scope
```
```
In drivers/iommu/intel-iommu.c (ffffffff81fd7be2)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:iommu_init_domains
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81592863)
Location: include/linux/slab.h:591
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff81595a0a)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_register
```
```
In drivers/lightnvm/sysblk.c (ffffffff81596707)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/lightnvm/sysblk.c:nvm_dev_factory
  - drivers/lightnvm/sysblk.c:nvm_write_and_verify
```
```
In drivers/base/property.c (ffffffff815a3cb0)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/base/property.c:device_add_properties
  - drivers/base/property.c:device_add_properties
  - drivers/base/property.c:fwnode_property_match_string
```
```
In drivers/base/cacheinfo.c (ffffffff815a4772)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_add_dev
  - drivers/base/cacheinfo.c:detect_cache_attributes
```
```
In drivers/base/power/clock_ops.c (ffffffff815b1ad5)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:of_pm_clk_add_clks
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff815bd871)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
```
In drivers/base/regmap/regcache-lzo.c (ffffffff815bdf56)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-lzo.c:regcache_lzo_init
```
```
In drivers/base/regmap/regcache-flat.c (ffffffff815be196)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-flat.c:regcache_flat_init
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff815c0d46)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/block/xen-blkfront.c (ffffffff815ca6cd)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
```
In drivers/mfd/mfd-core.c (ffffffff815e0099)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_devices
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff815f40d2)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
```
```
In drivers/nvdimm/label.c (ffffffff815f630e)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/dma-buf/fence.c (ffffffff815fb5b3)
Location: include/linux/slab.h:591
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff8165c655)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:talk_to_netback
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816988df)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816aac2e)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816b3e8e)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
```
```
In drivers/input/input.c (ffffffff816c94aa)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/input/input-mt.c (ffffffff816cafe7)
Location: include/linux/slab.h:591
Inline: True
```
```
In drivers/input/ff-core.c (ffffffff816cb4b7)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/evdev.c (ffffffff816ceb4a)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_do_ioctl
```
```
In drivers/thermal/power_allocator.c (ffffffff816eac1c)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In drivers/clk/clk.c (ffffffff8174ca18)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
```
```
In drivers/mailbox/pcc.c (ffffffff81fe548d)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
```
In net/core/ethtool.c (ffffffff8178a8d7)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:ethtool_set_channels
  - net/core/ethtool.c:ethtool_set_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxfh_indir
```
```
In net/core/rtnetlink.c (ffffffff8179512c)
Location: include/linux/slab.h:591
Inline: True
```
```
In net/core/filter.c (ffffffff8179bb94)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - net/core/filter.c:bpf_convert_filter
```
```
In net/sched/sch_mq.c (ffffffff817af39d)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_init
```
```
In net/netlink/af_netlink.c (ffffffff81fea400)
Location: include/linux/slab.h:591
Inline: True
```
```
In net/ipv4/route.c (ffffffff81fea652)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:rt_acct_proc_show
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81feb7a7)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
```
```
In net/ipv6/calipso.c (ffffffff81fec715)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_init
```
```
In net/packet/af_packet.c (ffffffff81875fdb)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff81fec9b6)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_init
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81fecaf3)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81882c6c)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
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
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103ee8d)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cache_get_priv_group
```
```
In arch/x86/kernel/cpu/intel_rdt_schemata.c (ffffffff81044a11)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_schemata.c:rdtgroup_schemata_write
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8106632e)
Location: include/linux/slab.h:591
Inline: True
```
```
In kernel/sched/cpupri.c (ffffffff810cdfcc)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/cpudeadline.c (ffffffff810ce502)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_init
```
```
In kernel/sched/debug.c (ffffffff810d13aa)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/irq/affinity.c (ffffffff810ef908)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/auditfilter.c (ffffffff81136631)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_register_class
```
```
In kernel/trace/ftrace.c (ffffffff81154061)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:alloc_ftrace_hash
```
```
In kernel/trace/trace.c (ffffffff8116609c)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - kernel/trace/trace.c:create_trace_option_files
  - kernel/trace/trace.c:__tracing_open
```
```
In kernel/trace/tracing_map.c (ffffffff8116a6f7)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_elt_alloc
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_syscalls.c (ffffffff81feb105)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:init_ftrace_syscalls
```
```
In kernel/trace/trace_events_filter.c (ffffffff8117a6fe)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:replace_preds
  - kernel/trace/trace_events_filter.c:replace_preds
```
```
In kernel/bpf/verifier.c (ffffffff811921b0)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_analyzer
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
```
```
In kernel/events/core.c (ffffffff8119f981)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/hw_breakpoint.c (ffffffff81fec290)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
```
```
In mm/slab_common.c (ffffffff811dddaa)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In mm/vmalloc.c (ffffffff811fca94)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
```
```
In mm/ksm.c (ffffffff8121596f)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - mm/ksm.c:merge_across_nodes_store
```
```
In mm/zsmalloc.c (ffffffff8123cbe5)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_create_pool
```
```
In fs/pipe.c (ffffffff8124fd79)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/splice.c (ffffffff8127a464)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:iter_file_splice_write
```
```
In fs/aio.c (ffffffff812991bc)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/squashfs/block.c (ffffffff81336ab1)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/cache.c (ffffffff81337a3f)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
```
```
In fs/squashfs/file.c (ffffffff81338c47)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
```
```
In fs/fuse/file.c (ffffffff8135fb78)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages
```
```
In security/selinux/hooks.c (ffffffff81396158)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_parse_opts_str
  - security/selinux/hooks.c:selinux_parse_opts_str
```
```
In security/selinux/ss/services.c (ffffffff813a6b04)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
```
```
In security/smack/smack_lsm.c (ffffffff813ae412)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff8140ced5)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
```
In block/bio.c (ffffffff8140f6e2)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
```
```
In block/partitions/aix.c (ffffffff8142fb8c)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In block/blk-zoned.c (ffffffff814490e8)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
```
In drivers/gpio/gpiolib.c (ffffffff814928ee)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data
  - drivers/gpio/gpiolib.c:gpiochip_add_data
```
```
In drivers/gpio/gpiolib-devprop.c (ffffffff81494bae)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
```
```
In drivers/pwm/core.c (ffffffff8149953e)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_add_with_polarity
```
```
In drivers/pci/pci.c (ffffffff814a5ddb)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_add_dma_alias
```
```
In drivers/rapidio/rio.c (ffffffff814c99fb)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/acpi/acpi_lpat.c (ffffffff814fcb36)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff8200c18a)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/acpi/processor_idle.c (ffffffff8151e8cb)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
```
```
In drivers/clk/clk.c (ffffffff81535278)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8153f7c7)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
```
In drivers/xen/grant-table.c (ffffffff81542bb1)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
```
```
In drivers/xen/events/events_base.c (ffffffff8200e89f)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/mcelog.c (ffffffff81785a2a)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:bind_virq_for_mce
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff815538ac)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:push_pxx_to_hypervisor
  - drivers/xen/xen-acpi-processor.c:push_cxx_to_hypervisor
```
```
In drivers/xen/xlate_mmu.c (ffffffff8200f6af)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
```
In drivers/tty/tty_io.c (ffffffff8155f507)
Location: include/linux/slab.h:591
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff8157eaef)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
```
In drivers/char/random.c (ffffffff815944fb)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/char/random.c:rand_initialize
```
```
In drivers/iommu/dmar.c (ffffffff815b5ca3)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_alloc_dev_scope
```
```
In drivers/iommu/intel-iommu.c (ffffffff82015840)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:iommu_init_domains
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815c0123)
Location: include/linux/slab.h:591
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff815c3563)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_register
```
```
In drivers/lightnvm/sysblk.c (ffffffff815c4234)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/lightnvm/sysblk.c:nvm_dev_factory
  - drivers/lightnvm/sysblk.c:nvm_write_and_verify
```
```
In drivers/base/property.c (ffffffff815d23c0)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/base/property.c:device_add_properties
  - drivers/base/property.c:device_add_properties
  - drivers/base/property.c:fwnode_property_match_string
```
```
In drivers/base/cacheinfo.c (ffffffff815d2d80)
Location: include/linux/slab.h:591
Inline: True
```
```
In drivers/base/power/clock_ops.c (ffffffff815e0db5)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:of_pm_clk_add_clks
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff815ecc81)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
```
In drivers/base/regmap/regcache-lzo.c (ffffffff815ed366)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-lzo.c:regcache_lzo_init
```
```
In drivers/base/regmap/regcache-flat.c (ffffffff815ed5a6)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-flat.c:regcache_flat_init
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff815f0186)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/block/xen-blkfront.c (ffffffff815f732e)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
```
In drivers/mfd/mfd-core.c (ffffffff8160cd39)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_devices
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81621e6e)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
```
In drivers/nvdimm/label.c (ffffffff8162413b)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81629d66)
Location: include/linux/slab.h:591
Inline: True
```
```
In drivers/dma-buf/sync_file.c (ffffffff8162bb77)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
```
In drivers/scsi/sd_zbc.c (ffffffff81648f2a)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
```
In drivers/net/xen-netfront.c (ffffffff8168a46e)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816c6e0f)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816d8d6e)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816e203e)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
```
```
In drivers/input/input.c (ffffffff816f748a)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/input/input-mt.c (ffffffff816f8fa7)
Location: include/linux/slab.h:591
Inline: True
```
```
In drivers/input/ff-core.c (ffffffff816f9467)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/evdev.c (ffffffff816fc81a)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_do_ioctl
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81719746)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
```
```
In drivers/thermal/power_allocator.c (ffffffff8171bb3c)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In drivers/firmware/efi/apple-properties.c (ffffffff820234cc)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/firmware/efi/apple-properties.c:map_properties
```
```
In drivers/mailbox/pcc.c (ffffffff82023b9d)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
```
In net/core/ethtool.c (ffffffff817b7ff5)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:ethtool_set_channels
  - net/core/ethtool.c:ethtool_set_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxfh_indir
```
```
In net/core/rtnetlink.c (ffffffff817c299c)
Location: include/linux/slab.h:591
Inline: True
```
```
In net/core/filter.c (ffffffff817c9824)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - net/core/filter.c:bpf_convert_filter
```
```
In net/sched/sch_mq.c (ffffffff817dea1d)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_init
```
```
In net/netlink/af_netlink.c (ffffffff82028d04)
Location: include/linux/slab.h:591
Inline: True
```
```
In net/ipv4/route.c (ffffffff82028f03)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:rt_acct_proc_show
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8202a087)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
```
```
In net/ipv6/calipso.c (ffffffff8202b090)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_init
```
```
In net/packet/af_packet.c (ffffffff818aa4f3)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff8202b517)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_init
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff8202b5ea)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818b7519)
Location: include/linux/slab.h:591
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
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
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103ce4d)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cache_get_priv_group
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81041770)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
```
```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff810447c7)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:rdt_get_mon_l3_config
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81065655)
Location: include/linux/slab.h:621
Inline: True
```
```
In kernel/sched/cpupri.c (ffffffff810ca92c)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/cpudeadline.c (ffffffff810cadf6)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_init
```
```
In kernel/sched/debug.c (ffffffff810d04ca)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/irq/affinity.c (ffffffff810ef751)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/cgroup/rdma.c (ffffffff8112c06c)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/auditfilter.c (ffffffff81137924)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_register_class
```
```
In kernel/trace/ftrace.c (ffffffff8115614f)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:alloc_ftrace_hash
```
```
In kernel/trace/trace.c (ffffffff811695a2)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - kernel/trace/trace.c:create_trace_option_files
  - kernel/trace/trace.c:__tracing_open
```
```
In kernel/trace/tracing_map.c (ffffffff8116d6fb)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_elt_alloc
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_syscalls.c (ffffffff820cbb16)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:init_ftrace_syscalls
```
```
In kernel/trace/trace_events_filter.c (ffffffff8117d351)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:replace_preds
  - kernel/trace/trace_events_filter.c:replace_preds
```
```
In kernel/bpf/verifier.c (ffffffff81198f84)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_analyzer
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
```
```
In kernel/events/core.c (ffffffff811a6386)
Location: include/linux/slab.h:621
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff820cd28a)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
```
```
In mm/slab_common.c (ffffffff811e7a81)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In mm/vmalloc.c (ffffffff812077a2)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
```
```
In mm/ksm.c (ffffffff81221095)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - mm/ksm.c:merge_across_nodes_store
```
```
In fs/pipe.c (ffffffff8125bcb8)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/splice.c (ffffffff81287ba9)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:iter_file_splice_write
```
```
In fs/aio.c (ffffffff812a688f)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/squashfs/block.c (ffffffff8134b7e4)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/cache.c (ffffffff8134c748)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
```
```
In fs/squashfs/file.c (ffffffff8134d906)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
```
```
In fs/fuse/file.c (ffffffff81374768)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages
```
```
In security/selinux/hooks.c (ffffffff813ac5dd)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_parse_opts_str
  - security/selinux/hooks.c:selinux_parse_opts_str
```
```
In security/selinux/ss/policydb.c (ffffffff813b6e66)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
```
In security/selinux/ss/services.c (ffffffff813bd531)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
```
```
In security/smack/smack_lsm.c (ffffffff813c333d)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff8141a6ad)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In block/bio.c (ffffffff8141d0ff)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
```
```
In block/partitions/aix.c (ffffffff8143cc15)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In block/blk-zoned.c (ffffffff81457622)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
```
In drivers/gpio/gpiolib.c (ffffffff8149c2da)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data
  - drivers/gpio/gpiolib.c:gpiochip_add_data
```
```
In drivers/gpio/gpiolib-devprop.c (ffffffff8149e5b1)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
```
```
In drivers/pwm/core.c (ffffffff814a3146)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_add_with_polarity
```
```
In drivers/pci/pci.c (ffffffff814afd11)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_add_dma_alias
```
```
In drivers/rapidio/rio.c (ffffffff814d5932)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/acpi/acpi_lpat.c (ffffffff8150cf5b)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff820ed9a5)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/acpi/processor_idle.c (ffffffff8152fd8e)
Location: include/linux/slab.h:621
Inline: True
```
```
In drivers/clk/clk.c (ffffffff8154867b)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff8154bb2f)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81553566)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
```
In drivers/xen/grant-table.c (ffffffff81556a72)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
```
```
In drivers/xen/events/events_base.c (ffffffff820f034f)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/mcelog.c (ffffffff81567724)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:bind_virq_for_mce
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff815681fe)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:push_pxx_to_hypervisor
  - drivers/xen/xen-acpi-processor.c:push_cxx_to_hypervisor
```
```
In drivers/xen/xlate_mmu.c (ffffffff820f116d)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
```
In drivers/tty/tty_io.c (ffffffff81574a3a)
Location: include/linux/slab.h:621
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff8159324e)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
```
In drivers/char/random.c (ffffffff815a845b)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - drivers/char/random.c:rand_initialize
```
```
In drivers/iommu/dmar.c (ffffffff815cbaef)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_alloc_dev_scope
```
```
In drivers/iommu/intel-iommu.c (ffffffff820f74f5)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:iommu_init_domains
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815d5c38)
Location: include/linux/slab.h:621
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff815d96b2)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_register
```
```
In drivers/base/property.c (ffffffff815e6edc)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - drivers/base/property.c:property_entries_dup
  - drivers/base/property.c:property_entries_dup
  - drivers/base/property.c:fwnode_property_match_string
```
```
In drivers/base/cacheinfo.c (ffffffff815e78ed)
Location: include/linux/slab.h:621
Inline: True
```
```
In drivers/base/power/clock_ops.c (ffffffff815f5c2c)
Location: include/linux/slab.h:621
Inline: True
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff816014c4)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
```
In drivers/base/regmap/regcache-flat.c (ffffffff81601781)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-flat.c:regcache_flat_init
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff8160434a)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/block/xen-blkfront.c (ffffffff8160cb5a)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
```
In drivers/mfd/mfd-core.c (ffffffff81620e38)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_devices
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81636954)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
```
In drivers/nvdimm/label.c (ffffffff81638e24)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8163f6c5)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/sync_file.c (ffffffff81640da2)
Location: include/linux/slab.h:621
Inline: True
```
```
In drivers/scsi/sd_zbc.c (ffffffff8165d5bd)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
```
In drivers/spi/spi.c (ffffffff8168d57f)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_board_info
```
```
In drivers/net/phy/mdio-boardinfo.c (ffffffff8168dac8)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - drivers/net/phy/mdio-boardinfo.c:mdiobus_register_board_info
```
```
In drivers/net/tun.c (ffffffff816975bf)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_attach
```
```
In drivers/net/xen-netfront.c (ffffffff8169f73b)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:talk_to_netback
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff816d146c)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816db5e1)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816ed22e)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816f61ac)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
```
```
In drivers/input/input.c (ffffffff8170cfca)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/input/input-mt.c (ffffffff8170eafc)
Location: include/linux/slab.h:621
Inline: True
```
```
In drivers/input/ff-core.c (ffffffff8170efb8)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/evdev.c (ffffffff8171236b)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_do_ioctl
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81731a06)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
```
```
In drivers/thermal/power_allocator.c (ffffffff81733db9)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In drivers/edac/edac_mc.c (ffffffff8175d289)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
```
```
In drivers/firmware/efi/apple-properties.c (ffffffff821061e9)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - drivers/firmware/efi/apple-properties.c:map_properties
```
```
In drivers/mailbox/pcc.c (ffffffff82106c31)
Location: include/linux/slab.h:621
Inline: True
```
```
In drivers/nvmem/core.c (ffffffff817a5fb4)
Location: include/linux/slab.h:621
Inline: True
```
```
In net/core/ethtool.c (ffffffff817d4998)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_channels
  - net/core/ethtool.c:ethtool_set_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxfh_indir
```
```
In net/core/rtnetlink.c (ffffffff817e1148)
Location: include/linux/slab.h:621
Inline: True
```
```
In net/core/filter.c (ffffffff817e8756)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - net/core/filter.c:bpf_convert_filter
```
```
In net/sched/sch_mq.c (ffffffff817fe048)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_init
```
```
In net/netlink/af_netlink.c (ffffffff8210c25a)
Location: include/linux/slab.h:621
Inline: True
```
```
In net/ipv4/route.c (ffffffff8210c46f)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:rt_acct_proc_show
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8210d6a7)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
```
```
In net/ipv6/calipso.c (ffffffff8210e7cb)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_init
```
```
In net/packet/af_packet.c (ffffffff818d1013)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff8210ec21)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_init
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff8210ed04)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818de005)
Location: include/linux/slab.h:621
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
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
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103f9cd)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cache_get_priv_group
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81044bc6)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
```
```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff81047f98)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:rdt_get_mon_l3_config
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81069825)
Location: include/linux/slab.h:627
Inline: True
```
```
In kernel/sched/cpupri.c (ffffffff810d2101)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/cpudeadline.c (ffffffff810d2596)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_init
```
```
In kernel/sched/debug.c (ffffffff810d8351)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/irq/affinity.c (ffffffff810f8341)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/cgroup/rdma.c (ffffffff81138e7c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/auditfilter.c (ffffffff81144623)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_register_class
```
```
In kernel/trace/ftrace.c (ffffffff81162c6f)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:alloc_ftrace_hash
```
```
In kernel/trace/trace.c (ffffffff81176552)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/trace.c:create_trace_option_files
  - kernel/trace/trace.c:__tracing_open
```
```
In kernel/trace/tracing_map.c (ffffffff8117a7a8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_elt_alloc
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_syscalls.c (ffffffff826d4185)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:init_ftrace_syscalls
```
```
In kernel/trace/trace_events_filter.c (ffffffff8118abe1)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:replace_preds
  - kernel/trace/trace_events_filter.c:replace_preds
```
```
In kernel/bpf/verifier.c (ffffffff811a8409)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:do_check
```
```
In kernel/events/core.c (ffffffff811b9f7c)
Location: include/linux/slab.h:627
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff826d5cc8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
```
```
In mm/slab_common.c (ffffffff811fdcc1)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In mm/gup.c (ffffffff81207ac1)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/gup.c:get_user_pages_longterm
```
```
In mm/vmalloc.c (ffffffff812208af)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
```
```
In mm/ksm.c (ffffffff8123c375)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/ksm.c:merge_across_nodes_store
```
```
In fs/pipe.c (ffffffff8127e06d)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/splice.c (ffffffff812aa6de)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:iter_file_splice_write
```
```
In fs/aio.c (ffffffff812c9dc8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/squashfs/block.c (ffffffff8136fe00)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/cache.c (ffffffff81370dc8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
```
```
In fs/squashfs/file.c (ffffffff81371fb6)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
```
```
In fs/fuse/file.c (ffffffff81399438)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages
```
```
In security/selinux/hooks.c (ffffffff813d266d)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_parse_opts_str
  - security/selinux/hooks.c:selinux_parse_opts_str
```
```
In security/selinux/ss/policydb.c (ffffffff813dcfc8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
```
In security/selinux/ss/services.c (ffffffff813e36a1)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
```
```
In security/smack/smack_lsm.c (ffffffff813e9603)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814457d6)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
```
In block/partitions/aix.c (ffffffff81468e15)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In block/blk-zoned.c (ffffffff81483352)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
```
In drivers/gpio/gpiolib.c (ffffffff814da698)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-devprop.c (ffffffff814dd0f3)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
```
```
In drivers/pwm/core.c (ffffffff814e1eb6)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_add_with_polarity
```
```
In drivers/pci/pci.c (ffffffff814ef241)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_add_dma_alias
```
```
In drivers/rapidio/rio.c (ffffffff81515df8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/acpi/sleep.c (ffffffff81539aac)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:lpi_device_get_constraints
```
```
In drivers/acpi/x86/apple.c (ffffffff8154f712)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/acpi_lpat.c (ffffffff8154fecb)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff826f6908)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/acpi/processor_idle.c (ffffffff81590a34)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/clk/clk.c (ffffffff815abb17)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff815af0bf)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff815b6ee6)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
```
In drivers/xen/grant-table.c (ffffffff815bac42)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
```
```
In drivers/xen/events/events_base.c (ffffffff826f9b53)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/mcelog.c (ffffffff815cb8e4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:bind_virq_for_mce
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff815cc3a9)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:push_pxx_to_hypervisor
  - drivers/xen/xen-acpi-processor.c:push_cxx_to_hypervisor
```
```
In drivers/xen/xlate_mmu.c (ffffffff826fa95f)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
```
In drivers/tty/tty_io.c (ffffffff815d920a)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff815f7d7e)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
```
In drivers/char/random.c (ffffffff8160ed6b)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/char/random.c:rand_initialize
```
```
In drivers/iommu/dmar.c (ffffffff816328bf)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_alloc_dev_scope
```
```
In drivers/iommu/intel-iommu.c (ffffffff82700c5c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:iommu_init_domains
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8163c9e8)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff8164041e)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_register
```
```
In drivers/base/property.c (ffffffff8164e2ac)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/property.c:property_entries_dup
  - drivers/base/property.c:property_entries_dup
  - drivers/base/property.c:fwnode_property_match_string
```
```
In drivers/base/cacheinfo.c (ffffffff8164eca0)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/base/power/clock_ops.c (ffffffff8165db4c)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff81669844)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
```
In drivers/base/regmap/regcache-flat.c (ffffffff81669b01)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-flat.c:regcache_flat_init
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff8166c72a)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/block/xen-blkfront.c (ffffffff81675431)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
```
In drivers/mfd/mfd-core.c (ffffffff81689658)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_devices
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8169fac5)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (ffffffff816a1504)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/dma-buf/dma-fence.c (ffffffff816a8248)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/sync_file.c (ffffffff816a9c42)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/scsi/sd_zbc.c (ffffffff816c6c9f)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
```
In drivers/spi/spi.c (ffffffff816f70ff)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_board_info
```
```
In drivers/net/phy/mdio-boardinfo.c (ffffffff816f7678)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/net/phy/mdio-boardinfo.c:mdiobus_register_board_info
```
```
In drivers/net/xen-netfront.c (ffffffff8170a8e4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:talk_to_netback
```
```
In drivers/usb/core/quirks.c (ffffffff8172d1a0)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8173dade)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81747d14)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81759a15)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81762b2c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
```
```
In drivers/input/input.c (ffffffff8177e20a)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/input/input-mt.c (ffffffff8177fd3c)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/input/ff-core.c (ffffffff81780208)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/evdev.c (ffffffff8178359b)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_do_ioctl
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff817a2aa6)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
```
```
In drivers/thermal/power_allocator.c (ffffffff817a4f79)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff817a628e)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
```
In drivers/edac/edac_mc.c (ffffffff817cf2f9)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
```
```
In drivers/opp/cpu.c (ffffffff817d5e7a)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
```
In drivers/firmware/efi/apple-properties.c (ffffffff8270f8e5)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/mailbox/pcc.c (ffffffff82710585)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/nvmem/core.c (ffffffff8181d14d)
Location: include/linux/slab.h:627
Inline: True
```
```
In net/core/ethtool.c (ffffffff8184eefb)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_channels
  - net/core/ethtool.c:ethtool_set_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxfh_indir
```
```
In net/core/rtnetlink.c (ffffffff8185b8a6)
Location: include/linux/slab.h:627
Inline: True
```
```
In net/core/filter.c (ffffffff81863ae6)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/core/filter.c:bpf_convert_filter
```
```
In net/sched/sch_mq.c (ffffffff8187bc68)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_init
```
```
In net/netlink/af_netlink.c (ffffffff827165d5)
Location: include/linux/slab.h:627
Inline: True
```
```
In net/ipv4/route.c (ffffffff827167f1)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:rt_acct_proc_show
```
```
In net/ipv4/cipso_ipv4.c (ffffffff827179d2)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
```
```
In net/ipv6/route.c (ffffffff8191c2a3)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/calipso.c (ffffffff82718b82)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_init
```
```
In net/packet/af_packet.c (ffffffff81955f17)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff8271900f)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_init
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff827190f2)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81963bf5)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
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
In arch/x86/events/amd/iommu.c (ffffffff826d043d)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff826d27d0)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_type_init
```
```
In arch/x86/hyperv/hv_init.c (ffffffff826d8832)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81040fe5)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81046ea8)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
```
```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff8104a816)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:rdt_get_mon_l3_config
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104e0cb)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81051200)
Location: include/linux/slab.h:644
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (ffffffff81053e3c)
Location: include/linux/slab.h:644
Inline: True
```
```
In arch/x86/kernel/hpet.c (ffffffff8106beb5)
Location: include/linux/slab.h:644
Inline: True
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8106c435)
Location: include/linux/slab.h:644
Inline: True
```
```
In kernel/sysctl.c (ffffffff81098943)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/workqueue.c (ffffffff826f3c61)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/sched/fair.c (ffffffff810d1965)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/sched/cpupri.c (ffffffff810da1bb)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/cpudeadline.c (ffffffff810da68b)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_init
```
```
In kernel/sched/debug.c (ffffffff810df7d5)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/irq/affinity.c (ffffffff81100b94)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/cgroup/rdma.c (ffffffff8114764c)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/auditfilter.c (ffffffff81152f96)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_register_class
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81163b82)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
```
```
In kernel/trace/ftrace.c (ffffffff81171ae8)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:alloc_ftrace_hash
  - kernel/trace/ftrace.c:ftrace_profile_write
```
```
In kernel/trace/trace.c (ffffffff811856e4)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - kernel/trace/trace.c:create_trace_option_files
  - kernel/trace/trace.c:set_tracer_flag
  - kernel/trace/trace.c:__tracing_open
```
```
In kernel/trace/tracing_map.c (ffffffff8118a4d4)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_init
  - kernel/trace/tracing_map.c:tracing_map_init
  - kernel/trace/tracing_map.c:tracing_map_init
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_syscalls.c (ffffffff826fe8da)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:init_ftrace_syscalls
```
```
In kernel/trace/trace_events_hist.c (ffffffff811a4114)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_synth_event
```
```
In kernel/trace/bpf_trace.c (ffffffff811a5d66)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
```
In kernel/bpf/core.c (ffffffff811b27d5)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
```
```
In kernel/bpf/verifier.c (ffffffff811bee36)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:do_check
```
```
In kernel/bpf/sockmap.c (ffffffff811cf6ff)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:bpf_exec_tx_verdict
```
```
In kernel/events/core.c (ffffffff811d9386)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/hw_breakpoint.c (ffffffff826fff5e)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
```
```
In kernel/events/uprobes.c (ffffffff811e5d3d)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In mm/slab_common.c (ffffffff8121eff9)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In mm/gup.c (ffffffff812286f7)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - mm/gup.c:get_user_pages_longterm
```
```
In mm/vmalloc.c (ffffffff81242696)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
```
```
In mm/ksm.c (ffffffff8125f8f5)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - mm/ksm.c:merge_across_nodes_store
```
```
In mm/slub.c (ffffffff81268925)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
  - mm/slub.c:__kmem_cache_shutdown
```
```
In fs/pipe.c (ffffffff812a4fd7)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/splice.c (ffffffff812d1da0)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:iter_file_splice_write
```
```
In fs/aio.c (ffffffff812f30ba)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/proc/proc_sysctl.c (ffffffff813276e0)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:register_leaf_sysctl_tables
```
```
In fs/ext4/extents.c (ffffffff8133dde3)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
```
```
In fs/squashfs/block.c (ffffffff8139e612)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/cache.c (ffffffff8139f60b)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
```
```
In fs/squashfs/file.c (ffffffff813a0851)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
```
```
In fs/fuse/file.c (ffffffff813c802f)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages
```
```
In security/selinux/hooks.c (ffffffff81402601)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_parse_opts_str
  - security/selinux/hooks.c:selinux_parse_opts_str
```
```
In security/selinux/ss/policydb.c (ffffffff8140e072)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
```
In security/selinux/ss/services.c (ffffffff81413e5e)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policy
```
```
In security/smack/smack_lsm.c (ffffffff8141a4f5)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
```
```
In security/apparmor/policy_unpack.c (ffffffff8143f2e9)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff8147863e)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
```
In block/bio.c (ffffffff82719004)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - block/bio.c:init_bio
```
```
In block/blk-tag.c (ffffffff81485a70)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - block/blk-tag.c:init_tag_map
  - block/blk-tag.c:init_tag_map
```
```
In block/partitions/aix.c (ffffffff8149cd35)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In lib/mpi/mpiutil.c (ffffffff814f6217)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - lib/mpi/mpiutil.c:mpi_resize
```
```
In drivers/gpio/gpiolib.c (ffffffff8150b342)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-devprop.c (ffffffff8150c2ba)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
```
```
In drivers/pwm/core.c (ffffffff815116c1)
Location: include/linux/slab.h:644
Inline: True
```
```
In drivers/pci/pci.c (ffffffff8151f321)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_add_dma_alias
```
```
In drivers/pci/msi.c (ffffffff81541b97)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/pci/msi.c:populate_msi_sysfs
```
```
In drivers/rapidio/rio.c (ffffffff8154cb9e)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/video/fbdev/core/fbmon.c (ffffffff81555966)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmon.c:fb_edid_add_monspecs
  - drivers/video/fbdev/core/fbmon.c:fb_create_modedb
```
```
In drivers/acpi/sleep.c (ffffffff8156f828)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:lpi_device_get_constraints
```
```
In drivers/acpi/acpi_platform.c (ffffffff8158135b)
Location: include/linux/slab.h:644
Inline: True
```
```
In drivers/acpi/sysfs.c (ffffffff81584072)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
```
```
In drivers/acpi/x86/apple.c (ffffffff81585f8d)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/acpi_lpat.c (ffffffff8158678f)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff8272093a)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/acpi/processor_idle.c (ffffffff815c7d4f)
Location: include/linux/slab.h:644
Inline: True
```
```
In drivers/clk/clk.c (ffffffff815e3b27)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff815e72d5)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff815ef3d7)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
```
In drivers/xen/grant-table.c (ffffffff815f28e1)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
```
```
In drivers/xen/events/events_base.c (ffffffff82723eed)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/mcelog.c (ffffffff816040d8)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:bind_virq_for_mce
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff82724a95)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:push_pxx_to_hypervisor
  - drivers/xen/xen-acpi-processor.c:push_cxx_to_hypervisor
```
```
In drivers/xen/xlate_mmu.c (ffffffff82724c4d)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
```
In drivers/tty/tty_io.c (ffffffff8161219a)
Location: include/linux/slab.h:644
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff81630dcb)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_core.c:uart_register_driver
```
```
In drivers/char/random.c (ffffffff81648495)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/iommu/dmar.c (ffffffff8166ee09)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_alloc_dev_scope
```
```
In drivers/iommu/intel-iommu.c (ffffffff816717bc)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_suspend
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:iommu_init_domains
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81677e36)
Location: include/linux/slab.h:644
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff8167a5d1)
Location: include/linux/slab.h:644
Inline: True
```
```
In drivers/base/property.c (ffffffff81689ab2)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/base/property.c:property_entries_dup
  - drivers/base/property.c:property_entries_dup
  - drivers/base/property.c:fwnode_property_match_string
```
```
In drivers/base/cacheinfo.c (ffffffff8168a438)
Location: include/linux/slab.h:644
Inline: True
```
```
In drivers/base/power/clock_ops.c (0)
Location: include/linux/slab.h:644
Inline: True
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff816a51ba)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
```
In drivers/base/regmap/regcache-flat.c (ffffffff816a547d)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-flat.c:regcache_flat_init
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff816a817c)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/block/xen-blkfront.c (ffffffff816b1fd4)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
```
In drivers/misc/sram.c (ffffffff816b375f)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/mfd-core.c (ffffffff816c5765)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_devices
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816dbd79)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (ffffffff816ddcd1)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/dma-buf/dma-fence.c (ffffffff816e4529)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/sync_file.c (ffffffff816e6167)
Location: include/linux/slab.h:644
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff81709e06)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
```
```
In drivers/ata/libata-core.c (ffffffff8272f0a1)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_parse_force_param
```
```
In drivers/ata/libata-pmp.c (ffffffff81725e93)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
```
In drivers/spi/spi.c (ffffffff8173259c)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_board_info
```
```
In drivers/net/phy/mdio-boardinfo.c (ffffffff81734845)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/net/phy/mdio-boardinfo.c:mdiobus_register_board_info
```
```
In drivers/net/xen-netfront.c (ffffffff817493bc)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:talk_to_netback
```
```
In drivers/usb/core/hub.c (ffffffff817582c7)
Location: include/linux/slab.h:644
Inline: True
```
```
In drivers/usb/core/quirks.c (ffffffff8176bff8)
Location: include/linux/slab.h:644
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8177e463)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81788502)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:find_tt
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81799fb8)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/input/input.c (ffffffff817bf339)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/input/input-mt.c (ffffffff817c0e35)
Location: include/linux/slab.h:644
Inline: True
```
```
In drivers/input/ff-core.c (ffffffff817c1307)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/evdev.c (ffffffff817c4658)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_do_ioctl
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff817e0772)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:ptp_populate_pin_groups
  - drivers/ptp/ptp_sysfs.c:ptp_populate_pin_groups
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff817ea3c5)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
```
```
In drivers/thermal/power_allocator.c (ffffffff817eca2a)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff817edd15)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
```
In drivers/md/md-bitmap.c (ffffffff81804375)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:bitmap_resize
```
```
In drivers/edac/edac_mc.c (ffffffff81817e81)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
```
```
In drivers/opp/cpu.c (ffffffff8181eb4c)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81827437)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/firmware/efi/capsule.c (ffffffff81846a21)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff82739407)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
```
```
In drivers/firmware/efi/apple-properties.c (ffffffff82739b94)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/firmware/efi/apple-properties.c:map_properties
```
```
In drivers/mailbox/pcc.c (ffffffff8273a7c4)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
```
In drivers/extcon/extcon.c (ffffffff818600ba)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In drivers/powercap/powercap_sys.c (ffffffff8186400b)
Location: include/linux/slab.h:644
Inline: True
```
```
In drivers/nvmem/core.c (ffffffff818670a5)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_add_cells
```
```
In arch/x86/pci/xen.c (ffffffff8186919c)
Location: include/linux/slab.h:644
Inline: True
```
```
In net/core/ethtool.c (ffffffff8189ab75)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_channels
  - net/core/ethtool.c:ethtool_set_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_get_sset_info
```
```
In net/core/rtnetlink.c (ffffffff818a7279)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_register_internal
```
```
In net/core/filter.c (ffffffff818b6e78)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - net/core/filter.c:bpf_convert_filter
```
```
In net/sched/sch_mq.c (ffffffff818ce486)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_init
```
```
In net/netlink/af_netlink.c (ffffffff8274091a)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_proto_init
```
```
In net/ipv4/route.c (ffffffff82740b2e)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
```
```
In net/ipv4/fib_frontend.c (ffffffff819322b8)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
```
In net/ipv4/cipso_ipv4.c (ffffffff82741dc4)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
```
```
In net/ipv6/route.c (ffffffff81973c51)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/icmp.c (ffffffff819894e1)
Location: include/linux/slab.h:644
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff82743306)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_init
```
```
In net/packet/af_packet.c (ffffffff819b1165)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff82743780)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_init
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff8274385a)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819bd1eb)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
```
In net/ncsi/ncsi-rsp.c (ffffffff819c76fd)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
```
```
In net/xdp/xdp_umem.c (ffffffff819cd1a1)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In arch/x86/events/amd/iommu.c (ffffffff828864fc)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff82888ae0)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_type_init
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8288eabd)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810425f5)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104b84e)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8104e8b7)
Location: include/linux/slab.h:679
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (ffffffff810514bc)
Location: include/linux/slab.h:679
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81055ef1)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105ab96)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
```
```
In arch/x86/kernel/hpet.c (ffffffff81071c45)
Location: include/linux/slab.h:679
Inline: True
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8107223b)
Location: include/linux/slab.h:679
Inline: True
```
```
In kernel/sysctl.c (ffffffff810a0cf6)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/workqueue.c (ffffffff828aaa49)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/sched/fair.c (ffffffff810db2a5)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/sched/cpupri.c (ffffffff810e3d0b)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/cpudeadline.c (ffffffff810e41db)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_init
```
```
In kernel/sched/debug.c (ffffffff810e9f55)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/irq/affinity.c (ffffffff8110c2f3)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/cgroup/rdma.c (ffffffff8115337c)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/auditfilter.c (ffffffff8115fc46)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_register_class
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff811708db)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
```
```
In kernel/trace/ftrace.c (ffffffff8117f2f8)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:alloc_ftrace_hash
  - kernel/trace/ftrace.c:ftrace_profile_write
```
```
In kernel/trace/trace.c (ffffffff81193014)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - kernel/trace/trace.c:create_trace_option_files
  - kernel/trace/trace.c:set_tracer_flag
  - kernel/trace/trace.c:__tracing_open
```
```
In kernel/trace/tracing_map.c (ffffffff81197e34)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_init
  - kernel/trace/tracing_map.c:tracing_map_init
  - kernel/trace/tracing_map.c:tracing_map_init
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_syscalls.c (ffffffff828b57f4)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:init_ftrace_syscalls
```
```
In kernel/trace/trace_events_hist.c (ffffffff811af80f)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
```
In kernel/trace/bpf_trace.c (ffffffff811b4076)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
```
In kernel/bpf/core.c (ffffffff811c135d)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
  - kernel/bpf/core.c:bpf_prog_alloc_jited_linfo
```
```
In kernel/bpf/verifier.c (ffffffff811cf94d)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:do_check
```
```
In kernel/events/core.c (ffffffff811e98b4)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/hw_breakpoint.c (ffffffff828b6fc8)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
```
```
In kernel/events/uprobes.c (ffffffff811f688d)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In mm/slab_common.c (ffffffff81231fe9)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In mm/gup.c (ffffffff8123bf17)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - mm/gup.c:get_user_pages_longterm
```
```
In mm/vmalloc.c (ffffffff81256dce)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
```
```
In mm/ksm.c (ffffffff81274035)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - mm/ksm.c:merge_across_nodes_store
```
```
In mm/slub.c (ffffffff8127d3c5)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
```
```
In fs/pipe.c (ffffffff812ba0a7)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/splice.c (ffffffff812e7180)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:iter_file_splice_write
```
```
In fs/aio.c (ffffffff81307ddd)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/proc/proc_sysctl.c (ffffffff8133e870)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:register_leaf_sysctl_tables
```
```
In fs/ext4/extents.c (ffffffff8135602f)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
```
```
In fs/squashfs/block.c (ffffffff813b7382)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/cache.c (ffffffff813b839b)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
```
```
In fs/squashfs/file.c (ffffffff813b95d3)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
```
```
In fs/fuse/file.c (ffffffff813e1259)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages
```
```
In fs/fuse/inode.c (ffffffff813e7cd1)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_dev_alloc
```
```
In security/security.c (ffffffff828cd5d7)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - security/security.c:ordered_lsm_init
```
```
In security/selinux/ss/policydb.c (ffffffff81428713)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In security/selinux/ss/services.c (ffffffff814303ae)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policy
```
```
In security/apparmor/policy_unpack.c (ffffffff8145c1f1)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In security/integrity/ima/ima_policy.c (ffffffff828d038e)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff8149686f)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
```
In block/bio.c (ffffffff828d1075)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - block/bio.c:init_bio
```
```
In block/partitions/aix.c (ffffffff814b7055)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In lib/mpi/mpiutil.c (ffffffff8150a617)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - lib/mpi/mpiutil.c:mpi_resize
```
```
In drivers/gpio/gpiolib.c (ffffffff81520197)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-devprop.c (ffffffff81521938)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
```
```
In drivers/pwm/core.c (ffffffff81526d71)
Location: include/linux/slab.h:679
Inline: True
```
```
In drivers/pci/msi.c (ffffffff81558ee7)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/pci/msi.c:populate_msi_sysfs
```
```
In drivers/rapidio/rio.c (ffffffff81563c0e)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/video/fbdev/core/fbmon.c (ffffffff8156d816)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmon.c:fb_edid_add_monspecs
  - drivers/video/fbdev/core/fbmon.c:fb_create_modedb
```
```
In drivers/acpi/sleep.c (ffffffff81587408)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:lpi_device_get_constraints
```
```
In drivers/acpi/acpi_platform.c (ffffffff8159941b)
Location: include/linux/slab.h:679
Inline: True
```
```
In drivers/acpi/sysfs.c (ffffffff8159c1a2)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
```
```
In drivers/acpi/acpi_lpat.c (ffffffff8159ea9f)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff828d88d0)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/acpi/acpi_adxl.c (ffffffff828d8ad1)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/acpi/acpi_adxl.c:adxl_init
```
```
In drivers/acpi/processor_idle.c (ffffffff815e130f)
Location: include/linux/slab.h:679
Inline: True
```
```
In drivers/clk/clk.c (ffffffff815fdf07)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81601705)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81609ae7)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
```
In drivers/xen/grant-table.c (ffffffff8160ded1)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
```
```
In drivers/xen/events/events_base.c (ffffffff828dc0c6)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/mcelog.c (ffffffff8161f178)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:bind_virq_for_mce
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff828dcc6e)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:push_pxx_to_hypervisor
  - drivers/xen/xen-acpi-processor.c:push_cxx_to_hypervisor
```
```
In drivers/xen/xlate_mmu.c (ffffffff828dce26)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
```
In drivers/tty/tty_io.c (ffffffff8162f23a)
Location: include/linux/slab.h:679
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff8164ef7f)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_core.c:uart_register_driver
```
```
In drivers/char/random.c (ffffffff81666965)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/iommu/dmar.c (ffffffff8168d362)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_alloc_dev_scope
```
```
In drivers/iommu/intel-iommu.c (ffffffff8168fa8c)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_suspend
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:iommu_init_domains
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81696f16)
Location: include/linux/slab.h:679
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff81699efb)
Location: include/linux/slab.h:679
Inline: True
```
```
In drivers/base/property.c (ffffffff816a9101)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_property_match_string
```
```
In drivers/base/cacheinfo.c (ffffffff816a9938)
Location: include/linux/slab.h:679
Inline: True
```
```
In drivers/base/swnode.c (ffffffff816aa5ee)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/base/swnode.c:property_entries_dup
  - drivers/base/swnode.c:property_entries_dup
```
```
In drivers/base/power/clock_ops.c (0)
Location: include/linux/slab.h:679
Inline: True
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff816c5d01)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
```
In drivers/base/regmap/regcache-flat.c (ffffffff816c5fbd)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-flat.c:regcache_flat_init
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff816c8dd5)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/block/xen-blkfront.c (ffffffff816d2ad4)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
```
In drivers/misc/sram.c (ffffffff816d4a1f)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/mfd-core.c (ffffffff816e6b55)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_devices
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816fdd57)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81707971)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/sync_file.c (ffffffff817094f7)
Location: include/linux/slab.h:679
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff8172c2f4)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
```
```
In drivers/ata/libata-core.c (ffffffff828e7ac9)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_parse_force_param
```
```
In drivers/ata/libata-pmp.c (ffffffff81748653)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
```
In drivers/spi/spi.c (ffffffff81754f8c)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_board_info
```
```
In drivers/net/phy/mdio-boardinfo.c (ffffffff81757985)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/net/phy/mdio-boardinfo.c:mdiobus_register_board_info
```
```
In drivers/net/xen-netfront.c (ffffffff8176d0f5)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
```
```
In drivers/usb/core/hub.c (ffffffff8177c837)
Location: include/linux/slab.h:679
Inline: True
```
```
In drivers/usb/core/quirks.c (ffffffff817905c8)
Location: include/linux/slab.h:679
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817a4aeb)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817b1692)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:find_tt
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817c03e8)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/input/input.c (ffffffff817e6799)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/input/input-mt.c (ffffffff817e8325)
Location: include/linux/slab.h:679
Inline: True
```
```
In drivers/input/ff-core.c (ffffffff817e87f7)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff8180bd42)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:ptp_populate_pin_groups
  - drivers/ptp/ptp_sysfs.c:ptp_populate_pin_groups
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81816275)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
```
```
In drivers/thermal/power_allocator.c (ffffffff81818b46)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff81819beb)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
```
In drivers/md/md-bitmap.c (ffffffff81830575)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
```
```
In drivers/edac/edac_mc.c (ffffffff81843713)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
```
```
In drivers/opp/cpu.c (ffffffff8184a9cc)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81853337)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/firmware/efi/capsule.c (ffffffff81872c81)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff828f33d6)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
```
```
In drivers/firmware/efi/apple-properties.c (ffffffff828f3b63)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/firmware/efi/apple-properties.c:map_properties
```
```
In drivers/mailbox/pcc.c (ffffffff828f47bf)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
```
In drivers/extcon/extcon.c (ffffffff8187fa26)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In drivers/powercap/powercap_sys.c (ffffffff8188379b)
Location: include/linux/slab.h:679
Inline: True
```
```
In drivers/nvmem/core.c (ffffffff81887254)
Location: include/linux/slab.h:679
Inline: True
```
```
In arch/x86/pci/xen.c (ffffffff8188921c)
Location: include/linux/slab.h:679
Inline: True
```
```
In net/core/ethtool.c (ffffffff818bd3d2)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_channels
  - net/core/ethtool.c:ethtool_set_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_get_sset_info
```
```
In net/core/rtnetlink.c (ffffffff818ca9b9)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_register_internal
```
```
In net/core/filter.c (ffffffff818dd428)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - net/core/filter.c:bpf_convert_filter
```
```
In net/core/net-sysfs.c (ffffffff818e44fc)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
```
```
In net/sched/sch_mq.c (ffffffff818f96c6)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_init
```
```
In net/netlink/af_netlink.c (ffffffff828fab4b)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_proto_init
```
```
In net/ipv4/route.c (ffffffff828fad5f)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
```
```
In net/ipv4/fib_frontend.c (ffffffff81961b18)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
```
In net/ipv4/cipso_ipv4.c (ffffffff828fc0e4)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
```
```
In net/ipv6/route.c (ffffffff819a9855)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/icmp.c (ffffffff819bfe01)
Location: include/linux/slab.h:679
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff828fd5fc)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_init
```
```
In net/packet/af_packet.c (ffffffff819e8549)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff828fda9e)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_init
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff828fdb78)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f457c)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/ncsi/ncsi-rsp.c (ffffffff819ff10d)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
```
```
In net/xdp/xdp_umem.c (ffffffff81a06369)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In arch/x86/events/amd/iommu.c (ffffffff8289d426)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:_init_events_attrs
```
```
In arch/x86/events/intel/uncore.c (ffffffff8289fcc6)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_types_init
```
```
In arch/x86/hyperv/hv_init.c (ffffffff828a6067)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81044a65)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81051982)
Location: include/linux/slab.h:685
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (ffffffff810545de)
Location: include/linux/slab.h:685
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81059105)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105deb0)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
```
```
In arch/x86/kernel/hpet.c (ffffffff828b7dec)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81075d5b)
Location: include/linux/slab.h:685
Inline: True
```
```
In kernel/workqueue.c (ffffffff828c322f)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/sched/fair.c (ffffffff810e2715)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/sched/cpupri.c (ffffffff810ea8fe)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/cpudeadline.c (ffffffff810eadd9)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_init
```
```
In kernel/sched/debug.c (ffffffff810f0e03)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/irq/affinity.c (ffffffff81115b6a)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/cgroup/rdma.c (ffffffff8115f70c)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/auditfilter.c (ffffffff8116c6a9)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_register_class
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8117cb1a)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
```
```
In kernel/trace/ftrace.c (ffffffff8118c3f8)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:alloc_ftrace_hash
  - kernel/trace/ftrace.c:ftrace_profile_init
```
```
In kernel/trace/trace.c (ffffffff811a0b0e)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - kernel/trace/trace.c:create_trace_option_files
  - kernel/trace/trace.c:set_tracer_flag
  - kernel/trace/trace.c:__tracing_open
```
```
In kernel/trace/tracing_map.c (ffffffff811a5a06)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_init
  - kernel/trace/tracing_map.c:tracing_map_init
  - kernel/trace/tracing_map.c:tracing_map_init
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_syscalls.c (ffffffff828ce74d)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:init_ftrace_syscalls
```
```
In kernel/trace/trace_events_filter.c (ffffffff811b54fb)
Location: include/linux/slab.h:685
Inline: True
```
```
In kernel/trace/trace_events_hist.c (ffffffff811c0982)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
```
In kernel/trace/bpf_trace.c (ffffffff811c3096)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
```
In kernel/trace/trace_probe.c (ffffffff811caad5)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
```
```
In kernel/bpf/core.c (ffffffff811d1aa5)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
  - kernel/bpf/core.c:bpf_prog_alloc_jited_linfo
```
```
In kernel/bpf/verifier.c (ffffffff811dfb17)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
```
In kernel/events/core.c (ffffffff81202a97)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/hw_breakpoint.c (ffffffff828d05d2)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
```
```
In kernel/events/uprobes.c (ffffffff8120e63e)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In mm/slab_common.c (ffffffff812424b9)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In mm/list_lru.c (ffffffff81248fbd)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
```
```
In mm/gup.c (ffffffff8124da58)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/vmalloc.c (ffffffff8126affa)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
```
```
In mm/ksm.c (ffffffff812901b5)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - mm/ksm.c:merge_across_nodes_store
```
```
In mm/slub.c (ffffffff81298ab5)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
```
```
In fs/pipe.c (ffffffff812d6d1c)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/splice.c (ffffffff81304488)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:iter_file_splice_write
```
```
In fs/aio.c (ffffffff8132c5c8)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/io_uring.c (ffffffff81331d65)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/proc/proc_sysctl.c (ffffffff81366ba0)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:register_leaf_sysctl_tables
```
```
In fs/ext4/extents.c (ffffffff8137f9b5)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
```
```
In fs/squashfs/block.c (ffffffff813e1afd)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/cache.c (ffffffff813e2b74)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
```
```
In fs/squashfs/file.c (ffffffff813e3946)
Location: include/linux/slab.h:685
Inline: True
```
```
In fs/fuse/file.c (ffffffff8140cef9)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages
```
```
In fs/fuse/inode.c (ffffffff81413d02)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_dev_alloc
```
```
In security/keys/trusted.c (ffffffff828e6a56)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - security/keys/trusted.c:init_trusted
```
```
In security/security.c (ffffffff828e700b)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - security/security.c:ordered_lsm_init
```
```
In security/selinux/ss/policydb.c (ffffffff814565b3)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In security/selinux/ss/services.c (ffffffff8145dd4e)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policy
```
```
In security/apparmor/policy_unpack.c (ffffffff814899b0)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In security/integrity/ima/ima_queue.c (ffffffff828e9aeb)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_init_digests
```
```
In security/integrity/ima/ima_policy.c (ffffffff828ea134)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814c3d84)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
```
```
In block/bio.c (ffffffff828eadc9)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - block/bio.c:init_bio
```
```
In block/partitions/aix.c (ffffffff814e5608)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In lib/mpi/mpiutil.c (ffffffff815386c7)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - lib/mpi/mpiutil.c:mpi_resize
```
```
In drivers/gpio/gpiolib.c (ffffffff8154e2cf)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-devprop.c (ffffffff8154fe57)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
```
```
In drivers/pwm/core.c (ffffffff81555ccb)
Location: include/linux/slab.h:685
Inline: True
```
```
In drivers/pci/msi.c (ffffffff81588fc1)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/pci/msi.c:populate_msi_sysfs
```
```
In drivers/rapidio/rio.c (ffffffff81593f97)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/video/fbdev/core/fbmon.c (ffffffff8159ed4c)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmon.c:fb_edid_add_monspecs
  - drivers/video/fbdev/core/fbmon.c:fb_create_modedb
```
```
In drivers/acpi/sleep.c (ffffffff815b8080)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:lpi_device_get_constraints
```
```
In drivers/acpi/acpi_platform.c (ffffffff815ca8d4)
Location: include/linux/slab.h:685
Inline: True
```
```
In drivers/acpi/sysfs.c (ffffffff815cd82e)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
```
```
In drivers/acpi/acpi_lpat.c (ffffffff815cffe4)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff828f2779)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/acpi/acpi_adxl.c (ffffffff828f2940)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/acpi/acpi_adxl.c:adxl_init
```
```
In drivers/acpi/processor_idle.c (ffffffff81612e84)
Location: include/linux/slab.h:685
Inline: True
```
```
In drivers/clk/clk.c (ffffffff8162e297)
Location: include/linux/slab.h:685
Inline: True
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81634048)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8163d8c1)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
```
In drivers/xen/grant-table.c (ffffffff81640c51)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
```
```
In drivers/xen/events/events_base.c (ffffffff828f69bf)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/mcelog.c (ffffffff81652766)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:bind_virq_for_mce
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81653245)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:push_pxx_to_hypervisor
  - drivers/xen/xen-acpi-processor.c:push_cxx_to_hypervisor
```
```
In drivers/xen/xlate_mmu.c (ffffffff828f771f)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
```
In drivers/tty/tty_io.c (ffffffff816630dc)
Location: include/linux/slab.h:685
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff81683b30)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_core.c:uart_register_driver
```
```
In drivers/char/random.c (ffffffff8169c6d5)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff816ad695)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_pcr_allocation
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816af5a6)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
```
```
In drivers/iommu/dmar.c (ffffffff816c4d6b)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_alloc_dev_scope
```
```
In drivers/iommu/intel-iommu.c (ffffffff816c8190)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_suspend
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:iommu_init_domains
```
```
In drivers/lightnvm/core.c (ffffffff816d2a8b)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/base/property.c (ffffffff816e26d5)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_property_match_string
```
```
In drivers/base/cacheinfo.c (ffffffff816e2f35)
Location: include/linux/slab.h:685
Inline: True
```
```
In drivers/base/swnode.c (ffffffff816e433c)
Location: include/linux/slab.h:685
Inline: True
```
```
In drivers/base/power/clock_ops.c (0)
Location: include/linux/slab.h:685
Inline: True
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff81700e6f)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
```
In drivers/base/regmap/regcache-flat.c (ffffffff81701156)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-flat.c:regcache_flat_init
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff8170419f)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/block/xen-blkfront.c (ffffffff8170d7a6)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
```
In drivers/misc/sram.c (ffffffff81710166)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/mfd/mfd-core.c (ffffffff81720205)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_devices
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81737831)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81742ba0)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/sync_file.c (ffffffff81744cba)
Location: include/linux/slab.h:685
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff81767d78)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
```
```
In drivers/ata/libata-core.c (ffffffff82902305)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_parse_force_param
```
```
In drivers/ata/libata-pmp.c (ffffffff817844f4)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
```
In drivers/spi/spi.c (ffffffff8179109c)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_board_info
```
```
In drivers/net/phy/mdio-boardinfo.c (ffffffff81794165)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/net/phy/mdio-boardinfo.c:mdiobus_register_board_info
```
```
In drivers/net/xen-netfront.c (ffffffff817aaeb5)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
```
```
In drivers/usb/core/hub.c (ffffffff817baf25)
Location: include/linux/slab.h:685
Inline: True
```
```
In drivers/usb/core/quirks.c (ffffffff817cee3f)
Location: include/linux/slab.h:685
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817e3d1f)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817ea8b3)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:find_tt
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817ff89d)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/input/input.c (ffffffff818273c2)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/input/input-mt.c (ffffffff81828eb7)
Location: include/linux/slab.h:685
Inline: True
```
```
In drivers/input/ff-core.c (ffffffff81829507)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff8184d9fc)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:ptp_populate_pin_groups
  - drivers/ptp/ptp_sysfs.c:ptp_populate_pin_groups
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff818584a5)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
```
```
In drivers/thermal/power_allocator.c (ffffffff8185ac5d)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff8185bd88)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
```
In drivers/md/md-bitmap.c (ffffffff81872bfc)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
```
```
In drivers/edac/edac_mc.c (ffffffff81886575)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
```
```
In drivers/opp/core.c (ffffffff8188ceb8)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
```
```
In drivers/opp/cpu.c (ffffffff8188db2c)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81896917)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/slab.h:685
Inline: True
```
```
In drivers/firmware/efi/capsule.c (ffffffff818b6e61)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff8290ece7)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
```
```
In drivers/firmware/efi/apple-properties.c (ffffffff8290f31d)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
```
In drivers/mailbox/pcc.c (ffffffff82910102)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
```
In drivers/extcon/extcon.c (ffffffff818ca017)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In drivers/powercap/powercap_sys.c (ffffffff818cdd92)
Location: include/linux/slab.h:685
Inline: True
```
```
In drivers/nvmem/core.c (ffffffff818d143b)
Location: include/linux/slab.h:685
Inline: True
```
```
In arch/x86/pci/xen.c (ffffffff818d3a7c)
Location: include/linux/slab.h:685
Inline: True
```
```
In net/core/ethtool.c (ffffffff8190a5b0)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_channels
  - net/core/ethtool.c:ethtool_set_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_get_sset_info
```
```
In net/core/rtnetlink.c (ffffffff819179f2)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_register_internal
```
```
In net/core/filter.c (ffffffff8192b934)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - net/core/filter.c:bpf_convert_filter
```
```
In net/sched/sch_mq.c (ffffffff81958e82)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_init
```
```
In net/netlink/af_netlink.c (ffffffff82917513)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_proto_init
```
```
In net/ipv4/route.c (ffffffff82917758)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
```
```
In net/ipv4/fib_frontend.c (ffffffff819c6243)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
```
In net/ipv4/cipso_ipv4.c (ffffffff82918be9)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
```
```
In net/ipv6/route.c (ffffffff81a16e29)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/calipso.c (ffffffff8291a18e)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_init
```
```
In net/packet/af_packet.c (ffffffff81a5884f)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff8291a672)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_init
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff8291a750)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a638ba)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81a6e40d)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
```
```
In net/xdp/xdp_umem.c (ffffffff81a75c83)
Location: include/linux/slab.h:685
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In arch/x86/events/amd/iommu.c (ffffffff828a0495)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:_init_events_attrs
```
```
In arch/x86/events/intel/uncore.c (ffffffff828a2d98)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_types_init
```
```
In arch/x86/hyperv/hv_init.c (ffffffff828a906f)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810451b5)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81052282)
Location: include/linux/slab.h:627
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (ffffffff81054ebe)
Location: include/linux/slab.h:627
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810599d5)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105e76c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
```
```
In arch/x86/kernel/hpet.c (ffffffff828be2ea)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81076d2b)
Location: include/linux/slab.h:627
Inline: True
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff828c898a)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff828c9d0b)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
```
```
In kernel/workqueue.c (ffffffff828cb830)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/sched/fair.c (ffffffff810ecdc5)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/sched/rt.c (ffffffff810f0065)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/sched/rt.c:alloc_rt_sched_group
  - kernel/sched/rt.c:alloc_rt_sched_group
```
```
In kernel/sched/cpupri.c (ffffffff810f62ce)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/cpudeadline.c (ffffffff810f67a9)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_init
```
```
In kernel/sched/debug.c (ffffffff810fcab3)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/irq/affinity.c (ffffffff81121fb2)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/cgroup/rdma.c (ffffffff8116b36c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/auditfilter.c (ffffffff81178529)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_register_class
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8118899a)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
```
```
In kernel/trace/ftrace.c (ffffffff81197fc8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:alloc_ftrace_hash
  - kernel/trace/ftrace.c:ftrace_profile_init
```
```
In kernel/trace/trace.c (ffffffff811ac53e)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/trace.c:create_trace_option_files
  - kernel/trace/trace.c:__tracing_open
```
```
In kernel/trace/tracing_map.c (ffffffff811b1236)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_init
  - kernel/trace/tracing_map.c:tracing_map_init
  - kernel/trace/tracing_map.c:tracing_map_init
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_syscalls.c (ffffffff828d6cab)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:init_ftrace_syscalls
```
```
In kernel/trace/trace_events_filter.c (ffffffff811c0b5b)
Location: include/linux/slab.h:627
Inline: True
```
```
In kernel/trace/trace_events_hist.c (ffffffff811cc232)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
```
In kernel/trace/bpf_trace.c (ffffffff811ce846)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
```
In kernel/trace/trace_probe.c (ffffffff811d6a1f)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
```
```
In kernel/bpf/core.c (ffffffff811de025)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
  - kernel/bpf/core.c:bpf_prog_alloc_jited_linfo
```
```
In kernel/bpf/verifier.c (ffffffff811ec2d7)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
```
In kernel/events/core.c (ffffffff8120fa8b)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/hw_breakpoint.c (ffffffff828d8a0f)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
```
```
In kernel/events/uprobes.c (ffffffff8121bc7e)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In mm/slab_common.c (ffffffff812509d9)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In mm/list_lru.c (ffffffff8125740d)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
```
```
In mm/gup.c (ffffffff8125bf8f)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/vmalloc.c (ffffffff81279f28)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
```
```
In mm/ksm.c (ffffffff8129ff35)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/ksm.c:merge_across_nodes_store
```
```
In mm/slub.c (ffffffff812a8945)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
```
```
In fs/pipe.c (ffffffff812e888c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/splice.c (ffffffff81317508)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:iter_file_splice_write
```
```
In fs/aio.c (ffffffff8133f418)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/io_uring.c (ffffffff81345925)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/proc/proc_sysctl.c (ffffffff8137ee30)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:register_leaf_sysctl_tables
```
```
In fs/ext4/extents.c (ffffffff813980b7)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
```
```
In fs/squashfs/block.c (ffffffff813fbb2d)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/cache.c (ffffffff813fcba4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
```
```
In fs/squashfs/file.c (ffffffff813fd976)
Location: include/linux/slab.h:627
Inline: True
```
```
In fs/fuse/file.c (ffffffff8142bde8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages
```
```
In fs/fuse/inode.c (ffffffff8142dd49)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_dev_alloc
```
```
In security/keys/trusted.c (ffffffff828ef50f)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/keys/trusted.c:init_trusted
```
```
In security/security.c (ffffffff828efc79)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/security.c:ordered_lsm_init
```
```
In security/selinux/ss/policydb.c (ffffffff81470353)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In security/selinux/ss/services.c (ffffffff81477afe)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policy
```
```
In security/apparmor/policy_unpack.c (ffffffff814a3875)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In security/integrity/ima/ima_queue.c (ffffffff828f2782)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_init_digests
```
```
In security/integrity/ima/ima_policy.c (ffffffff828f2dcb)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814dcc64)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
```
```
In block/bio.c (ffffffff828f39bc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - block/bio.c:init_bio
```
```
In block/partitions/aix.c (ffffffff814fe9d8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In lib/mpi/mpiutil.c (ffffffff815594e7)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - lib/mpi/mpiutil.c:mpi_resize
```
```
In drivers/gpio/gpiolib.c (ffffffff8156f4e7)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-devprop.c (ffffffff81571307)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
```
```
In drivers/pwm/core.c (ffffffff8157730b)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/pci/msi.c (ffffffff815aa961)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/pci/msi.c:populate_msi_sysfs
```
```
In drivers/rapidio/rio.c (ffffffff815b50f7)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/video/fbdev/core/fbmon.c (ffffffff815bf305)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmon.c:fb_create_modedb
```
```
In drivers/acpi/sleep.c (ffffffff815d9310)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:lpi_device_get_constraints
```
```
In drivers/acpi/acpi_platform.c (ffffffff815ebb54)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/acpi/sysfs.c (ffffffff815eeaae)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
```
```
In drivers/acpi/acpi_lpat.c (ffffffff815f1254)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff828fb983)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/acpi/acpi_adxl.c (ffffffff828fbb4a)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/acpi/acpi_adxl.c:adxl_init
```
```
In drivers/acpi/processor_idle.c (ffffffff81634384)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/clk/clk.c (ffffffff81651fdf)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81655d78)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8165fda1)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
```
In drivers/xen/grant-table.c (ffffffff81663611)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
```
```
In drivers/xen/events/events_base.c (ffffffff828ffa16)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/mcelog.c (ffffffff81674d06)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:bind_virq_for_mce
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff816757ed)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:push_pxx_to_hypervisor
  - drivers/xen/xen-acpi-processor.c:push_cxx_to_hypervisor
```
```
In drivers/xen/xlate_mmu.c (ffffffff82900763)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
```
In drivers/tty/tty_io.c (ffffffff8168574c)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff816a61de)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_core.c:uart_register_driver
```
```
In drivers/char/random.c (ffffffff816bf445)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff816d0375)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_pcr_allocation
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816d2296)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
```
```
In drivers/iommu/dmar.c (ffffffff816e7c9b)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_alloc_dev_scope
```
```
In drivers/iommu/intel-iommu.c (ffffffff816eb140)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_suspend
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:iommu_init_domains
```
```
In drivers/lightnvm/core.c (ffffffff816f696b)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/base/property.c (ffffffff81706885)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_property_match_string
```
```
In drivers/base/cacheinfo.c (ffffffff817070e5)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/base/swnode.c (ffffffff8170830c)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/base/power/clock_ops.c (0)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff817251bf)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
```
In drivers/base/regmap/regcache-flat.c (ffffffff817254a6)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-flat.c:regcache_flat_init
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff817284ef)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/block/xen-blkfront.c (ffffffff81731aa6)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
```
In drivers/misc/sram.c (ffffffff81734456)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/mfd/mfd-core.c (ffffffff817444d5)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_devices
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8175b5e3)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81766b73)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/sync_file.c (ffffffff81768e6a)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff8178bd68)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
```
```
In drivers/ata/libata-core.c (ffffffff8290b51f)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_parse_force_param
```
```
In drivers/ata/libata-pmp.c (ffffffff817a816b)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
```
In drivers/spi/spi.c (ffffffff817b4c8c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_board_info
```
```
In drivers/net/phy/mdio-boardinfo.c (ffffffff817b7c95)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/net/phy/mdio-boardinfo.c:mdiobus_register_board_info
```
```
In drivers/net/xen-netfront.c (ffffffff817ce8f5)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817d6c5b)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817d8ea5)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
```
```
In drivers/usb/core/hub.c (ffffffff817eb749)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/usb/core/quirks.c (ffffffff817ffc4f)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81814b30)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8181b783)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:find_tt
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff818306fd)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/input/input.c (ffffffff818588f2)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/input/input-mt.c (ffffffff8185a427)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/input/ff-core.c (ffffffff8185ae97)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff8187f43c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:ptp_populate_pin_groups
  - drivers/ptp/ptp_sysfs.c:ptp_populate_pin_groups
```
```
In drivers/hwmon/hwmon.c (ffffffff81884b6a)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81889f55)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
```
```
In drivers/thermal/power_allocator.c (ffffffff8188c76d)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff8188d898)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
```
In drivers/md/md-bitmap.c (ffffffff818a49fc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
```
```
In drivers/edac/edac_mc.c (ffffffff818b8535)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
```
```
In drivers/opp/core.c (ffffffff818bf077)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
```
```
In drivers/opp/cpu.c (ffffffff818bfcbc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818c8927)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818ce090)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
```
In drivers/leds/led-core.c (ffffffff818e46f1)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_get_default_pattern
```
```
In drivers/firmware/efi/capsule.c (ffffffff818e97c1)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff829186b6)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
```
```
In drivers/firmware/efi/apple-properties.c (ffffffff82918cec)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
```
In drivers/mailbox/pcc.c (ffffffff82919e18)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
```
In drivers/extcon/extcon.c (ffffffff818fc467)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In drivers/powercap/powercap_sys.c (ffffffff81900182)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/nvmem/core.c (ffffffff8190383b)
Location: include/linux/slab.h:627
Inline: True
```
```
In arch/x86/pci/xen.c (ffffffff81905dfc)
Location: include/linux/slab.h:627
Inline: True
```
```
In net/core/ethtool.c (ffffffff8193cbb0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_channels
  - net/core/ethtool.c:ethtool_set_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_get_sset_info
```
```
In net/core/rtnetlink.c (ffffffff8194a033)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_register_internal
```
```
In net/core/filter.c (ffffffff8195dc87)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/core/filter.c:bpf_convert_filter
```
```
In net/sched/sch_mq.c (ffffffff8198f322)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_init
```
```
In net/netlink/af_netlink.c (ffffffff82921382)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_proto_init
```
```
In net/ipv4/route.c (ffffffff829215c7)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
```
```
In net/ipv4/fib_frontend.c (ffffffff819fcdf3)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
```
In net/ipv4/cipso_ipv4.c (ffffffff82922a58)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
```
```
In net/ipv6/route.c (ffffffff81a4da6a)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/calipso.c (ffffffff82923ffd)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_init
```
```
In net/packet/af_packet.c (ffffffff81a8e93a)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff829244e1)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_init
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff829245bf)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a9a46a)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81aa4ddd)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
```
```
In net/xdp/xdp_umem.c (ffffffff81aacbf6)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In arch/x86/events/amd/iommu.c (ffffffff82cc68a3)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:_init_events_attrs
```
```
In arch/x86/events/intel/uncore.c (ffffffff82cc8e18)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_type_init
```
```
In arch/x86/hyperv/hv_init.c (ffffffff82cce8ce)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8104835d)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81056d83)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_create_device
```
```
In arch/x86/kernel/cpu/mtrr/if.c (ffffffff81059f5e)
Location: include/linux/slab.h:606
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105eabb)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_setup_mon_state
  - arch/x86/kernel/cpu/resctrl/core.c:domain_setup_mon_state
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff810638f5)
Location: include/linux/slab.h:606
Inline: True
```
```
In arch/x86/kernel/hpet.c (ffffffff82ce287a)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8107dfdc)
Location: include/linux/slab.h:606
Inline: True
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff82cebae2)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff82cec65a)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff810a2c2f)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
```
```
In kernel/workqueue.c (ffffffff82ced7dc)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/sched/fair.c (ffffffff810f6c55)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/sched/cpupri.c (ffffffff810ffc1b)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/cpudeadline.c (ffffffff81100139)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_init
```
```
In kernel/sched/debug.c (ffffffff81107258)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:sd_alloc_ctl_cpu_table
  - kernel/sched/debug.c:sd_alloc_ctl_domain_table
```
```
In kernel/power/energy_model.c (ffffffff8111ca45)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_create_pd
```
```
In kernel/irq/affinity.c (ffffffff8112e6bf)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/cgroup/rdma.c (ffffffff8117ce0a)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/auditfilter.c (ffffffff8118a877)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_init_entry
  - kernel/auditfilter.c:audit_register_class
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8119e119)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
```
```
In kernel/trace/ftrace.c (ffffffff811ad648)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:alloc_ftrace_hash
  - kernel/trace/ftrace.c:ftrace_profile_init
```
```
In kernel/trace/trace.c (ffffffff811be37e)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - kernel/trace/trace.c:create_trace_option_files
  - kernel/trace/trace.c:__tracing_open
```
```
In kernel/trace/tracing_map.c (ffffffff811c91b2)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_elt_alloc
  - kernel/trace/tracing_map.c:tracing_map_elt_alloc
  - kernel/trace/tracing_map.c:tracing_map_elt_alloc
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_syscalls.c (ffffffff82cf68d5)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:init_ftrace_syscalls
```
```
In kernel/trace/trace_events_filter.c (ffffffff811da8d0)
Location: include/linux/slab.h:606
Inline: True
```
```
In kernel/trace/trace_events_synth.c (ffffffff811df72a)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:alloc_synth_event
```
```
In kernel/trace/bpf_trace.c (ffffffff811ead56)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
```
In kernel/trace/trace_probe.c (ffffffff811f331f)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
```
```
In kernel/bpf/core.c (ffffffff811faae5)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
  - kernel/bpf/core.c:bpf_prog_select_runtime
```
```
In kernel/bpf/verifier.c (ffffffff8120b702)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:func_states_equal
```
```
In kernel/bpf/trampoline.c (ffffffff8121ecfd)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_get_progs
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8122f713)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
```
In kernel/events/core.c (ffffffff8123aa5a)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/hw_breakpoint.c (ffffffff82cf7edd)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
```
```
In kernel/events/uprobes.c (ffffffff8124835a)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In kernel/watch_queue.c (ffffffff8124cfff)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_size
```
```
In mm/slab_common.c (ffffffff8127f04d)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In mm/list_lru.c (ffffffff812859c1)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
```
```
In mm/gup.c (ffffffff8128a44f)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/vmalloc.c (ffffffff812aa718)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
```
```
In mm/ksm.c (ffffffff812d4594)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - mm/ksm.c:merge_across_nodes_store
```
```
In mm/slub.c (ffffffff812ddca5)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
```
```
In fs/pipe.c (ffffffff8132087d)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - fs/pipe.c:pipe_resize_ring
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/splice.c (ffffffff81351b11)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:iter_file_splice_write
```
```
In fs/aio.c (ffffffff81377a28)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/io_uring.c (ffffffff8137f378)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:io_sqe_files_register
```
```
In fs/io-wq.c (ffffffff8138b39b)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_create
```
```
In fs/proc/proc_sysctl.c (ffffffff813c8ee0)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:register_leaf_sysctl_tables
```
```
In fs/ext4/extents.c (ffffffff813e3d54)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_precache
```
```
In fs/squashfs/cache.c (ffffffff8144a514)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
```
```
In fs/squashfs/file.c (ffffffff8144afcd)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - fs/squashfs/file.c:empty_meta_index
```
```
In fs/fuse/file.c (ffffffff8147bba8)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages
```
```
In fs/fuse/inode.c (ffffffff8147cfe9)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_dev_alloc
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff82d046df)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:init_digests
```
```
In security/security.c (ffffffff82d04e95)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - security/security.c:ordered_lsm_init
```
```
In security/selinux/ss/hashtab.c (ffffffff814bf6bd)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - security/selinux/ss/hashtab.c:hashtab_init
```
```
In security/selinux/ss/policydb.c (ffffffff814c3817)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In security/selinux/ss/services.c (ffffffff814ccf7e)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policy
```
```
In security/selinux/ss/conditional.c (ffffffff814ceb6b)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_node
  - security/selinux/ss/conditional.c:cond_read_av_list
```
```
In security/apparmor/policy_unpack.c (ffffffff814fd766)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_secmark
  - security/apparmor/policy_unpack.c:unpack_xattrs
  - security/apparmor/policy_unpack.c:unpack_trans_table
```
```
In security/integrity/ima/ima_queue.c (ffffffff82d0773a)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_init_digests
```
```
In security/integrity/ima/ima_crypto.c (ffffffff82d07c3d)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
```
```
In security/integrity/ima/ima_api.c (ffffffff81517f12)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/slab.h:606
Inline: True
```
```
In security/integrity/ima/ima_template.c (ffffffff8151ab7b)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_template_data
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff8153ca34)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
```
```
In block/bio.c (ffffffff82d089e3)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - block/bio.c:init_bio
```
```
In block/partitions/aix.c (ffffffff8155f0e2)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In block/blk-crypto-fallback.c (ffffffff81582117)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
```
```
In lib/mpi/mpiutil.c (ffffffff815e2db7)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - lib/mpi/mpiutil.c:mpi_resize
```
```
In drivers/gpio/gpiolib.c (ffffffff81613b37)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-devprop.c (ffffffff81615855)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
```
```
In drivers/pwm/core.c (ffffffff8161ba7a)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_add_with_polarity
```
```
In drivers/pci/msi.c (ffffffff816536be)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/pci/msi.c:populate_msi_sysfs
```
```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff8165a2ed)
Location: include/linux/slab.h:606
Inline: True
```
```
In drivers/rapidio/rio.c (ffffffff8165e0d7)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/video/fbdev/core/fbmon.c (ffffffff816694b5)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmon.c:fb_create_modedb
```
```
In drivers/acpi/sleep.c (ffffffff81683250)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:lpi_device_get_constraints
```
```
In drivers/acpi/acpi_platform.c (ffffffff816975c4)
Location: include/linux/slab.h:606
Inline: True
```
```
In drivers/acpi/sysfs.c (ffffffff8169aa62)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
```
```
In drivers/acpi/acpi_lpat.c (ffffffff8169d264)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff82d121c3)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/acpi/acpi_adxl.c (ffffffff82d12392)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/acpi/acpi_adxl.c:adxl_init
```
```
In drivers/acpi/processor_idle.c (ffffffff816e13fa)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
```
```
In drivers/clk/clk.c (ffffffff816fd39a)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_populate_parent_map
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81705d04)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8170eee5)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_intx
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
```
```
In drivers/xen/grant-table.c (ffffffff81713721)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
```
```
In drivers/xen/events/events_base.c (ffffffff82d16d99)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/mcelog.c (ffffffff817257d7)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:bind_virq_for_mce
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81726204)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
```
```
In drivers/xen/xlate_mmu.c (ffffffff82d17b5f)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
```
In drivers/tty/tty_io.c (ffffffff81737098)
Location: include/linux/slab.h:606
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff8175b1ed)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_core.c:uart_register_driver
```
```
In drivers/char/random.c (ffffffff817736b5)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81785265)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_pcr_allocation
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81786671)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
```
```
In drivers/iommu/intel/dmar.c (ffffffff8179e7db)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_alloc_dev_scope
```
```
In drivers/iommu/intel/iommu.c (ffffffff817a1a30)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_suspend
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:iommu_init_domains
```
```
In drivers/lightnvm/core.c (ffffffff817af7c7)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_init
  - drivers/lightnvm/core.c:nvm_register_map
  - drivers/lightnvm/core.c:nvm_register_map
  - drivers/lightnvm/core.c:nvm_create_tgt_dev
  - drivers/lightnvm/core.c:nvm_create_tgt_dev
  - drivers/lightnvm/core.c:nvm_create_tgt_dev
```
```
In drivers/base/property.c (ffffffff817c0a65)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_property_match_string
```
```
In drivers/base/cacheinfo.c (ffffffff817c1aa4)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_init
  - drivers/base/cacheinfo.c:detect_cache_attributes
```
```
In drivers/base/swnode.c (ffffffff817c2cce)
Location: include/linux/slab.h:606
Inline: True
```
```
In drivers/base/power/clock_ops.c (0)
Location: include/linux/slab.h:606
Inline: True
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff817e1477)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_node_alloc
```
```
In drivers/base/regmap/regcache-flat.c (ffffffff817e189a)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-flat.c:regcache_flat_init
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff817e4b50)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_np
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_np
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_np
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_np
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_np
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_np
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_np
```
```
In drivers/block/xen-blkfront.c (ffffffff817ee214)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlbd_reserve_minors
```
```
In drivers/misc/sram.c (ffffffff817f1b86)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/mfd/mfd-core.c (ffffffff81801ce6)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8181adf0)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8182723c)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/sync_file.c (ffffffff8182aeca)
Location: include/linux/slab.h:606
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff81850c4f)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl_common
```
```
In drivers/ata/libata-core.c (ffffffff82d20891)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_parse_force_param
```
```
In drivers/ata/libata-pmp.c (ffffffff8186da9d)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
```
In drivers/spi/spi.c (ffffffff8187b87d)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_board_info
```
```
In drivers/net/phy/mdio-boardinfo.c (ffffffff8187ecb5)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/net/phy/mdio-boardinfo.c:mdiobus_register_board_info
```
```
In drivers/net/xen-netfront.c (ffffffff81898575)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a526e)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_try_bus_reset
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff818a676d)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable
```
```
In drivers/usb/core/hub.c (ffffffff818bad61)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/quirks.c (ffffffff818d033d)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/usb/core/quirks.c:quirks_param_set
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818e5de5)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818ecc93)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:find_tt
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81901a2a)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/input/input.c (ffffffff81929b19)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_abs_params
```
```
In drivers/input/input-mt.c (ffffffff8192d04d)
Location: include/linux/slab.h:606
Inline: True
```
```
In drivers/input/ff-core.c (ffffffff8192d6c9)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81932186)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_get_keymap_from_fwnode
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff8194d936)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:ptp_populate_pin_groups
  - drivers/ptp/ptp_sysfs.c:ptp_populate_pin_groups
```
```
In drivers/hwmon/hwmon.c (ffffffff81953ad8)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_create_attrs
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81958d95)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:create_trip_attrs
  - drivers/thermal/thermal_sysfs.c:create_trip_attrs
  - drivers/thermal/thermal_sysfs.c:create_trip_attrs
  - drivers/thermal/thermal_sysfs.c:create_trip_attrs
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff8195b7a6)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:allocate_power
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff8195c0ec)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables
```
```
In drivers/md/md-bitmap.c (ffffffff819743bf)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
```
```
In drivers/edac/edac_mc.c (ffffffff819883c3)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_alloc_dimms
  - drivers/edac/edac_mc.c:edac_mc_alloc_csrows
  - drivers/edac/edac_mc.c:edac_mc_alloc_csrows
```
```
In drivers/opp/core.c (ffffffff819906e0)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
```
```
In drivers/opp/cpu.c (ffffffff81991a1c)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8199ab77)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8199fff0)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
```
In drivers/leds/led-core.c (ffffffff819b7371)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_get_default_pattern
```
```
In drivers/firmware/efi/capsule.c (ffffffff819bceed)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff82d2abea)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
```
```
In drivers/firmware/efi/apple-properties.c (ffffffff82d2b329)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
```
In drivers/mailbox/pcc.c (ffffffff82d2c2e3)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
```
In drivers/extcon/extcon.c (ffffffff819d3049)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In drivers/powercap/powercap_sys.c (ffffffff819d71ea)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:powercap_register_zone
  - drivers/powercap/powercap_sys.c:powercap_register_zone
```
```
In drivers/nvmem/core.c (ffffffff819dabc5)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_add_cells
```
```
In net/core/rtnetlink.c (ffffffff81a19683)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_register_internal
```
```
In net/core/filter.c (ffffffff81a28b23)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - net/core/filter.c:bpf_convert_filter
```
```
In net/sched/sch_mq.c (ffffffff81a67022)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_init
```
```
In net/sched/cls_api.c (ffffffff81a6bf72)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_gate_get_list
```
```
In net/netlink/af_netlink.c (ffffffff82d2d928)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_proto_init
```
```
In net/ethtool/ioctl.c (ffffffff81a833b0)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_set_rxfh_indir
  - net/ethtool/ioctl.c:ethtool_get_rxfh_indir
  - net/ethtool/ioctl.c:ethtool_get_rxnfc
  - net/ethtool/ioctl.c:ethtool_get_sset_info
```
```
In net/ethtool/common.c (ffffffff81a856a7)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - net/ethtool/common.c:ethtool_get_max_rxfh_channel
```
```
In net/ethtool/strset.c (ffffffff81a8849b)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_prepare_data
```
```
In net/ethtool/privflags.c (ffffffff81a8a3ef)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - net/ethtool/privflags.c:ethnl_get_priv_flags_info
```
```
In net/ipv4/route.c (ffffffff82d2dbaa)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
```
```
In net/ipv4/fib_frontend.c (ffffffff81aeaf00)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
```
```
In net/ipv4/cipso_ipv4.c (ffffffff82d2f041)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
```
```
In net/ipv6/route.c (ffffffff81b43d84)
Location: include/linux/slab.h:606
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff82d30375)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_init
```
```
In net/packet/af_packet.c (ffffffff81b85b05)
Location: include/linux/slab.h:606
Inline: True
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff82d30736)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_init
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff82d30814)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b95d03)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81ba031b)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
```
```
In net/xdp/xdp_umem.c (ffffffff81ba82b5)
Location: include/linux/slab.h:606
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_pin_pages
```
```
In arch/x86/pci/xen.c (ffffffff81bb63a5)
Location: include/linux/slab.h:606
Inline: True
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
In arch/x86/events/amd/iommu.c (ffffffff82fb22c0)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:_init_events_attrs
```
```
In arch/x86/events/intel/uncore.c (ffffffff82fb4c32)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_type_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101fa54)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:skx_iio_set_mapping
  - arch/x86/events/intel/uncore_snbep.c:skx_iio_set_mapping
  - arch/x86/events/intel/uncore_snbep.c:skx_iio_get_topology
```
```
In arch/x86/hyperv/hv_init.c (ffffffff82fba748)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8104784d)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81055cb3)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_create_device
```
```
In arch/x86/kernel/cpu/mtrr/if.c (ffffffff81058ace)
Location: include/linux/slab.h:619
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105cfdb)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_setup_mon_state
  - arch/x86/kernel/cpu/resctrl/core.c:domain_setup_mon_state
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81061d18)
Location: include/linux/slab.h:619
Inline: True
```
```
In arch/x86/kernel/hpet.c (ffffffff82fcfb17)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8107dc9c)
Location: include/linux/slab.h:619
Inline: True
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff82fd8cb0)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff8109e4f0)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
```
```
In kernel/workqueue.c (ffffffff82fd9e36)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/sched/fair.c (ffffffff810f4e35)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/sched/cpupri.c (ffffffff810fe6eb)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/cpudeadline.c (ffffffff810fec99)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_init
```
```
In kernel/sched/debug.c (ffffffff81105a68)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:sd_alloc_ctl_cpu_table
  - kernel/sched/debug.c:sd_alloc_ctl_domain_table
  - kernel/sched/debug.c:sd_ctl_doflags
```
```
In kernel/power/energy_model.c (ffffffff811174d7)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_create_perf_table
```
```
In kernel/irq/affinity.c (ffffffff8112a2af)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/dma/direct.c (ffffffff811399e5)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_set_offset
```
```
In kernel/cgroup/rdma.c (ffffffff81179c6a)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/auditfilter.c (ffffffff81187ae7)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_init_entry
  - kernel/auditfilter.c:audit_register_class
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8119b15e)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
```
```
In kernel/trace/ftrace.c (ffffffff811aaf58)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:alloc_ftrace_hash
  - kernel/trace/ftrace.c:ftrace_profile_init
```
```
In kernel/trace/trace.c (ffffffff811bbfae)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - kernel/trace/trace.c:create_trace_option_files
  - kernel/trace/trace.c:__tracing_open
```
```
In kernel/trace/tracing_map.c (ffffffff811c6872)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_elt_alloc
  - kernel/trace/tracing_map.c:tracing_map_elt_alloc
  - kernel/trace/tracing_map.c:tracing_map_elt_alloc
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_syscalls.c (ffffffff82fe33c6)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:init_ftrace_syscalls
```
```
In kernel/trace/trace_events_filter.c (ffffffff811d7a00)
Location: include/linux/slab.h:619
Inline: True
```
```
In kernel/trace/trace_events_synth.c (ffffffff811dceea)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:alloc_synth_event
  - kernel/trace/trace_events_synth.c:alloc_synth_event
```
```
In kernel/trace/bpf_trace.c (ffffffff811e8ef6)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
```
In kernel/trace/trace_probe.c (ffffffff811f1ccf)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
```
```
In kernel/bpf/core.c (ffffffff811f9d3e)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
  - kernel/bpf/core.c:bpf_prog_select_runtime
```
```
In kernel/bpf/verifier.c (ffffffff8120d918)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:func_states_equal
```
```
In kernel/bpf/trampoline.c (ffffffff8122243d)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_get_progs
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff81237c13)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
```
In kernel/events/core.c (ffffffff81243e86)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/hw_breakpoint.c (ffffffff82fe4bd6)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
```
```
In kernel/events/uprobes.c (ffffffff81252a6a)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In kernel/watch_queue.c (ffffffff8125745f)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_size
```
```
In mm/slab_common.c (ffffffff81288ddd)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In mm/list_lru.c (ffffffff8128fc81)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
```
```
In mm/vmalloc.c (ffffffff812b5dde)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
```
```
In mm/ksm.c (ffffffff812dff74)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - mm/ksm.c:merge_across_nodes_store
```
```
In mm/slub.c (ffffffff812e8bc5)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
```
```
In fs/pipe.c (ffffffff8132bdfd)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - fs/pipe.c:pipe_resize_ring
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/splice.c (ffffffff8135e92c)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:iter_file_splice_write
```
```
In fs/aio.c (ffffffff813853b9)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/io_uring.c (ffffffff8138d825)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:io_sqe_files_register
```
```
In fs/io-wq.c (ffffffff8139c54a)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_create
```
```
In fs/proc/proc_sysctl.c (ffffffff813daed0)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:register_leaf_sysctl_tables
```
```
In fs/ext4/extents.c (ffffffff813f5592)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_precache
```
```
In fs/squashfs/cache.c (ffffffff81466c04)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
```
```
In fs/squashfs/file.c (ffffffff814676ad)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - fs/squashfs/file.c:empty_meta_index
```
```
In fs/fuse/file.c (ffffffff81496a05)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages
```
```
In fs/fuse/inode.c (ffffffff81497f79)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_dev_alloc
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff82ff1aac)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:init_digests
```
```
In security/security.c (ffffffff82ff2262)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - security/security.c:ordered_lsm_init
```
```
In security/selinux/ss/hashtab.c (ffffffff814dd22e)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - security/selinux/ss/hashtab.c:hashtab_duplicate
  - security/selinux/ss/hashtab.c:hashtab_init
```
```
In security/selinux/ss/policydb.c (ffffffff814e18c7)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In security/selinux/ss/services.c (ffffffff814ea6b6)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
```
```
In security/selinux/ss/conditional.c (ffffffff814eb8df)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:duplicate_policydb_cond_list
  - security/selinux/ss/conditional.c:duplicate_policydb_cond_list
  - security/selinux/ss/conditional.c:cond_dup_av_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_node
  - security/selinux/ss/conditional.c:cond_read_av_list
```
```
In security/apparmor/policy_unpack.c (ffffffff8151a9c6)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_secmark
  - security/apparmor/policy_unpack.c:unpack_xattrs
  - security/apparmor/policy_unpack.c:unpack_trans_table
```
```
In security/integrity/ima/ima_queue.c (ffffffff82ff4bf9)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_init_digests
```
```
In security/integrity/ima/ima_crypto.c (ffffffff82ff512a)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
```
```
In security/integrity/ima/ima_api.c (ffffffff81534ee2)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/slab.h:619
Inline: True
```
```
In security/integrity/ima/ima_template.c (ffffffff81537adb)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_template_data
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff81559594)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
```
```
In block/bio.c (ffffffff82ff5f92)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - block/bio.c:init_bio
```
```
In block/partitions/aix.c (ffffffff8157aca2)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In block/blk-crypto-fallback.c (ffffffff8159f0e7)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
```
```
In lib/mpi/mpi-mod.c (ffffffff81603ed8)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - lib/mpi/mpi-mod.c:mpi_barrett_init
```
```
In lib/mpi/mpiutil.c (ffffffff81606d25)
Location: include/linux/slab.h:619
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff81638a86)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/pwm/core.c (ffffffff8164216a)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_add_with_polarity
```
```
In drivers/pci/msi.c (ffffffff8165d5be)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/pci/msi.c:populate_msi_sysfs
```
```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff8167a55d)
Location: include/linux/slab.h:619
Inline: True
```
```
In drivers/rapidio/rio.c (ffffffff8167e6f7)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/video/fbdev/core/fbmon.c (ffffffff81689f25)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmon.c:fb_create_modedb
```
```
In drivers/acpi/acpi_platform.c (ffffffff816b4714)
Location: include/linux/slab.h:619
Inline: True
```
```
In drivers/acpi/sysfs.c (ffffffff816b7ae2)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
```
```
In drivers/acpi/x86/s2idle.c (ffffffff816ba120)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
```
```
In drivers/acpi/acpi_lpat.c (ffffffff816bab54)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff82fffc97)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/acpi/acpi_adxl.c (ffffffff82fffe66)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/acpi/acpi_adxl.c:adxl_init
```
```
In drivers/acpi/processor_idle.c (ffffffff816ff15a)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
```
```
In drivers/clk/clk.c (ffffffff8171a34a)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_populate_parent_map
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81722fa4)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8172bcc0)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_intx
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
```
```
In drivers/xen/grant-table.c (ffffffff81730611)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
```
```
In drivers/xen/events/events_base.c (ffffffff83004989)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/mcelog.c (ffffffff81c05bb6)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:bind_virq_for_mce
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81c06361)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
```
```
In drivers/xen/xlate_mmu.c (ffffffff8300574d)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
```
In drivers/regulator/core.c (ffffffff8174c222)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/tty/tty_io.c (ffffffff81753458)
Location: include/linux/slab.h:619
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff817762cd)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_core.c:uart_register_driver
```
```
In drivers/char/random.c (ffffffff8178e675)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff8179c6a5)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_pcr_allocation
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff8179d871)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
```
```
In drivers/iommu/intel/dmar.c (ffffffff817ac52b)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_alloc_dev_scope
```
```
In drivers/iommu/intel/iommu.c (ffffffff817af400)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_suspend
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:iommu_init_domains
```
```
In drivers/lightnvm/core.c (ffffffff817c4347)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_init
  - drivers/lightnvm/core.c:nvm_register_map
  - drivers/lightnvm/core.c:nvm_register_map
  - drivers/lightnvm/core.c:nvm_create_tgt_dev
  - drivers/lightnvm/core.c:nvm_create_tgt_dev
  - drivers/lightnvm/core.c:nvm_create_tgt_dev
```
```
In drivers/base/property.c (ffffffff817d5905)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_property_match_string
```
```
In drivers/base/cacheinfo.c (ffffffff817d6cc4)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_init
  - drivers/base/cacheinfo.c:detect_cache_attributes
```
```
In drivers/base/swnode.c (ffffffff817d7ade)
Location: include/linux/slab.h:619
Inline: True
```
```
In drivers/base/power/clock_ops.c (0)
Location: include/linux/slab.h:619
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffffffff817ef599)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_field_bulk_alloc
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff817f61c7)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_node_alloc
```
```
In drivers/base/regmap/regcache-flat.c (ffffffff817f65ca)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-flat.c:regcache_flat_init
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff817f9a10)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
```
```
In drivers/block/xen-blkfront.c (ffffffff81802b18)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlbd_reserve_minors
```
```
In drivers/misc/sram.c (ffffffff818061b6)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/mfd/mfd-core.c (ffffffff81812aa6)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81829f10)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81837cdc)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/sync_file.c (ffffffff8183bb7a)
Location: include/linux/slab.h:619
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff818610ac)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl_common
```
```
In drivers/ata/libata-core.c (ffffffff8300e670)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_parse_force_param
```
```
In drivers/ata/libata-pmp.c (ffffffff8187c76d)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
```
In drivers/spi/spi.c (ffffffff8188aa5d)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_board_info
```
```
In drivers/net/phy/mdio-boardinfo.c (ffffffff8188d1f8)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/net/phy/mdio-boardinfo.c:mdiobus_register_board_info
```
```
In drivers/net/xen-netfront.c (ffffffff818a6935)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b43ae)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_try_bus_reset
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff818b565d)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable
```
```
In drivers/usb/core/hub.c (ffffffff81c1b88a)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/quirks.c (ffffffff818da79d)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/usb/core/quirks.c:quirks_param_set
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818ef8c6)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818f5b1e)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:find_tt
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8190a2f6)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/input/input.c (ffffffff81931089)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_abs_params
```
```
In drivers/input/input-mt.c (ffffffff8193450e)
Location: include/linux/slab.h:619
Inline: True
```
```
In drivers/input/ff-core.c (ffffffff81934a99)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (ffffffff819393e6)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_get_keymap_from_fwnode
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff81953326)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:ptp_populate_pin_groups
  - drivers/ptp/ptp_sysfs.c:ptp_populate_pin_groups
```
```
In drivers/hwmon/hwmon.c (ffffffff819588f8)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_create_attrs
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff8195e435)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:create_trip_attrs
  - drivers/thermal/thermal_sysfs.c:create_trip_attrs
  - drivers/thermal/thermal_sysfs.c:create_trip_attrs
  - drivers/thermal/thermal_sysfs.c:create_trip_attrs
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff81962420)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:allocate_power
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff81962a2e)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables
```
```
In drivers/md/md-bitmap.c (ffffffff819792bf)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
```
```
In drivers/edac/edac_mc.c (ffffffff8198cd13)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_alloc_dimms
  - drivers/edac/edac_mc.c:edac_mc_alloc_csrows
  - drivers/edac/edac_mc.c:edac_mc_alloc_csrows
```
```
In drivers/opp/core.c (ffffffff819945e9)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
```
```
In drivers/opp/cpu.c (ffffffff81994cfc)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8199dce0)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff819a2e16)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
```
In drivers/leds/led-core.c (ffffffff819b9871)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_get_default_pattern
```
```
In drivers/firmware/efi/capsule.c (ffffffff819becaa)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff8301931b)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
```
```
In drivers/firmware/efi/apple-properties.c (ffffffff83019a71)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
```
In drivers/mailbox/pcc.c (ffffffff8301acef)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
```
In drivers/extcon/extcon.c (ffffffff819d2c40)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In drivers/powercap/powercap_sys.c (ffffffff819d65ea)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:powercap_register_zone
  - drivers/powercap/powercap_sys.c:powercap_register_zone
```
```
In drivers/nvmem/core.c (ffffffff819d9a79)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_add_cells
```
```
In net/core/rtnetlink.c (ffffffff81a19873)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_register_internal
```
```
In net/core/filter.c (ffffffff81a29443)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - net/core/filter.c:bpf_convert_filter
```
```
In net/sched/sch_mq.c (ffffffff81a6efd2)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_init
```
```
In net/sched/cls_api.c (ffffffff81a74812)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_gate_get_list
```
```
In net/netlink/af_netlink.c (ffffffff8301c47c)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_proto_init
```
```
In net/ethtool/ioctl.c (ffffffff81a8ce80)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_set_rxfh_indir
  - net/ethtool/ioctl.c:ethtool_get_rxfh_indir
  - net/ethtool/ioctl.c:ethtool_get_rxnfc
  - net/ethtool/ioctl.c:ethtool_get_sset_info
```
```
In net/ethtool/common.c (ffffffff81a8f037)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - net/ethtool/common.c:ethtool_get_max_rxfh_channel
```
```
In net/ethtool/strset.c (ffffffff81a91e08)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_prepare_data
```
```
In net/ethtool/privflags.c (ffffffff81a93c4f)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - net/ethtool/privflags.c:ethnl_get_priv_flags_info
```
```
In net/ipv4/route.c (ffffffff8301c700)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
```
```
In net/ipv4/fib_frontend.c (ffffffff81af7dd0)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8301dc33)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
```
```
In net/ipv6/route.c (ffffffff81b5248a)
Location: include/linux/slab.h:619
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81b7b6a2)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/calipso.c (ffffffff8301ef45)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_init
```
```
In net/packet/af_packet.c (ffffffff81b95518)
Location: include/linux/slab.h:619
Inline: True
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff8301f306)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_init
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff8301f3e4)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ba5973)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81bafcfb)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
```
```
In net/xdp/xdp_umem.c (ffffffff81bb7ff5)
Location: include/linux/slab.h:619
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_pin_pages
```
```
In arch/x86/pci/xen.c (ffffffff81bcb519)
Location: include/linux/slab.h:619
Inline: True
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
In arch/x86/events/amd/iommu.c (ffffffff831bc497)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:_init_events_attrs
```
```
In arch/x86/events/intel/core.c (ffffffff831bdb78)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff831bf1a3)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_type_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff810207e8)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:skx_iio_set_mapping
  - arch/x86/events/intel/uncore_snbep.c:skx_iio_set_mapping
  - arch/x86/events/intel/uncore_snbep.c:skx_iio_set_mapping
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81021a48)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_init_uncores
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
```
```
In arch/x86/hyperv/hv_init.c (ffffffff831c4e16)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff8103409f)
Location: include/linux/slab.h:623
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8104906d)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81057533)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_create_device
```
```
In arch/x86/kernel/cpu/mtrr/if.c (ffffffff8105943a)
Location: include/linux/slab.h:623
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105dada)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff810624e8)
Location: include/linux/slab.h:623
Inline: True
```
```
In arch/x86/kernel/hpet.c (ffffffff831da60d)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8107edbc)
Location: include/linux/slab.h:623
Inline: True
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff831e352d)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff8109f1db)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
```
```
In kernel/workqueue.c (ffffffff831e47ed)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/sched/fair.c (ffffffff810f6f25)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/sched/cpupri.c (ffffffff81100acb)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/cpudeadline.c (ffffffff8110107b)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_init
```
```
In kernel/sched/topology.c (ffffffff81103368)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
```
```
In kernel/power/energy_model.c (ffffffff81117a97)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_create_perf_table
```
```
In kernel/irq/affinity.c (ffffffff8112a52f)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/dma/direct.c (ffffffff8113aad5)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_set_offset
```
```
In kernel/cgroup/rdma.c (ffffffff8117a7f6)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/auditfilter.c (ffffffff81188b47)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_init_entry
  - kernel/auditfilter.c:audit_register_class
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8119c034)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
```
```
In kernel/trace/ftrace.c (ffffffff811aba18)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:alloc_ftrace_hash
  - kernel/trace/ftrace.c:ftrace_profile_init
```
```
In kernel/trace/trace.c (ffffffff811bb7ee)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - kernel/trace/trace.c:create_trace_option_files
  - kernel/trace/trace.c:__tracing_open
```
```
In kernel/trace/tracing_map.c (ffffffff811c78cf)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_alloc_elts
  - kernel/trace/tracing_map.c:tracing_map_alloc_elts
  - kernel/trace/tracing_map.c:tracing_map_alloc_elts
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_syscalls.c (ffffffff831edb38)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:init_ftrace_syscalls
```
```
In kernel/trace/trace_events_filter.c (ffffffff811d8cf0)
Location: include/linux/slab.h:623
Inline: True
```
```
In kernel/trace/trace_events_synth.c (ffffffff811de14a)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:alloc_synth_event
  - kernel/trace/trace_events_synth.c:alloc_synth_event
```
```
In kernel/trace/bpf_trace.c (ffffffff811e9de6)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
```
In kernel/trace/trace_probe.c (ffffffff811f2b6f)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
```
```
In kernel/bpf/core.c (ffffffff811facae)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
```
```
In kernel/bpf/verifier.c (ffffffff8120f56f)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
```
In kernel/bpf/trampoline.c (ffffffff8122741f)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8123c433)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
```
In kernel/events/core.c (ffffffff81248db9)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/hw_breakpoint.c (ffffffff831ef302)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
```
```
In kernel/events/uprobes.c (ffffffff81256acc)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In kernel/watch_queue.c (ffffffff8125b8df)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_size
```
```
In mm/slab_common.c (ffffffff8128e49d)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In mm/list_lru.c (ffffffff812953f1)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
```
```
In mm/vmalloc.c (ffffffff812bb4d1)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
```
```
In mm/ksm.c (ffffffff812e7194)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - mm/ksm.c:merge_across_nodes_store
```
```
In mm/slub.c (ffffffff812f0cd5)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
```
```
In fs/pipe.c (ffffffff81331e3d)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - fs/pipe.c:pipe_resize_ring
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/splice.c (ffffffff813649b4)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:iter_file_splice_write
```
```
In fs/aio.c (ffffffff8138c166)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/io_uring.c (ffffffff81398589)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffers_register
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:io_sqe_files_register
```
```
In fs/io-wq.c (ffffffff813a369f)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_create
```
```
In fs/proc/proc_sysctl.c (ffffffff813e1e00)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:register_leaf_sysctl_tables
```
```
In fs/ext4/extents.c (ffffffff813fb8cc)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_precache
```
```
In fs/squashfs/cache.c (ffffffff8146c315)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
```
```
In fs/squashfs/file.c (ffffffff8146cc7a)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - fs/squashfs/file.c:empty_meta_index
```
```
In fs/fuse/file.c (ffffffff8149ba95)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages
```
```
In fs/fuse/inode.c (ffffffff8149d1a9)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_dev_alloc
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff831fc433)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:init_digests
```
```
In security/security.c (ffffffff831fcbfc)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - security/security.c:ordered_lsm_init
```
```
In security/selinux/ss/hashtab.c (ffffffff814e3b9e)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - security/selinux/ss/hashtab.c:hashtab_duplicate
  - security/selinux/ss/hashtab.c:hashtab_init
```
```
In security/selinux/ss/policydb.c (ffffffff814e7ba7)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In security/selinux/ss/services.c (ffffffff814f1316)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
```
```
In security/selinux/ss/conditional.c (ffffffff814f30a8)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_policydb_dup
  - security/selinux/ss/conditional.c:cond_policydb_dup
  - security/selinux/ss/conditional.c:cond_dup_av_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_av_list
```
```
In security/apparmor/policy_unpack.c (ffffffff815212c6)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_secmark
  - security/apparmor/policy_unpack.c:unpack_xattrs
  - security/apparmor/policy_unpack.c:unpack_trans_table
```
```
In security/integrity/ima/ima_queue.c (ffffffff831ff8fb)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_init_digests
```
```
In security/integrity/ima/ima_crypto.c (ffffffff831ffe3c)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
```
```
In security/integrity/ima/ima_api.c (ffffffff8153d51b)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/slab.h:623
Inline: True
```
```
In security/integrity/ima/ima_template.c (ffffffff815400d4)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_template_data
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff81561ebb)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
```
```
In block/partitions/aix.c (ffffffff815829d2)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In block/blk-crypto-fallback.c (ffffffff815a5f17)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
```
```
In lib/mpi/mpi-mod.c (ffffffff815e6c58)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - lib/mpi/mpi-mod.c:mpi_barrett_init
```
```
In lib/mpi/mpiutil.c (ffffffff815e9a85)
Location: include/linux/slab.h:623
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff8161c593)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/pwm/core.c (ffffffff816250a6)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_add
```
```
In drivers/pci/msi.c (ffffffff8163fa1e)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/pci/msi.c:populate_msi_sysfs
```
```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff8165d05d)
Location: include/linux/slab.h:623
Inline: True
```
```
In drivers/rapidio/rio.c (ffffffff81661577)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/video/fbdev/core/fbmon.c (ffffffff8166cb55)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmon.c:fb_create_modedb
```
```
In drivers/acpi/acpi_platform.c (ffffffff81696944)
Location: include/linux/slab.h:623
Inline: True
```
```
In drivers/acpi/sysfs.c (ffffffff81699b42)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
```
```
In drivers/acpi/x86/s2idle.c (ffffffff8169c020)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
```
```
In drivers/acpi/acpi_lpat.c (ffffffff8169ca84)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff8320ad83)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/acpi/acpi_adxl.c (ffffffff8320af4e)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/acpi/acpi_adxl.c:adxl_init
```
```
In drivers/acpi/processor_idle.c (ffffffff816e0d0a)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
```
```
In drivers/clk/clk.c (ffffffff816fb63d)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_populate_parent_map
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81704204)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8170fab1)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
```
```
In drivers/xen/grant-table.c (ffffffff817141b1)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
```
```
In drivers/xen/events/events_base.c (ffffffff8320f441)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/mcelog.c (ffffffff81bf7861)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:bind_virq_for_mce
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81bf7ff3)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
```
```
In drivers/xen/xlate_mmu.c (ffffffff832102f4)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
```
In drivers/regulator/core.c (ffffffff8172fa32)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/tty/tty_io.c (ffffffff81735cfc)
Location: include/linux/slab.h:623
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff81759a58)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_core.c:uart_register_driver
```
```
In drivers/char/random.c (ffffffff81770ed5)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff8177f1d5)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_pcr_allocation
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff8178035d)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
```
```
In drivers/iommu/intel/dmar.c (ffffffff8178f3fb)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_alloc_dev_scope
```
```
In drivers/iommu/intel/iommu.c (ffffffff817918e9)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_suspend
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:iommu_init_domains
```
```
In drivers/lightnvm/core.c (ffffffff817a8254)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_init
  - drivers/lightnvm/core.c:nvm_init
  - drivers/lightnvm/core.c:nvm_init
  - drivers/lightnvm/core.c:nvm_create_tgt_dev
  - drivers/lightnvm/core.c:nvm_create_tgt_dev
  - drivers/lightnvm/core.c:nvm_create_tgt_dev
```
```
In drivers/base/property.c (ffffffff817b9315)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_property_match_string
```
```
In drivers/base/cacheinfo.c (ffffffff817bac89)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_add_dev
```
```
In drivers/base/swnode.c (ffffffff817bb6be)
Location: include/linux/slab.h:623
Inline: True
```
```
In drivers/base/power/clock_ops.c (0)
Location: include/linux/slab.h:623
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffffffff817d3e39)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_field_bulk_alloc
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff817daae1)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
```
In drivers/base/regmap/regcache-flat.c (ffffffff817dad36)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-flat.c:regcache_flat_init
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff817de54c)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
```
```
In drivers/block/xen-blkfront.c (ffffffff817e8e71)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlbd_reserve_minors
```
```
In drivers/misc/sram.c (ffffffff817eacc6)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/mfd/mfd-core.c (ffffffff817f71b6)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8180d1ef)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8181afc7)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/sync_file.c (ffffffff8181eda1)
Location: include/linux/slab.h:623
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff81843d25)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl_common
```
```
In drivers/ata/libata-core.c (ffffffff83219604)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_parse_force_param
```
```
In drivers/ata/libata-pmp.c (ffffffff8185efdd)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
```
In drivers/spi/spi.c (ffffffff8186d3f7)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_board_info
```
```
In drivers/net/phy/mdio-boardinfo.c (ffffffff8186fb38)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/net/phy/mdio-boardinfo.c:mdiobus_register_board_info
```
```
In drivers/net/xen-netfront.c (ffffffff81889cf2)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818976f8)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_try_bus_reset
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff81898afe)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable
```
```
In drivers/usb/core/hub.c (ffffffff81c0d762)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/quirks.c (ffffffff818bdbfd)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/usb/core/quirks.c:quirks_param_set
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818d2fe7)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818d93be)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:find_tt
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff818ee8ae)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/input/input.c (ffffffff81914309)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/input/input-mt.c (ffffffff8191787d)
Location: include/linux/slab.h:623
Inline: True
```
```
In drivers/input/ff-core.c (ffffffff81917dda)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8191cb06)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_get_keymap_from_fwnode
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff819371b6)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:ptp_populate_pin_groups
  - drivers/ptp/ptp_sysfs.c:ptp_populate_pin_groups
```
```
In drivers/hwmon/hwmon.c (ffffffff8193c250)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81941955)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:create_trip_attrs
  - drivers/thermal/thermal_sysfs.c:create_trip_attrs
  - drivers/thermal/thermal_sysfs.c:create_trip_attrs
  - drivers/thermal/thermal_sysfs.c:create_trip_attrs
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff81945846)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:allocate_power
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff8194602e)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables
```
```
In drivers/md/md-bitmap.c (ffffffff8195d87c)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
```
```
In drivers/edac/edac_mc.c (ffffffff819712e3)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_alloc_dimms
```
```
In drivers/opp/core.c (ffffffff81978bab)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
```
```
In drivers/opp/cpu.c (ffffffff81979c3c)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff819828b8)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81987916)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
```
In drivers/mmc/core/host.c (ffffffff81991190)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_of_parse_voltage
```
```
In drivers/leds/led-core.c (ffffffff8199e061)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_get_default_pattern
```
```
In drivers/firmware/efi/capsule.c (ffffffff819a33ab)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff83224300)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
```
```
In drivers/firmware/efi/apple-properties.c (ffffffff83224ab9)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
```
In drivers/mailbox/pcc.c (ffffffff83225d59)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
```
In drivers/extcon/extcon.c (ffffffff819b7eed)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In drivers/powercap/powercap_sys.c (ffffffff819bc6ba)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:powercap_register_zone
  - drivers/powercap/powercap_sys.c:powercap_register_zone
```
```
In drivers/nvmem/core.c (ffffffff819bf5d9)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_add_cells
```
```
In net/core/rtnetlink.c (ffffffff81a007b3)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_register_internal
```
```
In net/core/filter.c (ffffffff81a10737)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - net/core/filter.c:bpf_convert_filter
```
```
In net/sched/sch_mq.c (ffffffff81a57892)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_init
```
```
In net/sched/cls_api.c (ffffffff81a5d392)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_gate_get_list
```
```
In net/netlink/af_netlink.c (ffffffff832275bd)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_proto_init
```
```
In net/ethtool/ioctl.c (ffffffff81a76181)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_self_test
  - net/ethtool/ioctl.c:ethtool_set_rxfh_indir
  - net/ethtool/ioctl.c:ethtool_get_rxfh_indir
  - net/ethtool/ioctl.c:ethtool_get_rxnfc
  - net/ethtool/ioctl.c:ethtool_get_sset_info
```
```
In net/ethtool/common.c (ffffffff81a78737)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - net/ethtool/common.c:ethtool_get_max_rxfh_channel
```
```
In net/ethtool/strset.c (ffffffff81a7b011)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_prepare_set
```
```
In net/ethtool/privflags.c (ffffffff81a7d64f)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - net/ethtool/privflags.c:ethnl_get_priv_flags_info
```
```
In net/ipv4/route.c (ffffffff81a87b03)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae34e0)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
```
```
In net/ipv4/cipso_ipv4.c (ffffffff83228d40)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
```
```
In net/ipv6/route.c (ffffffff81b3fe38)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/exthdrs.c (ffffffff81b6a165)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/calipso.c (ffffffff8322a081)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_init
```
```
In net/packet/af_packet.c (ffffffff81b84608)
Location: include/linux/slab.h:623
Inline: True
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff8322a442)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_init
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff8322a520)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b94ae3)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81b9ee3b)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
```
```
In net/xdp/xdp_umem.c (ffffffff81ba71c5)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_pin_pages
```
```
In arch/x86/pci/xen.c (ffffffff81bbee69)
Location: include/linux/slab.h:623
Inline: True
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
In arch/x86/events/amd/iommu.c (ffffffff8329c763)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:_init_events_attrs
```
```
In arch/x86/events/intel/core.c (ffffffff8329df39)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff8329f5f1)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_type_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102445d)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:pmu_iio_set_mapping
  - arch/x86/events/intel/uncore_snbep.c:pmu_iio_set_mapping
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81025f73)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_init_uncores
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
```
```
In arch/x86/hyperv/hv_init.c (ffffffff832a5b32)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff8103933f)
Location: include/linux/slab.h:658
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8104fa2d)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81060363)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_create_device
```
```
In arch/x86/kernel/cpu/mtrr/if.c (ffffffff810626da)
Location: include/linux/slab.h:658
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810671fd)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8106c358)
Location: include/linux/slab.h:658
Inline: True
```
```
In arch/x86/kernel/hpet.c (ffffffff832bd7e0)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8108da4c)
Location: include/linux/slab.h:658
Inline: True
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff832c6ef3)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff810b047c)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
```
```
In kernel/workqueue.c (ffffffff832c8526)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/sched/fair.c (ffffffff81111275)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/sched/cpupri.c (ffffffff8111cbf1)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/cpudeadline.c (ffffffff8111d21b)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_init
```
```
In kernel/sched/topology.c (ffffffff81120168)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
```
```
In kernel/power/energy_model.c (ffffffff81137df7)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_create_perf_table
```
```
In kernel/irq/msi.c (ffffffff81149c3e)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_populate_sysfs
  - kernel/irq/msi.c:msi_populate_sysfs
```
```
In kernel/irq/affinity.c (ffffffff8114aebf)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/dma/direct.c (ffffffff8115da15)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_set_offset
```
```
In kernel/cgroup/rdma.c (ffffffff811a2146)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/auditfilter.c (ffffffff811b10e7)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_init_entry
  - kernel/auditfilter.c:audit_register_class
```
```
In kernel/trace/ftrace.c (ffffffff811d5641)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:alloc_ftrace_hash
  - kernel/trace/ftrace.c:ftrace_profile_init
```
```
In kernel/trace/trace.c (ffffffff811e5ed5)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - kernel/trace/trace.c:create_trace_option_files
  - kernel/trace/trace.c:__tracing_open
```
```
In kernel/trace/tracing_map.c (ffffffff811f3085)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_alloc_elts
  - kernel/trace/tracing_map.c:tracing_map_alloc_elts
  - kernel/trace/tracing_map.c:tracing_map_alloc_elts
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_syscalls.c (ffffffff832d27af)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:init_ftrace_syscalls
```
```
In kernel/trace/trace_events_filter.c (ffffffff81206000)
Location: include/linux/slab.h:658
Inline: True
```
```
In kernel/trace/trace_events_synth.c (ffffffff8120d9ad)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:alloc_synth_event
  - kernel/trace/trace_events_synth.c:alloc_synth_event
```
```
In kernel/trace/trace_events_hist.c (ffffffff8121423f)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_alloc
```
```
In kernel/trace/bpf_trace.c (ffffffff8121ac16)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
```
In kernel/trace/trace_probe.c (ffffffff81223e0e)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
```
```
In kernel/bpf/core.c (ffffffff8122c3be)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
```
```
In kernel/bpf/verifier.c (ffffffff81243ea3)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
```
In kernel/bpf/trampoline.c (ffffffff8125f51e)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff81276de5)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
```
In kernel/events/core.c (ffffffff81283bbc)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/hw_breakpoint.c (ffffffff832d49f7)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
```
```
In kernel/events/uprobes.c (ffffffff8129286c)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In kernel/watch_queue.c (ffffffff8129774d)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_size
```
```
In mm/slab_common.c (ffffffff812ce3dd)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In mm/list_lru.c (ffffffff812d5931)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
```
```
In mm/vmalloc.c (ffffffff812fdb02)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
```
```
In mm/ksm.c (ffffffff8132f0c4)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - mm/ksm.c:merge_across_nodes_store
```
```
In mm/slub.c (ffffffff813394a5)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
```
```
In fs/pipe.c (ffffffff8137f5cd)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - fs/pipe.c:pipe_resize_ring
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/splice.c (ffffffff813b37b0)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:iter_file_splice_write
```
```
In fs/aio.c (ffffffff813d9719)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/io_uring.c (ffffffff813e4ac8)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffers_register
  - fs/io_uring.c:io_rsrc_data_alloc
```
```
In fs/proc/proc_sysctl.c (ffffffff81433910)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:register_leaf_sysctl_tables
```
```
In fs/ext4/extents.c (ffffffff8144dc9a)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_precache
```
```
In fs/squashfs/cache.c (ffffffff814c2b75)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
```
```
In fs/squashfs/file.c (ffffffff814c351a)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - fs/squashfs/file.c:empty_meta_index
```
```
In fs/fuse/file.c (ffffffff814f3495)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages
```
```
In fs/fuse/inode.c (ffffffff814f4c09)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_dev_alloc
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff832e3485)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:init_digests
```
```
In security/security.c (ffffffff832e3d08)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - security/security.c:ordered_lsm_init
```
```
In security/selinux/ss/hashtab.c (ffffffff8153cfbe)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - security/selinux/ss/hashtab.c:hashtab_duplicate
  - security/selinux/ss/hashtab.c:hashtab_init
```
```
In security/selinux/ss/policydb.c (ffffffff8154143d)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In security/selinux/ss/services.c (ffffffff8154b956)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
```
```
In security/selinux/ss/conditional.c (ffffffff8154da1f)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_policydb_dup
  - security/selinux/ss/conditional.c:cond_dup_av_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_av_list
```
```
In security/apparmor/policy_unpack.c (ffffffff8157f466)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_secmark
  - security/apparmor/policy_unpack.c:unpack_xattrs
  - security/apparmor/policy_unpack.c:unpack_trans_table
```
```
In security/integrity/ima/ima_queue.c (ffffffff832e6ce4)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_init_digests
```
```
In security/integrity/ima/ima_crypto.c (ffffffff832e72de)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
```
```
In security/integrity/ima/ima_api.c (ffffffff8159c39b)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/slab.h:658
Inline: True
```
```
In security/integrity/ima/ima_template.c (ffffffff8159f8c4)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_template_data
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff815c32cb)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
```
```
In block/partitions/aix.c (ffffffff815e7d0b)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In block/blk-crypto-fallback.c (ffffffff8160ea33)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
```
```
In lib/mpi/mpi-mod.c (ffffffff81652ea8)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - lib/mpi/mpi-mod.c:mpi_barrett_init
```
```
In lib/mpi/mpiutil.c (ffffffff81655e28)
Location: include/linux/slab.h:658
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff8168bab3)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:devprop_gpiochip_set_names
```
```
In drivers/pwm/core.c (ffffffff816948b6)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_add
```
```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff816cfa9d)
Location: include/linux/slab.h:658
Inline: True
```
```
In drivers/rapidio/rio.c (ffffffff816d4307)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/video/fbdev/core/fbmon.c (ffffffff816e06f5)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmon.c:fb_create_modedb
```
```
In drivers/acpi/acpi_platform.c (ffffffff8170c6e4)
Location: include/linux/slab.h:658
Inline: True
```
```
In drivers/acpi/sysfs.c (ffffffff8170f9e2)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
```
```
In drivers/acpi/x86/s2idle.c (ffffffff81712410)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
```
```
In drivers/acpi/acpi_lpat.c (ffffffff81712dfe)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff832f32c8)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/acpi/acpi_adxl.c (ffffffff832f36c3)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/acpi/acpi_adxl.c:adxl_init
```
```
In drivers/acpi/processor_idle.c (ffffffff8175901a)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
```
```
In drivers/clk/clk.c (ffffffff81775ccd)
Location: include/linux/slab.h:658
Inline: True
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff8177f804)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8178c441)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
```
```
In drivers/xen/grant-table.c (ffffffff81790be1)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
```
```
In drivers/xen/events/events_base.c (ffffffff832f83e8)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/mcelog.c (ffffffff81cf692a)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:bind_virq_for_mce
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81cf712b)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
```
```
In drivers/xen/xlate_mmu.c (ffffffff832f9348)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
```
In drivers/regulator/core.c (ffffffff817af82e)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/tty/tty_io.c (ffffffff817b66bc)
Location: include/linux/slab.h:658
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff817ddbd8)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_core.c:uart_register_driver
```
```
In drivers/char/random.c (ffffffff817f6a15)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81805505)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_pcr_allocation
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff8180672d)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
```
```
In drivers/iommu/intel/dmar.c (ffffffff81816d1b)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_alloc_dev_scope
```
```
In drivers/iommu/intel/iommu.c (ffffffff818190f9)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_suspend
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:iommu_init_domains
```
```
In drivers/base/property.c (ffffffff81842f75)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_property_match_string
```
```
In drivers/base/cacheinfo.c (ffffffff81844c54)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_add_dev
```
```
In drivers/base/swnode.c (ffffffff81845c0e)
Location: include/linux/slab.h:658
Inline: True
```
```
In drivers/base/power/clock_ops.c (0)
Location: include/linux/slab.h:658
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffffffff8185f730)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_field_bulk_alloc
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff81866301)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
```
In drivers/base/regmap/regcache-flat.c (ffffffff81866525)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-flat.c:regcache_flat_init
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff8186a000)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
```
```
In drivers/block/xen-blkfront.c (ffffffff81875211)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlbd_reserve_minors
```
```
In drivers/misc/sram.c (ffffffff8187772e)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/mfd/mfd-core.c (ffffffff818804c6)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8189775f)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/dma-buf/dma-fence.c (ffffffff818a5447)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/sync_file.c (ffffffff818a9431)
Location: include/linux/slab.h:658
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff818d07ee)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl_common
```
```
In drivers/ata/libata-core.c (ffffffff833030f6)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_parse_force_param
```
```
In drivers/ata/libata-pmp.c (ffffffff818edd3d)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
```
In drivers/spi/spi.c (ffffffff818fd3d7)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_board_info
```
```
In drivers/net/phy/mdio-boardinfo.c (ffffffff81900108)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/net/phy/mdio-boardinfo.c:mdiobus_register_board_info
```
```
In drivers/net/xen-netfront.c (ffffffff8191c7fb)
Location: include/linux/slab.h:658
Inline: True
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff8192a56c)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff8192c50e)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable
```
```
In drivers/usb/core/hub.c (ffffffff81d147f3)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/quirks.c (ffffffff81953f5d)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/usb/core/quirks.c:quirks_param_set
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8196da87)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8197466e)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:find_tt
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8198b08e)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/input/input.c (ffffffff819b641e)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/input/input-mt.c (ffffffff819b9aed)
Location: include/linux/slab.h:658
Inline: True
```
```
In drivers/input/ff-core.c (ffffffff819ba04a)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (ffffffff819bf4ea)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_get_keymap_from_fwnode
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff819daca6)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:ptp_populate_pin_groups
  - drivers/ptp/ptp_sysfs.c:ptp_populate_pin_groups
```
```
In drivers/hwmon/hwmon.c (ffffffff819e0acd)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff819e6285)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:create_trip_attrs
  - drivers/thermal/thermal_sysfs.c:create_trip_attrs
  - drivers/thermal/thermal_sysfs.c:create_trip_attrs
  - drivers/thermal/thermal_sysfs.c:create_trip_attrs
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff819ea276)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:allocate_power
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff819eaa3e)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables
```
```
In drivers/md/md-bitmap.c (ffffffff81a03146)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
```
```
In drivers/md/dm-zone.c (ffffffff81a059a6)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_revalidate_cb
  - drivers/md/dm-zone.c:dm_zone_revalidate_cb
```
```
In drivers/edac/edac_mc.c (ffffffff81a1a2a7)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc_dimms
```
```
In drivers/opp/core.c (ffffffff81a21b2b)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
```
```
In drivers/opp/cpu.c (ffffffff81a22c4c)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81a2bd94)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81a31586)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
```
In drivers/mmc/core/host.c (ffffffff81a3cc0d)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_of_parse_voltage
```
```
In drivers/leds/led-core.c (ffffffff81a4ace1)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_get_default_pattern
```
```
In drivers/firmware/efi/capsule.c (ffffffff81a5062b)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff8330e0fa)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
```
```
In drivers/firmware/efi/apple-properties.c (ffffffff8330e8d2)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
```
In drivers/mailbox/pcc.c (ffffffff8330ff7e)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
```
In drivers/extcon/extcon.c (ffffffff81a66ded)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In drivers/powercap/powercap_sys.c (ffffffff81a6bafa)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:powercap_register_zone
  - drivers/powercap/powercap_sys.c:powercap_register_zone
```
```
In drivers/nvmem/core.c (ffffffff81a6ec29)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_add_cells
```
```
In net/core/rtnetlink.c (ffffffff81ab2b30)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_register_internal
```
```
In net/core/filter.c (ffffffff81ac449a)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - net/core/filter.c:bpf_convert_filter
```
```
In net/sched/sch_mq.c (ffffffff81b10802)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_init
```
```
In net/sched/cls_api.c (ffffffff81b163a2)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_gate_get_list
```
```
In net/netlink/af_netlink.c (ffffffff8331195d)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_proto_init
```
```
In net/ethtool/ioctl.c (ffffffff81b307c1)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_self_test
  - net/ethtool/ioctl.c:ethtool_set_rxfh_indir
  - net/ethtool/ioctl.c:ethtool_get_rxfh_indir
  - net/ethtool/ioctl.c:ethtool_get_rxnfc
  - net/ethtool/ioctl.c:ethtool_get_sset_info
```
```
In net/ethtool/common.c (ffffffff81b32827)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - net/ethtool/common.c:ethtool_get_max_rxfh_channel
```
```
In net/ethtool/strset.c (ffffffff81b35581)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_prepare_set
```
```
In net/ethtool/privflags.c (ffffffff81b3788f)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - net/ethtool/privflags.c:ethnl_get_priv_flags_info
```
```
In net/ipv4/route.c (ffffffff81b41e6e)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
```
```
In net/ipv4/fib_frontend.c (ffffffff81ba2de0)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
```
```
In net/ipv4/cipso_ipv4.c (ffffffff833131f2)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
```
```
In net/ipv6/route.c (ffffffff81c0604a)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/exthdrs.c (ffffffff81c31fc5)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/calipso.c (ffffffff83314729)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_init
```
```
In net/packet/af_packet.c (ffffffff81c50a98)
Location: include/linux/slab.h:658
Inline: True
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff83314b22)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_init
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff83314c1c)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81c612d1)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81c6c4bb)
Location: include/linux/slab.h:658
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
```
```
In arch/x86/pci/xen.c (ffffffff81c8edd9)
Location: include/linux/slab.h:658
Inline: True
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
In arch/x86/events/amd/iommu.c (ffffffff8344b20c)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:_init_events_attrs
```
```
In arch/x86/events/intel/core.c (ffffffff8344ca18)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff8344e3f5)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_type_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81028204)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:sad_cfg_iio_topology
  - arch/x86/events/intel/uncore_snbep.c:pmu_iio_set_mapping
  - arch/x86/events/intel/uncore_snbep.c:pmu_iio_set_mapping
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81029fd2)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_init_uncores
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
```
```
In arch/x86/hyperv/hv_init.c (ffffffff83454bcb)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/ivm.c (ffffffff8103f644)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_map_memory
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff810401be)
Location: include/linux/slab.h:669
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8105b227)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8106caf8)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_create_device
```
```
In arch/x86/kernel/cpu/mtrr/if.c (ffffffff8106f1bd)
Location: include/linux/slab.h:669
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81073ef1)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81079718)
Location: include/linux/slab.h:669
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81093fd7)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cluster_probe
```
```
In arch/x86/kernel/hpet.c (ffffffff8346f1d0)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81e4e580)
Location: include/linux/slab.h:669
Inline: True
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff83479d00)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff810c63bf)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
```
```
In kernel/workqueue.c (ffffffff8347b632)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/sched/fair.c (ffffffff8112d495)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/sched/build_policy.c (ffffffff811367cb)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:cpudl_init
```
```
In kernel/sched/build_utility.c (ffffffff8114a38a)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:cpupri_init
```
```
In kernel/power/energy_model.c (ffffffff8115a496)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_create_perf_table
```
```
In kernel/irq/msi.c (ffffffff8116e885)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_sysfs_populate_desc
```
```
In kernel/irq/affinity.c (ffffffff8117052f)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/rcu/srcutree.c (ffffffff81175fdf)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_nodes
```
```
In kernel/dma/direct.c (ffffffff811879a7)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_set_offset
```
```
In kernel/futex/syscalls.c (ffffffff811b398b)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - kernel/futex/syscalls.c:__do_sys_futex_waitv
```
```
In kernel/cgroup/rdma.c (ffffffff811d2ba6)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/auditfilter.c (ffffffff811e338e)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_init_entry
  - kernel/auditfilter.c:audit_register_class
```
```
In kernel/trace/ftrace.c (ffffffff8120a7a1)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:alloc_ftrace_hash
  - kernel/trace/ftrace.c:ftrace_profile_init
```
```
In kernel/trace/trace.c (ffffffff8121d702)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - kernel/trace/trace.c:create_trace_option_files
  - kernel/trace/trace.c:__tracing_open
```
```
In kernel/trace/tracing_map.c (ffffffff8122c5f4)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_elt_alloc
  - kernel/trace/tracing_map.c:tracing_map_elt_alloc
  - kernel/trace/tracing_map.c:tracing_map_elt_alloc
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_syscalls.c (ffffffff83486bd1)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:init_ftrace_syscalls
```
```
In kernel/trace/trace_events_filter.c (ffffffff812417e5)
Location: include/linux/slab.h:669
Inline: True
```
```
In kernel/trace/trace_events_synth.c (ffffffff812499b6)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:alloc_synth_event
  - kernel/trace/trace_events_synth.c:alloc_synth_event
```
```
In kernel/trace/trace_events_hist.c (ffffffff8124ffe9)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_alloc
```
```
In kernel/trace/bpf_trace.c (ffffffff812598ed)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
```
In kernel/trace/trace_probe.c (ffffffff81263d6a)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
```
```
In kernel/trace/fprobe.c (ffffffff8126871b)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - kernel/trace/fprobe.c:get_ftrace_locations
```
```
In kernel/bpf/core.c (ffffffff8126e01f)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
```
```
In kernel/bpf/verifier.c (ffffffff8128985b)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
```
In kernel/bpf/trampoline.c (ffffffff812a9c8f)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
```
In kernel/bpf/btf.c (ffffffff812b95a4)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - kernel/bpf/btf.c:bpf_core_apply
  - kernel/bpf/btf.c:bpf_core_apply
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff812c6a0f)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
```
In kernel/events/core.c (ffffffff812d6da7)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/hw_breakpoint.c (ffffffff8348908a)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
```
```
In kernel/events/uprobes.c (ffffffff812e827d)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In kernel/watch_queue.c (ffffffff812ed9cd)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_size
```
```
In mm/slab_common.c (ffffffff8132c4a8)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In mm/list_lru.c (ffffffff813352c9)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
```
```
In mm/vmalloc.c (ffffffff81364a91)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
```
```
In mm/ksm.c (ffffffff8139f2be)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - mm/ksm.c:merge_across_nodes_store
```
```
In mm/slub.c (ffffffff813ab135)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
```
```
In mm/migrate.c (ffffffff83492b09)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - mm/migrate.c:migrate_on_reclaim_init
```
```
In fs/pipe.c (ffffffff813ff6a8)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - fs/pipe.c:pipe_resize_ring
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/splice.c (ffffffff8143890e)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:iter_file_splice_write
```
```
In fs/aio.c (ffffffff8146381e)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/proc/proc_sysctl.c (ffffffff814ad866)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:register_leaf_sysctl_tables
```
```
In fs/ext4/extents.c (ffffffff814ca87e)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_precache
```
```
In fs/squashfs/cache.c (ffffffff8154d695)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
```
```
In fs/squashfs/file.c (ffffffff8154e0e8)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - fs/squashfs/file.c:empty_meta_index
```
```
In fs/fuse/file.c (ffffffff81582f2a)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages
```
```
In fs/fuse/inode.c (ffffffff815847d9)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_dev_alloc
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8349988f)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:init_digests
```
```
In security/security.c (ffffffff8349a1ab)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - security/security.c:ordered_lsm_init
```
```
In security/selinux/ss/hashtab.c (ffffffff815d4a21)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - security/selinux/ss/hashtab.c:hashtab_duplicate
  - security/selinux/ss/hashtab.c:hashtab_init
```
```
In security/selinux/ss/policydb.c (ffffffff815d87ed)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In security/selinux/ss/services.c (ffffffff815e4776)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
```
```
In security/selinux/ss/conditional.c (ffffffff815e6acd)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_policydb_dup
  - security/selinux/ss/conditional.c:cond_dup_av_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_av_list
```
```
In security/apparmor/policy_unpack.c (ffffffff8161e6ea)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_pdb
  - security/apparmor/policy_unpack.c:unpack_secmark
  - security/apparmor/policy_unpack.c:unpack_xattrs
  - security/apparmor/policy_unpack.c:unpack_trans_table
```
```
In security/integrity/ima/ima_queue.c (ffffffff8349ddb6)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_init_digests
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8349e40e)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
```
```
In security/integrity/ima/ima_api.c (ffffffff816413bb)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
```
```
In security/integrity/ima/ima_policy.c (ffffffff8349e7e0)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
```
```
In security/integrity/ima/ima_template.c (ffffffff81645053)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_template_data
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff8166d86d)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
```
```
In block/blk-stat.c (ffffffff8168e205)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stats_alloc_enable
```
```
In block/partitions/aix.c (ffffffff816972c5)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In block/blk-crypto-fallback.c (ffffffff816c31cb)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
```
```
In io_uring/io_uring.c (ffffffff81e90e6d)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_sqe_buffers_register
  - io_uring/io_uring.c:io_uring_alloc_task_context
  - io_uring/io_uring.c:io_rsrc_data_alloc
  - io_uring/io_uring.c:io_init_bl_list
```
```
In lib/string_helpers.c (ffffffff816ece9f)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - lib/string_helpers.c:kasprintf_strarray
```
```
In lib/mpi/mpi-mod.c (ffffffff8176a299)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - lib/mpi/mpi-mod.c:mpi_barrett_init
```
```
In lib/mpi/mpiutil.c (ffffffff8176d5dc)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - lib/mpi/mpiutil.c:mpi_resize
  - lib/mpi/mpiutil.c:mpi_resize
```
```
In drivers/gpio/gpiolib.c (ffffffff817a8edf)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/pwm/core.c (ffffffff817b5414)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_add
```
```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff817f878f)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_multi_mem_init
```
```
In drivers/rapidio/rio.c (ffffffff817fe3f7)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/video/fbdev/core/fbmon.c (ffffffff8180aaf5)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmon.c:fb_create_modedb
```
```
In drivers/acpi/acpi_platform.c (ffffffff8183ae24)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/acpi/acpi_platform.c:acpi_create_platform_device
```
```
In drivers/acpi/sysfs.c (ffffffff8183e560)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
```
```
In drivers/acpi/x86/s2idle.c (ffffffff818418e9)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
```
```
In drivers/acpi/acpi_lpat.c (ffffffff818423c4)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff834ab3dc)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/acpi/acpi_adxl.c (ffffffff834ab87b)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/acpi/acpi_adxl.c:adxl_init
```
```
In drivers/acpi/processor_idle.c (ffffffff8188c74c)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
```
```
In drivers/clk/clk.c (ffffffff818ac4a7)
Location: include/linux/slab.h:669
Inline: True
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff818b5f46)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff818c408f)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
```
```
In drivers/xen/grant-table.c (ffffffff818c8f78)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
```
```
In drivers/xen/events/events_base.c (ffffffff834b0c20)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/mcelog.c (ffffffff81ebe987)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:bind_virq_for_mce
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81ebf203)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
```
```
In drivers/xen/xlate_mmu.c (ffffffff834b1b55)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
```
In drivers/regulator/core.c (ffffffff818eabe3)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/tty/tty_io.c (ffffffff818f3900)
Location: include/linux/slab.h:669
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff8191c763)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_core.c:uart_register_driver
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81944f85)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_pcr_allocation
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff8194629a)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
```
```
In drivers/iommu/intel/dmar.c (ffffffff81957d22)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_alloc_dev_scope
```
```
In drivers/iommu/intel/iommu.c (ffffffff81959c86)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_suspend
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:copy_translation_tables
```
```
In drivers/iommu/iova.c (ffffffff8196e075)
Location: include/linux/slab.h:669
Inline: True
```
```
In drivers/base/property.c (ffffffff81986d14)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_property_match_string
```
```
In drivers/base/cacheinfo.c (ffffffff81988e70)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_add_dev
```
```
In drivers/base/swnode.c (ffffffff81989f6a)
Location: include/linux/slab.h:669
Inline: True
```
```
In drivers/base/power/clock_ops.c (0)
Location: include/linux/slab.h:669
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffffffff819a7a1b)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_field_bulk_alloc
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff819ae87f)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
```
In drivers/base/regmap/regcache-flat.c (ffffffff819aeaa3)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-flat.c:regcache_flat_init
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff819b2caa)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
```
```
In drivers/block/xen-blkfront.c (ffffffff819ba110)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlbd_reserve_minors
```
```
In drivers/misc/sram.c (ffffffff819bf9ee)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/mfd/mfd-core.c (ffffffff819c8b85)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff819e1494)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/dma-buf/dma-fence.c (ffffffff819ef066)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/sync_file.c (ffffffff819f34db)
Location: include/linux/slab.h:669
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff81a1dc11)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl_common
```
```
In drivers/ata/libata-core.c (ffffffff834bc3ac)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_parse_force_param
```
```
In drivers/ata/libata-pmp.c (ffffffff81a3ff03)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
```
In drivers/spi/spi.c (ffffffff81a4ea17)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_board_info
```
```
In drivers/net/phy/mdio-boardinfo.c (ffffffff81a51c58)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/net/phy/mdio-boardinfo.c:mdiobus_register_board_info
```
```
In drivers/net/xen-netfront.c (ffffffff81a71dbb)
Location: include/linux/slab.h:669
Inline: True
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81a818dc)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff81a82b45)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable
```
```
In drivers/usb/core/hub.c (ffffffff81edf373)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/quirks.c (ffffffff81aad861)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/usb/core/quirks.c:quirks_param_set
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81ac8066)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81acf6a6)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:find_tt
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81ae6943)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/input/input.c (ffffffff81b15c2f)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/input/input-mt.c (ffffffff81b196f0)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_init_slots
```
```
In drivers/input/ff-core.c (ffffffff81b1a048)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81b1f6c8)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_get_keymap_from_fwnode
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff81b3e491)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:ptp_populate_pin_groups
  - drivers/ptp/ptp_sysfs.c:ptp_populate_pin_groups
```
```
In drivers/hwmon/hwmon.c (ffffffff81b4572f)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81b4b6d5)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:create_trip_attrs
  - drivers/thermal/thermal_sysfs.c:create_trip_attrs
  - drivers/thermal/thermal_sysfs.c:create_trip_attrs
  - drivers/thermal/thermal_sysfs.c:create_trip_attrs
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff81b4ff65)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:allocate_power
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff81b50869)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81b52672)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:hfi_update_work_fn
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_init
```
```
In drivers/md/md-bitmap.c (ffffffff81b6ae16)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
```
```
In drivers/md/dm-zone.c (ffffffff81b6d6e1)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_revalidate_cb
  - drivers/md/dm-zone.c:dm_zone_revalidate_cb
```
```
In drivers/edac/edac_mc.c (ffffffff81b83017)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc_dimms
```
```
In drivers/edac/edac_device.c (ffffffff81b838db)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
```
```
In drivers/opp/core.c (ffffffff81b8ab69)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
```
```
In drivers/opp/cpu.c (ffffffff81b8be34)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81b96381)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81b9d805)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
```
In drivers/mmc/core/host.c (ffffffff81ba9cab)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_of_parse_voltage
```
```
In drivers/leds/led-core.c (ffffffff81bb9251)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_get_default_pattern
```
```
In drivers/firmware/efi/capsule.c (ffffffff81bbf509)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff834c7ee0)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
```
```
In drivers/firmware/efi/apple-properties.c (ffffffff834c8646)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
```
In drivers/extcon/extcon.c (ffffffff81bd83a3)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In drivers/powercap/powercap_sys.c (ffffffff81bdc585)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:powercap_register_zone
  - drivers/powercap/powercap_sys.c:powercap_register_zone
```
```
In drivers/nvmem/core.c (ffffffff81bdfc79)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_add_cells
```
```
In net/core/rtnetlink.c (ffffffff81c2bd79)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_register_internal
```
```
In net/core/filter.c (ffffffff81c3f9cc)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - net/core/filter.c:bpf_convert_filter
```
```
In net/sched/sch_mq.c (ffffffff81c97b02)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_init
```
```
In net/netlink/af_netlink.c (ffffffff834cb7a6)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_proto_init
```
```
In net/bpf/bpf_dummy_struct_ops.c (ffffffff81cb6931)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
```
```
In net/ethtool/ioctl.c (ffffffff81cbb65e)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_self_test
  - net/ethtool/ioctl.c:ethtool_set_rxfh_indir
  - net/ethtool/ioctl.c:ethtool_get_rxfh_indir
  - net/ethtool/ioctl.c:ethtool_get_rxnfc
  - net/ethtool/ioctl.c:ethtool_get_sset_info
```
```
In net/ethtool/common.c (ffffffff81cbdd97)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - net/ethtool/common.c:ethtool_get_max_rxfh_channel
```
```
In net/ethtool/strset.c (ffffffff81cc0dd2)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_prepare_set
```
```
In net/ethtool/privflags.c (ffffffff81cc330e)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - net/ethtool/privflags.c:ethnl_get_priv_flags_info
```
```
In net/ipv4/route.c (ffffffff81cce861)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
```
```
In net/ipv4/fib_frontend.c (ffffffff81d3556d)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
```
```
In net/ipv4/cipso_ipv4.c (ffffffff834cd4bd)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
```
```
In net/ipv6/addrconf.c (ffffffff81d94071)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_init_net
```
```
In net/ipv6/route.c (ffffffff81da0722)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/exthdrs.c (ffffffff81dcf7c4)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/calipso.c (ffffffff834cebf3)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_init
```
```
In net/packet/af_packet.c (ffffffff81df1cd8)
Location: include/linux/slab.h:669
Inline: True
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff834cf037)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_init
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff834cf151)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81e03866)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81e10408)
Location: include/linux/slab.h:669
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
```
```
In arch/x86/pci/xen.c (ffffffff81e3e1a9)
Location: include/linux/slab.h:669
Inline: True
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
In arch/x86/events/amd/iommu.c (ffffffff83e65e25)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
```
```
In arch/x86/events/intel/core.c (ffffffff83e676fd)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff83e699c5)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_type_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102eb6b)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:pmu_set_mapping
  - arch/x86/events/intel/uncore_snbep.c:pmu_set_mapping
  - arch/x86/events/intel/uncore_snbep.c:pmu_set_mapping
  - arch/x86/events/intel/uncore_snbep.c:pmu_set_mapping
  - arch/x86/events/intel/uncore_snbep.c:pmu_set_mapping
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81030ae2)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_init_uncores
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
```
```
In arch/x86/hyperv/hv_init.c (ffffffff83e727c0)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/ivm.c (ffffffff810487c4)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_map_memory
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff8104941e)
Location: include/linux/slab.h:665
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81068bb7)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107cba8)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_create_device
```
```
In arch/x86/kernel/cpu/mtrr/if.c (ffffffff8107f39d)
Location: include/linux/slab.h:665
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810841b3)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108a15f)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8108a518)
Location: include/linux/slab.h:665
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810a9a44)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cluster_probe
```
```
In arch/x86/kernel/hpet.c (ffffffff83e957a0)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In arch/x86/kernel/amd_nb.c (ffffffff810b58a5)
Location: include/linux/slab.h:665
Inline: True
```
```
In arch/x86/platform/efi/runtime-map.c (ffffffff83ea3f5b)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - arch/x86/platform/efi/runtime-map.c:efi_runtime_map_init
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff83ea4225)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff810e328a)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
```
```
In kernel/workqueue.c (ffffffff83ea64b8)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/sched/fair.c (ffffffff81157255)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/sched/build_policy.c (ffffffff81160e09)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:cpudl_init
```
```
In kernel/sched/build_utility.c (ffffffff81178d4a)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:cpupri_init
```
```
In kernel/power/energy_model.c (ffffffff8118c826)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_create_perf_table
```
```
In kernel/irq/msi.c (ffffffff811a3f65)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_sysfs_populate_desc
```
```
In kernel/irq/affinity.c (ffffffff811a69af)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/rcu/srcutree.c (ffffffff811ad9bf)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_nodes
```
```
In kernel/dma/direct.c (ffffffff811c35c3)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_set_offset
```
```
In kernel/futex/syscalls.c (ffffffff811f499b)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - kernel/futex/syscalls.c:__do_sys_futex_waitv
```
```
In kernel/cgroup/rdma.c (ffffffff81216ad6)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/auditfilter.c (ffffffff8122953e)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_init_entry
  - kernel/auditfilter.c:audit_register_class
```
```
In kernel/trace/ftrace.c (ffffffff81253071)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:alloc_ftrace_hash
  - kernel/trace/ftrace.c:ftrace_profile_init
```
```
In kernel/trace/trace.c (ffffffff81267e20)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - kernel/trace/trace.c:create_trace_option_files
  - kernel/trace/trace.c:__tracing_open
```
```
In kernel/trace/tracing_map.c (ffffffff81278144)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_elt_alloc
  - kernel/trace/tracing_map.c:tracing_map_elt_alloc
  - kernel/trace/tracing_map.c:tracing_map_elt_alloc
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_syscalls.c (ffffffff83eb6370)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:init_ftrace_syscalls
```
```
In kernel/trace/trace_events_filter.c (ffffffff8128f175)
Location: include/linux/slab.h:665
Inline: True
```
```
In kernel/trace/trace_events_synth.c (ffffffff81297ce6)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:alloc_synth_event
  - kernel/trace/trace_events_synth.c:alloc_synth_event
```
```
In kernel/trace/trace_events_hist.c (ffffffff8129ce3b)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:print_entries
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_alloc
```
```
In kernel/trace/bpf_trace.c (ffffffff812a9b3d)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
```
In kernel/trace/trace_probe.c (ffffffff812b57b2)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
```
```
In kernel/trace/fprobe.c (ffffffff812bad25)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - kernel/trace/fprobe.c:register_fprobe_syms
```
```
In kernel/bpf/core.c (ffffffff812c362f)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
```
```
In kernel/bpf/verifier.c (ffffffff812e0274)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
```
In kernel/bpf/trampoline.c (ffffffff81308df4)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
```
In kernel/bpf/btf.c (ffffffff8131b5dd)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - kernel/bpf/btf.c:bpf_core_apply
  - kernel/bpf/btf.c:bpf_core_apply
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8132c27f)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
```
In kernel/events/core.c (ffffffff8133fb52)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/uprobes.c (ffffffff81351ffb)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In kernel/watch_queue.c (ffffffff81357dbd)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_size
```
```
In mm/slab_common.c (ffffffff813a2848)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In mm/list_lru.c (ffffffff813abf89)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
```
```
In mm/vmalloc.c (ffffffff813e05f2)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
```
```
In mm/ksm.c (ffffffff8141f83e)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - mm/ksm.c:merge_across_nodes_store
```
```
In mm/slub.c (ffffffff81427235)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
```
```
In mm/memory-tiers.c (ffffffff83ec6910)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - mm/memory-tiers.c:memory_tier_init
```
```
In fs/pipe.c (ffffffff81489488)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - fs/pipe.c:pipe_resize_ring
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/splice.c (ffffffff814c63c8)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:iter_file_splice_write
```
```
In fs/aio.c (ffffffff814f290e)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/proc/proc_sysctl.c (ffffffff81543d56)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:register_leaf_sysctl_tables
```
```
In fs/ext4/extents.c (ffffffff81562f6a)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_precache
```
```
In fs/squashfs/cache.c (ffffffff815ed655)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
```
```
In fs/squashfs/file.c (ffffffff815ee418)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - fs/squashfs/file.c:empty_meta_index
```
```
In fs/fuse/file.c (ffffffff81628eaa)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages
```
```
In fs/fuse/inode.c (ffffffff8162a8f9)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_dev_alloc
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff83ecf955)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:init_digests
```
```
In security/security.c (ffffffff83ed0615)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - security/security.c:ordered_lsm_init
```
```
In security/selinux/ss/hashtab.c (ffffffff81682b91)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - security/selinux/ss/hashtab.c:hashtab_duplicate
  - security/selinux/ss/hashtab.c:hashtab_init
```
```
In security/selinux/ss/policydb.c (ffffffff8168727d)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In security/selinux/ss/services.c (ffffffff81693b26)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
```
```
In security/selinux/ss/conditional.c (ffffffff8169615d)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_policydb_dup
  - security/selinux/ss/conditional.c:cond_dup_av_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_av_list
```
```
In security/apparmor/policy_unpack.c (ffffffff816d1b34)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_pdb
  - security/apparmor/policy_unpack.c:unpack_secmark
  - security/apparmor/policy_unpack.c:unpack_xattrs
  - security/apparmor/policy_unpack.c:unpack_trans_table
```
```
In security/integrity/ima/ima_queue.c (ffffffff83ed5ad5)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_init_digests
```
```
In security/integrity/ima/ima_crypto.c (ffffffff83ed61a2)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
```
```
In security/integrity/ima/ima_api.c (ffffffff816f938b)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
```
```
In security/integrity/ima/ima_policy.c (ffffffff83ed6783)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
```
```
In security/integrity/ima/ima_template.c (ffffffff816fd4a4)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_template_data
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff81728945)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
```
```
In block/blk-stat.c (ffffffff8174cb75)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stats_alloc_enable
```
```
In block/partitions/aix.c (ffffffff817561c0)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In block/blk-crypto-fallback.c (ffffffff8178464c)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
```
```
In io_uring/kbuf.c (ffffffff8179ef15)
Location: include/linux/slab.h:665
Inline: True
```
```
In io_uring/rsrc.c (ffffffff817a2b3a)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_sqe_buffers_register
  - io_uring/rsrc.c:io_rsrc_data_alloc
```
```
In lib/string_helpers.c (ffffffff817dd8af)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - lib/string_helpers.c:kasprintf_strarray
  - lib/string_helpers.c:parse_int_array_user
```
```
In lib/mpi/mpi-mod.c (ffffffff81899859)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - lib/mpi/mpi-mod.c:mpi_barrett_init
```
```
In lib/mpi/mpiutil.c (ffffffff8189cd6c)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - lib/mpi/mpiutil.c:mpi_resize
  - lib/mpi/mpiutil.c:mpi_resize
```
```
In drivers/gpio/gpiolib.c (ffffffff818c184c)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/pwm/core.c (ffffffff818cf6ab)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_add
```
```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff8192453f)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_multi_mem_init
```
```
In drivers/rapidio/rio.c (ffffffff8192b657)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/video/fbdev/core/fbmon.c (ffffffff81939395)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmon.c:fb_create_modedb
```
```
In drivers/acpi/scan.c (ffffffff81962262)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_dma_get_range
```
```
In drivers/acpi/acpi_platform.c (ffffffff819704d2)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/acpi/acpi_platform.c:acpi_create_platform_device
```
```
In drivers/acpi/sysfs.c (ffffffff81974470)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
```
```
In drivers/acpi/x86/s2idle.c (ffffffff819784b9)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
```
```
In drivers/acpi/acpi_lpat.c (ffffffff81979014)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff83ee378f)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/acpi/acpi_adxl.c (ffffffff83ee3e1f)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/acpi/acpi_adxl.c:adxl_init
```
```
In drivers/acpi/processor_idle.c (ffffffff819d3fee)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
```
```
In drivers/clk/clk.c (ffffffff819f7c27)
Location: include/linux/slab.h:665
Inline: True
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81a033f6)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
```
```
In drivers/dma/hsu/hsu.c (ffffffff81a07dd3)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_prep_slave_sg
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81a14761)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
```
```
In drivers/xen/grant-table.c (ffffffff81a19ad8)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
```
```
In drivers/xen/events/events_base.c (ffffffff83eeaa51)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/mcelog.c (ffffffff81a31f5c)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:bind_virq_for_mce
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81a331ba)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
```
```
In drivers/xen/xlate_mmu.c (ffffffff83eebecc)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
```
In drivers/regulator/core.c (ffffffff81a418a0)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/tty/tty_io.c (ffffffff81a4be59)
Location: include/linux/slab.h:665
Inline: True
```
```
In drivers/tty/vt/consolemap.c (ffffffff81a6401b)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_insert_unipair
```
```
In drivers/tty/serial/serial_core.c (ffffffff81a78716)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_core.c:uart_register_driver
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81aa7f45)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_pcr_allocation
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81aa933a)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
```
```
In drivers/iommu/intel/dmar.c (ffffffff81abece2)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_alloc_dev_scope
```
```
In drivers/iommu/intel/iommu.c (ffffffff81ac0a36)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_suspend
  - drivers/iommu/intel/iommu.c:copy_translation_tables
```
```
In drivers/iommu/iommu.c (ffffffff83ef6966)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_subsys_init
```
```
In drivers/iommu/iova.c (ffffffff81ad89d5)
Location: include/linux/slab.h:665
Inline: True
```
```
In drivers/base/property.c (ffffffff81af54d4)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_property_match_string
```
```
In drivers/base/cacheinfo.c (ffffffff81af81ed)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_add_dev
  - drivers/base/cacheinfo.c:detect_cache_attributes
```
```
In drivers/base/swnode.c (ffffffff81af945a)
Location: include/linux/slab.h:665
Inline: True
```
```
In drivers/base/power/clock_ops.c (0)
Location: include/linux/slab.h:665
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffffffff81b1a4a9)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_field_bulk_alloc
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff81b2237c)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
```
In drivers/base/regmap/regcache-flat.c (ffffffff81b225e3)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-flat.c:regcache_flat_init
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81b276e4)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
```
```
In drivers/block/xen-blkfront.c (ffffffff81b2f610)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlbd_reserve_minors
```
```
In drivers/misc/sram.c (ffffffff81b3523e)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/mfd/mfd-core.c (ffffffff81b3fea5)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81b5d004)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81b6c596)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/scsi/sg.c (ffffffff81b9ef21)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl_common
```
```
In drivers/ata/libata-core.c (ffffffff83efa68a)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_parse_force_param
```
```
In drivers/ata/libata-pmp.c (ffffffff81bc5f4d)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
```
In drivers/spi/spi.c (ffffffff81bd8ad5)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_board_info
```
```
In drivers/net/phy/mdio-boardinfo.c (ffffffff81bdaf8e)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/net/phy/mdio-boardinfo.c:mdiobus_register_board_info
```
```
In drivers/net/xen-netfront.c (ffffffff81c0458b)
Location: include/linux/slab.h:665
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81c1be98)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/quirks.c (ffffffff81c35221)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/usb/core/quirks.c:quirks_param_set
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81c523b6)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81c59fd6)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:find_tt
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81c726f9)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/input/input.c (ffffffff81ca74c5)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_abs_params
```
```
In drivers/input/input-mt.c (ffffffff81cab151)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_init_slots
```
```
In drivers/input/ff-core.c (ffffffff81cabcd8)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81cb18e8)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_get_keymap_from_fwnode
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff81cd4721)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:ptp_populate_pin_groups
  - drivers/ptp/ptp_sysfs.c:ptp_populate_pin_groups
```
```
In drivers/hwmon/hwmon.c (ffffffff81cdc90b)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81ce3145)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:create_trip_attrs
  - drivers/thermal/thermal_sysfs.c:create_trip_attrs
  - drivers/thermal/thermal_sysfs.c:create_trip_attrs
  - drivers/thermal/thermal_sysfs.c:create_trip_attrs
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff81ce7eb0)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:allocate_power
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff81ce8809)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81cea842)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:hfi_update_work_fn
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_init
```
```
In drivers/md/md-bitmap.c (ffffffff81d06d0d)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
```
```
In drivers/md/dm-zone.c (ffffffff81d09a93)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_revalidate_cb
  - drivers/md/dm-zone.c:dm_zone_revalidate_cb
```
```
In drivers/edac/edac_mc.c (ffffffff81d21977)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc_dimms
```
```
In drivers/edac/edac_device.c (ffffffff81d224db)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
```
```
In drivers/opp/core.c (ffffffff81d29e49)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_set_config
```
```
In drivers/opp/cpu.c (ffffffff81d2b5a4)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81d36f79)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81d3f282)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
```
In drivers/mmc/core/host.c (ffffffff81d4cabb)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_of_parse_voltage
```
```
In drivers/leds/led-core.c (ffffffff81d5e501)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_get_default_pattern
```
```
In drivers/firmware/efi/capsule.c (ffffffff81d63d29)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In drivers/firmware/efi/apple-properties.c (ffffffff83f09922)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
```
In drivers/extcon/extcon.c (ffffffff81d84d9b)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In drivers/powercap/powercap_sys.c (ffffffff81d87673)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:powercap_register_zone
  - drivers/powercap/powercap_sys.c:powercap_register_zone
```
```
In drivers/nvmem/core.c (ffffffff81d8b419)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_add_cells
```
```
In net/core/rtnetlink.c (ffffffff81ddedf9)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_register_internal
```
```
In net/core/filter.c (ffffffff81df465c)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - net/core/filter.c:bpf_convert_filter
```
```
In net/sched/sch_mq.c (ffffffff81e53a02)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_init
```
```
In net/netlink/af_netlink.c (ffffffff83f0dcb8)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_proto_init
```
```
In net/bpf/bpf_dummy_struct_ops.c (ffffffff81e74ea1)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
```
```
In net/ethtool/ioctl.c (ffffffff81e79bee)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_self_test
  - net/ethtool/ioctl.c:ethtool_set_rxfh_indir
  - net/ethtool/ioctl.c:ethtool_get_rxfh_indir
  - net/ethtool/ioctl.c:ethtool_get_rxnfc
  - net/ethtool/ioctl.c:ethtool_get_sset_info
```
```
In net/ethtool/common.c (ffffffff81e7c7b7)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - net/ethtool/common.c:ethtool_get_max_rxfh_channel
```
```
In net/ethtool/strset.c (ffffffff81e7fae2)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_prepare_set
```
```
In net/ethtool/privflags.c (ffffffff81e8264e)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - net/ethtool/privflags.c:ethnl_get_priv_flags_info
```
```
In net/ipv4/route.c (ffffffff81e8ec31)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
```
```
In net/ipv4/fib_frontend.c (ffffffff81efdadd)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
```
```
In net/ipv4/cipso_ipv4.c (ffffffff83f10235)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
```
```
In net/ipv6/addrconf.c (ffffffff81f627c1)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_init_net
```
```
In net/ipv6/route.c (ffffffff81f6f997)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/exthdrs.c (ffffffff81fa0b47)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/calipso.c (ffffffff83f12065)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_init
```
```
In net/packet/af_packet.c (ffffffff81fc5d78)
Location: include/linux/slab.h:665
Inline: True
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff83f12645)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_init
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff83f127c5)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81fd87f6)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81fe6ae8)
Location: include/linux/slab.h:665
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
```
```
In arch/x86/pci/xen.c (ffffffff820178d9)
Location: include/linux/slab.h:665
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
In arch/x86/events/amd/iommu.c (ffffffff836864ac)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
```
```
In arch/x86/events/intel/core.c (ffffffff83687bb5)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff8368a355)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_type_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102e80e)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:spr_update_device_location
  - arch/x86/events/intel/uncore_snbep.c:pmu_set_mapping
  - arch/x86/events/intel/uncore_snbep.c:pmu_set_mapping
  - arch/x86/events/intel/uncore_snbep.c:pmu_set_mapping
  - arch/x86/events/intel/uncore_snbep.c:pmu_set_mapping
  - arch/x86/events/intel/uncore_snbep.c:pmu_set_mapping
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81030ae2)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_init_uncores
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
```
```
In arch/x86/hyperv/hv_init.c (ffffffff836936e0)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff8104967e)
Location: include/linux/slab.h:648
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106a4c7)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107ef56)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_create_device
```
```
In arch/x86/kernel/cpu/mtrr/if.c (ffffffff8108152d)
Location: include/linux/slab.h:648
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff836a342a)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_copy_map
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81086768)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108d143)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8108d588)
Location: include/linux/slab.h:648
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810ac7c4)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cluster_probe
```
```
In arch/x86/kernel/hpet.c (ffffffff836b9310)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In arch/x86/kernel/amd_nb.c (ffffffff810b898f)
Location: include/linux/slab.h:648
Inline: True
```
```
In arch/x86/platform/efi/runtime-map.c (ffffffff836c823b)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - arch/x86/platform/efi/runtime-map.c:efi_runtime_map_init
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff836c8505)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff810ee9e3)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
```
```
In kernel/workqueue.c (ffffffff836cac78)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/sched/fair.c (ffffffff81167325)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/sched/build_policy.c (ffffffff81171559)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:cpudl_init
```
```
In kernel/sched/build_utility.c (ffffffff8118993a)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:cpupri_init
```
```
In kernel/power/energy_model.c (ffffffff8119df46)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_create_perf_table
```
```
In kernel/irq/msi.c (ffffffff811b5e45)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_sysfs_populate_desc
```
```
In kernel/irq/affinity.c (ffffffff811b83a1)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/rcu/srcutree.c (ffffffff811bfa26)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_nodes
```
```
In kernel/dma/direct.c (ffffffff811d6113)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_set_offset
```
```
In kernel/futex/syscalls.c (ffffffff8120912b)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - kernel/futex/syscalls.c:__do_sys_futex_waitv
```
```
In kernel/cgroup/rdma.c (ffffffff8122c3cd)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/auditfilter.c (ffffffff8123fb3e)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_init_entry
  - kernel/auditfilter.c:audit_register_class
```
```
In kernel/trace/ftrace.c (ffffffff8126a5d1)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:alloc_ftrace_hash
  - kernel/trace/ftrace.c:ftrace_profile_init
```
```
In kernel/trace/trace.c (ffffffff8127ef14)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - kernel/trace/trace.c:create_trace_option_files
  - kernel/trace/trace.c:__tracing_open
```
```
In kernel/trace/tracing_map.c (ffffffff8128fb84)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_elt_alloc
  - kernel/trace/tracing_map.c:tracing_map_elt_alloc
  - kernel/trace/tracing_map.c:tracing_map_elt_alloc
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_syscalls.c (ffffffff836db750)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:init_ftrace_syscalls
```
```
In kernel/trace/trace_events_filter.c (ffffffff812ac335)
Location: include/linux/slab.h:648
Inline: True
```
```
In kernel/trace/trace_events_synth.c (ffffffff812b4d56)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:alloc_synth_event
  - kernel/trace/trace_events_synth.c:alloc_synth_event
```
```
In kernel/trace/trace_events_hist.c (ffffffff812ba7de)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:print_entries
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_alloc
```
```
In kernel/trace/bpf_trace.c (ffffffff812cc3ad)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
```
In kernel/trace/trace_probe.c (ffffffff812d9540)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_expand_meta_args
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
```
```
In kernel/trace/fprobe.c (ffffffff812de665)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - kernel/trace/fprobe.c:register_fprobe_syms
```
```
In kernel/bpf/core.c (ffffffff812ea47f)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
```
```
In kernel/bpf/verifier.c (ffffffff8130a404)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
```
In kernel/bpf/trampoline.c (ffffffff81337d14)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
```
In kernel/bpf/btf.c (ffffffff8134abde)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - kernel/bpf/btf.c:bpf_core_apply
  - kernel/bpf/btf.c:bpf_core_apply
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8135c840)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
```
In kernel/events/core.c (ffffffff81370b16)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/uprobes.c (ffffffff8138320b)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In kernel/watch_queue.c (ffffffff8138964a)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_size
```
```
In mm/slab_common.c (ffffffff813d5cd2)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In mm/list_lru.c (ffffffff813e0329)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
```
```
In mm/vmalloc.c (ffffffff814153b2)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
```
```
In mm/ksm.c (ffffffff8145482e)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - mm/ksm.c:merge_across_nodes_store
```
```
In mm/slub.c (ffffffff8145c1d5)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
```
```
In mm/memory-tiers.c (ffffffff836eb900)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - mm/memory-tiers.c:memory_tier_init
```
```
In fs/pipe.c (ffffffff814be3b8)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - fs/pipe.c:pipe_resize_ring
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/splice.c (ffffffff814fba38)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:iter_file_splice_write
```
```
In fs/aio.c (ffffffff8152952f)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/ext4/extents.c (ffffffff8159ac9d)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_precache
```
```
In fs/squashfs/cache.c (ffffffff81625615)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
```
```
In fs/squashfs/file.c (ffffffff81626398)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - fs/squashfs/file.c:empty_meta_index
```
```
In fs/fuse/file.c (ffffffff816610ca)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages
```
```
In fs/fuse/inode.c (ffffffff81662b19)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_dev_alloc
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff836f4a15)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:init_digests
```
```
In security/security.c (ffffffff836f5705)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - security/security.c:ordered_lsm_init
```
```
In security/selinux/ss/hashtab.c (ffffffff816bad11)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - security/selinux/ss/hashtab.c:hashtab_duplicate
  - security/selinux/ss/hashtab.c:hashtab_init
```
```
In security/selinux/ss/policydb.c (ffffffff816c02ed)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In security/selinux/ss/services.c (ffffffff816cc02a)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
```
```
In security/selinux/ss/conditional.c (ffffffff816ce66d)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_policydb_dup
  - security/selinux/ss/conditional.c:cond_dup_av_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_av_list
```
```
In security/apparmor/policy_unpack.c (ffffffff8170aa1e)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_pdb
  - security/apparmor/policy_unpack.c:unpack_secmark
  - security/apparmor/policy_unpack.c:unpack_xattrs
  - security/apparmor/policy_unpack.c:unpack_trans_table
```
```
In security/apparmor/lsm.c (ffffffff836f8a96)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
```
```
In security/integrity/ima/ima_queue.c (ffffffff836fac35)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_init_digests
```
```
In security/integrity/ima/ima_crypto.c (ffffffff836fb301)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
```
```
In security/integrity/ima/ima_api.c (ffffffff817334e4)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
```
```
In security/integrity/ima/ima_policy.c (ffffffff836fb91d)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
```
```
In security/integrity/ima/ima_template.c (ffffffff817374d2)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_template_data
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff81764c75)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
```
```
In block/partitions/aix.c (ffffffff81792f2c)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In block/blk-crypto-fallback.c (ffffffff817c49b7)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
```
```
In io_uring/kbuf.c (ffffffff817e0185)
Location: include/linux/slab.h:648
Inline: True
```
```
In io_uring/rsrc.c (ffffffff817e3b57)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_sqe_buffers_register
  - io_uring/rsrc.c:io_rsrc_data_alloc
```
```
In lib/string_helpers.c (ffffffff8181d0bf)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - lib/string_helpers.c:kasprintf_strarray
  - lib/string_helpers.c:parse_int_array_user
```
```
In lib/mpi/mpi-mod.c (ffffffff818dbdd9)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - lib/mpi/mpi-mod.c:mpi_barrett_init
```
```
In lib/mpi/mpiutil.c (ffffffff818df32c)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - lib/mpi/mpiutil.c:mpi_resize
  - lib/mpi/mpiutil.c:mpi_resize
```
```
In lib/group_cpus.c (ffffffff818e715f)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - lib/group_cpus.c:group_cpus_evenly
  - lib/group_cpus.c:group_cpus_evenly
  - lib/group_cpus.c:__group_cpus_evenly
```
```
In drivers/gpio/gpiolib.c (ffffffff819047b4)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/pwm/core.c (ffffffff8191266b)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_add
```
```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff819681ef)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_multi_mem_init
```
```
In drivers/rapidio/rio.c (ffffffff8196f8c7)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/video/fbdev/core/fbmon.c (ffffffff8197d3b5)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmon.c:fb_create_modedb
```
```
In drivers/acpi/scan.c (ffffffff819a8662)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_dma_get_range
```
```
In drivers/acpi/acpi_platform.c (ffffffff819b6b3b)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/acpi/acpi_platform.c:acpi_create_platform_device
```
```
In drivers/acpi/sysfs.c (ffffffff819bac80)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
```
```
In drivers/acpi/x86/s2idle.c (ffffffff819befbf)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
```
```
In drivers/acpi/acpi_lpat.c (ffffffff819bfab4)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff8370918f)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/acpi/acpi_adxl.c (ffffffff837097ff)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/acpi/acpi_adxl.c:adxl_init
```
```
In drivers/acpi/processor_idle.c (ffffffff81a1b71e)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
```
```
In drivers/clk/clk.c (ffffffff81a404e7)
Location: include/linux/slab.h:648
Inline: True
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81a4c24c)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
```
```
In drivers/dma/hsu/hsu.c (ffffffff81a50c43)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_prep_slave_sg
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81a5d7c1)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
```
```
In drivers/xen/grant-table.c (ffffffff81a62eb8)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
```
```
In drivers/xen/events/events_base.c (ffffffff83710441)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/mcelog.c (ffffffff81a7b83c)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:bind_virq_for_mce
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81a7caaa)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
```
```
In drivers/xen/xlate_mmu.c (ffffffff83711bbc)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
```
In drivers/regulator/core.c (ffffffff81a8b980)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/tty/tty_io.c (ffffffff81a96079)
Location: include/linux/slab.h:648
Inline: True
```
```
In drivers/tty/vt/consolemap.c (ffffffff81aae6cb)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_insert_unipair
```
```
In drivers/tty/serial/serial_core.c (ffffffff81ac31ce)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:serial_core_add_one_port
  - drivers/tty/serial/serial_core.c:uart_register_driver
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81af3775)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_pcr_allocation
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81af4b6a)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b0b682)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_alloc_dev_scope
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b0d2a6)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_suspend
  - drivers/iommu/intel/iommu.c:copy_translation_tables
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b1b8c7)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:alloc_iommu_pmu
  - drivers/iommu/intel/perfmon.c:alloc_iommu_pmu
  - drivers/iommu/intel/perfmon.c:alloc_iommu_pmu
```
```
In drivers/iommu/iommu.c (ffffffff8371c3fd)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_subsys_init
```
```
In drivers/iommu/iova.c (ffffffff81b267c5)
Location: include/linux/slab.h:648
Inline: True
```
```
In drivers/base/property.c (ffffffff81b43704)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_property_match_string
```
```
In drivers/base/cacheinfo.c (ffffffff81b4671d)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_add_dev
  - drivers/base/cacheinfo.c:allocate_cache_info
```
```
In drivers/base/swnode.c (ffffffff81b47a1e)
Location: include/linux/slab.h:648
Inline: True
```
```
In drivers/base/power/clock_ops.c (0)
Location: include/linux/slab.h:648
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffffffff81b6a11b)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_field_bulk_alloc
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff81b714e4)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_node_alloc
```
```
In drivers/base/regmap/regcache-flat.c (ffffffff81b71985)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-flat.c:regcache_flat_init
```
```
In drivers/base/regmap/regcache-maple.c (ffffffff81b725a7)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-maple.c:regcache_maple_insert_block
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81b774ae)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
```
```
In drivers/base/soc.c (ffffffff81b78639)
Location: include/linux/slab.h:648
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff81b82a5e)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlbd_reserve_minors
```
```
In drivers/misc/sram.c (ffffffff81b886fe)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/mfd/mfd-core.c (ffffffff81b93236)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81bb058c)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81bbfc26)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/scsi/sg.c (ffffffff81bf53eb)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl_common
```
```
In drivers/ata/libata-core.c (ffffffff837203dd)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_parse_force_param
```
```
In drivers/ata/libata-pmp.c (ffffffff81c1da9d)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
```
In drivers/spi/spi.c (ffffffff81c2f4c5)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_board_info
```
```
In drivers/net/phy/mdio-boardinfo.c (ffffffff81c31a3e)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/net/phy/mdio-boardinfo.c:mdiobus_register_board_info
```
```
In drivers/net/virtio_net.c (ffffffff81c4ec1d)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_alloc_queues
  - drivers/net/virtio_net.c:virtnet_alloc_queues
  - drivers/net/virtio_net.c:virtnet_find_vqs
  - drivers/net/virtio_net.c:virtnet_find_vqs
```
```
In drivers/net/xen-netfront.c (ffffffff81c69c8f)
Location: include/linux/slab.h:648
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81c82e03)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/quirks.c (ffffffff81c9c541)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/usb/core/quirks.c:quirks_param_set
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81cb9974)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81cc1696)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:find_tt
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81cd9ce9)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/input/input.c (ffffffff81d0e695)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_abs_params
```
```
In drivers/input/input-mt.c (ffffffff81d12739)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_init_slots
```
```
In drivers/input/ff-core.c (ffffffff81d132b8)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81d18f58)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_get_keymap_from_fwnode
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff81d3c381)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:ptp_populate_pin_groups
  - drivers/ptp/ptp_sysfs.c:ptp_populate_pin_groups
```
```
In drivers/hwmon/hwmon.c (ffffffff81d44dd4)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81d4b395)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:create_trip_attrs
  - drivers/thermal/thermal_sysfs.c:create_trip_attrs
  - drivers/thermal/thermal_sysfs.c:create_trip_attrs
  - drivers/thermal/thermal_sysfs.c:create_trip_attrs
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff81d50690)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:allocate_power
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff81d50fc9)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81d53452)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:hfi_update_work_fn
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_init
```
```
In drivers/md/md-bitmap.c (ffffffff81d6ff91)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
```
```
In drivers/edac/edac_mc.c (ffffffff81d8ab8e)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc_dimms
```
```
In drivers/edac/edac_device.c (ffffffff81d8b6db)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
```
```
In drivers/opp/core.c (ffffffff81d93021)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_set_config
```
```
In drivers/opp/cpu.c (ffffffff81d94874)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81da032f)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81da9dfb)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
```
In drivers/mmc/core/host.c (ffffffff81db742b)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_of_parse_voltage
```
```
In drivers/leds/led-core.c (ffffffff81dc9171)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_get_default_pattern
```
```
In drivers/firmware/efi/capsule.c (ffffffff81dcee79)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In drivers/firmware/efi/apple-properties.c (ffffffff8372fa42)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
```
In drivers/extcon/extcon.c (ffffffff81df32ce)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_alloc_muex
  - drivers/extcon/extcon.c:extcon_alloc_muex
```
```
In drivers/powercap/powercap_sys.c (ffffffff81df5ae3)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:powercap_register_zone
  - drivers/powercap/powercap_sys.c:powercap_register_zone
```
```
In net/core/rtnetlink.c (ffffffff81e50117)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_register_internal
```
```
In net/core/filter.c (ffffffff81e6609f)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - net/core/filter.c:bpf_convert_filter
```
```
In net/sched/sch_mq.c (ffffffff81eaf280)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_init
```
```
In net/sched/cls_api.c (ffffffff81eb6623)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_init_ex
```
```
In net/netlink/af_netlink.c (ffffffff837342c8)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_proto_init
```
```
In net/bpf/bpf_dummy_struct_ops.c (ffffffff81ed10a4)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
```
```
In net/ethtool/ioctl.c (ffffffff81ed5eee)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_self_test
  - net/ethtool/ioctl.c:ethtool_set_rxfh_indir
  - net/ethtool/ioctl.c:ethtool_get_rxfh_indir
  - net/ethtool/ioctl.c:ethtool_get_rxnfc
  - net/ethtool/ioctl.c:ethtool_get_sset_info
```
```
In net/ethtool/common.c (ffffffff81ed8b77)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - net/ethtool/common.c:ethtool_get_max_rxfh_channel
```
```
In net/ethtool/strset.c (ffffffff81edc1b0)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_prepare_set
```
```
In net/ethtool/privflags.c (ffffffff81eded3e)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - net/ethtool/privflags.c:ethnl_get_priv_flags_info
```
```
In net/ipv4/route.c (ffffffff81eed31e)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5d547)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
```
```
In net/ipv4/cipso_ipv4.c (ffffffff83736865)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
```
```
In net/ipv6/addrconf.c (ffffffff81fc25b1)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_init_net
```
```
In net/ipv6/route.c (ffffffff81fcfa78)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/exthdrs.c (ffffffff82001500)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/calipso.c (ffffffff837386b5)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_init
```
```
In net/packet/af_packet.c (ffffffff820263f8)
Location: include/linux/slab.h:648
Inline: True
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff83738cf5)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_init
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff83738e75)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff820544d6)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
```
In net/ncsi/ncsi-rsp.c (ffffffff82062e78)
Location: include/linux/slab.h:648
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
```
```
In arch/x86/pci/xen.c (ffffffff82097abe)
Location: include/linux/slab.h:648
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
In arch/x86/events/amd/iommu.c (ffffffff838b565f)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:_init_events_attrs
```
```
In arch/x86/events/intel/core.c (ffffffff838b6684)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff838b9f15)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_type_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff810348ce)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:spr_update_device_location
  - arch/x86/events/intel/uncore_snbep.c:pmu_set_mapping
  - arch/x86/events/intel/uncore_snbep.c:pmu_set_mapping
  - arch/x86/events/intel/uncore_snbep.c:pmu_set_mapping
  - arch/x86/events/intel/uncore_snbep.c:pmu_set_mapping
  - arch/x86/events/intel/uncore_snbep.c:pmu_set_mapping
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81036db4)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_init_uncores
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
```
```
In arch/x86/hyperv/hv_init.c (ffffffff838c33f2)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff81050a3d)
Location: include/linux/slab.h:656
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81071997)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81086446)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_create_device
```
```
In arch/x86/kernel/cpu/mtrr/if.c (ffffffff8108903d)
Location: include/linux/slab.h:656
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff838d34aa)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_copy_map
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8108d67d)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810944d3)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81094918)
Location: include/linux/slab.h:656
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810b3444)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cluster_probe
```
```
In arch/x86/kernel/hpet.c (ffffffff838e9c35)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In arch/x86/kernel/amd_nb.c (ffffffff810bfdcf)
Location: include/linux/slab.h:656
Inline: True
```
```
In arch/x86/platform/efi/runtime-map.c (ffffffff838f8e3b)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - arch/x86/platform/efi/runtime-map.c:efi_runtime_map_init
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff838f9105)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff810f41fa)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:__arch_prepare_bpf_trampoline
```
```
In kernel/workqueue.c (ffffffff838fbb83)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - kernel/workqueue.c:init_pod_type
  - kernel/workqueue.c:init_pod_type
  - kernel/workqueue.c:init_pod_type
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/sched/fair.c (ffffffff811740b5)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/sched/build_policy.c (ffffffff8117ee69)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:cpudl_init
```
```
In kernel/sched/build_utility.c (ffffffff8119823a)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:cpupri_init
```
```
In kernel/power/energy_model.c (ffffffff811ad0b6)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_create_perf_table
```
```
In kernel/irq/msi.c (ffffffff811c5cf5)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_sysfs_populate_desc
```
```
In kernel/irq/affinity.c (ffffffff811c8261)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/rcu/srcutree.c (ffffffff811cfe96)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_nodes
```
```
In kernel/dma/direct.c (ffffffff811eb10f)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_set_offset
```
```
In kernel/futex/syscalls.c (ffffffff81221134)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - kernel/futex/syscalls.c:__do_sys_futex_waitv
```
```
In kernel/cgroup/rdma.c (ffffffff81244426)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/auditfilter.c (ffffffff812599bd)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_init_entry
  - kernel/auditfilter.c:audit_register_class
```
```
In kernel/trace/ftrace.c (ffffffff81284770)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:alloc_ftrace_hash
  - kernel/trace/ftrace.c:ftrace_profile_init
```
```
In kernel/trace/trace.c (ffffffff81299854)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - kernel/trace/trace.c:create_trace_option_files
  - kernel/trace/trace.c:__tracing_open
```
```
In kernel/trace/tracing_map.c (ffffffff812ab143)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_elt_alloc
  - kernel/trace/tracing_map.c:tracing_map_elt_alloc
  - kernel/trace/tracing_map.c:tracing_map_elt_alloc
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_syscalls.c (ffffffff8390dcc0)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:init_ftrace_syscalls
```
```
In kernel/trace/trace_events_filter.c (ffffffff812c87b5)
Location: include/linux/slab.h:656
Inline: True
```
```
In kernel/trace/trace_events_synth.c (ffffffff812d13a5)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:alloc_synth_event
  - kernel/trace/trace_events_synth.c:alloc_synth_event
```
```
In kernel/trace/trace_events_hist.c (ffffffff812d6e2e)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:print_entries
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_alloc
```
```
In kernel/trace/bpf_trace.c (ffffffff812e982d)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
```
In kernel/trace/trace_probe.c (ffffffff812f7453)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_expand_meta_args
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
```
```
In kernel/trace/trace_btf.c (ffffffff812f850f)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - kernel/trace/trace_btf.c:btf_find_struct_member
```
```
In kernel/trace/fprobe.c (ffffffff812fc3ab)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - kernel/trace/fprobe.c:get_ftrace_locations
```
```
In kernel/bpf/core.c (ffffffff8130878f)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
```
```
In kernel/bpf/verifier.c (ffffffff8132cf15)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
```
In kernel/bpf/trampoline.c (ffffffff8135ddb2)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
```
In kernel/bpf/btf.c (ffffffff813713c5)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - kernel/bpf/btf.c:bpf_core_apply
  - kernel/bpf/btf.c:bpf_core_apply
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff81385b3e)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
```
In kernel/events/core.c (ffffffff81399e16)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/uprobes.c (ffffffff813ac5f9)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In kernel/watch_queue.c (ffffffff813b309a)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_size
```
```
In mm/slab_common.c (ffffffff813ff9a2)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In mm/list_lru.c (ffffffff8140a689)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
```
```
In mm/vmalloc.c (ffffffff81441e77)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
```
```
In mm/slub.c (ffffffff8145d435)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
```
```
In mm/ksm.c (ffffffff8148f0de)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - mm/ksm.c:merge_across_nodes_store
```
```
In mm/memory-tiers.c (ffffffff8391e570)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - mm/memory-tiers.c:memory_tier_init
```
```
In fs/pipe.c (ffffffff814f0838)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - fs/pipe.c:pipe_resize_ring
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/splice.c (ffffffff81530a0d)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:iter_file_splice_write
```
```
In fs/aio.c (ffffffff8155e400)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/ext4/extents.c (ffffffff815d3add)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_precache
```
```
In fs/squashfs/cache.c (ffffffff8165e725)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
```
```
In fs/squashfs/file.c (ffffffff8165f508)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - fs/squashfs/file.c:empty_meta_index
```
```
In fs/fuse/file.c (ffffffff8169af8a)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages
```
```
In fs/fuse/inode.c (ffffffff8169cdf5)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_dev_alloc
```
```
In fs/tracefs/event_inode.c (ffffffff816ab136)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - fs/tracefs/event_inode.c:eventfs_set_attr
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff83927c15)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:init_digests
```
```
In security/security.c (ffffffff816d96a1)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - security/security.c:security_inode_init_security
  - security/security.c:ordered_lsm_init
```
```
In security/selinux/ss/hashtab.c (ffffffff816f7701)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - security/selinux/ss/hashtab.c:hashtab_duplicate
  - security/selinux/ss/hashtab.c:hashtab_init
```
```
In security/selinux/ss/policydb.c (ffffffff816fcbed)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In security/selinux/ss/services.c (ffffffff81708cda)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
```
```
In security/selinux/ss/conditional.c (ffffffff8170ac8d)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_policydb_dup
  - security/selinux/ss/conditional.c:cond_dup_av_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_av_list
```
```
In security/apparmor/policy_unpack.c (ffffffff81748501)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_pdb
  - security/apparmor/policy_unpack.c:unpack_secmark
  - security/apparmor/policy_unpack.c:unpack_xattrs
  - security/apparmor/policy_unpack.c:unpack_trans_table
```
```
In security/apparmor/lsm.c (ffffffff8392bc8b)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - security/apparmor/lsm.c:aa_setup_dfa_engine
```
```
In security/integrity/ima/ima_queue.c (ffffffff8392e235)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_init_digests
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8392e901)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
```
```
In security/integrity/ima/ima_api.c (ffffffff81773f04)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
```
```
In security/integrity/ima/ima_policy.c (ffffffff8392ef0d)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
```
```
In security/integrity/ima/ima_template.c (ffffffff81777fc2)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_template_data
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff817a6895)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
```
```
In block/partitions/aix.c (ffffffff817d683c)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In block/bio-integrity.c (ffffffff817f962d)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_map_user
```
```
In block/blk-crypto-fallback.c (ffffffff818096a6)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
```
```
In io_uring/kbuf.c (ffffffff818245c5)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_init_bl_list
```
```
In io_uring/rsrc.c (ffffffff81827c07)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_sqe_buffers_register
  - io_uring/rsrc.c:io_rsrc_data_alloc
```
```
In io_uring/futex.c (ffffffff8182f4c9)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - io_uring/futex.c:io_futexv_prep
```
```
In lib/string_helpers.c (ffffffff81862f2f)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - lib/string_helpers.c:kasprintf_strarray
  - lib/string_helpers.c:parse_int_array_user
```
```
In lib/crypto/mpi/mpi-mod.c (ffffffff81872999)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - lib/crypto/mpi/mpi-mod.c:mpi_barrett_init
```
```
In lib/crypto/mpi/mpiutil.c (ffffffff81875f5c)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - lib/crypto/mpi/mpiutil.c:mpi_resize
  - lib/crypto/mpi/mpiutil.c:mpi_resize
```
```
In lib/group_cpus.c (ffffffff8192e17f)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - lib/group_cpus.c:group_cpus_evenly
  - lib/group_cpus.c:group_cpus_evenly
  - lib/group_cpus.c:__group_cpus_evenly
```
```
In drivers/gpio/gpiolib.c (ffffffff8194c1ec)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/pwm/core.c (ffffffff8195a4bb)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/pwm/core.c:__pwmchip_add
```
```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff819b18ef)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_multi_mem_init
```
```
In drivers/rapidio/rio.c (ffffffff819b97b7)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/video/fbdev/core/fbmon.c (ffffffff819c8ce5)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmon.c:fb_create_modedb
```
```
In drivers/acpi/utils.c (ffffffff819e5c93)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_evaluate_reference
```
```
In drivers/acpi/scan.c (ffffffff819f1085)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_dma_get_range
```
```
In drivers/acpi/acpi_platform.c (ffffffff81a010eb)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/acpi/acpi_platform.c:acpi_create_platform_device
```
```
In drivers/acpi/sysfs.c (ffffffff81a05360)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
```
```
In drivers/acpi/x86/s2idle.c (ffffffff81a0979f)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
```
```
In drivers/acpi/acpi_lpat.c (ffffffff81a0a474)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff8393c5ef)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/acpi/acpi_adxl.c (ffffffff8393cc8f)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/acpi/acpi_adxl.c:adxl_init
```
```
In drivers/acpi/processor_idle.c (ffffffff81a66a0e)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
```
```
In drivers/acpi/thermal.c (0)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
```
In drivers/clk/clk.c (ffffffff81a8bf07)
Location: include/linux/slab.h:656
Inline: True
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81a97e9c)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
```
```
In drivers/dma/hsu/hsu.c (ffffffff81a9c927)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_alloc_desc
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81aaf771)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
```
```
In drivers/xen/grant-table.c (ffffffff81ab54d8)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
```
```
In drivers/xen/events/events_base.c (ffffffff83943dc1)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/mcelog.c (ffffffff81acdcec)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:bind_virq_for_mce
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81acef5a)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
```
```
In drivers/xen/xlate_mmu.c (ffffffff8394554c)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
```
In drivers/regulator/core.c (ffffffff81ade152)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/tty/tty_io.c (ffffffff81ae8d50)
Location: include/linux/slab.h:656
Inline: True
```
```
In drivers/tty/vt/consolemap.c (ffffffff81b0135f)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_insert_unipair
```
```
In drivers/tty/serial/serial_core.c (ffffffff81b16072)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:serial_core_add_one_port
  - drivers/tty/serial/serial_core.c:uart_register_driver
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81b46d05)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_pcr_allocation
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81b4812a)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b5f727)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_alloc_dev_scope
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b63e18)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:copy_translation_tables
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b71426)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:alloc_iommu_pmu
  - drivers/iommu/intel/perfmon.c:alloc_iommu_pmu
  - drivers/iommu/intel/perfmon.c:alloc_iommu_pmu
```
```
In drivers/iommu/iommu.c (ffffffff8394feed)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_subsys_init
```
```
In drivers/iommu/iova.c (ffffffff81b7db65)
Location: include/linux/slab.h:656
Inline: True
```
```
In drivers/base/property.c (ffffffff81b9b674)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_property_match_string
```
```
In drivers/base/cacheinfo.c (ffffffff81b9ea5d)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_add_dev
  - drivers/base/cacheinfo.c:fetch_cache_info
```
```
In drivers/base/swnode.c (ffffffff81b9fdae)
Location: include/linux/slab.h:656
Inline: True
```
```
In drivers/base/power/qos.c (ffffffff81ba485c)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
```
```
In drivers/base/power/clock_ops.c (0)
Location: include/linux/slab.h:656
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffffffff81bbdddb)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_field_bulk_alloc
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff81bc51fa)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_node_alloc
```
```
In drivers/base/regmap/regcache-flat.c (ffffffff81bc56c5)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-flat.c:regcache_flat_init
```
```
In drivers/base/regmap/regcache-maple.c (ffffffff81bc5da5)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-maple.c:regcache_maple_insert_block
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81bcb2ad)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
```
```
In drivers/base/soc.c (ffffffff81bcc42e)
Location: include/linux/slab.h:656
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff81bd694e)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlbd_reserve_minors
```
```
In drivers/misc/sram.c (ffffffff81bdc5db)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/mfd/mfd-core.c (ffffffff81be71d6)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81c04a1b)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81c143a6)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/scsi/sg.c (ffffffff81c4ad38)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl_common
```
```
In drivers/ata/libata-core.c (ffffffff83953dad)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_parse_force_param
```
```
In drivers/ata/libata-pmp.c (ffffffff81c72b92)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
```
In drivers/gpu/drm/drm_atomic.c (ffffffff81c7b291)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_state_init
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_state_init
```
```
In drivers/gpu/drm/drm_client_modeset.c (ffffffff81c84173)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_probe
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_probe
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_probe
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_probe
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_pick_crtcs
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_create
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_create
```
```
In drivers/gpu/drm/drm_color_mgmt.c (ffffffff81c84e45)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_color_mgmt.c:drm_mode_crtc_set_gamma_size
```
```
In drivers/gpu/drm/drm_edid.c (ffffffff81c94add)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_edid.c:_drm_edid_to_sad
```
```
In drivers/gpu/drm/drm_framebuffer.c (ffffffff81c9af53)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_framebuffer.c:drm_mode_dirtyfb_ioctl
```
```
In drivers/gpu/drm/drm_lease.c (ffffffff81c9edd9)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_lease.c:fill_object_idr
```
```
In drivers/gpu/drm/drm_property.c (ffffffff81cae034)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_property.c:drm_property_create
```
```
In drivers/gpu/drm/drm_syncobj.c (ffffffff81cb01ac)
Location: include/linux/slab.h:656
Inline: True
```
```
In drivers/gpu/drm/drm_debugfs_crc.c (ffffffff81cbbbbd)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_debugfs_crc.c:crtc_crc_open
```
```
In drivers/gpu/drm/drm_crtc_helper.c (ffffffff81cc7546)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config
  - drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config
```
```
In drivers/gpu/drm/drm_damage_helper.c (ffffffff81cc82c1)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_damage_helper.c:drm_atomic_helper_dirtyfb
```
```
In drivers/gpu/drm/drm_plane_helper.c (ffffffff81cccf22)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_plane_helper.c:drm_plane_helper_update_primary
```
```
In drivers/spi/spi.c (ffffffff81ce2385)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_board_info
```
```
In drivers/net/phy/mdio-boardinfo.c (ffffffff81ce672e)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/net/phy/mdio-boardinfo.c:mdiobus_register_board_info
```
```
In drivers/net/virtio_net.c (ffffffff81d0574d)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_alloc_queues
  - drivers/net/virtio_net.c:virtnet_alloc_queues
  - drivers/net/virtio_net.c:virtnet_find_vqs
  - drivers/net/virtio_net.c:virtnet_find_vqs
```
```
In drivers/net/xen-netfront.c (ffffffff81d1e63f)
Location: include/linux/slab.h:656
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81d37786)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/quirks.c (ffffffff81d510e1)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/usb/core/quirks.c:quirks_param_set
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81d6e6e4)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81d7632a)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:find_tt
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81d8ecf9)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/input/input.c (ffffffff81dc42e5)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/input/input-mt.c (ffffffff81dc8339)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_init_slots
```
```
In drivers/input/ff-core.c (ffffffff81dc8ee8)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81dcec78)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_get_keymap_from_fwnode
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff81df2cc1)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:ptp_populate_pin_groups
  - drivers/ptp/ptp_sysfs.c:ptp_populate_pin_groups
```
```
In drivers/hwmon/hwmon.c (ffffffff81dfb961)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_create_attrs
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81e020b5)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:create_trip_attrs
  - drivers/thermal/thermal_sysfs.c:create_trip_attrs
  - drivers/thermal/thermal_sysfs.c:create_trip_attrs
  - drivers/thermal/thermal_sysfs.c:create_trip_attrs
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff81e06bcb)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:allocate_actors_buffer
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff81e07d19)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81e0a192)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:hfi_update_work_fn
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_init
```
```
In drivers/md/md-bitmap.c (ffffffff81e27055)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
```
```
In drivers/edac/edac_mc.c (ffffffff81e424fb)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc_dimms
  - drivers/edac/edac_mc.c:edac_mc_alloc_csrows
  - drivers/edac/edac_mc.c:edac_mc_alloc_csrows
```
```
In drivers/edac/edac_device.c (ffffffff81e42f8a)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
```
```
In drivers/opp/cpu.c (ffffffff81e4c384)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81e581ae)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81e61cd0)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
```
In drivers/mmc/core/host.c (ffffffff81e6f8fb)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_of_parse_voltage
```
```
In drivers/leds/led-core.c (ffffffff81e81c21)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_get_default_pattern
```
```
In drivers/firmware/efi/capsule.c (ffffffff81e87ba9)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In drivers/firmware/efi/apple-properties.c (ffffffff83963f42)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
```
In drivers/platform/x86/amd/wbrf.c (ffffffff81e92ce7)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/platform/x86/amd/wbrf.c:wbrf_record
```
```
In drivers/extcon/extcon.c (ffffffff81ea9922)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_alloc_muex
  - drivers/extcon/extcon.c:extcon_alloc_muex
```
```
In drivers/powercap/powercap_sys.c (ffffffff81eac1a3)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:powercap_register_zone
  - drivers/powercap/powercap_sys.c:powercap_register_zone
```
```
In net/core/rtnetlink.c (ffffffff81f0f19e)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_register_internal
```
```
In net/core/filter.c (ffffffff81f2524f)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - net/core/filter.c:bpf_convert_filter
```
```
In net/sched/sch_mq.c (ffffffff81f71d10)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_init
```
```
In net/sched/cls_api.c (ffffffff81f793e8)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_init_ex
```
```
In net/netlink/af_netlink.c (ffffffff83968808)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_proto_init
```
```
In net/bpf/bpf_dummy_struct_ops.c (ffffffff81f94af6)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
```
```
In net/ethtool/ioctl.c (ffffffff81f99a4e)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_self_test
  - net/ethtool/ioctl.c:ethtool_set_rxfh_indir
  - net/ethtool/ioctl.c:ethtool_get_rxfh_indir
  - net/ethtool/ioctl.c:ethtool_get_rxnfc
  - net/ethtool/ioctl.c:ethtool_get_sset_info
```
```
In net/ethtool/common.c (ffffffff81f9c9d4)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - net/ethtool/common.c:ethtool_get_max_rxfh_channel
```
```
In net/ethtool/strset.c (ffffffff81f9ff80)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_prepare_set
```
```
In net/ethtool/privflags.c (ffffffff81fa2b6e)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - net/ethtool/privflags.c:ethnl_get_priv_flags_info
```
```
In net/ipv4/route.c (ffffffff81fb13dd)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
```
```
In net/ipv4/fib_frontend.c (ffffffff82023ad7)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8396ae85)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
```
```
In net/ipv6/addrconf.c (ffffffff8208fb31)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_init_net
```
```
In net/ipv6/route.c (ffffffff8209d307)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/exthdrs.c (ffffffff820d0340)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/calipso.c (ffffffff8396cd65)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_init
```
```
In net/packet/af_packet.c (ffffffff820f5e08)
Location: include/linux/slab.h:656
Inline: True
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff8396d454)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_init
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff8396d604)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff82126d1a)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
```
In net/ncsi/ncsi-rsp.c (ffffffff82135fb8)
Location: include/linux/slab.h:656
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
```
```
In arch/x86/pci/xen.c (ffffffff8216ef9e)
Location: include/linux/slab.h:656
Inline: True
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
In arch/arm64/kernel/vdso.c (ffff8000114348f4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/arm64/kernel/vdso.c:vdso_init
```
```
In arch/arm64/kernel/suspend.c (ffff800011436018)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/arm64/kernel/suspend.c:cpu_suspend_init
```
```
In arch/arm64/kernel/armv8_deprecated.c (ffff8000114365a4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/arm64/kernel/armv8_deprecated.c:armv8_deprecated_init
```
```
In arch/arm64/mm/context.c (ffff8000100af94c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/arm64/mm/context.c:asids_init
```
```
In arch/arm64/net/bpf_jit_comp.c (ffff8000100b4cbc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/arm64/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In virt/kvm/kvm_main.c (ffff8000100bd18c)
Location: include/linux/slab.h:627
Inline: True
```
```
In virt/kvm/arm/vgic/vgic-init.c (ffff8000100ddef4)
Location: include/linux/slab.h:627
Inline: True
```
```
In virt/kvm/arm/vgic/vgic-irqfd.c (ffff8000100de7e8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-irqfd.c:kvm_vgic_setup_default_irq_routing
```
```
In virt/kvm/arm/vgic/vgic-v4.c (ffff8000100e0920)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-v4.c:vgic_v4_init
```
```
In kernel/workqueue.c (ffff800011442f3c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/sched/fair.c (ffff80001014d3ec)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/sched/rt.c (ffff800010151694)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/sched/rt.c:alloc_rt_sched_group
  - kernel/sched/rt.c:alloc_rt_sched_group
```
```
In kernel/sched/cpupri.c (ffff80001015a054)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/cpudeadline.c (ffff80001015a880)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_init
```
```
In kernel/sched/debug.c (ffff800010161e94)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/irq/affinity.c (ffff8000101881ac)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/cgroup/rdma.c (ffff8000101df608)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/auditfilter.c (ffff8000101ed698)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_register_class
```
```
In kernel/debug/kdb/kdb_main.c (ffff800010200690)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
```
```
In kernel/trace/ftrace.c (ffff800010210744)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:alloc_ftrace_hash
  - kernel/trace/ftrace.c:ftrace_profile_write
```
```
In kernel/trace/trace.c (ffff800010229564)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/trace.c:create_trace_option_files
  - kernel/trace/trace.c:__tracing_open
```
```
In kernel/trace/tracing_map.c (ffff80001022ee88)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_init
  - kernel/trace/tracing_map.c:tracing_map_init
  - kernel/trace/tracing_map.c:tracing_map_init
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_syscalls.c (ffff80001144f584)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:init_ftrace_syscalls
```
```
In kernel/trace/trace_events_filter.c (ffff8000102401f0)
Location: include/linux/slab.h:627
Inline: True
```
```
In kernel/trace/trace_events_hist.c (ffff80001024bf58)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
```
In kernel/trace/bpf_trace.c (ffff80001024ea7c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
```
In kernel/trace/trace_probe.c (ffff800010256d0c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
```
```
In kernel/bpf/core.c (ffff80001025f0a0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
  - kernel/bpf/core.c:bpf_prog_alloc_jited_linfo
```
```
In kernel/bpf/verifier.c (ffff80001026fbcc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
```
In kernel/events/core.c (ffff8000102978b0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/hw_breakpoint.c (ffff8000114514a8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
```
```
In kernel/events/uprobes.c (ffff8000102a75bc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In mm/slab_common.c (ffff8000102e7b1c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In mm/list_lru.c (ffff8000102eeea8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
```
```
In mm/gup.c (ffff8000102f3384)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/vmalloc.c (ffff800010311200)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
```
```
In mm/ksm.c (ffff80001033f6cc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/ksm.c:merge_across_nodes_store
```
```
In mm/slub.c (ffff80001034a378)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
```
```
In fs/pipe.c (ffff80001039196c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/splice.c (ffff8000103cf898)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:iter_file_splice_write
```
```
In fs/aio.c (ffff8000103fb3e4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/io_uring.c (ffff800010403ad4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/io_uring.c:__arm64_sys_io_uring_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/proc/proc_sysctl.c (ffff80001044c464)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:register_leaf_sysctl_tables
```
```
In fs/ext4/extents.c (ffff80001046ac78)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
```
```
In fs/squashfs/block.c (ffff8000104d9858)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/cache.c (ffff8000104dab18)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
```
```
In fs/squashfs/file.c (ffff8000104db998)
Location: include/linux/slab.h:627
Inline: True
```
```
In fs/fuse/file.c (ffff80001050fccc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages
```
```
In fs/fuse/inode.c (ffff800010511b6c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_dev_alloc
```
```
In security/keys/trusted.c (ffff8000114691e8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/keys/trusted.c:init_trusted
```
```
In security/security.c (ffff800011469b20)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/security.c:ordered_lsm_init
```
```
In security/selinux/ss/policydb.c (ffff80001055d810)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In security/selinux/ss/services.c (ffff8000105679ac)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policy
```
```
In security/apparmor/policy_unpack.c (ffff8000105997c4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In security/integrity/ima/ima_queue.c (ffff80001146cb84)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_init_digests
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/slab.h:627
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffff8000105d91c8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
```
```
In block/bio.c (ffff80001146e010)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - block/bio.c:init_bio
```
```
In block/partitions/aix.c (ffff800010600590)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In lib/mpi/mpiutil.c (ffff800010665be8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - lib/mpi/mpiutil.c:mpi_resize
```
```
In lib/sg_split.c (ffff8000106673f8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - lib/sg_split.c:sg_split
```
```
In drivers/irqchip/irq-gic-v2m.c (ffff8000114720bc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_init_one
```
```
In drivers/irqchip/irq-gic-v3.c (ffff800011473254)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_of_init
  - drivers/irqchip/irq-gic-v3.c:gic_populate_ppi_partitions
  - drivers/irqchip/irq-gic-v3.c:gic_populate_ppi_partitions
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
```
```
In drivers/irqchip/irq-gic-v3-mbi.c (ffff800011473700)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-mbi.c:mbi_init
  - drivers/irqchip/irq-gic-v3-mbi.c:mbi_init
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff800011474a94)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_init
  - drivers/irqchip/irq-gic-v3-its.c:its_probe_one
  - drivers/irqchip/irq-gic-v3-its.c:its_create_device
  - drivers/irqchip/irq-gic-v3-its.c:its_create_device
  - drivers/irqchip/irq-gic-v3-its.c:its_lpi_alloc
```
```
In drivers/irqchip/irq-partition-percpu.c (ffff80001067606c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/irqchip/irq-partition-percpu.c:partition_create_desc
```
```
In drivers/irqchip/irq-mtk-sysirq.c (ffff8000114758e0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/irqchip/irq-mtk-sysirq.c:mtk_sysirq_of_init
  - drivers/irqchip/irq-mtk-sysirq.c:mtk_sysirq_of_init
  - drivers/irqchip/irq-mtk-sysirq.c:mtk_sysirq_of_init
  - drivers/irqchip/irq-mtk-sysirq.c:mtk_sysirq_of_init
```
```
In drivers/irqchip/irq-mvebu-odmi.c (ffff800011475f60)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-odmi.c:mvebu_odmi_init
  - drivers/irqchip/irq-mvebu-odmi.c:mvebu_odmi_init
```
```
In drivers/irqchip/qcom-pdc.c (ffff80001067d094)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/irqchip/qcom-pdc.c:qcom_pdc_init
```
```
In drivers/pinctrl/pinconf-generic.c (ffff8000106917c0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_parse_dt_config
```
```
In drivers/pinctrl/pinctrl-ocelot.c (ffff80001069ffc8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
```
```
In drivers/pinctrl/bcm/pinctrl-bcm2835.c (ffff8000106a2f2c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pctl_dt_node_to_map
```
```
In drivers/pinctrl/berlin/berlin.c (ffff8000106a7cd8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/pinctrl/berlin/berlin.c:berlin_pinctrl_probe_regmap
```
```
In drivers/pinctrl/sunxi/pinctrl-sunxi.c (ffff8000106b51e8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_build_state
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pctrl_dt_node_to_map
```
```
In drivers/gpio/gpiolib.c (ffff8000106c56a4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-devprop.c (ffff8000106c764c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
```
```
In drivers/pwm/core.c (ffff8000106d7ffc)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/pci/msi.c (ffff800010713fc0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/pci/msi.c:populate_msi_sysfs
```
```
In drivers/pci/controller/pci-xgene-msi.c (ffff800010725914)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/pci/controller/pci-xgene-msi.c:xgene_msi_probe
```
```
In drivers/rapidio/rio.c (ffff80001073d324)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/video/fbdev/core/fbmon.c (ffff800010747dc8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmon.c:fb_create_modedb
```
```
In drivers/video/fbdev/simplefb.c (ffff800010761610)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/video/of_display_timing.c (ffff80001076206c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/video/of_display_timing.c:of_get_display_timings
```
```
In drivers/acpi/acpi_platform.c (ffff800010777008)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/acpi/sysfs.c (ffff8000107798a4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
```
```
In drivers/acpi/acpi_lpat.c (ffff80001077bf24)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table
```
```
In drivers/acpi/acpi_watchdog.c (ffff80001147eb58)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/acpi/pci_mcfg.c (ffff80001147f3fc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/acpi/pci_mcfg.c:pci_mcfg_parse
```
```
In drivers/acpi/processor_idle.c (ffff8000107a2670)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/acpi/arm64/iort.c (ffff80001148181c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/acpi/arm64/iort.c:iort_add_platform_device
```
```
In drivers/clk/clk.c (ffff8000107c2b54)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
```
```
In drivers/clk/clk-qoriq.c (ffff800011484668)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/clk-qoriq.c:legacy_pll_init
```
```
In drivers/clk/bcm/clk-iproc-pll.c (ffff8000107cc700)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/bcm/clk-iproc-pll.c:iproc_pll_clk_setup
```
```
In drivers/clk/bcm/clk-iproc-asiu.c (ffff800011484d10)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/bcm/clk-iproc-asiu.c:iproc_asiu_setup
```
```
In drivers/clk/hisilicon/clk.c (ffff8000107d0148)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/clk/hisilicon/clkdivider-hi6220.c (ffff8000107d0790)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/hisilicon/clkdivider-hi6220.c:hi6220_register_clkdiv
```
```
In drivers/clk/mediatek/clk-mtk.c (ffff8000107e16f4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/mediatek/clk-mtk.c:mtk_alloc_clk_data
```
```
In drivers/clk/rockchip/clk.c (ffff800011489190)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk.c:rockchip_clk_init
```
```
In drivers/clk/sunxi/clk-sunxi.c (ffff80001148baa8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sunxi.c:sunxi_divs_clk_setup
```
```
In drivers/clk/sunxi/clk-a10-pll2.c (ffff80001148c250)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-a10-pll2.c:sun4i_pll2_setup
```
```
In drivers/clk/sunxi/clk-mod0.c (ffff80001148caf8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-mod0.c:sunxi_mmc_setup
```
```
In drivers/clk/sunxi/clk-simple-gates.c (ffff80001148ce64)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-simple-gates.c:sunxi_simple_gates_setup
```
```
In drivers/clk/sunxi/clk-sun8i-bus-gates.c (ffff80001148d968)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun8i-bus-gates.c:sun8i_h3_bus_gates_init
```
```
In drivers/clk/sunxi/clk-sun8i-mbus.c (ffff80001148db98)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun8i-mbus.c:sun8i_a23_mbus_setup
```
```
In drivers/clk/sunxi/clk-usb.c (ffff80001148e0fc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-usb.c:sunxi_usb_clk_setup
```
```
In drivers/clk/zynqmp/clkc.c (ffff8000107fbebc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/zynqmp/clkc.c:zynqmp_clock_probe
```
```
In drivers/virtio/virtio_pci_common.c (ffff800010828cc4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
```
In drivers/xen/grant-table.c (ffff80001082d05c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
```
```
In drivers/xen/events/events_base.c (ffff8000114919c4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/arm-device.c (ffff80001083c268)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/xen/arm-device.c:xen_map_device_mmio
  - drivers/xen/arm-device.c:xen_map_device_mmio
  - drivers/xen/arm-device.c:xen_map_device_mmio
```
```
In drivers/xen/xlate_mmu.c (ffff800011492300)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
```
In drivers/tty/tty_io.c (ffff8000108511a0)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffff80001088249c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_core.c:uart_register_driver
```
```
In drivers/char/random.c (ffff8000108aff94)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/char/tpm/tpm1-cmd.c (ffff8000108bac40)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_pcr_allocation
```
```
In drivers/char/tpm/tpm2-cmd.c (ffff8000108bcce4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
```
```
In drivers/iommu/arm-smmu.c (ffff8000108d09c8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu.c:arm_smmu_add_device
```
```
In drivers/lightnvm/core.c (ffff8000108e06e0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/base/property.c (ffff8000108f39fc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_property_match_string
```
```
In drivers/base/cacheinfo.c (ffff8000108f45b0)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/base/swnode.c (ffff8000108f62f4)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/base/power/domain.c (ffff800010908038)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/power/domain.c:of_genpd_parse_idle_states
```
```
In drivers/base/power/clock_ops.c (ffff80001090baac)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:of_pm_clk_add_clks
```
```
In drivers/base/regmap/regcache-rbtree.c (ffff800010919e70)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
```
In drivers/base/regmap/regcache-flat.c (ffff80001091a1c4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-flat.c:regcache_flat_init
```
```
In drivers/base/regmap/regmap-irq.c (ffff80001091dddc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/base/arch_topology.c (ffff80001149802c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/arch_topology.c:topology_parse_cpu_capacity
```
```
In drivers/block/xen-blkfront.c (ffff800010929280)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
```
In drivers/misc/sram.c (ffff80001092b1cc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/mfd/mfd-core.c (ffff800010940630)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_devices
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/nvdimm/namespace_devs.c (ffff80001095cca8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/dma-buf/dma-fence.c (ffff800010967340)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/sync_file.c (ffff80001096a20c)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/scsi/sg.c (ffff800010993f48)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
```
```
In drivers/ata/libata-core.c (ffff80001149acf0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_parse_force_param
```
```
In drivers/ata/libata-pmp.c (ffff8000109b4b78)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
```
In drivers/ata/libahci_platform.c (ffff8000109bd4fc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/ata/libahci_platform.c:ahci_platform_get_resources
```
```
In drivers/spi/spi.c (ffff8000109c8380)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_board_info
```
```
In drivers/net/phy/mdio-boardinfo.c (ffff8000109d0400)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/net/phy/mdio-boardinfo.c:mdiobus_register_board_info
```
```
In drivers/net/xen-netfront.c (ffff800010a07ac4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
```
```
In drivers/usb/core/hub.c (ffff800010a1a998)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/usb/core/quirks.c (ffff800010a33a94)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffff800010a4dc9c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/ehci-hcd.c (ffff800010a538e4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:find_tt
```
```
In drivers/usb/host/uhci-hcd.c (ffff800010a6b614)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mtk-sch.c (ffff800010a8e17c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_add_ep_quirk
  - drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_sch_init
```
```
In drivers/input/input.c (ffff800010a975f0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/input/input-mt.c (ffff800010a9a450)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/input/ff-core.c (ffff800010a9ab64)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/ptp/ptp_sysfs.c (ffff800010ac925c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:ptp_populate_pin_groups
  - drivers/ptp/ptp_sysfs.c:ptp_populate_pin_groups
```
```
In drivers/hwmon/hwmon.c (ffff800010ad1840)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/thermal/thermal_sysfs.c (ffff800010ad7a0c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
```
```
In drivers/thermal/of-thermal.c (ffff80001149fcf8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/thermal/of-thermal.c:thermal_of_build_thermal_zone
  - drivers/thermal/of-thermal.c:thermal_of_build_thermal_zone
  - drivers/thermal/of-thermal.c:thermal_of_build_thermal_zone
```
```
In drivers/thermal/power_allocator.c (ffff800010adb418)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In drivers/thermal/cpu_cooling.c (ffff800010adc38c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register
  - drivers/thermal/cpu_cooling.c:cpufreq_get_requested_power
```
```
In drivers/thermal/devfreq_cooling.c (ffff800010add184)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
```
In drivers/md/md-bitmap.c (ffff800010af9090)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
```
```
In drivers/edac/edac_mc.c (ffff800010b10714)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
```
```
In drivers/opp/core.c (ffff800010b1a2b0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
```
```
In drivers/opp/cpu.c (ffff800010b1ad18)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
```
In drivers/opp/of.c (ffff800010b1bd4c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/opp/of.c:_of_init_opp_table
```
```
In drivers/cpuidle/cpuidle-psci.c (ffff8000114a23cc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle-psci.c:psci_idle_init
```
```
In drivers/mmc/core/block.c (ffff800010b42a84)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_ioctl_multi_cmd
```
```
In drivers/leds/led-core.c (ffff800010b48b2c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_get_default_pattern
```
```
In drivers/firmware/efi/capsule.c (ffff800010b5cb20)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In drivers/clocksource/sh_cmt.c (ffff800010b643a8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_setup
```
```
In drivers/clocksource/sh_tmu.c (ffff800010b6568c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_setup
```
```
In drivers/clocksource/arm_arch_timer.c (ffff8000114a99b0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clocksource/arm_arch_timer.c:arch_timer_acpi_init
```
```
In drivers/of/base.c (ffff800010b6a884)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/of/base.c:of_populate_phandle_cache
```
```
In drivers/of/platform.c (ffff800010b6d308)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/of/platform.c:of_device_alloc
```
```
In drivers/of/overlay.c (ffff800010b77a4c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/of/overlay.c:init_overlay_changeset
```
```
In drivers/mailbox/pcc.c (ffff8000114ace30)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
```
In drivers/extcon/extcon.c (ffff800010b88cf4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In drivers/powercap/powercap_sys.c (ffff800010b8fa30)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/nvmem/core.c (ffff800010b9fc84)
Location: include/linux/slab.h:627
Inline: True
```
```
In net/core/ethtool.c (ffff800010bdb304)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_channels
  - net/core/ethtool.c:ethtool_set_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_get_sset_info
```
```
In net/core/rtnetlink.c (ffff800010bebd04)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_register_internal
```
```
In net/core/filter.c (ffff800010bfea34)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/core/filter.c:bpf_convert_filter
```
```
In net/sched/sch_mq.c (ffff800010c3af48)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_init
```
```
In net/netlink/af_netlink.c (ffff8000114b1dd4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_proto_init
```
```
In net/ipv4/route.c (ffff8000114b2058)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
```
```
In net/ipv4/fib_frontend.c (ffff800010cb4400)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
```
```
In net/ipv4/cipso_ipv4.c (ffff8000114b384c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
```
```
In net/ipv6/route.c (ffff800010d12310)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/calipso.c (ffff8000114b5024)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_init
```
```
In net/packet/af_packet.c (ffff800010d5bb18)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/netlabel/netlabel_domainhash.c (ffff8000114b55dc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_init
```
```
In net/netlabel/netlabel_unlabeled.c (ffff8000114b56f4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
```
```
In net/netlabel/netlabel_cipso_v4.c (ffff800010d69fa4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
```
In net/ncsi/ncsi-rsp.c (ffff800010d763dc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
```
```
In net/xdp/xdp_umem.c (ffff800010d81470)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In arch/arm/kernel/suspend.c (c0311a8c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/arm/kernel/suspend.c:cpu_suspend_alloc_sp
```
```
In arch/arm/kernel/topology.c (c15069dc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/arm/kernel/topology.c:init_cpu_topology
```
```
In arch/arm/kernel/vdso.c (c1506df0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/arm/kernel/vdso.c:vdso_init
```
```
In arch/arm/mm/dma-mapping.c (c031e4e8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/arm/mm/dma-mapping.c:arm_iommu_create_mapping
```
```
In arch/arm/net/bpf_jit_32.c (c032c544)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/arm/net/bpf_jit_32.c:bpf_int_jit_compile
```
```
In arch/arm/mach-omap2/omap_hwmod.c (c0339df4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap_hwmod.c:omap_hwmod_init_module
```
```
In arch/arm/mach-omap2/omap_device.c (c1514618)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap_device.c:omap_device_build
  - arch/arm/mach-omap2/omap_device.c:omap_device_build_from_dt
```
```
In arch/arm/mach-omap2/sr_device.c (c15162b8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/arm/mach-omap2/sr_device.c:sr_set_nvalues
```
```
In arch/arm/mach-omap2/prm_common.c (c033f540)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/arm/mach-omap2/prm_common.c:omap_prcm_register_chain_handler
  - arch/arm/mach-omap2/prm_common.c:omap_prcm_register_chain_handler
  - arch/arm/mach-omap2/prm_common.c:omap_prcm_register_chain_handler
```
```
In arch/arm/mach-vexpress/spc.c (c034d46c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/arm/mach-vexpress/spc.c:ve_spc_populate_opps
```
```
In arch/arm/plat-omap/dma.c (c034ee78)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/arm/plat-omap/dma.c:omap_system_dma_probe
```
```
In kernel/workqueue.c (0)
Location: include/linux/slab.h:627
Inline: True
```
```
In kernel/sched/fair.c (c039afe0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/sched/rt.c (c039e944)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/sched/rt.c:alloc_rt_sched_group
  - kernel/sched/rt.c:alloc_rt_sched_group
```
```
In kernel/sched/cpupri.c (c03a6e0c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/cpudeadline.c (c03a7514)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_init
```
```
In kernel/sched/debug.c (c03ae684)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/irq/affinity.c (c03d6bc4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/cgroup/rdma.c (c0420f30)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/auditfilter.c (c042d734)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_register_class
```
```
In kernel/debug/kdb/kdb_main.c (c043f790)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
```
```
In kernel/trace/ftrace.c (c044f6a0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:alloc_ftrace_hash
  - kernel/trace/ftrace.c:ftrace_profile_write
```
```
In kernel/trace/trace.c (c0466b6c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/trace.c:create_trace_option_files
  - kernel/trace/trace.c:__tracing_open
```
```
In kernel/trace/trace_syscalls.c (c1529e08)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:init_ftrace_syscalls
```
```
In kernel/trace/trace_events_filter.c (c047bb50)
Location: include/linux/slab.h:627
Inline: True
```
```
In kernel/trace/bpf_trace.c (c04819d0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
```
In kernel/trace/trace_probe.c (c0489e6c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
```
```
In kernel/bpf/core.c (c0492594)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
  - kernel/bpf/core.c:bpf_prog_alloc_jited_linfo
```
```
In kernel/bpf/verifier.c (c04a1e38)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
```
In kernel/events/core.c (c04c7a70)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/hw_breakpoint.c (c152bf80)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
```
```
In kernel/events/uprobes.c (c04d6674)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In mm/slab_common.c (c050bc10)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In mm/list_lru.c (c0512e10)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
```
```
In mm/gup.c (c05156ec)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/vmalloc.c (c052ab44)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
```
```
In mm/slub.c (c054ec74)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
```
```
In fs/pipe.c (c05781d4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/splice.c (c05aa984)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:iter_file_splice_write
```
```
In fs/aio.c (c05d06d4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/io_uring.c (c05d77f8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/proc/proc_sysctl.c (c0610ed8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:register_leaf_sysctl_tables
```
```
In fs/ext4/extents.c (c062bae8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
```
```
In fs/squashfs/block.c (c069b004)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/cache.c (c069c188)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
```
```
In fs/squashfs/file.c (c069d174)
Location: include/linux/slab.h:627
Inline: True
```
```
In fs/fuse/file.c (c06cb4b8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages
```
```
In fs/fuse/inode.c (c06cd594)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_dev_alloc
```
```
In fs/pstore/ram.c (c06d687c)
Location: include/linux/slab.h:627
Inline: True
```
```
In security/keys/trusted.c (c1541d1c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/keys/trusted.c:init_trusted
```
```
In security/security.c (c15426c0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/security.c:ordered_lsm_init
```
```
In security/selinux/ss/policydb.c (c0713c14)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In security/selinux/ss/services.c (c071bdec)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policy
```
```
In security/apparmor/policy_unpack.c (c074a668)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_trans_table
```
```
In security/integrity/ima/ima_queue.c (c1545810)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_init_digests
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/slab.h:627
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (c07866f0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
```
```
In block/bio.c (c1546ca8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - block/bio.c:init_bio
```
```
In block/partitions/aix.c (c07ab8a8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In lib/mpi/mpiutil.c (c080e6b8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - lib/mpi/mpiutil.c:mpi_resize
```
```
In lib/sg_split.c (c080fbb0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - lib/sg_split.c:sg_split
```
```
In drivers/irqchip/irq-alpine-msi.c (c081353c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/irqchip/irq-alpine-msi.c:alpine_msix_init
```
```
In drivers/irqchip/exynos-combiner.c (c1549964)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/irqchip/exynos-combiner.c:combiner_init
```
```
In drivers/irqchip/irq-gic-v2m.c (c154b334)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/irqchip/irq-gic-v3.c (c154c0ac)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_of_init
  - drivers/irqchip/irq-gic-v3.c:gic_populate_ppi_partitions
  - drivers/irqchip/irq-gic-v3.c:gic_populate_ppi_partitions
```
```
In drivers/irqchip/irq-gic-v3-mbi.c (c154c394)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-mbi.c:mbi_init
  - drivers/irqchip/irq-gic-v3-mbi.c:mbi_init
```
```
In drivers/irqchip/irq-gic-v3-its.c (c154cf88)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_init
  - drivers/irqchip/irq-gic-v3-its.c:its_create_device
  - drivers/irqchip/irq-gic-v3-its.c:its_create_device
  - drivers/irqchip/irq-gic-v3-its.c:its_lpi_alloc
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_set_vcpu_affinity
```
```
In drivers/irqchip/irq-partition-percpu.c (c081e1dc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/irqchip/irq-partition-percpu.c:partition_create_desc
```
```
In drivers/irqchip/irq-crossbar.c (c154d86c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/irqchip/irq-crossbar.c:crossbar_of_init
  - drivers/irqchip/irq-crossbar.c:crossbar_of_init
```
```
In drivers/irqchip/irq-mtk-sysirq.c (c154df04)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/irqchip/irq-mtk-sysirq.c:mtk_sysirq_of_init
  - drivers/irqchip/irq-mtk-sysirq.c:mtk_sysirq_of_init
  - drivers/irqchip/irq-mtk-sysirq.c:mtk_sysirq_of_init
  - drivers/irqchip/irq-mtk-sysirq.c:mtk_sysirq_of_init
```
```
In drivers/irqchip/qcom-pdc.c (c0822c2c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/irqchip/qcom-pdc.c:qcom_pdc_init
```
```
In drivers/bus/arm-cci.c (c0823798)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/bus/arm-cci.c:cci_probe_ports
```
```
In drivers/bus/ti-sysc.c (c0827e7c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/bus/ti-sysc.c:sysc_get_clocks
```
```
In drivers/pinctrl/pinconf-generic.c (c083330c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_parse_dt_config
```
```
In drivers/pinctrl/pinctrl-ocelot.c (c0844b6c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
```
```
In drivers/pinctrl/berlin/berlin.c (c0847d1c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/pinctrl/berlin/berlin.c:berlin_pinctrl_probe_regmap
```
```
In drivers/gpio/gpiolib.c (c08637b0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-devprop.c (c0864f10)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
```
```
In drivers/pwm/core.c (c08758d8)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/pci/msi.c (c089ea38)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/pci/msi.c:populate_msi_sysfs
```
```
In drivers/pci/ecam.c (c08a3560)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/pci/ecam.c:pci_ecam_create
```
```
In drivers/rapidio/rio.c (c08c1ad4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/video/fbdev/core/fbmon.c (c08ca948)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmon.c:fb_create_modedb
```
```
In drivers/video/fbdev/simplefb.c (c08e3bbc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/video/of_display_timing.c (c08e47b0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/video/of_display_timing.c:of_get_display_timings
```
```
In drivers/clk/clk.c (c08ed7c0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
```
```
In drivers/clk/clk-qoriq.c (c1556610)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/clk-qoriq.c:legacy_pll_init
```
```
In drivers/clk/hisilicon/clk.c (c08f7b98)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/clk/hisilicon/clkdivider-hi6220.c (c08f7fec)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/hisilicon/clkdivider-hi6220.c:hi6220_register_clkdiv
```
```
In drivers/clk/hisilicon/clk-hi3620.c (c1557728)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/hisilicon/clk-hi3620.c:hi3620_mmc_clk_init
```
```
In drivers/clk/mediatek/clk-mtk.c (c08fe99c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/mediatek/clk-mtk.c:mtk_alloc_clk_data
```
```
In drivers/clk/mvebu/common.c (c157d03c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/mvebu/common.c:mvebu_clk_gating_setup
  - drivers/clk/mvebu/common.c:mvebu_coreclk_setup
```
```
In drivers/clk/mvebu/clk-cpu.c (c157d234)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/mvebu/clk-cpu.c:of_cpu_clk_setup
  - drivers/clk/mvebu/clk-cpu.c:of_cpu_clk_setup
```
```
In drivers/clk/mvebu/clk-corediv.c (c157d528)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/mvebu/clk-corediv.c:mvebu_corediv_clk_init
  - drivers/clk/mvebu/clk-corediv.c:mvebu_corediv_clk_init
```
```
In drivers/clk/renesas/clk-rz.c (c157e790)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/renesas/clk-rz.c:rz_cpg_clocks_init
```
```
In drivers/clk/renesas/clk-r8a7740.c (c157ecc0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/renesas/clk-r8a7740.c:r8a7740_cpg_clocks_init
```
```
In drivers/clk/renesas/clk-r8a7778.c (c157f32c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/renesas/clk-r8a7778.c:r8a7778_cpg_clocks_init
```
```
In drivers/clk/renesas/clk-r8a7779.c (c157f628)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/renesas/clk-r8a7779.c:r8a7779_cpg_clocks_init
```
```
In drivers/clk/renesas/clk-sh73a0.c (c1580278)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/renesas/clk-sh73a0.c:sh73a0_cpg_clocks_init
```
```
In drivers/clk/renesas/clk-rcar-gen2.c (c1580c58)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/renesas/clk-rcar-gen2.c:rcar_gen2_cpg_clocks_init
```
```
In drivers/clk/rockchip/clk.c (c1582384)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk.c:rockchip_clk_init
```
```
In drivers/clk/samsung/clk.c (c0909a50)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/samsung/clk.c:samsung_clk_alloc_reg_dump
```
```
In drivers/clk/tegra/clk.c (c1585f54)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/tegra/clk.c:tegra_clk_init
  - drivers/clk/tegra/clk.c:tegra_clk_init
```
```
In drivers/clk/tegra/clk-emc.c (c09132cc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-emc.c:tegra_clk_register_emc
```
```
In drivers/clk/tegra/clk-bpmp.c (c09152d0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-bpmp.c:tegra_bpmp_init_clocks
  - drivers/clk/tegra/clk-bpmp.c:tegra_bpmp_init_clocks
```
```
In drivers/clk/ti/dpll.c (c158a3a0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/ti/dpll.c:of_ti_dpll_setup
```
```
In drivers/clk/ti/divider.c (c158b6f0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/ti/divider.c:ti_clk_divider_populate
  - drivers/clk/ti/divider.c:ti_clk_parse_divider_data
```
```
In drivers/clk/ti/apll.c (c158c6b8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/ti/apll.c:of_dra7_apll_setup
```
```
In drivers/dma/ti/edma.c (c092e498)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/dma/ti/edma.c:edma_setup_info_from_dt
```
```
In drivers/dma/ti/dma-crossbar.c (c09333fc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/dma/ti/dma-crossbar.c:ti_dra7_xbar_probe
```
```
In drivers/soc/tegra/pmc.c (c093c934)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/soc/tegra/pmc.c:tegra_powergate_init
```
```
In drivers/soc/tegra/powergate-bpmp.c (c093e394)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/soc/tegra/powergate-bpmp.c:tegra_bpmp_init_powergates
  - drivers/soc/tegra/powergate-bpmp.c:tegra_bpmp_init_powergates
```
```
In drivers/virtio/virtio_pci_common.c (c0946994)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
```
In drivers/tty/tty_io.c (c095db38)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/tty/serial/serial_core.c (c097fa14)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_core.c:uart_register_driver
```
```
In drivers/char/tpm/tpm1-cmd.c (c09b409c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_pcr_allocation
```
```
In drivers/char/tpm/tpm2-cmd.c (c09b6080)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
```
```
In drivers/iommu/omap-iommu.c (c09c35f8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/iommu/omap-iommu.c:_omap_iommu_add_device
  - drivers/iommu/omap-iommu.c:omap_iommu_attach_dev
```
```
In drivers/iommu/tegra-smmu.c (c09c8504)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/lightnvm/core.c (c09cf298)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/base/property.c (c09e01a0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_property_match_string
```
```
In drivers/base/cacheinfo.c (c09e0ad4)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/base/swnode.c (c09e23c4)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/base/power/domain.c (c09f28f4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/power/domain.c:of_genpd_parse_idle_states
```
```
In drivers/base/power/clock_ops.c (c09f4fe4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:of_pm_clk_add_clks
```
```
In drivers/base/regmap/regcache-rbtree.c (c09ffac8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
```
In drivers/base/regmap/regcache-flat.c (c09ffdb8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-flat.c:regcache_flat_init
```
```
In drivers/base/regmap/regmap-irq.c (c0a031f8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/base/arch_topology.c (c1598d38)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/arch_topology.c:topology_parse_cpu_capacity
```
```
In drivers/misc/sram.c (c0a09910)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/mfd/mfd-core.c (c0a29cdc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_devices
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/dma-buf/dma-fence.c (c0a3dc8c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/sync_file.c (c0a4025c)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/scsi/sg.c (c0a64a78)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
```
```
In drivers/ata/libata-core.c (c159bbb8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_parse_force_param
```
```
In drivers/ata/libata-pmp.c (c0a8399c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
```
In drivers/ata/libahci_platform.c (c0a88338)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/ata/libahci_platform.c:ahci_platform_get_resources
```
```
In drivers/mtd/parsers/ofpart.c (c0a974c8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/mtd/parsers/ofpart.c:parse_ofoldpart_partitions
  - drivers/mtd/parsers/ofpart.c:parse_fixed_partitions
```
```
In drivers/mtd/nand/bbt.c (c0a9a0fc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/mtd/nand/bbt.c:nanddev_bbt_init
```
```
In drivers/spi/spi.c (c0ab1f64)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_board_info
```
```
In drivers/net/phy/mdio-boardinfo.c (c0ab861c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/net/phy/mdio-boardinfo.c:mdiobus_register_board_info
```
```
In drivers/usb/core/hub.c (c0af27b4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/quirks.c (c0b07338)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (c0b1fde8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/ehci-hcd.c (c0b27d64)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:find_tt
```
```
In drivers/usb/host/uhci-hcd.c (c0b3e588)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mtk-sch.c (c0b608d8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_add_ep_quirk
  - drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_sch_init
```
```
In drivers/input/input.c (c0b7a6fc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/input/input-mt.c (c0b7c08c)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/input/ff-core.c (c0b7cb58)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/ptp/ptp_sysfs.c (c0ba8a44)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:ptp_populate_pin_groups
  - drivers/ptp/ptp_sysfs.c:ptp_populate_pin_groups
```
```
In drivers/hwmon/hwmon.c (c0bb25b0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_create_attrs
```
```
In drivers/thermal/thermal_sysfs.c (c0bb7f68)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
```
```
In drivers/thermal/of-thermal.c (c15a21a4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/thermal/of-thermal.c:thermal_of_build_thermal_zone
  - drivers/thermal/of-thermal.c:thermal_of_build_thermal_zone
  - drivers/thermal/of-thermal.c:thermal_of_build_thermal_zone
```
```
In drivers/thermal/power_allocator.c (c0bbb70c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In drivers/thermal/cpu_cooling.c (c0bbc8e8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register
  - drivers/thermal/cpu_cooling.c:cpufreq_get_requested_power
```
```
In drivers/thermal/devfreq_cooling.c (c0bbd6f0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
```
In drivers/md/md-bitmap.c (c0bda004)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
```
```
In drivers/edac/edac_mc.c (c0beeb48)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
```
```
In drivers/opp/core.c (c0bf4ef4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
```
```
In drivers/opp/cpu.c (c0bf57cc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
```
In drivers/opp/of.c (c0bf65d0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/opp/of.c:_of_init_opp_table
```
```
In drivers/opp/ti-opp-supply.c (c0bf79bc)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/cpuidle/cpuidle-psci.c (c15a4958)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle-psci.c:psci_dt_cpu_init_idle
```
```
In drivers/mmc/core/block.c (c0c1b7ec)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_ioctl_multi_cmd
```
```
In drivers/leds/led-core.c (c0c32918)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_get_default_pattern
```
```
In drivers/firmware/efi/capsule.c (c0c3d6a8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In drivers/clocksource/sh_cmt.c (c0c44e24)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_setup
```
```
In drivers/clocksource/sh_mtu2.c (c0c45554)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clocksource/sh_mtu2.c:sh_mtu2_setup
```
```
In drivers/clocksource/sh_tmu.c (c0c465f4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_setup
```
```
In drivers/of/base.c (c0c4de74)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/of/base.c:of_populate_phandle_cache
```
```
In drivers/of/platform.c (c0c503bc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/of/platform.c:of_device_alloc
```
```
In drivers/of/overlay.c (c0c599f0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/of/overlay.c:init_overlay_changeset
```
```
In drivers/extcon/extcon.c (c0c6dcd4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In drivers/memory/samsung/exynos-srom.c (c0c733a8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/memory/samsung/exynos-srom.c:exynos_srom_probe
```
```
In drivers/powercap/powercap_sys.c (c0c79ac4)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/nvmem/core.c (c0c81610)
Location: include/linux/slab.h:627
Inline: True
```
```
In sound/core/timer.c (c0c8e1d0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - sound/core/timer.c:realloc_user_queue
  - sound/core/timer.c:realloc_user_queue
```
```
In sound/core/pcm_native.c (c0c936c0)
Location: include/linux/slab.h:627
Inline: True
```
```
In sound/soc/soc-core.c (c0ca2b58)
Location: include/linux/slab.h:627
Inline: True
```
```
In sound/soc/soc-dapm.c (c0cac850)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - sound/soc/soc-dapm.c:snd_soc_dapm_new_widgets
```
```
In sound/soc/soc-topology.c (c0cba50c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - sound/soc/soc-topology.c:soc_tplg_process_headers
  - sound/soc/soc-topology.c:soc_tplg_dapm_widget_create
  - sound/soc/soc-topology.c:soc_tplg_dapm_widget_create
  - sound/soc/soc-topology.c:soc_tplg_dapm_widget_denum_create
  - sound/soc/soc-topology.c:soc_tplg_dapm_widget_denum_create
```
```
In net/core/ethtool.c (c0cf6a20)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_channels
  - net/core/ethtool.c:ethtool_set_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_get_sset_info
```
```
In net/core/rtnetlink.c (c0d0482c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_register_internal
```
```
In net/core/filter.c (c0d1a110)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/core/filter.c:bpf_convert_filter
```
```
In net/sched/sch_mq.c (c0d4cf2c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_init
```
```
In net/netlink/af_netlink.c (c15b70a4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_proto_init
```
```
In net/ipv4/route.c (c15b7310)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
```
```
In net/ipv4/fib_frontend.c (c0dbf7d8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
```
```
In net/ipv4/cipso_ipv4.c (c15b8b24)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
```
```
In net/ipv6/route.c (c0e18038)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/calipso.c (c15ba2e8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_init
```
```
In net/packet/af_packet.c (c0e5bc64)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/netlabel/netlabel_domainhash.c (c15ba874)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_init
```
```
In net/netlabel/netlabel_unlabeled.c (c15ba9b0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
```
```
In net/netlabel/netlabel_cipso_v4.c (c0e68508)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
```
In net/ncsi/ncsi-rsp.c (c0e735f4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
```
```
In net/xdp/xdp_umem.c (c0e7ba28)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In arch/powerpc/kernel/vdso.c (c0000000013484b8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/powerpc/kernel/vdso.c:vdso_init
```
```
In arch/powerpc/mm/drmem.c (c0000000013549cc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/powerpc/mm/drmem.c:drmem_init
  - arch/powerpc/mm/drmem.c:drmem_init
```
```
In arch/powerpc/mm/numa.c (c0000000000a3450)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/powerpc/mm/numa.c:numa_update_cpu_topology
```
```
In arch/powerpc/sysdev/mpic.c (c00000000135871c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/powerpc/sysdev/mpic.c:mpic_alloc
```
```
In arch/powerpc/sysdev/xive/native.c (c000000001359fa4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/native.c:xive_native_init
```
```
In arch/powerpc/platforms/powernv/opal-async.c (c00000000135bab0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-async.c:opal_async_comp_init
```
```
In arch/powerpc/platforms/powernv/idle.c (c0000000000c88ac)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/idle.c:pnv_parse_cpuidle_dt
  - arch/powerpc/platforms/powernv/idle.c:pnv_parse_cpuidle_dt
  - arch/powerpc/platforms/powernv/idle.c:pnv_parse_cpuidle_dt
  - arch/powerpc/platforms/powernv/idle.c:pnv_parse_cpuidle_dt
```
```
In arch/powerpc/platforms/powernv/opal-sysparam.c (c00000000135d2bc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-sysparam.c:opal_sys_param_init
  - arch/powerpc/platforms/powernv/opal-sysparam.c:opal_sys_param_init
  - arch/powerpc/platforms/powernv/opal-sysparam.c:opal_sys_param_init
  - arch/powerpc/platforms/powernv/opal-sysparam.c:opal_sys_param_init
```
```
In arch/powerpc/platforms/powernv/opal-irqchip.c (c00000000135dba4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-irqchip.c:opal_event_init
```
```
In arch/powerpc/platforms/powernv/opal-powercap.c (c00000000135e11c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-powercap.c:opal_powercap_init
  - arch/powerpc/platforms/powernv/opal-powercap.c:opal_powercap_init
  - arch/powerpc/platforms/powernv/opal-powercap.c:opal_powercap_init
```
```
In arch/powerpc/platforms/powernv/opal-psr.c (c00000000135e450)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-psr.c:opal_psr_init
```
```
In arch/powerpc/platforms/powernv/opal-sensor-groups.c (c00000000135e820)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-sensor-groups.c:opal_sensor_groups_init
  - arch/powerpc/platforms/powernv/opal-sensor-groups.c:opal_sensor_groups_init
  - arch/powerpc/platforms/powernv/opal-sensor-groups.c:opal_sensor_groups_init
```
```
In arch/powerpc/platforms/powernv/opal-imc.c (c0000000000e01e4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-imc.c:opal_imc_counters_probe
  - arch/powerpc/platforms/powernv/opal-imc.c:opal_imc_counters_probe
  - arch/powerpc/platforms/powernv/opal-imc.c:opal_imc_counters_probe
```
```
In arch/powerpc/platforms/powernv/memtrace.c (c0000000000e09a4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/memtrace.c:memtrace_init_regions_runtime
```
```
In arch/powerpc/platforms/pseries/lpar.c (c0000000000eaba4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/lpar.c:vcpudispatch_stats_write
  - arch/powerpc/platforms/pseries/lpar.c:vcpudispatch_stats_write
```
```
In arch/powerpc/platforms/pseries/hotplug-cpu.c (c0000000000fa758)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_cpu
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_cpu
```
```
In arch/powerpc/net/bpf_jit_comp64.c (c000000000108d40)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/powerpc/net/bpf_jit_comp64.c:bpf_int_jit_compile
```
```
In arch/powerpc/perf/imc-pmu.c (c00000000012cf90)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/powerpc/perf/imc-pmu.c:init_imc_pmu
  - arch/powerpc/perf/imc-pmu.c:init_imc_pmu
  - arch/powerpc/perf/imc-pmu.c:init_imc_pmu
  - arch/powerpc/perf/imc-pmu.c:init_imc_pmu
  - arch/powerpc/perf/imc-pmu.c:init_imc_pmu
```
```
In kernel/workqueue.c (c000000001366eb8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/sched/fair.c (c0000000001a0238)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/sched/rt.c (c0000000001a4f28)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/sched/rt.c:alloc_rt_sched_group
  - kernel/sched/rt.c:alloc_rt_sched_group
```
```
In kernel/sched/cpupri.c (c0000000001ae304)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/cpudeadline.c (c0000000001aeb4c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_init
```
```
In kernel/sched/debug.c (c0000000001b8114)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/irq/affinity.c (c0000000001e221c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/cgroup/rdma.c (c00000000024d9c4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/auditfilter.c (c00000000025feb8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_register_class
```
```
In kernel/debug/kdb/kdb_main.c (c0000000002782e8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
```
```
In kernel/trace/ftrace.c (c000000000290144)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:alloc_ftrace_hash
  - kernel/trace/ftrace.c:ftrace_profile_write
```
```
In kernel/trace/trace.c (c0000000002b0b5c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/trace.c:create_trace_option_files
  - kernel/trace/trace.c:__tracing_open
```
```
In kernel/trace/tracing_map.c (c0000000002b85e0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_init
  - kernel/trace/tracing_map.c:tracing_map_init
  - kernel/trace/tracing_map.c:tracing_map_init
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_syscalls.c (c000000001376608)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:init_ftrace_syscalls
```
```
In kernel/trace/trace_events_filter.c (c0000000002d0b20)
Location: include/linux/slab.h:627
Inline: True
```
```
In kernel/trace/trace_events_hist.c (c0000000002e7218)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
```
In kernel/trace/bpf_trace.c (c0000000002eace4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
```
In kernel/trace/trace_probe.c (c0000000002f8110)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
```
```
In kernel/bpf/core.c (c000000000304080)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
  - kernel/bpf/core.c:bpf_prog_alloc_jited_linfo
```
```
In kernel/bpf/verifier.c (c000000000316a10)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
```
In kernel/events/core.c (c0000000003471b0)
Location: include/linux/slab.h:627
Inline: True
```
```
In kernel/events/hw_breakpoint.c (c000000001378f50)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
```
```
In kernel/events/uprobes.c (c00000000035aa98)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In mm/slab_common.c (c0000000003a9980)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In mm/list_lru.c (c0000000003b3540)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
```
```
In mm/gup.c (c0000000003b9d80)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/vmalloc.c (c0000000003e2cbc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
```
```
In mm/ksm.c (c00000000041bd70)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/ksm.c:merge_across_nodes_store
```
```
In mm/slub.c (c0000000004293a8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
```
```
In fs/pipe.c (c0000000004899e0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/splice.c (c0000000004d0300)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:iter_file_splice_write
```
```
In fs/aio.c (c000000000508390)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/io_uring.c (c00000000051094c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/proc/proc_sysctl.c (c000000000563cd0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:register_leaf_sysctl_tables
```
```
In fs/ext4/extents.c (c00000000058a110)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
```
```
In fs/squashfs/block.c (c000000000614140)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/cache.c (c000000000615858)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
```
```
In fs/squashfs/file.c (c000000000616ab4)
Location: include/linux/slab.h:627
Inline: True
```
```
In fs/fuse/file.c (c000000000657454)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages
```
```
In fs/fuse/inode.c (c00000000065a0b8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_dev_alloc
```
```
In security/keys/trusted.c (c0000000013972c8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/keys/trusted.c:init_trusted
```
```
In security/security.c (c000000001397df4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/security.c:ordered_lsm_init
```
```
In security/selinux/ss/policydb.c (c0000000006c0398)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In security/selinux/ss/services.c (c0000000006cae88)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policy
```
```
In security/apparmor/policy_unpack.c (c0000000007109b0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In security/integrity/ima/ima_queue.c (c00000000139ba4c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_init_digests
```
```
In security/integrity/ima/ima_policy.c (c00000000139c47c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
```
```
In crypto/asymmetric_keys/verify_pefile.c (c000000000768fec)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
```
```
In block/bio.c (c00000000139d854)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - block/bio.c:init_bio
```
```
In block/partitions/aix.c (c00000000079ad68)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In lib/mpi/mpiutil.c (c00000000081b460)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - lib/mpi/mpiutil.c:mpi_resize
```
```
In drivers/pinctrl/pinconf-generic.c (c00000000082d980)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_parse_dt_config
```
```
In drivers/pinctrl/pinctrl-ocelot.c (c00000000083892c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
```
```
In drivers/gpio/gpiolib.c (c000000000842328)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-devprop.c (c0000000008441f0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
```
```
In drivers/pwm/core.c (c000000000850428)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/pci/pci-sysfs.c (c00000000086bbb4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_create_legacy_files
```
```
In drivers/pci/msi.c (c0000000008837b0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/pci/msi.c:populate_msi_sysfs
```
```
In drivers/rapidio/rio.c (c0000000008951a4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/video/fbdev/core/fbmon.c (c0000000008a8cec)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmon.c:fb_create_modedb
```
```
In drivers/video/of_display_timing.c (c0000000008c5d70)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/video/of_display_timing.c:of_get_display_timings
```
```
In drivers/virtio/virtio_pci_common.c (c0000000008d5348)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
```
In drivers/tty/tty_io.c (c0000000008f22c8)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/tty/serial/serial_core.c (c00000000092582c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_core.c:uart_register_driver
```
```
In drivers/char/random.c (c00000000094984c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/char/tpm/tpm1-cmd.c (c00000000095c120)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_pcr_allocation
```
```
In drivers/char/tpm/tpm2-cmd.c (c00000000095e9dc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
```
```
In drivers/lightnvm/core.c (c000000000974aa4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/base/property.c (c00000000098d818)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_property_match_string
```
```
In drivers/base/cacheinfo.c (c00000000098e5a0)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/base/swnode.c (c00000000099150c)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/base/power/domain.c (c0000000009a7c00)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/power/domain.c:of_genpd_parse_idle_states
```
```
In drivers/base/regmap/regcache-rbtree.c (c0000000009bde10)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
```
In drivers/base/regmap/regcache-flat.c (c0000000009be208)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-flat.c:regcache_flat_init
```
```
In drivers/base/regmap/regmap-irq.c (c0000000009c2c04)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/misc/sram.c (c0000000009ca358)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/mfd/mfd-core.c (c0000000009e8fc0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_devices
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/nvdimm/namespace_devs.c (c000000000a0e3c4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/dma-buf/dma-fence.c (c000000000a1ef00)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/sync_file.c (c000000000a22b38)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/scsi/sg.c (c000000000a55ecc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
```
```
In drivers/ata/libata-core.c (c0000000013aed50)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_parse_force_param
```
```
In drivers/ata/libata-pmp.c (c000000000a7dbc0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
```
In drivers/spi/spi.c (c000000000a89ad0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_board_info
```
```
In drivers/net/phy/mdio-boardinfo.c (c000000000a8f668)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/net/phy/mdio-boardinfo.c:mdiobus_register_board_info
```
```
In drivers/vfio/pci/vfio_pci.c (c000000000ab5e64)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (c000000000ab8e6c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
```
```
In drivers/usb/core/hub.c (c000000000ad3da8)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/usb/core/quirks.c (c000000000af1120)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (c000000000b154d8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/ehci-hcd.c (c000000000b21c90)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:find_tt
```
```
In drivers/usb/host/uhci-hcd.c (c000000000b3ce34)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/input/input.c (c000000000b781a8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/input/input-mt.c (c000000000b7a494)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/input/ff-core.c (c000000000b7b618)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/ptp/ptp_sysfs.c (c000000000baafd0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:ptp_populate_pin_groups
  - drivers/ptp/ptp_sysfs.c:ptp_populate_pin_groups
```
```
In drivers/hwmon/hwmon.c (c000000000bb6474)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/thermal/thermal_sysfs.c (c000000000bbe48c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
```
```
In drivers/thermal/of-thermal.c (c0000000013b6358)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/thermal/of-thermal.c:thermal_of_build_thermal_zone
  - drivers/thermal/of-thermal.c:thermal_of_build_thermal_zone
  - drivers/thermal/of-thermal.c:thermal_of_build_thermal_zone
```
```
In drivers/thermal/power_allocator.c (c000000000bc2f68)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In drivers/thermal/cpu_cooling.c (c000000000bc4748)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register
  - drivers/thermal/cpu_cooling.c:cpufreq_get_requested_power
```
```
In drivers/thermal/devfreq_cooling.c (c000000000bc59d8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
```
In drivers/md/md-bitmap.c (c000000000be71cc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
```
```
In drivers/edac/edac_mc.c (c000000000c04278)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
```
```
In drivers/opp/core.c (c000000000c0bf44)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
```
```
In drivers/opp/cpu.c (c000000000c0ccd0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
```
In drivers/opp/of.c (c000000000c0e23c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/opp/of.c:_of_init_opp_table
```
```
In drivers/cpufreq/powernv-cpufreq.c (c0000000013b8778)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_init
  - drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_init
```
```
In drivers/leds/led-core.c (c000000000c3d900)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_get_default_pattern
```
```
In drivers/of/base.c (c000000000c4410c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/of/base.c:of_populate_phandle_cache
```
```
In drivers/of/platform.c (c000000000c47abc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/of/platform.c:of_device_alloc
```
```
In drivers/of/overlay.c (c000000000c56780)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/of/overlay.c:init_overlay_changeset
```
```
In drivers/extcon/extcon.c (c000000000c68f90)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In drivers/powercap/powercap_sys.c (c000000000c6e9c0)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/nvmem/core.c (c000000000c73360)
Location: include/linux/slab.h:627
Inline: True
```
```
In net/core/ethtool.c (c000000000cbc344)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_channels
  - net/core/ethtool.c:ethtool_set_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_get_sset_info
```
```
In net/core/rtnetlink.c (c000000000ccf170)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_register_internal
```
```
In net/core/filter.c (c000000000ce99fc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/core/filter.c:bpf_convert_filter
```
```
In net/sched/sch_mq.c (c000000000d34150)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_init
```
```
In net/netlink/af_netlink.c (c0000000013c2b14)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_proto_init
```
```
In net/ipv4/route.c (c0000000013c2ea0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
```
```
In net/ipv4/fib_frontend.c (c000000000dcc780)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
```
In net/ipv4/cipso_ipv4.c (c0000000013c4eb8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
```
```
In net/ipv6/route.c (c000000000e3e560)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/calipso.c (c0000000013c6f3c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_init
```
```
In net/packet/af_packet.c (c000000000e974b0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/netlabel/netlabel_domainhash.c (c0000000013c7774)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_init
```
```
In net/netlabel/netlabel_unlabeled.c (c0000000013c7928)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
```
```
In net/netlabel/netlabel_cipso_v4.c (c000000000ea706c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
```
In net/ncsi/ncsi-rsp.c (c000000000eb6b88)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
```
```
In net/xdp/xdp_umem.c (c000000000ec1390)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In arch/riscv/kernel/vdso.c (ffffffe00000333c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/riscv/kernel/vdso.c:vdso_init
```
```
In arch/riscv/net/bpf_jit_comp.c (ffffffe0000be22c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/riscv/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/workqueue.c (0)
Location: include/linux/slab.h:627
Inline: True
```
```
In kernel/sched/fair.c (ffffffe0000f6740)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/sched/rt.c (ffffffe0000f9964)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/sched/rt.c:alloc_rt_sched_group
  - kernel/sched/rt.c:alloc_rt_sched_group
```
```
In kernel/sched/cpupri.c (ffffffe0000ffabe)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/cpudeadline.c (ffffffe0001000f4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_init
```
```
In kernel/sched/debug.c (ffffffe000105c28)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/irq/affinity.c (ffffffe00011d934)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/cgroup/rdma.c (ffffffe0001566b6)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/auditfilter.c (ffffffe000161c24)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_register_class
```
```
In kernel/trace/ftrace.c (ffffffe0001712fa)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:alloc_ftrace_hash
  - kernel/trace/ftrace.c:ftrace_profile_write
```
```
In kernel/trace/trace.c (ffffffe000183c6c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/trace.c:create_trace_option_files
  - kernel/trace/trace.c:__tracing_open
```
```
In kernel/trace/trace_syscalls.c (ffffffe00000f998)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:init_ftrace_syscalls
```
```
In kernel/trace/trace_events_filter.c (ffffffe00019555c)
Location: include/linux/slab.h:627
Inline: True
```
```
In kernel/bpf/core.c (ffffffe00019d1a4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
  - kernel/bpf/core.c:bpf_prog_alloc_jited_linfo
```
```
In kernel/bpf/verifier.c (ffffffe0001a9432)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
```
In kernel/events/core.c (ffffffe0001ca43c)
Location: include/linux/slab.h:627
Inline: True
```
```
In mm/slab_common.c (ffffffe0001fd624)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In mm/list_lru.c (ffffffe000202db6)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
```
```
In mm/gup.c (ffffffe000205628)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/vmalloc.c (ffffffe000218e6a)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
```
```
In mm/slub.c (ffffffe00023bc9e)
Location: include/linux/slab.h:627
Inline: True
```
```
In fs/pipe.c (ffffffe000260db0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/splice.c (ffffffe00028b840)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:iter_file_splice_write
```
```
In fs/aio.c (ffffffe0002aac42)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/io_uring.c (ffffffe0002b1202)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/proc/proc_sysctl.c (ffffffe0002e15cc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:register_leaf_sysctl_tables
```
```
In fs/ext4/extents.c (ffffffe0002f84a0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
```
```
In fs/squashfs/block.c (ffffffe00034ea20)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/cache.c (ffffffe00034fa24)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
```
```
In fs/squashfs/file.c (ffffffe00035067e)
Location: include/linux/slab.h:627
Inline: True
```
```
In fs/fuse/file.c (ffffffe00037a520)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages
```
```
In fs/fuse/inode.c (ffffffe00037c3bc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_dev_alloc
```
```
In security/keys/trusted.c (ffffffe000024428)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/keys/trusted.c:init_trusted
```
```
In security/security.c (ffffffe000024c9c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/security.c:ordered_lsm_init
```
```
In security/selinux/ss/policydb.c (ffffffe0003b650c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In security/selinux/ss/services.c (ffffffe0003bd51c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policy
```
```
In security/apparmor/policy_unpack.c (ffffffe0003e5ec6)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In security/integrity/ima/ima_queue.c (ffffffe00002735a)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_init_digests
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/slab.h:627
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffe00041d044)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
```
In block/bio.c (ffffffe00002873e)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - block/bio.c:init_bio
```
```
In block/partitions/aix.c (ffffffe00043bd2e)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In lib/mpi/mpiutil.c (ffffffe000491df6)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - lib/mpi/mpiutil.c:mpi_resize
```
```
In drivers/pinctrl/pinconf-generic.c (ffffffe00049cf22)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_parse_dt_config
```
```
In drivers/pinctrl/pinctrl-ocelot.c (ffffffe0004a3be8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
```
```
In drivers/gpio/gpiolib.c (ffffffe0004a9ae8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-devprop.c (ffffffe0004aafc8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
```
```
In drivers/pwm/core.c (ffffffe0004b1fd0)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/pci/msi.c (ffffffe0004dda74)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/pci/msi.c:populate_msi_sysfs
```
```
In drivers/rapidio/rio.c (ffffffe0004ed1e0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/video/fbdev/core/fbmon.c (ffffffe0004f66d0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmon.c:fb_create_modedb
```
```
In drivers/video/fbdev/simplefb.c (ffffffe00050831a)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/video/of_display_timing.c (ffffffe000508c28)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/video/of_display_timing.c:of_get_display_timings
```
```
In drivers/clk/clk.c (ffffffe00051056e)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
```
```
In drivers/virtio/virtio_pci_common.c (ffffffe00051f072)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
```
In drivers/tty/tty_io.c (ffffffe00052f32a)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffe00054caf0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_core.c:uart_register_driver
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffe00056b698)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_pcr_allocation
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffe00056ee2a)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
```
```
In drivers/lightnvm/core.c (ffffffe0005765aa)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/base/property.c (ffffffe000585006)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_property_match_string
```
```
In drivers/base/cacheinfo.c (ffffffe000585b58)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/base/swnode.c (ffffffe0005872b6)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/base/power/domain.c (ffffffe00058f0fe)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/power/domain.c:of_genpd_parse_idle_states
```
```
In drivers/base/power/clock_ops.c (ffffffe000591420)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:of_pm_clk_add_clks
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffe000599fcc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
```
In drivers/base/regmap/regcache-flat.c (ffffffe00059a2ba)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-flat.c:regcache_flat_init
```
```
In drivers/base/regmap/regmap-irq.c (ffffffe00059d554)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/base/arch_topology.c (ffffffe0000317e8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/arch_topology.c:topology_parse_cpu_capacity
```
```
In drivers/misc/sram.c (ffffffe0005a2b0e)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/mfd/mfd-core.c (ffffffe0005b3fd2)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_devices
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/nvdimm/namespace_devs.c (ffffffe0005cafc4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/dma-buf/dma-fence.c (ffffffe0005d3b14)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/sync_file.c (ffffffe0005d5b3a)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/scsi/sg.c (ffffffe0005f5e72)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
```
```
In drivers/ata/libata-core.c (ffffffe00003407c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_parse_force_param
```
```
In drivers/ata/libata-pmp.c (ffffffe000610f5e)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
```
In drivers/spi/spi.c (ffffffe000618884)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_board_info
```
```
In drivers/net/phy/mdio-boardinfo.c (ffffffe00061cfd4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/net/phy/mdio-boardinfo.c:mdiobus_register_board_info
```
```
In drivers/usb/core/hub.c (ffffffe00063ef8c)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/usb/core/quirks.c (ffffffe0006517d8)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffe00066a6fe)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/ehci-hcd.c (ffffffe000671046)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:find_tt
```
```
In drivers/usb/host/uhci-hcd.c (ffffffe000685834)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/input/input.c (ffffffe0006a8b12)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/input/input-mt.c (ffffffe0006aad6e)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/input/ff-core.c (ffffffe0006ab674)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/ptp/ptp_sysfs.c (ffffffe0006c73fa)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:ptp_populate_pin_groups
  - drivers/ptp/ptp_sysfs.c:ptp_populate_pin_groups
```
```
In drivers/hwmon/hwmon.c (ffffffe0006ce1ee)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/thermal/thermal_sysfs.c (ffffffe0006d2688)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
```
```
In drivers/thermal/of-thermal.c (ffffffe000037be6)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/thermal/of-thermal.c:thermal_of_build_thermal_zone
  - drivers/thermal/of-thermal.c:thermal_of_build_thermal_zone
  - drivers/thermal/of-thermal.c:thermal_of_build_thermal_zone
```
```
In drivers/thermal/power_allocator.c (ffffffe0006d555a)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In drivers/thermal/devfreq_cooling.c (ffffffe0006d6424)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
```
In drivers/md/md-bitmap.c (ffffffe0006eb26a)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
```
```
In drivers/edac/edac_mc.c (ffffffe0006fd746)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
```
```
In drivers/opp/core.c (ffffffe000702a76)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
```
```
In drivers/opp/of.c (ffffffe000703f14)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/opp/of.c:_of_init_opp_table
```
```
In drivers/mmc/core/block.c (ffffffe0007173b8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_ioctl_multi_cmd
```
```
In drivers/leds/led-core.c (ffffffe00071cb6c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_get_default_pattern
```
```
In drivers/of/base.c (ffffffe00072003e)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/of/base.c:of_populate_phandle_cache
```
```
In drivers/of/platform.c (ffffffe000722100)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/of/platform.c:of_device_alloc
```
```
In drivers/of/overlay.c (ffffffe00072b024)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/of/overlay.c:init_overlay_changeset
```
```
In drivers/extcon/extcon.c (ffffffe000731e3c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In drivers/powercap/powercap_sys.c (ffffffe0007354ce)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/nvmem/core.c (ffffffe000737d6e)
Location: include/linux/slab.h:627
Inline: True
```
```
In net/core/ethtool.c (ffffffe000763474)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_channels
  - net/core/ethtool.c:ethtool_set_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_get_sset_info
```
```
In net/core/rtnetlink.c (ffffffe00076faf6)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_register_internal
```
```
In net/core/filter.c (ffffffe000780a14)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/core/filter.c:bpf_convert_filter
```
```
In net/sched/sch_mq.c (ffffffe0007abd2a)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_init
```
```
In net/netlink/af_netlink.c (ffffffe000040a98)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_proto_init
```
```
In net/ipv4/route.c (ffffffe000040d3c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
```
```
In net/ipv4/fib_frontend.c (ffffffe00080c154)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
```
```
In net/ipv4/cipso_ipv4.c (ffffffe000042604)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
```
```
In net/ipv6/route.c (ffffffe000858740)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/calipso.c (ffffffe000043e4a)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_init
```
```
In net/packet/af_packet.c (ffffffe000891e8e)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/netlabel/netlabel_domainhash.c (ffffffe00004441e)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_init
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffe00004452e)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffe00089cdaa)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
```
In net/ncsi/ncsi-rsp.c (ffffffe0008a6d54)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
```
```
In net/xdp/xdp_umem.c (ffffffe0008ad8ec)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In arch/x86/events/amd/iommu.c (ffffffff8288e495)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:_init_events_attrs
```
```
In arch/x86/events/intel/uncore.c (ffffffff82890d98)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_types_init
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8289707f)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81045335)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81052382)
Location: include/linux/slab.h:627
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (ffffffff81054a3e)
Location: include/linux/slab.h:627
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81059555)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105e2ec)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
```
```
In arch/x86/kernel/hpet.c (ffffffff828a92c0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81075d2b)
Location: include/linux/slab.h:627
Inline: True
```
```
In kernel/workqueue.c (ffffffff828b4623)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/sched/fair.c (ffffffff810e6f25)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/sched/cpupri.c (ffffffff810ef6ce)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/cpudeadline.c (ffffffff810efba9)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_init
```
```
In kernel/sched/debug.c (ffffffff810f5de3)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/irq/affinity.c (ffffffff8111a592)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/cgroup/rdma.c (ffffffff8116398c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/auditfilter.c (ffffffff81170b49)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_register_class
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81180fba)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
```
```
In kernel/trace/ftrace.c (ffffffff811905e8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:alloc_ftrace_hash
  - kernel/trace/ftrace.c:ftrace_profile_init
```
```
In kernel/trace/trace.c (ffffffff811a4b5e)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/trace.c:create_trace_option_files
  - kernel/trace/trace.c:__tracing_open
```
```
In kernel/trace/tracing_map.c (ffffffff811a9856)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_init
  - kernel/trace/tracing_map.c:tracing_map_init
  - kernel/trace/tracing_map.c:tracing_map_init
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_syscalls.c (ffffffff828bfb5c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:init_ftrace_syscalls
```
```
In kernel/trace/trace_events_filter.c (ffffffff811b917b)
Location: include/linux/slab.h:627
Inline: True
```
```
In kernel/trace/trace_events_hist.c (ffffffff811c4852)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
```
In kernel/trace/bpf_trace.c (ffffffff811c6e66)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
```
In kernel/trace/trace_probe.c (ffffffff811cf03f)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
```
```
In kernel/bpf/core.c (ffffffff811d6645)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
  - kernel/bpf/core.c:bpf_prog_alloc_jited_linfo
```
```
In kernel/bpf/verifier.c (ffffffff811e48f7)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
```
In kernel/events/core.c (ffffffff812080ab)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/hw_breakpoint.c (ffffffff828c18c0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
```
```
In kernel/events/uprobes.c (ffffffff812142ce)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In mm/slab_common.c (ffffffff81249029)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In mm/list_lru.c (ffffffff8124fa5d)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
```
```
In mm/gup.c (ffffffff812545df)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/vmalloc.c (ffffffff81272578)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
```
```
In mm/ksm.c (ffffffff81298515)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/ksm.c:merge_across_nodes_store
```
```
In mm/slub.c (ffffffff812a0f25)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
```
```
In fs/pipe.c (ffffffff812e0e6c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/splice.c (ffffffff8130fae8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:iter_file_splice_write
```
```
In fs/aio.c (ffffffff813379f8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/io_uring.c (ffffffff8133df05)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/proc/proc_sysctl.c (ffffffff81377410)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:register_leaf_sysctl_tables
```
```
In fs/ext4/extents.c (ffffffff81390697)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
```
```
In fs/squashfs/block.c (ffffffff813f410d)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/cache.c (ffffffff813f5184)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
```
```
In fs/squashfs/file.c (ffffffff813f5f56)
Location: include/linux/slab.h:627
Inline: True
```
```
In fs/fuse/file.c (ffffffff814243c8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages
```
```
In fs/fuse/inode.c (ffffffff81426329)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_dev_alloc
```
```
In security/keys/trusted.c (ffffffff828d83c3)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/keys/trusted.c:init_trusted
```
```
In security/security.c (ffffffff828d8b2d)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/security.c:ordered_lsm_init
```
```
In security/selinux/ss/policydb.c (ffffffff81468933)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In security/selinux/ss/services.c (ffffffff814700de)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policy
```
```
In security/apparmor/policy_unpack.c (ffffffff8149be55)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In security/integrity/ima/ima_queue.c (ffffffff828db636)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_init_digests
```
```
In security/integrity/ima/ima_policy.c (ffffffff828dbc7f)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814d5244)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
```
```
In block/bio.c (ffffffff828dc870)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - block/bio.c:init_bio
```
```
In block/partitions/aix.c (ffffffff814f6fb8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In lib/mpi/mpiutil.c (ffffffff81551ac7)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - lib/mpi/mpiutil.c:mpi_resize
```
```
In drivers/gpio/gpiolib.c (ffffffff81564ca7)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-devprop.c (ffffffff81566ac7)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
```
```
In drivers/pwm/core.c (ffffffff8156c11b)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/pci/msi.c (ffffffff8159e131)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/pci/msi.c:populate_msi_sysfs
```
```
In drivers/rapidio/rio.c (ffffffff815a9367)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/video/fbdev/core/fbmon.c (ffffffff815b3455)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmon.c:fb_create_modedb
```
```
In drivers/acpi/acpi_platform.c (ffffffff815daf34)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/acpi/sysfs.c (ffffffff815dd76e)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
```
```
In drivers/acpi/acpi_lpat.c (ffffffff815dfee4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff828e4617)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/acpi/acpi_adxl.c (ffffffff828e47de)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/acpi/acpi_adxl.c:adxl_init
```
```
In drivers/acpi/processor_idle.c (ffffffff81603ed4)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/clk/clk.c (ffffffff8161803f)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff8161bdd8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81625c11)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
```
In drivers/xen/grant-table.c (ffffffff81629481)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
```
```
In drivers/xen/events/events_base.c (ffffffff828e7233)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/mcelog.c (ffffffff8163a9f6)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:bind_virq_for_mce
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff8163b4dd)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:push_pxx_to_hypervisor
  - drivers/xen/xen-acpi-processor.c:push_cxx_to_hypervisor
```
```
In drivers/xen/xlate_mmu.c (ffffffff828e7f80)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
```
In drivers/tty/tty_io.c (ffffffff8164b1cc)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff8166bc3e)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_core.c:uart_register_driver
```
```
In drivers/char/random.c (ffffffff81684e95)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81695dc5)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_pcr_allocation
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81697ce6)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
```
```
In drivers/iommu/dmar.c (ffffffff816ad77b)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_alloc_dev_scope
```
```
In drivers/iommu/intel-iommu.c (ffffffff828ee3ae)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:iommu_init_domains
```
```
In drivers/lightnvm/core.c (ffffffff816bc15b)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/base/property.c (ffffffff816cbfd5)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_property_match_string
```
```
In drivers/base/cacheinfo.c (ffffffff816cc835)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/base/swnode.c (ffffffff816cda5c)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/base/power/clock_ops.c (0)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff816eb4ef)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
```
In drivers/base/regmap/regcache-flat.c (ffffffff816eb7d6)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-flat.c:regcache_flat_init
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff816ee2cf)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/block/xen-blkfront.c (ffffffff816f7a3b)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
```
In drivers/misc/sram.c (ffffffff816fa4e6)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/mfd/mfd-core.c (ffffffff81702575)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_devices
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8170fcd3)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8171b263)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/sync_file.c (ffffffff8171d55a)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff81740458)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
```
```
In drivers/nvme/host/pci.c (ffffffff8174d8d6)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_alloc_host_mem
```
```
In drivers/ata/libata-core.c (ffffffff828f2edc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_parse_force_param
```
```
In drivers/ata/libata-pmp.c (ffffffff8176d22b)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
```
In drivers/spi/spi.c (ffffffff8177976c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_board_info
```
```
In drivers/net/phy/mdio-boardinfo.c (ffffffff8177c765)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/net/phy/mdio-boardinfo.c:mdiobus_register_board_info
```
```
In drivers/net/xen-netfront.c (ffffffff81793515)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
```
```
In drivers/usb/core/hub.c (ffffffff817a3b29)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/usb/core/quirks.c (ffffffff817b802f)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817ccf10)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817d3b63)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:find_tt
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817e8add)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/input/input.c (ffffffff8180d902)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/input/input-mt.c (ffffffff8180f437)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/input/ff-core.c (ffffffff8180fea7)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff818279ac)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:ptp_populate_pin_groups
  - drivers/ptp/ptp_sysfs.c:ptp_populate_pin_groups
```
```
In drivers/hwmon/hwmon.c (ffffffff8182a9ea)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff8182fdd5)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
```
```
In drivers/thermal/power_allocator.c (ffffffff818325ed)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff81833718)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
```
In drivers/md/md-bitmap.c (ffffffff8184a87c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
```
```
In drivers/edac/edac_mc.c (ffffffff8185e3b5)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
```
```
In drivers/opp/core.c (ffffffff81863797)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
```
```
In drivers/opp/cpu.c (ffffffff818643dc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8186d047)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81871c90)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
```
In drivers/leds/led-core.c (ffffffff818880b1)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_get_default_pattern
```
```
In drivers/firmware/efi/capsule.c (ffffffff8188c541)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff828fdabc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
```
```
In drivers/firmware/efi/apple-properties.c (ffffffff828fe0f2)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
```
In drivers/mailbox/pcc.c (ffffffff828fef21)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
```
In drivers/extcon/extcon.c (ffffffff8189d797)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In drivers/nvmem/core.c (ffffffff818a2c6b)
Location: include/linux/slab.h:627
Inline: True
```
```
In arch/x86/pci/xen.c (ffffffff818a51bc)
Location: include/linux/slab.h:627
Inline: True
```
```
In net/core/ethtool.c (ffffffff818dcb80)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_channels
  - net/core/ethtool.c:ethtool_set_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_get_sset_info
```
```
In net/core/rtnetlink.c (ffffffff818ea003)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_register_internal
```
```
In net/core/filter.c (ffffffff818fdc57)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/core/filter.c:bpf_convert_filter
```
```
In net/sched/sch_mq.c (ffffffff8192f192)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_init
```
```
In net/netlink/af_netlink.c (ffffffff82906086)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_proto_init
```
```
In net/ipv4/route.c (ffffffff829062cb)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
```
```
In net/ipv4/fib_frontend.c (ffffffff8199cb93)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8290775c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
```
```
In net/ipv6/route.c (ffffffff819ed0fa)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/calipso.c (ffffffff82908d01)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_init
```
```
In net/packet/af_packet.c (ffffffff81a2dfca)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff829091e5)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_init
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff829092c3)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a397fa)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81a4416d)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
```
```
In net/xdp/xdp_umem.c (ffffffff81a4bf86)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In arch/x86/events/amd/iommu.c (ffffffff8288c3fb)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:_init_events_attrs
```
```
In arch/x86/events/intel/uncore.c (ffffffff8288ec7d)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_types_init
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8288f399)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81034845)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81041d72)
Location: include/linux/slab.h:627
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (ffffffff81044abe)
Location: include/linux/slab.h:627
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81049775)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8104e61c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
```
```
In arch/x86/kernel/hpet.c (ffffffff828a136c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81065d0c)
Location: include/linux/slab.h:627
Inline: True
```
```
In kernel/workqueue.c (ffffffff828ac7a4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/sched/fair.c (ffffffff810d60c5)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/sched/rt.c (ffffffff810d9425)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/sched/rt.c:alloc_rt_sched_group
  - kernel/sched/rt.c:alloc_rt_sched_group
```
```
In kernel/sched/cpupri.c (ffffffff810df73e)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/cpudeadline.c (ffffffff810dfc19)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_init
```
```
In kernel/sched/debug.c (ffffffff810e5fa3)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/irq/affinity.c (ffffffff8110b602)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/cgroup/rdma.c (ffffffff81156bdc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/auditfilter.c (ffffffff81163ce9)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_register_class
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff811740fa)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
```
```
In kernel/trace/ftrace.c (ffffffff81183978)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:alloc_ftrace_hash
  - kernel/trace/ftrace.c:ftrace_profile_init
```
```
In kernel/trace/trace.c (ffffffff81197b0e)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/trace.c:create_trace_option_files
  - kernel/trace/trace.c:__tracing_open
```
```
In kernel/trace/tracing_map.c (ffffffff8119c7d6)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_init
  - kernel/trace/tracing_map.c:tracing_map_init
  - kernel/trace/tracing_map.c:tracing_map_init
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_syscalls.c (ffffffff828b81fc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:init_ftrace_syscalls
```
```
In kernel/trace/trace_events_filter.c (ffffffff811abf5b)
Location: include/linux/slab.h:627
Inline: True
```
```
In kernel/trace/trace_events_hist.c (ffffffff811b7632)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
```
In kernel/trace/bpf_trace.c (ffffffff811b9c46)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
```
In kernel/trace/trace_probe.c (ffffffff811c1e0f)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
```
```
In kernel/bpf/core.c (ffffffff811c9405)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
  - kernel/bpf/core.c:bpf_prog_alloc_jited_linfo
```
```
In kernel/bpf/verifier.c (ffffffff811d76b7)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
```
In kernel/events/core.c (ffffffff811fb1d8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/hw_breakpoint.c (ffffffff828b9f60)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
```
```
In kernel/events/uprobes.c (ffffffff8120703e)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In mm/slab_common.c (ffffffff8123bfd9)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In mm/list_lru.c (ffffffff812429fd)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
```
```
In mm/gup.c (ffffffff8124722f)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/vmalloc.c (ffffffff812644e8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
```
```
In mm/ksm.c (ffffffff8128a0d5)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/ksm.c:merge_across_nodes_store
```
```
In mm/slub.c (ffffffff81292a05)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
```
```
In fs/pipe.c (ffffffff812d1aac)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/splice.c (ffffffff813006f8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:iter_file_splice_write
```
```
In fs/aio.c (ffffffff81328728)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/io_uring.c (ffffffff8132ebc5)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/proc/proc_sysctl.c (ffffffff81367ee0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:register_leaf_sysctl_tables
```
```
In fs/ext4/extents.c (ffffffff81381127)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
```
```
In fs/squashfs/block.c (ffffffff813e4b8d)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/cache.c (ffffffff813e5c04)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
```
```
In fs/squashfs/file.c (ffffffff813e69d6)
Location: include/linux/slab.h:627
Inline: True
```
```
In fs/fuse/file.c (ffffffff81414e48)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages
```
```
In fs/fuse/inode.c (ffffffff81416da9)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_dev_alloc
```
```
In security/keys/trusted.c (ffffffff828d0adf)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/keys/trusted.c:init_trusted
```
```
In security/security.c (ffffffff828d1249)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/security.c:ordered_lsm_init
```
```
In security/selinux/ss/policydb.c (ffffffff81459363)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In security/selinux/ss/services.c (ffffffff81460afe)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policy
```
```
In security/apparmor/policy_unpack.c (ffffffff8148c875)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In security/integrity/ima/ima_queue.c (ffffffff828d3d52)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_init_digests
```
```
In security/integrity/ima/ima_policy.c (ffffffff828d439b)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814c5c64)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
```
```
In block/bio.c (ffffffff828d4f8c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - block/bio.c:init_bio
```
```
In block/partitions/aix.c (ffffffff814e74c8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In lib/mpi/mpiutil.c (ffffffff81541da7)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - lib/mpi/mpiutil.c:mpi_resize
```
```
In drivers/gpio/gpiolib.c (ffffffff81555af7)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-devprop.c (ffffffff81557917)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
```
```
In drivers/pci/msi.c (ffffffff8158d2c1)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/pci/msi.c:populate_msi_sysfs
```
```
In drivers/rapidio/rio.c (ffffffff81598507)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/video/fbdev/core/fbmon.c (ffffffff815a24f5)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmon.c:fb_create_modedb
```
```
In drivers/acpi/sleep.c (ffffffff815b5830)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:lpi_device_get_constraints
```
```
In drivers/acpi/acpi_platform.c (ffffffff815c6574)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/acpi/sysfs.c (ffffffff815c8dae)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
```
```
In drivers/acpi/acpi_lpat.c (ffffffff815cb524)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff828dc6be)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/acpi/acpi_adxl.c (ffffffff828dc885)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/acpi/acpi_adxl.c:adxl_init
```
```
In drivers/acpi/processor_idle.c (ffffffff815eef84)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/clk/clk.c (ffffffff8160c56f)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81610308)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8161a291)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
```
In drivers/tty/tty_io.c (ffffffff8162b61c)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff8164ad9e)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_core.c:uart_register_driver
```
```
In drivers/char/random.c (ffffffff81662b35)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff816737b5)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_pcr_allocation
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816756d6)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
```
```
In drivers/iommu/dmar.c (ffffffff8168b0db)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_alloc_dev_scope
```
```
In drivers/iommu/intel-iommu.c (ffffffff8168e570)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_suspend
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:iommu_init_domains
```
```
In drivers/base/property.c (ffffffff816a7305)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_property_match_string
```
```
In drivers/base/cacheinfo.c (ffffffff816a7b65)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/base/swnode.c (ffffffff816a8d8c)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/base/power/clock_ops.c (0)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff816c5b2f)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
```
In drivers/base/regmap/regcache-flat.c (ffffffff816c5e16)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-flat.c:regcache_flat_init
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff816c890f)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/misc/sram.c (ffffffff816ce2f6)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/mfd/mfd-core.c (ffffffff816d6385)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_devices
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816e3753)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/btt.c (ffffffff816edbbf)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/nvdimm/btt.c:btt_meta_init
  - drivers/nvdimm/btt.c:btt_meta_init
  - drivers/nvdimm/btt.c:discover_arenas
  - drivers/nvdimm/btt.c:discover_arenas
```
```
In drivers/dma-buf/dma-fence.c (ffffffff816f46c3)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/sync_file.c (ffffffff816f69ba)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/scsi/storvsc_drv.c (ffffffff81712ff5)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/scsi/storvsc_drv.c:storvsc_channel_init
```
```
In drivers/scsi/sg.c (ffffffff817220ec)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
```
```
In drivers/nvme/host/pci.c (ffffffff8172d776)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_alloc_host_mem
```
```
In drivers/ata/libata-core.c (ffffffff828ea387)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_parse_force_param
```
```
In drivers/ata/libata-pmp.c (ffffffff8174d07b)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
```
In drivers/spi/spi.c (ffffffff8175951c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_board_info
```
```
In drivers/net/phy/mdio-boardinfo.c (ffffffff8175c515)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/net/phy/mdio-boardinfo.c:mdiobus_register_board_info
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff81780d0b)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff81782f55)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
```
```
In drivers/usb/core/hub.c (ffffffff8179569a)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/usb/core/quirks.c (ffffffff817a9a5f)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/input/input.c (ffffffff817d5072)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/input/input-mt.c (ffffffff817d6b87)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/input/ff-core.c (ffffffff817d75f7)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff817ef03c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:ptp_populate_pin_groups
  - drivers/ptp/ptp_sysfs.c:ptp_populate_pin_groups
```
```
In drivers/hwmon/hwmon.c (ffffffff817f207a)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff817f7465)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
```
```
In drivers/thermal/power_allocator.c (ffffffff817f9c7d)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff817fada8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
```
In drivers/md/md-bitmap.c (ffffffff81811eac)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
```
```
In drivers/edac/edac_mc.c (ffffffff81825985)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
```
```
In drivers/opp/core.c (ffffffff8182c447)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
```
```
In drivers/opp/cpu.c (ffffffff8182d08c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81835dc7)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8183b480)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
```
In drivers/leds/led-core.c (ffffffff8183fa31)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_get_default_pattern
```
```
In drivers/firmware/efi/capsule.c (ffffffff81843ec1)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff828f5358)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
```
```
In drivers/firmware/efi/apple-properties.c (ffffffff828f598e)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
```
In drivers/mailbox/pcc.c (ffffffff828f6a26)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
```
In drivers/hv/hv.c (ffffffff8184f7b8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/hv/hv.c:hv_synic_alloc
```
```
In drivers/hv/ring_buffer.c (ffffffff818539f3)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/hv/ring_buffer.c:hv_ringbuffer_init
```
```
In drivers/nvmem/core.c (ffffffff8185e3db)
Location: include/linux/slab.h:627
Inline: True
```
```
In net/core/ethtool.c (ffffffff818969c0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_channels
  - net/core/ethtool.c:ethtool_set_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_get_sset_info
```
```
In net/core/rtnetlink.c (ffffffff818a3e43)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_register_internal
```
```
In net/core/filter.c (ffffffff818b7a87)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/core/filter.c:bpf_convert_filter
```
```
In net/sched/sch_mq.c (ffffffff818e8c92)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_init
```
```
In net/netlink/af_netlink.c (ffffffff828fe3d4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_proto_init
```
```
In net/ipv4/route.c (ffffffff828fe619)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
```
```
In net/ipv4/fib_frontend.c (ffffffff81956653)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
```
In net/ipv4/cipso_ipv4.c (ffffffff828ffaaa)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
```
```
In net/ipv6/route.c (ffffffff819a9eba)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/calipso.c (ffffffff8290104f)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_init
```
```
In net/packet/af_packet.c (ffffffff819eb1ba)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff82901533)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_init
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff82901611)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f641a)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81a00d5d)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
```
```
In net/xdp/xdp_umem.c (ffffffff81a08b76)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In arch/x86/events/amd/iommu.c (ffffffff828a1495)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:_init_events_attrs
```
```
In arch/x86/events/intel/uncore.c (ffffffff828a3d98)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_types_init
```
```
In arch/x86/hyperv/hv_init.c (ffffffff828aa06f)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81045175)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81052232)
Location: include/linux/slab.h:627
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (ffffffff81054e6e)
Location: include/linux/slab.h:627
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81059985)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105e71c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
```
```
In arch/x86/kernel/hpet.c (ffffffff828bc1bf)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81075cdb)
Location: include/linux/slab.h:627
Inline: True
```
```
In kernel/workqueue.c (ffffffff828c7522)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/sched/fair.c (ffffffff810e32f5)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/sched/rt.c (ffffffff810e6595)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/sched/rt.c:alloc_rt_sched_group
  - kernel/sched/rt.c:alloc_rt_sched_group
```
```
In kernel/sched/cpupri.c (ffffffff810ec7fe)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/cpudeadline.c (ffffffff810eccd9)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_init
```
```
In kernel/sched/debug.c (ffffffff810f2fe3)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/irq/affinity.c (ffffffff81118482)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/cgroup/rdma.c (ffffffff8116175c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/auditfilter.c (ffffffff8116e919)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_register_class
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8117ed8a)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
```
```
In kernel/trace/ftrace.c (ffffffff8118e3b8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:alloc_ftrace_hash
  - kernel/trace/ftrace.c:ftrace_profile_init
```
```
In kernel/trace/trace.c (ffffffff811a292e)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/trace.c:create_trace_option_files
  - kernel/trace/trace.c:__tracing_open
```
```
In kernel/trace/tracing_map.c (ffffffff811a7626)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_init
  - kernel/trace/tracing_map.c:tracing_map_init
  - kernel/trace/tracing_map.c:tracing_map_init
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_syscalls.c (ffffffff828d28df)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:init_ftrace_syscalls
```
```
In kernel/trace/trace_events_filter.c (ffffffff811b6f4b)
Location: include/linux/slab.h:627
Inline: True
```
```
In kernel/trace/trace_events_hist.c (ffffffff811c2622)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
```
In kernel/trace/bpf_trace.c (ffffffff811c4c36)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
```
In kernel/trace/trace_probe.c (ffffffff811cce0f)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
```
```
In kernel/bpf/core.c (ffffffff811d4415)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
  - kernel/bpf/core.c:bpf_prog_alloc_jited_linfo
```
```
In kernel/bpf/verifier.c (ffffffff811e26c7)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
```
In kernel/events/core.c (ffffffff81205e7b)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/hw_breakpoint.c (ffffffff828d4643)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
```
```
In kernel/events/uprobes.c (ffffffff8121206e)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In mm/slab_common.c (ffffffff81246dc9)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In mm/list_lru.c (ffffffff8124d7fd)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
```
```
In mm/gup.c (ffffffff8125237f)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/vmalloc.c (ffffffff81270318)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
```
```
In mm/ksm.c (ffffffff81296325)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/ksm.c:merge_across_nodes_store
```
```
In mm/slub.c (ffffffff8129ed35)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
```
```
In fs/pipe.c (ffffffff812dec7c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/splice.c (ffffffff8130d8d8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:iter_file_splice_write
```
```
In fs/aio.c (ffffffff813354c8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/io_uring.c (ffffffff8133b9d5)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/proc/proc_sysctl.c (ffffffff81374ee0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:register_leaf_sysctl_tables
```
```
In fs/ext4/extents.c (ffffffff8138dff7)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
```
```
In fs/squashfs/block.c (ffffffff813f148d)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/cache.c (ffffffff813f2504)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
```
```
In fs/squashfs/file.c (ffffffff813f32d6)
Location: include/linux/slab.h:627
Inline: True
```
```
In fs/fuse/file.c (ffffffff81420568)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages
```
```
In fs/fuse/inode.c (ffffffff814224c9)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_dev_alloc
```
```
In security/keys/trusted.c (ffffffff828eb143)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/keys/trusted.c:init_trusted
```
```
In security/security.c (ffffffff828eb8ad)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/security.c:ordered_lsm_init
```
```
In security/selinux/ss/policydb.c (ffffffff814649d3)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In security/selinux/ss/services.c (ffffffff8146c17e)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policy
```
```
In security/apparmor/policy_unpack.c (ffffffff81497ef5)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In security/integrity/ima/ima_queue.c (ffffffff828ee3aa)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_init_digests
```
```
In security/integrity/ima/ima_policy.c (ffffffff828ee9f3)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814d12d4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
```
```
In block/bio.c (ffffffff828ef5e4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - block/bio.c:init_bio
```
```
In block/partitions/aix.c (ffffffff814f3048)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In lib/mpi/mpiutil.c (ffffffff8154d807)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - lib/mpi/mpiutil.c:mpi_resize
```
```
In drivers/gpio/gpiolib.c (ffffffff81563817)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-devprop.c (ffffffff81565637)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
```
```
In drivers/pwm/core.c (ffffffff8156b05b)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/pci/msi.c (ffffffff8159e6b1)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/pci/msi.c:populate_msi_sysfs
```
```
In drivers/rapidio/rio.c (ffffffff815a98f7)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/video/fbdev/core/fbmon.c (ffffffff815b39e5)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmon.c:fb_create_modedb
```
```
In drivers/acpi/sleep.c (ffffffff815cd5f0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:lpi_device_get_constraints
```
```
In drivers/acpi/acpi_platform.c (ffffffff815dfe34)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/acpi/sysfs.c (ffffffff815e2d8e)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
```
```
In drivers/acpi/acpi_lpat.c (ffffffff815e5534)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff828f757f)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/acpi/acpi_adxl.c (ffffffff828f7746)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/acpi/acpi_adxl.c:adxl_init
```
```
In drivers/acpi/processor_idle.c (ffffffff81628664)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/clk/clk.c (ffffffff81645e1f)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81649bb8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81653be1)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
```
In drivers/xen/grant-table.c (ffffffff81657451)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
```
```
In drivers/xen/events/events_base.c (ffffffff828fad39)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/mcelog.c (ffffffff81668b46)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:bind_virq_for_mce
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff8166962d)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:push_pxx_to_hypervisor
  - drivers/xen/xen-acpi-processor.c:push_cxx_to_hypervisor
```
```
In drivers/xen/xlate_mmu.c (ffffffff828fba86)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
```
In drivers/tty/tty_io.c (ffffffff8167958c)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff8169a01e)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_core.c:uart_register_driver
```
```
In drivers/char/random.c (ffffffff816b3285)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff816c4035)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_pcr_allocation
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816c5f56)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
```
```
In drivers/iommu/dmar.c (ffffffff816db95b)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_alloc_dev_scope
```
```
In drivers/iommu/intel-iommu.c (ffffffff816dee00)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_suspend
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:iommu_init_domains
```
```
In drivers/lightnvm/core.c (ffffffff816ea62b)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/base/property.c (ffffffff816fa545)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_property_match_string
```
```
In drivers/base/cacheinfo.c (ffffffff816fada5)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/base/swnode.c (ffffffff816fbfcc)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/base/power/clock_ops.c (0)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff8171867f)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
```
In drivers/base/regmap/regcache-flat.c (ffffffff81718966)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-flat.c:regcache_flat_init
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff8171b9af)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/block/xen-blkfront.c (ffffffff81724f66)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
```
In drivers/misc/sram.c (ffffffff81727916)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/mfd/mfd-core.c (ffffffff81737995)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_devices
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8174eaa3)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8175a033)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/sync_file.c (ffffffff8175c32a)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff81780be8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
```
```
In drivers/ata/libata-core.c (ffffffff8290691a)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_parse_force_param
```
```
In drivers/ata/libata-pmp.c (ffffffff8179cfeb)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
```
In drivers/spi/spi.c (ffffffff817a9b0c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_board_info
```
```
In drivers/net/phy/mdio-boardinfo.c (ffffffff817acb15)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/net/phy/mdio-boardinfo.c:mdiobus_register_board_info
```
```
In drivers/net/xen-netfront.c (ffffffff817c3775)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817cbadb)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817cdd25)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
```
```
In drivers/usb/core/hub.c (ffffffff817e05c9)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/usb/core/quirks.c (ffffffff817f4acf)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818099b0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81810603)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:find_tt
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8182557d)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/input/input.c (ffffffff8184ca82)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/input/input-mt.c (ffffffff8184e5b7)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/input/ff-core.c (ffffffff8184f027)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff818748ec)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:ptp_populate_pin_groups
  - drivers/ptp/ptp_sysfs.c:ptp_populate_pin_groups
```
```
In drivers/hwmon/hwmon.c (ffffffff8187a01a)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff8187f405)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
```
```
In drivers/thermal/power_allocator.c (ffffffff81881c1d)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff81882d48)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
```
In drivers/md/md-bitmap.c (ffffffff81899eac)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
```
```
In drivers/edac/edac_mc.c (ffffffff818ad9e5)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
```
```
In drivers/opp/core.c (ffffffff818b4527)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
```
```
In drivers/opp/cpu.c (ffffffff818b516c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818bddd7)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818c3540)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
```
In drivers/leds/led-core.c (ffffffff818d9551)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_get_default_pattern
```
```
In drivers/firmware/efi/capsule.c (ffffffff818de621)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff82912ceb)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
```
```
In drivers/firmware/efi/apple-properties.c (ffffffff82913321)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
```
In drivers/mailbox/pcc.c (ffffffff829141b3)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
```
In drivers/extcon/extcon.c (ffffffff818ece87)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In drivers/powercap/powercap_sys.c (ffffffff818f0ba2)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/nvmem/core.c (ffffffff818f425b)
Location: include/linux/slab.h:627
Inline: True
```
```
In arch/x86/pci/xen.c (ffffffff818f681c)
Location: include/linux/slab.h:627
Inline: True
```
```
In net/core/ethtool.c (ffffffff8192dbb0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_channels
  - net/core/ethtool.c:ethtool_set_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_get_sset_info
```
```
In net/core/rtnetlink.c (ffffffff8193b033)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_register_internal
```
```
In net/core/filter.c (ffffffff8194ec87)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/core/filter.c:bpf_convert_filter
```
```
In net/sched/sch_mq.c (ffffffff81980322)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_init
```
```
In net/netlink/af_netlink.c (ffffffff8291b68d)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_proto_init
```
```
In net/ipv4/route.c (ffffffff8291bbae)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
```
```
In net/ipv4/fib_frontend.c (ffffffff81a07433)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8291d056)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
```
```
In net/ipv6/route.c (ffffffff81a57b7a)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/calipso.c (ffffffff8291e5fb)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_init
```
```
In net/packet/af_packet.c (ffffffff81a99b7a)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff8291eb2f)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_init
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff8291ec0d)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81aa56aa)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81ab001d)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
```
```
In net/xdp/xdp_umem.c (ffffffff81ab7e36)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In arch/x86/events/amd/iommu.c (ffffffff828a14a9)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:_init_events_attrs
```
```
In arch/x86/events/intel/uncore.c (ffffffff828a3dac)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_types_init
```
```
In arch/x86/hyperv/hv_init.c (ffffffff828aa07f)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81046575)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81053672)
Location: include/linux/slab.h:627
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (ffffffff810562ee)
Location: include/linux/slab.h:627
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105ae25)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105fc5c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
```
```
In arch/x86/kernel/hpet.c (ffffffff828bf317)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81077d3b)
Location: include/linux/slab.h:627
Inline: True
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff828c99c7)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff828cad48)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
```
```
In kernel/workqueue.c (ffffffff828cc879)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/sched/fair.c (ffffffff810eeed5)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/sched/cpupri.c (ffffffff810f783e)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/cpudeadline.c (ffffffff810f7d19)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_init
```
```
In kernel/sched/debug.c (ffffffff810fdfe3)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/irq/affinity.c (ffffffff81123b12)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/cgroup/rdma.c (ffffffff8116ebac)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/auditfilter.c (ffffffff8117c109)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_register_class
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8118c6aa)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
```
```
In kernel/trace/ftrace.c (ffffffff8119bf48)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:alloc_ftrace_hash
  - kernel/trace/ftrace.c:ftrace_profile_init
```
```
In kernel/trace/trace.c (ffffffff811b06be)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/trace.c:create_trace_option_files
  - kernel/trace/trace.c:__tracing_open
```
```
In kernel/trace/tracing_map.c (ffffffff811b53c6)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_init
  - kernel/trace/tracing_map.c:tracing_map_init
  - kernel/trace/tracing_map.c:tracing_map_init
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_syscalls.c (ffffffff828d7d00)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:init_ftrace_syscalls
```
```
In kernel/trace/trace_events_filter.c (ffffffff811c4feb)
Location: include/linux/slab.h:627
Inline: True
```
```
In kernel/trace/trace_events_hist.c (ffffffff811d06c2)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
```
In kernel/trace/bpf_trace.c (ffffffff811d2e96)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
```
In kernel/trace/trace_probe.c (ffffffff811db06f)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
```
```
In kernel/bpf/core.c (ffffffff811e2735)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
  - kernel/bpf/core.c:bpf_prog_alloc_jited_linfo
```
```
In kernel/bpf/verifier.c (ffffffff811f0ad3)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
```
In kernel/events/core.c (ffffffff81214d22)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/hw_breakpoint.c (ffffffff828d9a64)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
```
```
In kernel/events/uprobes.c (ffffffff81220fee)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In mm/slab_common.c (ffffffff812565f9)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In mm/list_lru.c (ffffffff8125d4bd)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
```
```
In mm/gup.c (ffffffff81261d2f)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/vmalloc.c (ffffffff8127fd4e)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
```
```
In mm/ksm.c (ffffffff812a6125)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/ksm.c:merge_across_nodes_store
```
```
In mm/slub.c (ffffffff812aee45)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
```
```
In fs/pipe.c (ffffffff812efbec)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/splice.c (ffffffff8131f0d8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:iter_file_splice_write
```
```
In fs/aio.c (ffffffff813484cc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/io_uring.c (ffffffff8134eb85)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/proc/proc_sysctl.c (ffffffff813888b0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:register_leaf_sysctl_tables
```
```
In fs/ext4/extents.c (ffffffff813a1da5)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
```
```
In fs/squashfs/block.c (ffffffff8140709d)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/cache.c (ffffffff814080f4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
```
```
In fs/squashfs/file.c (ffffffff81408ec6)
Location: include/linux/slab.h:627
Inline: True
```
```
In fs/fuse/file.c (ffffffff81437328)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages
```
```
In fs/fuse/inode.c (ffffffff814393c9)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_dev_alloc
```
```
In security/keys/trusted.c (ffffffff828f0559)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/keys/trusted.c:init_trusted
```
```
In security/security.c (ffffffff828f0cc3)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/security.c:ordered_lsm_init
```
```
In security/selinux/ss/policydb.c (ffffffff8147c1d3)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In security/selinux/ss/services.c (ffffffff8148393e)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policy
```
```
In security/apparmor/policy_unpack.c (ffffffff814b0045)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In security/integrity/ima/ima_queue.c (ffffffff828f37cc)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_init_digests
```
```
In security/integrity/ima/ima_policy.c (ffffffff828f3e15)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814e9d84)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
```
```
In block/bio.c (ffffffff828f4a06)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - block/bio.c:init_bio
```
```
In block/partitions/aix.c (ffffffff8150c0a8)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In lib/mpi/mpiutil.c (ffffffff81567657)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - lib/mpi/mpiutil.c:mpi_resize
```
```
In drivers/gpio/gpiolib.c (ffffffff8157d737)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-devprop.c (ffffffff8157f557)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
```
```
In drivers/pwm/core.c (ffffffff8158555b)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/pci/msi.c (ffffffff815b8ae1)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/pci/msi.c:populate_msi_sysfs
```
```
In drivers/rapidio/rio.c (ffffffff815c2937)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/video/fbdev/core/fbmon.c (ffffffff815cd455)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmon.c:fb_create_modedb
```
```
In drivers/acpi/sleep.c (ffffffff815e7490)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:lpi_device_get_constraints
```
```
In drivers/acpi/acpi_platform.c (ffffffff815f9cf4)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/acpi/sysfs.c (ffffffff815fcc4e)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
```
```
In drivers/acpi/acpi_lpat.c (ffffffff815ff3e4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff828fc9d7)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/acpi/acpi_adxl.c (ffffffff828fcb9e)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/acpi/acpi_adxl.c:adxl_init
```
```
In drivers/acpi/processor_idle.c (ffffffff81642514)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/clk/clk.c (ffffffff816603af)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81664148)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8166e271)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
```
In drivers/xen/grant-table.c (ffffffff81671a51)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
```
```
In drivers/xen/events/events_base.c (ffffffff82900a6a)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/mcelog.c (ffffffff81683108)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:bind_virq_for_mce
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81683bed)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:push_pxx_to_hypervisor
  - drivers/xen/xen-acpi-processor.c:push_cxx_to_hypervisor
```
```
In drivers/xen/xlate_mmu.c (ffffffff829017b7)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
```
In drivers/tty/tty_io.c (ffffffff81693bec)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff816b4c1e)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_core.c:uart_register_driver
```
```
In drivers/char/random.c (ffffffff816cd805)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff816de5d5)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_pcr_allocation
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816e044e)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
```
```
In drivers/iommu/dmar.c (ffffffff816f5f2b)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_alloc_dev_scope
```
```
In drivers/iommu/intel-iommu.c (ffffffff816f9410)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_suspend
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:iommu_init_domains
```
```
In drivers/lightnvm/core.c (ffffffff81704e6b)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/base/property.c (ffffffff81714de5)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_property_match_string
```
```
In drivers/base/cacheinfo.c (ffffffff81715645)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/base/swnode.c (ffffffff81716b6c)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/base/power/clock_ops.c (0)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff817339df)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
```
In drivers/base/regmap/regcache-flat.c (ffffffff81733cc6)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-flat.c:regcache_flat_init
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81736d0f)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/block/xen-blkfront.c (ffffffff8173fe7b)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
```
In drivers/misc/sram.c (ffffffff81742d56)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/mfd/mfd-core.c (ffffffff81752dd5)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_devices
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81769f23)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/dma-buf/dma-fence.c (ffffffff817755f3)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/sync_file.c (ffffffff817779ca)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff8179aa83)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
```
```
In drivers/ata/libata-core.c (ffffffff8290c581)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_parse_force_param
```
```
In drivers/ata/libata-pmp.c (ffffffff817b6e6b)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
```
In drivers/spi/spi.c (ffffffff817c399c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_board_info
```
```
In drivers/net/phy/mdio-boardinfo.c (ffffffff817c6aa5)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/net/phy/mdio-boardinfo.c:mdiobus_register_board_info
```
```
In drivers/net/xen-netfront.c (ffffffff817dda35)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817e5d7b)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817e7fc5)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
```
```
In drivers/usb/core/hub.c (ffffffff817fa8b9)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/usb/core/quirks.c (ffffffff8180ed0f)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81823ac0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8182b0d3)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:find_tt
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8183eefd)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/input/input.c (ffffffff81867d72)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/input/input-mt.c (ffffffff81869787)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/input/ff-core.c (ffffffff8186a1d7)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff8189029c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:ptp_populate_pin_groups
  - drivers/ptp/ptp_sysfs.c:ptp_populate_pin_groups
```
```
In drivers/hwmon/hwmon.c (ffffffff81895a1a)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff8189ae35)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
```
```
In drivers/thermal/power_allocator.c (ffffffff8189d68d)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff8189e808)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
```
In drivers/md/md-bitmap.c (ffffffff818b601c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
```
```
In drivers/edac/edac_mc.c (ffffffff818c9c75)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
```
```
In drivers/opp/core.c (ffffffff818d07d7)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
```
```
In drivers/opp/cpu.c (ffffffff818d141c)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818da0e7)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818df8a0)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
```
In drivers/leds/led-core.c (ffffffff818f6071)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_get_default_pattern
```
```
In drivers/firmware/efi/capsule.c (ffffffff818fb12a)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff82919718)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
```
```
In drivers/firmware/efi/apple-properties.c (ffffffff82919d4e)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
```
In drivers/mailbox/pcc.c (ffffffff8291ae7a)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
```
In drivers/extcon/extcon.c (ffffffff8190df07)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In drivers/powercap/powercap_sys.c (ffffffff81911c22)
Location: include/linux/slab.h:627
Inline: True
```
```
In drivers/nvmem/core.c (ffffffff819152fb)
Location: include/linux/slab.h:627
Inline: True
```
```
In arch/x86/pci/xen.c (ffffffff81917dac)
Location: include/linux/slab.h:627
Inline: True
```
```
In net/core/ethtool.c (ffffffff8194f280)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_channels
  - net/core/ethtool.c:ethtool_set_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_get_sset_info
```
```
In net/core/rtnetlink.c (ffffffff8195c873)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_register_internal
```
```
In net/core/filter.c (ffffffff81970657)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/core/filter.c:bpf_convert_filter
```
```
In net/sched/sch_mq.c (ffffffff819a2882)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_init
```
```
In net/netlink/af_netlink.c (ffffffff829223e4)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_proto_init
```
```
In net/ipv4/route.c (ffffffff82922629)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
```
```
In net/ipv4/fib_frontend.c (ffffffff81a11b87)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
```
In net/ipv4/cipso_ipv4.c (ffffffff82923aba)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
```
```
In net/ipv6/route.c (ffffffff81a63c87)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/calipso.c (ffffffff8292505f)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_init
```
```
In net/packet/af_packet.c (ffffffff81aa68ab)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff82925543)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_init
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff82925628)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ab1a4a)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81abc3cd)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
```
```
In net/xdp/xdp_umem.c (ffffffff81ac4256)
Location: include/linux/slab.h:627
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_umem_create
```
</details>
</li>
</ul>

## Differences
