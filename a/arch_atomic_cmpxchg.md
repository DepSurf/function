# Function: <code>arch_atomic_cmpxchg</code>

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
In arch/x86/kernel/dumpstack.c (ffffffff81031b83)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8105828c)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff81059b3a)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8105b987)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8105c941)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
```
```
In arch/x86/kernel/hpet.c (ffffffff8106b5c6)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
```
```
In kernel/panic.c (ffffffff8108ea1d)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - kernel/panic.c:panic
  - kernel/panic.c:nmi_panic
```
```
In kernel/smpboot.c (ffffffff810b77b7)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_report_death
  - kernel/smpboot.c:cpu_wait_death
```
```
In kernel/ucount.c (ffffffff810b7c4a)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
  - kernel/ucount.c:inc_ucount
```
```
In kernel/kmod.c (ffffffff810b7f1e)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/rt.c (ffffffff810d3cdb)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/locking/spinlock.c (ffffffff819f1b9f)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_trylock
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
  - kernel/locking/spinlock.c:_raw_write_lock_irq
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_write_lock
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/osq_lock.c (ffffffff810e4f12)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff810e5349)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
```
```
In kernel/locking/qrwlock.c (ffffffff810e6996)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/printk/printk_safe.c (ffffffff810f5312)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_log_store
```
```
In kernel/rcu/tree.c (ffffffff81107d74)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_eqs_special_set
```
```
In kernel/module.c (ffffffff8112ed70)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
```
```
In kernel/kexec_core.c (ffffffff81137b3a)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/trace/trace_clock.c (ffffffff81170067)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff8117b3d0)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
```
```
In kernel/trace/trace.c (ffffffff8117f89c)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:tracing_stop
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8118bc84)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff8118d01b)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/events/core.c (ffffffff811d909b)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/jump_label.c (ffffffff811e867a)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_disable_cpuslocked
```
```
In mm/vmscan.c (ffffffff81209488)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/mmap.c (ffffffff81237e51)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
```
In mm/migrate.c (ffffffff8127274a)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff81278878)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff8127b458)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memfd.c (ffffffff8129418a)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff81295300)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/super.c (ffffffff8129d733)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
```
```
In fs/exec.c (ffffffff812a08a7)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
```
In fs/namei.c (ffffffff812aaba0)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
```
In fs/block_dev.c (ffffffff812ddb13)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_open
```
```
In fs/aio.c (ffffffff812f201d)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - fs/aio.c:get_reqs_available
```
```
In fs/proc/inode.c (ffffffff8131a582)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/kernfs/dir.c (ffffffff8132c182)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
```
```
In block/blk-mq.c (ffffffff81490d26)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (ffffffff8149318e)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-wbt.c (ffffffff814b994f)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_wait
```
```
In lib/sbitmap.c (ffffffff814f86bd)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/rapidio/rio.c (ffffffff8154c342)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/iommu/iova.c (ffffffff81664dc4)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
```
```
In drivers/thermal/thermal_core.c (ffffffff817e7ad3)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
```
In net/core/dev.c (ffffffff8188e375)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
```
```
In net/ipv4/route.c (ffffffff818e1fd4)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv6/ip6_fib.c (ffffffff8197996b)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_update_sernum_upto_root
  - net/ipv6/ip6_fib.c:fib6_update_sernum
```
```
In lib/dump_stack.c (ffffffff819ce35f)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8105df2a)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff8105f7ba)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810625c1)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
```
```
In kernel/panic.c (ffffffff81096d5d)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/panic.c:panic
  - kernel/panic.c:nmi_panic
```
```
In kernel/smpboot.c (ffffffff810c08b7)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_report_death
  - kernel/smpboot.c:cpu_wait_death
```
```
In kernel/ucount.c (ffffffff810c0bc2)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/rt.c (ffffffff810dd97b)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/locking/osq_lock.c (ffffffff810f04f3)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff810f0929)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
```
```
In kernel/locking/qrwlock.c (ffffffff810f1fa7)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
```
```
In kernel/printk/printk_safe.c (ffffffff81100ab2)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_log_store
```
```
In kernel/rcu/tree.c (ffffffff81113294)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_eqs_special_set
```
```
In kernel/kexec_core.c (ffffffff81143355)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/trace/ring_buffer.c (ffffffff81185385)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
```
```
In kernel/jump_label.c (ffffffff811f933f)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_disable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
```
In mm/vmscan.c (ffffffff8121c16a)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/migrate.c (ffffffff81286d27)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff8128cf2d)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff8128ffa3)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/aio.c (ffffffff813076bd)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - fs/aio.c:__get_reqs_available
```
```
In block/blk-mq.c (ffffffff814a9ee3)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (ffffffff814ad114)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-rq-qos.c (ffffffff814bd7a3)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
```
In lib/sbitmap.c (ffffffff8150c944)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/rapidio/rio.c (ffffffff815636d2)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/iommu/iova.c (ffffffff816833c4)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
```
```
In drivers/thermal/thermal_core.c (ffffffff81813376)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
```
In net/core/dev.c (ffffffff818af285)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
```
```
In net/ipv4/route.c (ffffffff8190ee74)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv6/ip6_fib.c (ffffffff819af53b)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_update_sernum_upto_root
  - net/ipv6/ip6_fib.c:fib6_update_sernum
```
```
In lib/dump_stack.c (ffffffff81a07818)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8106132a)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff81062c3f)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81065c36)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
```
```
In kernel/panic.c (ffffffff8109b2d9)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/panic.c:panic
  - kernel/panic.c:nmi_panic
```
```
In kernel/smpboot.c (ffffffff810c69ac)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_report_death
  - kernel/smpboot.c:cpu_wait_death
```
```
In kernel/ucount.c (ffffffff810c6cc9)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/rt.c (ffffffff810e496b)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/sched/psi.c (ffffffff810f6535)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
```
```
In kernel/locking/osq_lock.c (ffffffff810f8b72)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff810f8c49)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
```
```
In kernel/locking/qrwlock.c (ffffffff810fa407)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
```
```
In kernel/printk/printk_safe.c (ffffffff8110925e)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_log_store
```
```
In kernel/rcu/tree.c (ffffffff8111ce64)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_eqs_special_set
```
```
In kernel/kexec_core.c (ffffffff8114e69c)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/trace/ring_buffer.c (ffffffff81192521)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
```
```
In kernel/jump_label.c (ffffffff812112bf)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_disable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
```
In mm/vmscan.c (ffffffff8122bec1)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/ksm.c (ffffffff81292bd2)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
```
```
In mm/migrate.c (ffffffff812a12b9)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812a7bc2)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff812aae26)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/aio.c (ffffffff81328cb1)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - fs/aio.c:__get_reqs_available
```
```
In block/blk-mq.c (ffffffff814d7e71)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (ffffffff814db3b9)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-rq-qos.c (ffffffff814ebe51)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
```
In lib/sbitmap.c (ffffffff8153b04b)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/rapidio/rio.c (ffffffff81593a72)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/iommu/iova.c (ffffffff816ba979)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
```
```
In drivers/thermal/thermal_core.c (ffffffff818554b1)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
```
In net/core/dev.c (ffffffff818fb0c2)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
```
```
In net/ipv4/route.c (ffffffff81970985)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv6/ip6_fib.c (ffffffff81a1d75b)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_update_sernum_upto_root
  - net/ipv6/ip6_fib.c:fib6_update_sernum
```
```
In lib/dump_stack.c (ffffffff81a771a8)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81061b9a)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff81063313)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81066266)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
```
```
In kernel/panic.c (ffffffff810a17f9)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/panic.c:panic
  - kernel/panic.c:nmi_panic
```
```
In kernel/smpboot.c (ffffffff810cfa8c)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_report_death
  - kernel/smpboot.c:cpu_wait_death
```
```
In kernel/ucount.c (ffffffff810cfd99)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/rt.c (ffffffff810efb3b)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/sched/psi.c (ffffffff811022d5)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
```
```
In kernel/locking/osq_lock.c (ffffffff81104982)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff81104a59)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
```
```
In kernel/locking/qrwlock.c (ffffffff811061e7)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
```
```
In kernel/printk/printk_safe.c (ffffffff8111563e)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_log_store
```
```
In kernel/rcu/tree.c (ffffffff81129344)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_eqs_special_set
```
```
In kernel/kexec_core.c (ffffffff8115a3ac)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/trace/ring_buffer.c (ffffffff8119e1d1)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
```
```
In kernel/jump_label.c (ffffffff8121ef6f)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
```
```
In mm/vmscan.c (ffffffff81239d8b)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/ksm.c (ffffffff812a2952)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
```
```
In mm/migrate.c (ffffffff812b26d9)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812b908b)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff812bc54f)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/aio.c (ffffffff8133ba61)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - fs/aio.c:__get_reqs_available
```
```
In block/blk-mq.c (ffffffff814f1203)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (ffffffff814f47e9)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-rq-qos.c (ffffffff81505211)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
```
In block/blk-iocost.c (ffffffff8150fcc9)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffffffff8155be6b)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/rapidio/rio.c (ffffffff815b4cf2)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/iommu/iova.c (ffffffff816dd7c8)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
```
```
In drivers/vfio/vfio.c (ffffffff817d1455)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
```
In drivers/thermal/thermal_core.c (ffffffff81887db9)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
```
In net/core/dev.c (ffffffff8192d212)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
```
```
In net/ipv4/route.c (ffffffff819a7385)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv6/ip6_fib.c (ffffffff81a5438b)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_update_sernum_upto_root
  - net/ipv6/ip6_fib.c:fib6_update_sernum
```
```
In lib/dump_stack.c (ffffffff81aae588)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81067aba)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff81069336)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106cb66)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
```
```
In kernel/panic.c (ffffffff810a8612)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
Inline callers:
  - kernel/panic.c:panic
  - kernel/panic.c:nmi_panic
```
```
In kernel/smpboot.c (ffffffff810d9989)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_report_death
  - kernel/smpboot.c:cpu_wait_death
```
```
In kernel/ucount.c (ffffffff810d9d92)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/rt.c (ffffffff810f8033)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
Inline callers:
  - kernel/sched/rt.c:tell_cpu_to_push
```
```
In kernel/sched/psi.c (ffffffff8110ca25)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
```
```
In kernel/locking/osq_lock.c (ffffffff8110f732)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff8110fb85)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
```
```
In kernel/locking/qrwlock.c (ffffffff81111217)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
```
```
In kernel/printk/printk_safe.c (ffffffff81120f47)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_log_store
```
```
In kernel/rcu/tree.c (ffffffff81137d2a)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_eqs_special_set
```
```
In kernel/kexec_core.c (ffffffff8116b17c)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/trace/ring_buffer.c (ffffffff811b4a81)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
```
```
In kernel/irq_work.c (ffffffff811f7524)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_single
```
```
In kernel/jump_label.c (ffffffff8124adbf)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_disable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
```
In mm/vmscan.c (ffffffff81266247)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/ksm.c (ffffffff812d70d2)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
```
```
In mm/migrate.c (ffffffff812e7c79)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812edc5d)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff812f1a6c)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/page_reporting.c (ffffffff8130d512)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_process
```
```
In fs/aio.c (ffffffff813756af)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
Inline callers:
  - fs/aio.c:__get_reqs_available
```
```
In block/blk-mq.c (ffffffff81551a24)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In block/blk-mq-tag.c (ffffffff81554fb7)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-rq-qos.c (ffffffff81565ae1)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
```
In block/blk-iocost.c (ffffffff81570d1d)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffffffff815e5960)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
```
```
In lib/dump_stack.c (ffffffff815e82e5)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
```
In drivers/rapidio/rio.c (ffffffff8165dda2)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/iommu/iova.c (ffffffff817945a4)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
```
```
In drivers/vfio/vfio.c (ffffffff8189d5be)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
```
In drivers/thermal/thermal_core.c (ffffffff81956ca4)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
```
In net/core/dev.c (ffffffff81a00873)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4c31b)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_update_sernum
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff810698ba)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff8106af56)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106e316)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
```
```
In kernel/panic.c (ffffffff81bdb1ca)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/panic.c:panic
  - kernel/panic.c:nmi_panic
```
```
In kernel/smpboot.c (ffffffff810d4b39)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_report_death
  - kernel/smpboot.c:cpu_wait_death
```
```
In kernel/ucount.c (ffffffff810d4f42)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/rt.c (ffffffff810f6243)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/sched/rt.c:tell_cpu_to_push
```
```
In kernel/sched/psi.c (ffffffff8110a8ce)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_poll_worker
  - kernel/sched/psi.c:psi_poll_worker
```
```
In kernel/locking/osq_lock.c (ffffffff8110c8f2)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff8110cd45)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
```
```
In kernel/locking/qrwlock.c (ffffffff8110e397)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
```
```
In kernel/printk/printk_safe.c (ffffffff8111bba7)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_log_store
```
```
In kernel/rcu/tree.c (ffffffff811335ca)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_eqs_special_set
```
```
In kernel/kexec_core.c (ffffffff811678bc)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/trace/ring_buffer.c (ffffffff811b2331)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
```
```
In kernel/irq_work.c (ffffffff811f6093)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_single
```
```
In kernel/jump_label.c (ffffffff812551af)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_disable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
```
In mm/vmscan.c (ffffffff81270c41)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/migrate.c (ffffffff812f3059)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812f9332)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff812fdff3)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/page_reporting.c (ffffffff81319462)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_process
```
```
In fs/aio.c (ffffffff8138358c)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - fs/aio.c:__get_reqs_available
```
```
In block/blk-mq.c (ffffffff8156db78)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In block/blk-mq-tag.c (ffffffff8157166c)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-rq-qos.c (ffffffff81580a61)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
```
In block/blk-iocost.c (ffffffff8158bd1b)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffffffff81609d20)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
```
```
In lib/dump_stack.c (ffffffff81bf49e5)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
```
In drivers/rapidio/rio.c (ffffffff8167f4c2)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/scsi/scsi_lib.c (ffffffff818463fe)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
```
```
In drivers/vfio/vfio.c (ffffffff818ac1ee)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
```
In drivers/thermal/thermal_core.c (ffffffff8195ae6e)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
```
In net/core/dev.c (ffffffff81a00c83)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81b5af5b)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_update_sernum
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8106a30a)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff8106bb53)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106ed35)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
```
```
In kernel/panic.c (ffffffff81bcd2bc)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/panic.c:panic
  - kernel/panic.c:nmi_panic
```
```
In kernel/smpboot.c (ffffffff810d6759)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_report_death
  - kernel/smpboot.c:cpu_wait_death
```
```
In kernel/ucount.c (ffffffff810d6c22)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/rt.c (ffffffff810f94c9)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/sched/psi.c (ffffffff8110c2bd)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_poll_worker
  - kernel/sched/psi.c:psi_poll_worker
```
```
In kernel/locking/osq_lock.c (ffffffff8110e722)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff8110ea35)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
```
```
In kernel/printk/printk_safe.c (ffffffff8111bffe)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_log_store
```
```
In kernel/rcu/tree.c (ffffffff811340ea)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_eqs_special_set
```
```
In kernel/kexec_core.c (ffffffff8116864c)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/trace/ring_buffer.c (ffffffff811b2e31)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
```
```
In kernel/irq_work.c (ffffffff811f6f83)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_single
```
```
In kernel/jump_label.c (ffffffff812596af)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_disable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
```
In mm/vmscan.c (ffffffff8127572a)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/migrate.c (ffffffff812f93e8)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812ff8ff)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff81304be0)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/page_reporting.c (ffffffff8131f611)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_process
```
```
In fs/aio.c (ffffffff8138cab8)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - fs/aio.c:__get_reqs_available
```
```
In block/blk-mq.c (ffffffff81575658)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In block/blk-mq-tag.c (ffffffff8157969c)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-rq-qos.c (ffffffff815885d1)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
```
In block/blk-iocost.c (ffffffff81592bdb)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffffffff815ecf00)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
```
```
In lib/dump_stack.c (ffffffff81be68dd)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
```
In drivers/rapidio/rio.c (ffffffff81662d52)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/scsi/scsi_lib.c (ffffffff818296ce)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
```
```
In drivers/vfio/vfio.c (ffffffff8188f31a)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
```
In drivers/thermal/thermal_core.c (ffffffff8193fc23)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
```
In net/core/dev.c (ffffffff819e7453)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81b491db)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_update_sernum
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81074a8a)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff81076623)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8107a6da)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
```
```
In kernel/panic.c (ffffffff81ca3a5c)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/panic.c:panic
  - kernel/panic.c:nmi_panic
```
```
In kernel/smpboot.c (ffffffff810e9c23)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_report_death
  - kernel/smpboot.c:cpu_wait_death
```
```
In kernel/sched/rt.c (ffffffff81112c89)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/sched/psi.c (ffffffff8112b09d)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_poll_worker
  - kernel/sched/psi.c:psi_poll_worker
```
```
In kernel/locking/osq_lock.c (ffffffff8112deb2)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff8112e262)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
```
```
In kernel/printk/printk.c (ffffffff81139352)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
```
```
In kernel/kexec_core.c (ffffffff8118e38c)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/trace/ring_buffer.c (ffffffff811dcd61)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
```
```
In kernel/irq_work.c (ffffffff81228553)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_single
```
```
In kernel/jump_label.c (ffffffff8129537b)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_disable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
```
In mm/vmscan.c (ffffffff812b32d8)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/hugetlb.c (ffffffff8131ca0b)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
```
```
In mm/migrate.c (ffffffff813429f9)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff8134953b)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff8134e970)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/page_reporting.c (ffffffff8136ca48)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_process
```
```
In fs/aio.c (ffffffff813da108)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - fs/aio.c:__get_reqs_available
```
```
In security/integrity/ima/ima_policy.c (ffffffff8159efef)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy_flags
```
```
In block/blk-mq.c (ffffffff815da358)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In block/blk-mq-tag.c (ffffffff815de8b5)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-rq-qos.c (ffffffff815ee271)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
```
In block/blk-iocost.c (ffffffff815fa079)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffffffff81659e20)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/rapidio/rio.c (ffffffff816d5c2f)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b50be)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
```
```
In drivers/vfio/vfio.c (ffffffff819228fa)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
```
In drivers/thermal/thermal_core.c (ffffffff819e4473)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
```
In net/core/dev.c (ffffffff81a97e43)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81c104eb)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_update_sernum
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8108325a)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_nmi_unknown
```
```
In arch/x86/kernel/smp.c (ffffffff81085166)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81088f13)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
```
```
In kernel/panic.c (ffffffff81e53231)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In kernel/smpboot.c (ffffffff811048b3)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_report_death
  - kernel/smpboot.c:cpu_wait_death
```
```
In kernel/sched/build_policy.c (ffffffff8112ff8f)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_rt_task
```
```
In kernel/sched/build_utility.c (ffffffff81143cc0)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_poll_worker
  - kernel/sched/build_utility.c:psi_poll_worker
```
```
In kernel/locking/osq_lock.c (ffffffff8114eed2)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff8114f382)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
```
```
In kernel/printk/printk.c (ffffffff8115ac62)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/printk/printk.c:__printk_cpu_sync_try_get
```
```
In kernel/kexec_core.c (ffffffff811bd91c)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/trace/ring_buffer.c (ffffffff81213231)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
```
```
In kernel/irq_work.c (ffffffff812695d3)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_single
```
```
In kernel/jump_label.c (ffffffff812eb148)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_disable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
```
In mm/vmscan.c (ffffffff8130e63a)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/rmap.c (ffffffff8135db1a)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:flush_tlb_batched_pending
```
```
In mm/hugetlb.c (ffffffff8138839e)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - mm/hugetlb.c:__prep_compound_gigantic_page
```
```
In mm/migrate.c (ffffffff813b4eff)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff813bfacd)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff813c50f2)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/page_reporting.c (ffffffff813eac83)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_process
```
```
In fs/aio.c (ffffffff81460a26)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - fs/aio.c:__get_reqs_available
```
```
In security/integrity/ima/ima_policy.c (ffffffff81644964)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy_flags
```
```
In block/blk-mq.c (ffffffff81688419)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In block/blk-mq-tag.c (ffffffff8168cb14)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-rq-qos.c (ffffffff8169ea61)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
```
In block/blk-iocost.c (ffffffff816ac287)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffffffff817724e1)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff817abe95)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
```
```
In drivers/rapidio/rio.c (ffffffff817fde62)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/scsi/scsi_lib.c (ffffffff81a0008c)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffffffff81b4970b)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
```
In net/core/dev.c (ffffffff81c0f813)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81dab74b)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_update_sernum
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81095dda)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_nmi_unknown
```
```
In arch/x86/kernel/smp.c (ffffffff810985d6)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8109cb8b)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
```
```
In kernel/panic.c (ffffffff810ea3a6)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In kernel/sched/build_policy.c (ffffffff8115a1da)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_rt_task
```
```
In kernel/sched/build_utility.c (ffffffff8116f629)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_poll_worker
  - kernel/sched/build_utility.c:psi_poll_worker
```
```
In kernel/locking/osq_lock.c (ffffffff8117e122)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff820d63a2)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
```
```
In kernel/printk/printk.c (ffffffff8118d192)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/printk/printk.c:__printk_cpu_sync_try_get
```
```
In kernel/kexec_core.c (ffffffff811ffed5)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/kexec_core.c:kernel_kexec
  - kernel/kexec_core.c:crash_shrink_memory
  - kernel/kexec_core.c:crash_get_memory_size
  - kernel/kexec_core.c:crash_kexec
  - kernel/kexec_core.c:__crash_kexec
```
```
In kernel/kexec.c (ffffffff81200238)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/kexec.c:do_kexec_load
```
```
In kernel/kexec_file.c (ffffffff81201d48)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
```
In kernel/trace/ring_buffer.c (ffffffff8125ca81)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
```
```
In kernel/irq_work.c (ffffffff812be473)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_single
```
```
In kernel/jump_label.c (ffffffff813551a8)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_disable_cpuslocked
```
```
In mm/vmscan.c (ffffffff81380608)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/rmap.c (ffffffff813d899d)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:flush_tlb_batched_pending
```
```
In mm/hugetlb.c (ffffffff81405929)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - mm/hugetlb.c:__prep_compound_gigantic_folio
```
```
In mm/migrate.c (ffffffff8143409e)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff81441eec)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff81449a14)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/page_reporting.c (ffffffff81472e33)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_process
```
```
In fs/mbcache.c (ffffffff81514ab6)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_or_get
```
```
In security/integrity/ima/ima_policy.c (ffffffff816fcde4)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy_flags
```
```
In block/blk-mq.c (ffffffff817468d1)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In block/blk-mq-tag.c (ffffffff8174b309)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In io_uring/poll.c (ffffffff8179d491)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - io_uring/poll.c:__io_arm_poll_handler
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c47d5)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
```
```
In drivers/rapidio/rio.c (ffffffff8192b032)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b7e60c)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffffffff81ce0cc9)
Location: arch/x86/include/asm/atomic.h:194
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81098c9a)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_nmi_unknown
```
```
In arch/x86/kernel/smp.c (ffffffff8109b873)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:native_stop_other_cpus
```
```
In kernel/panic.c (ffffffff810f5fb2)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In kernel/sched/build_policy.c (ffffffff8116a3ea)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_rt_task
```
```
In kernel/sched/build_utility.c (ffffffff81180f08)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_rtpoll_worker
  - kernel/sched/build_utility.c:psi_rtpoll_worker
```
```
In kernel/locking/osq_lock.c (ffffffff8118edc2)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff82159782)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
```
```
In kernel/printk/printk.c (ffffffff8119e952)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - kernel/printk/printk.c:__printk_cpu_sync_try_get
```
```
In kernel/kexec_core.c (ffffffff81215335)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - kernel/kexec_core.c:kernel_kexec
  - kernel/kexec_core.c:crash_shrink_memory
  - kernel/kexec_core.c:crash_get_memory_size
  - kernel/kexec_core.c:crash_kexec
  - kernel/kexec_core.c:__crash_kexec
```
```
In kernel/kexec.c (ffffffff81215698)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - kernel/kexec.c:do_kexec_load
```
```
In kernel/kexec_file.c (ffffffff81217116)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
```
In kernel/irq_work.c (ffffffff812e50b3)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_single
```
```
In kernel/jump_label.c (ffffffff81386698)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_disable_cpuslocked
```
```
In mm/vmscan.c (ffffffff813b1f37)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/rmap.c (ffffffff8140bd7f)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - mm/rmap.c:flush_tlb_batched_pending
```
```
In mm/hugetlb.c (ffffffff81438e2f)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - mm/hugetlb.c:__prep_compound_gigantic_folio
```
```
In mm/migrate.c (ffffffff814699de)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff81477838)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/page_reporting.c (ffffffff814a75a3)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_process
```
```
In fs/mbcache.c (ffffffff8154c4c5)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_or_get
```
```
In security/integrity/ima/ima_policy.c (ffffffff81736e14)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy_flags
```
```
In block/blk-mq.c (ffffffff81783b31)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In block/blk-mq-tag.c (ffffffff81787a29)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In io_uring/poll.c (ffffffff817de6c1)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - io_uring/poll.c:__io_arm_poll_handler
```
```
In lib/rcuref.c (ffffffff8181ad71)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - lib/rcuref.c:rcuref_put_slowpath
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff819078a5)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
```
```
In drivers/rapidio/rio.c (ffffffff8196f2a2)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd23f2)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffffffff81d4901c)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
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
In arch/x86/kernel/smp.c (ffffffff810a2e13)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:native_stop_other_cpus
```
```
In kernel/sched/build_policy.c (ffffffff81177aaa)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_rt_task
```
```
In kernel/sched/build_utility.c (ffffffff8118ec58)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_rtpoll_worker
  - kernel/sched/build_utility.c:psi_rtpoll_worker
```
```
In kernel/locking/osq_lock.c (ffffffff8119d772)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff8223d002)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
```
```
In kernel/printk/printk.c (ffffffff811adb12)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - kernel/printk/printk.c:__printk_cpu_sync_try_get
```
```
In kernel/crash_core.c (ffffffff8122a227)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - kernel/crash_core.c:crash_handle_hotplug_event
  - kernel/crash_core.c:crash_check_update_elfcorehdr
```
```
In kernel/kexec_core.c (ffffffff8122d2d5)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - kernel/kexec_core.c:kernel_kexec
  - kernel/kexec_core.c:crash_shrink_memory
  - kernel/kexec_core.c:crash_get_memory_size
  - kernel/kexec_core.c:__crash_kexec
```
```
In kernel/kexec.c (ffffffff8122d638)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - kernel/kexec.c:do_kexec_load
```
```
In kernel/kexec_file.c (ffffffff8122f004)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
```
In kernel/irq_work.c (ffffffff81303163)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_single
```
```
In kernel/jump_label.c (ffffffff813afb58)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_disable_cpuslocked
```
```
In mm/vmscan.c (ffffffff813dafe8)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/rmap.c (ffffffff8143862f)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - mm/rmap.c:flush_tlb_batched_pending
```
```
In mm/hugetlb.c (ffffffff8391ad11)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/hugetlb.c:hugetlb_folio_init_tail_vmemmap
  - mm/hugetlb.c:__prep_compound_gigantic_folio
```
```
In mm/migrate.c (ffffffff81498925)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff814a6fbb)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/page_reporting.c (ffffffff814d85d2)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_process
```
```
In fs/mbcache.c (ffffffff815822f5)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_or_get
```
```
In security/integrity/ima/ima_policy.c (ffffffff817778d4)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy_flags
```
```
In block/blk-mq.c (ffffffff817c5eb4)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In block/blk-mq-tag.c (ffffffff817ca0f9)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In io_uring/poll.c (ffffffff81822a91)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - io_uring/poll.c:__io_arm_poll_handler
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff81950d2c)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
```
```
In drivers/rapidio/rio.c (ffffffff819b9192)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c27062)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffffffff81dff4bd)
Location: arch/x86/include/asm/atomic.h:107
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8106171a)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff81062e03)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81065d56)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
```
```
In kernel/panic.c (ffffffff8109b119)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/panic.c:panic
  - kernel/panic.c:nmi_panic
```
```
In kernel/smpboot.c (ffffffff810c9e0c)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_report_death
  - kernel/smpboot.c:cpu_wait_death
```
```
In kernel/ucount.c (ffffffff810ca119)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/rt.c (ffffffff810e942b)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/sched/psi.c (ffffffff810fb5e5)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
```
```
In kernel/locking/osq_lock.c (ffffffff810fdc92)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff810fdd69)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
```
```
In kernel/locking/qrwlock.c (ffffffff810ff4f7)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
```
```
In kernel/printk/printk_safe.c (ffffffff8110dc1e)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_log_store
```
```
In kernel/rcu/tree.c (ffffffff81121924)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_eqs_special_set
```
```
In kernel/kexec_core.c (ffffffff811529cc)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/trace/ring_buffer.c (ffffffff811967f1)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
```
```
In kernel/jump_label.c (ffffffff812175bf)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
```
```
In mm/vmscan.c (ffffffff812323db)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/ksm.c (ffffffff8129af32)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
```
```
In mm/migrate.c (ffffffff812aacb9)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812b166b)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff812b4b2f)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/aio.c (ffffffff81334041)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - fs/aio.c:__get_reqs_available
```
```
In block/blk-mq.c (ffffffff814e97e3)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (ffffffff814ecdc9)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-rq-qos.c (ffffffff814fd7f1)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
```
In block/blk-iocost.c (ffffffff815082a9)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffffffff8155445b)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/rapidio/rio.c (ffffffff815a8f62)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/iommu/iova.c (ffffffff816a3218)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
```
```
In drivers/thermal/thermal_core.c (ffffffff8182dc39)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
```
In net/core/dev.c (ffffffff818cd212)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
```
```
In net/ipv4/route.c (ffffffff819471f5)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv6/ip6_fib.c (ffffffff819f3a1b)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_update_sernum_upto_root
  - net/ipv6/ip6_fib.c:fib6_update_sernum
```
```
In lib/dump_stack.c (ffffffff81a4d3d8)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81051b8a)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff810530b3)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810560d6)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
```
```
In kernel/panic.c (ffffffff81089b53)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/panic.c:panic
  - kernel/panic.c:nmi_panic
```
```
In kernel/smpboot.c (ffffffff810b862c)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_report_death
  - kernel/smpboot.c:cpu_wait_death
```
```
In kernel/ucount.c (ffffffff810b8933)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/rt.c (ffffffff810d8efb)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/sched/psi.c (ffffffff810eb805)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
```
```
In kernel/locking/osq_lock.c (ffffffff810ede92)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff810edf69)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
```
```
In kernel/locking/qrwlock.c (ffffffff810ef6e7)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
```
```
In kernel/printk/printk_safe.c (ffffffff810fe97e)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_log_store
```
```
In kernel/rcu/tree.c (ffffffff81114004)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_eqs_special_set
```
```
In kernel/kexec_core.c (ffffffff81145cac)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/trace/ring_buffer.c (ffffffff81189901)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
```
```
In kernel/jump_label.c (ffffffff8120a31f)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
```
```
In mm/vmscan.c (ffffffff81225487)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/ksm.c (ffffffff8128caf2)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
```
```
In mm/migrate.c (ffffffff8129c5fc)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812a2a3b)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff812a5b81)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/aio.c (ffffffff81323e5e)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - fs/aio.c:__get_reqs_available
```
```
In block/blk-mq.c (ffffffff814d9d53)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (ffffffff814dd319)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-rq-qos.c (ffffffff814edd01)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
```
In block/blk-iocost.c (ffffffff814f8759)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffffffff815446db)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/rapidio/rio.c (ffffffff81598102)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/iommu/iova.c (ffffffff81680c08)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
```
```
In drivers/vfio/vfio.c (ffffffff8177b505)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
```
In drivers/thermal/thermal_core.c (ffffffff817f52c9)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
```
In net/core/dev.c (ffffffff818872a2)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
```
```
In net/ipv4/route.c (ffffffff81900ce5)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv6/ip6_fib.c (ffffffff819b07db)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_update_sernum_upto_root
  - net/ipv6/ip6_fib.c:fib6_update_sernum
```
```
In lib/dump_stack.c (ffffffff81a0a4fa)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81061b4a)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff810632b3)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81066206)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
```
```
In kernel/panic.c (ffffffff8109b0c9)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/panic.c:panic
  - kernel/panic.c:nmi_panic
```
```
In kernel/smpboot.c (ffffffff810c933c)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_report_death
  - kernel/smpboot.c:cpu_wait_death
```
```
In kernel/ucount.c (ffffffff810c9649)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/rt.c (ffffffff810e606b)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/sched/psi.c (ffffffff810f87a5)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
```
```
In kernel/locking/osq_lock.c (ffffffff810fae52)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff810faf29)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
```
```
In kernel/locking/qrwlock.c (ffffffff810fc6b7)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
```
```
In kernel/printk/printk_safe.c (ffffffff8110bb0e)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_log_store
```
```
In kernel/rcu/tree.c (ffffffff8111f814)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_eqs_special_set
```
```
In kernel/kexec_core.c (ffffffff8115087c)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/trace/ring_buffer.c (ffffffff811945c1)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
```
```
In kernel/jump_label.c (ffffffff8121535f)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
```
```
In mm/vmscan.c (ffffffff8123017b)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/ksm.c (ffffffff81298d42)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
```
```
In mm/migrate.c (ffffffff812a8ac9)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812af47b)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff812b293f)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/aio.c (ffffffff81331b11)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - fs/aio.c:__get_reqs_available
```
```
In block/blk-mq.c (ffffffff814e5873)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (ffffffff814e8e59)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-rq-qos.c (ffffffff814f9881)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
```
In block/blk-iocost.c (ffffffff81504339)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffffffff8155019b)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/rapidio/rio.c (ffffffff815a94f2)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/iommu/iova.c (ffffffff816d1488)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
```
```
In drivers/vfio/vfio.c (ffffffff817c62d5)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
```
In drivers/thermal/thermal_core.c (ffffffff8187d269)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
```
In net/core/dev.c (ffffffff8191e212)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
```
```
In net/ipv4/route.c (ffffffff819b19c5)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv6/ip6_fib.c (ffffffff81a5e49b)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_update_sernum_upto_root
  - net/ipv6/ip6_fib.c:fib6_update_sernum
```
```
In lib/dump_stack.c (ffffffff81ab97c8)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff810630fa)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff81064873)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810677e6)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
```
```
In kernel/panic.c (ffffffff810a2d40)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/panic.c:panic
  - kernel/panic.c:nmi_panic
```
```
In kernel/smpboot.c (ffffffff810d189c)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_report_death
  - kernel/smpboot.c:cpu_wait_death
```
```
In kernel/ucount.c (ffffffff810d1b97)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/rt.c (ffffffff810efd6b)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/sched/psi.c (ffffffff811038e5)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
```
```
In kernel/locking/osq_lock.c (ffffffff81106022)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff811060f9)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
```
```
In kernel/locking/qrwlock.c (ffffffff811078e7)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
```
```
In kernel/printk/printk_safe.c (ffffffff8111701e)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_log_store
```
```
In kernel/rcu/tree.c (ffffffff8112b964)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_eqs_special_set
```
```
In kernel/kexec_core.c (ffffffff8115d69c)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/trace/ring_buffer.c (ffffffff811a21a1)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
```
```
In kernel/jump_label.c (ffffffff8122434f)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
```
```
In mm/vmscan.c (ffffffff8123f5c4)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/ksm.c (ffffffff812a8b22)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
```
```
In mm/migrate.c (ffffffff812b8de9)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812bf7cb)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff812c2b78)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/aio.c (ffffffff81344931)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - fs/aio.c:__get_reqs_available
```
```
In block/blk-mq.c (ffffffff814fe7d9)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (ffffffff81501df9)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-rq-qos.c (ffffffff815128e1)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
```
In block/blk-iocost.c (ffffffff8151d8e9)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffffffff81569fdb)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/rapidio/rio.c (ffffffff815c22c2)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/iommu/iova.c (ffffffff816ebd98)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
```
```
In drivers/vfio/vfio.c (ffffffff817e0575)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
```
In drivers/thermal/thermal_core.c (ffffffff81898c99)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
```
In net/core/dev.c (ffffffff8193f8a2)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
```
```
In net/ipv4/route.c (ffffffff819bb065)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv6/ip6_fib.c (ffffffff81a6aa4b)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_update_sernum_upto_root
  - net/ipv6/ip6_fib.c:fib6_update_sernum
```
```
In lib/dump_stack.c (ffffffff81ac5c18)
Location: arch/x86/include/asm/atomic.h:192
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
</details>
</li>
</ul>

## Differences
