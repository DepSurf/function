# Function: <code>panic</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void panic(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff8118b914)
Location: kernel/panic.c:72
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:kernel_init
  - init/main.c:kernel_init
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
  - init/do_mounts_rd.c:rd_load_image
  - init/initramfs.c:do_name
  - arch/x86/xen/setup.c:xen_auto_xlated_memory_setup
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:finish_e820_parsing
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/tboot.c:tboot_shutdown
  - arch/x86/kernel/cpu/mcheck/mce.c:wait_for_panic
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_save_irq
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/doublefault.c:df_debug
  - arch/x86/kernel/amd_gart_64.c:dma_map_area
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/init_64.c:spp_getpage
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - kernel/panic.c:__stack_chk_fail
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/cred.c:put_cred_rcu
  - kernel/power/swap.c:swsusp_header_init
  - kernel/debug/debug_core.c:kgdb_handle_exception
  - kernel/hung_task.c:watchdog
  - kernel/watchdog.c:watchdog_timer_fn
  - certs/system_keyring.c:system_trusted_keyring_init
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/slab_common.c:kmem_cache_create
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:create_kmalloc_cache
  - mm/memblock.c:memblock_alloc_base
  - mm/memblock.c:memblock_virt_alloc_try_nid
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/slub.c:kmem_cache_open
  - mm/memory-failure.c:memory_failure
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/nsfs.c:nsfs_init
  - fs/block_dev.c:bdev_cache_init
  - fs/block_dev.c:bdev_cache_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/mark.c:fsnotify_mark_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/ext4/super.c:__ext4_abort
  - fs/fat/misc.c:__fat_fs_error
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - security/selinux/netlink.c:selnl_init
  - security/selinux/ss/services.c:aurule_init
  - security/smack/smackfs.c:smk_cipso_doi
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/memory.c:tomoyo_warn_oom
  - security/yama/yama_lsm.c:yama_add_hooks
  - block/bio.c:init_bio
  - block/bio.c:init_bio
  - block/blk-core.c:blk_dev_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - lib/swiotlb.c:swiotlb_tbl_map_single
  - lib/swiotlb.c:swiotlb_map_page
  - lib/swiotlb.c:swiotlb_map_page
  - lib/swiotlb.c:swiotlb_map_page
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
  - drivers/virtio/virtio.c:virtio_init
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_ldisc_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/agp/generic.c:global_cache_flush
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/irq_remapping.c:panic_if_irq_remap
  - drivers/base/cpu.c:cpu_dev_init
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/rtnetlink.c:rtnl_register
  - net/core/rtnetlink.c:rtnetlink_init
  - net/netlink/genetlink.c:genl_pernet_init
  - net/netlink/genetlink.c:genl_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
  - net/netlabel/netlabel_kapi.c:netlbl_init
```
**Symbols:**

```
ffffffff8118b914-ffffffff8118bb29: panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void panic(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff8119e638)
Location: kernel/panic.c:104
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/main.c:kernel_init
  - init/main.c:start_kernel
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
  - init/do_mounts_rd.c:rd_load_image
  - init/initramfs.c:do_name
  - arch/x86/xen/setup.c:xen_auto_xlated_memory_setup
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:finish_e820_parsing
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/tboot.c:tboot_shutdown
  - arch/x86/kernel/cpu/mcheck/mce.c:wait_for_panic
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_save_irq
  - arch/x86/kernel/doublefault.c:df_debug
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:dma_map_area
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/init_64.c:spp_getpage
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - kernel/panic.c:__stack_chk_fail
  - kernel/panic.c:__warn
  - kernel/panic.c:nmi_panic
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/cred.c:put_cred_rcu
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule_bug
  - kernel/power/swap.c:swsusp_header_init
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/debug/debug_core.c:kgdb_handle_exception
  - kernel/hung_task.c:watchdog
  - kernel/watchdog.c:watchdog_timer_fn
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create
  - mm/memblock.c:memblock_virt_alloc_try_nid
  - mm/memblock.c:memblock_alloc_base
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/slub.c:kmem_cache_open
  - mm/memory-failure.c:memory_failure
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/nsfs.c:nsfs_init
  - fs/block_dev.c:bdev_cache_init
  - fs/block_dev.c:bdev_cache_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/ext4/super.c:__ext4_abort
  - fs/fat/misc.c:__fat_fs_error
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - security/selinux/netlink.c:selnl_init
  - security/selinux/ss/services.c:aurule_init
  - security/smack/smackfs.c:smk_cipso_doi
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/memory.c:tomoyo_warn_oom
  - security/yama/yama_lsm.c:yama_add_hooks
  - security/integrity/ima/ima_mok.c:ima_mok_init
  - crypto/jitterentropy-kcapi.c:jent_panic
  - block/bio.c:init_bio
  - block/bio.c:init_bio
  - block/blk-core.c:blk_dev_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - lib/swiotlb.c:swiotlb_map_page
  - lib/swiotlb.c:swiotlb_map_page
  - lib/swiotlb.c:swiotlb_map_page
  - lib/swiotlb.c:swiotlb_tbl_map_single
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
  - drivers/virtio/virtio.c:virtio_init
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_ldisc.c:tty_ldisc_init
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/agp/generic.c:global_cache_flush
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/irq_remapping.c:panic_if_irq_remap
  - drivers/base/cpu.c:cpu_dev_init
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnl_register
  - net/netlink/genetlink.c:genl_init
  - net/netlink/genetlink.c:genl_pernet_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
  - net/netlabel/netlabel_kapi.c:netlbl_init
```
**Symbols:**

```
ffffffff8119e638-ffffffff8119e85e: panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void panic(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff811ae064)
Location: kernel/panic.c:130
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/main.c:kernel_init
  - init/main.c:start_kernel
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
  - init/initramfs.c:do_name
  - arch/x86/xen/setup.c:xen_auto_xlated_memory_setup
  - arch/x86/xen/smp.c:xen_smp_prepare_cpus
  - arch/x86/xen/smp.c:xen_smp_prepare_cpus
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/traps.c:handle_stack_overflow
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:finish_e820_parsing
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/tboot.c:tboot_shutdown
  - arch/x86/kernel/cpu/mcheck/mce.c:wait_for_panic
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_save_irq
  - arch/x86/kernel/doublefault.c:df_debug
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:dma_map_area
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/init_64.c:spp_getpage
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - kernel/panic.c:__stack_chk_fail
  - kernel/panic.c:__warn
  - kernel/panic.c:nmi_panic
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/cred.c:put_cred_rcu
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule_bug
  - kernel/power/swap.c:swsusp_header_init
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/debug/debug_core.c:kgdb_handle_exception
  - kernel/hung_task.c:watchdog
  - kernel/watchdog.c:watchdog_timer_fn
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create
  - mm/memblock.c:memblock_virt_alloc_try_nid
  - mm/memblock.c:memblock_alloc_base
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/slub.c:kmem_cache_open
  - mm/memory-failure.c:memory_failure
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/nsfs.c:nsfs_init
  - fs/block_dev.c:bdev_cache_init
  - fs/block_dev.c:bdev_cache_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/ext4/super.c:__ext4_abort
  - fs/fat/misc.c:__fat_fs_error
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - security/selinux/netlink.c:selnl_init
  - security/selinux/ss/services.c:aurule_init
  - security/smack/smackfs.c:smk_cipso_doi
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/memory.c:tomoyo_warn_oom
  - security/yama/yama_lsm.c:yama_add_hooks
  - crypto/jitterentropy-kcapi.c:jent_panic
  - block/bio.c:init_bio
  - block/bio.c:init_bio
  - block/blk-core.c:blk_dev_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - lib/swiotlb.c:swiotlb_tbl_map_single
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
  - drivers/virtio/virtio.c:virtio_init
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_ldisc.c:tty_ldisc_init
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/agp/generic.c:global_cache_flush
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/irq_remapping.c:panic_if_irq_remap
  - drivers/base/cpu.c:cpu_dev_init
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnl_register
  - net/netlink/genetlink.c:genl_init
  - net/netlink/genetlink.c:genl_pernet_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
  - net/netlabel/netlabel_kapi.c:netlbl_init
```
**Symbols:**

```
ffffffff811ae064-ffffffff811ae291: panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void panic(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff81084793)
Location: kernel/panic.c:131
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/main.c:kernel_init
  - init/main.c:start_kernel
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
  - init/initramfs.c:populate_rootfs
  - init/initramfs.c:do_name
  - arch/x86/xen/setup.c:xen_auto_xlated_memory_setup
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/traps.c:handle_stack_overflow
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/kernel/cpu/mcheck/mce.c:wait_for_panic
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_save_irq
  - arch/x86/kernel/doublefault.c:df_debug
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:dma_map_area
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/init_64.c:spp_getpage
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - kernel/panic.c:__stack_chk_fail
  - kernel/panic.c:__warn
  - kernel/panic.c:nmi_panic
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/cred.c:put_cred_rcu
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule_bug
  - kernel/power/swap.c:swsusp_header_init
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/debug/debug_core.c:kgdb_handle_exception
  - kernel/hung_task.c:watchdog
  - kernel/watchdog.c:watchdog_timer_fn
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create
  - mm/memblock.c:memblock_virt_alloc_try_nid
  - mm/memblock.c:memblock_alloc_base
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/slub.c:__kmem_cache_create
  - mm/memory-failure.c:memory_failure
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/nsfs.c:nsfs_init
  - fs/block_dev.c:bdev_cache_init
  - fs/block_dev.c:bdev_cache_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/ext4/super.c:__ext4_abort
  - fs/fat/misc.c:__fat_fs_error
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - security/security.c:lsm_early_inode
  - security/security.c:lsm_early_inode
  - security/security.c:lsm_early_cred
  - security/security.c:lsm_early_cred
  - security/security.c:security_add_hooks
  - security/selinux/netlink.c:selnl_init
  - security/selinux/ss/services.c:aurule_init
  - security/smack/smackfs.c:smk_cipso_doi
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/memory.c:tomoyo_warn_oom
  - security/yama/yama_lsm.c:yama_add_hooks
  - crypto/jitterentropy-kcapi.c:jent_panic
  - block/bio.c:init_bio
  - block/bio.c:init_bio
  - block/blk-core.c:blk_dev_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - lib/swiotlb.c:swiotlb_tbl_map_single
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/virtio/virtio.c:virtio_init
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_ldisc.c:tty_ldisc_init
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/agp/generic.c:global_cache_flush
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/irq_remapping.c:panic_if_irq_remap
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/edac/edac_device.c:edac_device_handle_ue
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnl_register
  - net/netlink/genetlink.c:genl_init
  - net/netlink/genetlink.c:genl_pernet_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
  - net/netlabel/netlabel_kapi.c:netlbl_init
```
**Symbols:**

```
ffffffff81084793-ffffffff810849c5: panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void panic(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff8108b24c)
Location: kernel/panic.c:134
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/main.c:kernel_init
  - init/main.c:start_kernel
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
  - init/initramfs.c:populate_rootfs
  - init/initramfs.c:do_name
  - arch/x86/xen/setup.c:xen_auto_xlated_memory_setup
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/traps.c:handle_stack_overflow
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/kernel/tboot.c:tboot_shutdown
  - arch/x86/kernel/cpu/mcheck/mce.c:wait_for_panic
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_save_irq
  - arch/x86/kernel/doublefault.c:df_debug
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:dma_map_area
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/init_64.c:spp_getpage
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - kernel/panic.c:__stack_chk_fail
  - kernel/panic.c:__warn
  - kernel/panic.c:nmi_panic
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/cred.c:put_cred_rcu
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule_bug
  - kernel/power/swap.c:swsusp_header_init
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/debug/debug_core.c:kgdb_handle_exception
  - kernel/hung_task.c:watchdog
  - kernel/watchdog.c:watchdog_timer_fn
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create
  - mm/memblock.c:memblock_virt_alloc_try_nid
  - mm/memblock.c:memblock_alloc_base
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/slub.c:__kmem_cache_create
  - mm/memory-failure.c:memory_failure
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/nsfs.c:nsfs_init
  - fs/block_dev.c:bdev_cache_init
  - fs/block_dev.c:bdev_cache_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/ext4/super.c:__ext4_abort
  - fs/fat/misc.c:__fat_fs_error
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - security/security.c:lsm_early_inode
  - security/security.c:lsm_early_inode
  - security/security.c:lsm_early_cred
  - security/security.c:lsm_early_cred
  - security/security.c:security_add_hooks
  - security/selinux/netlink.c:selnl_init
  - security/selinux/ss/services.c:aurule_init
  - security/smack/smackfs.c:smk_cipso_doi
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/memory.c:tomoyo_warn_oom
  - security/yama/yama_lsm.c:yama_add_hooks
  - crypto/jitterentropy-kcapi.c:jent_panic
  - block/bio.c:init_bio
  - block/bio.c:init_bio
  - block/blk-core.c:blk_dev_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - lib/swiotlb.c:swiotlb_tbl_map_single
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/virtio/virtio.c:virtio_init
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_ldisc.c:tty_ldisc_init
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/agp/generic.c:global_cache_flush
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/irq_remapping.c:panic_if_irq_remap
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/edac/edac_device.c:edac_device_handle_ue
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnl_register
  - net/netlink/genetlink.c:genl_init
  - net/netlink/genetlink.c:genl_pernet_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
  - net/netlabel/netlabel_kapi.c:netlbl_init
```
**Symbols:**

```
ffffffff8108b24c-ffffffff8108b490: panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void panic(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff8108e9c9)
Location: kernel/panic.c:135
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/main.c:kernel_init
  - init/main.c:start_kernel
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
  - init/initramfs.c:populate_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:do_name
  - init/initramfs.c:maybe_link
  - arch/x86/xen/setup.c:xen_auto_xlated_memory_setup
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/traps.c:handle_stack_overflow
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_panic
  - arch/x86/kernel/cpu/mcheck/mce.c:wait_for_panic
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_save_irq
  - arch/x86/kernel/doublefault.c:df_debug
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:dma_map_area
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/init_64.c:spp_getpage
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - kernel/panic.c:__stack_chk_fail
  - kernel/panic.c:__warn
  - kernel/panic.c:nmi_panic
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/cred.c:put_cred_rcu
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule_bug
  - kernel/power/swap.c:swsusp_header_init
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - kernel/audit.c:audit_init
  - kernel/debug/debug_core.c:kgdb_handle_exception
  - kernel/hung_task.c:watchdog
  - kernel/watchdog.c:watchdog_timer_fn
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/blacklist.c:blacklist_init
  - certs/blacklist.c:blacklist_init
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/nobootmem.c:__alloc_bootmem_low_node
  - mm/nobootmem.c:__alloc_bootmem_low
  - mm/nobootmem.c:__alloc_bootmem_node
  - mm/nobootmem.c:__alloc_bootmem
  - mm/memblock.c:memblock_virt_alloc_try_nid
  - mm/memblock.c:memblock_alloc_base
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/slub.c:kmem_cache_open
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/nsfs.c:nsfs_init
  - fs/block_dev.c:bdev_cache_init
  - fs/block_dev.c:bdev_cache_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup
  - fs/quota/dquot.c:dquot_init
  - fs/quota/dquot.c:dquot_init
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/super.c:__ext4_abort
  - fs/fat/misc.c:__fat_fs_error
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - security/security.c:security_add_hooks
  - security/selinux/hooks.c:selinux_nf_ip_init
  - security/selinux/hooks.c:selinux_init
  - security/selinux/hooks.c:selinux_init
  - security/selinux/hooks.c:selinux_init
  - security/selinux/netlink.c:selnl_init
  - security/selinux/ss/services.c:aurule_init
  - security/smack/smackfs.c:smk_cipso_doi
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/memory.c:tomoyo_warn_oom
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/yama/yama_lsm.c:yama_add_hooks
  - crypto/jitterentropy-kcapi.c:jent_panic
  - block/bio.c:init_bio
  - block/bio.c:init_bio
  - block/blk-core.c:blk_dev_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/virtio/virtio.c:virtio_init
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/agp/generic.c:global_cache_flush
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/irq_remapping.c:panic_if_irq_remap
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/edac/edac_device.c:edac_device_handle_ue
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/genetlink.c:genl_init
  - net/netlink/genetlink.c:genl_pernet_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
  - net/netlabel/netlabel_kapi.c:netlbl_init
```
**Symbols:**

```
ffffffff8108e9c9-ffffffff8108ec10: panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void panic(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff81096d09)
Location: kernel/panic.c:161
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/main.c:kernel_init
  - init/main.c:start_kernel
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
  - init/initramfs.c:populate_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:do_name
  - init/initramfs.c:maybe_link
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/traps.c:handle_stack_overflow
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:wait_for_panic
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_save_irq
  - arch/x86/kernel/doublefault.c:df_debug
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/init_64.c:spp_getpage
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - kernel/panic.c:__stack_chk_fail
  - kernel/panic.c:__warn
  - kernel/panic.c:nmi_panic
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/cred.c:put_cred_rcu
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule_bug
  - kernel/power/swap.c:swsusp_header_init
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - kernel/audit.c:audit_init
  - kernel/debug/debug_core.c:kgdb_handle_exception
  - kernel/hung_task.c:watchdog
  - kernel/watchdog.c:watchdog_timer_fn
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/blacklist.c:blacklist_init
  - certs/blacklist.c:blacklist_init
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/memblock.c:memblock_alloc_try_nid
  - mm/memblock.c:memblock_alloc_base
  - mm/slub.c:kmem_cache_open
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/nsfs.c:nsfs_init
  - fs/block_dev.c:bdev_cache_init
  - fs/block_dev.c:bdev_cache_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup
  - fs/quota/dquot.c:dquot_init
  - fs/quota/dquot.c:dquot_init
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/super.c:__ext4_abort
  - fs/fat/misc.c:__fat_fs_error
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - security/security.c:security_add_hooks
  - security/security.c:ordered_lsm_init
  - security/security.c:ordered_lsm_init
  - security/selinux/hooks.c:selinux_nf_ip_init
  - security/selinux/hooks.c:selinux_init
  - security/selinux/hooks.c:selinux_init
  - security/selinux/netlink.c:selnl_init
  - security/selinux/ss/services.c:aurule_init
  - security/smack/smackfs.c:smk_cipso_doi
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/memory.c:tomoyo_warn_oom
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/yama/yama_lsm.c:yama_init
  - crypto/jitterentropy-kcapi.c:jent_panic
  - block/bio.c:init_bio
  - block/bio.c:init_bio
  - block/blk-core.c:blk_dev_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/acpi/apei/ghes.c:__ghes_panic
  - drivers/virtio/virtio.c:virtio_init
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/sysrq.c:sysrq_handle_crash
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/agp/generic.c:global_cache_flush
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/irq_remapping.c:panic_if_irq_remap
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/edac/edac_device.c:edac_device_handle_ue
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/genetlink.c:genl_init
  - net/netlink/genetlink.c:genl_pernet_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/raw.c:raw_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
  - net/netlabel/netlabel_kapi.c:netlbl_init
```
**Symbols:**

```
ffffffff81096d09-ffffffff81096fb0: panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void panic(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff8109b285)
Location: kernel/panic.c:166
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/main.c:kernel_init
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
  - init/initramfs.c:populate_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:do_name
  - init/initramfs.c:maybe_link
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_late_init
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/traps.c:handle_stack_overflow
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/acpi/boot.c:acpi_parse_hpet
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_save_irq
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/doublefault.c:df_debug
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
  - arch/x86/mm/init.c:save_mr
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/init_64.c:spp_getpage
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - kernel/panic.c:__stack_chk_fail
  - kernel/panic.c:__warn
  - kernel/panic.c:nmi_panic
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/cred.c:put_cred_rcu
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule_bug
  - kernel/power/snapshot.c:__register_nosave_region
  - kernel/power/swap.c:swsusp_header_init
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/audit.c:audit_init
  - kernel/debug/debug_core.c:kgdb_handle_exception
  - kernel/hung_task.c:watchdog
  - kernel/watchdog.c:watchdog_timer_fn
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/blacklist.c:blacklist_init
  - certs/blacklist.c:blacklist_init
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/sparse.c:memory_present
  - mm/sparse.c:sparse_index_alloc
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/nsfs.c:nsfs_init
  - fs/block_dev.c:bdev_cache_init
  - fs/block_dev.c:bdev_cache_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup
  - fs/quota/dquot.c:dquot_init
  - fs/quota/dquot.c:dquot_init
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/super.c:__ext4_abort
  - fs/fat/misc.c:__fat_fs_error
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - security/security.c:security_add_hooks
  - security/security.c:ordered_lsm_init
  - security/security.c:ordered_lsm_init
  - security/selinux/hooks.c:selinux_nf_ip_init
  - security/selinux/hooks.c:selinux_init
  - security/selinux/hooks.c:selinux_init
  - security/selinux/netlink.c:selnl_init
  - security/selinux/ss/services.c:aurule_init
  - security/smack/smackfs.c:smk_cipso_doi
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/memory.c:tomoyo_warn_oom
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/yama/yama_lsm.c:yama_init
  - crypto/jitterentropy-kcapi.c:jent_panic
  - block/bio.c:init_bio
  - block/bio.c:init_bio
  - block/blk-core.c:blk_dev_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/virtio/virtio.c:virtio_init
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/sysrq.c:sysrq_handle_crash
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/irq_remapping.c:panic_if_irq_remap
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/edac/edac_device.c:edac_device_handle_ue
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/genetlink.c:genl_init
  - net/netlink/genetlink.c:genl_pernet_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/raw.c:raw_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
  - net/netlabel/netlabel_kapi.c:netlbl_init
  - lib/cpumask.c:alloc_bootmem_cpumask_var
```
**Symbols:**

```
ffffffff8109b285-ffffffff8109b55c: panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void panic(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810a17a5)
Location: kernel/panic.c:167
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/main.c:kernel_init
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
  - init/initramfs.c:populate_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:do_name
  - init/initramfs.c:maybe_link
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_late_init
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/traps.c:handle_stack_overflow
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/acpi/boot.c:acpi_parse_hpet
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_save_irq
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_undefined
  - arch/x86/kernel/doublefault.c:df_debug
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
  - arch/x86/mm/init.c:save_mr
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/init_64.c:spp_getpage
  - arch/x86/mm/pat.c:pat_init
  - kernel/panic.c:__stack_chk_fail
  - kernel/panic.c:__warn
  - kernel/panic.c:nmi_panic
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/cred.c:put_cred_rcu
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule_bug
  - kernel/power/snapshot.c:__register_nosave_region
  - kernel/power/swap.c:swsusp_header_init
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/audit.c:audit_init
  - kernel/debug/debug_core.c:kgdb_handle_exception
  - kernel/hung_task.c:watchdog
  - kernel/watchdog.c:watchdog_timer_fn
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/blacklist.c:blacklist_init
  - certs/blacklist.c:blacklist_init
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/sparse.c:memory_present
  - mm/sparse.c:sparse_index_alloc
  - mm/memory-failure.c:memory_failure
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/nsfs.c:nsfs_init
  - fs/block_dev.c:bdev_cache_init
  - fs/block_dev.c:bdev_cache_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup
  - fs/quota/dquot.c:dquot_init
  - fs/quota/dquot.c:dquot_init
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/super.c:__ext4_abort
  - fs/fat/misc.c:__fat_fs_error
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - security/security.c:security_add_hooks
  - security/security.c:ordered_lsm_init
  - security/security.c:ordered_lsm_init
  - security/selinux/hooks.c:selinux_nf_ip_init
  - security/selinux/hooks.c:selinux_init
  - security/selinux/hooks.c:selinux_init
  - security/selinux/netlink.c:selnl_init
  - security/selinux/ss/services.c:aurule_init
  - security/smack/smackfs.c:smk_cipso_doi
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/memory.c:tomoyo_warn_oom
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/yama/yama_lsm.c:yama_init
  - crypto/jitterentropy-kcapi.c:jent_panic
  - block/bio.c:init_bio
  - block/bio.c:init_bio
  - block/blk-core.c:blk_dev_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/virtio/virtio.c:virtio_init
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/sysrq.c:sysrq_handle_crash
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/irq_remapping.c:panic_if_irq_remap
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:memory_dev_init
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/edac/edac_device.c:edac_device_handle_ue
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/genetlink.c:genl_init
  - net/netlink/genetlink.c:genl_pernet_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/raw.c:raw_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
  - net/netlabel/netlabel_kapi.c:netlbl_init
  - lib/cpumask.c:alloc_bootmem_cpumask_var
```
**Symbols:**

```
ffffffff810a17a5-ffffffff810a1a88: panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void panic(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810a85be)
Location: kernel/panic.c:177
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/main.c:kernel_init
  - init/main.c:do_initcalls
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - init/main.c:setup_command_line
  - init/main.c:setup_command_line
  - init/main.c:start_kernel
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
  - init/initramfs.c:populate_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:do_name
  - init/initramfs.c:find_link
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_late_init
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/traps.c:exc_double_fault
  - arch/x86/kernel/traps.c:handle_stack_overflow
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/setup.c:reserve_initrd
  - arch/x86/kernel/setup.c:relocate_initrd
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/kernel/tboot.c:tboot_setup_sleep
  - arch/x86/kernel/tboot.c:tboot_create_trampoline
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:wait_for_panic
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/acpi/boot.c:acpi_parse_hpet
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:__apic_intr_mode_select
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:ioapic_setup_resources
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_save_irq
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/kvm.c:__kvm_handle_async_pf
  - arch/x86/kernel/kvm.c:__kvm_handle_async_pf
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/mm/init.c:save_mr
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/init_64.c:spp_getpage
  - arch/x86/mm/pat/memtype.c:pat_init
  - kernel/panic.c:__stack_chk_fail
  - kernel/panic.c:__warn
  - kernel/panic.c:nmi_panic
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/cred.c:put_cred_rcu
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule_bug
  - kernel/power/snapshot.c:__register_nosave_region
  - kernel/power/swap.c:swsusp_header_init
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/audit.c:audit_init
  - kernel/debug/debug_core.c:kgdb_reenter_check
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/watchdog.c:watchdog_timer_fn
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/blacklist.c:blacklist_init
  - certs/blacklist.c:blacklist_init
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/sparse.c:memory_present
  - mm/sparse.c:sparse_index_alloc
  - mm/memory-failure.c:memory_failure
  - fs/namespace.c:init_mount_tree
  - fs/namespace.c:init_mount_tree
  - fs/namespace.c:mnt_init
  - fs/nsfs.c:nsfs_init
  - fs/block_dev.c:bdev_cache_init
  - fs/block_dev.c:bdev_cache_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup
  - fs/quota/dquot.c:dquot_init
  - fs/quota/dquot.c:dquot_init
  - fs/quota/dquot.c:dquot_init
  - fs/proc/proc_sysctl.c:do_sysctl_args
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:ext4_handle_error
  - fs/fat/misc.c:__fat_fs_error
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - security/security.c:security_add_hooks
  - security/security.c:security_add_hooks
  - security/security.c:ordered_lsm_init
  - security/security.c:ordered_lsm_init
  - security/selinux/hooks.c:selinux_nf_ip_init
  - security/selinux/hooks.c:selinux_init
  - security/selinux/hooks.c:selinux_init
  - security/selinux/netlink.c:selnl_init
  - security/selinux/ss/services.c:aurule_init
  - security/smack/smackfs.c:smk_cipso_doi
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/memory.c:tomoyo_memory_ok
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/lsm.c:apparmor_nf_ip_init
  - security/yama/yama_lsm.c:yama_init
  - crypto/jitterentropy-kcapi.c:jent_panic
  - block/bio.c:init_bio
  - block/bio.c:init_bio
  - block/blk-core.c:blk_dev_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - block/blk-crypto.c:bio_crypt_ctx_init
  - lib/cpumask.c:alloc_bootmem_cpumask_var
  - drivers/pci/setup-bus.c:pdev_sort_resources
  - drivers/acpi/apei/ghes.c:__ghes_panic
  - drivers/virtio/virtio.c:virtio_init
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/sysrq.c:sysrq_handle_crash
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/irq_remapping.c:panic_if_irq_remap
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:memory_dev_init
  - drivers/net/loopback.c:loopback_net_init
  - drivers/edac/edac_mc.c:edac_ue_error
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/genetlink.c:genl_init
  - net/netlink/genetlink.c:genl_pernet_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/raw.c:raw_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
  - net/netlabel/netlabel_kapi.c:netlbl_init
  - net/mptcp/protocol.c:mptcp_proto_init
  - net/mptcp/protocol.c:mptcp_proto_init
  - net/mptcp/subflow.c:mptcp_subflow_init
  - net/mptcp/subflow.c:mptcp_subflow_init
  - net/mptcp/ctrl.c:mptcp_init
  - net/mptcp/pm.c:mptcp_pm_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_init
```
**Symbols:**

```
ffffffff810a85be-ffffffff810a88a1: panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void panic(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff81bdb176)
Location: kernel/panic.c:177
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/main.c:kernel_init
  - init/main.c:do_initcalls
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - init/main.c:setup_command_line
  - init/main.c:setup_command_line
  - init/main.c:start_kernel
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
  - init/initramfs.c:populate_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:do_name
  - init/initramfs.c:find_link
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_late_init
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/realmode/init.c:setup_real_mode
  - arch/x86/kernel/traps.c:exc_double_fault
  - arch/x86/kernel/traps.c:handle_stack_overflow
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/setup.c:relocate_initrd
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/kernel/tboot.c:tboot_setup_sleep
  - arch/x86/kernel/tboot.c:tboot_create_trampoline
  - arch/x86/kernel/cpu/mce/core.c:ex_handler_wrmsr_fault
  - arch/x86/kernel/cpu/mce/core.c:ex_handler_rdmsr_fault
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:wait_for_panic
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/acpi/boot.c:acpi_parse_hpet
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:__apic_intr_mode_select
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:ioapic_setup_resources
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_save_irq
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/kvm.c:__kvm_handle_async_pf
  - arch/x86/kernel/kvm.c:__kvm_handle_async_pf
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/sev-es.c:safe_stack_exc_vmm_communication
  - arch/x86/kernel/sev-es.c:ist_exc_vmm_communication
  - arch/x86/kernel/sev-es.c:sev_es_init_vc_handling
  - arch/x86/kernel/sev-es.c:sev_es_init_vc_handling
  - arch/x86/kernel/sev-es.c:sev_es_init_vc_handling
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/mm/init.c:save_mr
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:spp_getpage
  - arch/x86/mm/pat/memtype.c:pat_init
  - kernel/panic.c:__stack_chk_fail
  - kernel/panic.c:__warn
  - kernel/panic.c:nmi_panic
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/cred.c:put_cred_rcu
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule_bug
  - kernel/power/snapshot.c:__register_nosave_region
  - kernel/power/swap.c:swsusp_header_init
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/audit.c:audit_init
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/watchdog.c:watchdog_timer_fn
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/blacklist.c:blacklist_init
  - certs/blacklist.c:blacklist_init
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/sparse.c:memory_present
  - mm/sparse.c:sparse_index_alloc
  - mm/memory-failure.c:memory_failure
  - fs/namespace.c:init_mount_tree
  - fs/namespace.c:init_mount_tree
  - fs/namespace.c:mnt_init
  - fs/nsfs.c:nsfs_init
  - fs/block_dev.c:bdev_cache_init
  - fs/block_dev.c:bdev_cache_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup
  - fs/quota/dquot.c:dquot_init
  - fs/quota/dquot.c:dquot_init
  - fs/quota/dquot.c:dquot_init
  - fs/proc/proc_sysctl.c:do_sysctl_args
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - fs/ext4/super.c:ext4_handle_error
  - fs/fat/misc.c:__fat_fs_error
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - security/security.c:security_add_hooks
  - security/security.c:security_add_hooks
  - security/security.c:ordered_lsm_init
  - security/security.c:ordered_lsm_init
  - security/selinux/hooks.c:selinux_nf_ip_init
  - security/selinux/hooks.c:selinux_init
  - security/selinux/hooks.c:selinux_init
  - security/selinux/netlink.c:selnl_init
  - security/selinux/ss/services.c:aurule_init
  - security/smack/smackfs.c:smk_cipso_doi
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/memory.c:tomoyo_memory_ok
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/lsm.c:apparmor_nf_ip_init
  - security/yama/yama_lsm.c:yama_init
  - security/integrity/iint.c:integrity_inode_get
  - crypto/jitterentropy-kcapi.c:jent_panic
  - block/bio.c:init_bio
  - block/bio.c:init_bio
  - block/blk-core.c:blk_dev_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - block/blk-crypto.c:bio_crypt_ctx_init
  - lib/cpumask.c:alloc_bootmem_cpumask_var
  - drivers/pci/setup-bus.c:pdev_sort_resources
  - drivers/acpi/apei/ghes.c:__ghes_panic
  - drivers/virtio/virtio.c:virtio_init
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/sysrq.c:sysrq_handle_crash
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/irq_remapping.c:panic_if_irq_remap
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:memory_dev_init
  - drivers/net/loopback.c:loopback_net_init
  - drivers/edac/edac_mc.c:edac_ue_error
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/genetlink.c:genl_init
  - net/netlink/genetlink.c:genl_pernet_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/raw.c:raw_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/inet_fragment.c:inet_frag_wq_init
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
  - net/netlabel/netlabel_kapi.c:netlbl_init
  - net/mptcp/protocol.c:mptcp_proto_init
  - net/mptcp/protocol.c:mptcp_proto_init
  - net/mptcp/subflow.c:mptcp_subflow_init
  - net/mptcp/subflow.c:mptcp_subflow_init
  - net/mptcp/ctrl.c:mptcp_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_init
```
**Symbols:**

```
ffffffff81bdb176-ffffffff81bdb459: panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void panic(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff81bcd268)
Location: kernel/panic.c:177
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/main.c:kernel_init
  - init/main.c:do_initcalls
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - init/main.c:setup_command_line
  - init/main.c:setup_command_line
  - init/main.c:start_kernel
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
  - init/initramfs.c:panic_show_mem
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_late_init
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/realmode/init.c:setup_real_mode
  - arch/x86/kernel/traps.c:exc_double_fault
  - arch/x86/kernel/traps.c:handle_stack_overflow
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/mce/core.c:ex_handler_wrmsr_fault
  - arch/x86/kernel/cpu/mce/core.c:ex_handler_rdmsr_fault
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:wait_for_panic
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/acpi/boot.c:acpi_parse_hpet
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_save_irq
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/kvm.c:__kvm_handle_async_pf
  - arch/x86/kernel/kvm.c:__kvm_handle_async_pf
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/sev.c:__sev_get_ghcb
  - arch/x86/kernel/sev.c:kernel_exc_vmm_communication
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/mm/init.c:save_mr
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:spp_getpage
  - arch/x86/mm/pat/memtype.c:pat_init
  - kernel/panic.c:__stack_chk_fail
  - kernel/panic.c:__warn
  - kernel/panic.c:nmi_panic
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/cred.c:put_cred_rcu
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule_bug
  - kernel/power/snapshot.c:__register_nosave_region
  - kernel/power/swap.c:swsusp_header_init
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/audit.c:audit_init
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/watchdog.c:watchdog_timer_fn
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/blacklist.c:blacklist_init
  - certs/blacklist.c:blacklist_init
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/sparse.c:memory_present
  - mm/sparse.c:sparse_index_alloc
  - mm/memory-failure.c:memory_failure
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/nsfs.c:nsfs_init
  - fs/block_dev.c:bdev_cache_init
  - fs/block_dev.c:bdev_cache_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup
  - fs/quota/dquot.c:dquot_init
  - fs/quota/dquot.c:dquot_init
  - fs/quota/dquot.c:dquot_init
  - fs/proc/proc_sysctl.c:do_sysctl_args
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - fs/ext4/super.c:ext4_handle_error
  - fs/fat/misc.c:__fat_fs_error
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - security/security.c:security_add_hooks
  - security/security.c:security_add_hooks
  - security/security.c:ordered_lsm_init
  - security/security.c:ordered_lsm_init
  - security/selinux/hooks.c:selinux_nf_ip_init
  - security/selinux/hooks.c:selinux_init
  - security/selinux/hooks.c:selinux_init
  - security/selinux/netlink.c:selnl_init
  - security/selinux/ss/services.c:aurule_init
  - security/smack/smackfs.c:smk_cipso_doi
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/memory.c:tomoyo_memory_ok
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/lsm.c:apparmor_nf_ip_init
  - security/yama/yama_lsm.c:yama_init
  - security/integrity/iint.c:integrity_inode_get
  - crypto/jitterentropy-kcapi.c:jent_panic
  - block/bio.c:init_bio
  - block/bio.c:init_bio
  - block/blk-core.c:blk_dev_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - block/blk-crypto.c:bio_crypt_ctx_init
  - lib/cpumask.c:alloc_bootmem_cpumask_var
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/acpi/apei/ghes.c:__ghes_panic
  - drivers/virtio/virtio.c:virtio_init
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init_early
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init_early
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init_early
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/sysrq.c:sysrq_handle_crash
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/irq_remapping.c:panic_if_irq_remap
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:memory_dev_init
  - drivers/net/loopback.c:loopback_net_init
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/genetlink.c:genl_init
  - net/netlink/genetlink.c:genl_pernet_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/raw.c:raw_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/inet_fragment.c:inet_frag_wq_init
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
  - net/netlabel/netlabel_kapi.c:netlbl_init
  - net/mptcp/protocol.c:mptcp_proto_init
  - net/mptcp/protocol.c:mptcp_proto_init
  - net/mptcp/subflow.c:mptcp_subflow_init
  - net/mptcp/subflow.c:mptcp_subflow_init
  - net/mptcp/ctrl.c:mptcp_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_init
```
**Symbols:**

```
ffffffff81bcd268-ffffffff81bcd54b: panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void panic(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff81ca39f1)
Location: kernel/panic.c:178
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/main.c:kernel_init
  - init/main.c:do_initcalls
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - init/main.c:setup_command_line
  - init/main.c:setup_command_line
  - init/main.c:start_kernel
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
  - init/initramfs.c:panic_show_mem
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_late_init
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/realmode/init.c:setup_real_mode
  - arch/x86/kernel/traps.c:exc_double_fault
  - arch/x86/kernel/traps.c:handle_stack_overflow
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/mce/core.c:ex_handler_wrmsr_fault
  - arch/x86/kernel/cpu/mce/core.c:ex_handler_rdmsr_fault
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:wait_for_panic
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/acpi/boot.c:acpi_parse_hpet
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_save_irq
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/kvm.c:__kvm_handle_async_pf
  - arch/x86/kernel/kvm.c:__kvm_handle_async_pf
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/sev.c:__sev_get_ghcb
  - arch/x86/kernel/sev.c:kernel_exc_vmm_communication
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/mm/init.c:save_mr
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:spp_getpage
  - arch/x86/mm/pat/memtype.c:pat_init
  - kernel/panic.c:__stack_chk_fail
  - kernel/panic.c:__warn
  - kernel/panic.c:nmi_panic
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/user.c:uid_cache_init
  - kernel/cred.c:put_cred_rcu
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule_bug
  - kernel/power/snapshot.c:register_nosave_region
  - kernel/power/swap.c:swsusp_header_init
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/audit.c:audit_init
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/watchdog.c:watchdog_timer_fn
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/blacklist.c:blacklist_init
  - certs/blacklist.c:blacklist_init
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:out_of_memory
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/sparse.c:memory_present
  - mm/sparse.c:sparse_index_alloc
  - mm/kfence/report.c:kfence_report_error
  - mm/memory-failure.c:memory_failure
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/nsfs.c:nsfs_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup
  - fs/quota/dquot.c:dquot_init
  - fs/quota/dquot.c:dquot_init
  - fs/quota/dquot.c:dquot_init
  - fs/proc/proc_sysctl.c:do_sysctl_args
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - fs/ext4/super.c:ext4_handle_error
  - fs/squashfs/block.c:squashfs_read_data
  - fs/fat/misc.c:__fat_fs_error
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - security/security.c:security_add_hooks
  - security/security.c:security_add_hooks
  - security/security.c:ordered_lsm_init
  - security/security.c:ordered_lsm_init
  - security/selinux/hooks.c:selinux_nf_ip_init
  - security/selinux/hooks.c:selinux_init
  - security/selinux/hooks.c:selinux_init
  - security/selinux/netlink.c:selnl_init
  - security/selinux/ss/services.c:aurule_init
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/memory.c:tomoyo_warn_oom
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/lsm.c:apparmor_nf_ip_init
  - security/yama/yama_lsm.c:yama_init
  - security/integrity/iint.c:integrity_inode_get
  - crypto/jitterentropy-kcapi.c:jent_panic
  - block/bdev.c:bdev_cache_init
  - block/bdev.c:bdev_cache_init
  - block/bio.c:init_bio
  - block/bio.c:init_bio
  - block/blk-core.c:blk_dev_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - block/blk-crypto.c:bio_crypt_ctx_init
  - lib/ubsan.c:__ubsan_handle_builtin_unreachable
  - lib/ubsan.c:ubsan_epilogue
  - lib/cpumask.c:alloc_bootmem_cpumask_var
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/acpi/apei/ghes.c:__ghes_panic
  - drivers/virtio/virtio.c:virtio_init
  - drivers/xen/features.c:xen_setup_features
  - drivers/xen/features.c:xen_setup_features
  - drivers/xen/balloon.c:balloon_wait_finish
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init_early
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init_early
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init_early
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/sysrq.c:sysrq_handle_crash
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/irq_remapping.c:panic_if_irq_remap
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:memory_dev_init
  - drivers/net/loopback.c:loopback_net_init
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/genetlink.c:genl_init
  - net/netlink/genetlink.c:genl_pernet_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/raw.c:raw_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/inet_fragment.c:inet_frag_wq_init
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
  - net/netlabel/netlabel_kapi.c:netlbl_init
  - net/mptcp/protocol.c:mptcp_proto_init
  - net/mptcp/protocol.c:mptcp_proto_init
  - net/mptcp/subflow.c:mptcp_subflow_init
  - net/mptcp/subflow.c:mptcp_subflow_init
  - net/mptcp/ctrl.c:mptcp_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_init
```
**Symbols:**

```
ffffffff81ca39f1-ffffffff81ca3d12: panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void panic(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff81e5319e)
Location: kernel/panic.c:210
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/main.c:kernel_init
  - init/main.c:do_initcalls
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - init/main.c:setup_command_line
  - init/main.c:setup_command_line
  - init/main.c:start_kernel
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
  - init/initramfs.c:panic_show_mem
  - arch/x86/coco/tdx/tdx.c:tdx_get_ve_info
  - arch/x86/coco/tdx/tdx.c:__tdx_hypercall_failed
  - arch/x86/coco/tdx/tdx.c:tdx_early_init
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_late_init
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/realmode/init.c:setup_real_mode
  - arch/x86/kernel/traps.c:exc_double_fault
  - arch/x86/kernel/traps.c:handle_stack_overflow
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/mce/core.c:ex_handler_msr_mce
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:wait_for_panic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_hpet
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_save_irq
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/kvm.c:__kvm_handle_async_pf
  - arch/x86/kernel/kvm.c:__kvm_handle_async_pf
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/sev.c:__sev_get_ghcb
  - arch/x86/kernel/sev.c:kernel_exc_vmm_communication
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/mm/init.c:save_mr
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:spp_getpage
  - arch/x86/mm/pat/memtype.c:pat_init
  - kernel/panic.c:__stack_chk_fail
  - kernel/panic.c:__warn
  - kernel/panic.c:add_taint
  - kernel/exit.c:make_task_dead
  - kernel/exit.c:make_task_dead
  - kernel/exit.c:do_exit
  - kernel/user.c:uid_cache_init
  - kernel/cred.c:put_cred_rcu
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule_bug
  - kernel/power/snapshot.c:register_nosave_region
  - kernel/power/swap.c:swsusp_header_init
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - kernel/dma/swiotlb.c:swiotlb_init_remap
  - kernel/dma/swiotlb.c:swiotlb_init_remap
  - kernel/audit.c:audit_init
  - kernel/debug/debug_core.c:kgdb_reenter_check
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/watchdog.c:watchdog_timer_fn
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:set_machine_trusted_keys
  - certs/blacklist.c:blacklist_init
  - certs/blacklist.c:blacklist_init
  - certs/blacklist.c:blacklist_init
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:out_of_memory
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_populate_pte
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/sparse.c:memory_present
  - mm/sparse.c:sparse_index_alloc
  - mm/kfence/report.c:kfence_report_error
  - mm/memory-failure.c:memory_failure
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/nsfs.c:nsfs_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup
  - fs/quota/dquot.c:dquot_init
  - fs/quota/dquot.c:dquot_init
  - fs/quota/dquot.c:dquot_init
  - fs/proc/proc_sysctl.c:do_sysctl_args
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - fs/ext4/super.c:ext4_handle_error
  - fs/squashfs/block.c:squashfs_read_data
  - fs/fat/misc.c:__fat_fs_error
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - security/security.c:security_add_hooks
  - security/security.c:security_add_hooks
  - security/security.c:ordered_lsm_init
  - security/security.c:ordered_lsm_init
  - security/selinux/hooks.c:selinux_nf_ip_init
  - security/selinux/hooks.c:selinux_init
  - security/selinux/hooks.c:selinux_init
  - security/selinux/netlink.c:selnl_init
  - security/selinux/ss/services.c:aurule_init
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/lsm.c:apparmor_nf_ip_init
  - security/yama/yama_lsm.c:yama_init
  - security/integrity/iint.c:integrity_inode_get
  - crypto/jitterentropy-kcapi.c:jent_panic
  - block/bdev.c:bdev_cache_init
  - block/bdev.c:bdev_cache_init
  - block/bio.c:init_bio
  - block/bio.c:init_bio
  - block/blk-core.c:blk_dev_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - block/blk-crypto.c:bio_crypt_ctx_init
  - lib/ubsan.c:__ubsan_handle_builtin_unreachable
  - lib/ubsan.c:ubsan_epilogue
  - lib/cpumask.c:alloc_bootmem_cpumask_var
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/acpi/apei/ghes.c:__ghes_panic
  - drivers/virtio/virtio.c:virtio_init
  - drivers/xen/features.c:xen_setup_features
  - drivers/xen/features.c:xen_setup_features
  - drivers/xen/balloon.c:balloon_wait_finish
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/sysrq.c:sysrq_handle_crash
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/irq_remapping.c:panic_if_irq_remap
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/node.c:node_dev_init
  - drivers/base/node.c:node_dev_init
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:memory_dev_init
  - drivers/net/loopback.c:loopback_net_init
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/genetlink.c:genl_init
  - net/netlink/genetlink.c:genl_pernet_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/raw.c:raw_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/inet_fragment.c:inet_frag_wq_init
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
  - net/netlabel/netlabel_kapi.c:netlbl_init
  - net/mptcp/protocol.c:mptcp_proto_init
  - net/mptcp/protocol.c:mptcp_proto_init
  - net/mptcp/subflow.c:mptcp_subflow_init
  - net/mptcp/subflow.c:mptcp_subflow_init
  - net/mptcp/ctrl.c:mptcp_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_init
```
**Symbols:**

```
ffffffff81e5319e-ffffffff81e534c2: panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void panic(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/panic.c (0)
Location: kernel/panic.c:276
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/main.c:kernel_init
  - init/main.c:do_initcalls
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - init/main.c:setup_command_line
  - init/main.c:setup_command_line
  - init/main.c:start_kernel
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
  - init/initramfs.c:panic_show_mem
  - arch/x86/coco/tdx/tdx.c:tdx_get_ve_info
  - arch/x86/coco/tdx/tdx.c:__tdx_hypercall_failed
  - arch/x86/coco/tdx/tdx.c:tdx_early_init
  - arch/x86/coco/tdx/tdx.c:tdx_early_init
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_late_init
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/realmode/init.c:setup_real_mode
  - arch/x86/kernel/traps.c:exc_double_fault
  - arch/x86/kernel/traps.c:handle_stack_overflow
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/mce/core.c:ex_handler_msr_mce
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:wait_for_panic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_hpet
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_save_irq
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/kvm.c:__kvm_handle_async_pf
  - arch/x86/kernel/kvm.c:__kvm_handle_async_pf
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/sev.c:__sev_get_ghcb
  - arch/x86/kernel/sev.c:kernel_exc_vmm_communication
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:spp_getpage
  - arch/x86/mm/pat/memtype.c:pat_cpu_init
  - kernel/panic.c:__stack_chk_fail
  - kernel/panic.c:add_taint
  - kernel/exit.c:make_task_dead
  - kernel/exit.c:make_task_dead
  - kernel/exit.c:make_task_dead
  - kernel/exit.c:do_exit
  - kernel/user.c:uid_cache_init
  - kernel/cred.c:put_cred_rcu
  - kernel/sched/core.c:__schedule
  - kernel/power/snapshot.c:register_nosave_region
  - kernel/power/swap.c:swsusp_header_init
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/audit.c:audit_init
  - kernel/debug/debug_core.c:kgdb_reenter_check
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/trace/rv/reactor_panic.c:rv_panic_reaction
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:set_machine_trusted_keys
  - certs/blacklist.c:blacklist_init
  - certs/blacklist.c:blacklist_init
  - certs/blacklist.c:blacklist_init
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:out_of_memory
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_populate_pte
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/sparse.c:memory_present
  - mm/sparse.c:sparse_index_alloc
  - mm/memory-tiers.c:memory_tier_init
  - mm/memory-tiers.c:memory_tier_init
  - mm/memory-failure.c:memory_failure
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/nsfs.c:nsfs_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup
  - fs/quota/dquot.c:dquot_init
  - fs/quota/dquot.c:dquot_init
  - fs/quota/dquot.c:dquot_init
  - fs/proc/proc_sysctl.c:do_sysctl_args
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - fs/ext4/super.c:ext4_handle_error
  - fs/squashfs/block.c:squashfs_read_data
  - fs/fat/misc.c:__fat_fs_error
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - security/security.c:security_add_hooks
  - security/security.c:security_add_hooks
  - security/security.c:ordered_lsm_init
  - security/security.c:ordered_lsm_init
  - security/selinux/hooks.c:selinux_nf_ip_init
  - security/selinux/hooks.c:selinux_init
  - security/selinux/hooks.c:selinux_init
  - security/selinux/netlink.c:selnl_init
  - security/selinux/ss/services.c:aurule_init
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/lsm.c:apparmor_nf_ip_init
  - security/yama/yama_lsm.c:yama_init
  - security/integrity/iint.c:integrity_inode_get
  - crypto/jitterentropy-kcapi.c:jent_panic
  - block/bdev.c:bdev_cache_init
  - block/bdev.c:bdev_cache_init
  - block/bio.c:init_bio
  - block/bio.c:init_bio
  - block/blk-core.c:blk_dev_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - block/blk-crypto.c:bio_crypt_ctx_init
  - lib/ubsan.c:__ubsan_handle_builtin_unreachable
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/acpi/apei/ghes.c:__ghes_panic
  - drivers/virtio/virtio.c:virtio_init
  - drivers/xen/features.c:xen_setup_features
  - drivers/xen/features.c:xen_setup_features
  - drivers/xen/balloon.c:balloon_wait_finish
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/sysrq.c:sysrq_handle_crash
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/irq_remapping.c:panic_if_irq_remap
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/node.c:node_dev_init
  - drivers/base/node.c:node_dev_init
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:memory_dev_init
  - drivers/net/loopback.c:loopback_net_init
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/genetlink.c:genl_init
  - net/netlink/genetlink.c:genl_pernet_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/raw.c:raw_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/inet_fragment.c:inet_frag_wq_init
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
  - net/netlabel/netlabel_kapi.c:netlbl_init
  - net/mptcp/protocol.c:mptcp_proto_init
  - net/mptcp/protocol.c:mptcp_proto_init
  - net/mptcp/subflow.c:mptcp_subflow_init
  - net/mptcp/subflow.c:mptcp_subflow_init
  - net/mptcp/subflow.c:mptcp_subflow_init
  - net/mptcp/ctrl.c:mptcp_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_init
  - lib/cpumask.c:alloc_bootmem_cpumask_var
```
**Symbols:**

```
ffffffff82055aa9-ffffffff82055abe: panic.cold (STB_LOCAL)
ffffffff810ea310-ffffffff810ea6c5: panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void panic(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/panic.c (0)
Location: kernel/panic.c:276
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/main.c:kernel_init
  - init/main.c:do_initcalls
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - init/main.c:setup_command_line
  - init/main.c:setup_command_line
  - init/main.c:start_kernel
  - init/do_mounts.c:mount_root_generic
  - init/initramfs.c:do_populate_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:dir_add
  - init/initramfs.c:find_link
  - arch/x86/coco/tdx/tdx.c:tdx_handle_virt_exception
  - arch/x86/coco/tdx/tdx.c:__tdx_hypercall_failed
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_late_init
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/realmode/init.c:setup_real_mode
  - arch/x86/kernel/traps.c:exc_double_fault
  - arch/x86/kernel/traps.c:handle_stack_overflow
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/mce/core.c:ex_handler_msr_mce
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:wait_for_panic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_hpet
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_save_irq
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/kvm.c:__kvm_handle_async_pf
  - arch/x86/kernel/kvm.c:__kvm_handle_async_pf
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/sev.c:__sev_get_ghcb
  - arch/x86/kernel/sev.c:kernel_exc_vmm_communication
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:spp_getpage
  - arch/x86/mm/pat/memtype.c:pat_cpu_init
  - kernel/panic.c:__stack_chk_fail
  - kernel/panic.c:add_taint
  - kernel/exit.c:make_task_dead
  - kernel/exit.c:make_task_dead
  - kernel/exit.c:make_task_dead
  - kernel/exit.c:do_exit
  - kernel/user.c:uid_cache_init
  - kernel/cred.c:put_cred_rcu
  - kernel/sched/core.c:__schedule
  - kernel/power/snapshot.c:register_nosave_region
  - kernel/power/swap.c:swsusp_header_init
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/audit.c:audit_init
  - kernel/debug/debug_core.c:kgdb_reenter_check
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/trace/trace_osnoise.c:timerlat_fd_read
  - kernel/trace/trace_osnoise.c:timerlat_main
  - kernel/trace/trace_osnoise.c:timerlat_irq
  - kernel/trace/trace_osnoise.c:trace_sched_migrate_callback
  - kernel/trace/rv/reactor_panic.c:rv_panic_reaction
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:set_machine_trusted_keys
  - certs/blacklist.c:blacklist_init
  - certs/blacklist.c:blacklist_init
  - certs/blacklist.c:blacklist_init
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:out_of_memory
  - mm/mm_init.c:alloc_large_system_hash
  - mm/mm_init.c:free_area_init
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_populate_pte
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:new_kmalloc_cache
  - mm/sparse.c:memory_present
  - mm/sparse.c:sparse_index_alloc
  - mm/memory-tiers.c:memory_tier_init
  - mm/memory-tiers.c:memory_tier_init
  - mm/memory-failure.c:memory_failure
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/nsfs.c:nsfs_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup
  - fs/quota/dquot.c:dquot_init
  - fs/quota/dquot.c:dquot_init
  - fs/quota/dquot.c:dquot_init
  - fs/proc/proc_sysctl.c:do_sysctl_args
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - fs/ext4/super.c:ext4_handle_error
  - fs/squashfs/block.c:squashfs_read_data
  - fs/fat/misc.c:__fat_fs_error
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - security/security.c:security_add_hooks
  - security/security.c:security_add_hooks
  - security/security.c:ordered_lsm_init
  - security/security.c:ordered_lsm_init
  - security/selinux/hooks.c:selinux_nf_ip_init
  - security/selinux/hooks.c:selinux_init
  - security/selinux/hooks.c:selinux_init
  - security/selinux/netlink.c:selnl_init
  - security/selinux/ss/services.c:aurule_init
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/lsm.c:apparmor_nf_ip_init
  - security/yama/yama_lsm.c:yama_init
  - block/bdev.c:bdev_cache_init
  - block/bdev.c:bdev_cache_init
  - block/bio.c:init_bio
  - block/bio.c:init_bio
  - block/blk-core.c:blk_dev_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - block/blk-crypto.c:bio_crypt_ctx_init
  - lib/ubsan.c:__ubsan_handle_builtin_unreachable
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/acpi/apei/ghes.c:__ghes_panic
  - drivers/virtio/virtio.c:virtio_init
  - drivers/xen/features.c:xen_setup_features
  - drivers/xen/features.c:xen_setup_features
  - drivers/xen/balloon.c:balloon_wait_finish
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/sysrq.c:sysrq_handle_crash
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/iommu.c:ecmd_submit_sync
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/irq_remapping.c:panic_if_irq_remap
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/node.c:node_dev_init
  - drivers/base/node.c:node_dev_init
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:memory_dev_init
  - drivers/net/loopback.c:loopback_net_init
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/firmware/efi/unaccepted_memory.c:accept_memory
  - drivers/firmware/efi/unaccepted_memory.c:accept_memory
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/genetlink.c:genl_init
  - net/netlink/genetlink.c:genl_pernet_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/raw.c:raw_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/inet_fragment.c:inet_frag_wq_init
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
  - net/netlabel/netlabel_kapi.c:netlbl_init
  - net/mptcp/protocol.c:mptcp_proto_init
  - net/mptcp/protocol.c:mptcp_proto_init
  - net/mptcp/subflow.c:mptcp_subflow_init
  - net/mptcp/subflow.c:mptcp_subflow_init
  - net/mptcp/subflow.c:mptcp_subflow_init
  - net/mptcp/ctrl.c:mptcp_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_init
  - lib/cpumask.c:alloc_bootmem_cpumask_var
```
**Symbols:**

```
ffffffff820d408f-ffffffff820d40a4: panic.cold (STB_LOCAL)
ffffffff810f5f20-ffffffff810f62b3: panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void panic(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/panic.c (0)
Location: kernel/panic.c:277
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/main.c:kernel_init
  - init/main.c:do_initcalls
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - init/main.c:setup_command_line
  - init/main.c:setup_command_line
  - init/main.c:start_kernel
  - init/do_mounts.c:mount_root_generic
  - init/do_mounts.c:mount_root_generic
  - init/initramfs.c:do_populate_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:dir_add
  - init/initramfs.c:find_link
  - arch/x86/coco/tdx/tdx.c:tdx_handle_virt_exception
  - arch/x86/coco/tdx/tdx.c:__tdx_hypercall_failed
  - arch/x86/entry/common.c:do_int80_emulation
  - arch/x86/entry/common.c:do_int80_emulation
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_late_init
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/hyperv/ivm.c:hv_vtom_init
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/realmode/init.c:setup_real_mode
  - arch/x86/kernel/traps.c:exc_double_fault
  - arch/x86/kernel/traps.c:handle_stack_overflow
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/mce/core.c:ex_handler_msr_mce
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:wait_for_panic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_hpet
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_save_irq
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/kvm.c:__kvm_handle_async_pf
  - arch/x86/kernel/kvm.c:__kvm_handle_async_pf
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/sev.c:__sev_get_ghcb
  - arch/x86/kernel/sev.c:kernel_exc_vmm_communication
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:spp_getpage
  - arch/x86/mm/pat/memtype.c:pat_cpu_init
  - kernel/panic.c:__stack_chk_fail
  - kernel/panic.c:add_taint
  - kernel/panic.c:nmi_panic
  - kernel/exit.c:make_task_dead
  - kernel/exit.c:make_task_dead
  - kernel/exit.c:make_task_dead
  - kernel/exit.c:do_exit
  - kernel/user.c:uid_cache_init
  - kernel/cred.c:put_cred_rcu
  - kernel/power/snapshot.c:register_nosave_region
  - kernel/power/swap.c:swsusp_header_init
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/audit.c:audit_init
  - kernel/debug/debug_core.c:kgdb_reenter_check
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/trace/trace_osnoise.c:timerlat_fd_read
  - kernel/trace/trace_osnoise.c:timerlat_main
  - kernel/trace/trace_osnoise.c:timerlat_irq
  - kernel/trace/trace_osnoise.c:trace_sched_migrate_callback
  - kernel/trace/rv/reactor_panic.c:rv_panic_reaction
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:set_machine_trusted_keys
  - certs/blacklist.c:blacklist_init
  - certs/blacklist.c:blacklist_init
  - certs/blacklist.c:blacklist_init
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:out_of_memory
  - mm/mm_init.c:alloc_large_system_hash
  - mm/mm_init.c:free_area_init
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_populate_pte
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:new_kmalloc_cache
  - mm/memblock.c:memblock_double_array
  - mm/sparse.c:memory_present
  - mm/sparse.c:sparse_index_alloc
  - mm/memory-tiers.c:memory_tier_init
  - mm/memory-tiers.c:memory_tier_init
  - mm/memory-failure.c:memory_failure
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/nsfs.c:nsfs_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup
  - fs/verity/init.c:fsverity_init
  - fs/verity/verify.c:fsverity_init_workqueue
  - fs/verity/signature.c:fsverity_init_signature
  - fs/quota/dquot.c:dquot_init
  - fs/quota/dquot.c:dquot_init
  - fs/quota/dquot.c:dquot_init
  - fs/proc/proc_sysctl.c:do_sysctl_args
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - fs/ext4/super.c:ext4_handle_error
  - fs/squashfs/block.c:squashfs_read_data
  - fs/fat/misc.c:__fat_fs_error
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - security/security.c:security_add_hooks
  - security/security.c:security_add_hooks
  - security/security.c:ordered_lsm_init
  - security/security.c:ordered_lsm_init
  - security/selinux/hooks.c:selinux_nf_ip_init
  - security/selinux/hooks.c:selinux_init
  - security/selinux/hooks.c:selinux_init
  - security/selinux/netlink.c:selnl_init
  - security/selinux/ss/services.c:aurule_init
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/lsm.c:apparmor_nf_ip_init
  - security/yama/yama_lsm.c:yama_init
  - block/bdev.c:bdev_cache_init
  - block/bdev.c:bdev_cache_init
  - block/bio.c:init_bio
  - block/bio.c:init_bio
  - block/blk-core.c:blk_dev_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - block/blk-crypto.c:bio_crypt_ctx_init
  - lib/ubsan.c:__ubsan_handle_builtin_unreachable
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/acpi/apei/ghes.c:__ghes_panic
  - drivers/virtio/virtio.c:virtio_init
  - drivers/xen/features.c:xen_setup_features
  - drivers/xen/features.c:xen_setup_features
  - drivers/xen/balloon.c:balloon_wait_finish
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/sysrq.c:sysrq_handle_crash
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/iommu.c:ecmd_submit_sync
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/irq_remapping.c:panic_if_irq_remap
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/node.c:node_dev_init
  - drivers/base/node.c:node_dev_init
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:memory_dev_init
  - drivers/net/loopback.c:loopback_net_init
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/firmware/efi/unaccepted_memory.c:accept_memory
  - drivers/firmware/efi/unaccepted_memory.c:accept_memory
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/genetlink.c:genl_init
  - net/netlink/genetlink.c:genl_pernet_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/raw.c:raw_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/inet_fragment.c:inet_frag_wq_init
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
  - net/netlabel/netlabel_kapi.c:netlbl_init
  - net/mptcp/protocol.c:mptcp_proto_init
  - net/mptcp/protocol.c:mptcp_proto_init
  - net/mptcp/subflow.c:mptcp_subflow_init
  - net/mptcp/subflow.c:mptcp_subflow_init
  - net/mptcp/subflow.c:mptcp_subflow_init
  - net/mptcp/ctrl.c:mptcp_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_init
  - lib/cpumask.c:alloc_bootmem_cpumask_var
```
**Symbols:**

```
ffffffff821aef63-ffffffff821aef78: panic.cold (STB_LOCAL)
ffffffff810ff2b0-ffffffff810ff663: panic (STB_GLOBAL)
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
void panic(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffff8000100f6968)
Location: kernel/panic.c:167
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/main.c:kernel_init
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
  - init/initramfs.c:populate_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:do_name
  - init/initramfs.c:maybe_link
  - arch/arm64/kernel/irq.c:init_IRQ
  - arch/arm64/kernel/fpsimd.c:sve_setup
  - arch/arm64/kernel/setup.c:setup_arch
  - arch/arm64/kernel/time.c:time_init
  - arch/arm64/kernel/traps.c:bad_mode
  - arch/arm64/kernel/traps.c:die
  - arch/arm64/kernel/traps.c:die
  - arch/arm64/kernel/smp.c:__cpu_up
  - arch/arm64/mm/mmu.c:early_pgtable_alloc
  - arch/arm64/mm/context.c:asids_init
  - arch/arm64/mm/numa.c:numa_init
  - arch/arm64/mm/numa.c:setup_per_cpu_areas
  - arch/arm64/kvm/hyp/switch.c:__hyp_call_panic_vhe
  - kernel/panic.c:__stack_chk_fail
  - kernel/panic.c:__warn
  - kernel/panic.c:nmi_panic
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/cred.c:put_cred_rcu
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule_bug
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/audit.c:audit_init
  - kernel/debug/debug_core.c:kgdb_handle_exception
  - kernel/hung_task.c:watchdog
  - kernel/watchdog.c:watchdog_timer_fn
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/blacklist.c:blacklist_init
  - certs/blacklist.c:blacklist_init
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/sparse.c:memory_present
  - mm/sparse.c:sparse_index_alloc
  - mm/memory-failure.c:memory_failure
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/nsfs.c:nsfs_init
  - fs/block_dev.c:bdev_cache_init
  - fs/block_dev.c:bdev_cache_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup
  - fs/quota/dquot.c:dquot_init
  - fs/quota/dquot.c:dquot_init
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/super.c:__ext4_abort
  - fs/fat/misc.c:__fat_fs_error
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - security/security.c:security_add_hooks
  - security/security.c:ordered_lsm_init
  - security/security.c:ordered_lsm_init
  - security/selinux/hooks.c:selinux_nf_ip_init
  - security/selinux/hooks.c:selinux_init
  - security/selinux/hooks.c:selinux_init
  - security/selinux/netlink.c:selnl_init
  - security/selinux/ss/services.c:aurule_init
  - security/smack/smackfs.c:smk_cipso_doi
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/memory.c:tomoyo_warn_oom
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/yama/yama_lsm.c:yama_init
  - crypto/jitterentropy-kcapi.c:jent_panic
  - block/bio.c:init_bio
  - block/bio.c:init_bio
  - block/blk-core.c:blk_dev_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - drivers/irqchip/irq-bcm2836.c:bcm2836_arm_irqchip_l1_intc_of_init
  - drivers/irqchip/irq-bcm2836.c:bcm2836_arm_irqchip_l1_intc_of_init
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/acpi/apei/ghes.c:__ghes_panic
  - drivers/virtio/virtio.c:virtio_init
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/sysrq.c:sysrq_handle_crash
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:memory_dev_init
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/edac/edac_device.c:edac_device_handle_ue
  - drivers/edac/altera_edac.c:altr_edac_a10_ecc_irq
  - drivers/edac/altera_edac.c:altr_sdram_mc_err_handler
  - drivers/firmware/efi/arm-init.c:efi_init
  - drivers/firmware/xilinx/zynqmp.c:zynqmp_firmware_probe
  - drivers/firmware/xilinx/zynqmp.c:zynqmp_firmware_probe
  - drivers/firmware/xilinx/zynqmp.c:zynqmp_firmware_probe
  - drivers/of/fdt.c:early_init_dt_alloc_memory_arch
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/genetlink.c:genl_init
  - net/netlink/genetlink.c:genl_pernet_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/raw.c:raw_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
  - net/netlabel/netlabel_kapi.c:netlbl_init
```
**Symbols:**

```
ffff8000100f6968-ffff8000100f6ca0: panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void panic(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (c0354980)
Location: kernel/panic.c:167
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/main.c:kernel_init
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
  - init/initramfs.c:populate_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:do_name
  - init/initramfs.c:maybe_link
  - arch/arm/kernel/setup.c:setup_arch
  - arch/arm/kernel/traps.c:bad_mode
  - arch/arm/kernel/traps.c:die
  - arch/arm/kernel/traps.c:die
  - arch/arm/kernel/psci_smp.c:psci_cpu_die
  - arch/arm/mm/init.c:arm_memblock_steal
  - arch/arm/mm/mmu.c:vm_reserve_area_early
  - arch/arm/mm/mmu.c:iotable_init
  - arch/arm/mm/mmu.c:early_alloc
  - arch/arm/common/bL_switcher.c:bL_switch_to
  - arch/arm/common/bL_switcher.c:bL_switch_to
  - arch/arm/mach-hisi/hotplug.c:hi3xxx_cpu_die
  - arch/arm/mach-mvebu/platsmp.c:armada_xp_smp_prepare_cpus
  - arch/arm/mach-mvebu/platsmp.c:armada_xp_smp_prepare_cpus
  - arch/arm/mach-mvebu/platsmp.c:armada_xp_smp_prepare_cpus
  - arch/arm/mach-mvebu/platsmp.c:armada_xp_smp_init_cpus
  - arch/arm/plat-samsung/init.c:s3c24xx_init_clocks
  - arch/arm/plat-samsung/init.c:s3c24xx_init_clocks
  - arch/arm/plat-samsung/init.c:s3c_init_cpu
  - arch/arm/plat-samsung/init.c:s3c_init_cpu
  - kernel/panic.c:__stack_chk_fail
  - kernel/panic.c:nmi_panic
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/cred.c:put_cred_rcu
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule_bug
  - kernel/power/snapshot.c:__register_nosave_region
  - kernel/power/swap.c:swsusp_header_init
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/audit.c:audit_init
  - kernel/debug/debug_core.c:kgdb_handle_exception
  - kernel/hung_task.c:watchdog
  - kernel/watchdog.c:watchdog_timer_fn
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/blacklist.c:blacklist_init
  - certs/blacklist.c:blacklist_init
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:setup_per_cpu_areas
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/page_ext.c:page_ext_init_flatmem
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/nsfs.c:nsfs_init
  - fs/block_dev.c:bdev_cache_init
  - fs/block_dev.c:bdev_cache_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup
  - fs/quota/dquot.c:dquot_init
  - fs/quota/dquot.c:dquot_init
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/super.c:__ext4_abort
  - fs/fat/misc.c:__fat_fs_error
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - security/security.c:security_add_hooks
  - security/security.c:ordered_lsm_init
  - security/security.c:ordered_lsm_init
  - security/selinux/hooks.c:selinux_nf_ip_init
  - security/selinux/hooks.c:selinux_init
  - security/selinux/hooks.c:selinux_init
  - security/selinux/netlink.c:selnl_init
  - security/selinux/ss/services.c:aurule_init
  - security/smack/smackfs.c:smk_cipso_doi
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/memory.c:tomoyo_warn_oom
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/yama/yama_lsm.c:yama_init
  - crypto/jitterentropy-kcapi.c:jent_panic
  - block/bio.c:init_bio
  - block/bio.c:init_bio
  - block/blk-core.c:blk_dev_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - drivers/irqchip/irq-orion.c:orion_irq_init
  - drivers/irqchip/irq-orion.c:orion_irq_init
  - drivers/irqchip/irq-orion.c:orion_irq_init
  - drivers/irqchip/irq-orion.c:orion_irq_init
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/clk/samsung/clk.c:samsung_clk_extended_sleep_init
  - drivers/clk/samsung/clk.c:samsung_clk_extended_sleep_init
  - drivers/clk/samsung/clk.c:samsung_cmu_register_one
  - drivers/clk/samsung/clk.c:samsung_cmu_register_one
  - drivers/clk/samsung/clk.c:samsung_clk_of_add_provider
  - drivers/clk/samsung/clk.c:samsung_clk_init
  - drivers/clk/samsung/clk-exynos5250.c:exynos5250_clk_of_clk_init_driver
  - drivers/clk/samsung/clk-exynos5250.c:exynos5250_clk_of_clk_init_driver
  - drivers/clk/samsung/clk-exynos5420.c:exynos5x_clk_init
  - drivers/clk/samsung/clk-exynos5420.c:exynos5x_clk_init
  - drivers/clk/ti/clk.c:omap2_clk_legacy_provider_init
  - drivers/virtio/virtio.c:virtio_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/sysrq.c:sysrq_handle_crash
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/edac/edac_device.c:edac_device_handle_ue
  - drivers/firmware/trusted_foundations.c:of_register_trusted_foundations
  - drivers/firmware/trusted_foundations.c:of_register_trusted_foundations
  - drivers/firmware/efi/arm-init.c:efi_init
  - drivers/clocksource/dw_apb_timer_of.c:dw_apb_timer_init
  - drivers/clocksource/dw_apb_timer_of.c:dw_apb_timer_init
  - drivers/clocksource/dw_apb_timer_of.c:dw_apb_timer_init
  - drivers/clocksource/dw_apb_timer_of.c:timer_get_base_and_rate
  - drivers/clocksource/dw_apb_timer_of.c:timer_get_base_and_rate
  - drivers/clocksource/exynos_mct.c:mct_init_dt
  - drivers/clocksource/exynos_mct.c:mct_init_dt
  - drivers/clocksource/exynos_mct.c:mct_init_dt
  - drivers/clocksource/exynos_mct.c:mct_init_dt
  - drivers/clocksource/exynos_mct.c:exynos4_mct_write
  - drivers/of/fdt.c:early_init_dt_alloc_memory_arch
  - sound/core/init.c:snd_disconnect_release
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/genetlink.c:genl_init
  - net/netlink/genetlink.c:genl_pernet_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/raw.c:raw_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
  - net/netlabel/netlabel_kapi.c:netlbl_init
```
**Symbols:**

```
c0354980-c0354cc8: panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void panic(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (c00000000013c7c0)
Location: kernel/panic.c:167
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/main.c:kernel_init
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
  - init/initramfs.c:populate_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:do_name
  - init/initramfs.c:maybe_link
  - arch/powerpc/kernel/prom.c:early_init_devtree
  - arch/powerpc/kernel/prom.c:early_init_devtree
  - arch/powerpc/kernel/traps.c:StackOverflow
  - arch/powerpc/kernel/setup-common.c:setup_arch
  - arch/powerpc/kernel/setup-common.c:smp_setup_cpu_maps
  - arch/powerpc/kernel/setup_64.c:init_fallback_flush
  - arch/powerpc/kernel/setup_64.c:setup_per_cpu_areas
  - arch/powerpc/kernel/setup_64.c:alloc_stack
  - arch/powerpc/kernel/paca.c:allocate_paca
  - arch/powerpc/kernel/paca.c:allocate_paca_ptrs
  - arch/powerpc/kernel/paca.c:alloc_paca_data
  - arch/powerpc/kernel/rtas.c:rtas_initialize
  - arch/powerpc/kernel/dt_cpu_ftrs.c:dt_cpu_ftrs_scan_callback
  - arch/powerpc/kernel/iommu.c:iommu_init_table
  - arch/powerpc/mm/init-common.c:pgtable_cache_add
  - arch/powerpc/mm/book3s64/hash_utils.c:hash__early_init_mmu
  - arch/powerpc/mm/book3s64/hash_utils.c:htab_initialize
  - arch/powerpc/mm/book3s64/pgtable.c:mmu_partition_table_init
  - arch/powerpc/mm/book3s64/hash_native.c:native_hpte_updateboltedpp
  - arch/powerpc/mm/book3s64/radix_pgtable.c:early_alloc_pgtable
  - arch/powerpc/mm/numa.c:initmem_init
  - arch/powerpc/mm/numa.c:parse_numa_properties
  - arch/powerpc/lib/alloc.c:zalloc_maybe_bootmem
  - arch/powerpc/sysdev/msi_bitmap.c:msi_bitmap_alloc
  - arch/powerpc/platforms/powernv/opal.c:pnv_platform_error_reboot
  - arch/powerpc/platforms/powernv/opal.c:early_init_dt_scan_recoverable_ranges
  - arch/powerpc/platforms/powernv/opal.c:early_init_dt_scan_opal
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_init_ioda_phb
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_init_ioda_phb
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_init_ioda_phb
  - arch/powerpc/platforms/pseries/setup.c:pSeries_setup_arch
  - arch/powerpc/platforms/pseries/setup.c:pSeries_setup_arch
  - arch/powerpc/platforms/pseries/setup.c:pseries_little_endian_exceptions
  - arch/powerpc/platforms/pseries/setup.c:pseries_big_endian_exceptions
  - arch/powerpc/platforms/pseries/iommu.c:iommu_table_setparms
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_mach_cpu_die
  - arch/powerpc/platforms/pseries/vio.c:vio_bus_init
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvmppc_bad_interrupt
  - kernel/panic.c:__stack_chk_fail
  - kernel/panic.c:__warn
  - kernel/panic.c:nmi_panic
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/cred.c:put_cred_rcu
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule_bug
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/audit.c:audit_init
  - kernel/debug/debug_core.c:kgdb_handle_exception
  - kernel/hung_task.c:watchdog
  - kernel/watchdog.c:watchdog_timer_fn
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/blacklist.c:blacklist_init
  - certs/blacklist.c:blacklist_init
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/sparse.c:memory_present
  - mm/sparse.c:sparse_index_alloc
  - mm/memory-failure.c:memory_failure
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/nsfs.c:nsfs_init
  - fs/block_dev.c:bdev_cache_init
  - fs/block_dev.c:bdev_cache_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup
  - fs/quota/dquot.c:dquot_init
  - fs/quota/dquot.c:dquot_init
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/super.c:__ext4_abort
  - fs/fat/misc.c:__fat_fs_error
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - security/security.c:security_add_hooks
  - security/security.c:ordered_lsm_init
  - security/security.c:ordered_lsm_init
  - security/selinux/hooks.c:selinux_nf_ip_init
  - security/selinux/hooks.c:selinux_init
  - security/selinux/hooks.c:selinux_init
  - security/selinux/netlink.c:selnl_init
  - security/selinux/ss/services.c:aurule_init
  - security/smack/smackfs.c:smk_cipso_doi
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/memory.c:tomoyo_warn_oom
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/yama/yama_lsm.c:yama_init
  - crypto/jitterentropy-kcapi.c:jent_panic
  - block/bio.c:init_bio
  - block/bio.c:init_bio
  - block/blk-core.c:blk_dev_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/virtio/virtio.c:virtio_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/sysrq.c:sysrq_handle_crash
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/hvc/hvsi.c:hvsi_init
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:memory_dev_init
  - drivers/net/loopback.c:loopback_net_init
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/edac/edac_device.c:edac_device_handle_ue
  - drivers/of/fdt.c:early_init_dt_alloc_memory_arch
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/genetlink.c:genl_init
  - net/netlink/genetlink.c:genl_pernet_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/raw.c:raw_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
  - net/netlabel/netlabel_kapi.c:netlbl_init
```
**Symbols:**

```
c00000000013c7c0-c00000000013cbc8: panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void panic(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffe0000c2566)
Location: kernel/panic.c:167
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/main.c:kernel_init
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
  - init/initramfs.c:populate_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:do_name
  - init/initramfs.c:maybe_link
  - arch/riscv/kernel/time.c:time_init
  - arch/riscv/kernel/traps.c:die
  - arch/riscv/kernel/traps.c:die
  - arch/riscv/mm/fault.c:do_page_fault
  - kernel/panic.c:__warn
  - kernel/panic.c:nmi_panic
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/cred.c:put_cred_rcu
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule_bug
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/audit.c:audit_init
  - kernel/hung_task.c:watchdog
  - kernel/watchdog.c:watchdog_timer_fn
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/blacklist.c:blacklist_init
  - certs/blacklist.c:blacklist_init
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:setup_per_cpu_areas
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/sparse.c:memory_present
  - mm/sparse.c:sparse_index_alloc
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/nsfs.c:nsfs_init
  - fs/block_dev.c:bdev_cache_init
  - fs/block_dev.c:bdev_cache_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup
  - fs/quota/dquot.c:dquot_init
  - fs/quota/dquot.c:dquot_init
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/super.c:__ext4_abort
  - fs/fat/misc.c:__fat_fs_error
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - security/security.c:security_add_hooks
  - security/security.c:ordered_lsm_init
  - security/security.c:ordered_lsm_init
  - security/selinux/hooks.c:selinux_nf_ip_init
  - security/selinux/hooks.c:selinux_init
  - security/selinux/hooks.c:selinux_init
  - security/selinux/netlink.c:selnl_init
  - security/selinux/ss/services.c:aurule_init
  - security/smack/smackfs.c:smk_cipso_doi
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/memory.c:tomoyo_warn_oom
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/yama/yama_lsm.c:yama_init
  - crypto/jitterentropy-kcapi.c:jent_panic
  - block/bio.c:init_bio
  - block/bio.c:init_bio
  - block/blk-core.c:blk_dev_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/virtio/virtio.c:virtio_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/sysrq.c:sysrq_handle_crash
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/edac/edac_device.c:edac_device_handle_ue
  - drivers/of/fdt.c:early_init_dt_alloc_memory_arch
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/genetlink.c:genl_init
  - net/netlink/genetlink.c:genl_pernet_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/raw.c:raw_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
  - net/netlabel/netlabel_kapi.c:netlbl_init
```
**Symbols:**

```
ffffffe0000c2566-ffffffe0000c283e: panic (STB_GLOBAL)
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
void panic(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff8109b0c5)
Location: kernel/panic.c:167
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/main.c:kernel_init
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
  - init/initramfs.c:populate_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:do_name
  - init/initramfs.c:maybe_link
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_late_init
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/traps.c:handle_stack_overflow
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/acpi/boot.c:acpi_parse_hpet
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_save_irq
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/doublefault.c:df_debug
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
  - arch/x86/mm/init.c:save_mr
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/init_64.c:spp_getpage
  - arch/x86/mm/pat.c:pat_init
  - kernel/panic.c:__stack_chk_fail
  - kernel/panic.c:__warn
  - kernel/panic.c:nmi_panic
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/cred.c:put_cred_rcu
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule_bug
  - kernel/power/snapshot.c:__register_nosave_region
  - kernel/power/swap.c:swsusp_header_init
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/audit.c:audit_init
  - kernel/debug/debug_core.c:kgdb_handle_exception
  - kernel/hung_task.c:watchdog
  - kernel/watchdog.c:watchdog_timer_fn
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/blacklist.c:blacklist_init
  - certs/blacklist.c:blacklist_init
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/sparse.c:memory_present
  - mm/sparse.c:sparse_index_alloc
  - mm/memory-failure.c:memory_failure
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/nsfs.c:nsfs_init
  - fs/block_dev.c:bdev_cache_init
  - fs/block_dev.c:bdev_cache_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup
  - fs/quota/dquot.c:dquot_init
  - fs/quota/dquot.c:dquot_init
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/super.c:__ext4_abort
  - fs/fat/misc.c:__fat_fs_error
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - security/security.c:security_add_hooks
  - security/security.c:ordered_lsm_init
  - security/security.c:ordered_lsm_init
  - security/selinux/hooks.c:selinux_nf_ip_init
  - security/selinux/hooks.c:selinux_init
  - security/selinux/hooks.c:selinux_init
  - security/selinux/netlink.c:selnl_init
  - security/selinux/ss/services.c:aurule_init
  - security/smack/smackfs.c:smk_cipso_doi
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/memory.c:tomoyo_warn_oom
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/yama/yama_lsm.c:yama_init
  - crypto/jitterentropy-kcapi.c:jent_panic
  - block/bio.c:init_bio
  - block/bio.c:init_bio
  - block/blk-core.c:blk_dev_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/virtio/virtio.c:virtio_init
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/sysrq.c:sysrq_handle_crash
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/irq_remapping.c:panic_if_irq_remap
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:memory_dev_init
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/edac/edac_device.c:edac_device_handle_ue
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/genetlink.c:genl_init
  - net/netlink/genetlink.c:genl_pernet_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/raw.c:raw_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
  - net/netlabel/netlabel_kapi.c:netlbl_init
  - lib/cpumask.c:alloc_bootmem_cpumask_var
```
**Symbols:**

```
ffffffff8109b0c5-ffffffff8109b3a8: panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void panic(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff81089b05)
Location: kernel/panic.c:167
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/main.c:kernel_init
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
  - init/initramfs.c:populate_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:do_name
  - init/initramfs.c:maybe_link
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/traps.c:handle_stack_overflow
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/acpi/boot.c:acpi_parse_hpet
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_save_irq
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/doublefault.c:df_debug
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
  - arch/x86/mm/init.c:save_mr
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/init_64.c:spp_getpage
  - arch/x86/mm/pat.c:pat_init
  - kernel/panic.c:__stack_chk_fail
  - kernel/panic.c:__warn
  - kernel/panic.c:nmi_panic
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/cred.c:put_cred_rcu
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule_bug
  - kernel/power/snapshot.c:__register_nosave_region
  - kernel/power/swap.c:swsusp_header_init
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/audit.c:audit_init
  - kernel/debug/debug_core.c:kgdb_handle_exception
  - kernel/hung_task.c:watchdog
  - kernel/watchdog.c:watchdog_timer_fn
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/blacklist.c:blacklist_init
  - certs/blacklist.c:blacklist_init
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/sparse.c:memory_present
  - mm/sparse.c:sparse_index_alloc
  - mm/memory-failure.c:memory_failure
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/nsfs.c:nsfs_init
  - fs/block_dev.c:bdev_cache_init
  - fs/block_dev.c:bdev_cache_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup
  - fs/quota/dquot.c:dquot_init
  - fs/quota/dquot.c:dquot_init
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/super.c:__ext4_abort
  - fs/fat/misc.c:__fat_fs_error
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - security/security.c:security_add_hooks
  - security/security.c:ordered_lsm_init
  - security/security.c:ordered_lsm_init
  - security/selinux/hooks.c:selinux_nf_ip_init
  - security/selinux/hooks.c:selinux_init
  - security/selinux/hooks.c:selinux_init
  - security/selinux/netlink.c:selnl_init
  - security/selinux/ss/services.c:aurule_init
  - security/smack/smackfs.c:smk_cipso_doi
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/memory.c:tomoyo_warn_oom
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/yama/yama_lsm.c:yama_init
  - crypto/jitterentropy-kcapi.c:jent_panic
  - block/bio.c:init_bio
  - block/bio.c:init_bio
  - block/blk-core.c:blk_dev_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/virtio/virtio.c:virtio_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/sysrq.c:sysrq_handle_crash
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/irq_remapping.c:panic_if_irq_remap
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:memory_dev_init
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/edac/edac_device.c:edac_device_handle_ue
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/genetlink.c:genl_init
  - net/netlink/genetlink.c:genl_pernet_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/raw.c:raw_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
  - net/netlabel/netlabel_kapi.c:netlbl_init
  - lib/cpumask.c:alloc_bootmem_cpumask_var
```
**Symbols:**

```
ffffffff81089b05-ffffffff81089ddc: panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void panic(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff8109b075)
Location: kernel/panic.c:167
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/main.c:kernel_init
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
  - init/initramfs.c:populate_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:do_name
  - init/initramfs.c:maybe_link
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_late_init
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/traps.c:handle_stack_overflow
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/acpi/boot.c:acpi_parse_hpet
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_save_irq
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/doublefault.c:df_debug
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
  - arch/x86/mm/init.c:save_mr
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/init_64.c:spp_getpage
  - arch/x86/mm/pat.c:pat_init
  - kernel/panic.c:__stack_chk_fail
  - kernel/panic.c:__warn
  - kernel/panic.c:nmi_panic
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/cred.c:put_cred_rcu
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule_bug
  - kernel/power/snapshot.c:__register_nosave_region
  - kernel/power/swap.c:swsusp_header_init
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/audit.c:audit_init
  - kernel/debug/debug_core.c:kgdb_handle_exception
  - kernel/hung_task.c:watchdog
  - kernel/watchdog.c:watchdog_timer_fn
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/blacklist.c:blacklist_init
  - certs/blacklist.c:blacklist_init
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/sparse.c:memory_present
  - mm/sparse.c:sparse_index_alloc
  - mm/memory-failure.c:memory_failure
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/nsfs.c:nsfs_init
  - fs/block_dev.c:bdev_cache_init
  - fs/block_dev.c:bdev_cache_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup
  - fs/quota/dquot.c:dquot_init
  - fs/quota/dquot.c:dquot_init
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/super.c:__ext4_abort
  - fs/fat/misc.c:__fat_fs_error
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - security/security.c:security_add_hooks
  - security/security.c:ordered_lsm_init
  - security/security.c:ordered_lsm_init
  - security/selinux/hooks.c:selinux_nf_ip_init
  - security/selinux/hooks.c:selinux_init
  - security/selinux/hooks.c:selinux_init
  - security/selinux/netlink.c:selnl_init
  - security/selinux/ss/services.c:aurule_init
  - security/smack/smackfs.c:smk_cipso_doi
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/memory.c:tomoyo_warn_oom
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/yama/yama_lsm.c:yama_init
  - crypto/jitterentropy-kcapi.c:jent_panic
  - block/bio.c:init_bio
  - block/bio.c:init_bio
  - block/blk-core.c:blk_dev_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/virtio/virtio.c:virtio_init
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/sysrq.c:sysrq_handle_crash
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/irq_remapping.c:panic_if_irq_remap
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:memory_dev_init
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/edac/edac_device.c:edac_device_handle_ue
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/genetlink.c:genl_init
  - net/netlink/genetlink.c:genl_pernet_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/raw.c:raw_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
  - net/netlabel/netlabel_kapi.c:netlbl_init
  - lib/cpumask.c:alloc_bootmem_cpumask_var
```
**Symbols:**

```
ffffffff8109b075-ffffffff8109b358: panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void panic(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810a2ce5)
Location: kernel/panic.c:167
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/main.c:kernel_init
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
  - init/initramfs.c:populate_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:do_name
  - init/initramfs.c:maybe_link
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_late_init
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/traps.c:handle_stack_overflow
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/acpi/boot.c:acpi_parse_hpet
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_save_irq
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_undefined
  - arch/x86/kernel/doublefault.c:df_debug
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
  - arch/x86/mm/init.c:save_mr
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/init_64.c:spp_getpage
  - arch/x86/mm/pat.c:pat_init
  - kernel/panic.c:__stack_chk_fail
  - kernel/panic.c:__warn
  - kernel/panic.c:nmi_panic
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/cred.c:put_cred_rcu
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule_bug
  - kernel/power/snapshot.c:__register_nosave_region
  - kernel/power/swap.c:swsusp_header_init
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/audit.c:audit_init
  - kernel/debug/debug_core.c:kgdb_handle_exception
  - kernel/hung_task.c:watchdog
  - kernel/watchdog.c:watchdog_timer_fn
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/blacklist.c:blacklist_init
  - certs/blacklist.c:blacklist_init
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/sparse.c:memory_present
  - mm/sparse.c:sparse_index_alloc
  - mm/memory-failure.c:memory_failure
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - fs/nsfs.c:nsfs_init
  - fs/block_dev.c:bdev_cache_init
  - fs/block_dev.c:bdev_cache_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup
  - fs/quota/dquot.c:dquot_init
  - fs/quota/dquot.c:dquot_init
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/super.c:__ext4_abort
  - fs/fat/misc.c:__fat_fs_error
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - security/security.c:security_add_hooks
  - security/security.c:ordered_lsm_init
  - security/security.c:ordered_lsm_init
  - security/selinux/hooks.c:selinux_nf_ip_init
  - security/selinux/hooks.c:selinux_init
  - security/selinux/hooks.c:selinux_init
  - security/selinux/netlink.c:selnl_init
  - security/selinux/ss/services.c:aurule_init
  - security/smack/smackfs.c:smk_cipso_doi
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/memory.c:tomoyo_warn_oom
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/yama/yama_lsm.c:yama_init
  - crypto/jitterentropy-kcapi.c:jent_panic
  - block/bio.c:init_bio
  - block/bio.c:init_bio
  - block/blk-core.c:blk_dev_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/virtio/virtio.c:virtio_init
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/sysrq.c:sysrq_handle_crash
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/irq_remapping.c:panic_if_irq_remap
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:memory_dev_init
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/edac/edac_device.c:edac_device_handle_ue
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/genetlink.c:genl_init
  - net/netlink/genetlink.c:genl_pernet_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/raw.c:raw_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
  - net/netlabel/netlabel_kapi.c:netlbl_init
  - lib/cpumask.c:alloc_bootmem_cpumask_var
```
**Symbols:**

```
ffffffff810a2ce5-ffffffff810a2fcf: panic (STB_GLOBAL)
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
