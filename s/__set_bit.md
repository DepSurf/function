# Function: <code>__set_bit</code>

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
In arch/x86/events/core.c (ffffffff8100684e)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_schedule_events
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_pmu_start
```
```
In arch/x86/events/amd/core.c (ffffffff810080d0)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015509)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_assign_events
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104577b)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81057ede)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
```
```
In kernel/workqueue.c (ffffffff8109aefd)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_work
  - kernel/workqueue.c:flush_work
```
```
In kernel/sched/rt.c (ffffffff810c07f9)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/events/uprobes.c (ffffffff8118766e)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff8118df4a)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
  - mm/filemap.c:pagecache_get_page
```
```
In mm/page_alloc.c (ffffffff8119295c)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/shmem.c (ffffffff811a8e03)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/memory.c (ffffffff811bc582)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
```
```
In mm/swap_state.c (ffffffff811d2b58)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff811daff7)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/ksm.c (ffffffff811e6ddc)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff811e97ac)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/slub.c:new_slab
```
```
In mm/migrate.c (ffffffff811f32c5)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff811f573d)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/userfaultfd.c (ffffffff81207989)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/file.c (ffffffff81229f81)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:set_close_on_exec
```
```
In fs/ext4/balloc.c (ffffffff8128feb7)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff81292ff7)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
```
```
In fs/ext4/super.c (ffffffff812bb7a8)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
```
```
In fs/ext4/mballoc.c (ffffffff812cebbd)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_set_bits
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
```
```
In fs/hugetlbfs/inode.c (ffffffff812f4d48)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff8130d7f6)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_init
  - fs/fuse/dev.c:fuse_request_send
  - fs/fuse/dev.c:fuse_request_send
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:fuse_request_send_background_locked
  - fs/fuse/dev.c:fuse_request_send_background_locked
```
```
In fs/fuse/file.c (ffffffff8131523e)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_sync_release
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepages_fill
```
```
In fs/fuse/inode.c (ffffffff8131b56c)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_put_super
  - fs/fuse/inode.c:fuse_fill_super
```
```
In block/blk-core.c (ffffffff813b55f9)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - block/blk-core.c:blk_stop_queue
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
```
```
In block/blk-tag.c (ffffffff813bc2eb)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_init_tags
  - block/blk-tag.c:blk_queue_init_tags
```
```
In block/blk-sysfs.c (ffffffff813bccee)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_store_nonrot
  - block/blk-sysfs.c:queue_store_random
  - block/blk-sysfs.c:queue_store_iostats
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:blk_register_queue
```
```
In block/scsi_ioctl.c (ffffffff81f9b6f9)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
```
```
In block/bsg-lib.c (ffffffff813d6c3c)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_setup_queue
```
```
In block/blk-cgroup.c (ffffffff813d8d9a)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
```
```
In lib/idr.c (ffffffff813e9f6d)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - lib/idr.c:idr_mark_full
  - lib/idr.c:idr_mark_full
  - lib/idr.c:ida_remove
  - lib/idr.c:idr_get_empty_slot
  - lib/idr.c:ida_get_new_above
```
```
In lib/radix-tree.c (ffffffff813ee21a)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_range_tag_if_tagged
  - lib/radix-tree.c:radix_tree_range_tag_if_tagged
  - lib/radix-tree.c:__radix_tree_create
```
```
In drivers/gpio/gpiolib.c (ffffffff8142666d)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_priv
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_priv
```
```
In drivers/pnp/quirks.c (ffffffff814bb215)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff81fa41e4)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff814d5f15)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
```
In drivers/tty/tty_buffer.c (ffffffff814eabe2)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/sysrq.c (ffffffff814ee1fe)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/iommu/amd_iommu.c (ffffffff8152e729)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:domain_id_alloc
  - drivers/iommu/amd_iommu.c:alloc_new_range
  - drivers/iommu/amd_iommu.c:alloc_new_range
  - drivers/iommu/amd_iommu.c:alloc_new_range
```
```
In drivers/base/dma-mapping.c (ffffffff8155daaa)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dmam_alloc_noncoherent
  - drivers/base/dma-mapping.c:dmam_noncoherent_release
```
```
In drivers/block/brd.c (ffffffff8156d190)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/block/brd.c:brd_alloc
```
```
In drivers/block/loop.c (ffffffff8156e4d4)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_add
```
```
In drivers/block/xen-blkfront.c (ffffffff8157386c)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
```
In drivers/scsi/sd.c (ffffffff815ba1bf)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/scsi/sr.c (ffffffff815c09b9)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/net/tun.c (ffffffff815ede5d)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In drivers/input/input.c (ffffffff81666af4)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_abs_params
  - drivers/input/input.c:input_set_abs_params
```
```
In drivers/input/input-mt.c (ffffffff8166ac73)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
```
```
In drivers/input/ff-core.c (ffffffff8166b243)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8166f6cc)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/md/dm-table.c (ffffffff816a6cc0)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
```
In net/socket.c (ffffffff816fb9e2)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81700709)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/core/sock.c:sk_set_memalloc
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_enable_timestamp
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
```
```
In net/netlink/af_netlink.c (ffffffff8174a338)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff81762dca)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817648c4)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff817658f7)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff8176b10d)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81775700)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177c967)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/udp.c (ffffffff81786101)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff8178df23)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_sk_init
```
```
In net/unix/af_unix.c (ffffffff817bfdaa)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/unix/garbage.c (ffffffff817c2592)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/addrconf.c (ffffffff817cb203)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
```
```
In net/ipv6/route.c (ffffffff817d4b1e)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81805a5b)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/rfkill/input.c (ffffffff818126cf)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
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
In arch/x86/events/core.c (ffffffff81006d06)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_schedule_events
```
```
In arch/x86/events/amd/core.c (ffffffff81008321)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101467c)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_assign_events
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810457d9)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810581f9)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
```
```
In kernel/workqueue.c (ffffffff8109e506)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_work
  - kernel/workqueue.c:flush_work
```
```
In kernel/sched/rt.c (ffffffff810c422f)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/time/timer.c (ffffffff8189e159)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:__internal_add_timer
```
```
In kernel/events/uprobes.c (ffffffff81199c50)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff811a1160)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/page_alloc.c (ffffffff811a995e)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/shmem.c (ffffffff811c0b90)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/memory.c (ffffffff811dbbc5)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:wp_page_copy
```
```
In mm/rmap.c (ffffffff811e7db2)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/swap_state.c (ffffffff811f08e3)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff811fd43e)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:prep_compound_gigantic_page
```
```
In mm/ksm.c (ffffffff81205e40)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff81208291)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/slub.c:new_slab
```
```
In mm/migrate.c (ffffffff81213090)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff81216c04)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8121abfe)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff8122d28d)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/pipe.c (ffffffff8123ba1f)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
```
```
In fs/file.c (ffffffff812526ed)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
```
```
In fs/ext4/balloc.c (ffffffff812bd3f9)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff812c05a7)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
```
```
In fs/ext4/super.c (ffffffff812ea748)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
```
```
In fs/ext4/mballoc.c (ffffffff813010d9)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/hugetlbfs/inode.c (ffffffff8132880d)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff81345994)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_send_background_locked
  - fs/fuse/dev.c:fuse_request_send_background_locked
  - fs/fuse/dev.c:fuse_request_send
  - fs/fuse/dev.c:fuse_request_send
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dev.c:fuse_request_init
```
```
In fs/fuse/file.c (ffffffff8134ef63)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_sync_release
```
```
In fs/fuse/inode.c (ffffffff8135102b)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_put_super
```
```
In block/blk-core.c (ffffffff813fa87e)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_stop_queue
```
```
In block/blk-tag.c (ffffffff814000eb)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_init_tags
  - block/blk-tag.c:blk_queue_init_tags
```
```
In block/blk-sysfs.c (ffffffff81401240)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:queue_wc_store
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_store_iostats
  - block/blk-sysfs.c:queue_store_random
  - block/blk-sysfs.c:queue_store_nonrot
```
```
In block/blk-settings.c (ffffffff81402b3f)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-settings.c:blk_queue_write_cache
```
```
In block/scsi_ioctl.c (ffffffff81fc6a97)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
```
```
In block/bsg-lib.c (ffffffff8141c92c)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_setup_queue
```
```
In block/blk-cgroup.c (ffffffff8141eb00)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
```
```
In lib/idr.c (ffffffff81430940)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - lib/idr.c:ida_remove
  - lib/idr.c:ida_get_new_above
  - lib/idr.c:idr_get_empty_slot
  - lib/idr.c:idr_mark_full
  - lib/idr.c:idr_mark_full
```
```
In lib/radix-tree.c (ffffffff81434e77)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_range_tag_if_tagged
  - lib/radix-tree.c:radix_tree_range_tag_if_tagged
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:__radix_tree_create
```
```
In drivers/gpio/gpiolib.c (ffffffff81472164)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
```
In drivers/pnp/quirks.c (ffffffff8150acac)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff81fd0779)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff815269e5)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
```
In drivers/tty/sysrq.c (ffffffff8153eda7)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/iommu/amd_iommu.c (ffffffff81582119)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:domain_id_alloc
```
```
In drivers/block/brd.c (ffffffff815c29a9)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/block/brd.c:brd_alloc
  - drivers/block/brd.c:brd_alloc
```
```
In drivers/block/loop.c (ffffffff815c4eef)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_set_status
```
```
In drivers/block/xen-blkfront.c (ffffffff815ca102)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
```
```
In drivers/scsi/sd.c (ffffffff816170a8)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_config_discard
```
```
In drivers/scsi/sr.c (ffffffff81619163)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/net/tun.c (ffffffff8164ce1d)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In drivers/input/input.c (ffffffff816c93d7)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_set_abs_params
  - drivers/input/input.c:input_set_abs_params
```
```
In drivers/input/input-mt.c (ffffffff816caf42)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
```
```
In drivers/input/ff-core.c (ffffffff816cb511)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (ffffffff816cfa2c)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/md/dm.c (ffffffff8170416e)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_setup_md_queue
```
```
In drivers/md/dm-table.c (ffffffff817070e9)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
```
In drivers/md/dm-rq.c (ffffffff8170fc35)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_stop_queue
```
```
In net/socket.c (ffffffff81762442)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff8176ab4a)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_init_data
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
  - net/core/sock.c:sk_set_memalloc
```
```
In net/netlink/af_netlink.c (ffffffff817b724c)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff817cf176)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817d0fe7)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff817d49c3)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff817debbd)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff817e665e)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ea26c)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/udp.c (ffffffff817f496c)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff817fb4fa)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_sk_init
```
```
In net/unix/af_unix.c (ffffffff8182d1ba)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/unix/garbage.c (ffffffff8182f5b0)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/addrconf.c (ffffffff81837d94)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
```
```
In net/ipv6/route.c (ffffffff81842a19)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
```
```
In net/packet/af_packet.c (ffffffff8187661f)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/rfkill/input.c (ffffffff818855af)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
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
In arch/x86/events/core.c (ffffffff81006d06)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_schedule_events
```
```
In arch/x86/events/amd/core.c (ffffffff81008341)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101484f)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_assign_events
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101ab90)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:skx_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_uncore_pci_init_box
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104741c)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105af89)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
```
```
In kernel/workqueue.c (ffffffff810a3073)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_work
  - kernel/workqueue.c:flush_work
```
```
In kernel/sched/rt.c (ffffffff810ca289)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/time/timer.c (ffffffff818d300f)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:__internal_add_timer
```
```
In kernel/events/uprobes.c (ffffffff811a9321)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff811b0d60)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/page_alloc.c (ffffffff811b9ec2)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/shmem.c (ffffffff811d119a)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/memory.c (ffffffff811eb438)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:wp_page_copy
```
```
In mm/rmap.c (ffffffff811f9132)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/swap_state.c (ffffffff812012e5)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff8120df0d)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:prep_compound_gigantic_page
```
```
In mm/ksm.c (ffffffff81217e52)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff8121a2f1)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/slub.c:new_slab
```
```
In mm/migrate.c (ffffffff81225400)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812291a8)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8122eab7)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/userfaultfd.c (ffffffff8123f7b4)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/pipe.c (ffffffff8124e7bf)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
```
```
In fs/file.c (ffffffff81265956)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
```
```
In fs/dax.c (ffffffff8129c3db)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
```
```
In fs/ext4/balloc.c (ffffffff812d2a49)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff812d5bd7)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
```
```
In fs/ext4/super.c (ffffffff813004f7)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
```
```
In fs/ext4/mballoc.c (ffffffff8131714e)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/hugetlbfs/inode.c (ffffffff8133e551)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff8135b6b4)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_send_background_locked
  - fs/fuse/dev.c:fuse_request_send_background_locked
  - fs/fuse/dev.c:fuse_request_send
  - fs/fuse/dev.c:fuse_request_send
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dev.c:fuse_request_init
```
```
In fs/fuse/file.c (ffffffff81364871)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_sync_release
```
```
In fs/fuse/inode.c (ffffffff813669c8)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_put_super
```
```
In block/blk-core.c (ffffffff814141fe)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_stop_queue
```
```
In block/blk-tag.c (ffffffff8141998b)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_init_tags
  - block/blk-tag.c:blk_queue_init_tags
```
```
In block/blk-sysfs.c (ffffffff8141ae6e)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:queue_wc_store
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_store_iostats
  - block/blk-sysfs.c:queue_store_random
  - block/blk-sysfs.c:queue_store_nonrot
```
```
In block/blk-settings.c (ffffffff8141c6ef)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-settings.c:blk_queue_write_cache
```
```
In block/scsi_ioctl.c (ffffffff820034df)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
```
```
In block/bsg-lib.c (ffffffff81437eac)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_setup_queue
```
```
In block/blk-cgroup.c (ffffffff8143a0c0)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
```
```
In lib/idr.c (ffffffff8144cb10)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - lib/idr.c:ida_remove
  - lib/idr.c:ida_get_new_above
  - lib/idr.c:ida_get_new_above
  - lib/idr.c:ida_get_new_above
  - lib/idr.c:idr_alloc
  - lib/idr.c:idr_alloc
  - lib/idr.c:idr_get_empty_slot
```
```
In lib/radix-tree.c (ffffffff81452b95)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_iter_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_join
  - lib/radix-tree.c:__radix_tree_create
```
```
In drivers/gpio/gpiolib.c (ffffffff81494284)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
```
In drivers/pnp/quirks.c (ffffffff8152eecc)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff8200de30)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81552f35)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
```
In drivers/tty/sysrq.c (ffffffff8156b3f7)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/iommu/amd_iommu.c (ffffffff815ae929)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:domain_id_alloc
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff8201440f)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
```
```
In drivers/block/loop.c (ffffffff815f361f)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_set_status
```
```
In drivers/block/xen-blkfront.c (ffffffff815f6d62)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
```
```
In drivers/scsi/sd.c (ffffffff816474f4)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_config_discard
```
```
In drivers/scsi/sr.c (ffffffff81649df3)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/net/tun.c (ffffffff8167eb5d)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In drivers/input/input.c (ffffffff816f73b7)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_set_abs_params
  - drivers/input/input.c:input_set_abs_params
```
```
In drivers/input/input-mt.c (ffffffff816f8f02)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
```
```
In drivers/input/ff-core.c (ffffffff816f94c1)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (ffffffff816fd90c)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817010a1)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/md/md.c (ffffffff8172a66b)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
```
```
In drivers/md/dm.c (ffffffff8173603e)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_setup_md_queue
```
```
In drivers/md/dm-table.c (ffffffff81738fc4)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
```
In drivers/extcon/extcon.c (ffffffff8177f280)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
```
```
In net/socket.c (ffffffff8178f472)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81797c6a)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_init_data
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
  - net/core/sock.c:sk_set_memalloc
```
```
In net/netlink/af_netlink.c (ffffffff817e6ccc)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff817fef90)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81800ea7)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff81804717)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff8180ef9b)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81816d9e)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81818aa9)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/udp.c (ffffffff81825a3c)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff8182c3aa)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_sk_init
```
```
In net/unix/af_unix.c (ffffffff8185ec9a)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/unix/garbage.c (ffffffff81861042)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/addrconf.c (ffffffff81869d54)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
```
```
In net/ipv6/route.c (ffffffff81874789)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818aab9a)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/rfkill/input.c (ffffffff818b9e1f)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
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
In arch/x86/events/core.c (ffffffff81006a61)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_schedule_events
```
```
In arch/x86/events/amd/core.c (ffffffff81008012)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/intel/uncore.c (ffffffff81012e6f)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_assign_events
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81018f63)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:skx_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_uncore_pci_init_box
```
```
In arch/x86/kernel/ioport.c (0)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81046cdb)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105a539)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
```
```
In kernel/sysctl.c (0)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
```
```
In kernel/workqueue.c (ffffffff810a03a0)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_work
  - kernel/workqueue.c:flush_work
```
```
In kernel/sched/rt.c (ffffffff810c3ddc)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/irq/irqdesc.c (0)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
```
```
In kernel/time/timer.c (ffffffff810fe2fe)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:__internal_add_timer
```
```
In kernel/smp.c (ffffffff81114041)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/events/uprobes.c (ffffffff811b089e)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff811b8284)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/page_alloc.c (ffffffff811c241c)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/shmem.c (ffffffff811dcc1a)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mcopy_atomic_pte
  - mm/shmem.c:shmem_mcopy_atomic_pte
  - mm/shmem.c:shmem_mcopy_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
```
```
In mm/memory.c (ffffffff811f5e4e)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:wp_page_copy
```
```
In mm/rmap.c (ffffffff81203ce2)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/swap_state.c (ffffffff8120c190)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff81217779)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:prep_compound_gigantic_page
```
```
In mm/ksm.c (ffffffff81223a31)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff81225dc3)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/slub.c:new_slab
```
```
In mm/migrate.c (ffffffff81230ac5)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812355de)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81238c93)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/cma.c (0)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
```
```
In mm/userfaultfd.c (ffffffff8124b366)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/pipe.c (ffffffff8125a71f)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
```
```
In fs/file.c (ffffffff8127309f)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
```
```
In fs/dax.c (ffffffff812ab4de)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
```
```
In fs/ext4/balloc.c (ffffffff812e405d)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff812f3e57)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff8130e19a)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/ext4/super.c (ffffffff81335318)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
```
```
In fs/hugetlbfs/inode.c (ffffffff81353182)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff81370030)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_send_background_locked
  - fs/fuse/dev.c:fuse_request_send_background_locked
  - fs/fuse/dev.c:fuse_request_send
  - fs/fuse/dev.c:fuse_request_send
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dev.c:fuse_request_init
```
```
In fs/fuse/file.c (ffffffff8137903f)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_flush
```
```
In fs/fuse/inode.c (ffffffff8137b08d)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_put_super
```
```
In security/integrity/ima/ima_template.c (ffffffff813fa7a6)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/blk-core.c (ffffffff81421cca)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_stop_queue
```
```
In block/blk-tag.c (ffffffff814278bd)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_init_tags
  - block/blk-tag.c:blk_queue_init_tags
```
```
In block/blk-sysfs.c (ffffffff81428d4f)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:queue_wc_store
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_store_iostats
  - block/blk-sysfs.c:queue_store_random
  - block/blk-sysfs.c:queue_store_nonrot
```
```
In block/blk-settings.c (ffffffff8142a648)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-settings.c:blk_queue_write_cache
```
```
In block/blk-mq.c (ffffffff8142ec49)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_quiesce_queue_nowait
```
```
In block/scsi_ioctl.c (ffffffff820e6dd9)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
```
```
In block/bsg-lib.c (ffffffff814456ac)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_setup_queue
  - block/bsg-lib.c:bsg_setup_queue
```
```
In block/blk-cgroup.c (ffffffff81447834)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
```
```
In lib/iommu-helper.c (0)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff8149d7c9)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
```
In drivers/pwm/core.c (0)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
```
```
In drivers/pnp/quirks.c (ffffffff815426c7)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff820ef87c)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff815678fb)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
```
In drivers/tty/sysrq.c (ffffffff8157fba2)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/iommu/amd_iommu.c (ffffffff815c4529)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:domain_id_alloc
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff820f5925)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815d5dc5)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
```
```
In drivers/block/loop.c (ffffffff8160799b)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_set_status
```
```
In drivers/block/xen-blkfront.c (ffffffff8160affe)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
```
```
In drivers/scsi/scsi_lib.c (ffffffff81649cbb)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
```
In drivers/scsi/sd.c (ffffffff8165b5df)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_config_discard
```
```
In drivers/scsi/sr.c (ffffffff8165e8d3)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/net/tun.c (ffffffff81693d34)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
```
```
In drivers/input/input.c (ffffffff8170ce9b)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_set_abs_params
  - drivers/input/input.c:input_set_abs_params
```
```
In drivers/input/input-mt.c (ffffffff8170ea55)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
```
```
In drivers/input/ff-core.c (ffffffff8170f012)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (ffffffff817131f9)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817168ef)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/md/md.c (ffffffff817432fc)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
```
```
In drivers/md/dm.c (ffffffff8174f4de)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_setup_md_queue
```
```
In drivers/md/dm-table.c (ffffffff81752799)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
```
In drivers/extcon/extcon.c (ffffffff8179dd3b)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
```
```
In net/socket.c (ffffffff817ad3f2)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff817b582a)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_init_data
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
  - net/core/sock.c:sk_set_memalloc
```
```
In net/netlink/af_netlink.c (ffffffff81806b16)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff8181f238)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81820c07)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff81824987)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff8182eeeb)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81837023)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81839288)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/udp.c (ffffffff81847ad9)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff8184d95a)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81882f2c)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/unix/garbage.c (ffffffff81885748)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/addrconf.c (ffffffff8188e227)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
```
```
In net/ipv6/route.c (ffffffff818995a1)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818d1638)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/rfkill/input.c (ffffffff818e082f)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
```
```
In lib/idr.c (ffffffff818ecd4f)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - lib/idr.c:ida_get_new_above
  - lib/idr.c:ida_get_new_above
```
```
In lib/radix-tree.c (ffffffff818f05cb)
Location: arch/x86/include/asm/bitops.h:94
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_join
  - lib/radix-tree.c:radix_tree_extend
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
In arch/x86/events/core.c (ffffffff81006e71)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_schedule_events
```
```
In arch/x86/events/amd/core.c (ffffffff81008492)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101367f)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_assign_events
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81019683)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:skx_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_uncore_pci_init_box
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102a8ce)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/kernel/ioport.c (0)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81042136)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104a762)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105ea51)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106b270)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff8107a2d2)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826c59bb)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
```
In kernel/sysctl.c (0)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In kernel/workqueue.c (ffffffff810a6906)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_work
  - kernel/workqueue.c:flush_work
```
```
In kernel/sched/rt.c (ffffffff810cb5ac)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/sched/debug.c (ffffffff810d84c7)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - kernel/sched/debug.c:dirty_sched_domain_sysctl
```
```
In kernel/sched/membarrier.c (ffffffff810dbf40)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:SyS_membarrier
```
```
In kernel/irq/irqdesc.c (0)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In kernel/irq/matrix.c (ffffffff810f8faf)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In kernel/time/timer.c (ffffffff81108b8e)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:__internal_add_timer
```
```
In kernel/smp.c (ffffffff8111f5bb)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/bpf/devmap.c (ffffffff811af5da)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_insert_ctx
```
```
In kernel/bpf/cpumap.c (ffffffff811b039a)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_insert_ctx
```
```
In kernel/events/uprobes.c (ffffffff811c43a5)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff811cc974)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/page_alloc.c (ffffffff811d6dcd)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/shmem.c (ffffffff811eeb0c)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In mm/memory.c (ffffffff8120db2a)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
```
In mm/rmap.c (ffffffff8121ca52)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/swap_state.c (ffffffff81225854)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff81232429)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:prep_compound_gigantic_page
```
```
In mm/ksm.c (ffffffff8123f071)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff81243058)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - mm/slub.c:new_slab
```
```
In mm/migrate.c (ffffffff8124e841)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff81253541)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81259be0)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/cma.c (0)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In mm/userfaultfd.c (ffffffff8126b624)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/pipe.c (ffffffff8127ca7f)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
```
```
In fs/file.c (ffffffff812959cf)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
```
```
In fs/dax.c (ffffffff812cee24)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
```
```
In fs/ext4/balloc.c (ffffffff813089ed)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff8131a19a)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/mballoc.c (ffffffff813332aa)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/ext4/super.c (ffffffff81359828)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
```
```
In fs/hugetlbfs/inode.c (ffffffff81377cfb)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff81394d30)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_send_background_locked
  - fs/fuse/dev.c:fuse_request_send_background_locked
  - fs/fuse/dev.c:fuse_request_send
  - fs/fuse/dev.c:fuse_request_send
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dev.c:fuse_request_init
```
```
In fs/fuse/file.c (ffffffff8139dedf)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_flush
```
```
In fs/fuse/inode.c (ffffffff8139ff33)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_put_super
```
```
In security/integrity/ima/ima_template.c (ffffffff81422c46)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/blk-core.c (ffffffff8144c7f8)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_set_queue_dying
  - block/blk-core.c:blk_set_preempt_only
  - block/blk-core.c:blk_stop_queue
```
```
In block/blk-tag.c (ffffffff814528bd)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_init_tags
  - block/blk-tag.c:blk_queue_init_tags
```
```
In block/blk-sysfs.c (ffffffff81453e1f)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:queue_wc_store
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_store_iostats
  - block/blk-sysfs.c:queue_store_random
  - block/blk-sysfs.c:queue_store_nonrot
```
```
In block/blk-settings.c (ffffffff81455998)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-settings.c:blk_queue_write_cache
```
```
In block/blk-mq.c (ffffffff8145a0d9)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_quiesce_queue_nowait
```
```
In block/scsi_ioctl.c (ffffffff826efb54)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
```
```
In block/bsg-lib.c (ffffffff81472189)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_setup_queue
  - block/bsg-lib.c:bsg_setup_queue
```
```
In block/blk-cgroup.c (ffffffff81474433)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In lib/bitmap.c (0)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In lib/iommu-helper.c (0)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff814dc1db)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/pwm/core.c (0)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In drivers/acpi/x86/apple.c (ffffffff8154f768)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/pnp/quirks.c (ffffffff815a57e7)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff826f906d)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff815cbabb)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
```
In drivers/tty/sysrq.c (ffffffff815e4722)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/iommu/amd_iommu.c (ffffffff8162b2e9)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:domain_id_alloc
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff826fefe5)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8163cb75)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In drivers/block/loop.c (ffffffff81670049)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/block/xen-blkfront.c (ffffffff816738ce)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
```
```
In drivers/scsi/scsi_lib.c (ffffffff816b2e0b)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
```
In drivers/scsi/sd.c (ffffffff816c4c59)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_config_discard
```
```
In drivers/scsi/sr.c (ffffffff816c7ce8)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/net/tun.c (ffffffff816fdb64)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In drivers/input/input.c (ffffffff8177e0db)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_set_abs_params
  - drivers/input/input.c:input_set_abs_params
```
```
In drivers/input/input-mt.c (ffffffff8177fc95)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In drivers/input/ff-core.c (ffffffff81780262)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81784439)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81787af1)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/md/md.c (ffffffff817b543a)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
```
```
In drivers/md/dm.c (ffffffff817c1709)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_setup_md_queue
```
```
In drivers/md/dm-table.c (ffffffff817c472c)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
```
In drivers/extcon/extcon.c (ffffffff81814e90)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
```
```
In net/socket.c (ffffffff81825382)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff8182dcf3)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_init_data
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
  - net/core/sock.c:sk_set_memalloc
```
```
In net/netlink/af_netlink.c (ffffffff818857f6)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff8189e1a8)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8189fbfd)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff818a65e5)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff818adf0b)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff818b66bf)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818ba550)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In net/ipv4/udp.c (ffffffff818c7539)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff818cd69c)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In net/unix/af_unix.c (ffffffff819048f8)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/unix/garbage.c (ffffffff819068f8)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/addrconf.c (ffffffff8190f2cf)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In net/ipv6/route.c (ffffffff8191a8e5)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_convert_metrics
  - net/ipv6/route.c:ip6_convert_metrics
```
```
In net/packet/af_packet.c (ffffffff81956591)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/rfkill/input.c (ffffffff8196653f)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In lib/idr.c (ffffffff81972d6f)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - lib/idr.c:ida_get_new_above
  - lib/idr.c:ida_get_new_above
```
```
In lib/radix-tree.c (ffffffff81976a1b)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_join
  - lib/radix-tree.c:radix_tree_extend
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
In arch/x86/events/core.c (ffffffff81007601)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_schedule_events
```
```
In arch/x86/events/amd/core.c (ffffffff81008c42)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/intel/uncore.c (ffffffff81013fe5)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_assign_events
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101a000)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:skx_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_uncore_pci_init_box
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102b4c3)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102bcf0)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In arch/x86/kernel/signal.c (ffffffff8102d6ba)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/ioport.c (0)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81044016)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104cd94)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810619f7)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106dedd)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff8107d076)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826efa91)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
```
In kernel/sysctl.c (0)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In kernel/workqueue.c (ffffffff810ad576)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:__flush_work
```
```
In kernel/sched/core.c (ffffffff819ec5d7)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/rt.c (ffffffff810d2ee8)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/sched/debug.c (ffffffff810df934)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - kernel/sched/debug.c:dirty_sched_domain_sysctl
```
```
In kernel/sched/membarrier.c (ffffffff810e423a)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/irq/irqdesc.c (0)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In kernel/irq/matrix.c (ffffffff8110150f)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In kernel/time/timer.c (ffffffff811145dd)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:__internal_add_timer
```
```
In kernel/smp.c (ffffffff8112c8ea)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/bpf/devmap.c (ffffffff811c9f3a)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_insert_ctx
```
```
In kernel/bpf/cpumap.c (ffffffff811cae9a)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_insert_ctx
```
```
In kernel/events/uprobes.c (ffffffff811e48b3)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff811eda61)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/page_alloc.c (ffffffff811f86ea)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/shmem.c (ffffffff8120f634)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In mm/memory.c (ffffffff8122e24c)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
```
In mm/rmap.c (ffffffff8123e7e1)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/swap_state.c (ffffffff81247df4)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff81255479)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:prep_compound_gigantic_page
```
```
In mm/ksm.c (ffffffff8126281d)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff812648ac)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - mm/slub.c:new_slab
```
```
In mm/migrate.c (ffffffff81272649)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff81277b47)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8127b2c7)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/cma.c (0)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In mm/userfaultfd.c (ffffffff8128feb1)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/pipe.c (ffffffff812a39cf)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
```
```
In fs/file.c (ffffffff812bbc5f)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
```
```
In fs/dax.c (ffffffff812f9586)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff8133697c)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff81347da5)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/mballoc.c (ffffffff81361446)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/ext4/super.c (ffffffff813881ae)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
```
```
In fs/hugetlbfs/inode.c (ffffffff813a6671)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff813c3e50)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_send_background_locked
  - fs/fuse/dev.c:fuse_request_send_background_locked
  - fs/fuse/dev.c:fuse_request_send
  - fs/fuse/dev.c:fuse_request_send
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dev.c:fuse_request_init
```
```
In fs/fuse/file.c (ffffffff813cd2b0)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_flush
```
```
In fs/fuse/inode.c (ffffffff813cda5a)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_sb_destroy
  - fs/fuse/inode.c:fuse_fill_super
```
```
In security/integrity/ima/ima_template.c (ffffffff81455216)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/blk-core.c (ffffffff8147fad8)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_stop_queue
  - block/blk-core.c:blk_queue_flag_test_and_set
  - block/blk-core.c:blk_queue_flag_set
```
```
In block/blk-tag.c (ffffffff81485c8d)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_init_tags
  - block/blk-tag.c:blk_queue_init_tags
```
```
In block/blk-sysfs.c (ffffffff81486db4)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_nomerges_store
```
```
In block/blk-settings.c (ffffffff81488c28)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-settings.c:blk_queue_write_cache
```
```
In block/blk-mq.c (ffffffff8149223b)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/scsi_ioctl.c (ffffffff82719faa)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
```
```
In block/blk-cgroup.c (ffffffff814a8b97)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In lib/bitmap.c (0)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In lib/iommu-helper.c (0)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff8150a56a)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/pwm/core.c (0)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In drivers/acpi/x86/apple.c (ffffffff81585fc5)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/pnp/quirks.c (ffffffff815dd3e7)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff8272342a)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81604311)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
```
In drivers/tty/sysrq.c (ffffffff8161d766)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/iommu/amd_iommu.c (ffffffff816688d1)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:domain_id_alloc
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff827292c2)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81677fb6)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In drivers/scsi/sr.c (ffffffff81704693)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/net/phy/sfp-bus.c (ffffffff8173ab04)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
```
```
In drivers/net/tun.c (ffffffff8173bc76)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In drivers/input/input.c (ffffffff817bf1fb)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_set_abs_params
  - drivers/input/input.c:input_set_abs_params
```
```
In drivers/input/input-mt.c (ffffffff817c0d92)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In drivers/input/ff-core.c (ffffffff817c1361)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (ffffffff817c552e)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817c8bf3)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/extcon/extcon.c (ffffffff8185ed99)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
```
```
In net/socket.c (ffffffff8186f332)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff818780c3)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_init_data
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
  - net/core/sock.c:sk_set_memalloc
```
```
In net/netlink/af_netlink.c (ffffffff818d917f)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff818f2bcb)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f4c5d)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff818fb685)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff8190358b)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff8190beff)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8190efe0)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8191e731)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff81923a78)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In net/unix/af_unix.c (ffffffff8195a127)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/unix/garbage.c (ffffffff8195d8e8)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/addrconf.c (ffffffff81966398)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff8199fe37)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff819b19cf)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/rfkill/input.c (ffffffff819bfe1a)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In net/xdp/xsk.c (ffffffff819cbff6)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In lib/idr.c (ffffffff819cf353)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - lib/idr.c:ida_get_new_above
  - lib/idr.c:ida_get_new_above
```
```
In lib/radix-tree.c (ffffffff819d31cb)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_join
  - lib/radix-tree.c:radix_tree_extend
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
In arch/x86/events/core.c (ffffffff810074e1)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_schedule_events
```
```
In arch/x86/events/amd/core.c (ffffffff81008b62)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/intel/uncore.c (ffffffff810146e5)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_assign_events
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff810181d3)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101a7d0)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:skx_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_uncore_pci_init_box
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102bdc7)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102ccd6)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/signal.c (ffffffff8102e904)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/ioport.c (0)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81045a16)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104a400)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105d986)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810676d7)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
```
```
In arch/x86/kernel/kvm.c (ffffffff81072a08)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In arch/x86/kernel/paravirt.c (ffffffff81073e6d)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff81083ab6)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a674e)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
```
In kernel/sysctl.c (0)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In kernel/workqueue.c (ffffffff810b685c)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:__flush_work
```
```
In kernel/sched/core.c (ffffffff81a27859)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/rt.c (ffffffff810dd128)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/sched/debug.c (ffffffff810ea0b4)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - kernel/sched/debug.c:dirty_sched_domain_sysctl
```
```
In kernel/sched/membarrier.c (ffffffff810eeb5a)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/irq/irqdesc.c (0)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In kernel/irq/matrix.c (ffffffff8110ce29)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In kernel/time/timer.c (ffffffff8111fe5d)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:__internal_add_timer
```
```
In kernel/smp.c (ffffffff81138431)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/bpf/devmap.c (ffffffff811dd84a)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_insert_ctx
```
```
In kernel/bpf/cpumap.c (ffffffff811de7aa)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_insert_ctx
```
```
In kernel/events/uprobes.c (ffffffff811f570e)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff811ff011)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/page_alloc.c (ffffffff81a20e81)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:reserve_bootmem_region
```
```
In mm/shmem.c (ffffffff8122255f)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In mm/memory.c (ffffffff81242334)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
```
In mm/rmap.c (ffffffff81252d71)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/swap_state.c (ffffffff8125c3b5)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff81269859)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:prep_compound_gigantic_page
```
```
In mm/ksm.c (ffffffff8127709d)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff81278fda)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - mm/slub.c:new_slab
```
```
In mm/migrate.c (ffffffff81286c43)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff8128c164)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8128f936)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/cma.c (0)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812a4dbe)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/pipe.c (ffffffff812b8a3f)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
```
```
In fs/file.c (ffffffff812d0edf)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
```
```
In fs/dax.c (ffffffff8130d764)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff8134dbfc)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff8135ff55)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/mballoc.c (ffffffff813796f6)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/ext4/super.c (ffffffff813a0d7e)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
```
```
In fs/hugetlbfs/inode.c (ffffffff813bf451)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff813dd609)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_queue_background
  - fs/fuse/dev.c:fuse_request_queue_background
  - fs/fuse/dev.c:fuse_request_send
  - fs/fuse/dev.c:fuse_request_send
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dev.c:__fuse_request_alloc
```
```
In fs/fuse/file.c (ffffffff813e662c)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_flush
```
```
In fs/fuse/inode.c (ffffffff813e6e4a)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_sb_destroy
  - fs/fuse/inode.c:fuse_fill_super
```
```
In security/integrity/ima/ima_template.c (ffffffff814725f6)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/scsi_ioctl.c (ffffffff828d1fa3)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
```
```
In block/blk-cgroup.c (ffffffff814c29ca)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In lib/bitmap.c (0)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In lib/iommu-helper.c (0)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff8151fda5)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/pwm/core.c (0)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In drivers/acpi/x86/apple.c (ffffffff8159e2e7)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/pnp/quirks.c (ffffffff815f6b87)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff828db591)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff8161f3cf)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
```
In drivers/tty/sysrq.c (ffffffff8163aa07)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/iommu/amd_iommu.c (ffffffff816873a1)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:domain_id_alloc
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff828e1510)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81697096)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In drivers/scsi/sr.c (ffffffff81726b03)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/net/phy/phy.c (ffffffff817580b6)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_speed_up
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
In drivers/net/phy/phy-c45.c (ffffffff817596f1)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:gen10g_config_init
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
In drivers/net/phy/phy_device.c (ffffffff828e855f)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
```
```
In drivers/net/phy/sfp-bus.c (ffffffff8175e264)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8175edb2)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In drivers/net/tun.c (ffffffff8175f5b0)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In drivers/input/input.c (ffffffff817e665b)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_set_abs_params
  - drivers/input/input.c:input_set_abs_params
```
```
In drivers/input/input-mt.c (ffffffff817e8282)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In drivers/input/ff-core.c (ffffffff817e8851)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (ffffffff817ecafe)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817f0293)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/extcon/extcon.c (ffffffff8187e739)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
```
```
In net/socket.c (ffffffff8188f7f2)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff818985a3)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_init_data
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
  - net/core/sock.c:sk_set_memalloc
```
```
In net/core/dev.c (ffffffff818b751e)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/netlink/af_netlink.c (ffffffff819058ff)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff8192063b)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8192215d)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff819295d5)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff819316db)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff8193a1dc)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193d410)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8194d531)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff81952868)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In net/unix/af_unix.c (ffffffff8198ec87)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/unix/garbage.c (ffffffff81992428)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/addrconf.c (ffffffff8199b7b6)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff819d66ce)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff819e8daf)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/rfkill/input.c (ffffffff819f704a)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81a050fe)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In lib/idr.c (ffffffff81a08a32)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffff81a0d11d)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff81a187bd)
Location: arch/x86/include/asm/bitops.h:95
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In arch/x86/events/core.c (ffffffff810077ab)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_schedule_events
```
```
In arch/x86/events/amd/core.c (ffffffff81009102)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015b65)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_assign_events
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff810197b3)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101c1c1)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snr_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_uncore_pci_init_box
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102de9d)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102ec20)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
```
```
In arch/x86/kernel/signal.c (ffffffff81030ba1)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81048234)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d582)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81060d36)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106ae80)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
```
```
In arch/x86/kernel/kvm.c (ffffffff8107687d)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077a0d)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff81087760)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828bedea)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
```
In kernel/sysctl.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In kernel/workqueue.c (ffffffff810bccc9)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:__flush_work
```
```
In kernel/sched/core.c (ffffffff81a98102)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/rt.c (ffffffff810e40e8)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/sched/debug.c (ffffffff810f0ea7)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/sched/debug.c:dirty_sched_domain_sysctl
```
```
In kernel/sched/membarrier.c (ffffffff810f5967)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/sched/isolation.c (ffffffff828c55a8)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In kernel/irq/matrix.c (ffffffff8111650e)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In kernel/time/timer.c (ffffffff81128240)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/smp.c (ffffffff811435ef)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/events/uprobes.c (ffffffff8120d48a)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff8121602c)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/shmem.c (ffffffff81231b61)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/percpu.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In mm/memory.c (ffffffff81253ece)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
```
In mm/rmap.c (ffffffff812650f4)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/page_alloc.c (ffffffff81a91446)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:reserve_bootmem_region
```
```
In mm/swap_state.c (ffffffff8127759d)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff81284997)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:prep_compound_gigantic_page
```
```
In mm/sparse.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In mm/ksm.c (ffffffff812928fb)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff81294214)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff812a11e2)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812a6d8c)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812aa9dd)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/cma.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812c038c)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/pipe.c (ffffffff812d577f)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
```
```
In fs/file.c (ffffffff812edf13)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
```
```
In fs/dax.c (ffffffff8133597c)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff813765d9)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff813890c6)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/mballoc.c (ffffffff813a3210)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/ext4/super.c (ffffffff813cb63a)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
```
```
In fs/hugetlbfs/inode.c (ffffffff813e9da9)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff81409138)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_queue_background
  - fs/fuse/dev.c:fuse_request_queue_background
  - fs/fuse/dev.c:fuse_request_send
  - fs/fuse/dev.c:fuse_request_send
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dev.c:__fuse_request_alloc
```
```
In fs/fuse/file.c (ffffffff81412660)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_flush
```
```
In fs/fuse/inode.c (ffffffff81412e78)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_sb_destroy
  - fs/fuse/inode.c:fuse_fill_super
```
```
In security/integrity/ima/ima_template.c (ffffffff814a02f6)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/scsi_ioctl.c (ffffffff828ebf95)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
```
```
In block/blk-cgroup.c (ffffffff814f10ac)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In lib/bitmap.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In lib/iommu-helper.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff8154def9)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/pwm/core.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/acpi/x86/apple.c (ffffffff815cf847)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/pnp/quirks.c (ffffffff8162889b)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff828f5ec4)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff816529b8)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
```
In drivers/tty/sysrq.c (ffffffff8166ed71)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81695636)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff816beb3b)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:domain_id_alloc
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff828fc6ff)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816cfa0f)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/scsi/sr.c (ffffffff81762236)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/net/phy/phy.c (ffffffff817948fe)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_speed_up
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
In drivers/net/phy/phy-c45.c (ffffffff817960bd)
Location: include/asm-generic/bitops-instrumented.h:41
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
```
```
In drivers/net/phy/phy_device.c (ffffffff82902e8b)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
```
```
In drivers/net/phy/sfp-bus.c (ffffffff8179b8e7)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8179c3f1)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/net/tun.c (ffffffff8179cde6)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/input/input.c (ffffffff81827293)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_set_abs_params
  - drivers/input/input.c:input_set_abs_params
```
```
In drivers/input/input-mt.c (ffffffff81828dcb)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/input/ff-core.c (ffffffff81829562)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8182d69e)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8183069c)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/extcon/extcon.c (ffffffff818c8d72)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
```
```
In net/socket.c (ffffffff818d984e)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff818e2b56)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_init_data
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
  - net/core/sock.c:sk_set_memalloc
```
```
In net/core/dev.c (ffffffff81903355)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/netlink/af_netlink.c (ffffffff81966b3d)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff81982f70)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8198523e)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff8198c505)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff81994e0b)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff8199e484)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a1841)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819b1cfd)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff819b7121)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In net/unix/af_unix.c (ffffffff819fa2a9)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/unix/garbage.c (ffffffff819fda44)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: False
```
```
In net/ipv6/addrconf.c (ffffffff81a07721)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a45b41)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff81a590e9)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/rfkill/input.c (ffffffff81a6658c)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81a7465c)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In lib/idr.c (ffffffff81a7840c)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffff81a7ca5e)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff81a883c8)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In arch/x86/events/core.c (ffffffff8100796b)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_pmu_start
```
```
In arch/x86/events/amd/core.c (ffffffff810094b2)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016525)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_assign_events
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101a133)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101cb41)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snr_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_uncore_pci_init_box
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102e7ad)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f530)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
```
```
In arch/x86/kernel/signal.c (ffffffff81031029)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81048ae4)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104df22)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810615e6)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106b820)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
```
```
In arch/x86/kernel/kvm.c (ffffffff8107790d)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In arch/x86/kernel/paravirt.c (ffffffff81078a7d)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff81088450)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c5263)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff81097853)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
```
```
In kernel/sysctl.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In kernel/workqueue.c (ffffffff810c2949)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:__flush_work
```
```
In kernel/sched/core.c (ffffffff81acf9d8)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/rt.c (ffffffff810ee617)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:alloc_rt_sched_group
```
```
In kernel/sched/debug.c (ffffffff810fcb57)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/sched/debug.c:dirty_sched_domain_sysctl
```
```
In kernel/sched/membarrier.c (ffffffff811014bf)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/sched/isolation.c (ffffffff828cdc11)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In kernel/irq/matrix.c (ffffffff811228de)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In kernel/time/timer.c (ffffffff811341e0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/smp.c (ffffffff8114f12f)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/events/uprobes.c (ffffffff8121a914)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff8122393b)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/shmem.c (ffffffff8123fc21)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/percpu.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In mm/memory.c (ffffffff81262425)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
```
In mm/rmap.c (ffffffff81273984)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/page_alloc.c (ffffffff81ac877b)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:reserve_bootmem_region
```
```
In mm/swap_state.c (ffffffff8128707d)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff81294537)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:prep_compound_gigantic_page
```
```
In mm/sparse.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In mm/ksm.c (ffffffff812a267e)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff812a3f13)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff812b25f2)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812b8237)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812bbf81)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/cma.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812d22dc)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/pipe.c (ffffffff812e72ef)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
```
```
In fs/file.c (ffffffff812ff9d3)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
```
```
In fs/dax.c (ffffffff8134957c)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff8138e849)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff813a1a4c)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/mballoc.c (ffffffff813bc070)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/ext4/super.c (ffffffff813e49fa)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
```
```
In fs/hugetlbfs/inode.c (ffffffff81403e49)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff814221bf)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_request_alloc
```
```
In security/integrity/ima/ima_template.c (ffffffff814ba959)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/scsi_ioctl.c (ffffffff828f4b64)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
```
```
In block/blk-cgroup.c (ffffffff8150a5c7)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In lib/bitmap.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In lib/iommu-helper.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff8156f0f9)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/pwm/core.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/acpi/x86/apple.c (ffffffff815f0ac7)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/pnp/quirks.c (ffffffff8164a38b)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff828fef1b)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81674f58)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
```
In drivers/tty/sysrq.c (ffffffff81691381)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff816b81c6)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff816e1eeb)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:domain_id_alloc
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff82905699)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816f384f)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/scsi/sr.c (ffffffff81786226)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/net/phy/phy.c (ffffffff817b849e)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
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
In drivers/net/phy/phy-c45.c (ffffffff817b9a7d)
Location: include/asm-generic/bitops-instrumented.h:41
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
```
```
In drivers/net/phy/phy_device.c (ffffffff8290c088)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:genphy_read_abilities
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
In drivers/net/phy/sfp-bus.c (ffffffff817bf397)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
```
```
In drivers/net/phy/fixed_phy.c (ffffffff817bfea5)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/net/tun.c (ffffffff817c0886)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/input/input.c (ffffffff818587c3)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_set_abs_params
  - drivers/input/input.c:input_set_abs_params
```
```
In drivers/input/input-mt.c (ffffffff8185a33b)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/input/ff-core.c (ffffffff8185aef2)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8185efce)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81861fcc)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/extcon/extcon.c (ffffffff818fb1c2)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
```
```
In net/socket.c (ffffffff8190b82e)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81914d36)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_init_data
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
  - net/core/sock.c:sk_set_memalloc
```
```
In net/core/dev.c (ffffffff81936105)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/netlink/af_netlink.c (ffffffff8199d5bd)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff819b97d9)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bb32e)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff819c2e55)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff819cb95b)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff819d4f71)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819d84f1)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819e8a83)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff819ede21)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81a30f29)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/unix/garbage.c (ffffffff81a34634)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: False
```
```
In net/ipv6/addrconf.c (ffffffff81a3e291)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a7c731)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff81a8f1f9)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/rfkill/input.c (ffffffff81a9d0ac)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81aaafec)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In lib/idr.c (ffffffff81aaf6cc)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffff81ab3d8e)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff81abf668)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In arch/x86/events/core.c (ffffffff810089db)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_pmu_start
```
```
In arch/x86/events/amd/core.c (ffffffff8100a491)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_alloc_nb
```
```
In arch/x86/events/intel/uncore.c (ffffffff81018a75)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_assign_events
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101ba73)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101e1e1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snr_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_uncore_pci_init_box
```
```
In arch/x86/hyperv/mmu.c (ffffffff81030d95)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81031a70)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/signal.c (ffffffff8103396d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:setup_rt_frame
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff8104cc14)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810528a8)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810671f6)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81071641)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
```
```
In arch/x86/kernel/kvm.c (ffffffff8107ebfd)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In arch/x86/mm/tlb.c (ffffffff8108ba10)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_local
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff8109c982)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
```
```
In kernel/sysctl.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In kernel/workqueue.c (ffffffff810c8e02)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In kernel/sched/core.c (ffffffff810dde38)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/rt.c (ffffffff810f828d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/sched/debug.c (ffffffff811072e7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/sched/debug.c:dirty_sched_domain_sysctl
```
```
In kernel/sched/membarrier.c (ffffffff8110bcf6)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/sched/isolation.c (ffffffff82ceefd5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In kernel/irq/matrix.c (ffffffff8112ef2e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In kernel/time/timer.c (ffffffff81145d3d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
```
```
In kernel/smp.c (ffffffff8115f853)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/events/uprobes.c (ffffffff8124730b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In kernel/watch_queue.c (ffffffff8124d26e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_filter
```
```
In mm/filemap.c (ffffffff81251e79)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/shmem.c (ffffffff8126e48d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/percpu.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In mm/memory.c (ffffffff81291eeb)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/memory.c:do_cow_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
```
In mm/rmap.c (ffffffff812a4c58)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/page_alloc.c (ffffffff82cfb4e0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/page_alloc.c:init_unavailable_range
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:reserve_bootmem_region
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/swap_state.c (ffffffff812b968c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff812c7927)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:prep_compound_gigantic_page
```
```
In mm/sparse.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In mm/ksm.c (ffffffff812d6d9a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff812d9a33)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff812e7b92)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812e9500)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812f14a7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff81307fff)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/mapping_dirty_helpers.c (ffffffff8130c741)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
```
```
In mm/page_reporting.c (ffffffff8130cf06)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In fs/pipe.c (ffffffff8131ec5f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_try_steal
```
```
In fs/file.c (ffffffff81338ae5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
```
```
In fs/dax.c (ffffffff8138e8d8)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
```
```
In fs/ext4/balloc.c (ffffffff813d9c20)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff813edca6)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/mballoc.c (ffffffff81407ca4)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/ext4/super.c (ffffffff8142ce44)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
```
```
In fs/hugetlbfs/inode.c (ffffffff81451c99)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff8146e84b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_request_queue_background
  - fs/fuse/dev.c:fuse_request_queue_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_get_req
```
```
In security/integrity/ima/ima_template.c (ffffffff8151aef9)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/scsi_ioctl.c (ffffffff81568096)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In block/blk-cgroup.c (ffffffff8156b199)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In lib/bitmap.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In lib/iommu-helper.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In lib/idr.c (ffffffff815e9570)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffff815ee285)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff815fbb34)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
```
```
In drivers/gpio/gpiolib.c (ffffffff816135bb)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/pwm/core.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In drivers/acpi/x86/apple.c (ffffffff8169cd6e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/pnp/quirks.c (ffffffff816f946b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff82d15fe1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff817259f8)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
```
In drivers/tty/sysrq.c (ffffffff81743ada)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8176c2a6)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In drivers/iommu/amd/iommu.c (ffffffff81796624)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:protection_domain_alloc
```
```
In drivers/iommu/amd/init.c (ffffffff82d1c413)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:copy_device_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817aafe1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81837f8c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
```
In drivers/scsi/sr.c (ffffffff8184ad5a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/net/phy/phy.c (ffffffff8187f02e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
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
In drivers/net/phy/phy-c45.c (ffffffff81880f80)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
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
```
```
In drivers/net/phy/phy_device.c (ffffffff81884e86)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:genphy_read_abilities
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
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
```
```
In drivers/net/phy/linkmode.c (ffffffff8188602d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/sfp-bus.c (ffffffff8188846f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
  - drivers/net/phy/sfp-bus.c:sfp_quirk_2500basex
```
```
In drivers/net/phy/bcm84881.c (ffffffff818892b1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (ffffffff81889945)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In drivers/net/tun.c (ffffffff8188a966)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189f7f7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_bitmap_alloc_all
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In drivers/input/input.c (ffffffff81929ae1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_set_abs_params
  - drivers/input/input.c:input_set_abs_params
```
```
In drivers/input/input-mt.c (ffffffff8192cf62)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In drivers/input/ff-core.c (ffffffff8192d724)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81931a7e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/extcon/extcon.c (ffffffff819d2862)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In net/socket.c (ffffffff819dda1e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff819e6cd6)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data
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
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sk_set_memalloc
```
```
In net/core/dev.c (ffffffff81a0ae53)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/skmsg.c (ffffffff81a3c70c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/netlink/af_netlink.c (ffffffff81a79ac2)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ethtool/bitset.c (ffffffff81a8794b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aa432b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa622e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff81aae569)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff81ab890b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81ac198b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac4b82)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ad6d3a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff81adbc01)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b093c6)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
```
In net/unix/af_unix.c (ffffffff81b25668)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/unix/garbage.c (ffffffff81b29434)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: False
```
```
In net/ipv6/addrconf.c (ffffffff81b32ff2)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b771c4)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff81b8b5ef)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/rfkill/input.c (ffffffff81b98d28)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81ba6f6c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81ba9fbb)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_sk_clone
```
```
In net/mptcp/subflow.c (ffffffff81baef28)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:mptcp_sock_destruct
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
In arch/x86/events/core.c (ffffffff81007a8b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_pmu_start
```
```
In arch/x86/events/amd/core.c (ffffffff81009311)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_alloc_nb
```
```
In arch/x86/events/intel/core.c (ffffffff8100ef7d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_fixed
  - arch/x86/events/intel/core.c:intel_pmu_enable_fixed
  - arch/x86/events/intel/core.c:intel_pmu_enable_fixed
```
```
In arch/x86/events/intel/uncore.c (ffffffff810191f5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_assign_events
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101bf73)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101e721)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snr_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_uncore_pci_init_box
```
```
In arch/x86/hyperv/mmu.c (ffffffff81031b05)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8103276c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/signal.c (ffffffff810343dd)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:setup_rt_frame
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff8104c074)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81051b4c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81065426)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff8106934d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81072c71)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
```
```
In arch/x86/kernel/kvm.c (ffffffff8107e2ca)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In arch/x86/kernel/sev-es.c (ffffffff8108400d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/sev-es.c:vc_handle_exitcode
  - arch/x86/kernel/sev-es.c:vc_handle_exitcode
  - arch/x86/kernel/sev-es.c:vc_handle_exitcode
  - arch/x86/kernel/sev-es.c:vc_handle_exitcode
  - arch/x86/kernel/sev-es.c:vc_handle_vmmcall
  - arch/x86/kernel/sev-es.c:vc_handle_vmmcall
  - arch/x86/kernel/sev-es.c:vc_handle_dr7_write
  - arch/x86/kernel/sev-es.c:vc_do_mmio
  - arch/x86/kernel/sev-es.c:sev_es_ap_hlt_loop
  - arch/x86/kernel/sev-es.c:sev_es_ap_hlt_loop
  - arch/x86/kernel/sev-es.c:sev_es_ap_hlt_loop
  - arch/x86/kernel/sev-es.c:get_jump_table_addr
  - arch/x86/kernel/sev-es.c:get_jump_table_addr
  - arch/x86/kernel/sev-es.c:get_jump_table_addr
  - arch/x86/kernel/sev-es.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev-es.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev-es.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev-es.c:vc_handle_cpuid
  - arch/x86/kernel/sev-es.c:vc_handle_cpuid
  - arch/x86/kernel/sev-es.c:vc_handle_cpuid
  - arch/x86/kernel/sev-es.c:vc_handle_cpuid
  - arch/x86/kernel/sev-es.c:vc_handle_ioio
  - arch/x86/kernel/sev-es.c:vc_handle_ioio
  - arch/x86/kernel/sev-es.c:sev_es_ghcb_hv_call
  - arch/x86/kernel/sev-es.c:sev_es_ghcb_hv_call
  - arch/x86/kernel/sev-es.c:sev_es_ghcb_hv_call
```
```
In arch/x86/mm/tlb.c (ffffffff8108ba60)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_local
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In kernel/sysctl.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In kernel/workqueue.c (ffffffff810c3f62)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In kernel/sched/core.c (ffffffff810da3a8)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/rt.c (ffffffff810f649d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/sched/debug.c (ffffffff81105af7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/sched/debug.c:dirty_sched_domain_sysctl
```
```
In kernel/sched/membarrier.c (ffffffff81108f3c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/sched/membarrier.c:ipi_rseq
```
```
In kernel/sched/isolation.c (ffffffff82fdb6ec)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In kernel/irq/matrix.c (ffffffff8112af0e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In kernel/time/timer.c (ffffffff81140a24)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/smp.c (ffffffff8115b7f3)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/events/uprobes.c (ffffffff81251987)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In kernel/watch_queue.c (ffffffff812576ce)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_filter
```
```
In mm/filemap.c (ffffffff8125d4cb)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff8126a7c1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/shmem.c (ffffffff81278e8f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/percpu.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In mm/memory.c (ffffffff8129c7ab)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/memory.c:do_cow_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
```
```
In mm/rmap.c (ffffffff812b0304)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/page_alloc.c (ffffffff81c3e42b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/page_alloc.c:init_unavailable_range
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:reserve_bootmem_region
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/swap_state.c (ffffffff812c5120)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff812d3497)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:prep_compound_gigantic_page
```
```
In mm/sparse.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In mm/ksm.c (ffffffff812e292a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff812e4da3)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff812f2f82)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812f49a0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812fda07)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff81313d9f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/mapping_dirty_helpers.c (ffffffff81318681)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
```
```
In mm/page_reporting.c (ffffffff81318e5f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In fs/pipe.c (ffffffff8132a189)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_try_steal
```
```
In fs/inode.c (ffffffff81340334)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
```
```
In fs/file.c (ffffffff81344565)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:alloc_fd
  - fs/file.c:alloc_fd
  - fs/file.c:alloc_fd
```
```
In fs/io_uring.c (ffffffff8138f567)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:__io_uring_register
```
```
In fs/dax.c (ffffffff813a0037)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
```
```
In fs/iomap/buffered-io.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff813eb8d0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff814001f6)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
```
```
In fs/ext4/mballoc.c (ffffffff8141a6f4)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/ext4/super.c (ffffffff81445c44)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
```
```
In fs/hugetlbfs/inode.c (ffffffff8146e157)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff81488fcb)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_request_queue_background
  - fs/fuse/dev.c:fuse_request_queue_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_get_req
```
```
In security/integrity/ima/ima_template.c (ffffffff81537e99)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/scsi_ioctl.c (ffffffff81bf3732)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In block/blk-cgroup.c (ffffffff81585c79)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In lib/bitmap.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In lib/iommu-helper.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In lib/idr.c (ffffffff8160e620)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffff816129b5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff816206c4)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
```
```
In drivers/gpio/gpiolib.c (ffffffff816384ab)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8163a2b2)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_set_values_unlocked
```
```
In drivers/pwm/core.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In drivers/acpi/x86/apple.c (ffffffff816b9bce)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/pnp/quirks.c (ffffffff8171615b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff83003c93)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff817427e8)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
```
In drivers/tty/sysrq.c (ffffffff8175f935)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81786dc6)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In drivers/iommu/amd/iommu.c (ffffffff817a4e04)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:protection_domain_alloc
```
```
In drivers/iommu/amd/init.c (ffffffff8300a232)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:copy_device_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817b7441)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff818488a5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
```
In drivers/scsi/sr.c (ffffffff8185b15c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/net/phy/phy.c (ffffffff8188d8ce)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
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
In drivers/net/phy/phy-c45.c (ffffffff8188f6b0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
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
```
```
In drivers/net/phy/phy_device.c (ffffffff81893909)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:genphy_read_abilities
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
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
```
```
In drivers/net/phy/linkmode.c (ffffffff8189448d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/sfp-bus.c (ffffffff8189670f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
  - drivers/net/phy/sfp-bus.c:sfp_quirk_ubnt_uf_instant
  - drivers/net/phy/sfp-bus.c:sfp_quirk_2500basex
```
```
In drivers/net/phy/bcm84881.c (ffffffff81897521)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (ffffffff81897bb5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In drivers/net/tun.c (ffffffff81898b66)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_xdp
  - drivers/net/tun.c:tun_xdp
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818ae857)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_bitmap_alloc_all
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In drivers/input/input.c (ffffffff81931051)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_set_abs_params
  - drivers/input/input.c:input_set_abs_params
```
```
In drivers/input/input-mt.c (ffffffff81934386)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In drivers/input/ff-core.c (ffffffff81934af4)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81938cfe)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/extcon/extcon.c (ffffffff819d2442)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In net/socket.c (ffffffff819dd40e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff819e6506)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data
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
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sk_set_memalloc
```
```
In net/core/dev.c (ffffffff81a0c09f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/filter.c (ffffffff81a2ae1e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_setsockopt
```
```
In net/core/skmsg.c (ffffffff81a3eddc)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/netlink/af_netlink.c (ffffffff81a8297b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ethtool/bitset.c (ffffffff81a912cb)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aae96b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ab087e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff81ab832d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff81ac3c7b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad0512)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ae331a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff81ae85f1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b17be1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
```
In net/unix/af_unix.c (ffffffff81b34078)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/unix/garbage.c (ffffffff81b37d64)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: False
```
```
In net/ipv6/addrconf.c (ffffffff81b41912)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b85fa0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff81b9a5b9)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/rfkill/input.c (ffffffff81ba89f8)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81bb62ac)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81bb9df9)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
```
In net/mptcp/subflow.c (ffffffff81bc1ac1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:mptcp_sock_destruct
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
In arch/x86/events/core.c (ffffffff81006ae8)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_start
```
```
In arch/x86/events/amd/core.c (ffffffff81009d19)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/intel/core.c (ffffffff8100f75b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
```
```
In arch/x86/events/intel/p4.c (ffffffff81016a79)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101a515)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_assign_events
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101d323)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101fc31)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snr_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_uncore_pci_init_box
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff810218e1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_init_box
```
```
In arch/x86/hyperv/mmu.c (ffffffff8103261f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff81033561)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81033bbc)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/signal.c (ffffffff81035eef)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:handle_signal
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff8104dbb4)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81c292ee)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81065afa)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff81069dea)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810733af)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
```
```
In arch/x86/kernel/kvm.c (ffffffff8107f3e6)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In arch/x86/kernel/sev.c (ffffffff81084860)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_do_mmio
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev.c:vc_handle_ioio
  - arch/x86/kernel/sev.c:vc_handle_ioio
  - arch/x86/kernel/sev.c:sev_es_ghcb_hv_call
  - arch/x86/kernel/sev.c:sev_es_ghcb_hv_call
  - arch/x86/kernel/sev.c:sev_es_ghcb_hv_call
```
```
In arch/x86/mm/tlb.c (ffffffff8108c1e0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
```
```
In kernel/sysctl.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In kernel/workqueue.c (ffffffff810c57de)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In kernel/sched/core.c (ffffffff810dc9d4)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/rt.c (ffffffff810f84bd)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/sched/topology.c (ffffffff811032ff)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
```
```
In kernel/sched/debug.c (ffffffff81107a47)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/sched/debug.c:dirty_sched_domain_sysctl
```
```
In kernel/sched/membarrier.c (ffffffff8110aecc)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/sched/membarrier.c:ipi_rseq
```
```
In kernel/sched/isolation.c (ffffffff831e6446)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In kernel/irq/matrix.c (ffffffff8112b1ac)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In kernel/time/timer.c (ffffffff81141af9)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/smp.c (ffffffff8115c8d5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/events/uprobes.c (ffffffff812557b9)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In kernel/watch_queue.c (ffffffff8125bb57)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_filter
```
```
In mm/filemap.c (ffffffff8126014d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff8126f902)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/swap.c:__lru_add_drain_all
```
```
In mm/shmem.c (ffffffff8127de3f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/percpu.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In mm/memory.c (ffffffff812a1fc5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
```
```
In mm/rmap.c (ffffffff812b5904)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/page_alloc.c (ffffffff831f2876)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/page_alloc.c:init_unavailable_range
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_range
  - mm/page_alloc.c:reserve_bootmem_region
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/swap_state.c (ffffffff812cbdd5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff812da2de)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:prep_compound_gigantic_page
```
```
In mm/sparse.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In mm/ksm.c (ffffffff812ea0ba)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff812ec98a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff812f9302)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812faf30)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8130477b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff81319f4f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131e873)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
```
```
In mm/page_reporting.c (ffffffff8131f04c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In fs/pipe.c (ffffffff81330139)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_try_steal
```
```
In fs/inode.c (ffffffff8134685c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
```
```
In fs/file.c (ffffffff8134a905)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:alloc_fd
  - fs/file.c:alloc_fd
  - fs/file.c:alloc_fd
```
```
In fs/io_uring.c (ffffffff8139e92b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:__io_uring_register
```
```
In fs/dax.c (ffffffff813a75d4)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
```
```
In fs/iomap/buffered-io.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff813f1e10)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff81406691)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
```
```
In fs/ext4/mballoc.c (ffffffff81420ba3)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/ext4/super.c (ffffffff8144b50e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
```
```
In fs/hugetlbfs/inode.c (ffffffff81473599)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff8148e8d5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_get_req
```
```
In security/integrity/ima/ima_template.c (ffffffff81540500)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/scsi_ioctl.c (ffffffff81be569f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In block/blk-cgroup.c (ffffffff8158d009)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In lib/bitmap.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In lib/iommu-helper.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In lib/idr.c (ffffffff815f1dfc)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffff815f5f3b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff81603d05)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
```
```
In drivers/gpio/gpiolib.c (ffffffff8161bfee)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8161df24)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_set_values
```
```
In drivers/pwm/core.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In drivers/acpi/x86/apple.c (ffffffff8169baae)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/pnp/quirks.c (ffffffff816f746f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff8320e75e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff817261d8)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
```
In drivers/tty/sysrq.c (ffffffff81743795)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8176a726)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In drivers/iommu/amd/iommu.c (ffffffff817892dd)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_alloc
```
```
In drivers/iommu/amd/init.c (ffffffff83214d68)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:copy_device_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff8179b029)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff8182bc4a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
```
In drivers/scsi/sr.c (ffffffff8183e14f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/net/phy/phy.c (ffffffff8187020e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
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
In drivers/net/phy/phy-c45.c (ffffffff81871f78)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
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
```
```
In drivers/net/phy/phy_device.c (ffffffff818764f1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:genphy_read_abilities
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
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
```
```
In drivers/net/phy/linkmode.c (ffffffff81876d8d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/sfp-bus.c (ffffffff818792db)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
  - drivers/net/phy/sfp-bus.c:sfp_quirk_ubnt_uf_instant
  - drivers/net/phy/sfp-bus.c:sfp_quirk_2500basex
```
```
In drivers/net/phy/bcm84881.c (ffffffff81879d3c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8187a43f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In drivers/net/tun.c (ffffffff8187b2a6)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_xdp
  - drivers/net/tun.c:tun_xdp
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81892e82)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In drivers/input/input.c (ffffffff819142d1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_set_abs_params
  - drivers/input/input.c:input_set_abs_params
```
```
In drivers/input/input-mt.c (ffffffff819176f0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In drivers/input/ff-core.c (ffffffff81917e34)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8191c56e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/extcon/extcon.c (ffffffff819b7a44)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In net/socket.c (ffffffff819c3662)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff819cbf36)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data
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
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sk_set_memalloc
```
```
In net/core/dev.c (ffffffff819f2254)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/filter.c (ffffffff81a11ffb)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_setsockopt
```
```
In net/core/skmsg.c (ffffffff81a4d15c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/netlink/af_netlink.c (ffffffff81a6ba5b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ethtool/bitset.c (ffffffff81a7aace)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ethtool/fec.c (ffffffff81a81789)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ethtool/fec.c:fec_prepare_data
  - net/ethtool/fec.c:fec_prepare_data
  - net/ethtool/fec.c:fec_prepare_data
  - net/ethtool/fec.c:fec_prepare_data
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a99aeb)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9ba5e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff81aa3627)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff81aaed8b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abb652)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81aca127)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff81ad3881)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b057b1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
```
In net/unix/af_unix.c (ffffffff81b21bb8)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/unix/garbage.c (ffffffff81b25a04)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: False
```
```
In net/ipv6/addrconf.c (ffffffff81b2f602)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81b54c45)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_destroy_sock
```
```
In net/ipv6/ip6mr.c (ffffffff81b74c50)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff81b89528)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/rfkill/input.c (ffffffff81b97998)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81ba661c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81ba91d9)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
```
In net/mptcp/subflow.c (ffffffff81bb240a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:mptcp_sock_destruct
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb860c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
```
```
In net/mptcp/sockopt.c (ffffffff81bbc069)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
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
In arch/x86/events/core.c (ffffffff8100720a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_start
```
```
In arch/x86/events/amd/core.c (ffffffff8100adfc)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/intel/core.c (ffffffff8100fc0d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_fixed
  - arch/x86/events/intel/core.c:intel_pmu_enable_fixed
  - arch/x86/events/intel/core.c:intel_pmu_enable_fixed
```
```
In arch/x86/events/intel/p4.c (ffffffff810185cd)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101ce83)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_assign_events
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81020423)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81023081)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snr_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_uncore_pci_init_box
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff810254a1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_init_box
```
```
In arch/x86/hyperv/mmu.c (ffffffff810377ab)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff81038704)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81038f9b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/signal.c (ffffffff8103b170)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:handle_signal
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81055384)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81d47acb)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106fc1a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff8107447a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8107f843)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
```
```
In arch/x86/kernel/kvm.c (ffffffff8108e146)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In arch/x86/kernel/sev.c (ffffffff81093a20)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_do_mmio
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev.c:vc_handle_ioio
  - arch/x86/kernel/sev.c:vc_handle_ioio
  - arch/x86/kernel/sev.c:sev_es_ghcb_hv_call
  - arch/x86/kernel/sev.c:sev_es_ghcb_hv_call
  - arch/x86/kernel/sev.c:sev_es_ghcb_hv_call
```
```
In arch/x86/mm/tlb.c (ffffffff8109b9ed)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
```
```
In kernel/sysctl.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In kernel/workqueue.c (ffffffff810d83ca)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In kernel/sched/core.c (ffffffff810f14fc)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_cgroup_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/rt.c (ffffffff81113a84)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/sched/topology.c (ffffffff81120698)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:asym_cpu_capacity_scan
```
```
In kernel/sched/debug.c (ffffffff81125b37)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/sched/debug.c:dirty_sched_domain_sysctl
```
```
In kernel/sched/membarrier.c (ffffffff811296fb)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/sched/membarrier.c:ipi_rseq
```
```
In kernel/sched/isolation.c (ffffffff832ca542)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In kernel/irq/matrix.c (ffffffff8114bb8c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In kernel/time/timer.c (ffffffff811650e9)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/smp.c (ffffffff81181a4b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/cgroup/cpuset.c (ffffffff811a3540)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff8126e672)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_generic_redirect
```
```
In kernel/events/uprobes.c (ffffffff81291469)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In kernel/watch_queue.c (ffffffff81297a02)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_filter
```
```
In mm/filemap.c (ffffffff8129cadb)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff812aca92)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/swap.c:__lru_add_drain_all
```
```
In mm/shmem.c (ffffffff812bfeb9)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/percpu.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In mm/memory.c (ffffffff812e308e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
```
```
In mm/rmap.c (ffffffff812f7594)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/page_alloc.c (ffffffff832d8768)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/page_alloc.c:init_unavailable_range
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_range
  - mm/page_alloc.c:reserve_bootmem_region
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/swap_state.c (ffffffff81310f8b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff813211a1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:prep_compound_gigantic_page
```
```
In mm/sparse.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In mm/ksm.c (ffffffff81331fdc)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff81334b57)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In mm/kfence/core.c (ffffffff832dce34)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_init_pool
```
```
In mm/migrate.c (ffffffff813404e3)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff81344d99)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8134e4b0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/secretmem.c (ffffffff8136674c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff81367049)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/mapping_dirty_helpers.c (ffffffff8136bc53)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
```
```
In mm/page_reporting.c (ffffffff8136c41c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In fs/pipe.c (ffffffff8137d8f6)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_try_steal
```
```
In fs/inode.c (ffffffff81394296)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
```
```
In fs/file.c (ffffffff813986b5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:alloc_fd
  - fs/file.c:alloc_fd
  - fs/file.c:alloc_fd
```
```
In fs/io_uring.c (ffffffff813eec86)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:__io_uring_register
```
```
In fs/dax.c (ffffffff813f4d2c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
```
```
In fs/iomap/buffered-io.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff81443e44)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff81458f06)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
```
```
In fs/ext4/mballoc.c (ffffffff81473fa7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/ext4/super.c (ffffffff8149f472)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
```
```
In fs/hugetlbfs/inode.c (ffffffff814ca196)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff814e6345)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_get_req
```
```
In security/integrity/ima/ima_template.c (ffffffff8159fd3f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/blk-cgroup.c (ffffffff815f2977)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In lib/bitmap.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In lib/iommu-helper.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In lib/idr.c (ffffffff8165f0a9)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffff81663445)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff8166fee1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - lib/xarray.c:xas_squash_marks
```
```
In drivers/gpio/gpiolib.c (ffffffff8168b50c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8168d639)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_set_values_unlocked
```
```
In drivers/pwm/core.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In drivers/acpi/x86/apple.c (ffffffff81711963)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/pnp/quirks.c (ffffffff81771c0f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff832f74f1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff817a51b8)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
```
In drivers/tty/sysrq.c (ffffffff817c43c9)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff817ef9c1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In drivers/iommu/amd/iommu.c (ffffffff8180f153)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_alloc
```
```
In drivers/iommu/amd/init.c (ffffffff832fe4f6)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:copy_device_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81823b59)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b77fe)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
```
In drivers/scsi/sr.c (ffffffff818cac17)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/net/phy/phy.c (ffffffff819007ee)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
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
In drivers/net/phy/phy-c45.c (ffffffff81902578)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
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
```
```
In drivers/net/phy/phy_device.c (ffffffff81907101)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:genphy_read_abilities
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
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
```
```
In drivers/net/phy/linkmode.c (ffffffff8190799d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/sfp-bus.c (ffffffff8190a13b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
  - drivers/net/phy/sfp-bus.c:sfp_quirk_ubnt_uf_instant
  - drivers/net/phy/sfp-bus.c:sfp_quirk_2500basex
```
```
In drivers/net/phy/bcm84881.c (ffffffff8190adc3)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8190b53f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In drivers/net/tun.c (ffffffff8190caa6)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_xdp
  - drivers/net/tun.c:tun_xdp
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81925d7f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_populate_bitmap
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In drivers/input/input.c (ffffffff819b63c8)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_set_abs_params
  - drivers/input/input.c:input_set_abs_params
```
```
In drivers/input/input-mt.c (ffffffff819b9960)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In drivers/input/ff-core.c (ffffffff819ba0a4)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (ffffffff819bee45)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/extcon/extcon.c (ffffffff81a66892)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In net/socket.c (ffffffff81a72ef2)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81a7b596)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_init_data
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
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_set_timestamping
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sk_set_memalloc
```
```
In net/core/dev.c (ffffffff81aa4124)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/filter.c (ffffffff81acd36c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_setsockopt
```
```
In net/core/skmsg.c (ffffffff81b0587e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/netlink/af_netlink.c (ffffffff81b2508b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ethtool/bitset.c (ffffffff81b34eec)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ethtool/fec.c (ffffffff81b3b4d0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ethtool/fec.c:fec_prepare_data
  - net/ethtool/fec.c:fec_prepare_data
  - net/ethtool/fec.c:fec_prepare_data
  - net/ethtool/fec.c:fec_prepare_data
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b54f58)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b5707e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff81b5f7c7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff81b6ba6b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b78867)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81b889a7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff81b92525)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff81bc830e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
```
In net/unix/af_unix.c (ffffffff81be70e8)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/unix/garbage.c (ffffffff81beb143)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: False
```
```
In net/ipv6/addrconf.c (ffffffff81bf5982)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81c1b505)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_destroy_sock
```
```
In net/ipv6/ip6mr.c (ffffffff81c3f55c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff81c55638)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/rfkill/input.c (ffffffff81c642bf)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81c7416c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81c78e39)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
```
In net/mptcp/subflow.c (ffffffff81c8066e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:mptcp_sock_destruct
```
```
In net/mptcp/pm_netlink.c (ffffffff81c883bc)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
```
```
In net/mptcp/sockopt.c (ffffffff81c8bc09)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
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
In arch/x86/events/core.c (ffffffff81006727)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_start
```
```
In arch/x86/events/amd/core.c (ffffffff8100a504)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/intel/core.c (ffffffff810111bb)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_fixed
  - arch/x86/events/intel/core.c:intel_pmu_enable_fixed
  - arch/x86/events/intel/core.c:intel_pmu_enable_fixed
```
```
In arch/x86/events/intel/p4.c (ffffffff8101a77d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101f6a5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_assign_events
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff810233a3)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81026a41)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snr_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_uncore_pci_init_box
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81029381)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_init_box
```
```
In arch/x86/hyperv/mmu.c (ffffffff8103d9b8)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff8103e98e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/ivm.c (ffffffff8103ee0b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_read
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_read
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_read
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_read
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8103fd84)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/signal.c (ffffffff810420f9)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:handle_signal
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff810612c0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8107d4a2)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff81082cda)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8108ecc3)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
```
```
In arch/x86/kernel/kvm.c (ffffffff8109e946)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In arch/x86/kernel/sev.c (ffffffff810a3d20)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:snp_issue_guest_request
  - arch/x86/kernel/sev.c:snp_issue_guest_request
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_do_mmio
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:vmgexit_psc
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev.c:vc_handle_ioio
  - arch/x86/kernel/sev.c:vc_handle_ioio
  - arch/x86/kernel/sev.c:sev_es_ghcb_hv_call
  - arch/x86/kernel/sev.c:sev_es_ghcb_hv_call
  - arch/x86/kernel/sev.c:sev_es_ghcb_hv_call
```
```
In arch/x86/mm/tlb.c (ffffffff810ae06f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In kernel/workqueue.c (ffffffff810f3111)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In kernel/sched/core.c (ffffffff8110d8ec)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_cgroup_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/build_policy.c (ffffffff81131129)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:init_rt_rq
```
```
In kernel/sched/build_utility.c (ffffffff8347d6e5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:membarrier_global_expedited
  - kernel/sched/build_utility.c:ipi_rseq
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:asym_cpu_capacity_scan
  - kernel/sched/build_utility.c:cpu_attach_domain
```
```
In kernel/irq/irqdesc.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In kernel/irq/matrix.c (ffffffff8117152b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In kernel/time/timer.c (ffffffff81198d29)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/smp.c (ffffffff811b80a7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/cgroup/cpuset.c (ffffffff811d4688)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff812bd580)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_generic_redirect
```
```
In kernel/events/uprobes.c (ffffffff812e6a57)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In kernel/watch_queue.c (ffffffff812edcca)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_filter
```
```
In mm/filemap.c (ffffffff812f3e21)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:filemap_add_folio
```
```
In mm/swap.c (ffffffff81302f24)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/swap.c:__lru_add_drain_all
```
```
In mm/shmem.c (ffffffff8131c797)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_alloc_and_acct_folio
```
```
In mm/percpu.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In mm/memory.c (ffffffff813439e5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_present_pte
```
```
In mm/rmap.c (ffffffff8135d019)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/page_alloc.c (ffffffff8348ccbe)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/page_alloc.c:init_unavailable_range
  - mm/page_alloc.c:memmap_init_compound
  - mm/page_alloc.c:__init_zone_device_page
  - mm/page_alloc.c:memmap_init_range
  - mm/page_alloc.c:reserve_bootmem_region
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/swap_state.c (ffffffff8137bdf2)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff8138df84)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:__prep_compound_gigantic_page
```
```
In mm/sparse.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In mm/ksm.c (ffffffff813a333e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff813a633b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
```
In mm/kfence/core.c (ffffffff813aef18)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_init_pool
```
```
In mm/migrate.c (ffffffff813b1f8b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/migrate_device.c (ffffffff813b7e0f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In mm/huge_memory.c (ffffffff813ba0a7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff813c4bc4)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/secretmem.c (ffffffff813e3a5c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff813e45b6)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/mapping_dirty_helpers.c (ffffffff813e9e19)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
```
```
In mm/page_reporting.c (ffffffff813ea71a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In fs/pipe.c (ffffffff813fe615)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_try_steal
```
```
In fs/file.c (ffffffff8141ae0a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:alloc_fd
  - fs/file.c:alloc_fd
  - fs/file.c:alloc_fd
```
```
In fs/dax.c (ffffffff814678ad)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
```
```
In fs/iomap/buffered-io.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff814bfd20)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff814d70e7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff814f601a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_set_bits
```
```
In fs/ext4/super.c (ffffffff81525d12)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
```
```
In fs/hugetlbfs/inode.c (ffffffff81555eb5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff81574ecd)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_get_req
```
```
In security/integrity/ima/ima_template.c (ffffffff8164593a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/blk-cgroup.c (ffffffff816a343c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In io_uring/io_uring.c (ffffffff81e8f32f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_register_restrictions
  - io_uring/io_uring.c:io_register_restrictions
  - io_uring/io_uring.c:__io_sqe_files_update
  - io_uring/io_uring.c:io_fixed_fd_install
```
```
In lib/bitmap.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In lib/iommu-helper.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In lib/idr.c (ffffffff81778915)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffff8177d4ee)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/vsprintf.c (ffffffff8178481f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
```
```
In lib/xarray.c (ffffffff8178cae4)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
```
```
In drivers/gpio/gpiolib.c (ffffffff817a8812)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff817ad013)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_set_values_unlocked
  - drivers/gpio/gpiolib-cdev.c:linehandle_ioctl
```
```
In drivers/pwm/core.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In drivers/acpi/x86/apple.c (ffffffff81840a1a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/pnp/quirks.c (ffffffff818a72dd)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff834afb40)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/xen/grant-table.c (ffffffff818c7191)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:put_free_entry_locked
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff818def16)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
```
In drivers/tty/sysrq.c (ffffffff819010d6)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8192f756)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_set
```
```
In drivers/iommu/amd/iommu.c (ffffffff8194df64)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_alloc
```
```
In drivers/iommu/amd/init.c (ffffffff834b712d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:copy_device_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81962fd4)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81a02f74)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
```
```
In drivers/scsi/sr.c (ffffffff81a17c4e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/net/phy/phy.c (ffffffff81a525ee)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
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
In drivers/net/phy/phy-c45.c (ffffffff81a54396)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
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
In drivers/net/phy/phy_device.c (ffffffff81a5a380)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:genphy_read_abilities
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
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
```
```
In drivers/net/phy/linkmode.c (ffffffff81a5aa1d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81a5d877)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
  - drivers/net/phy/sfp-bus.c:sfp_quirk_ubnt_uf_instant
  - drivers/net/phy/sfp-bus.c:sfp_quirk_2500basex
```
```
In drivers/net/phy/bcm84881.c (ffffffff81a5e770)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
```
```
In drivers/net/phy/fixed_phy.c (ffffffff81a5ed6e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In drivers/net/tun.c (ffffffff81a61384)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_xdp
  - drivers/net/tun.c:tun_xdp
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a7c834)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_populate_bitmap
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In drivers/input/input.c (ffffffff81b15bf7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_copy_abs
  - drivers/input/input.c:input_copy_abs
  - drivers/input/input.c:input_set_abs_params
  - drivers/input/input.c:input_set_abs_params
```
```
In drivers/input/input-mt.c (ffffffff81b19645)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_init_slots
  - drivers/input/input-mt.c:input_mt_init_slots
  - drivers/input/input-mt.c:input_mt_init_slots
  - drivers/input/input-mt.c:input_mt_init_slots
  - drivers/input/input-mt.c:input_mt_init_slots
  - drivers/input/input-mt.c:input_mt_init_slots
  - drivers/input/input-mt.c:input_mt_init_slots
  - drivers/input/input-mt.c:input_mt_init_slots
  - drivers/input/input-mt.c:input_mt_init_slots
  - drivers/input/input-mt.c:input_mt_init_slots
  - drivers/input/input-mt.c:copy_abs
```
```
In drivers/input/ff-core.c (ffffffff81b1a0a2)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81b1f0a5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/extcon/extcon.c (ffffffff81bd7da5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
```
```
In net/socket.c (ffffffff81be5773)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81befe83)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_gettstamp
  - net/core/sock.c:sock_init_data
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
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_set_timestamping
  - net/core/sock.c:sock_set_timestamping
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sk_set_memalloc
```
```
In net/core/dev.c (ffffffff81c13fef)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev.c:__dev_alloc_name
```
```
In net/core/filter.c (ffffffff81c4ac7f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_setsockopt
```
```
In net/core/gro.c (ffffffff81c54300)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
```
```
In net/core/net-sysfs.c (ffffffff81c55bf1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_queue_show
```
```
In net/core/skmsg.c (ffffffff81c8aee7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/netlink/af_netlink.c (ffffffff81cae0ed)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ethtool/bitset.c (ffffffff81cc06da)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ethtool/fec.c (ffffffff81cc74c3)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ethtool/fec.c:fec_prepare_data
  - net/ethtool/fec.c:fec_prepare_data
  - net/ethtool/fec.c:fec_prepare_data
  - net/ethtool/fec.c:fec_prepare_data
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce2b20)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce4fed)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff81cee27f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff81cfabdb)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
```
```
In net/ipv4/tcp_ipv4.c (ffffffff834cc2e1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
```
```
In net/ipv4/raw.c (ffffffff81d15976)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff81d19e67)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff834cc958)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_init
```
```
In net/ipv4/ping.c (ffffffff81d439d4)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5dba9)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
```
In net/unix/af_unix.c (ffffffff81d7e719)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/unix/garbage.c (ffffffff81d83447)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81d8eb39)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_get_saddr_eval
```
```
In net/ipv6/udp.c (ffffffff81db7c34)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_destroy_sock
```
```
In net/ipv6/ip6mr.c (ffffffff81ddda4c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff81df53c8)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/rfkill/input.c (ffffffff81e06fa3)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81e17a1c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81e1d9e9)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:__mptcp_check_push
  - net/mptcp/protocol.c:__mptcp_data_acked
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:mptcp_retransmit_timer
  - net/mptcp/protocol.c:mptcp_data_ready
```
```
In net/mptcp/subflow.c (ffffffff81e27dad)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:mptcp_sock_destruct
  - net/mptcp/subflow.c:mptcp_set_connected
```
```
In net/mptcp/pm.c (ffffffff81e2d383)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_mp_prio_received
```
```
In net/mptcp/pm_netlink.c (ffffffff81e2f4fa)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
```
```
In net/mptcp/sockopt.c (ffffffff81e3328c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
```
```
In net/mptcp/pm_userspace.c (ffffffff81e35284)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr
```
```
In net/mctp/af_mctp.c (ffffffff81e37a39)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:25
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_pf_create
```
</details>
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
In arch/arm64/kernel/signal.c (ffff800010093500)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - arch/arm64/kernel/signal.c:do_notify_resume
```
```
In arch/arm64/kernel/cpufeature.c (ffff800010099e40)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - arch/arm64/kernel/cpufeature.c:update_cpu_capabilities
```
```
In arch/arm64/mm/context.c (ffff8000100afe18)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - arch/arm64/mm/context.c:check_and_switch_context
  - arch/arm64/mm/context.c:check_and_switch_context
```
```
In virt/kvm/kvm_main.c (ffff8000100bc77c)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:kvm_make_vcpus_request_mask
```
```
In kernel/sysctl.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In kernel/workqueue.c (ffff80001011e8ac)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In kernel/sched/core.c (ffff800010da160c)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/rt.c (ffff80001014f788)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/sched/debug.c (ffff800010161f30)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - kernel/sched/debug.c:dirty_sched_domain_sysctl
```
```
In kernel/sched/membarrier.c (ffff8000101662ec)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__arm64_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_private_expedited
```
```
In kernel/sched/isolation.c (ffff8000114454f0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In kernel/time/timer.c (ffff80001019e2f0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/smp.c (ffff8000101bd804)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/events/uprobes.c (ffff8000102a5cd8)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffff8000102b13ec)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/shmem.c (ffff8000102d2f64)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/percpu.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In mm/memory.c (ffff8000102f9658)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
```
In mm/rmap.c (ffff800010309534)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/page_alloc.c (ffff8000103134fc)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:reserve_bootmem_region
```
```
In mm/swap_state.c (ffff800010321b70)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffff800010332e40)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:prep_compound_gigantic_page
```
```
In mm/sparse.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In mm/ksm.c (ffff800010342074)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffff800010345c94)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffff800010352e40)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffff80001035886c)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffff80001035d284)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/cma.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In mm/userfaultfd.c (ffff800010378014)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/pipe.c (ffff80001038fba8)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
```
```
In fs/file.c (ffff8000103b0fd0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
```
```
In fs/dax.c (ffff80001040a1d8)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In fs/ext4/balloc.c (ffff800010460bd0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffff800010475220)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/mballoc.c (ffff800010492cac)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/ext4/super.c (ffff8000104bdf6c)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
```
```
In fs/hugetlbfs/inode.c (ffff8000104e25f4)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffff800010502658)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_request_alloc
```
```
In security/integrity/ima/ima_template.c (ffff8000105b2e58)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/scsi_ioctl.c (ffff80001146f000)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
```
```
In block/blk-cgroup.c (ffff80001060d558)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In lib/bitmap.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff800010672938)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_affinity
```
```
In drivers/irqchip/irq-mvebu-gicp.c (ffff800010678fb4)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-gicp.c:gicp_irq_domain_alloc
```
```
In drivers/irqchip/irq-mvebu-odmi.c (ffff800010679b0c)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-odmi.c:odmi_irq_domain_alloc
```
```
In drivers/irqchip/irq-ls-scfg-msi.c (ffff80001067afa4)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_remove
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_domain_irq_alloc
```
```
In drivers/gpio/gpiolib.c (ffff8000106c5078)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/pwm/core.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In drivers/pci/controller/pci-aardvark.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In drivers/pci/controller/pci-xgene-msi.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In drivers/pci/controller/pcie-iproc-msi.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In drivers/pci/controller/pcie-mediatek.c (ffff80001072a30c)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_irq_domain_alloc
```
```
In drivers/pnp/quirks.c (ffff8000107b783c)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffff800011482adc)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/soc/qcom/rpmh-rsc.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In drivers/tty/sysrq.c (ffff8000108648b4)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffff8000108a7aa0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In drivers/scsi/sr.c (ffff80001098c8fc)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/net/phy/phy.c (ffff8000109d11ec)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
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
In drivers/net/phy/phy-c45.c (ffff8000109d2464)
Location: include/asm-generic/bitops/non-atomic.h:16
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
In drivers/net/phy/phy_device.c (ffff8000109d6364)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
```
```
In drivers/net/phy/sfp-bus.c (ffff8000109d97e4)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
```
```
In drivers/net/phy/fixed_phy.c (ffff8000109da3c0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In drivers/net/tun.c (ffff8000109dad84)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In drivers/input/input.c (ffff800010a97500)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_set_abs_params
  - drivers/input/input.c:input_set_abs_params
```
```
In drivers/input/input-mt.c (ffff800010a9a360)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In drivers/input/ff-core.c (ffff800010a9abc4)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (ffff800010aa1370)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
```
```
In drivers/extcon/extcon.c (ffff800010b87c58)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
```
```
In net/socket.c (ffff800010ba0dc4)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffff800010bada70)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_init_data
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
  - net/core/sock.c:sk_set_memalloc
```
```
In net/core/dev.c (ffff800010bd4768)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/netlink/af_netlink.c (ffff800010c4f070)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffff800010c6af64)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6c92c)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffff800010c75c5c)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffff800010c7e55c)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffff800010c87be8)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8b044)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In net/ipv4/udp.c (ffff800010c9bfc8)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/icmp.c (ffff800010ca39ac)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In net/unix/af_unix.c (ffff800010cf1184)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/unix/garbage.c (ffff800010cf4c64)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: False
```
```
In net/ipv6/addrconf.c (ffff800010cff1c4)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In net/ipv6/ip6mr.c (ffff800010d467f4)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffff800010d5c428)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/rfkill/input.c (ffff800010d6def0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In net/xdp/xsk.c (ffff800010d7e6ac)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In lib/idr.c (ffff800010d88f88)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffff800010d8e0c0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffff800010d9a858)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In arch/arm/kernel/signal.c (c030e824)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - arch/arm/kernel/signal.c:do_work_pending
```
```
In arch/arm/mm/dma-mapping.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In arch/arm/mm/context.c (c03224a0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - arch/arm/mm/context.c:check_and_switch_context
  - arch/arm/mm/context.c:check_and_switch_context
```
```
In kernel/sysctl.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In kernel/workqueue.c (c0373654)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:__flush_work
```
```
In kernel/sched/core.c (c0e99734)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/rt.c (c039cf5c)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/sched/debug.c (c03ae740)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - kernel/sched/debug.c:dirty_sched_domain_sysctl
```
```
In kernel/sched/membarrier.c (c03b280c)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__se_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_private_expedited
```
```
In kernel/sched/isolation.c (c151f610)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In kernel/time/timer.c (c03e7668)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/smp.c (c0405ad8)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/events/uprobes.c (c04d50a4)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (c04ddccc)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/shmem.c (c04fae98)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/percpu.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In mm/memory.c (c051b794)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
```
In mm/rmap.c (c0526160)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/page_alloc.c (c15bdd68)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:reserve_bootmem_region
```
```
In mm/swap_state.c (c053a298)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/ksm.c (c0547dd4)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (c0549a24)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (c0550f88)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:isolate_movable_page
```
```
In mm/cma.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In mm/userfaultfd.c (c0563804)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/pipe.c (c057680c)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
```
```
In fs/file.c (c0590ab4)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
```
```
In fs/ext4/balloc.c (c0621298)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (c0636888)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/mballoc.c (c0653fe8)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/ext4/super.c (c06817d8)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
```
```
In fs/fuse/dev.c (c06bf78c)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_retrieve
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_request_alloc
```
```
In security/integrity/ima/ima_template.c (c0762424)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/scsi_ioctl.c (c1547f64)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
```
```
In block/blk-cgroup.c (c07b815c)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In lib/bitmap.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In drivers/irqchip/irq-alpine-msi.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In drivers/irqchip/irq-gic-v3-its.c (c081ad88)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_affinity
```
```
In drivers/irqchip/irq-armada-370-xp.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In drivers/gpio/gpiolib.c (c08631cc)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/pwm/core.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In drivers/pci/controller/pcie-mediatek.c (c08b5110)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_irq_domain_alloc
```
```
In drivers/dma/ti/edma.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In drivers/tty/sysrq.c (c096a2d4)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (c09a46c8)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In drivers/scsi/sr.c (c0a5ee84)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/mtd/nand/raw/nand_onfi.c (c0aa66f8)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/nand_onfi.c:nand_onfi_detect
  - drivers/mtd/nand/raw/nand_onfi.c:nand_onfi_detect
```
```
In drivers/mtd/nand/raw/nand_macronix.c (c0aa7ab0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In drivers/net/phy/phy.c (c0ab8f0c)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
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
In drivers/net/phy/phy-c45.c (c0aba5a8)
Location: include/asm-generic/bitops/non-atomic.h:16
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
In drivers/net/phy/phy_device.c (c0abdcbc)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
```
```
In drivers/net/phy/sfp-bus.c (c0ac03d8)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
```
```
In drivers/net/phy/fixed_phy.c (c0ac0f94)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In drivers/net/tun.c (c0ac1ca8)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In drivers/input/input.c (c0b7a608)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_set_abs_params
  - drivers/input/input.c:input_set_abs_params
```
```
In drivers/input/input-mt.c (c0b7bfb0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In drivers/input/ff-core.c (c0b7cbc4)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (c0b8114c)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/extcon/extcon.c (c0c6cc20)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In net/socket.c (c0cc30f8)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (c0ccb5f8)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_init_data
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
  - net/core/sock.c:sk_set_memalloc
```
```
In net/core/dev.c (c0ceed30)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/netlink/af_netlink.c (c0d5b364)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (c0d7a02c)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (c0d7be30)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (c0d842f4)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (c0d8d580)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (c0d96f38)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_ipv4.c (c0d9b2e8)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In net/ipv4/udp.c (c0da86f0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (c0db0650)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In net/unix/af_unix.c (c0df823c)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/unix/garbage.c (c0dfb8c4)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: False
```
```
In net/ipv6/addrconf.c (c0e07224)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In net/ipv6/ip6mr.c (c0e48f60)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (c0e5c444)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/rfkill/input.c (c0e6b790)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In net/xdp/xsk.c (c0e790b0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In lib/idr.c (c0e84000)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (c0e887c0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (c0e97688)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In arch/powerpc/kernel/signal.c (c0000000000238b8)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - arch/powerpc/kernel/signal.c:do_notify_resume
```
```
In arch/powerpc/kernel/iommu.c (c000000000052a80)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - arch/powerpc/kernel/iommu.c:iommu_init_table
```
```
In arch/powerpc/mm/slice.c (c0000000000a498c)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - arch/powerpc/mm/slice.c:slice_get_unmapped_area
  - arch/powerpc/mm/slice.c:slice_convert
```
```
In arch/powerpc/sysdev/mpic.c (c000000001358764)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - arch/powerpc/sysdev/mpic.c:mpic_alloc
```
```
In arch/powerpc/sysdev/msi_bitmap.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In arch/powerpc/platforms/powernv/pci-ioda.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In kernel/workqueue.c (c0000000001698cc)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In kernel/sched/core.c (c000000000ee2690)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/rt.c (c0000000001a2dfc)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/sched/debug.c (c0000000001b8230)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - kernel/sched/debug.c:dirty_sched_domain_sysctl
```
```
In kernel/sched/membarrier.c (c0000000001bd30c)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/sched/isolation.c (c000000001369f68)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In kernel/time/timer.c (c0000000001fc2c0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/smp.c (c000000000223ca0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/events/uprobes.c (c000000000358d28)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (c0000000003669e0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/shmem.c (c000000000391928)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/percpu.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In mm/memory.c (c0000000003c33c0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
```
In mm/rmap.c (c0000000003d8af8)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/page_alloc.c (c0000000003ee9e8)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:reserve_bootmem_region
```
```
In mm/swap_state.c (c0000000003f7340)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (c00000000040ed48)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:prep_compound_gigantic_page
```
```
In mm/sparse.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In mm/ksm.c (c00000000041f8d4)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (c000000000422364)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (c0000000004399cc)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (c000000000441610)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (c000000000448630)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/cma.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In mm/userfaultfd.c (c00000000046a7a8)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/pipe.c (c000000000487880)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
```
```
In fs/file.c (c0000000004acc64)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
```
```
In fs/dax.c (c0000000005161e0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In fs/ext4/balloc.c (c00000000057d150)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (c000000000596c20)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/mballoc.c (c0000000005bb3b4)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/ext4/super.c (c0000000005f4344)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
```
```
In fs/hugetlbfs/inode.c (c00000000061f6f0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (c00000000064a120)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_request_alloc
```
```
In security/integrity/ima/ima_template.c (c000000000735468)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/scsi_ioctl.c (c00000000139f000)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
```
```
In block/blk-cgroup.c (c0000000007aa644)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In lib/bitmap.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In lib/iommu-helper.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In drivers/gpio/gpiolib.c (c000000000841c30)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/pwm/core.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In drivers/tty/sysrq.c (c0000000009039a0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (c00000000093e5c0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In drivers/scsi/sr.c (c000000000a4df10)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/net/phy/phy.c (c000000000a90a7c)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
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
In drivers/net/phy/phy-c45.c (c000000000a924a0)
Location: include/asm-generic/bitops/non-atomic.h:16
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
In drivers/net/phy/phy_device.c (c000000000a97a38)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
```
```
In drivers/net/phy/sfp-bus.c (c000000000a9b32c)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
```
```
In drivers/net/phy/fixed_phy.c (c000000000a9c340)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In drivers/net/tun.c (c000000000a9d2e8)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In drivers/input/input.c (c000000000b78080)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_set_abs_params
  - drivers/input/input.c:input_set_abs_params
```
```
In drivers/input/input-mt.c (c000000000b7a3cc)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In drivers/input/ff-core.c (c000000000b7b6b0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (c000000000b81948)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/extcon/extcon.c (c000000000c67b70)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In net/socket.c (c000000000c74d94)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (c000000000c8339c)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_init_data
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
  - net/core/sock.c:sk_set_memalloc
```
```
In net/core/dev.c (c000000000cb3828)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/netlink/af_netlink.c (c000000000d487a0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (c000000000d70334)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (c000000000d72c20)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (c000000000d7d504)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (c000000000d887cc)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (c000000000d948d0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_ipv4.c (c000000000d99ca8)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In net/ipv4/udp.c (c000000000dae03c)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (c000000000db7298)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In net/unix/af_unix.c (c000000000e16130)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/unix/garbage.c (c000000000e1acc4)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: False
```
```
In net/ipv6/addrconf.c (c000000000e28844)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In net/ipv6/ip6mr.c (c000000000e7c518)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (c000000000e97f00)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/rfkill/input.c (c000000000eab7a0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In net/xdp/xsk.c (c000000000ebe6b8)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In lib/idr.c (c000000000ec9b94)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (c000000000ed0b70)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (c000000000ee0f74)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In arch/riscv/net/bpf_jit_comp.c (ffffffe0000bdd72)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - arch/riscv/net/bpf_jit_comp.c:build_prologue
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
  - arch/riscv/net/bpf_jit_comp.c:emit_bpf_tail_call
  - arch/riscv/net/bpf_jit_comp.c:emit_bpf_tail_call
```
```
In kernel/sysctl.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In kernel/workqueue.c (ffffffe0000d8032)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In kernel/sched/rt.c (ffffffe0000f806a)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/sched/debug.c (ffffffe000105ca4)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - kernel/sched/debug.c:dirty_sched_domain_sysctl
```
```
In kernel/sched/membarrier.c (ffffffe000108684)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__se_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_private_expedited
```
```
In kernel/sched/isolation.c (ffffffe00000728c)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In kernel/time/timer.c (ffffffe00012bea4)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/smp.c (ffffffe000140cdc)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_many
```
```
In mm/filemap.c (ffffffe0001d6b52)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/shmem.c (ffffffe0001ee1d0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/percpu.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In mm/memory.c (ffffffe00020962a)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
```
In mm/rmap.c (ffffffe000213936)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/page_alloc.c (ffffffe0000470f8)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:reserve_bootmem_region
```
```
In mm/swap_state.c (ffffffe000222cb6)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffe00022f528)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:prep_compound_gigantic_page
```
```
In mm/sparse.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In mm/ksm.c (ffffffe00023632c)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffe00023840c)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffe00023ea7e)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:isolate_movable_page
```
```
In mm/cma.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In mm/userfaultfd.c (ffffffe00024fbee)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/pipe.c (ffffffe00025f7c6)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
```
```
In fs/file.c (ffffffe0002754e2)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
```
```
In fs/dax.c (ffffffe0002b3b22)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In fs/ext4/balloc.c (ffffffe0002eff4e)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffe000300bf4)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/mballoc.c (ffffffe000317866)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/ext4/super.c (ffffffe000339998)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
```
```
In fs/hugetlbfs/inode.c (ffffffe000356072)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffe000371972)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_request_alloc
```
```
In security/integrity/ima/ima_template.c (ffffffe0003fa52e)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/scsi_ioctl.c (ffffffe0000295a6)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
```
```
In block/blk-cgroup.c (ffffffe000445e54)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In lib/bitmap.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffe0004a9470)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/pwm/core.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In drivers/tty/sysrq.c (ffffffe00053af7c)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffe00055e3a2)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In drivers/scsi/sr.c (ffffffe0005f1408)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/net/phy/phy.c (ffffffe00061d47c)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
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
In drivers/net/phy/phy-c45.c (ffffffe00061ed90)
Location: include/asm-generic/bitops/non-atomic.h:16
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
In drivers/net/phy/phy_device.c (ffffffe00062265c)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
```
```
In drivers/net/phy/sfp-bus.c (ffffffe000624720)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
```
```
In drivers/net/phy/fixed_phy.c (ffffffe0006251ca)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In drivers/net/tun.c (ffffffe000625cde)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In drivers/input/input.c (ffffffe0006a8a68)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_set_abs_params
  - drivers/input/input.c:input_set_abs_params
```
```
In drivers/input/input-mt.c (ffffffe0006aacc0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In drivers/input/ff-core.c (ffffffe0006ab6ae)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (ffffffe0006af436)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/extcon/extcon.c (ffffffe00073123c)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In net/socket.c (ffffffe000738b28)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffe00073fc86)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_init_data
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
  - net/core/sock.c:sk_set_memalloc
```
```
In net/core/dev.c (ffffffe00075e5b2)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/netlink/af_netlink.c (ffffffe0007b7ba0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffe0007d0c54)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d2284)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffe0007d8e48)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffe0007e0914)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffe0007e8eea)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ecc86)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In net/ipv4/udp.c (ffffffe0007fb022)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffe0007ff7b6)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In net/unix/af_unix.c (ffffffe00083d40e)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/unix/garbage.c (ffffffe00084094c)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (0)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: False
```
```
In net/ipv6/addrconf.c (ffffffe000849b92)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffe0008813ce)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffe0008925c8)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/rfkill/input.c (ffffffe00089f890)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
```
```
In net/xdp/xsk.c (ffffffe0008ac092)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In lib/idr.c (ffffffe0008b2ed8)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffe0008b6d1a)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffe0008c2dfa)
Location: include/asm-generic/bitops/non-atomic.h:16
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In arch/x86/events/core.c (ffffffff8100796b)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_pmu_start
```
```
In arch/x86/events/amd/core.c (ffffffff810094b2)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016525)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_assign_events
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101a133)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101cb41)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snr_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_uncore_pci_init_box
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102e90d)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f690)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
```
```
In arch/x86/kernel/signal.c (ffffffff81031189)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81048c54)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e082)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81061166)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106b310)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
```
```
In arch/x86/kernel/kvm.c (ffffffff8107690d)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077a7d)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff81087450)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828b01fb)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
```
In kernel/sysctl.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In kernel/workqueue.c (ffffffff810bccb9)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:__flush_work
```
```
In kernel/sched/core.c (ffffffff81a6e848)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/rt.c (ffffffff810e84d8)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/sched/debug.c (ffffffff810f5e87)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/sched/debug.c:dirty_sched_domain_sysctl
```
```
In kernel/sched/membarrier.c (ffffffff810fa7cf)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/sched/isolation.c (ffffffff828b69a1)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In kernel/irq/matrix.c (ffffffff8111aebe)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In kernel/time/timer.c (ffffffff8112c990)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/smp.c (ffffffff8114774f)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/events/uprobes.c (ffffffff81212f64)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff8121bf8b)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/shmem.c (ffffffff81238271)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/percpu.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In mm/memory.c (ffffffff8125aa75)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
```
In mm/rmap.c (ffffffff8126bfd4)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/page_alloc.c (ffffffff81a675eb)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:reserve_bootmem_region
```
```
In mm/swap_state.c (ffffffff8127f6cd)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff8128cb17)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:prep_compound_gigantic_page
```
```
In mm/sparse.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In mm/ksm.c (ffffffff8129ac5e)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff8129c4f3)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff812aabd2)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812b0817)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812b4561)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/cma.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812ca8bc)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/pipe.c (ffffffff812df8cf)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
```
```
In fs/file.c (ffffffff812f7fb3)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
```
```
In fs/dax.c (ffffffff81341b5c)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff81386e29)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff8139a02c)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/mballoc.c (ffffffff813b4650)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/ext4/super.c (ffffffff813dcfda)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
```
```
In fs/hugetlbfs/inode.c (ffffffff813fc429)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff8141a79f)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_request_alloc
```
```
In security/integrity/ima/ima_template.c (ffffffff814b2f39)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/scsi_ioctl.c (ffffffff828dda18)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
```
```
In block/blk-cgroup.c (ffffffff81502ba7)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In lib/bitmap.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In lib/iommu-helper.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff815648b9)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/pwm/core.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/acpi/x86/apple.c (ffffffff815df757)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/pnp/quirks.c (ffffffff816103eb)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff828e6793)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff8163ac48)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
```
In drivers/tty/sysrq.c (ffffffff81656e01)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8167dc26)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff816a793b)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:domain_id_alloc
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff828ece80)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816b903f)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/scsi/sr.c (ffffffff8173a916)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/net/phy/phy.c (ffffffff8177cf6e)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
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
In drivers/net/phy/phy-c45.c (ffffffff8177e54d)
Location: include/asm-generic/bitops-instrumented.h:41
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
```
```
In drivers/net/phy/phy_device.c (ffffffff828f3a45)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:genphy_read_abilities
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
In drivers/net/phy/sfp-bus.c (ffffffff81783e67)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
```
```
In drivers/net/phy/fixed_phy.c (ffffffff81784975)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/net/tun.c (ffffffff81785356)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/input/input.c (ffffffff8180d7d3)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_set_abs_params
  - drivers/input/input.c:input_set_abs_params
```
```
In drivers/input/input-mt.c (ffffffff8180f34b)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/input/ff-core.c (ffffffff8180ff02)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81813fde)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/extcon/extcon.c (ffffffff8189c4f2)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
```
```
In net/socket.c (ffffffff818ab82e)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff818b4d36)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_init_data
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
  - net/core/sock.c:sk_set_memalloc
```
```
In net/core/dev.c (ffffffff818d60d5)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/netlink/af_netlink.c (ffffffff8193d42d)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff81959649)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195b19e)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff81962cc5)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff8196b7cb)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81974de1)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81978361)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819888f3)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff8198dbc1)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In net/unix/af_unix.c (ffffffff819d05b9)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/unix/garbage.c (ffffffff819d3cc4)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: False
```
```
In net/ipv6/addrconf.c (ffffffff819dd921)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a1bdc1)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff81a2e889)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/rfkill/input.c (ffffffff81a3c43c)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81a4a37c)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In lib/idr.c (ffffffff81a4e51c)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffff81a52bde)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff81a5e4b8)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In arch/x86/events/core.c (ffffffff8100613b)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_pmu_start
```
```
In arch/x86/events/amd/core.c (ffffffff81007c42)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015955)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_assign_events
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81019893)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101c231)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snr_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_uncore_pci_init_box
```
```
In arch/x86/hyperv/mmu.c (ffffffff8101e55d)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8101ed19)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/signal.c (ffffffff81020ba9)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81037fe4)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103d552)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810515c6)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105b649)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
```
```
In arch/x86/kernel/kvm.c (ffffffff810668dd)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106775d)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff81076016)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a83e8)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
```
In kernel/sysctl.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In kernel/workqueue.c (ffffffff810ab509)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:__flush_work
```
```
In kernel/sched/core.c (ffffffff81a2ac41)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/rt.c (ffffffff810d79d7)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:alloc_rt_sched_group
```
```
In kernel/sched/debug.c (ffffffff810e6047)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/sched/debug.c:dirty_sched_domain_sysctl
```
```
In kernel/sched/membarrier.c (ffffffff810ea9af)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/sched/isolation.c (ffffffff828aeb97)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In kernel/irq/matrix.c (ffffffff8110bf2e)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In kernel/time/timer.c (ffffffff8111f200)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/smp.c (ffffffff8113a9ff)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/events/uprobes.c (ffffffff81205cd4)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff8120f17b)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/shmem.c (ffffffff8122b2ad)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/percpu.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In mm/memory.c (ffffffff8124ce40)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
```
In mm/rmap.c (ffffffff8125e044)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/page_alloc.c (ffffffff81a240ab)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:reserve_bootmem_region
```
```
In mm/swap_state.c (ffffffff812714ed)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff8127e937)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:prep_compound_gigantic_page
```
```
In mm/sparse.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In mm/ksm.c (ffffffff8128c81e)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff8128e0a0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff8129c52f)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812a1a95)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812a55e0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/cma.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812bb843)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/pipe.c (ffffffff812d050f)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
```
```
In fs/file.c (ffffffff812e8bd3)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
```
```
In fs/dax.c (ffffffff813324e1)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff813778b9)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff8138aabc)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/mballoc.c (ffffffff813a50e0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/ext4/super.c (ffffffff813cda5a)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
```
```
In fs/hugetlbfs/inode.c (ffffffff813ecea9)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff8140b21f)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_request_alloc
```
```
In security/integrity/ima/ima_template.c (ffffffff814a3959)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/scsi_ioctl.c (ffffffff828d6134)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
```
```
In block/blk-cgroup.c (ffffffff814f2da7)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In lib/bitmap.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In lib/iommu-helper.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff81555709)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/pci/pci.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/acpi/x86/apple.c (ffffffff815cad77)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/pnp/quirks.c (ffffffff8160493b)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff828def88)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/tty/sysrq.c (ffffffff81637191)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8165cd16)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff8168532b)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:domain_id_alloc
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff828e430d)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81696c7f)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/scsi/sr.c (ffffffff8171c5b6)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/net/phy/phy.c (ffffffff8175cd1e)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
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
In drivers/net/phy/phy-c45.c (ffffffff8175e2ed)
Location: include/asm-generic/bitops-instrumented.h:41
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
```
```
In drivers/net/phy/phy_device.c (ffffffff828eaef0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:genphy_read_abilities
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
In drivers/net/phy/sfp-bus.c (ffffffff817637b7)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
```
```
In drivers/net/phy/fixed_phy.c (ffffffff817642c5)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/net/tun.c (ffffffff81764ca6)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In drivers/input/input.c (ffffffff817d4f43)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_set_abs_params
  - drivers/input/input.c:input_set_abs_params
```
```
In drivers/input/input-mt.c (ffffffff817d6a9b)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/input/ff-core.c (ffffffff817d7652)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (ffffffff817db70e)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In net/socket.c (ffffffff8186577e)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff8186ec86)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_init_data
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
  - net/core/sock.c:sk_set_memalloc
```
```
In net/core/dev.c (ffffffff8188ff15)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/netlink/af_netlink.c (ffffffff818f6f2d)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff81913139)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81914c8e)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff8191c7b5)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff819252bb)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff8192e8a1)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81931e21)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819423b3)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff81947681)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In net/unix/af_unix.c (ffffffff8198d379)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/unix/garbage.c (ffffffff81990a84)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: False
```
```
In net/ipv6/addrconf.c (ffffffff8199a6e1)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff819d8b81)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff819eba79)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/rfkill/input.c (ffffffff819f905c)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81a06f6c)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In lib/idr.c (ffffffff81a0b60c)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffff81a0fcde)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff81a1b588)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In arch/x86/events/core.c (ffffffff8100792b)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_pmu_start
```
```
In arch/x86/events/amd/core.c (ffffffff81009472)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/intel/uncore.c (ffffffff810164e5)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_assign_events
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101a0f3)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101cb01)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snr_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_uncore_pci_init_box
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102e76d)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f4f0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
```
```
In arch/x86/kernel/signal.c (ffffffff81030fe9)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81048a94)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104ded2)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81061596)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106b7c0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
```
```
In arch/x86/kernel/kvm.c (ffffffff810768bd)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077a2d)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff81087400)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c30fa)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
```
In kernel/sysctl.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In kernel/workqueue.c (ffffffff810bc219)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:__flush_work
```
```
In kernel/sched/core.c (ffffffff81adac58)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/rt.c (ffffffff810e4b47)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:alloc_rt_sched_group
```
```
In kernel/sched/debug.c (ffffffff810f3087)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/sched/debug.c:dirty_sched_domain_sysctl
```
```
In kernel/sched/membarrier.c (ffffffff810f798f)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/sched/isolation.c (ffffffff828c9845)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In kernel/irq/matrix.c (ffffffff81118dae)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In kernel/time/timer.c (ffffffff8112a6b0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/smp.c (ffffffff811455ff)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/events/uprobes.c (ffffffff81210d04)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff81219d2b)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/shmem.c (ffffffff81236011)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/percpu.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In mm/memory.c (ffffffff81258815)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
```
In mm/rmap.c (ffffffff81269d74)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/page_alloc.c (ffffffff81ad39fb)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:reserve_bootmem_region
```
```
In mm/swap_state.c (ffffffff8127d46d)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff8128a927)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:prep_compound_gigantic_page
```
```
In mm/sparse.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In mm/ksm.c (ffffffff81298a6e)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff8129a303)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff812a89e2)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812ae627)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812b2371)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/cma.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812c86cc)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/pipe.c (ffffffff812dd6df)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
```
```
In fs/file.c (ffffffff812f5dc3)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
```
```
In fs/dax.c (ffffffff8133f62c)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff813848f9)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff8139788c)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/mballoc.c (ffffffff813b1eb0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/ext4/super.c (ffffffff813da47a)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
```
```
In fs/hugetlbfs/inode.c (ffffffff813f97a9)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff8141693f)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_request_alloc
```
```
In security/integrity/ima/ima_template.c (ffffffff814aefc9)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/scsi_ioctl.c (ffffffff828f078c)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
```
```
In block/blk-cgroup.c (ffffffff814fec37)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In lib/bitmap.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In lib/iommu-helper.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff81563429)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/pwm/core.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/acpi/x86/apple.c (ffffffff815e4da7)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/pnp/quirks.c (ffffffff8163e1cb)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff828fa23e)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81668d98)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
```
In drivers/tty/sysrq.c (ffffffff816851c1)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff816ac006)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff816d5bab)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:domain_id_alloc
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff829009bc)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816e750f)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/scsi/sr.c (ffffffff8177b0a6)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/net/phy/phy.c (ffffffff817ad31e)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
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
In drivers/net/phy/phy-c45.c (ffffffff817ae8fd)
Location: include/asm-generic/bitops-instrumented.h:41
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
```
```
In drivers/net/phy/phy_device.c (ffffffff82907483)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:genphy_read_abilities
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
In drivers/net/phy/sfp-bus.c (ffffffff817b4217)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
```
```
In drivers/net/phy/fixed_phy.c (ffffffff817b4d25)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/net/tun.c (ffffffff817b5706)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/input/input.c (ffffffff8184c953)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_set_abs_params
  - drivers/input/input.c:input_set_abs_params
```
```
In drivers/input/input-mt.c (ffffffff8184e4cb)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/input/ff-core.c (ffffffff8184f082)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8185315e)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8185615c)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/extcon/extcon.c (ffffffff818ebbe2)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
```
```
In net/socket.c (ffffffff818fc82e)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81905d36)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_init_data
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
  - net/core/sock.c:sk_set_memalloc
```
```
In net/core/dev.c (ffffffff81927105)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/netlink/af_netlink.c (ffffffff8198e5bd)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff8199eebe)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In net/netfilter/nf_conntrack_netlink.c (ffffffff819ae0a1)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_create_conntrack
```
```
In net/ipv4/inet_hashtables.c (ffffffff819c3e19)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c596e)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff819cd495)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff819d5f9b)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff819df5b1)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e2b31)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819f30c3)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff819f8461)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81a3b039)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/unix/garbage.c (ffffffff81a3e744)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: False
```
```
In net/ipv6/addrconf.c (ffffffff81a483a1)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a86841)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff81a9a439)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/rfkill/input.c (ffffffff81aa82ec)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81ab622c)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In lib/idr.c (ffffffff81aba90c)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffff81abefce)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff81aca8a8)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In arch/x86/events/core.c (ffffffff81007a8b)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_pmu_start
```
```
In arch/x86/events/amd/core.c (ffffffff810095d2)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016725)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_assign_events
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101a333)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101cd41)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snr_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_uncore_pci_init_box
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102f55d)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81030330)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
```
```
In arch/x86/kernel/signal.c (ffffffff81031e80)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81049ea4)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104f312)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81062b46)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106cec0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
```
```
In arch/x86/kernel/kvm.c (ffffffff81078a1d)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In arch/x86/kernel/paravirt.c (ffffffff81079acd)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff81089530)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c62a0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff81098d23)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
```
```
In kernel/sysctl.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In kernel/workqueue.c (ffffffff810c331b)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:__flush_work
```
```
In kernel/sched/core.c (ffffffff81ae710a)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/rt.c (ffffffff810f1238)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/sched/debug.c (ffffffff810fe087)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/sched/debug.c:dirty_sched_domain_sysctl
```
```
In kernel/sched/membarrier.c (ffffffff81102a9c)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/sched/isolation.c (ffffffff828cebf7)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In kernel/irq/matrix.c (ffffffff8112443e)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In kernel/time/timer.c (ffffffff81137c90)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/smp.c (ffffffff811521f6)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/events/uprobes.c (ffffffff8121fc1c)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff81228e2b)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/shmem.c (ffffffff812462f1)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/percpu.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In mm/memory.c (ffffffff8126822f)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
```
In mm/rmap.c (ffffffff812796e4)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/page_alloc.c (ffffffff81adfef5)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:reserve_bootmem_region
```
```
In mm/swap_state.c (ffffffff8128d043)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff8129a71d)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:prep_compound_gigantic_page
```
```
In mm/sparse.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In mm/ksm.c (ffffffff812a884d)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff812aa1e3)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff812b8d02)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812be984)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812c2778)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/cma.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812d9370)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/pipe.c (ffffffff812ee65f)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
```
```
In fs/file.c (ffffffff81306ee7)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
```
```
In fs/dax.c (ffffffff81352ff3)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff81398474)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff813ac158)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/mballoc.c (ffffffff813c69f0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/ext4/super.c (ffffffff813ef75a)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
```
```
In fs/hugetlbfs/inode.c (ffffffff8140f404)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff8142d69f)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_request_alloc
```
```
In security/integrity/ima/ima_template.c (ffffffff814c7a49)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/scsi_ioctl.c (ffffffff828f5bb8)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
```
```
In block/blk-cgroup.c (ffffffff81517a07)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In lib/bitmap.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In lib/iommu-helper.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff8157d349)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/pwm/core.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/acpi/x86/apple.c (ffffffff815fec57)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/pnp/quirks.c (ffffffff8165851b)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff828fff6f)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81683358)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
```
In drivers/tty/sysrq.c (ffffffff8169f7c1)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff816c6466)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff816ece6d)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:domain_id_alloc
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff829066fb)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81701c0f)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/scsi/sr.c (ffffffff81794c0f)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/net/phy/phy.c (ffffffff817c72ae)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
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
In drivers/net/phy/phy-c45.c (ffffffff817c888d)
Location: include/asm-generic/bitops-instrumented.h:41
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
```
```
In drivers/net/phy/phy_device.c (ffffffff8290d0ea)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:genphy_read_abilities
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
In drivers/net/phy/sfp-bus.c (ffffffff817ce1e7)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
```
```
In drivers/net/phy/fixed_phy.c (ffffffff817cecf5)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/net/tun.c (ffffffff817cf8e6)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/input/input.c (ffffffff81867c43)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_set_abs_params
  - drivers/input/input.c:input_set_abs_params
```
```
In drivers/input/input-mt.c (ffffffff8186969b)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In drivers/input/ff-core.c (ffffffff8186a232)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8186e3ae)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8187128c)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/extcon/extcon.c (ffffffff8190cc62)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
```
```
In net/socket.c (ffffffff8191d82e)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81926d66)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_init_data
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
  - net/core/sock.c:sk_set_memalloc
```
```
In net/core/dev.c (ffffffff81948774)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/netlink/af_netlink.c (ffffffff819b0e6d)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff819cd86f)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819cf44e)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff819d7025)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff819dfb9b)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff819e9261)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ecc51)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819fb98e)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff81a02781)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81a48817)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/unix/garbage.c (ffffffff81a4a204)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (0)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: False
```
```
In net/ipv6/addrconf.c (ffffffff81a542d1)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a93401)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff81aa717b)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/rfkill/input.c (ffffffff81ab484c)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81ac234c)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In lib/idr.c (ffffffff81ac6d5c)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffff81acb49e)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff81ad6e78)
Location: include/asm-generic/bitops-instrumented.h:41
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
```
</details>
</li>
</ul>

## Differences
