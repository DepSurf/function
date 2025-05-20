# Function: <code>raw_atomic_cmpxchg</code>

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
In <code>6.2</code>: Absent ⚠️
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
Location: include/linux/atomic/atomic-arch-fallback.h:2005
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_nmi_unknown
```
```
In arch/x86/kernel/smp.c (ffffffff8109b873)
Location: include/linux/atomic/atomic-arch-fallback.h:2005
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:native_stop_other_cpus
```
```
In kernel/panic.c (ffffffff810f5fb2)
Location: include/linux/atomic/atomic-arch-fallback.h:2005
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In kernel/sched/build_utility.c (ffffffff81180f08)
Location: include/linux/atomic/atomic-arch-fallback.h:2005
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_rtpoll_worker
  - kernel/sched/build_utility.c:psi_rtpoll_worker
```
```
In kernel/locking/qspinlock.c (ffffffff82159782)
Location: include/linux/atomic/atomic-arch-fallback.h:2005
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
```
```
In kernel/kexec_core.c (ffffffff81214dbc)
Location: include/linux/atomic/atomic-arch-fallback.h:2005
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/irq_work.c (ffffffff812e50b3)
Location: include/linux/atomic/atomic-arch-fallback.h:2005
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_single
```
```
In kernel/jump_label.c (ffffffff81386698)
Location: include/linux/atomic/atomic-arch-fallback.h:2005
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_disable_cpuslocked
```
```
In mm/vmscan.c (ffffffff813b1f37)
Location: include/linux/atomic/atomic-arch-fallback.h:2005
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/rmap.c (ffffffff8140bd7f)
Location: include/linux/atomic/atomic-arch-fallback.h:2005
Inline: True
Inline callers:
  - mm/rmap.c:flush_tlb_batched_pending
```
```
In mm/hugetlb.c (ffffffff81438e2f)
Location: include/linux/atomic/atomic-arch-fallback.h:2005
Inline: True
Inline callers:
  - mm/hugetlb.c:__prep_compound_gigantic_folio
```
```
In mm/migrate.c (ffffffff814699de)
Location: include/linux/atomic/atomic-arch-fallback.h:2005
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff81477838)
Location: include/linux/atomic/atomic-arch-fallback.h:2005
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/page_reporting.c (ffffffff814a75a3)
Location: include/linux/atomic/atomic-arch-fallback.h:2005
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_process
```
```
In fs/mbcache.c (ffffffff8154c4c5)
Location: include/linux/atomic/atomic-arch-fallback.h:2005
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_or_get
```
```
In security/integrity/ima/ima_policy.c (ffffffff81736e14)
Location: include/linux/atomic/atomic-arch-fallback.h:2005
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy_flags
```
```
In block/blk-mq.c (ffffffff81783b31)
Location: include/linux/atomic/atomic-arch-fallback.h:2005
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In block/blk-mq-tag.c (ffffffff81787a29)
Location: include/linux/atomic/atomic-arch-fallback.h:2005
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In io_uring/poll.c (ffffffff817de6c1)
Location: include/linux/atomic/atomic-arch-fallback.h:2005
Inline: True
Inline callers:
  - io_uring/poll.c:__io_arm_poll_handler
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff819078a5)
Location: include/linux/atomic/atomic-arch-fallback.h:2005
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
```
```
In drivers/rapidio/rio.c (ffffffff8196f2a2)
Location: include/linux/atomic/atomic-arch-fallback.h:2005
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd23f2)
Location: include/linux/atomic/atomic-arch-fallback.h:2005
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffffffff81d4901c)
Location: include/linux/atomic/atomic-arch-fallback.h:2005
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
Location: include/linux/atomic/atomic-arch-fallback.h:2014
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:native_stop_other_cpus
```
```
In kernel/sched/build_utility.c (ffffffff8118ec58)
Location: include/linux/atomic/atomic-arch-fallback.h:2014
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_rtpoll_worker
  - kernel/sched/build_utility.c:psi_rtpoll_worker
```
```
In kernel/locking/qspinlock.c (ffffffff8223d002)
Location: include/linux/atomic/atomic-arch-fallback.h:2014
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
```
```
In kernel/irq_work.c (ffffffff81303163)
Location: include/linux/atomic/atomic-arch-fallback.h:2014
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_single
```
```
In kernel/jump_label.c (ffffffff813afb58)
Location: include/linux/atomic/atomic-arch-fallback.h:2014
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_disable_cpuslocked
```
```
In mm/vmscan.c (ffffffff813dafe8)
Location: include/linux/atomic/atomic-arch-fallback.h:2014
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/rmap.c (ffffffff8143862f)
Location: include/linux/atomic/atomic-arch-fallback.h:2014
Inline: True
Inline callers:
  - mm/rmap.c:flush_tlb_batched_pending
```
```
In mm/hugetlb.c (ffffffff8391ad11)
Location: include/linux/atomic/atomic-arch-fallback.h:2014
Inline: True
Inline callers:
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/hugetlb.c:hugetlb_folio_init_tail_vmemmap
  - mm/hugetlb.c:__prep_compound_gigantic_folio
```
```
In mm/migrate.c (ffffffff81498925)
Location: include/linux/atomic/atomic-arch-fallback.h:2014
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff814a6fbb)
Location: include/linux/atomic/atomic-arch-fallback.h:2014
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/page_reporting.c (ffffffff814d85d2)
Location: include/linux/atomic/atomic-arch-fallback.h:2014
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_process
```
```
In fs/mbcache.c (ffffffff815822f5)
Location: include/linux/atomic/atomic-arch-fallback.h:2014
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_or_get
```
```
In security/integrity/ima/ima_policy.c (ffffffff817778d4)
Location: include/linux/atomic/atomic-arch-fallback.h:2014
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy_flags
```
```
In block/blk-mq.c (ffffffff817c5eb4)
Location: include/linux/atomic/atomic-arch-fallback.h:2014
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In block/blk-mq-tag.c (ffffffff817ca0f9)
Location: include/linux/atomic/atomic-arch-fallback.h:2014
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In io_uring/poll.c (ffffffff81822a91)
Location: include/linux/atomic/atomic-arch-fallback.h:2014
Inline: True
Inline callers:
  - io_uring/poll.c:__io_arm_poll_handler
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff81950d2c)
Location: include/linux/atomic/atomic-arch-fallback.h:2014
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
```
```
In drivers/rapidio/rio.c (ffffffff819b9192)
Location: include/linux/atomic/atomic-arch-fallback.h:2014
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c27062)
Location: include/linux/atomic/atomic-arch-fallback.h:2014
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffffffff81dff4bd)
Location: include/linux/atomic/atomic-arch-fallback.h:2014
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
