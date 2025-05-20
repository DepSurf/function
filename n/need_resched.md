# Function: <code>need_resched</code>

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
In arch/x86/kernel/process.c (ffffffff81039001)
Location: include/linux/sched.h:3052
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8105011b)
Location: include/linux/sched.h:3052
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/softirq.c (ffffffff81085902)
Location: include/linux/sched.h:3052
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:irq_exit
```
```
In kernel/sched/core.c (ffffffff818203e5)
Location: include/linux/sched.h:3052
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule
  - kernel/sched/core.c:preempt_schedule_common
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:preempt_schedule_irq
```
```
In kernel/sched/fair.c (ffffffff810be381)
Location: include/linux/sched.h:3052
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In kernel/sched/idle.c (ffffffff810c3e02)
Location: include/linux/sched.h:3052
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_startup_entry
  - kernel/sched/idle.c:cpu_startup_entry
```
```
In kernel/locking/mutex.c (ffffffff810c9a95)
Location: include/linux/sched.h:3052
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_optimistic_spin
  - kernel/locking/mutex.c:mutex_optimistic_spin
  - kernel/locking/mutex.c:mutex_optimistic_spin
```
```
In kernel/locking/osq_lock.c (ffffffff810ca34f)
Location: include/linux/sched.h:3052
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/rwsem-xadd.c (ffffffff810cbcc9)
Location: include/linux/sched.h:3052
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_spin_on_owner
```
```
In kernel/rcu/tree.c (ffffffff810e7263)
Location: include/linux/sched.h:3052
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
```
```
In kernel/time/tick-sched.c (ffffffff810fe6d4)
Location: include/linux/sched.h:3052
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
```
In mm/shmem.c (ffffffff811a87fd)
Location: include/linux/sched.h:3052
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
```
```
In mm/compaction.c (ffffffff811b56a8)
Location: include/linux/sched.h:3052
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:compact_zone
```
```
In mm/memory.c (ffffffff811c0dda)
Location: include/linux/sched.h:3052
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In fs/select.c (ffffffff812211ef)
Location: include/linux/sched.h:3052
Inline: True
Inline callers:
  - fs/select.c:do_select
  - fs/select.c:do_sys_poll
```
```
In fs/dcache.c (ffffffff812232ce)
Location: include/linux/sched.h:3052
Inline: True
Inline callers:
  - fs/dcache.c:select_collect
```
```
In fs/inode.c (ffffffff81228c2d)
Location: include/linux/sched.h:3052
Inline: True
Inline callers:
  - fs/inode.c:evict_inodes
```
```
In fs/fs-writeback.c (ffffffff8123b69d)
Location: include/linux/sched.h:3052
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
```
```
In fs/ext4/mballoc.c (ffffffff812d57a4)
Location: include/linux/sched.h:3052
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
```
In fs/jbd2/checkpoint.c (ffffffff812eccaa)
Location: include/linux/sched.h:3052
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
```
```
In security/keys/gc.c (ffffffff8132f00b)
Location: include/linux/sched.h:3052
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In block/blk-core.c (ffffffff813bbc0a)
Location: include/linux/sched.h:3052
Inline: True
Inline callers:
  - block/blk-core.c:blk_poll
```
```
In drivers/idle/intel_idle.c (ffffffff81479478)
Location: include/linux/sched.h:3052
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle_freeze
```
```
In drivers/xen/preempt.c (ffffffff814c7641)
Location: include/linux/sched.h:3052
Inline: True
Inline callers:
  - drivers/xen/preempt.c:xen_maybe_preempt_hcall
```
```
In drivers/char/random.c (ffffffff8151355c)
Location: include/linux/sched.h:3052
Inline: True
Inline callers:
  - drivers/char/random.c:extract_entropy_user
```
```
In drivers/char/hw_random/core.c (ffffffff8151a613)
Location: include/linux/sched.h:3052
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/cpuidle/driver.c (ffffffff816bc08c)
Location: include/linux/sched.h:3052
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:poll_idle
```
```
In net/socket.c (ffffffff816fdf84)
Location: include/linux/sched.h:3052
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff8170ca3c)
Location: include/linux/sched.h:3052
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/core/datagram.c:__skb_recv_datagram
```
```
In net/sched/sch_generic.c (ffffffff8174161d)
Location: include/linux/sched.h:3052
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/inetpeer.c (ffffffff81757da1)
Location: include/linux/sched.h:3052
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_gc_worker
```
```
In net/ipv4/tcp.c (ffffffff81766e8c)
Location: include/linux/sched.h:3052
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/packet/af_packet.c (ffffffff81807bd9)
Location: include/linux/sched.h:3052
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In arch/x86/kernel/process.c (ffffffff81038043)
Location: include/linux/sched.h:3329
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81050277)
Location: include/linux/sched.h:3329
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/softirq.c (ffffffff81088a94)
Location: include/linux/sched.h:3329
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff8189ab1f)
Location: include/linux/sched.h:3329
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:preempt_schedule_common
  - kernel/sched/core.c:schedule
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/fair.c (ffffffff810c1b6c)
Location: include/linux/sched.h:3329
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In kernel/sched/idle.c (ffffffff810c7cb3)
Location: include/linux/sched.h:3329
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_startup_entry
  - kernel/sched/idle.c:cpu_startup_entry
```
```
In kernel/locking/mutex.c (ffffffff810ce4b2)
Location: include/linux/sched.h:3329
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_optimistic_spin
  - kernel/locking/mutex.c:mutex_optimistic_spin
  - kernel/locking/mutex.c:mutex_optimistic_spin
```
```
In kernel/locking/osq_lock.c (ffffffff810cecdf)
Location: include/linux/sched.h:3329
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/rwsem-xadd.c (ffffffff8189d8fa)
Location: include/linux/sched.h:3329
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_spin_on_owner
```
```
In kernel/rcu/tree.c (ffffffff810ed4cc)
Location: include/linux/sched.h:3329
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
```
```
In kernel/time/tick-sched.c (ffffffff81105a5d)
Location: include/linux/sched.h:3329
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
```
In mm/shmem.c (ffffffff811bf5e8)
Location: include/linux/sched.h:3329
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/compaction.c (ffffffff811d211e)
Location: include/linux/sched.h:3329
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/memory.c (ffffffff811dcafc)
Location: include/linux/sched.h:3329
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/khugepaged.c (ffffffff8121c696)
Location: include/linux/sched.h:3329
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/select.c (ffffffff81249d04)
Location: include/linux/sched.h:3329
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/dcache.c (ffffffff8124b0f1)
Location: include/linux/sched.h:3329
Inline: True
Inline callers:
  - fs/dcache.c:select_collect
```
```
In fs/inode.c (ffffffff81251326)
Location: include/linux/sched.h:3329
Inline: True
Inline callers:
  - fs/inode.c:evict_inodes
```
```
In fs/fs-writeback.c (ffffffff81263517)
Location: include/linux/sched.h:3329
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
```
```
In fs/ext4/mballoc.c (ffffffff8130543f)
Location: include/linux/sched.h:3329
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
```
In fs/jbd2/checkpoint.c (ffffffff8131ada6)
Location: include/linux/sched.h:3329
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In security/keys/gc.c (ffffffff81363cd9)
Location: include/linux/sched.h:3329
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In block/blk-core.c (ffffffff813ffa1a)
Location: include/linux/sched.h:3329
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff814c7921)
Location: include/linux/sched.h:3329
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_freeze
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/xen/preempt.c (ffffffff81517ed2)
Location: include/linux/sched.h:3329
Inline: True
Inline callers:
  - drivers/xen/preempt.c:xen_maybe_preempt_hcall
```
```
In drivers/char/random.c (ffffffff81567ef7)
Location: include/linux/sched.h:3329
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/hw_random/core.c (ffffffff8156d307)
Location: include/linux/sched.h:3329
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/cpuidle/driver.c (ffffffff8171d99c)
Location: include/linux/sched.h:3329
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:poll_idle
```
```
In net/socket.c (ffffffff81763518)
Location: include/linux/sched.h:3329
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff817742bb)
Location: include/linux/sched.h:3329
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/core/dev.c (ffffffff817833c6)
Location: include/linux/sched.h:3329
Inline: True
Inline callers:
  - net/core/dev.c:sk_busy_loop
```
```
In net/sched/sch_generic.c (ffffffff817ae3dd)
Location: include/linux/sched.h:3329
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/inetpeer.c (ffffffff817c404b)
Location: include/linux/sched.h:3329
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_gc_worker
```
```
In net/ipv4/tcp.c (ffffffff817d338c)
Location: include/linux/sched.h:3329
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/packet/af_packet.c (ffffffff81878c8c)
Location: include/linux/sched.h:3329
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In arch/x86/kernel/process.c (ffffffff818d3ba5)
Location: include/linux/sched.h:3498
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff818d3d0b)
Location: include/linux/sched.h:3498
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/softirq.c (ffffffff8108d9d4)
Location: include/linux/sched.h:3498
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff818cf12f)
Location: include/linux/sched.h:3498
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:schedule
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/fair.c (ffffffff810c7b6a)
Location: include/linux/sched.h:3498
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In kernel/sched/idle.c (ffffffff810cd92a)
Location: include/linux/sched.h:3498
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
```
In kernel/locking/mutex.c (ffffffff810d51c0)
Location: include/linux/sched.h:3498
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_optimistic_spin
  - kernel/locking/mutex.c:mutex_optimistic_spin
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff810d58ff)
Location: include/linux/sched.h:3498
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/rwsem-xadd.c (ffffffff818d27ca)
Location: include/linux/sched.h:3498
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_spin_on_owner
```
```
In kernel/rcu/tree.c (ffffffff810f444c)
Location: include/linux/sched.h:3498
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
```
```
In kernel/time/tick-sched.c (ffffffff8110d1ad)
Location: include/linux/sched.h:3498
Inline: True
```
```
In mm/shmem.c (ffffffff811cfc24)
Location: include/linux/sched.h:3498
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/compaction.c (ffffffff811e205b)
Location: include/linux/sched.h:3498
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/memory.c (ffffffff811ec60c)
Location: include/linux/sched.h:3498
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/khugepaged.c (ffffffff8122e0ba)
Location: include/linux/sched.h:3498
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/select.c (ffffffff8125ccd4)
Location: include/linux/sched.h:3498
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/dcache.c (ffffffff8125e0dd)
Location: include/linux/sched.h:3498
Inline: True
Inline callers:
  - fs/dcache.c:select_collect
```
```
In fs/inode.c (ffffffff81264426)
Location: include/linux/sched.h:3498
Inline: True
Inline callers:
  - fs/inode.c:evict_inodes
```
```
In fs/fs-writeback.c (ffffffff81276967)
Location: include/linux/sched.h:3498
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
```
```
In fs/ext4/mballoc.c (ffffffff8131b424)
Location: include/linux/sched.h:3498
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
```
In fs/jbd2/checkpoint.c (ffffffff81330d96)
Location: include/linux/sched.h:3498
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In security/keys/gc.c (ffffffff8137a4f9)
Location: include/linux/sched.h:3498
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In block/blk-mq.c (ffffffff81422089)
Location: include/linux/sched.h:3498
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff814e9846)
Location: include/linux/sched.h:3498
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_freeze
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/xen/preempt.c (ffffffff815443f2)
Location: include/linux/sched.h:3498
Inline: True
Inline callers:
  - drivers/xen/preempt.c:xen_maybe_preempt_hcall
```
```
In drivers/char/random.c (ffffffff81594637)
Location: include/linux/sched.h:3498
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/hw_random/core.c (ffffffff81599a7d)
Location: include/linux/sched.h:3498
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/cpuidle/driver.c (ffffffff818d4055)
Location: include/linux/sched.h:3498
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:poll_idle
```
```
In net/core/dev.c (ffffffff817aec5f)
Location: include/linux/sched.h:3498
Inline: True
Inline callers:
  - net/core/dev.c:sk_busy_loop
```
```
In net/sched/sch_generic.c (ffffffff817dda6d)
Location: include/linux/sched.h:3498
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/inetpeer.c (ffffffff817f3b6b)
Location: include/linux/sched.h:3498
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_gc_worker
```
```
In net/packet/af_packet.c (ffffffff818ad20c)
Location: include/linux/sched.h:3498
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In arch/x86/kernel/process.c (ffffffff8190ad0c)
Location: include/linux/sched.h:1577
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8190ae6b)
Location: include/linux/sched.h:1577
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/softirq.c (ffffffff8108aa04)
Location: include/linux/sched.h:1577
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff819066cf)
Location: include/linux/sched.h:1577
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:schedule_idle
  - kernel/sched/core.c:schedule
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/fair.c (ffffffff810c17f1)
Location: include/linux/sched.h:1577
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In kernel/sched/idle.c (ffffffff810ca33f)
Location: include/linux/sched.h:1577
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
```
In kernel/locking/mutex.c (ffffffff810d41ae)
Location: include/linux/sched.h:1577
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff810d487f)
Location: include/linux/sched.h:1577
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/rwsem-xadd.c (ffffffff81909691)
Location: include/linux/sched.h:1577
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_spin_on_owner
```
```
In kernel/rcu/tree.c (ffffffff810f534f)
Location: include/linux/sched.h:1577
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
```
```
In kernel/time/tick-sched.c (ffffffff8110f01b)
Location: include/linux/sched.h:1577
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
```
In kernel/bpf/verifier.c (ffffffff81195be3)
Location: include/linux/sched.h:1577
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
```
In mm/shmem.c (ffffffff811d9383)
Location: include/linux/sched.h:1577
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/compaction.c (ffffffff811ebe61)
Location: include/linux/sched.h:1577
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/memory.c (ffffffff811f72f8)
Location: include/linux/sched.h:1577
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/khugepaged.c (ffffffff8123a39a)
Location: include/linux/sched.h:1577
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/select.c (ffffffff8126988d)
Location: include/linux/sched.h:1577
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/dcache.c (ffffffff8126b8a1)
Location: include/linux/sched.h:1577
Inline: True
```
```
In fs/inode.c (ffffffff81270e86)
Location: include/linux/sched.h:1577
Inline: True
Inline callers:
  - fs/inode.c:evict_inodes
```
```
In fs/fs-writeback.c (ffffffff81283ddd)
Location: include/linux/sched.h:1577
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
```
```
In fs/ext4/mballoc.c (ffffffff81312811)
Location: include/linux/sched.h:1577
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
```
In fs/jbd2/checkpoint.c (ffffffff81345cf6)
Location: include/linux/sched.h:1577
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In security/keys/gc.c (ffffffff8138e0e3)
Location: include/linux/sched.h:1577
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In block/blk-mq.c (ffffffff81430844)
Location: include/linux/sched.h:1577
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff814f5466)
Location: include/linux/sched.h:1577
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_freeze
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/xen/preempt.c (ffffffff81558282)
Location: include/linux/sched.h:1577
Inline: True
Inline callers:
  - drivers/xen/preempt.c:xen_maybe_preempt_hcall
```
```
In drivers/char/random.c (ffffffff815a8661)
Location: include/linux/sched.h:1577
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/hw_random/core.c (ffffffff815adaad)
Location: include/linux/sched.h:1577
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/cpuidle/driver.c (ffffffff8190b1e9)
Location: include/linux/sched.h:1577
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:poll_idle
```
```
In net/core/dev.c (ffffffff817cd629)
Location: include/linux/sched.h:1577
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
```
```
In net/sched/sch_generic.c (ffffffff817fd082)
Location: include/linux/sched.h:1577
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/bpf/test_run.c (ffffffff8180c6cd)
Location: include/linux/sched.h:1577
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/inetpeer.c (ffffffff81813f4b)
Location: include/linux/sched.h:1577
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_gc_worker
```
```
In net/packet/af_packet.c (ffffffff818d27bb)
Location: include/linux/sched.h:1577
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In arch/x86/kernel/process.c (ffffffff8199507f)
Location: include/linux/sched.h:1611
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff819951db)
Location: include/linux/sched.h:1611
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/softirq.c (ffffffff810916d4)
Location: include/linux/sched.h:1611
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff8199076b)
Location: include/linux/sched.h:1611
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:schedule_idle
  - kernel/sched/core.c:schedule
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/fair.c (ffffffff810c8fb3)
Location: include/linux/sched.h:1611
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In kernel/sched/idle.c (ffffffff810d1b5c)
Location: include/linux/sched.h:1611
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
```
In kernel/locking/mutex.c (ffffffff810dc102)
Location: include/linux/sched.h:1611
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff810dc825)
Location: include/linux/sched.h:1611
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/rwsem-xadd.c (ffffffff81993681)
Location: include/linux/sched.h:1611
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_spin_on_owner
```
```
In kernel/rcu/tree.c (ffffffff810ff273)
Location: include/linux/sched.h:1611
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
```
```
In kernel/time/tick-sched.c (ffffffff8111a03b)
Location: include/linux/sched.h:1611
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
```
In kernel/bpf/verifier.c (ffffffff811a64f0)
Location: include/linux/sched.h:1611
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
```
In mm/shmem.c (ffffffff811ee6a9)
Location: include/linux/sched.h:1611
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/compaction.c (ffffffff81202213)
Location: include/linux/sched.h:1611
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/memory.c (ffffffff8120a4b0)
Location: include/linux/sched.h:1611
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/khugepaged.c (ffffffff812591bc)
Location: include/linux/sched.h:1611
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/select.c (ffffffff8128c281)
Location: include/linux/sched.h:1611
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/dcache.c (ffffffff8128e131)
Location: include/linux/sched.h:1611
Inline: True
```
```
In fs/inode.c (ffffffff812938d3)
Location: include/linux/sched.h:1611
Inline: True
Inline callers:
  - fs/inode.c:evict_inodes
```
```
In fs/fs-writeback.c (ffffffff812a6b25)
Location: include/linux/sched.h:1611
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
```
```
In fs/ext4/mballoc.c (ffffffff81337190)
Location: include/linux/sched.h:1611
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
```
In fs/jbd2/checkpoint.c (ffffffff8136a398)
Location: include/linux/sched.h:1611
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In security/keys/gc.c (ffffffff813b35fa)
Location: include/linux/sched.h:1611
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In block/blk-mq.c (ffffffff8145bd33)
Location: include/linux/sched.h:1611
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff81535ce6)
Location: include/linux/sched.h:1611
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/xen/preempt.c (ffffffff815bc416)
Location: include/linux/sched.h:1611
Inline: True
Inline callers:
  - drivers/xen/preempt.c:xen_maybe_preempt_hcall
```
```
In drivers/char/random.c (ffffffff8160efc6)
Location: include/linux/sched.h:1611
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/hw_random/core.c (ffffffff81614574)
Location: include/linux/sched.h:1611
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/cpuidle/poll_state.c (ffffffff8199557a)
Location: include/linux/sched.h:1611
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/dev.c (ffffffff81846e34)
Location: include/linux/sched.h:1611
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
```
```
In net/sched/sch_generic.c (ffffffff8187ab28)
Location: include/linux/sched.h:1611
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/bpf/test_run.c (ffffffff8188b6d1)
Location: include/linux/sched.h:1611
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/packet/af_packet.c (ffffffff81957e1f)
Location: include/linux/sched.h:1611
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In arch/x86/kernel/process.c (ffffffff819f15e6)
Location: include/linux/sched.h:1725
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff819f173b)
Location: include/linux/sched.h:1725
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/softirq.c (ffffffff810951a6)
Location: include/linux/sched.h:1725
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff819ecf6b)
Location: include/linux/sched.h:1725
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:preempt_schedule_common
  - kernel/sched/core.c:schedule_idle
  - kernel/sched/core.c:schedule
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/idle.c (ffffffff810c4271)
Location: include/linux/sched.h:1725
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
```
In kernel/sched/fair.c (ffffffff810d09dc)
Location: include/linux/sched.h:1725
Inline: True
Inline callers:
  - kernel/sched/fair.c:_nohz_idle_balance
```
```
In kernel/locking/mutex.c (ffffffff810e4751)
Location: include/linux/sched.h:1725
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff810e4e75)
Location: include/linux/sched.h:1725
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/rwsem-xadd.c (ffffffff819efc4a)
Location: include/linux/sched.h:1725
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_spin_on_owner
```
```
In kernel/rcu/tree.c (ffffffff81106c07)
Location: include/linux/sched.h:1725
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
```
```
In kernel/time/tick-sched.c (ffffffff81126cef)
Location: include/linux/sched.h:1725
Inline: True
```
```
In kernel/cgroup/rstat.c (ffffffff81143e07)
Location: include/linux/sched.h:1725
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/bpf/verifier.c (ffffffff811bc448)
Location: include/linux/sched.h:1725
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
```
In mm/shmem.c (ffffffff81213707)
Location: include/linux/sched.h:1725
Inline: True
Inline callers:
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/compaction.c (ffffffff812235d3)
Location: include/linux/sched.h:1725
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/memory.c (ffffffff8122b31d)
Location: include/linux/sched.h:1725
Inline: True
```
```
In mm/khugepaged.c (ffffffff8127d59c)
Location: include/linux/sched.h:1725
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memfd.c (ffffffff81294227)
Location: include/linux/sched.h:1725
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
```
In fs/select.c (ffffffff812b2b62)
Location: include/linux/sched.h:1725
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/dcache.c (ffffffff812b46d4)
Location: include/linux/sched.h:1725
Inline: True
```
```
In fs/inode.c (ffffffff812b9a73)
Location: include/linux/sched.h:1725
Inline: True
Inline callers:
  - fs/inode.c:evict_inodes
```
```
In fs/fs-writeback.c (ffffffff812cd742)
Location: include/linux/sched.h:1725
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
```
```
In fs/ext4/mballoc.c (ffffffff81365926)
Location: include/linux/sched.h:1725
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
```
In fs/jbd2/checkpoint.c (ffffffff81398a88)
Location: include/linux/sched.h:1725
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In security/keys/gc.c (ffffffff813e3d38)
Location: include/linux/sched.h:1725
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In block/blk-mq.c (ffffffff8148f4a7)
Location: include/linux/sched.h:1725
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff8156b885)
Location: include/linux/sched.h:1725
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/xen/preempt.c (ffffffff815f4ac6)
Location: include/linux/sched.h:1725
Inline: True
Inline callers:
  - drivers/xen/preempt.c:xen_maybe_preempt_hcall
```
```
In drivers/char/random.c (ffffffff81648abe)
Location: include/linux/sched.h:1725
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/hw_random/core.c (ffffffff8164e21f)
Location: include/linux/sched.h:1725
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/cpuidle/poll_state.c (ffffffff819f1b1b)
Location: include/linux/sched.h:1725
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/dev.c (ffffffff8189048e)
Location: include/linux/sched.h:1725
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
```
```
In net/sched/sch_generic.c (ffffffff818ccd03)
Location: include/linux/sched.h:1725
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/bpf/test_run.c (ffffffff818df120)
Location: include/linux/sched.h:1725
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/packet/af_packet.c (ffffffff819afc83)
Location: include/linux/sched.h:1725
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In arch/x86/kernel/process.c (ffffffff81a2ca18)
Location: include/linux/sched.h:1738
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81a2cbdb)
Location: include/linux/sched.h:1738
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/softirq.c (ffffffff8109d516)
Location: include/linux/sched.h:1738
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff81a2819b)
Location: include/linux/sched.h:1738
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:preempt_schedule_common
  - kernel/sched/core.c:schedule_idle
  - kernel/sched/core.c:schedule
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/idle.c (ffffffff810cd531)
Location: include/linux/sched.h:1738
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
```
In kernel/sched/fair.c (ffffffff810da21c)
Location: include/linux/sched.h:1738
Inline: True
Inline callers:
  - kernel/sched/fair.c:_nohz_idle_balance
```
```
In kernel/locking/mutex.c (ffffffff810efd41)
Location: include/linux/sched.h:1738
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff810f0455)
Location: include/linux/sched.h:1738
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/rwsem-xadd.c (ffffffff81a2b67a)
Location: include/linux/sched.h:1738
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_spin_on_owner
```
```
In kernel/rcu/tree.c (ffffffff81112f2c)
Location: include/linux/sched.h:1738
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
```
```
In kernel/time/tick-sched.c (ffffffff811323cf)
Location: include/linux/sched.h:1738
Inline: True
```
```
In kernel/cgroup/rstat.c (ffffffff8114f917)
Location: include/linux/sched.h:1738
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/bpf/verifier.c (ffffffff811cd99b)
Location: include/linux/sched.h:1738
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
```
In mm/shmem.c (ffffffff81226615)
Location: include/linux/sched.h:1738
Inline: True
Inline callers:
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/compaction.c (ffffffff81236633)
Location: include/linux/sched.h:1738
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/memory.c (ffffffff8123e6dd)
Location: include/linux/sched.h:1738
Inline: True
```
```
In mm/khugepaged.c (ffffffff81292200)
Location: include/linux/sched.h:1738
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/select.c (ffffffff812c7c73)
Location: include/linux/sched.h:1738
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/dcache.c (ffffffff812c9954)
Location: include/linux/sched.h:1738
Inline: True
```
```
In fs/inode.c (ffffffff812ceb23)
Location: include/linux/sched.h:1738
Inline: True
Inline callers:
  - fs/inode.c:evict_inodes
```
```
In fs/fs-writeback.c (ffffffff812e2a61)
Location: include/linux/sched.h:1738
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
```
```
In fs/drop_caches.c (ffffffff81322aff)
Location: include/linux/sched.h:1738
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_pagecache_sb
```
```
In fs/ext4/mballoc.c (ffffffff8137dce6)
Location: include/linux/sched.h:1738
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
```
In fs/jbd2/checkpoint.c (ffffffff813b17f8)
Location: include/linux/sched.h:1738
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/fat/fatent.c (ffffffff813c5281)
Location: include/linux/sched.h:1738
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In security/keys/gc.c (ffffffff813fe528)
Location: include/linux/sched.h:1738
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In block/blk-mq.c (ffffffff814a8fb1)
Location: include/linux/sched.h:1738
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff81583405)
Location: include/linux/sched.h:1738
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/xen/preempt.c (ffffffff8160f926)
Location: include/linux/sched.h:1738
Inline: True
Inline callers:
  - drivers/xen/preempt.c:xen_maybe_preempt_hcall
```
```
In drivers/char/random.c (ffffffff81666cde)
Location: include/linux/sched.h:1738
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/hw_random/core.c (ffffffff8166c39f)
Location: include/linux/sched.h:1738
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/cpuidle/poll_state.c (ffffffff81a2d04e)
Location: include/linux/sched.h:1738
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/dev.c (ffffffff818b0d3e)
Location: include/linux/sched.h:1738
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
```
```
In net/sched/sch_generic.c (ffffffff818f806a)
Location: include/linux/sched.h:1738
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/bpf/test_run.c (ffffffff8190bb7c)
Location: include/linux/sched.h:1738
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/packet/af_packet.c (ffffffff819e7270)
Location: include/linux/sched.h:1738
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In arch/x86/kernel/process.c (ffffffff81a9cb76)
Location: include/linux/sched.h:1811
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81a9cd3b)
Location: include/linux/sched.h:1811
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/softirq.c (ffffffff810a1af6)
Location: include/linux/sched.h:1811
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff81a98935)
Location: include/linux/sched.h:1811
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:preempt_schedule_common
  - kernel/sched/core.c:schedule_idle
  - kernel/sched/core.c:schedule
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/idle.c (ffffffff810d5920)
Location: include/linux/sched.h:1811
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
```
In kernel/sched/fair.c (ffffffff810e1587)
Location: include/linux/sched.h:1811
Inline: True
Inline callers:
  - kernel/sched/fair.c:_nohz_idle_balance
```
```
In kernel/locking/mutex.c (ffffffff810f7798)
Location: include/linux/sched.h:1811
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff810f826a)
Location: include/linux/sched.h:1811
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff810f8ace)
Location: include/linux/sched.h:1811
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/rcu/tree.c (ffffffff8111c750)
Location: include/linux/sched.h:1811
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
```
```
In kernel/time/tick-sched.c (ffffffff8113cd31)
Location: include/linux/sched.h:1811
Inline: True
```
```
In kernel/cgroup/rstat.c (ffffffff8115b836)
Location: include/linux/sched.h:1811
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/bpf/verifier.c (ffffffff811e2cb5)
Location: include/linux/sched.h:1811
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
```
In mm/shmem.c (ffffffff81235f30)
Location: include/linux/sched.h:1811
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/compaction.c (ffffffff81247b66)
Location: include/linux/sched.h:1811
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
```
```
In mm/memory.c (ffffffff8125053c)
Location: include/linux/sched.h:1811
Inline: True
```
```
In mm/khugepaged.c (ffffffff812acc52)
Location: include/linux/sched.h:1811
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/select.c (ffffffff812e47cb)
Location: include/linux/sched.h:1811
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/dcache.c (ffffffff812e6331)
Location: include/linux/sched.h:1811
Inline: True
```
```
In fs/inode.c (ffffffff812eba45)
Location: include/linux/sched.h:1811
Inline: True
Inline callers:
  - fs/inode.c:evict_inodes
```
```
In fs/fs-writeback.c (ffffffff81301428)
Location: include/linux/sched.h:1811
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
```
```
In fs/io_uring.c (ffffffff8132eb1d)
Location: include/linux/sched.h:1811
Inline: True
Inline callers:
  - fs/io_uring.c:io_iopoll_check
  - fs/io_uring.c:io_iopoll_getevents
```
```
In fs/drop_caches.c (ffffffff8134a525)
Location: include/linux/sched.h:1811
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_pagecache_sb
```
```
In fs/ext4/mballoc.c (ffffffff813a439d)
Location: include/linux/sched.h:1811
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
```
In fs/jbd2/checkpoint.c (ffffffff813dbe47)
Location: include/linux/sched.h:1811
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/fat/fatent.c (ffffffff813efa65)
Location: include/linux/sched.h:1811
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In security/keys/gc.c (ffffffff8142ab79)
Location: include/linux/sched.h:1811
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In block/blk-mq.c (ffffffff814d693d)
Location: include/linux/sched.h:1811
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff815b3b46)
Location: include/linux/sched.h:1811
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/xen/preempt.c (ffffffff81643731)
Location: include/linux/sched.h:1811
Inline: True
Inline callers:
  - drivers/xen/preempt.c:xen_maybe_preempt_hcall
```
```
In drivers/char/random.c (ffffffff8169ca4c)
Location: include/linux/sched.h:1811
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/hw_random/core.c (ffffffff816a1fd2)
Location: include/linux/sched.h:1811
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/cpuidle/poll_state.c (ffffffff81a9d1b7)
Location: include/linux/sched.h:1811
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/dev.c (ffffffff818fdadc)
Location: include/linux/sched.h:1811
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
```
```
In net/sched/sch_generic.c (ffffffff81957797)
Location: include/linux/sched.h:1811
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/bpf/test_run.c (ffffffff8196dcfe)
Location: include/linux/sched.h:1811
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
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
In arch/x86/kernel/process.c (ffffffff81ad43c6)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81ad458b)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/softirq.c (ffffffff810a80b6)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff81ad0285)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:preempt_schedule_common
  - kernel/sched/core.c:schedule_idle
  - kernel/sched/core.c:schedule
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/idle.c (ffffffff810dff30)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
```
In kernel/sched/fair.c (ffffffff810ebc27)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/fair.c:_nohz_idle_balance
```
```
In kernel/locking/mutex.c (ffffffff81103558)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff8110409a)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff811048de)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/rcu/tree.c (ffffffff81127b6f)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/time/tick-sched.c (ffffffff81148ad1)
Location: include/linux/sched.h:1804
Inline: True
```
```
In kernel/cgroup/rstat.c (ffffffff81167456)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/bpf/verifier.c (ffffffff811ef532)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
```
In mm/shmem.c (ffffffff81244170)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/compaction.c (ffffffff81255fc6)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
```
```
In mm/memory.c (ffffffff8125eaec)
Location: include/linux/sched.h:1804
Inline: True
```
```
In mm/khugepaged.c (ffffffff812be522)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In fs/select.c (ffffffff812f6192)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/dcache.c (ffffffff812f7ccb)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/dcache.c:select_collect2
  - fs/dcache.c:select_collect
```
```
In fs/inode.c (ffffffff812fe6db)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
```
```
In fs/libfs.c (ffffffff8130ca75)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/libfs.c:scan_positives
```
```
In fs/fs-writeback.c (ffffffff81313b08)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
```
```
In fs/io_uring.c (ffffffff8134202d)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/io_uring.c:io_iopoll_check
  - fs/io_uring.c:io_iopoll_getevents
```
```
In fs/drop_caches.c (ffffffff813627c5)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_pagecache_sb
```
```
In fs/ext4/mballoc.c (ffffffff813bd20d)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
```
In fs/jbd2/checkpoint.c (ffffffff813f5eb7)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/fat/fatent.c (ffffffff81409ad5)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In security/keys/gc.c (ffffffff814448c9)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In block/blk-mq.c (ffffffff814efc96)
Location: include/linux/sched.h:1804
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff815d4d86)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/xen/preempt.c (ffffffff81665cd1)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - drivers/xen/preempt.c:xen_maybe_preempt_hcall
```
```
In drivers/char/mem.c (ffffffff816baea5)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (ffffffff816bf7bc)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/hw_random/core.c (ffffffff816c4d3f)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/cpuidle/poll_state.c (ffffffff81ad49bf)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/dev.c (ffffffff81935862)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
```
```
In net/sched/sch_generic.c (ffffffff8198dc37)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/bpf/test_run.c (ffffffff819a46cb)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
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
In arch/x86/entry/common.c (ffffffff81bbc9cf)
Location: include/linux/sched.h:1854
Inline: True
Inline callers:
  - arch/x86/entry/common.c:xen_pv_evtchn_do_upcall
```
```
In arch/x86/kernel/process.c (ffffffff81bcc4b2)
Location: include/linux/sched.h:1854
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81068aad)
Location: include/linux/sched.h:1854
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In kernel/softirq.c (ffffffff810af99d)
Location: include/linux/sched.h:1854
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit_rcu
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff81bc89e5)
Location: include/linux/sched.h:1854
Inline: True
Inline callers:
  - kernel/sched/core.c:_cond_resched
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:schedule_idle
  - kernel/sched/core.c:schedule
  - kernel/sched/core.c:nohz_csd_func
```
```
In kernel/sched/idle.c (ffffffff810e8417)
Location: include/linux/sched.h:1854
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:cpuidle_idle_call
```
```
In kernel/sched/fair.c (ffffffff810f5a5b)
Location: include/linux/sched.h:1854
Inline: True
Inline callers:
  - kernel/sched/fair.c:_nohz_idle_balance
```
```
In kernel/locking/mutex.c (ffffffff8110e077)
Location: include/linux/sched.h:1854
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff8110ec9e)
Location: include/linux/sched.h:1854
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff8110f690)
Location: include/linux/sched.h:1854
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/rcu/tree.c (ffffffff8113642a)
Location: include/linux/sched.h:1854
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/time/tick-sched.c (ffffffff81158972)
Location: include/linux/sched.h:1854
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:can_stop_idle_tick
```
```
In kernel/cgroup/rstat.c (ffffffff81178c52)
Location: include/linux/sched.h:1854
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/bpf/verifier.c (ffffffff8121233f)
Location: include/linux/sched.h:1854
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
```
In mm/shmem.c (ffffffff8126e079)
Location: include/linux/sched.h:1854
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/compaction.c (ffffffff812846ae)
Location: include/linux/sched.h:1854
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
```
```
In mm/memory.c (ffffffff8128f6c4)
Location: include/linux/sched.h:1854
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/khugepaged.c (ffffffff812f22ce)
Location: include/linux/sched.h:1854
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
```
```
In fs/select.c (ffffffff8132e093)
Location: include/linux/sched.h:1854
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/dcache.c (ffffffff81330f83)
Location: include/linux/sched.h:1854
Inline: True
Inline callers:
  - fs/dcache.c:select_collect2
  - fs/dcache.c:select_collect
```
```
In fs/inode.c (ffffffff81337712)
Location: include/linux/sched.h:1854
Inline: True
Inline callers:
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
```
```
In fs/libfs.c (ffffffff81346495)
Location: include/linux/sched.h:1854
Inline: True
Inline callers:
  - fs/libfs.c:scan_positives
```
```
In fs/fs-writeback.c (ffffffff8134d3c3)
Location: include/linux/sched.h:1854
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
```
```
In fs/io_uring.c (ffffffff8138565e)
Location: include/linux/sched.h:1854
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_exit_work
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
```
```
In fs/drop_caches.c (ffffffff813a8595)
Location: include/linux/sched.h:1854
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_pagecache_sb
```
```
In fs/ext4/mballoc.c (ffffffff814092b3)
Location: include/linux/sched.h:1854
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
```
In fs/jbd2/checkpoint.c (ffffffff8144325a)
Location: include/linux/sched.h:1854
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/fat/fatent.c (ffffffff814576a2)
Location: include/linux/sched.h:1854
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In security/keys/gc.c (ffffffff8149592c)
Location: include/linux/sched.h:1854
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In block/blk-mq.c (ffffffff8154eff6)
Location: include/linux/sched.h:1854
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff8167e8cd)
Location: include/linux/sched.h:1854
Inline: True
```
```
In drivers/char/mem.c (ffffffff8176f1b3)
Location: include/linux/sched.h:1854
Inline: True
Inline callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (ffffffff81772e96)
Location: include/linux/sched.h:1854
Inline: True
Inline callers:
  - drivers/char/random.c:extract_crng_user
```
```
In drivers/char/hw_random/core.c (ffffffff817795e8)
Location: include/linux/sched.h:1854
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/cpuidle/poll_state.c (ffffffff81bcc9b1)
Location: include/linux/sched.h:1854
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/dev.c (ffffffff81a0a547)
Location: include/linux/sched.h:1854
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
```
```
In net/bpf/test_run.c (ffffffff81a7f23d)
Location: include/linux/sched.h:1854
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
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
In arch/x86/kernel/process.c (ffffffff81c4518f)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81067b0c)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8106a74d)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In kernel/softirq.c (ffffffff810ab12d)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit_rcu
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff81c41a05)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:schedule_idle
  - kernel/sched/core.c:schedule
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:nohz_csd_func
```
```
In kernel/sched/idle.c (ffffffff810e6007)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:cpuidle_idle_call
```
```
In kernel/sched/fair.c (ffffffff810f3b6b)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - kernel/sched/fair.c:_nohz_idle_balance
```
```
In kernel/locking/mutex.c (ffffffff8110b33d)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff8110beae)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff8110c850)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/rcu/tree.c (ffffffff81131c6f)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/entry/common.c (ffffffff8113bbe4)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_exit_cond_resched
```
```
In kernel/entry/kvm.c (ffffffff8113be54)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - kernel/entry/kvm.c:xfer_to_guest_mode_work
```
```
In kernel/time/tick-sched.c (ffffffff81154982)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:can_stop_idle_tick
```
```
In kernel/cgroup/rstat.c (ffffffff811758a2)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/bpf/verifier.c (ffffffff8121308e)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
```
In mm/shmem.c (ffffffff8127c279)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/compaction.c (ffffffff8128e9d1)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
```
```
In mm/memory.c (ffffffff8129a1d4)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/khugepaged.c (ffffffff812fe785)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
```
```
In fs/select.c (ffffffff8133990b)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/dcache.c (ffffffff8133c913)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - fs/dcache.c:select_collect2
  - fs/dcache.c:select_collect
```
```
In fs/inode.c (ffffffff81343052)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
```
```
In fs/libfs.c (ffffffff81352985)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - fs/libfs.c:scan_positives
```
```
In fs/fs-writeback.c (ffffffff8135a2bc)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
```
```
In fs/io_uring.c (ffffffff813976b4)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - fs/io_uring.c:io_iopoll_check
  - fs/io_uring.c:io_iopoll_check
```
```
In fs/drop_caches.c (ffffffff813b9915)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_pagecache_sb
```
```
In fs/ext4/mballoc.c (ffffffff8141b7ba)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
```
In fs/jbd2/checkpoint.c (ffffffff8145f3ba)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/fat/fatent.c (ffffffff81473a62)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In security/keys/gc.c (ffffffff814b338c)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In block/blk-mq.c (ffffffff8156cddd)
Location: include/linux/sched.h:1915
Inline: True
```
```
In block/blk-cgroup.c (ffffffff8158699d)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
```
```
In drivers/idle/intel_idle.c (ffffffff8169d5cd)
Location: include/linux/sched.h:1915
Inline: True
```
```
In drivers/char/mem.c (ffffffff81789b93)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (ffffffff8178de86)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - drivers/char/random.c:extract_crng_user
```
```
In drivers/char/hw_random/core.c (ffffffff81793d58)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/cpuidle/poll_state.c (ffffffff81c45511)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/dev.c (ffffffff81a0c877)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
```
```
In net/bpf/test_run.c (ffffffff81a88cd0)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
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
In arch/x86/kernel/process.c (ffffffff81c3840c)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81067cdd)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8106b214)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In kernel/softirq.c (ffffffff810ac31d)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit_rcu
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff81c33975)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:schedule_idle
  - kernel/sched/core.c:schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:nohz_csd_func
```
```
In kernel/sched/idle.c (ffffffff810e7fcf)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:cpuidle_idle_call
```
```
In kernel/sched/fair.c (ffffffff810f6a74)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_run_idle_balance
```
```
In kernel/locking/mutex.c (ffffffff8110d1cd)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff8110dcd4)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff8110e680)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/rcu/tree.c (ffffffff81132c1b)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/entry/common.c (ffffffff8113ced4)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_exit_cond_resched
```
```
In kernel/entry/kvm.c (ffffffff8113d10f)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
```
```
In kernel/time/tick-sched.c (ffffffff81155e02)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:can_stop_idle_tick
```
```
In kernel/cgroup/rstat.c (ffffffff8117640b)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/bpf/verifier.c (ffffffff8121553e)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
```
In mm/shmem.c (ffffffff81281439)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/compaction.c (ffffffff81294061)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
```
```
In mm/memory.c (ffffffff8129f3f6)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/khugepaged.c (ffffffff81305405)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
```
```
In fs/select.c (ffffffff8133fea7)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/dcache.c (ffffffff81342d93)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - fs/dcache.c:select_collect2
  - fs/dcache.c:select_collect
```
```
In fs/inode.c (ffffffff81349312)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
```
```
In fs/libfs.c (ffffffff81359775)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - fs/libfs.c:scan_positives
```
```
In fs/fs-writeback.c (ffffffff81360f2c)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
```
```
In fs/io_uring.c (ffffffff813a19ea)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - fs/io_uring.c:__do_sys_io_uring_enter
```
```
In fs/drop_caches.c (ffffffff813c0a66)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_pagecache_sb
```
```
In fs/ext4/mballoc.c (ffffffff81421a9e)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
```
In fs/jbd2/checkpoint.c (ffffffff81464c2a)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/fat/fatent.c (ffffffff814794ae)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In security/keys/gc.c (ffffffff814b91d1)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In block/blk-mq.c (ffffffff81574c7d)
Location: include/linux/sched.h:1987
Inline: True
```
```
In block/blk-cgroup.c (ffffffff8158d6ad)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
```
```
In drivers/idle/intel_idle.c (ffffffff81680354)
Location: include/linux/sched.h:1987
Inline: True
```
```
In drivers/char/mem.c (ffffffff8176d403)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (ffffffff81770836)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - drivers/char/random.c:extract_crng_user
```
```
In drivers/char/hw_random/core.c (ffffffff81776935)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/cpuidle/poll_state.c (ffffffff81c38791)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/dev.c (ffffffff819f2b57)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
```
```
In net/bpf/test_run.c (ffffffff81a70b8d)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_timer_continue
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
In arch/x86/kernel/process.c (ffffffff81d56c9c)
Location: include/linux/sched.h:2104
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8107213d)
Location: include/linux/sched.h:2104
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81075d34)
Location: include/linux/sched.h:2104
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In kernel/softirq.c (ffffffff810bd97d)
Location: include/linux/sched.h:2104
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit_rcu
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff81d52335)
Location: include/linux/sched.h:2104
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:schedule_idle
  - kernel/sched/core.c:schedule
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:nohz_csd_func
```
```
In kernel/sched/idle.c (ffffffff810ff68f)
Location: include/linux/sched.h:2104
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:cpuidle_idle_call
```
```
In kernel/sched/fair.c (ffffffff81110a00)
Location: include/linux/sched.h:2104
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_run_idle_balance
```
```
In kernel/locking/mutex.c (ffffffff8112ca0d)
Location: include/linux/sched.h:2104
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff8112d4c3)
Location: include/linux/sched.h:2104
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff8112ddf1)
Location: include/linux/sched.h:2104
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/rtmutex_api.c (ffffffff81d549ed)
Location: include/linux/sched.h:2104
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff81154e4b)
Location: include/linux/sched.h:2104
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/entry/common.c (ffffffff8115fff4)
Location: include/linux/sched.h:2104
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_exit_cond_resched
```
```
In kernel/entry/kvm.c (ffffffff8116025c)
Location: include/linux/sched.h:2104
Inline: True
Inline callers:
  - kernel/entry/kvm.c:xfer_to_guest_mode_work
```
```
In kernel/time/tick-sched.c (ffffffff8117aa92)
Location: include/linux/sched.h:2104
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:can_stop_idle_tick
```
```
In kernel/cgroup/rstat.c (ffffffff8119da49)
Location: include/linux/sched.h:2104
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/bpf/verifier.c (ffffffff8124bb30)
Location: include/linux/sched.h:2104
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
```
In mm/shmem.c (ffffffff812bca18)
Location: include/linux/sched.h:2104
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/compaction.c (ffffffff812d45de)
Location: include/linux/sched.h:2104
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
```
```
In mm/memory.c (ffffffff812e0664)
Location: include/linux/sched.h:2104
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/khugepaged.c (ffffffff8134f255)
Location: include/linux/sched.h:2104
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
```
```
In fs/select.c (ffffffff8138d87d)
Location: include/linux/sched.h:2104
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/dcache.c (ffffffff813904d3)
Location: include/linux/sched.h:2104
Inline: True
Inline callers:
  - fs/dcache.c:select_collect2
  - fs/dcache.c:select_collect
```
```
In fs/inode.c (ffffffff81397062)
Location: include/linux/sched.h:2104
Inline: True
Inline callers:
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
```
```
In fs/libfs.c (ffffffff813a7c15)
Location: include/linux/sched.h:2104
Inline: True
Inline callers:
  - fs/libfs.c:scan_positives
```
```
In fs/fs-writeback.c (ffffffff813af59c)
Location: include/linux/sched.h:2104
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
```
```
In fs/io_uring.c (ffffffff813f03e5)
Location: include/linux/sched.h:2104
Inline: True
Inline callers:
  - fs/io_uring.c:__do_sys_io_uring_enter
```
```
In fs/drop_caches.c (ffffffff81410961)
Location: include/linux/sched.h:2104
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_pagecache_sb
```
```
In fs/ext4/mballoc.c (ffffffff814743f5)
Location: include/linux/sched.h:2104
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
```
```
In fs/jbd2/checkpoint.c (ffffffff814ba57a)
Location: include/linux/sched.h:2104
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/fat/fatent.c (ffffffff814d0aed)
Location: include/linux/sched.h:2104
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In security/keys/gc.c (ffffffff81511a01)
Location: include/linux/sched.h:2104
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In block/blk-mq.c (ffffffff815d91cc)
Location: include/linux/sched.h:2104
Inline: True
```
```
In block/blk-cgroup.c (ffffffff815f312d)
Location: include/linux/sched.h:2104
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
```
```
In drivers/idle/intel_idle.c (ffffffff816f50c4)
Location: include/linux/sched.h:2104
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff817bf4b4)
Location: include/linux/sched.h:2104
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
```
```
In drivers/char/mem.c (ffffffff817f2d93)
Location: include/linux/sched.h:2104
Inline: True
Inline callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (ffffffff817f6244)
Location: include/linux/sched.h:2104
Inline: True
```
```
In drivers/char/hw_random/core.c (ffffffff817fc8f5)
Location: include/linux/sched.h:2104
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/cpuidle/poll_state.c (ffffffff81d57071)
Location: include/linux/sched.h:2104
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/dev.c (ffffffff81aa4a27)
Location: include/linux/sched.h:2104
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
```
```
In net/bpf/test_run.c (ffffffff81b2a4ad)
Location: include/linux/sched.h:2104
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_timer_continue
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
In arch/x86/kernel/process.c (ffffffff81f28f0c)
Location: include/linux/sched.h:2194
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81080525)
Location: include/linux/sched.h:2194
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8108477d)
Location: include/linux/sched.h:2194
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In kernel/softirq.c (ffffffff810d45f0)
Location: include/linux/sched.h:2194
Inline: True
Inline callers:
  - kernel/softirq.c:__irq_exit_rcu
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff81f226e4)
Location: include/linux/sched.h:2194
Inline: True
Inline callers:
  - kernel/sched/core.c:__cond_resched
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:preempt_schedule_notrace
  - kernel/sched/core.c:preempt_schedule
  - kernel/sched/core.c:schedule_idle
  - kernel/sched/core.c:schedule
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:nohz_csd_func
```
```
In kernel/sched/fair.c (ffffffff8112cbe2)
Location: include/linux/sched.h:2194
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_run_idle_balance
```
```
In kernel/sched/build_policy.c (ffffffff8113369f)
Location: include/linux/sched.h:2194
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:do_idle
  - kernel/sched/build_policy.c:cpuidle_idle_call
```
```
In kernel/locking/mutex.c (ffffffff8114d9d1)
Location: include/linux/sched.h:2194
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff81f25674)
Location: include/linux/sched.h:2194
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff8114ee00)
Location: include/linux/sched.h:2194
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/rtmutex_api.c (ffffffff81f2657d)
Location: include/linux/sched.h:2194
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff8117c25c)
Location: include/linux/sched.h:2194
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/entry/common.c (ffffffff81189ca3)
Location: include/linux/sched.h:2194
Inline: True
```
```
In kernel/entry/kvm.c (ffffffff8118a755)
Location: include/linux/sched.h:2194
Inline: True
Inline callers:
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
```
```
In kernel/time/tick-sched.c (ffffffff811b033f)
Location: include/linux/sched.h:2194
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:can_stop_idle_tick
```
```
In kernel/cgroup/rstat.c (ffffffff811cdcd4)
Location: include/linux/sched.h:2194
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/bpf/verifier.c (ffffffff81292ce8)
Location: include/linux/sched.h:2194
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
```
In mm/shmem.c (ffffffff81318ab0)
Location: include/linux/sched.h:2194
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/compaction.c (ffffffff81333593)
Location: include/linux/sched.h:2194
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
```
```
In mm/memory.c (ffffffff81340d40)
Location: include/linux/sched.h:2194
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/khugepaged.c (ffffffff813c5f92)
Location: include/linux/sched.h:2194
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
```
```
In fs/select.c (ffffffff8140ea79)
Location: include/linux/sched.h:2194
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/dcache.c (ffffffff8141261f)
Location: include/linux/sched.h:2194
Inline: True
Inline callers:
  - fs/dcache.c:select_collect2
  - fs/dcache.c:select_collect
```
```
In fs/inode.c (ffffffff81419170)
Location: include/linux/sched.h:2194
Inline: True
Inline callers:
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
```
```
In fs/libfs.c (ffffffff8142a895)
Location: include/linux/sched.h:2194
Inline: True
Inline callers:
  - fs/libfs.c:scan_positives
```
```
In fs/fs-writeback.c (ffffffff81434055)
Location: include/linux/sched.h:2194
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
```
```
In fs/drop_caches.c (ffffffff814862ae)
Location: include/linux/sched.h:2194
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_pagecache_sb
```
```
In fs/ext4/mballoc.c (ffffffff814f62dd)
Location: include/linux/sched.h:2194
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
```
```
In fs/jbd2/checkpoint.c (ffffffff815443ca)
Location: include/linux/sched.h:2194
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/fat/fatent.c (ffffffff8155d677)
Location: include/linux/sched.h:2194
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In security/keys/gc.c (ffffffff815a3d5b)
Location: include/linux/sched.h:2194
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In block/blk-mq.c (ffffffff8168bd95)
Location: include/linux/sched.h:2194
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll
```
```
In block/blk-mq-sched.c (ffffffff8168f2b3)
Location: include/linux/sched.h:2194
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_sched
```
```
In block/blk-cgroup.c (ffffffff816a4684)
Location: include/linux/sched.h:2194
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_unpin_online
```
```
In io_uring/io_uring.c (ffffffff816d6cb2)
Location: include/linux/sched.h:2194
Inline: True
Inline callers:
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:io_iopoll_try_reap_events
```
```
In drivers/idle/intel_idle.c (ffffffff818219ed)
Location: include/linux/sched.h:2194
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff818fb976)
Location: include/linux/sched.h:2194
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
```
```
In drivers/char/mem.c (ffffffff819335e7)
Location: include/linux/sched.h:2194
Inline: True
Inline callers:
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/hw_random/core.c (ffffffff8193b675)
Location: include/linux/sched.h:2194
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/cpuidle/poll_state.c (ffffffff81f29a4a)
Location: include/linux/sched.h:2194
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/dev.c (ffffffff81c1c1b3)
Location: include/linux/sched.h:2194
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
```
```
In net/bpf/test_run.c (ffffffff81cb40aa)
Location: include/linux/sched.h:2194
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_timer_continue
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
In arch/x86/kernel/process.c (ffffffff820d4bfc)
Location: include/linux/sched.h:2221
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81092e5d)
Location: include/linux/sched.h:2221
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81097a0d)
Location: include/linux/sched.h:2221
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In kernel/softirq.c (ffffffff810f34d0)
Location: include/linux/sched.h:2221
Inline: True
Inline callers:
  - kernel/softirq.c:__irq_exit_rcu
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff820cd360)
Location: include/linux/sched.h:2221
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:preempt_schedule_notrace
  - kernel/sched/core.c:preempt_schedule_common
  - kernel/sched/core.c:schedule_idle
  - kernel/sched/core.c:schedule
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:nohz_csd_func
```
```
In kernel/sched/fair.c (ffffffff811568e2)
Location: include/linux/sched.h:2221
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_run_idle_balance
```
```
In kernel/sched/build_policy.c (ffffffff8115dabf)
Location: include/linux/sched.h:2221
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:do_idle
  - kernel/sched/build_policy.c:cpuidle_idle_call
```
```
In kernel/locking/mutex.c (ffffffff8117ccb5)
Location: include/linux/sched.h:2221
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff820d1060)
Location: include/linux/sched.h:2221
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff8117e042)
Location: include/linux/sched.h:2221
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/rtmutex_api.c (ffffffff8117e396)
Location: include/linux/sched.h:2221
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rtmutex_spin_on_owner
```
```
In kernel/rcu/tree.c (ffffffff811b3b7d)
Location: include/linux/sched.h:2221
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/entry/common.c (ffffffff811c61ca)
Location: include/linux/sched.h:2221
Inline: True
```
```
In kernel/entry/kvm.c (ffffffff811c6dab)
Location: include/linux/sched.h:2221
Inline: True
Inline callers:
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
```
```
In kernel/time/tick-sched.c (ffffffff811f0e0f)
Location: include/linux/sched.h:2221
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:can_stop_idle_tick
```
```
In kernel/cgroup/rstat.c (ffffffff81211628)
Location: include/linux/sched.h:2221
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/bpf/verifier.c (ffffffff812ed777)
Location: include/linux/sched.h:2221
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
```
In mm/vmscan.c (ffffffff8137fe4a)
Location: include/linux/sched.h:2221
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pud_range
```
```
In mm/shmem.c (ffffffff8138c970)
Location: include/linux/sched.h:2221
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/compaction.c (ffffffff813aa298)
Location: include/linux/sched.h:2221
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
```
```
In mm/memory.c (ffffffff813b8caa)
Location: include/linux/sched.h:2221
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/khugepaged.c (ffffffff8144a937)
Location: include/linux/sched.h:2221
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
```
```
In fs/select.c (ffffffff8149971d)
Location: include/linux/sched.h:2221
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/dcache.c (ffffffff8149dc2f)
Location: include/linux/sched.h:2221
Inline: True
Inline callers:
  - fs/dcache.c:select_collect2
  - fs/dcache.c:select_collect
```
```
In fs/inode.c (ffffffff814a4b80)
Location: include/linux/sched.h:2221
Inline: True
Inline callers:
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
```
```
In fs/libfs.c (ffffffff814b9016)
Location: include/linux/sched.h:2221
Inline: True
Inline callers:
  - fs/libfs.c:scan_positives
```
```
In fs/fs-writeback.c (ffffffff814c2008)
Location: include/linux/sched.h:2221
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
```
```
In fs/drop_caches.c (ffffffff81519b6e)
Location: include/linux/sched.h:2221
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_pagecache_sb
```
```
In fs/ext4/mballoc.c (ffffffff815906aa)
Location: include/linux/sched.h:2221
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
```
```
In fs/jbd2/checkpoint.c (ffffffff815e33ca)
Location: include/linux/sched.h:2221
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/fat/fatent.c (ffffffff815ff6c7)
Location: include/linux/sched.h:2221
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In security/keys/gc.c (ffffffff8164da1b)
Location: include/linux/sched.h:2221
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In block/blk-mq.c (ffffffff81741c6f)
Location: include/linux/sched.h:2221
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_classic
```
```
In block/blk-mq-sched.c (ffffffff8174df43)
Location: include/linux/sched.h:2221
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_sched
```
```
In block/blk-cgroup.c (ffffffff817633d4)
Location: include/linux/sched.h:2221
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_unpin_online
```
```
In io_uring/io_uring.c (ffffffff8178f4f6)
Location: include/linux/sched.h:2221
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_iopoll_check
  - io_uring/io_uring.c:handle_tw_list
```
```
In drivers/idle/intel_idle.c (ffffffff819526dd)
Location: include/linux/sched.h:2221
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff81a54d9f)
Location: include/linux/sched.h:2221
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
```
```
In drivers/char/mem.c (ffffffff81a922e7)
Location: include/linux/sched.h:2221
Inline: True
Inline callers:
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/hw_random/core.c (ffffffff81a9bd35)
Location: include/linux/sched.h:2221
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/cpuidle/poll_state.c (ffffffff820d58ac)
Location: include/linux/sched.h:2221
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/dev.c (ffffffff81dcd193)
Location: include/linux/sched.h:2221
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
```
```
In net/bpf/test_run.c (ffffffff81e7230a)
Location: include/linux/sched.h:2221
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_timer_continue
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
In arch/x86/kernel/process.c (ffffffff82142fea)
Location: include/linux/sched.h:2238
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81095dad)
Location: include/linux/sched.h:2238
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff821430f0)
Location: include/linux/sched.h:2238
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/softirq.c (ffffffff810ff8f0)
Location: include/linux/sched.h:2238
Inline: True
Inline callers:
  - kernel/softirq.c:__irq_exit_rcu
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff811495cb)
Location: include/linux/sched.h:2238
Inline: True
Inline callers:
  - kernel/sched/core.c:klp_cond_resched
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:preempt_schedule_notrace
  - kernel/sched/core.c:preempt_schedule
  - kernel/sched/core.c:schedule_idle
  - kernel/sched/core.c:schedule
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:nohz_csd_func
```
```
In kernel/sched/fair.c (ffffffff8116695a)
Location: include/linux/sched.h:2238
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_run_idle_balance
```
```
In kernel/sched/build_policy.c (ffffffff8116e1af)
Location: include/linux/sched.h:2238
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:do_idle
  - kernel/sched/build_policy.c:cpuidle_idle_call
```
```
In kernel/locking/mutex.c (ffffffff8118d855)
Location: include/linux/sched.h:2238
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff82155420)
Location: include/linux/sched.h:2238
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff8118ece2)
Location: include/linux/sched.h:2238
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/rtmutex_api.c (ffffffff82156481)
Location: include/linux/sched.h:2238
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff811c5808)
Location: include/linux/sched.h:2238
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/entry/common.c (ffffffff811d8d93)
Location: include/linux/sched.h:2238
Inline: True
```
```
In kernel/entry/kvm.c (ffffffff811d9b2a)
Location: include/linux/sched.h:2238
Inline: True
Inline callers:
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
```
```
In kernel/time/tick-sched.c (ffffffff81205846)
Location: include/linux/sched.h:2238
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:can_stop_idle_tick
```
```
In kernel/cgroup/rstat.c (ffffffff8122700c)
Location: include/linux/sched.h:2238
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/bpf/verifier.c (ffffffff8131a0c7)
Location: include/linux/sched.h:2238
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
```
In mm/filemap.c (ffffffff8138cb09)
Location: include/linux/sched.h:2238
Inline: True
Inline callers:
  - mm/filemap.c:filemap_cachestat
```
```
In mm/vmscan.c (ffffffff813b133a)
Location: include/linux/sched.h:2238
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pud_range
```
```
In mm/shmem.c (ffffffff813bf027)
Location: include/linux/sched.h:2238
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/compaction.c (ffffffff813dd533)
Location: include/linux/sched.h:2238
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
```
```
In mm/memory.c (ffffffff813ed6e6)
Location: include/linux/sched.h:2238
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/khugepaged.c (ffffffff81480bf6)
Location: include/linux/sched.h:2238
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
```
```
In fs/select.c (ffffffff814ce6ee)
Location: include/linux/sched.h:2238
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/dcache.c (ffffffff814d2c7f)
Location: include/linux/sched.h:2238
Inline: True
Inline callers:
  - fs/dcache.c:select_collect2
  - fs/dcache.c:select_collect
```
```
In fs/inode.c (ffffffff814d9d10)
Location: include/linux/sched.h:2238
Inline: True
Inline callers:
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
```
```
In fs/libfs.c (ffffffff814ecb56)
Location: include/linux/sched.h:2238
Inline: True
Inline callers:
  - fs/libfs.c:scan_positives
```
```
In fs/fs-writeback.c (ffffffff814f7398)
Location: include/linux/sched.h:2238
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
```
```
In fs/drop_caches.c (ffffffff8155145e)
Location: include/linux/sched.h:2238
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_pagecache_sb
```
```
In fs/ext4/mballoc.c (ffffffff815c785d)
Location: include/linux/sched.h:2238
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
```
```
In fs/jbd2/checkpoint.c (ffffffff8161ab6b)
Location: include/linux/sched.h:2238
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
  - fs/jbd2/checkpoint.c:journal_shrink_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/fat/fatent.c (ffffffff816376a7)
Location: include/linux/sched.h:2238
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In security/keys/gc.c (ffffffff816861cb)
Location: include/linux/sched.h:2238
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In crypto/jitterentropy-testing.c (ffffffff8175e776)
Location: include/linux/sched.h:2238
Inline: True
Inline callers:
  - crypto/jitterentropy-testing.c:jent_raw_hires_read
```
```
In block/blk-mq.c (ffffffff8177d2ad)
Location: include/linux/sched.h:2238
Inline: True
Inline callers:
  - block/blk-mq.c:blk_hctx_poll
```
```
In block/blk-mq-sched.c (ffffffff8178a7ba)
Location: include/linux/sched.h:2238
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
```
```
In block/blk-cgroup.c (ffffffff817a2524)
Location: include/linux/sched.h:2238
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_unpin_online
```
```
In io_uring/io_uring.c (ffffffff817d084b)
Location: include/linux/sched.h:2238
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_iopoll_check
  - io_uring/io_uring.c:tctx_task_work
```
```
In io_uring/sqpoll.c (ffffffff817db78b)
Location: include/linux/sched.h:2238
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread
```
```
In drivers/idle/intel_idle.c (ffffffff82143625)
Location: include/linux/sched.h:2238
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle_xstate
  - drivers/idle/intel_idle.c:intel_idle_ibrs
  - drivers/idle/intel_idle.c:intel_idle_irq
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/tty/tty_buffer.c (ffffffff81a9f26f)
Location: include/linux/sched.h:2238
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
```
```
In drivers/char/mem.c (ffffffff81addb67)
Location: include/linux/sched.h:2238
Inline: True
Inline callers:
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/hw_random/core.c (ffffffff81ae7695)
Location: include/linux/sched.h:2238
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/cpuidle/poll_state.c (ffffffff82144040)
Location: include/linux/sched.h:2238
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/dev.c (ffffffff81e3dcec)
Location: include/linux/sched.h:2238
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
```
```
In net/bpf/test_run.c (ffffffff81ece47a)
Location: include/linux/sched.h:2238
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_timer_continue
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
In arch/x86/kernel/process.c (ffffffff822256d7)
Location: include/linux/sched.h:2100
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109d2ed)
Location: include/linux/sched.h:2100
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff822257d5)
Location: include/linux/sched.h:2100
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/softirq.c (ffffffff81108fa9)
Location: include/linux/sched.h:2100
Inline: True
Inline callers:
  - kernel/softirq.c:__irq_exit_rcu
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff81154fcb)
Location: include/linux/sched.h:2100
Inline: True
Inline callers:
  - kernel/sched/core.c:klp_cond_resched
  - kernel/sched/core.c:rt_mutex_schedule
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:preempt_schedule_notrace
  - kernel/sched/core.c:preempt_schedule
  - kernel/sched/core.c:schedule_idle
  - kernel/sched/core.c:schedule
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:nohz_csd_func
```
```
In kernel/sched/fair.c (ffffffff8117369a)
Location: include/linux/sched.h:2100
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_run_idle_balance
```
```
In kernel/sched/build_policy.c (ffffffff8117b76f)
Location: include/linux/sched.h:2100
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:do_idle
  - kernel/sched/build_policy.c:cpuidle_idle_call
```
```
In kernel/locking/mutex.c (ffffffff8119c205)
Location: include/linux/sched.h:2100
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff82238260)
Location: include/linux/sched.h:2100
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff8119d690)
Location: include/linux/sched.h:2100
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/rtmutex_api.c (ffffffff822392c1)
Location: include/linux/sched.h:2100
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff811ddf52)
Location: include/linux/sched.h:2100
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/entry/common.c (ffffffff811ee8a3)
Location: include/linux/sched.h:2100
Inline: True
```
```
In kernel/entry/kvm.c (ffffffff811ef7da)
Location: include/linux/sched.h:2100
Inline: True
Inline callers:
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
```
```
In kernel/time/tick-sched.c (ffffffff8121be80)
Location: include/linux/sched.h:2100
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:can_stop_idle_tick
```
```
In kernel/cgroup/rstat.c (ffffffff8123ed8a)
Location: include/linux/sched.h:2100
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/bpf/verifier.c (ffffffff8133ba55)
Location: include/linux/sched.h:2100
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
```
In mm/filemap.c (ffffffff813b6678)
Location: include/linux/sched.h:2100
Inline: True
Inline callers:
  - mm/filemap.c:filemap_cachestat
```
```
In mm/vmscan.c (ffffffff813da8ba)
Location: include/linux/sched.h:2100
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pud_range
```
```
In mm/shmem.c (ffffffff813ea077)
Location: include/linux/sched.h:2100
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/compaction.c (ffffffff81407493)
Location: include/linux/sched.h:2100
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
```
```
In mm/memory.c (ffffffff81418cbc)
Location: include/linux/sched.h:2100
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/madvise.c (ffffffff814617ea)
Location: include/linux/sched.h:2100
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/khugepaged.c (ffffffff814aebd0)
Location: include/linux/sched.h:2100
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
```
```
In fs/select.c (ffffffff8150102e)
Location: include/linux/sched.h:2100
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/dcache.c (ffffffff81503f69)
Location: include/linux/sched.h:2100
Inline: True
Inline callers:
  - fs/dcache.c:select_collect2
  - fs/dcache.c:select_collect
```
```
In fs/inode.c (ffffffff8150c4b5)
Location: include/linux/sched.h:2100
Inline: True
Inline callers:
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
```
```
In fs/file.c (ffffffff8150f94c)
Location: include/linux/sched.h:2100
Inline: True
Inline callers:
  - fs/file.c:__close_range
```
```
In fs/libfs.c (ffffffff81520a9f)
Location: include/linux/sched.h:2100
Inline: True
Inline callers:
  - fs/libfs.c:scan_positives
```
```
In fs/fs-writeback.c (ffffffff8152bad8)
Location: include/linux/sched.h:2100
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
```
```
In fs/drop_caches.c (ffffffff8158735e)
Location: include/linux/sched.h:2100
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_pagecache_sb
```
```
In fs/ext4/mballoc.c (ffffffff815ff475)
Location: include/linux/sched.h:2100
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
```
```
In fs/jbd2/checkpoint.c (ffffffff81653a8e)
Location: include/linux/sched.h:2100
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
  - fs/jbd2/checkpoint.c:journal_shrink_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/fat/fatent.c (ffffffff81670b97)
Location: include/linux/sched.h:2100
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In security/keys/gc.c (ffffffff816c25f8)
Location: include/linux/sched.h:2100
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In block/blk-mq.c (ffffffff817bf63d)
Location: include/linux/sched.h:2100
Inline: True
Inline callers:
  - block/blk-mq.c:blk_hctx_poll
```
```
In block/blk-mq-sched.c (ffffffff817ccf1a)
Location: include/linux/sched.h:2100
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
```
```
In block/blk-cgroup.c (ffffffff817e6064)
Location: include/linux/sched.h:2100
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_unpin_online
```
```
In io_uring/io_uring.c (ffffffff81814140)
Location: include/linux/sched.h:2100
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_iopoll_check
  - io_uring/io_uring.c:tctx_task_work
```
```
In io_uring/sqpoll.c (ffffffff8181fae2)
Location: include/linux/sched.h:2100
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread
```
```
In drivers/idle/intel_idle.c (ffffffff82225d35)
Location: include/linux/sched.h:2100
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle_xstate
  - drivers/idle/intel_idle.c:intel_idle_ibrs
  - drivers/idle/intel_idle.c:intel_idle_irq
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/tty/tty_buffer.c (ffffffff81af1dd1)
Location: include/linux/sched.h:2100
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
```
```
In drivers/char/mem.c (ffffffff81b30f57)
Location: include/linux/sched.h:2100
Inline: True
Inline callers:
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/hw_random/core.c (ffffffff81b3aa97)
Location: include/linux/sched.h:2100
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/cpuidle/poll_state.c (ffffffff82226760)
Location: include/linux/sched.h:2100
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/dev.c (ffffffff81efc58c)
Location: include/linux/sched.h:2100
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
```
```
In net/bpf/test_run.c (ffffffff81f91caa)
Location: include/linux/sched.h:2100
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_timer_continue
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
In kernel/softirq.c (ffff8000100ff1bc)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffff800010da2020)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:preempt_schedule_common
  - kernel/sched/core.c:schedule_idle
  - kernel/sched/core.c:schedule
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/idle.c (ffff80001013fc34)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
```
In kernel/sched/fair.c (ffff80001014beac)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/fair.c:_nohz_idle_balance
```
```
In kernel/locking/mutex.c (ffff800010168664)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffff8000101698bc)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffff80001016a60c)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/rcu/tree.c (ffff80001018f20c)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/time/tick-sched.c (ffff8000101b5100)
Location: include/linux/sched.h:1804
Inline: True
```
```
In kernel/cgroup/rstat.c (ffff8000101d9884)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/bpf/verifier.c (ffff800010272d28)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
```
In mm/shmem.c (ffff8000102d63ac)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/compaction.c (ffff8000102ed56c)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
```
```
In mm/memory.c (ffff8000102f6d7c)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_pte_range
```
```
In mm/khugepaged.c (ffff80001035fea8)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/select.c (ffff8000103a3274)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/dcache.c (ffff8000103a64a0)
Location: include/linux/sched.h:1804
Inline: True
```
```
In fs/inode.c (ffff8000103af518)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
```
```
In fs/libfs.c (ffff8000103c14a0)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/libfs.c:scan_positives
```
```
In fs/fs-writeback.c (ffff8000103c9620)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
```
```
In fs/io_uring.c (ffff800010405c84)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/io_uring.c:__arm64_sys_io_uring_enter
  - fs/io_uring.c:io_iopoll_getevents
```
```
In fs/drop_caches.c (ffff800010428fa8)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_pagecache_sb
```
```
In fs/ext4/mballoc.c (ffff800010493f14)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
```
In fs/jbd2/checkpoint.c (ffff8000104d1bf4)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/fat/fatent.c (ffff8000104e9f70)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In security/keys/gc.c (ffff80001052d518)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In block/blk-mq.c (ffff8000105eda64)
Location: include/linux/sched.h:1804
Inline: True
```
```
In drivers/xen/preempt.c (ffff80001082f744)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - drivers/xen/preempt.c:xen_maybe_preempt_hcall
```
```
In drivers/char/mem.c (ffff8000108ab348)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (ffff8000108b0ad8)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/hw_random/core.c (ffff8000108b788c)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In net/core/dev.c (ffff800010bd3c08)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
```
```
In net/sched/sch_generic.c (ffff800010c392fc)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/bpf/test_run.c (ffff800010c53a3c)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
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
In arch/arm/mach-omap2/cpuidle34xx.c (c033ec8c)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - arch/arm/mach-omap2/cpuidle34xx.c:omap3_enter_idle_bm
```
```
In kernel/softirq.c (c035bed4)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (c0e9a198)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:preempt_schedule_common
  - kernel/sched/core.c:schedule_idle
  - kernel/sched/core.c:schedule
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/idle.c (c038fb68)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
```
In kernel/sched/fair.c (c0399b78)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/fair.c:_nohz_idle_balance
```
```
In kernel/locking/mutex.c (c03b4d48)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (c03b5bc8)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (c03b65f8)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/rcu/tree.c (c03ddc10)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
```
```
In kernel/time/tick-sched.c (c03fe594)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:can_stop_idle_tick
```
```
In kernel/cgroup/rstat.c (c041c2b8)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/bpf/verifier.c (c04a5404)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
```
In mm/shmem.c (c04fe654)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/compaction.c (c05115b8)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
```
```
In mm/memory.c (c0518e98)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_pte_range
```
```
In fs/select.c (c0585bf8)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/dcache.c (c0587cb8)
Location: include/linux/sched.h:1804
Inline: True
```
```
In fs/inode.c (c058f2f0)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
```
```
In fs/libfs.c (c059cb6c)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/libfs.c:scan_positives
```
```
In fs/fs-writeback.c (c05a5b74)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
```
```
In fs/io_uring.c (c05d7468)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:io_iopoll_getevents
```
```
In fs/drop_caches.c (c05f1be8)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_pagecache_sb
```
```
In fs/ext4/mballoc.c (c0655558)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
```
In fs/jbd2/checkpoint.c (c06945c4)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/fat/fatent.c (c06a7f08)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In security/keys/gc.c (c06e5cf8)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In block/blk-mq.c (c079b3cc)
Location: include/linux/sched.h:1804
Inline: True
```
```
In drivers/char/mem.c (c09a7758)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (c09aa498)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/hw_random/core.c (c09b0aa8)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/cpuidle/coupled.c (c0c052f0)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - drivers/cpuidle/coupled.c:cpuidle_enter_state_coupled
  - drivers/cpuidle/coupled.c:cpuidle_enter_state_coupled
  - drivers/cpuidle/coupled.c:cpuidle_enter_state_coupled
```
```
In net/core/dev.c (c0cee93c)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
```
```
In net/sched/sch_generic.c (c0d4b670)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/bpf/test_run.c (c0d63564)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
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
In arch/powerpc/kernel/rtas.c (c00000000003cf74)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - arch/powerpc/kernel/rtas.c:rtas_busy_delay
```
```
In kernel/softirq.c (c0000000001464d4)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (c000000000ee3468)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:preempt_schedule_common
  - kernel/sched/core.c:schedule_idle
  - kernel/sched/core.c:schedule
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/idle.c (c00000000018ecb0)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
```
In kernel/sched/fair.c (c00000000019e6f4)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/fair.c:_nohz_idle_balance
```
```
In kernel/locking/mutex.c (c0000000001c0498)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (c0000000001c167c)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (c0000000001c22e8)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/rcu/tree.c (c0000000001eb31c)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
```
```
In kernel/time/tick-sched.c (c00000000021a17c)
Location: include/linux/sched.h:1804
Inline: True
```
```
In kernel/cgroup/rstat.c (c0000000002469a8)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/bpf/verifier.c (c00000000031a6e0)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
```
In mm/shmem.c (c000000000396608)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/compaction.c (c0000000003b12e0)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
```
```
In mm/memory.c (c0000000003be940)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/khugepaged.c (c00000000044ac34)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In fs/select.c (c00000000049d054)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/dcache.c (c00000000049ff70)
Location: include/linux/sched.h:1804
Inline: True
```
```
In fs/inode.c (c0000000004ab08c)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
```
```
In fs/libfs.c (c0000000004be7b0)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/libfs.c:scan_positives
```
```
In fs/fs-writeback.c (c0000000004ca900)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
```
```
In fs/io_uring.c (c00000000050e9ac)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:io_iopoll_getevents
```
```
In fs/drop_caches.c (c000000000539230)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_pagecache_sb
```
```
In fs/ext4/mballoc.c (c0000000005bcedc)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
```
In fs/jbd2/checkpoint.c (c00000000060b1e0)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/fat/fatent.c (c000000000627e24)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In security/keys/gc.c (c0000000006796ac)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In block/blk-mq.c (c00000000078519c)
Location: include/linux/sched.h:1804
Inline: True
```
```
In drivers/char/mem.c (c000000000942cfc)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (c000000000948448)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/hw_random/core.c (c000000000950f8c)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/cpuidle/cpuidle-pseries.c (c000000000c22478)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle-pseries.c:snooze_loop
```
```
In drivers/cpuidle/cpuidle-powernv.c (c000000000c22b60)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle-powernv.c:snooze_loop
```
```
In net/core/dev.c (c000000000cb29c0)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
```
```
In net/sched/sch_generic.c (c000000000d31f10)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/bpf/test_run.c (c000000000d53320)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
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
In kernel/softirq.c (ffffffe0000c70e4)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffe0008c5730)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:preempt_schedule_common
  - kernel/sched/core.c:schedule_idle
  - kernel/sched/core.c:schedule
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/idle.c (ffffffe0000edf64)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
```
In kernel/sched/fair.c (ffffffe0000f5574)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/fair.c:_nohz_idle_balance
```
```
In kernel/rcu/tree.c (ffffffe000122cd6)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
```
```
In kernel/time/tick-sched.c (ffffffe00013af90)
Location: include/linux/sched.h:1804
Inline: True
```
```
In kernel/cgroup/rstat.c (ffffffe0001521a0)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/bpf/verifier.c (ffffffe0001abb18)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
```
In mm/shmem.c (ffffffe0001f1c24)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/compaction.c (ffffffe000201b98)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
```
```
In mm/memory.c (ffffffe00020762e)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In fs/select.c (ffffffe00026b29a)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/dcache.c (ffffffe00026c48e)
Location: include/linux/sched.h:1804
Inline: True
```
```
In fs/inode.c (ffffffe000273f72)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
```
```
In fs/libfs.c (ffffffe0002817dc)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/libfs.c:scan_positives
```
```
In fs/fs-writeback.c (ffffffe000287b32)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
```
```
In fs/io_uring.c (ffffffe0002b0e10)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:io_iopoll_getevents
```
```
In fs/drop_caches.c (ffffffe0002c6f8e)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_pagecache_sb
```
```
In fs/ext4/mballoc.c (ffffffe000318a62)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
```
In fs/jbd2/checkpoint.c (ffffffe000348e6e)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/fat/fatent.c (ffffffe00035aef6)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In security/keys/gc.c (ffffffe00038f1fe)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In block/blk-mq.c (ffffffe00042e208)
Location: include/linux/sched.h:1804
Inline: True
```
```
In drivers/char/mem.c (ffffffe0005601aa)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (ffffffe000562232)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/hw_random/core.c (ffffffe000567bdc)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In net/core/dev.c (ffffffe00075dd1a)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
```
```
In net/sched/sch_generic.c (ffffffe0007aa73c)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/bpf/test_run.c (ffffffe0007be29c)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
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
In arch/x86/kernel/process.c (ffffffff81a73236)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81a733fb)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/softirq.c (ffffffff810a19d6)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff81a6f0f5)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:preempt_schedule_common
  - kernel/sched/core.c:schedule_idle
  - kernel/sched/core.c:schedule
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/idle.c (ffffffff810da120)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
```
In kernel/sched/fair.c (ffffffff810e5d87)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/fair.c:_nohz_idle_balance
```
```
In kernel/locking/mutex.c (ffffffff810fc868)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff810fd3aa)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff810fdbee)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/rcu/tree.c (ffffffff8112014f)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/time/tick-sched.c (ffffffff811410f1)
Location: include/linux/sched.h:1804
Inline: True
```
```
In kernel/cgroup/rstat.c (ffffffff8115fa76)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/bpf/verifier.c (ffffffff811e7b52)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
```
In mm/shmem.c (ffffffff8123c7c0)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/compaction.c (ffffffff8124e616)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
```
```
In mm/memory.c (ffffffff8125713c)
Location: include/linux/sched.h:1804
Inline: True
```
```
In mm/khugepaged.c (ffffffff812b6b02)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In fs/select.c (ffffffff812ee772)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/dcache.c (ffffffff812f02ab)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/dcache.c:select_collect2
  - fs/dcache.c:select_collect
```
```
In fs/inode.c (ffffffff812f6cbb)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
```
```
In fs/libfs.c (ffffffff81305055)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/libfs.c:scan_positives
```
```
In fs/fs-writeback.c (ffffffff8130c0e8)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
```
```
In fs/io_uring.c (ffffffff8133a60d)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/io_uring.c:io_iopoll_check
  - fs/io_uring.c:io_iopoll_getevents
```
```
In fs/drop_caches.c (ffffffff8135ada5)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_pagecache_sb
```
```
In fs/ext4/mballoc.c (ffffffff813b57ed)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
```
In fs/jbd2/checkpoint.c (ffffffff813ee497)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/fat/fatent.c (ffffffff814020b5)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In security/keys/gc.c (ffffffff8143cea9)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In block/blk-mq.c (ffffffff814e8276)
Location: include/linux/sched.h:1804
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff815c8ad6)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/xen/preempt.c (ffffffff8162b921)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - drivers/xen/preempt.c:xen_maybe_preempt_hcall
```
```
In drivers/char/mem.c (ffffffff81680905)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (ffffffff8168520c)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/hw_random/core.c (ffffffff8168a78f)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/cpuidle/poll_state.c (ffffffff81a7382f)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/dev.c (ffffffff818d5832)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
```
```
In net/sched/sch_generic.c (ffffffff8192daa7)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/bpf/test_run.c (ffffffff8194453b)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
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
In arch/x86/kernel/process.c (ffffffff81a2f5f6)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81a2f7ab)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/softirq.c (ffffffff81090393)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff81a2b4fe)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:preempt_schedule_common
  - kernel/sched/core.c:schedule_idle
  - kernel/sched/core.c:schedule
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/idle.c (ffffffff810c9110)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
```
In kernel/sched/fair.c (ffffffff810d4f27)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/fair.c:_nohz_idle_balance
```
```
In kernel/locking/mutex.c (ffffffff810eca78)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff810ed5ba)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff810eddee)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/rcu/tree.c (ffffffff8111038b)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/time/tick-sched.c (ffffffff81133e91)
Location: include/linux/sched.h:1804
Inline: True
```
```
In kernel/cgroup/rstat.c (ffffffff81152d06)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/bpf/verifier.c (ffffffff811da912)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
```
In mm/shmem.c (ffffffff8122f7c0)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/compaction.c (ffffffff812415b6)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
```
```
In mm/memory.c (ffffffff8124a044)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/khugepaged.c (ffffffff812a7cd2)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In fs/select.c (ffffffff812df3a2)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/dcache.c (ffffffff812e0edb)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/dcache.c:select_collect2
  - fs/dcache.c:select_collect
```
```
In fs/inode.c (ffffffff812e78db)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
```
```
In fs/libfs.c (ffffffff812f5c75)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/libfs.c:scan_positives
```
```
In fs/fs-writeback.c (ffffffff812fcd08)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
```
```
In fs/io_uring.c (ffffffff8132b31d)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/io_uring.c:io_iopoll_check
  - fs/io_uring.c:io_iopoll_getevents
```
```
In fs/drop_caches.c (ffffffff8134ba45)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_pagecache_sb
```
```
In fs/ext4/mballoc.c (ffffffff813a627d)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
```
In fs/jbd2/checkpoint.c (ffffffff813def17)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/fat/fatent.c (ffffffff813f2b35)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In security/keys/gc.c (ffffffff8142d919)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In block/blk-mq.c (ffffffff814d87e6)
Location: include/linux/sched.h:1804
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff815b1b46)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/char/mem.c (ffffffff8165e5d5)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (ffffffff81662eac)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/hw_random/core.c (ffffffff8166818f)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/cpuidle/poll_state.c (ffffffff81a2fba9)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/dev.c (ffffffff8188f6a2)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
```
```
In net/sched/sch_generic.c (ffffffff818e75a7)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/bpf/test_run.c (ffffffff818fe02b)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
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
In arch/x86/kernel/process.c (ffffffff81adf646)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81adf80b)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/softirq.c (ffffffff810a1986)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff81adb505)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:preempt_schedule_common
  - kernel/sched/core.c:schedule_idle
  - kernel/sched/core.c:schedule
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/idle.c (ffffffff810d6460)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
```
In kernel/sched/fair.c (ffffffff810e2157)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/fair.c:_nohz_idle_balance
```
```
In kernel/locking/mutex.c (ffffffff810f9a28)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff810fa56a)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff810fadae)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/rcu/tree.c (ffffffff8111e03f)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/time/tick-sched.c (ffffffff8113efa1)
Location: include/linux/sched.h:1804
Inline: True
```
```
In kernel/cgroup/rstat.c (ffffffff8115d846)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/bpf/verifier.c (ffffffff811e5922)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
```
In mm/shmem.c (ffffffff8123a560)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/compaction.c (ffffffff8124c3b6)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
```
```
In mm/memory.c (ffffffff81254edc)
Location: include/linux/sched.h:1804
Inline: True
```
```
In mm/khugepaged.c (ffffffff812b4912)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In fs/select.c (ffffffff812ec582)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/dcache.c (ffffffff812ee0bb)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/dcache.c:select_collect2
  - fs/dcache.c:select_collect
```
```
In fs/inode.c (ffffffff812f4acb)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
```
```
In fs/libfs.c (ffffffff81302e45)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/libfs.c:scan_positives
```
```
In fs/fs-writeback.c (ffffffff81309ed8)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
```
```
In fs/io_uring.c (ffffffff813380dd)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/io_uring.c:io_iopoll_check
  - fs/io_uring.c:io_iopoll_getevents
```
```
In fs/drop_caches.c (ffffffff81358875)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_pagecache_sb
```
```
In fs/ext4/mballoc.c (ffffffff813b304d)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
```
In fs/jbd2/checkpoint.c (ffffffff813eb817)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/fat/fatent.c (ffffffff813ff435)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In security/keys/gc.c (ffffffff81439049)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In block/blk-mq.c (ffffffff814e4306)
Location: include/linux/sched.h:1804
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff815c9066)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/xen/preempt.c (ffffffff81659b11)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - drivers/xen/preempt.c:xen_maybe_preempt_hcall
```
```
In drivers/char/mem.c (ffffffff816aece5)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (ffffffff816b35fc)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/hw_random/core.c (ffffffff816b89ff)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/cpuidle/poll_state.c (ffffffff81adfc3f)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/dev.c (ffffffff81926862)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
```
```
In net/sched/sch_generic.c (ffffffff8197ec37)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/bpf/test_run.c (ffffffff819956cb)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
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
In arch/x86/kernel/process.c (ffffffff81aebdd6)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81aebfdb)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/softirq.c (ffffffff810a9976)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff81ae7ab3)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:preempt_schedule_notrace
  - kernel/sched/core.c:preempt_schedule_common
  - kernel/sched/core.c:schedule_idle
  - kernel/sched/core.c:schedule
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/idle.c (ffffffff810e1d60)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
```
In kernel/sched/fair.c (ffffffff810edcf7)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/fair.c:_nohz_idle_balance
```
```
In kernel/locking/mutex.c (ffffffff81104b9e)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff811056fa)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff81105f7e)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/rcu/tree.c (ffffffff8112b09f)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/time/tick-sched.c (ffffffff8114be21)
Location: include/linux/sched.h:1804
Inline: True
```
```
In kernel/cgroup/rstat.c (ffffffff8116aa7b)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/bpf/verifier.c (ffffffff811f3cf2)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
```
In mm/shmem.c (ffffffff81249c55)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/compaction.c (ffffffff8125bd16)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
```
```
In mm/memory.c (ffffffff81264974)
Location: include/linux/sched.h:1804
Inline: True
```
```
In mm/khugepaged.c (ffffffff812c531f)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/select.c (ffffffff812fd582)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/dcache.c (ffffffff812ff58b)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/dcache.c:select_collect2
  - fs/dcache.c:select_collect
```
```
In fs/inode.c (ffffffff81305c69)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
```
```
In fs/libfs.c (ffffffff81313ed1)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/libfs.c:scan_positives
```
```
In fs/fs-writeback.c (ffffffff8131b2e6)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
```
```
In fs/io_uring.c (ffffffff8134cfbd)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/io_uring.c:io_iopoll_check
  - fs/io_uring.c:io_iopoll_getevents
```
```
In fs/drop_caches.c (ffffffff8136bf85)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_pagecache_sb
```
```
In fs/ext4/mballoc.c (ffffffff813c7b9d)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
```
In fs/jbd2/checkpoint.c (ffffffff814011c7)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/fat/fatent.c (ffffffff81415065)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In security/keys/gc.c (ffffffff814501b2)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In block/blk-mq.c (ffffffff814fd886)
Location: include/linux/sched.h:1804
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff815e2ec6)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/char/mem.c (ffffffff816c8e15)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (ffffffff816cdb7c)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/hw_random/core.c (ffffffff816d2fcf)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/cpuidle/poll_state.c (ffffffff81aec43f)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/dev.c (ffffffff81947e6e)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
```
```
In net/sched/sch_generic.c (ffffffff819a11a7)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/bpf/test_run.c (ffffffff819b8257)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
```
</details>
</li>
</ul>

## Differences
