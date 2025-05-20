# Function: <code>atomic_cmpxchg_relaxed</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff81111249)
Location: include/asm-generic/atomic-instrumented.h:682
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff8110e3c9)
Location: include/asm-generic/atomic-instrumented.h:682
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
```
</details>
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
In kernel/locking/qspinlock.c (ffff80001016abf8)
Location: include/asm-generic/atomic-instrumented.h:681
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:queued_spin_lock_slowpath
```
```
In kernel/locking/qrwlock.c (ffff80001016c92c)
Location: include/asm-generic/atomic-instrumented.h:681
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
```
```
In lib/refcount.c (ffff800010637acc)
Location: include/asm-generic/atomic-instrumented.h:681
Inline: True
```
```
In drivers/iommu/arm-smmu-v3.c (ffff8000108d51a0)
Location: include/asm-generic/atomic-instrumented.h:681
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_cmdq_issue_cmdlist
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_cmdq_issue_cmdlist
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
In kernel/panic.c (c03549d8)
Location: arch/arm/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/panic.c:panic
  - kernel/panic.c:nmi_panic
```
```
In kernel/smpboot.c (c037f7e8)
Location: arch/arm/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_report_death
  - kernel/smpboot.c:cpu_wait_death
```
```
In kernel/ucount.c (c037fd10)
Location: arch/arm/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
  - kernel/ucount.c:inc_ucount
```
```
In kernel/kmod.c (c0380004)
Location: arch/arm/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/rt.c (c039c4b4)
Location: arch/arm/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/sched/psi.c (c03b2f60)
Location: arch/arm/include/asm/atomic.h:108
Inline: True
```
```
In kernel/locking/mutex.c (c0e9c018)
Location: arch/arm/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
  - kernel/locking/mutex.c:mutex_unlock
  - kernel/locking/mutex.c:mutex_lock
  - kernel/locking/mutex.c:mutex_trylock_recursive
```
```
In kernel/locking/rwsem.c (c03b6074)
Location: arch/arm/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_write_trylock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/locking/osq_lock.c (c03b6788)
Location: arch/arm/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/printk/printk_safe.c (c03c89f8)
Location: arch/arm/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_log_store
```
```
In kernel/rcu/tree.c (c03de4ac)
Location: arch/arm/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_eqs_special_set
```
```
In kernel/module.c (c0408214)
Location: arch/arm/include/asm/atomic.h:108
Inline: True
```
```
In kernel/kexec_core.c (c04109fc)
Location: arch/arm/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/trace/ring_buffer.c (c0455ea0)
Location: arch/arm/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/events/core.c (c04c78e8)
Location: arch/arm/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:free_event
```
```
In kernel/events/ring_buffer.c (c04d22cc)
Location: arch/arm/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In mm/vmscan.c (c04f5004)
Location: arch/arm/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/mmap.c (c0521eb0)
Location: arch/arm/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
```
In mm/ksm.c (c05480e4)
Location: arch/arm/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
```
```
In mm/migrate.c (c0552658)
Location: arch/arm/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memfd.c (c0566eb4)
Location: arch/arm/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (c0567864)
Location: arch/arm/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/exec.c (c0574408)
Location: arch/arm/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file
  - fs/exec.c:do_open_execat
```
```
In fs/namei.c (c057e8b8)
Location: arch/arm/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/nsfs.c (c05ae5ac)
Location: arch/arm/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In fs/aio.c (c05cdf40)
Location: arch/arm/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/aio.c:__get_reqs_available
```
```
In fs/io_uring.c (c05d1ea0)
Location: arch/arm/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/io_uring.c:io_account_mem
```
```
In fs/verity/enable.c (c05de118)
Location: arch/arm/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/proc/inode.c (c0601ce4)
Location: arch/arm/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/kernfs/dir.c (c0615cf8)
Location: arch/arm/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
```
```
In block/blk-mq.c (c079c65c)
Location: arch/arm/include/asm/atomic.h:108
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (c07a0224)
Location: arch/arm/include/asm/atomic.h:108
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-rq-qos.c (c07b2494)
Location: arch/arm/include/asm/atomic.h:108
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
```
In block/blk-iocost.c (c07be670)
Location: arch/arm/include/asm/atomic.h:108
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/refcount.c (c07dd42c)
Location: arch/arm/include/asm/atomic.h:108
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_if_one
```
```
In lib/sbitmap.c (c0811c08)
Location: arch/arm/include/asm/atomic.h:108
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/rapidio/rio.c (c08c0dd0)
Location: arch/arm/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/tty/tty_ldsem.c (c0966ab4)
Location: arch/arm/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In drivers/base/power/wakeup.c (c09eeeb8)
Location: arch/arm/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/thermal/thermal_core.c (c0bb4b20)
Location: arch/arm/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
```
In net/core/skbuff.c (c0cd0038)
Location: arch/arm/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dump
```
```
In net/ipv4/route.c (c0d67a00)
Location: arch/arm/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv6/ip6_fib.c (c0e1dc80)
Location: arch/arm/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_new_sernum
```
```
In net/xdp/xdp_umem.c (c0e7b960)
Location: arch/arm/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/dump_stack.c (c0e7fe60)
Location: arch/arm/include/asm/atomic.h:108
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffe000464a16)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
```
</details>
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
