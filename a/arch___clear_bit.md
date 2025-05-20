# Function: <code>arch___clear_bit</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006628)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_stop
```
```
In arch/x86/events/intel/core.c (ffffffff8100d03e)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/kernel/ioport.c (0)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104c13e)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__mce_disable_bank
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104f47c)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81060a2c)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/smp.c (ffffffff81062b94)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:native_send_call_func_ipi
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106c9f8)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106d0f2)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
```
```
In arch/x86/kernel/kvm.c (ffffffff81076428)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81a93c43)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/workqueue.c (ffffffff810b9bbf)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/fair.c (ffffffff810e0b79)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/rt.c (ffffffff810e344e)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/sched/debug.c (ffffffff810f0cdb)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/isolation.c (ffffffff828c55b9)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
```
```
In kernel/time/timer.c (ffffffff81128178)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/smp.c (ffffffff811432bf)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In mm/filemap.c (ffffffff81215f37)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff81223dfb)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8122c6f9)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
```
```
In mm/page_alloc.c (ffffffff828d5df5)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/swap_state.c (ffffffff8127764f)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff81284865)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/slub.c (ffffffff8129823e)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff812a0078)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_page
```
```
In mm/cma.c (0)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
```
```
In mm/memremap.c (ffffffff812c2410)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
```
```
In fs/dcache.c (ffffffff812e6620)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/file.c (ffffffff812edf45)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
```
```
In fs/mbcache.c (ffffffff8134754f)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/ext4/mballoc.c (ffffffff813a3259)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_clear_bits
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dev.c (ffffffff81407394)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_force_forget
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
```
```
In fs/fuse/file.c (ffffffff8140cd04)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
```
```
In fs/fuse/inode.c (ffffffff81412e7f)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_sb_destroy
```
```
In block/blk-cgroup.c (ffffffff814f0f03)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff8154de21)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/pwm/core.c (0)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
```
```
In drivers/acpi/hmat/hmat.c (0)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8169566e)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff816be8b3)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:domain_id_free
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
```
```
In drivers/net/phy/phy.c (ffffffff81794fa6)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (ffffffff81796035)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy-core.c (ffffffff817968fb)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_set_max_speed
```
```
In drivers/net/phy/phy_device.c (ffffffff81799625)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_remove_link_mode
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
```
```
In drivers/net/tun.c (ffffffff8179d65c)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
```
```
In drivers/input/input.c (ffffffff8182729d)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_keycode
  - drivers/input/input.c:input_default_setkeycode
```
```
In drivers/input/ff-core.c (ffffffff81829273)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_destroy
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8182e23c)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In net/socket.c (ffffffff818d9869)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff818e2920)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/dev.c (ffffffff81903337)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
```
```
In net/netlink/af_netlink.c (ffffffff81966b55)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819843ef)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff8198c96d)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff8198d97e)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffffffff819996ba)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/unix/garbage.c (ffffffff819fdbd5)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (ffffffff819fedba)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
```
```
In lib/idr.c (ffffffff81a7823c)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - lib/idr.c:ida_free
```
```
In lib/radix-tree.c (ffffffff81a7cc02)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (0)
Location: arch/x86/include/asm/bitops.h:93
Inline: True
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
In arch/x86/events/core.c (ffffffff810066b8)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_stop
```
```
In arch/x86/events/intel/core.c (ffffffff8100d4ae)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/kernel/ioport.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104cafe)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__mce_disable_bank
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104fdfc)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810612dc)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106e198)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106e651)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
```
```
In arch/x86/kernel/kvm.c (ffffffff81077438)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81acb523)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/workqueue.c (ffffffff810c003f)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/fair.c (ffffffff810eb209)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/rt.c (ffffffff810edddf)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:alloc_rt_sched_group
```
```
In kernel/sched/debug.c (ffffffff810fc98b)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/isolation.c (ffffffff828cdc22)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In kernel/time/timer.c (ffffffff81134118)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/smp.c (ffffffff8114edff)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In mm/filemap.c (ffffffff81223837)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff81231b8b)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8123a919)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In mm/page_alloc.c (ffffffff828de269)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/swap_state.c (ffffffff81287136)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff81294405)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/slub.c (ffffffff812a809e)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff812b1418)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_page
```
```
In mm/cma.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In mm/memremap.c (ffffffff812d4340)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In fs/dcache.c (ffffffff812f8180)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/file.c (ffffffff812ffa05)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
```
```
In fs/mbcache.c (ffffffff8135f6bf)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/ext4/mballoc.c (ffffffff813bc0b9)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_clear_bits
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dev.c (ffffffff8142219c)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
```
```
In block/blk-cgroup.c (ffffffff8150a100)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff8156f021)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/pwm/core.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/acpi/hmat/hmat.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff816b81fe)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff816e1c83)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:domain_id_free
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/net/phy/phy.c (ffffffff817b8b15)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (ffffffff817b99f5)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy-core.c (ffffffff817badf9)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_set_max_speed
```
```
In drivers/net/phy/phy_device.c (ffffffff817bd145)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_remove_link_mode
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
```
```
In drivers/net/tun.c (ffffffff817c10fc)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/input/input.c (ffffffff818587cd)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_keycode
  - drivers/input/input.c:input_default_setkeycode
```
```
In drivers/input/ff-core.c (ffffffff8185ac03)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_destroy
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8185fb6c)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In net/socket.c (ffffffff8190b849)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81914af0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/dev.c (ffffffff819360e7)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
```
```
In net/netlink/af_netlink.c (ffffffff8199d5d5)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bab9f)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff819c32dd)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff819c452e)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffffffff819d00ba)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/unix/garbage.c (ffffffff81a347c5)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (ffffffff81a359ba)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a90be9)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In lib/idr.c (ffffffff81aaf4fc)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - lib/idr.c:ida_free
```
```
In lib/radix-tree.c (ffffffff81ab3f32)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
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
In arch/x86/events/core.c (ffffffff81007818)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_stop
```
```
In arch/x86/events/intel/core.c (ffffffff8100e72f)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/kernel/ioport.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105171e)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__mce_disable_bank
  - arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff810544fc)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81066e7b)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81075818)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81075b11)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
```
```
In arch/x86/kernel/kvm.c (ffffffff8107e788)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81bc3a29)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/workqueue.c (ffffffff810c774f)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/fair.c (ffffffff810f5043)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/rt.c (ffffffff810f760b)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/rt.c:__dequeue_rt_entity
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/sched/debug.c (ffffffff811070df)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/isolation.c (ffffffff82ceefe6)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In kernel/time/timer.c (ffffffff81144299)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/smp.c (ffffffff8115f76f)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In mm/filemap.c (ffffffff81250f07)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff8125e74a)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff81265394)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In mm/page_alloc.c (ffffffff812b46a8)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_one_page
```
```
In mm/hugetlb.c (ffffffff812c77f5)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:destroy_compound_gigantic_page
```
```
In mm/slub.c (ffffffff812dd301)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff812e66d5)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_pages
```
```
In mm/memremap.c (ffffffff8130aa69)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/memremap.c:free_devmap_managed_page
  - mm/memremap.c:free_devmap_managed_page
```
```
In fs/dcache.c (ffffffff81330ee0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/file.c (ffffffff81338b3b)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
```
```
In fs/mbcache.c (ffffffff813a529b)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_create
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/ext4/mballoc.c (ffffffff81407cf1)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_clear_bits
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dev.c (ffffffff8146e4bc)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In block/blk-cgroup.c (ffffffff8156ae64)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In lib/bitmap.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In lib/idr.c (ffffffff815e93a8)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - lib/idr.c:ida_free
```
```
In lib/radix-tree.c (ffffffff815edf32)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff816134e1)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/pwm/core.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/acpi/numa/hmat.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8176c2e0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/iommu/amd/iommu.c (ffffffff81799db7)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:protection_domain_free
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff8183722d)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
```
```
In drivers/net/phy/phy.c (ffffffff8187fc5e)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
```
```
In drivers/net/phy/phy-c45.c (ffffffff81880ef5)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy-core.c (ffffffff818826a5)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_set_max_speed
```
```
In drivers/net/phy/phy_device.c (ffffffff81884f45)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_remove_link_mode
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
```
```
In drivers/net/phy/linkmode.c (ffffffff81886045)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/bcm84881.c (ffffffff818890f6)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/bcm84881.c:bcm84881_get_features
  - drivers/net/phy/bcm84881.c:bcm84881_get_features
```
```
In drivers/net/tun.c (ffffffff8188ad0c)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/input/input.c (ffffffff81929ae7)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_keycode
  - drivers/input/input.c:input_default_setkeycode
```
```
In drivers/input/ff-core.c (ffffffff8192d623)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_destroy
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81933c74)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In net/socket.c (ffffffff819dda39)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff819e7068)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/dev.c (ffffffff81a0ae6f)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
```
```
In net/core/filter.c (ffffffff81a31a20)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/netlink/af_netlink.c (ffffffff81a7b5b4)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_clear_multicast_users
  - net/netlink/af_netlink.c:netlink_setsockopt
```
```
In net/ethtool/bitset.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa5434)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff81aae988)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff81ab326e)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffffffff81abd106)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/unix/garbage.c (ffffffff81b295e9)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (ffffffff81b2a9a9)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_net_init
```
```
In net/packet/af_packet.c (ffffffff81b8c06a)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/mptcp/protocol.c (ffffffff81bad81d)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sk_clone
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
In arch/x86/events/core.c (ffffffff810068d7)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_stop
```
```
In arch/x86/events/intel/core.c (ffffffff8100db40)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_fixed
  - arch/x86/events/intel/core.c:intel_pmu_disable_fixed
  - arch/x86/events/intel/core.c:intel_pmu_disable_fixed
```
```
In arch/x86/kernel/ioport.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810509de)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__mce_disable_bank
  - arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8105343c)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810650bb)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81075e5b)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81076141)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
```
```
In arch/x86/kernel/kvm.c (ffffffff8107e3b8)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81c3c95b)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/workqueue.c (ffffffff810c272d)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/fair.c (ffffffff810f30d5)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/rt.c (ffffffff810f580b)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/rt.c:__dequeue_rt_entity
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/sched/debug.c (ffffffff811058ef)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/isolation.c (ffffffff82fdb6fd)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In kernel/time/timer.c (ffffffff8114082f)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/smp.c (ffffffff8115b70f)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/seccomp.c (ffffffff811a381c)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In mm/filemap.c (ffffffff8125b247)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff81268999)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff81270059)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In mm/page_alloc.c (ffffffff812c03fe)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_one_page
```
```
In mm/hugetlb.c (ffffffff812d3365)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/slub.c (ffffffff812e60d1)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff812f1b84)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_pages
```
```
In mm/memremap.c (ffffffff81316937)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/memremap.c:free_devmap_managed_page
```
```
In fs/dcache.c (ffffffff8133c870)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/file.c (ffffffff813445bb)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd_get_file
  - fs/file.c:pick_file
  - fs/file.c:pick_file
  - fs/file.c:put_unused_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:alloc_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
```
```
In fs/mbcache.c (ffffffff813b5ffb)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_create
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/ext4/mballoc.c (ffffffff8141a741)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_clear_bits
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dev.c (ffffffff81488c2f)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_put_request
```
```
In block/blk-cgroup.c (ffffffff81585814)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In lib/bitmap.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In lib/idr.c (ffffffff8160e458)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - lib/idr.c:ida_free
```
```
In lib/radix-tree.c (ffffffff81612662)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff816383b8)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/pwm/core.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/acpi/numa/hmat.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81786e00)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/iommu/amd/iommu.c (ffffffff817a84e7)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:protection_domain_free
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff818468bf)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
```
In drivers/net/phy/phy.c (ffffffff8188e50e)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
```
```
In drivers/net/phy/phy-c45.c (ffffffff8188f625)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy-core.c (ffffffff81890dd5)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_set_max_speed
```
```
In drivers/net/phy/phy_device.c (ffffffff818939c5)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_remove_link_mode
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
```
```
In drivers/net/phy/linkmode.c (ffffffff818944a5)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/bcm84881.c (ffffffff81897366)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/bcm84881.c:bcm84881_get_features
  - drivers/net/phy/bcm84881.c:bcm84881_get_features
```
```
In drivers/net/tun.c (ffffffff818989b2)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp
  - drivers/net/tun.c:tun_xdp
```
```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/input/input.c (ffffffff81931057)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_keycode
  - drivers/input/input.c:input_default_setkeycode
```
```
In drivers/input/ff-core.c (ffffffff819349f3)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_destroy
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8193aec4)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In net/socket.c (ffffffff819dd429)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff819e689e)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/dev.c (ffffffff81a0c0bb)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
```
```
In net/core/filter.c (ffffffff81a2ae3c)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_setsockopt
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/netlink/af_netlink.c (ffffffff81a84434)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_clear_multicast_users
  - net/netlink/af_netlink.c:netlink_setsockopt
```
```
In net/ethtool/bitset.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aafa34)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff81ab8bc8)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81ac885b)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/unix/garbage.c (ffffffff81b37f19)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (ffffffff81b39339)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_net_init
```
```
In net/packet/af_packet.c (ffffffff81b9b4c7)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/mptcp/protocol.c (ffffffff81bc07d6)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sk_clone
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
In arch/x86/events/core.c (ffffffff81008bfd)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:x86_pmu_stop
```
```
In arch/x86/events/intel/core.c (ffffffff8100fecc)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
```
In arch/x86/kernel/ioport.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105238e)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__mce_disable_bank
  - arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81054d0c)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106572f)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810768db)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81076bd1)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
```
```
In arch/x86/kernel/kvm.c (ffffffff8107f4c8)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_multi
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81c2ee37)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/workqueue.c (ffffffff810c442d)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/fair.c (ffffffff810f52a5)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/rt.c (ffffffff810f7975)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/sched/debug.c (ffffffff81107990)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/debug.c:update_sched_domain_debugfs
```
```
In kernel/sched/isolation.c (ffffffff831e6457)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In kernel/time/timer.c (ffffffff811419af)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/smp.c (ffffffff8115c7f5)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/seccomp.c (ffffffff811a443c)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In mm/filemap.c (ffffffff8125eed7)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff8126e830)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff812750cb)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In mm/page_alloc.c (ffffffff812c5b78)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_one_page
```
```
In mm/hugetlb.c (ffffffff812da0a5)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/slub.c (ffffffff812ed861)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff812f7e99)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_pages
```
```
In mm/memremap.c (ffffffff8131cb87)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/memremap.c:free_devmap_managed_page
```
```
In fs/dcache.c (ffffffff81342cf5)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/file.c (ffffffff8134a95b)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd_get_file
  - fs/file.c:pick_file
  - fs/file.c:pick_file
  - fs/file.c:put_unused_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:alloc_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
```
```
In fs/mbcache.c (ffffffff813bd14b)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_create
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/ext4/mballoc.c (ffffffff81420bf3)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_clear_bits
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dev.c (ffffffff8148e52f)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_put_request
```
```
In block/blk-cgroup.c (ffffffff8158c7c7)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In lib/bitmap.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In lib/idr.c (ffffffff815f1ba8)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - lib/idr.c:ida_free
```
```
In lib/radix-tree.c (ffffffff815f5d42)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff8161befb)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/pwm/core.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/acpi/numa/hmat.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8176a760)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/iommu/amd/iommu.c (ffffffff8178919e)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:protection_domain_free
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81829acf)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
```
In drivers/net/phy/phy.c (ffffffff81870d71)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
```
```
In drivers/net/phy/phy-c45.c (ffffffff81871f06)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy-core.c (ffffffff818736b5)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_set_max_speed
```
```
In drivers/net/phy/phy_device.c (ffffffff8187659d)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_remove_link_mode
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
```
```
In drivers/net/phy/linkmode.c (ffffffff81876da5)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/bcm84881.c (ffffffff81879b7d)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/bcm84881.c:bcm84881_get_features
  - drivers/net/phy/bcm84881.c:bcm84881_get_features
```
```
In drivers/net/tun.c (ffffffff8187b0f5)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp
  - drivers/net/tun.c:tun_xdp
```
```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/input/input.c (ffffffff819142d7)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_keycode
  - drivers/input/input.c:input_default_setkeycode
```
```
In drivers/input/ff-core.c (ffffffff81917d33)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_destroy
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8191dfc5)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In net/socket.c (ffffffff819c367c)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff819cc6a6)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/dev.c (ffffffff819f2270)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
```
```
In net/core/filter.c (ffffffff81a12051)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_setsockopt
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/netlink/af_netlink.c (ffffffff81a6d524)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_clear_multicast_users
  - net/netlink/af_netlink.c:netlink_setsockopt
```
```
In net/ethtool/bitset.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9ad44)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff81aa3e78)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81ab3590)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/unix/garbage.c (ffffffff81b25bb1)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (ffffffff81b26f1a)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_net_init
```
```
In net/packet/af_packet.c (ffffffff81b8ae95)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/mptcp/protocol.c (ffffffff81bb058a)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sk_clone
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb9bf3)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
```
```
In net/mptcp/sockopt.c (ffffffff81bbc0ea)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
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
In arch/x86/events/core.c (ffffffff81009a7a)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:x86_pmu_stop
```
```
In arch/x86/events/intel/core.c (ffffffff8101089a)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
```
In arch/x86/kernel/ioport.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105a80e)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__mce_disable_bank
  - arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8105d65c)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106f82d)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8108404b)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810843b1)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
```
```
In arch/x86/kernel/kvm.c (ffffffff8108e23b)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_multi
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81d4d538)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/workqueue.c (ffffffff810d703a)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/workqueue.c:pwq_activate_inactive_work
```
```
In kernel/sched/fair.c (ffffffff8110edb4)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/rt.c (ffffffff81111fc4)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/sched/debug.c (ffffffff81125a6b)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/debug.c:update_sched_domain_debugfs
```
```
In kernel/sched/isolation.c (ffffffff832ca553)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In kernel/time/timer.c (ffffffff81164eec)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/smp.c (ffffffff8118194b)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/seccomp.c (ffffffff811cdc0f)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff8126e045)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In mm/filemap.c (ffffffff8129c2e7)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff812ab841)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff812b23a3)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In mm/page_alloc.c (ffffffff8130a2d1)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_one_page
```
```
In mm/hugetlb.c (ffffffff81320e62)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
```
```
In mm/slub.c (ffffffff81335bd8)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff81342506)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_pages
```
```
In mm/memremap.c (ffffffff81369ed1)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/memremap.c:free_devmap_managed_page
```
```
In fs/dcache.c (ffffffff81390735)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/file.c (ffffffff8139870b)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd_get_file
  - fs/file.c:pick_file
  - fs/file.c:pick_file
  - fs/file.c:put_unused_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:alloc_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
```
```
In fs/mbcache.c (ffffffff8140ceef)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_create
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/ext4/mballoc.c (ffffffff81473ff7)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_clear_bits
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dev.c (ffffffff814e5f9f)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_put_request
```
```
In block/blk-cgroup.c (ffffffff815f1dff)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In lib/bitmap.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In lib/idr.c (ffffffff8165ed28)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - lib/idr.c:ida_free
```
```
In lib/radix-tree.c (ffffffff8166320c)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff8168b294)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/pwm/core.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/acpi/numa/hmat.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff817efa33)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/iommu/amd/iommu.c (ffffffff8181109a)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b550f)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
```
In drivers/net/phy/phy.c (ffffffff81900ff5)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
```
In drivers/net/phy/phy-c45.c (ffffffff81902506)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy-core.c (ffffffff81903f79)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_set_max_speed
```
```
In drivers/net/phy/phy_device.c (ffffffff819071ad)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_remove_link_mode
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
```
```
In drivers/net/phy/linkmode.c (ffffffff819079b5)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/bcm84881.c (ffffffff8190ac1d)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/bcm84881.c:bcm84881_get_features
  - drivers/net/phy/bcm84881.c:bcm84881_get_features
```
```
In drivers/net/tun.c (ffffffff8190c604)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp
  - drivers/net/tun.c:tun_xdp
```
```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/input/input.c (ffffffff819b63d2)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_keycode
  - drivers/input/input.c:input_default_setkeycode
```
```
In drivers/input/ff-core.c (ffffffff819b9fa3)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_destroy
```
```
In drivers/input/keyboard/atkbd.c (ffffffff819c1567)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In net/socket.c (ffffffff81a72f0c)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81a7bd25)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_timestamping
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/dev.c (ffffffff81aa4140)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
```
```
In net/core/filter.c (ffffffff81acd37a)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_setsockopt
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/netlink/af_netlink.c (ffffffff81b26ba4)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_clear_multicast_users
  - net/netlink/af_netlink.c:netlink_setsockopt
```
```
In net/ethtool/bitset.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b561b4)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff81b6008d)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81b703a2)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/unix/garbage.c (ffffffff81beb2cb)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (ffffffff81bec97c)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_net_init
```
```
In net/packet/af_packet.c (ffffffff81c570d8)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/mptcp/protocol.c (ffffffff81c7e444)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sk_clone
```
```
In net/mptcp/pm_netlink.c (ffffffff81c89503)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
```
```
In net/mptcp/sockopt.c (ffffffff81c8bc8a)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
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
In arch/x86/events/core.c (ffffffff81009178)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:x86_pmu_stop
```
```
In arch/x86/events/intel/core.c (ffffffff81011f35)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
```
In arch/x86/kernel/ioport.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810671db)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__mce_disable_bank
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81069e9a)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8107d0d4)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8109414b)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81094561)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
```
```
In arch/x86/kernel/kvm.c (ffffffff8109ebfb)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_multi
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81f1d237)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/workqueue.c (ffffffff810f0c2d)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/workqueue.c:pwq_activate_inactive_work
```
```
In kernel/sched/fair.c (ffffffff8112ad02)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/build_policy.c (ffffffff8112f162)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dequeue_rt_stack
  - kernel/sched/build_policy.c:init_rt_rq
```
```
In kernel/sched/build_utility.c (ffffffff8347d6f6)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:update_sched_domain_debugfs
```
```
In kernel/irq/irqdesc.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In kernel/time/timer.c (ffffffff81198ae6)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/smp.c (ffffffff811b7f99)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/seccomp.c (ffffffff8120195d)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff812bceab)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In mm/filemap.c (ffffffff812f298b)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/filemap.c:filemap_add_folio
```
```
In mm/swap.c (ffffffff8130566c)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8130d343)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In mm/page_alloc.c (ffffffff81372c3a)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:split_free_page
  - mm/page_alloc.c:__free_one_page
```
```
In mm/hugetlb.c (ffffffff8138dbc8)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:__prep_compound_gigantic_page
  - mm/hugetlb.c:__prep_compound_gigantic_page
  - mm/hugetlb.c:__prep_compound_gigantic_page
  - mm/hugetlb.c:__prep_compound_gigantic_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:__destroy_compound_gigantic_page
```
```
In mm/slub.c (ffffffff813a738f)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:free_partial
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:free_debug_processing
```
```
In mm/kfence/core.c (ffffffff8349276a)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_init
```
```
In mm/memremap.c (ffffffff813e7c31)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/memremap.c:free_zone_device_page
```
```
In fs/dcache.c (ffffffff814131ec)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/file.c (ffffffff8141ae71)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd_get_file
  - fs/file.c:alloc_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
```
```
In fs/mbcache.c (ffffffff81481d4b)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_or_get
  - fs/mbcache.c:mb_cache_entry_delete_or_get
  - fs/mbcache.c:mb_cache_entry_delete_or_get
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_create
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/ext4/mballoc.c (ffffffff814f606f)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_clear_bits
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dev.c (ffffffff815743fb)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_put_request
```
```
In block/blk-cgroup.c (ffffffff816a307d)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In io_uring/io_uring.c (ffffffff816d4b18)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_sqe_files_update
  - io_uring/io_uring.c:__io_sqe_files_unregister
  - io_uring/io_uring.c:io_fixed_fd_install
```
```
In lib/bitmap.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In lib/idr.c (ffffffff8177860b)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - lib/idr.c:ida_free
```
```
In lib/radix-tree.c (ffffffff8177d3bc)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - lib/radix-tree.c:node_tag_clear
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/vsprintf.c (ffffffff81784abf)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
```
```
In lib/xarray.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff817a85fd)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff817aaeb3)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linehandle_ioctl
```
```
In drivers/pwm/core.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/acpi/numa/hmat.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff818c8516)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_entries
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8192f7c7)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_set
```
```
In drivers/iommu/amd/iommu.c (ffffffff81951446)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff819feb8b)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
```
In drivers/net/phy/phy.c (ffffffff81a53874)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
```
In drivers/net/phy/phy-c45.c (ffffffff81a54312)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
```
```
In drivers/net/phy/phy-core.c (ffffffff81a56a04)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_set_max_speed
```
```
In drivers/net/phy/phy_device.c (ffffffff81a5a43d)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_remove_link_mode
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
```
```
In drivers/net/phy/linkmode.c (ffffffff81a5aa49)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/bcm84881.c (ffffffff81a5e80a)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_get_features
  - drivers/net/phy/bcm84881.c:bcm84881_get_features
```
```
In drivers/net/tun.c (ffffffff81a601f8)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp
  - drivers/net/tun.c:tun_xdp
```
```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/input/input.c (ffffffff81b15bfd)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_keycode
  - drivers/input/input.c:input_default_setkeycode
```
```
In drivers/input/ff-core.c (ffffffff81b19fa3)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_destroy
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81b1fdaa)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In net/socket.c (ffffffff81be5799)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81befb80)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_timestamping
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/dev.c (ffffffff81c17eda)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/core/filter.c (ffffffff81c4ac8c)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_setsockopt
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/gro.c (ffffffff81c543a3)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:napi_gro_flush
```
```
In net/netlink/af_netlink.c (ffffffff81caf8cb)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_clear_multicast_users
```
```
In net/ethtool/bitset.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce42ce)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff81ceea1d)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81cff929)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/unix/garbage.c (ffffffff81d83483)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (ffffffff81d84e33)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_net_init
```
```
In net/packet/af_packet.c (ffffffff81df64bc)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/mptcp/protocol.c (ffffffff81e23855)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sk_clone
```
```
In net/mptcp/pm_netlink.c (ffffffff81e31de0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
```
```
In net/mptcp/sockopt.c (ffffffff81e3337e)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
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
In arch/x86/events/core.c (ffffffff8100a5c4)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:x86_pmu_stop
```
```
In arch/x86/events/intel/core.c (ffffffff8101375e)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_excl_constraints
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
```
In arch/x86/kernel/ioport.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8107675b)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__mce_disable_bank
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8107997a)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108e52d)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810a977e)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810a9ee1)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
```
```
In arch/x86/kernel/kvm.c (ffffffff810b6af9)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_multi
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff820c53a8)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/workqueue.c (ffffffff811128ed)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/workqueue.c:pwq_activate_inactive_work
```
```
In kernel/sched/fair.c (ffffffff811546d7)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/build_policy.c (ffffffff81158f2e)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dequeue_rt_stack
  - kernel/sched/build_policy.c:init_rt_rq
```
```
In kernel/sched/build_utility.c (ffffffff83ea8fdf)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:update_sched_domain_debugfs
```
```
In kernel/irq/irqdesc.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In kernel/time/timer.c (ffffffff811d6e96)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/smp.c (ffffffff811f9235)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/cgroup/cpuset.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In kernel/seccomp.c (ffffffff8124972d)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff8132030f)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In mm/filemap.c (ffffffff8135adcb)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/filemap.c:filemap_add_folio
```
```
In mm/swap.c (ffffffff8136f7f2)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8137c886)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:move_folios_to_lru
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In mm/page_alloc.c (ffffffff813f03aa)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:split_free_page
  - mm/page_alloc.c:__free_one_page
```
```
In mm/hugetlb.c (ffffffff8140c944)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_add_to_page_cache
  - mm/hugetlb.c:__prep_compound_gigantic_folio
  - mm/hugetlb.c:__prep_compound_gigantic_folio
  - mm/hugetlb.c:__prep_compound_gigantic_folio
  - mm/hugetlb.c:__prep_compound_gigantic_folio
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:__destroy_compound_gigantic_folio
```
```
In mm/slub.c (ffffffff81429fa8)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
```
```
In mm/kfence/core.c (ffffffff83ec6403)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_init
```
```
In mm/memory-tiers.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In mm/memremap.c (ffffffff8146fa6e)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/memremap.c:free_zone_device_page
```
```
In fs/dcache.c (ffffffff8149e498)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_unhash
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/file.c (ffffffff814a7035)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:pick_file
  - fs/file.c:pick_file
  - fs/file.c:put_unused_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:alloc_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
```
```
In fs/mbcache.c (ffffffff81514fa4)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:__mb_cache_entry_free
  - fs/mbcache.c:mb_cache_entry_create
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/ext4/mballoc.c (ffffffff815903eb)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_clear_bits
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dev.c (ffffffff81619c67)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_put_request
```
```
In block/blk-cgroup.c (ffffffff81760abc)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In io_uring/filetable.c (ffffffff817943bc)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - io_uring/filetable.c:io_fixed_fd_remove
  - io_uring/filetable.c:io_install_fixed_file
```
```
In io_uring/rsrc.c (ffffffff817a12e1)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - io_uring/rsrc.c:__io_sqe_files_unregister
  - io_uring/rsrc.c:__io_sqe_files_update
```
```
In lib/bitmap.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In lib/find_bit.c (ffffffff817d6e3a)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - lib/find_bit.c:__find_nth_andnot_bit
  - lib/find_bit.c:__find_nth_and_bit
  - lib/find_bit.c:__find_nth_bit
```
```
In drivers/gpio/gpiolib.c (ffffffff818c11af)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c3c85)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linehandle_ioctl_unlocked
```
```
In drivers/pwm/core.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/acpi/numa/hmat.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81a18f16)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_entries
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81a8db87)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_set
```
```
In drivers/iommu/amd/iommu.c (ffffffff81ab1ba3)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:domain_id_free
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b7d1bb)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
```
In drivers/net/phy/phy.c (ffffffff81bdd254)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
```
In drivers/net/phy/phy-c45.c (ffffffff81bdeaa2)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
```
```
In drivers/net/phy/phy-core.c (ffffffff81bdf316)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:__set_linkmode_max_speed
```
```
In drivers/net/phy/phy_device.c (ffffffff81be37cd)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:phy_remove_link_mode
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
```
```
In drivers/net/phy/linkmode.c (ffffffff81be52d9)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/bcm84881.c (ffffffff81be95aa)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
```
```
In drivers/net/tun.c (ffffffff81bec198)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp
  - drivers/net/tun.c:tun_xdp
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/input/input.c (ffffffff81ca7493)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_keycode
  - drivers/input/input.c:input_default_setkeycode
```
```
In drivers/input/ff-core.c (ffffffff81cabc23)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_destroy
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81cb1fc2)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In net/socket.c (ffffffff81d92e59)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81d9c9cd)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_set_timestamping
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/dev.c (ffffffff81dc8e02)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/core/filter.c (ffffffff81dffbad)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/gro.c (ffffffff81e09a67)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:napi_gro_flush
```
```
In net/netlink/af_netlink.c (ffffffff81e669fe)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
```
```
In net/ethtool/bitset.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea6e49)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff81eb1c85)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81ec49c9)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/unix/garbage.c (ffffffff81f50d86)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (ffffffff81f529cf)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_net_init
```
```
In net/packet/af_packet.c (ffffffff81fcaa3f)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/mptcp/protocol.c (ffffffff81ffafc3)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sk_clone
```
```
In net/mptcp/pm_netlink.c (ffffffff8200a440)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
```
```
In net/mptcp/sockopt.c (ffffffff8200cab7)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
```
```
In lib/cpumask.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In lib/idr.c (ffffffff82021391)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - lib/idr.c:ida_free
```
```
In lib/radix-tree.c (ffffffff82039b99)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/vsprintf.c (ffffffff82041a88)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
```
```
In lib/xarray.c (0)
Location: arch/x86/include/asm/bitops.h:92
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
In arch/x86/events/core.c (ffffffff81009e14)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:x86_pmu_stop
```
```
In arch/x86/events/intel/core.c (ffffffff81012d0e)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_excl_constraints
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
```
In arch/x86/kernel/ioport.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810789db)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__mce_disable_bank
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8107bc2a)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810913dd)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810ac99e)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810ad2a1)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
```
```
In arch/x86/kernel/kvm.c (ffffffff810b9c52)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_multi
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff82149408)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/workqueue.c (ffffffff8111eeed)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/workqueue.c:pwq_activate_inactive_work
```
```
In kernel/sched/fair.c (ffffffff81164833)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/build_policy.c (ffffffff8116921a)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dequeue_rt_stack
  - kernel/sched/build_policy.c:init_rt_rq
```
```
In kernel/sched/build_utility.c (ffffffff836cda9f)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
```
```
In kernel/time/timer.c (ffffffff811eb326)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/smp.c (ffffffff8120df2d)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/cgroup/cpuset.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In kernel/seccomp.c (ffffffff81260b12)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff813501c1)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In mm/filemap.c (ffffffff8138c7eb)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/filemap.c:filemap_add_folio
```
```
In mm/swap.c (ffffffff813a1912)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff813acbc9)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:move_folios_to_lru
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In mm/page_alloc.c (ffffffff81423f30)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:split_free_page
  - mm/page_alloc.c:__free_one_page
```
```
In mm/hugetlb.c (ffffffff8143fd65)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_add_to_page_cache
  - mm/hugetlb.c:demote_free_hugetlb_folio
  - mm/hugetlb.c:__prep_compound_gigantic_folio
  - mm/hugetlb.c:__prep_compound_gigantic_folio
  - mm/hugetlb.c:__prep_compound_gigantic_folio
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:__update_and_free_hugetlb_folio
```
```
In mm/slub.c (ffffffff8145f449)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
```
```
In mm/kfence/core.c (ffffffff81464782)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_init_pool
```
```
In mm/memory-tiers.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In mm/memremap.c (ffffffff814a424e)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/memremap.c:free_zone_device_page
```
```
In fs/dcache.c (ffffffff814d37b8)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_unhash
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/file.c (ffffffff814dc012)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:pick_file
  - fs/file.c:pick_file
  - fs/file.c:put_unused_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:alloc_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
```
```
In fs/mbcache.c (ffffffff8154c9a4)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:__mb_cache_entry_free
  - fs/mbcache.c:mb_cache_entry_create
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/ext4/mballoc.c (ffffffff815c75a7)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_clear_bits
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dev.c (ffffffff81651e17)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_put_request
```
```
In block/blk-cgroup.c (ffffffff8179f8f6)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_deactivate_policy
```
```
In io_uring/filetable.c (ffffffff817d5087)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - io_uring/filetable.c:io_fixed_fd_remove
  - io_uring/filetable.c:io_install_fixed_file
```
```
In io_uring/rsrc.c (ffffffff817e24d3)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - io_uring/rsrc.c:__io_sqe_files_unregister
  - io_uring/rsrc.c:__io_sqe_files_update
```
```
In lib/bitmap.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In lib/find_bit.c (ffffffff81815e5b)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - lib/find_bit.c:__find_nth_and_andnot_bit
  - lib/find_bit.c:__find_nth_andnot_bit
  - lib/find_bit.c:__find_nth_and_bit
  - lib/find_bit.c:__find_nth_bit
```
```
In drivers/gpio/gpiolib.c (ffffffff81904153)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff81906d87)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linehandle_ioctl_unlocked
```
```
In drivers/pwm/core.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/acpi/numa/hmat.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81a61f96)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_entries
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81ad9337)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_set
```
```
In drivers/iommu/amd/iommu.c (ffffffff81afdc13)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:domain_id_free
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd0f3b)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
```
In drivers/net/phy/phy.c (ffffffff81c3335e)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
```
In drivers/net/phy/phy-c45.c (ffffffff81c362ff)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_eee_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_eee_adv
```
```
In drivers/net/phy/phy-core.c (ffffffff81c36c06)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:__set_linkmode_max_speed
```
```
In drivers/net/phy/phy_device.c (ffffffff81c3b6ed)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:phy_remove_link_mode
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
```
```
In drivers/net/phy/linkmode.c (ffffffff81c3cd69)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/bcm84881.c (ffffffff81c419e1)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
```
```
In drivers/net/tun.c (ffffffff81c446b3)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp
  - drivers/net/tun.c:tun_xdp
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/input/input.c (ffffffff81d0e663)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_keycode
  - drivers/input/input.c:input_default_setkeycode
```
```
In drivers/input/ff-core.c (ffffffff81d13203)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_destroy
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81d1958c)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
```
```
In drivers/firmware/efi/unaccepted_memory.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/hid/bpf/hid_bpf_jmp_table.c (ffffffff81dd725f)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/hid/bpf/hid_bpf_jmp_table.c:__hid_bpf_destroy_device
  - drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_link_release
```
```
In net/socket.c (ffffffff81e01256)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81e0b229)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_set_timestamping
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/dev.c (ffffffff81e37370)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/core/filter.c (ffffffff81e715a9)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/gro.c (ffffffff81e7c070)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:napi_gro_flush
```
```
In net/netlink/af_netlink.c (ffffffff81ec27be)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
```
```
In net/ethtool/bitset.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f05623)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff81f10333)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81f23332)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/unix/garbage.c (ffffffff81fb06e7)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (ffffffff81fb23d1)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_net_init
```
```
In net/packet/af_packet.c (ffffffff8202b780)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/mptcp/protocol.c (ffffffff8207724f)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sk_clone_init
```
```
In net/mptcp/pm_netlink.c (ffffffff820864b0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
```
```
In net/mptcp/sockopt.c (ffffffff8208940c)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
```
```
In lib/cpumask.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In lib/idr.c (ffffffff820a13c1)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - lib/idr.c:ida_free
```
```
In lib/radix-tree.c (ffffffff820b7eb5)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/vsprintf.c (ffffffff820bffd8)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
```
```
In lib/xarray.c (0)
Location: arch/x86/include/asm/bitops.h:92
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
In arch/x86/events/core.c (ffffffff8100f534)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:x86_pmu_stop
```
```
In arch/x86/events/intel/core.c (ffffffff8101898e)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_excl_constraints
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
```
In arch/x86/kernel/ioport.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8107ff8b)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__mce_disable_bank
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff810831c7)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_claim_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_skip_bank
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81086af3)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:mce_track_storm
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810987ba)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810b361e)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810b3e21)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
```
```
In arch/x86/kernel/kvm.c (ffffffff810c0ea2)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_multi
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff8222bec8)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/workqueue.c (ffffffff8112849d)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/workqueue.c:pwq_activate_inactive_work
```
```
In kernel/sched/fair.c (ffffffff81171585)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/build_policy.c (ffffffff81177313)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dequeue_rt_stack
  - kernel/sched/build_policy.c:init_rt_rq
```
```
In kernel/sched/build_utility.c (ffffffff838feedd)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
```
```
In kernel/time/timer.c (ffffffff81201356)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/smp.c (ffffffff812256bd)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/cgroup/cpuset.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In kernel/seccomp.c (ffffffff8127ace2)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In kernel/trace/trace_events_filter.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff8137672b)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In mm/filemap.c (ffffffff813b634c)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/filemap.c:filemap_add_folio
```
```
In mm/swap.c (ffffffff813cb598)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff813d6074)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:move_folios_to_lru
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In mm/page_alloc.c (ffffffff81450ddd)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:split_free_page
  - mm/page_alloc.c:__free_one_page
```
```
In mm/slub.c (ffffffff81459707)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
```
```
In mm/hugetlb.c (ffffffff81479c2a)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_add_to_page_cache
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/hugetlb.c:__prep_compound_gigantic_folio
  - mm/hugetlb.c:__prep_compound_gigantic_folio
  - mm/hugetlb.c:__prep_compound_gigantic_folio
  - mm/hugetlb.c:free_huge_folio
  - mm/hugetlb.c:__destroy_compound_gigantic_folio
```
```
In mm/kfence/core.c (ffffffff81493f32)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In mm/memory-tiers.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In mm/memremap.c (ffffffff814d509e)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/memremap.c:free_zone_device_page
```
```
In fs/dcache.c (ffffffff81505f38)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_unhash
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:___d_drop
```
```
In fs/file.c (ffffffff8150e232)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:file_close_fd_locked
  - fs/file.c:file_close_fd_locked
  - fs/file.c:put_unused_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:alloc_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
```
```
In fs/mbcache.c (ffffffff815827d4)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:__mb_cache_entry_free
  - fs/mbcache.c:mb_cache_entry_create
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/buffered-io.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff815fdd97)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_clear_bits
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dev.c (ffffffff8168b427)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_put_request
```
```
In block/blk-cgroup.c (ffffffff817e33c3)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_deactivate_policy
```
```
In io_uring/filetable.c (ffffffff81818ed7)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - io_uring/filetable.c:io_fixed_fd_remove
  - io_uring/filetable.c:io_install_fixed_file
```
```
In io_uring/rsrc.c (ffffffff81826dfd)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - io_uring/rsrc.c:__io_sqe_files_unregister
  - io_uring/rsrc.c:__io_sqe_files_update
```
```
In lib/bitmap.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In lib/find_bit.c (ffffffff8185af9b)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - lib/find_bit.c:__find_nth_and_andnot_bit
  - lib/find_bit.c:__find_nth_andnot_bit
  - lib/find_bit.c:__find_nth_and_bit
  - lib/find_bit.c:__find_nth_bit
```
```
In lib/bitmap-str.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff8194bb85)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8194e5c0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linehandle_ioctl
```
```
In drivers/pci/endpoint/pci-epc-mem.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/acpi/numa/hmat.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81ab47c6)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_entries
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81b2c627)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_set
```
```
In drivers/iommu/amd/iommu.c (ffffffff81b514cb)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:protection_domain_free
```
```
In drivers/iommu/intel/irq_remapping.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c25bab)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
```
In drivers/gpu/drm/drm_mm.c (ffffffff81ca0e55)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mm.c:drm_mm_scan_remove_block
```
```
In drivers/net/phy/phy.c (ffffffff81ce804e)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
```
In drivers/net/phy/phy-c45.c (ffffffff81ceb27f)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_ext_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_ext_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_ext_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_ext_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_ext_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_ext_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_ext_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_ext_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_ext_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_ext_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_ext_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_ext_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_baset1_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_baset1_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_baset1_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_baset1_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_eee_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_eee_adv
```
```
In drivers/net/phy/phy-core.c (ffffffff81cebb86)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:__set_linkmode_max_speed
```
```
In drivers/net/phy/phy_device.c (ffffffff81cf0aed)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:phy_remove_link_mode
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
```
```
In drivers/net/phy/linkmode.c (ffffffff81cf2169)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/bcm84881.c (ffffffff81cf7071)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
```
```
In drivers/net/tun.c (ffffffff81cf9fa3)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp
  - drivers/net/tun.c:tun_xdp
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/input/input.c (ffffffff81dc42b3)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_keycode
  - drivers/input/input.c:input_default_setkeycode
```
```
In drivers/input/ff-core.c (ffffffff81dc8e33)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_destroy
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81dcf2ac)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
```
```
In drivers/ptp/ptp_chardev.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/firmware/efi/unaccepted_memory.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/hid/bpf/hid_bpf_jmp_table.c (ffffffff81e8f4ff)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/hid/bpf/hid_bpf_jmp_table.c:__hid_bpf_destroy_device
  - drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_link_release
```
```
In net/socket.c (ffffffff81ebd956)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81ec7c19)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_set_timestamping
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/dev.c (ffffffff81ef5390)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/core/filter.c (ffffffff81f30ca1)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/gro.c (ffffffff81f3c3c0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:napi_gro_flush
```
```
In net/netlink/af_netlink.c (ffffffff81f85b0e)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
```
```
In net/ethtool/bitset.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fc9989)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff81fd4521)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81fe77bd)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/unix/garbage.c (ffffffff8207dd7e)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (ffffffff8207fb61)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_net_init
```
```
In net/packet/af_packet.c (ffffffff820fb246)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/mptcp/protocol.c (ffffffff8214c0e2)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sk_clone_init
```
```
In net/mptcp/pm_netlink.c (ffffffff8215b3f3)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_del_addr_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
```
```
In net/mptcp/sockopt.c (ffffffff8215f013)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
```
```
In lib/idr.c (ffffffff8217932c)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - lib/idr.c:ida_free
```
```
In lib/radix-tree.c (ffffffff821927c5)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/vsprintf.c (ffffffff8219a093)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
```
```
In lib/xarray.c (0)
Location: arch/x86/include/asm/bitops.h:92
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810066b8)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_stop
```
```
In arch/x86/events/intel/core.c (ffffffff8100d4ae)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/kernel/ioport.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104cc6e)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__mce_disable_bank
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104fefc)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81060e5c)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d138)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106d5f1)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
```
```
In arch/x86/kernel/kvm.c (ffffffff81076438)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81a6a393)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/workqueue.c (ffffffff810ba3af)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/fair.c (ffffffff810e5369)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/rt.c (ffffffff810e7c96)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/sched/debug.c (ffffffff810f5cbb)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/isolation.c (ffffffff828b69b2)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In kernel/time/timer.c (ffffffff8112c8c8)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/smp.c (ffffffff8114741f)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In mm/filemap.c (ffffffff8121be87)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff8122a1db)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff81232f69)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In mm/page_alloc.c (ffffffff828c711d)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/swap_state.c (ffffffff8127f786)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff8128c9e5)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/slub.c (ffffffff812a067e)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff812a99f8)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_page
```
```
In mm/cma.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In mm/memremap.c (ffffffff812cc920)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In fs/dcache.c (ffffffff812f0760)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/file.c (ffffffff812f7fe5)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
```
```
In fs/mbcache.c (ffffffff81357c9f)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/ext4/mballoc.c (ffffffff813b4699)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_clear_bits
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dev.c (ffffffff8141a77c)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
```
```
In block/blk-cgroup.c (ffffffff815026e0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff815647e1)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/pwm/core.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/acpi/hmat/hmat.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8167dc5e)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff816a76d3)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:domain_id_free
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/net/phy/phy.c (ffffffff8177d5e5)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (ffffffff8177e4c5)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy-core.c (ffffffff8177f8c9)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_set_max_speed
```
```
In drivers/net/phy/phy_device.c (ffffffff81781c15)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_remove_link_mode
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
```
```
In drivers/net/tun.c (ffffffff81785bcc)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/input/input.c (ffffffff8180d7dd)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_keycode
  - drivers/input/input.c:input_default_setkeycode
```
```
In drivers/input/ff-core.c (ffffffff8180fc13)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_destroy
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81814b7c)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In net/socket.c (ffffffff818ab849)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff818b4af0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/dev.c (ffffffff818d60b7)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
```
```
In net/netlink/af_netlink.c (ffffffff8193d445)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195aa0f)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff8196314d)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff8196439e)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffffffff8196ff2a)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/unix/garbage.c (ffffffff819d3e55)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (ffffffff819d504a)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a30279)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In lib/idr.c (ffffffff81a4e34c)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - lib/idr.c:ida_free
```
```
In lib/radix-tree.c (ffffffff81a52d82)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
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
In arch/x86/events/core.c (ffffffff81004dd8)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_stop
```
```
In arch/x86/events/intel/core.c (ffffffff8100bcae)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/kernel/ioport.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103c0ee)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__mce_disable_bank
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8103f9e1)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810512bc)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105d52b)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105da21)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
```
```
In arch/x86/kernel/kvm.c (ffffffff810663a8)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81a26855)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/workqueue.c (ffffffff810a8cef)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/fair.c (ffffffff810d4512)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/rt.c (ffffffff810d712f)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:alloc_rt_sched_group
```
```
In kernel/sched/debug.c (ffffffff810e5e7b)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/isolation.c (ffffffff828aeba8)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In kernel/time/timer.c (ffffffff8111f138)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/smp.c (ffffffff8113a6fa)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In mm/filemap.c (ffffffff8120f077)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff8121d2fb)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff81226009)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In mm/page_alloc.c (ffffffff828bf842)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/swap_state.c (ffffffff812715a6)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff8127e805)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/slub.c (ffffffff8129218e)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff8129b358)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_page
```
```
In mm/cma.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In mm/memremap.c (ffffffff812bd790)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In fs/dcache.c (ffffffff812e1390)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/file.c (ffffffff812e8c05)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
```
```
In fs/mbcache.c (ffffffff8134894f)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/ext4/mballoc.c (ffffffff813a5129)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_clear_bits
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dev.c (ffffffff8140b1fc)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
```
```
In block/blk-cgroup.c (ffffffff814f2a10)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff81555631)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/acpi/hmat/hmat.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8165cd4e)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff816850c3)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:domain_id_free
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/net/phy/phy.c (ffffffff8175d3a5)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (ffffffff8175e265)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy-core.c (ffffffff8175f669)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_set_max_speed
```
```
In drivers/net/phy/phy_device.c (ffffffff817619a5)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_remove_link_mode
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
```
```
In drivers/net/tun.c (ffffffff8176551c)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/input/input.c (ffffffff817d4f4d)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_keycode
  - drivers/input/input.c:input_default_setkeycode
```
```
In drivers/input/ff-core.c (ffffffff817d7363)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_destroy
```
```
In drivers/input/keyboard/atkbd.c (ffffffff817dc2ac)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In net/socket.c (ffffffff81865799)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff8186ea40)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/dev.c (ffffffff8188fef7)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
```
```
In net/netlink/af_netlink.c (ffffffff818f6f45)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819144ff)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff8191cc3d)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff8191de8e)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffffffff819299fa)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/unix/garbage.c (ffffffff81990c15)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (ffffffff81991e0a)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819ed469)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In lib/idr.c (ffffffff81a0b43c)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - lib/idr.c:ida_free
```
```
In lib/radix-tree.c (ffffffff81a0fe82)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
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
In arch/x86/events/core.c (ffffffff81006678)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_stop
```
```
In arch/x86/events/intel/core.c (ffffffff8100d46e)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/kernel/ioport.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104caae)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__mce_disable_bank
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104fdac)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106128c)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d5e8)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106daa1)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
```
```
In arch/x86/kernel/kvm.c (ffffffff810763e8)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81ad67a3)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/workqueue.c (ffffffff810b990f)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/fair.c (ffffffff810e1739)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/rt.c (ffffffff810e430f)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:alloc_rt_sched_group
```
```
In kernel/sched/debug.c (ffffffff810f2ebb)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/isolation.c (ffffffff828c9856)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In kernel/time/timer.c (ffffffff8112a5e8)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/smp.c (ffffffff811452cf)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In mm/filemap.c (ffffffff81219c27)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff81227f7b)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff81230d09)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In mm/page_alloc.c (ffffffff828d9e9d)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/swap_state.c (ffffffff8127d526)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff8128a7f5)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/slub.c (ffffffff8129e48e)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff812a7808)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_page
```
```
In mm/cma.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In mm/memremap.c (ffffffff812ca730)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In fs/dcache.c (ffffffff812ee570)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/file.c (ffffffff812f5df5)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
```
```
In fs/mbcache.c (ffffffff8135576f)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/ext4/mballoc.c (ffffffff813b1ef9)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_clear_bits
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dev.c (ffffffff8141691c)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
```
```
In block/blk-cgroup.c (ffffffff814fe770)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff81563351)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/pwm/core.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff816ac03e)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff816d5943)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:domain_id_free
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/net/phy/phy.c (ffffffff817ad995)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (ffffffff817ae875)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy-core.c (ffffffff817afc79)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_set_max_speed
```
```
In drivers/net/phy/phy_device.c (ffffffff817b1fc5)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_remove_link_mode
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
```
```
In drivers/net/tun.c (ffffffff817b5f7c)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/input/input.c (ffffffff8184c95d)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_keycode
  - drivers/input/input.c:input_default_setkeycode
```
```
In drivers/input/ff-core.c (ffffffff8184ed93)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_destroy
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81853cfc)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In net/socket.c (ffffffff818fc849)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81905af0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/dev.c (ffffffff819270e7)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
```
```
In net/netlink/af_netlink.c (ffffffff8198e5d5)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c51df)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff819cd91d)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff819ceb6e)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffffffff819da6fa)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/unix/garbage.c (ffffffff81a3e8d5)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (ffffffff81a3faca)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a9be29)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In lib/idr.c (ffffffff81aba73c)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - lib/idr.c:ida_free
```
```
In lib/radix-tree.c (ffffffff81abf172)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
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
In arch/x86/events/core.c (ffffffff810067d8)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_stop
```
```
In arch/x86/events/intel/core.c (ffffffff8100d69e)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/kernel/ioport.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104debe)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__mce_disable_bank
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff810511ec)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81062847)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106f868)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106fd21)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
```
```
In arch/x86/kernel/kvm.c (ffffffff81078438)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81ae2c63)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/workqueue.c (ffffffff810c2a2f)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/fair.c (ffffffff810ed3a4)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/rt.c (ffffffff810f04a6)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/sched/debug.c (ffffffff810fdebb)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/isolation.c (ffffffff828cec08)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In kernel/time/timer.c (ffffffff81137bc8)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/smp.c (ffffffff81151eaf)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In mm/filemap.c (ffffffff81228d27)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff812372bb)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff81240159)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In mm/page_alloc.c (ffffffff828df2be)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/swap_state.c (ffffffff8128d0e5)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff8129a5e3)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/slub.c (ffffffff812ae24b)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/slub.c:validate_slab_slab
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff812b7b09)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_page
```
```
In mm/cma.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In mm/memremap.c (ffffffff812db430)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In fs/dcache.c (ffffffff81300537)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/file.c (ffffffff81306f19)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
```
```
In fs/mbcache.c (ffffffff81368d70)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/ext4/mballoc.c (ffffffff813c6a39)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_clear_bits
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dev.c (ffffffff8142d67c)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
```
```
In block/blk-cgroup.c (ffffffff81516ba0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff8157d271)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/pwm/core.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/acpi/hmat/hmat.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff816c649e)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff816ec503)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:domain_id_free
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/net/phy/phy.c (ffffffff817c7925)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (ffffffff817c8805)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy-core.c (ffffffff817c9c09)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_set_max_speed
```
```
In drivers/net/phy/phy_device.c (ffffffff817cbf55)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_remove_link_mode
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
```
```
In drivers/net/tun.c (ffffffff817d03ec)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In drivers/input/input.c (ffffffff81867c4d)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_keycode
  - drivers/input/input.c:input_default_setkeycode
```
```
In drivers/input/ff-core.c (ffffffff8186a143)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_destroy
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8186f0cc)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In net/socket.c (ffffffff8191d849)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81926b12)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/dev.c (ffffffff81948756)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
```
```
In net/netlink/af_netlink.c (ffffffff819b0e85)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819cecaf)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff819d74ad)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff819d86fe)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffffffff819e437c)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/unix/garbage.c (ffffffff81a4a247)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (ffffffff81a4b60a)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81aa65e8)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In lib/idr.c (ffffffff81ac6b8c)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - lib/idr.c:ida_free
```
```
In lib/radix-tree.c (ffffffff81acb642)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (0)
Location: arch/x86/include/asm/bitops.h:92
Inline: True
```
</details>
</li>
</ul>

## Differences
