# Function: <code>___clear_bit</code>

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
In arch/x86/events/core.c (ffffffff8100a5c4)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:x86_pmu_stop
```
```
In arch/x86/events/intel/core.c (ffffffff8101375e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8107675b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__mce_disable_bank
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8107997a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108e52d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810a977e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810a9ee1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
```
```
In arch/x86/kernel/kvm.c (ffffffff810b6af9)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_multi
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff820c53a8)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/workqueue.c (ffffffff811128ed)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - kernel/workqueue.c:pwq_activate_inactive_work
```
```
In kernel/sched/fair.c (ffffffff811546d7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/build_policy.c (ffffffff81158f2e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dequeue_rt_stack
  - kernel/sched/build_policy.c:init_rt_rq
```
```
In kernel/sched/build_utility.c (ffffffff83ea8fdf)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:update_sched_domain_debugfs
```
```
In kernel/irq/irqdesc.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In kernel/time/timer.c (ffffffff811d6e96)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/smp.c (ffffffff811f9235)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In kernel/seccomp.c (ffffffff8124972d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff8132030f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In mm/filemap.c (ffffffff8135adcb)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - mm/filemap.c:filemap_add_folio
```
```
In mm/swap.c (ffffffff8136f7f2)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:move_folios_to_lru
```
```
In mm/percpu.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In mm/page_alloc.c (ffffffff813f03aa)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
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
In mm/slub.c (ffffffff814256d4)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
```
```
In mm/kfence/core.c (ffffffff83ec6403)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_init
```
```
In mm/memory-tiers.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In mm/memremap.c (ffffffff8146fa6e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - mm/memremap.c:free_zone_device_page
```
```
In fs/file.c (ffffffff814a7035)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
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
In fs/ext4/mballoc.c (ffffffff815903eb)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_put_request
```
```
In block/blk-cgroup.c (ffffffff81760abc)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In io_uring/filetable.c (ffffffff817943bc)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - io_uring/filetable.c:io_fixed_fd_remove
  - io_uring/filetable.c:io_install_fixed_file
```
```
In io_uring/rsrc.c (ffffffff817a12e1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - io_uring/rsrc.c:__io_sqe_files_unregister
  - io_uring/rsrc.c:__io_sqe_files_update
```
```
In lib/bitmap.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In lib/find_bit.c (ffffffff817d6e3a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - lib/find_bit.c:__find_nth_andnot_bit
  - lib/find_bit.c:__find_nth_and_bit
  - lib/find_bit.c:__find_nth_bit
```
```
In drivers/gpio/gpiolib.c (ffffffff818c11af)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linehandle_ioctl_unlocked
```
```
In drivers/pwm/core.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In drivers/acpi/numa/hmat.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81a18f16)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_entries
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81a8db87)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_set
```
```
In drivers/iommu/amd/iommu.c (ffffffff81ab1ba3)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:domain_id_free
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b7d1bb)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
```
In drivers/net/phy/phy.c (ffffffff81bdd254)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:__set_linkmode_max_speed
```
```
In drivers/net/phy/phy_device.c (ffffffff81be37cd)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/bcm84881.c (ffffffff81be95aa)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
```
```
In drivers/net/tun.c (ffffffff81bec198)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp
  - drivers/net/tun.c:tun_xdp
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In drivers/input/input.c (ffffffff81ca7493)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_keycode
  - drivers/input/input.c:input_default_setkeycode
```
```
In drivers/input/ff-core.c (ffffffff81cabc23)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_destroy
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81cb1fc2)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In net/socket.c (ffffffff81d92e59)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81d9c9cd)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/gro.c (ffffffff81e09a67)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:napi_gro_flush
```
```
In net/netlink/af_netlink.c (ffffffff81e669fe)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
```
```
In net/ethtool/bitset.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea6e49)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff81eb1c85)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81ec49c9)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/unix/garbage.c (ffffffff81f50d86)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (ffffffff81f529cf)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_net_init
```
```
In net/packet/af_packet.c (ffffffff81fcaa3f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/mptcp/protocol.c (ffffffff81ffafc3)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sk_clone
```
```
In net/mptcp/pm_netlink.c (ffffffff8200a440)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
```
```
In net/mptcp/sockopt.c (ffffffff8200cab7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In lib/idr.c (ffffffff82021391)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - lib/idr.c:ida_free
```
```
In lib/radix-tree.c (ffffffff82039b99)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/vsprintf.c (ffffffff82041a88)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
```
```
In lib/xarray.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:x86_pmu_stop
```
```
In arch/x86/events/intel/core.c (ffffffff81012d0e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810789db)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__mce_disable_bank
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8107bc2a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810913dd)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810ac99e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810ad2a1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
```
```
In arch/x86/kernel/kvm.c (ffffffff810b9c52)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_multi
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff82149408)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/workqueue.c (ffffffff8111eeed)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - kernel/workqueue.c:pwq_activate_inactive_work
```
```
In kernel/sched/fair.c (ffffffff81164833)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/build_policy.c (ffffffff8116921a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dequeue_rt_stack
  - kernel/sched/build_policy.c:init_rt_rq
```
```
In kernel/sched/build_utility.c (ffffffff836cda9f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
```
```
In kernel/time/timer.c (ffffffff811eb326)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/smp.c (ffffffff8120df2d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In kernel/seccomp.c (ffffffff81260b12)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff813501c1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In mm/filemap.c (ffffffff8138c7eb)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - mm/filemap.c:filemap_add_folio
```
```
In mm/swap.c (ffffffff813a1912)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:move_folios_to_lru
```
```
In mm/percpu.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In mm/page_alloc.c (ffffffff81423f30)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
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
In mm/slub.c (ffffffff8145a96e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
```
```
In mm/kfence/core.c (ffffffff81464782)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_init_pool
```
```
In mm/memory-tiers.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In mm/memremap.c (ffffffff814a424e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - mm/memremap.c:free_zone_device_page
```
```
In fs/file.c (ffffffff814dc012)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
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
In fs/ext4/mballoc.c (ffffffff815c75a7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_put_request
```
```
In block/blk-cgroup.c (ffffffff8179f8f6)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_deactivate_policy
```
```
In io_uring/filetable.c (ffffffff817d5087)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - io_uring/filetable.c:io_fixed_fd_remove
  - io_uring/filetable.c:io_install_fixed_file
```
```
In io_uring/rsrc.c (ffffffff817e24d3)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - io_uring/rsrc.c:__io_sqe_files_unregister
  - io_uring/rsrc.c:__io_sqe_files_update
```
```
In lib/bitmap.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In lib/find_bit.c (ffffffff81815e5b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - lib/find_bit.c:__find_nth_and_andnot_bit
  - lib/find_bit.c:__find_nth_andnot_bit
  - lib/find_bit.c:__find_nth_and_bit
  - lib/find_bit.c:__find_nth_bit
```
```
In drivers/gpio/gpiolib.c (ffffffff81904153)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linehandle_ioctl_unlocked
```
```
In drivers/pwm/core.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In drivers/acpi/numa/hmat.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81a61f96)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_entries
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81ad9337)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_set
```
```
In drivers/iommu/amd/iommu.c (ffffffff81afdc13)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:domain_id_free
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd0f3b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
```
In drivers/net/phy/phy.c (ffffffff81c3335e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:__set_linkmode_max_speed
```
```
In drivers/net/phy/phy_device.c (ffffffff81c3b6ed)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/bcm84881.c (ffffffff81c419e1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
```
```
In drivers/net/tun.c (ffffffff81c446b3)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp
  - drivers/net/tun.c:tun_xdp
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In drivers/input/input.c (ffffffff81d0e663)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_keycode
  - drivers/input/input.c:input_default_setkeycode
```
```
In drivers/input/ff-core.c (ffffffff81d13203)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_destroy
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81d1958c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
```
```
In drivers/firmware/efi/unaccepted_memory.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In drivers/hid/bpf/hid_bpf_jmp_table.c (ffffffff81dd725f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - drivers/hid/bpf/hid_bpf_jmp_table.c:__hid_bpf_destroy_device
  - drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_link_release
```
```
In net/socket.c (ffffffff81e01256)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81e0b229)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/gro.c (ffffffff81e7c070)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:napi_gro_flush
```
```
In net/netlink/af_netlink.c (ffffffff81ec27be)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
```
```
In net/ethtool/bitset.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f05623)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff81f10333)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81f23332)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/unix/garbage.c (ffffffff81fb06e7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (ffffffff81fb23d1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_net_init
```
```
In net/packet/af_packet.c (ffffffff8202b780)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/mptcp/protocol.c (ffffffff8207724f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sk_clone_init
```
```
In net/mptcp/pm_netlink.c (ffffffff820864b0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
```
```
In net/mptcp/sockopt.c (ffffffff8208940c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In lib/idr.c (ffffffff820a13c1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - lib/idr.c:ida_free
```
```
In lib/radix-tree.c (ffffffff820b7eb5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/vsprintf.c (ffffffff820bffd8)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
```
```
In lib/xarray.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:x86_pmu_stop
```
```
In arch/x86/events/intel/core.c (ffffffff8101898e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8107ff8b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__mce_disable_bank
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff810831c7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_claim_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_skip_bank
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81086af3)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:mce_track_storm
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810987ba)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810b361e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810b3e21)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
```
```
In arch/x86/kernel/kvm.c (ffffffff810c0ea2)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_multi
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff8222bec8)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/workqueue.c (ffffffff8112849d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - kernel/workqueue.c:pwq_activate_inactive_work
```
```
In kernel/sched/fair.c (ffffffff81171585)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/build_policy.c (ffffffff81177313)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dequeue_rt_stack
  - kernel/sched/build_policy.c:init_rt_rq
```
```
In kernel/sched/build_utility.c (ffffffff838feedd)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
```
```
In kernel/time/timer.c (ffffffff81201356)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/smp.c (ffffffff812256bd)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In kernel/seccomp.c (ffffffff8127ace2)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In kernel/trace/trace_events_filter.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff8137672b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In mm/filemap.c (ffffffff813b634c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - mm/filemap.c:filemap_add_folio
```
```
In mm/swap.c (ffffffff813cb598)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:move_folios_to_lru
```
```
In mm/percpu.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In mm/page_alloc.c (ffffffff81450ddd)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
```
```
In mm/hugetlb.c (ffffffff81479c2a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In mm/memory-tiers.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In mm/memremap.c (ffffffff814d509e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - mm/memremap.c:free_zone_device_page
```
```
In fs/file.c (ffffffff8150e232)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
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
In fs/iomap/buffered-io.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff815fdd97)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_put_request
```
```
In block/blk-cgroup.c (ffffffff817e33c3)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_deactivate_policy
```
```
In io_uring/filetable.c (ffffffff81818ed7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - io_uring/filetable.c:io_fixed_fd_remove
  - io_uring/filetable.c:io_install_fixed_file
```
```
In io_uring/rsrc.c (ffffffff81826dfd)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - io_uring/rsrc.c:__io_sqe_files_unregister
  - io_uring/rsrc.c:__io_sqe_files_update
```
```
In lib/bitmap.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In lib/find_bit.c (ffffffff8185af9b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - lib/find_bit.c:__find_nth_and_andnot_bit
  - lib/find_bit.c:__find_nth_andnot_bit
  - lib/find_bit.c:__find_nth_and_bit
  - lib/find_bit.c:__find_nth_bit
```
```
In lib/bitmap-str.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff8194bb85)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linehandle_ioctl
```
```
In drivers/pci/endpoint/pci-epc-mem.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In drivers/acpi/numa/hmat.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81ab47c6)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_entries
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81b2c627)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_set
```
```
In drivers/iommu/amd/iommu.c (ffffffff81b514cb)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:protection_domain_free
```
```
In drivers/iommu/intel/irq_remapping.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c25bab)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
```
In drivers/gpu/drm/drm_mm.c (ffffffff81ca0e55)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mm.c:drm_mm_scan_remove_block
```
```
In drivers/net/phy/phy.c (ffffffff81ce804e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:__set_linkmode_max_speed
```
```
In drivers/net/phy/phy_device.c (ffffffff81cf0aed)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/bcm84881.c (ffffffff81cf7071)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
```
```
In drivers/net/tun.c (ffffffff81cf9fa3)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp
  - drivers/net/tun.c:tun_xdp
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In drivers/input/input.c (ffffffff81dc42b3)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_keycode
  - drivers/input/input.c:input_default_setkeycode
```
```
In drivers/input/ff-core.c (ffffffff81dc8e33)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_destroy
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81dcf2ac)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
```
```
In drivers/ptp/ptp_chardev.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In drivers/firmware/efi/unaccepted_memory.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In drivers/hid/bpf/hid_bpf_jmp_table.c (ffffffff81e8f4ff)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - drivers/hid/bpf/hid_bpf_jmp_table.c:__hid_bpf_destroy_device
  - drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_link_release
```
```
In net/socket.c (ffffffff81ebd956)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81ec7c19)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/gro.c (ffffffff81f3c3c0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:napi_gro_flush
```
```
In net/netlink/af_netlink.c (ffffffff81f85b0e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
```
```
In net/ethtool/bitset.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fc9989)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff81fd4521)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81fe77bd)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/unix/garbage.c (ffffffff8207dd7e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (ffffffff8207fb61)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_net_init
```
```
In net/packet/af_packet.c (ffffffff820fb246)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/mptcp/protocol.c (ffffffff8214c0e2)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sk_clone_init
```
```
In net/mptcp/pm_netlink.c (ffffffff8215b3f3)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_del_addr_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
```
```
In net/mptcp/sockopt.c (ffffffff8215f013)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
```
```
In lib/idr.c (ffffffff8217932c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - lib/idr.c:ida_free
```
```
In lib/radix-tree.c (ffffffff821927c5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/vsprintf.c (ffffffff8219a093)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
```
```
In lib/xarray.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:42
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
