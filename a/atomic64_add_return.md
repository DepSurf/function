# Function: <code>atomic64_add_return</code>

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
In kernel/cgroup_pids.c (ffffffff8111a48b)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - kernel/cgroup_pids.c:pids_can_fork
```
```
In kernel/trace/trace_clock.c (ffffffff8113fe81)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In kernel/events/core.c (ffffffff8117ea5b)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/page-writeback.c (ffffffff81198862)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff811a0788)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
```
```
In mm/backing-dev.c (ffffffff811afa75)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
```
```
In mm/workingset.c (ffffffff811b9e40)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/page_counter.c (ffffffff811f92d5)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_charge
  - mm/page_counter.c:page_counter_try_charge
```
```
In fs/namespace.c (ffffffff8122b6fa)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fs-writeback.c (ffffffff812361bb)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
```
```
In drivers/tty/tty_ldsem.c (ffffffff814ebc49)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_up_read
  - drivers/tty/tty_ldsem.c:ldsem_up_write
```
```
In drivers/firmware/efi/cper.c (ffffffff816d3845)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffffffff81702a3d)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_schedule
  - net/core/sock.c:__sk_mem_schedule
```
```
In net/core/sock_diag.c (ffffffff81732f32)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/ipv4/tcp_output.c (ffffffff81778f71)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/unix/garbage.c (ffffffff817c233e)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_inflight
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
In kernel/locking/rwsem-xadd.c (ffffffff8189d8f0)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed
  - kernel/locking/rwsem-xadd.c:__rwsem_mark_wake
```
```
In kernel/cgroup_pids.c (ffffffff811222bd)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - kernel/cgroup_pids.c:pids_can_fork
  - kernel/cgroup_pids.c:pids_can_fork
```
```
In kernel/trace/trace_clock.c (ffffffff811484f1)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In kernel/events/core.c (ffffffff8119053a)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/page-writeback.c (ffffffff811ad7b5)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff811b6b4d)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
```
```
In mm/backing-dev.c (ffffffff811c8f13)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
```
```
In mm/workingset.c (ffffffff811d4212)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/page_counter.c (ffffffff8121cee3)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/namespace.c (ffffffff81253e6a)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fs-writeback.c (ffffffff8125fb3b)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
```
```
In drivers/tty/tty_ldsem.c (ffffffff8153ce75)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_up_write
  - drivers/tty/tty_ldsem.c:ldsem_up_read
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
```
```
In drivers/dma-buf/fence.c (ffffffff815fafff)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
```
```
In drivers/firmware/efi/cper.c (ffffffff81737205)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffffffff81767f00)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_schedule
```
```
In net/core/sock_diag.c (ffffffff8179e952)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/ipv4/tcp_output.c (ffffffff817e6123)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/unix/garbage.c (ffffffff8182f35e)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_inflight
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
In kernel/locking/rwsem-xadd.c (ffffffff818d27c0)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed
```
```
In kernel/cgroup_pids.c (ffffffff8112a8ed)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - kernel/cgroup_pids.c:pids_can_fork
  - kernel/cgroup_pids.c:pids_can_fork
```
```
In kernel/trace/trace_clock.c (ffffffff811523a1)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In kernel/bpf/syscall.c (ffffffff8118d39e)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
```
```
In kernel/events/core.c (ffffffff8119f3fa)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/page-writeback.c (ffffffff811bdd15)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff811c712c)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
```
```
In mm/backing-dev.c (ffffffff811d8ff3)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
```
```
In mm/workingset.c (ffffffff811e4252)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/page_counter.c (ffffffff8122f4e3)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/pipe.c (ffffffff8124fcfe)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/namespace.c (ffffffff81267179)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fs-writeback.c (ffffffff8127305b)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
```
```
In drivers/tty/tty_ldsem.c (ffffffff815694c5)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_up_write
  - drivers/tty/tty_ldsem.c:ldsem_up_read
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
```
```
In drivers/dma-buf/dma-fence.c (ffffffff816294cf)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
```
```
In drivers/firmware/efi/cper.c (ffffffff8176a3a5)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffffffff81794efb)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/sock_diag.c (ffffffff817cd322)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/ipv4/tcp_output.c (ffffffff81816843)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/unix/garbage.c (ffffffff81860dde)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_inflight
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
In kernel/locking/rwsem-xadd.c (ffffffff81909687)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed
```
```
In kernel/cgroup/pids.c (ffffffff8112b5ec)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/trace/trace_clock.c (ffffffff81154981)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In kernel/bpf/syscall.c (ffffffff81191f87)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
```
```
In kernel/events/core.c (ffffffff811a5e46)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
```
```
In mm/page-writeback.c (ffffffff811c5ce7)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff811cf8b5)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
```
```
In mm/workingset.c (ffffffff811ee625)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/page_counter.c (ffffffff8123ad23)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/super.c (ffffffff81253c06)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/pipe.c (ffffffff8125bc65)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/namespace.c (ffffffff812749c9)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fs-writeback.c (ffffffff812804bf)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
```
```
In drivers/tty/tty_ldsem.c (ffffffff8157ca15)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_up_write
  - drivers/tty/tty_ldsem.c:ldsem_up_read
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8163f09f)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
```
```
In drivers/firmware/efi/cper.c (ffffffff81788735)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffffffff817b35de)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/sock_diag.c (ffffffff817ece12)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/ipv4/tcp_output.c (ffffffff81836b43)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/unix/garbage.c (ffffffff8188553e)
Location: arch/x86/include/asm/atomic64_64.h:151
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_inflight
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
In arch/x86/mm/tlb.c (ffffffff8107ad36)
Location: arch/x86/include/asm/atomic64_64.h:152
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In kernel/fork.c (ffffffff8108774e)
Location: arch/x86/include/asm/atomic64_64.h:152
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/locking/rwsem-xadd.c (ffffffff81993677)
Location: arch/x86/include/asm/atomic64_64.h:152
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed
```
```
In kernel/cgroup/pids.c (ffffffff811383ec)
Location: arch/x86/include/asm/atomic64_64.h:152
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/trace/trace_clock.c (ffffffff811611a1)
Location: arch/x86/include/asm/atomic64_64.h:152
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In kernel/bpf/syscall.c (ffffffff8119f6b7)
Location: arch/x86/include/asm/atomic64_64.h:152
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
```
```
In kernel/events/core.c (ffffffff811b9a3c)
Location: arch/x86/include/asm/atomic64_64.h:152
Inline: True
```
```
In mm/page-writeback.c (ffffffff811daaf7)
Location: arch/x86/include/asm/atomic64_64.h:152
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff811e4ce6)
Location: arch/x86/include/asm/atomic64_64.h:152
Inline: True
```
```
In mm/workingset.c (ffffffff81204a95)
Location: arch/x86/include/asm/atomic64_64.h:152
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff8121d2b2)
Location: arch/x86/include/asm/atomic64_64.h:152
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_counter.c (ffffffff8125a5b3)
Location: arch/x86/include/asm/atomic64_64.h:152
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/super.c (ffffffff81275c86)
Location: arch/x86/include/asm/atomic64_64.h:152
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/pipe.c (ffffffff8127e01a)
Location: arch/x86/include/asm/atomic64_64.h:152
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/namespace.c (ffffffff812972f9)
Location: arch/x86/include/asm/atomic64_64.h:152
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fs-writeback.c (ffffffff812a2fef)
Location: arch/x86/include/asm/atomic64_64.h:152
Inline: True
```
```
In drivers/tty/tty_ldsem.c (ffffffff815e1536)
Location: arch/x86/include/asm/atomic64_64.h:152
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_up_write
  - drivers/tty/tty_ldsem.c:ldsem_up_read
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In drivers/dma-buf/dma-fence.c (ffffffff816a77ef)
Location: arch/x86/include/asm/atomic64_64.h:152
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_context_alloc
```
```
In drivers/firmware/efi/cper.c (ffffffff817febf5)
Location: arch/x86/include/asm/atomic64_64.h:152
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffffffff8182b9be)
Location: arch/x86/include/asm/atomic64_64.h:152
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/sock_diag.c (ffffffff81869002)
Location: arch/x86/include/asm/atomic64_64.h:152
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/ipv4/tcp_output.c (ffffffff818b61f7)
Location: arch/x86/include/asm/atomic64_64.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/unix/garbage.c (ffffffff819066ee)
Location: arch/x86/include/asm/atomic64_64.h:152
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_inflight
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
In kernel/locking/rwsem-xadd.c (ffffffff819eff0f)
Location: include/asm-generic/atomic-instrumented.h:250
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed
```
```
In kernel/cgroup/pids.c (ffffffff81146d0c)
Location: include/asm-generic/atomic-instrumented.h:250
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/trace/trace_clock.c (ffffffff811700f0)
Location: include/asm-generic/atomic-instrumented.h:250
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In kernel/bpf/syscall.c (ffffffff811b5a97)
Location: include/asm-generic/atomic-instrumented.h:250
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
```
```
In mm/page-writeback.c (ffffffff811fc2c3)
Location: include/asm-generic/atomic-instrumented.h:250
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff8120644c)
Location: include/asm-generic/atomic-instrumented.h:250
Inline: True
```
```
In mm/page_counter.c (ffffffff8127e3c1)
Location: include/asm-generic/atomic-instrumented.h:250
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/pipe.c (ffffffff812a4f74)
Location: include/asm-generic/atomic-instrumented.h:250
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/namespace.c (ffffffff812bd4e9)
Location: include/asm-generic/atomic-instrumented.h:250
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In drivers/tty/tty_ldsem.c (ffffffff8161a7b5)
Location: include/asm-generic/atomic-instrumented.h:250
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_up_write
  - drivers/tty/tty_ldsem.c:ldsem_up_read
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In drivers/dma-buf/dma-fence.c (ffffffff816e37ed)
Location: include/asm-generic/atomic-instrumented.h:250
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_context_alloc
```
```
In net/core/sock.c (ffffffff81875541)
Location: include/asm-generic/atomic-instrumented.h:250
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (ffffffff8190ba34)
Location: include/asm-generic/atomic-instrumented.h:250
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In arch/x86/mm/tlb.c (ffffffff81084670)
Location: include/asm-generic/atomic-instrumented.h:297
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828a9181)
Location: include/asm-generic/atomic-instrumented.h:297
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff81092c71)
Location: include/asm-generic/atomic-instrumented.h:297
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/locking/rwsem-xadd.c (ffffffff81a2b941)
Location: include/asm-generic/atomic-instrumented.h:297
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed
  - kernel/locking/rwsem-xadd.c:__rwsem_mark_wake
```
```
In kernel/cgroup/pids.c (ffffffff8115288c)
Location: include/asm-generic/atomic-instrumented.h:297
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/trace/trace_clock.c (ffffffff8117dca0)
Location: include/asm-generic/atomic-instrumented.h:297
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In kernel/bpf/core.c (ffffffff811c09a9)
Location: include/asm-generic/atomic-instrumented.h:297
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff811c36b7)
Location: include/asm-generic/atomic-instrumented.h:297
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffffffff811e92c4)
Location: include/asm-generic/atomic-instrumented.h:297
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/page-writeback.c (ffffffff8120ed73)
Location: include/asm-generic/atomic-instrumented.h:297
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff81218bcc)
Location: include/asm-generic/atomic-instrumented.h:297
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/workingset.c (ffffffff81238dc6)
Location: include/asm-generic/atomic-instrumented.h:297
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff812537d9)
Location: include/asm-generic/atomic-instrumented.h:297
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_counter.c (ffffffff81292ab1)
Location: include/asm-generic/atomic-instrumented.h:297
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/super.c (ffffffff812b1325)
Location: include/asm-generic/atomic-instrumented.h:297
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/pipe.c (ffffffff812ba044)
Location: include/asm-generic/atomic-instrumented.h:297
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/namespace.c (ffffffff812d27f9)
Location: include/asm-generic/atomic-instrumented.h:297
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In drivers/regulator/core.c (ffffffff816233cc)
Location: include/asm-generic/atomic-instrumented.h:297
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_lock_dependent
```
```
In drivers/tty/tty_ldsem.c (ffffffff81637a15)
Location: include/asm-generic/atomic-instrumented.h:297
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_up_write
  - drivers/tty/tty_ldsem.c:ldsem_up_read
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81706b8d)
Location: include/asm-generic/atomic-instrumented.h:297
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_context_alloc
```
```
In drivers/firmware/efi/cper.c (ffffffff81874635)
Location: include/asm-generic/atomic-instrumented.h:297
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffffffff81895e13)
Location: include/asm-generic/atomic-instrumented.h:297
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/sock_diag.c (ffffffff818dfad2)
Location: include/asm-generic/atomic-instrumented.h:297
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/ipv4/tcp_output.c (ffffffff81939d04)
Location: include/asm-generic/atomic-instrumented.h:297
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/unix/garbage.c (ffffffff819921f9)
Location: include/asm-generic/atomic-instrumented.h:297
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_inflight
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
In arch/x86/mm/tlb.c (ffffffff81088328)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c1968)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff81096c67)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/locking/rwsem.c (ffffffff810f7f15)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/cgroup/pids.c (ffffffff8115ef0c)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/trace/trace_clock.c (ffffffff8118ab80)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In kernel/bpf/core.c (ffffffff811d14ee)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff811d4e07)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffffffff812025e3)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/page-writeback.c (ffffffff8121e96f)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff812285f5)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/workingset.c (ffffffff81249fca)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff81265a0d)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff81268ec7)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/page_counter.c (ffffffff812ad497)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/super.c (ffffffff812cddb5)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/pipe.c (ffffffff812d6ccb)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/namespace.c (ffffffff812efa53)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fuse/dir.c (ffffffff8140ae87)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_unlink
```
```
In fs/fuse/file.c (ffffffff81410520)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_short_read
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff81413e7f)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In drivers/regulator/core.c (ffffffff8165557c)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_lock_dependent
```
```
In drivers/tty/tty_ldsem.c (ffffffff8166bcd5)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_up_write
  - drivers/tty/tty_ldsem.c:ldsem_up_read
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81741e64)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_context_alloc
```
```
In drivers/firmware/efi/cper.c (ffffffff818b8895)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffffffff818e0323)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/sock_diag.c (ffffffff8192e11e)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/ipv4/tcp_output.c (ffffffff8199dfc5)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/unix/scm.c (ffffffff819fdebb)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
In arch/x86/mm/tlb.c (ffffffff81088fd8)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c7de1)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff8109d49b)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/locking/rwsem.c (ffffffff81103d45)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/futex.c (ffffffff8114a8ab)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/cgroup/pids.c (ffffffff8116ab6c)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/trace/trace_clock.c (ffffffff81196a70)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In kernel/bpf/core.c (ffffffff811dda6e)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff811e1517)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffffffff8120f413)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/page-writeback.c (ffffffff8122c40f)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff81236495)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/workingset.c (ffffffff81258419)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff8127432c)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff81277e0c)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/page_counter.c (ffffffff812befe7)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/super.c (ffffffff812df7e5)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/pipe.c (ffffffff812e883b)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/namespace.c (ffffffff81301523)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fuse/dir.c (ffffffff81424a59)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_unlink
```
```
In fs/fuse/file.c (ffffffff8142a130)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff8142df1f)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In drivers/regulator/core.c (ffffffff81677aac)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_lock_dependent
```
```
In drivers/tty/tty_ldsem.c (ffffffff8168e345)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_up_write
  - drivers/tty/tty_ldsem.c:ldsem_up_read
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81765ead)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_context_alloc
```
```
In drivers/firmware/efi/cper.c (ffffffff818eb295)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffffffff819124e3)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/sock_diag.c (ffffffff819603ae)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/ipv4/tcp_output.c (ffffffff819d4a85)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/unix/scm.c (ffffffff81a34aab)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
In arch/x86/kernel/ioport.c (ffffffff8103728e)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In kernel/locking/rwsem.c (ffffffff81bcaac0)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/futex.c (ffffffff8115b3d3)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/cgroup/pids.c (ffffffff8117c8e6)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/trace/trace_clock.c (ffffffff811abda0)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In kernel/bpf/core.c (ffffffff811fa57f)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff811ffc77)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_map_charge_memlock
```
```
In mm/page-writeback.c (ffffffff81259094)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff81265004)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/memory.c (ffffffff8128c85a)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:add_mm_counter_fast
  - mm/memory.c:sync_mm_rss
```
```
In mm/vmalloc.c (ffffffff812a8cec)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/madvise.c (ffffffff812b6ad5)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/huge_memory.c (ffffffff812e9d97)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812f3945)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:__collapse_huge_page_copy
```
```
In mm/page_counter.c (ffffffff812f42ca)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/exec.c (ffffffff8131bbde)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - fs/exec.c:acct_arg_size
```
```
In fs/pipe.c (ffffffff81320aa6)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/namespace.c (ffffffff8133abf0)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In drivers/tty/tty_ldsem.c (ffffffff81740605)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_up_write
  - drivers/tty/tty_ldsem.c:ldsem_up_read
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
```
```
In net/core/sock.c (ffffffff819e4364)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (ffffffff81ac1456)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In arch/x86/kernel/ioport.c (ffffffff8103834e)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In kernel/locking/rwsem.c (ffffffff81c4397e)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/futex.c (ffffffff81157517)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/cgroup/pids.c (ffffffff81179796)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/trace/trace_clock.c (ffffffff811a9660)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In kernel/bpf/core.c (ffffffff811f95cc)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_charge_modmem
```
```
In mm/page-writeback.c (ffffffff81263584)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff8126f986)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/memory.c (ffffffff81297b07)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:add_mm_counter_fast
  - mm/memory.c:sync_mm_rss
```
```
In mm/vmalloc.c (ffffffff812b3f3d)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/madvise.c (ffffffff812c2d25)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/huge_memory.c (ffffffff812f4f77)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812ff160)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff812ffbba)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/exec.c (ffffffff81326d1e)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - fs/exec.c:acct_arg_size
```
```
In fs/pipe.c (ffffffff8132c008)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/namespace.c (ffffffff81346e1c)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In drivers/tty/tty_ldsem.c (ffffffff8175c535)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_up_write
  - drivers/tty/tty_ldsem.c:ldsem_up_read
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
```
```
In net/core/sock.c (ffffffff819e3be2)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/net_namespace.c (ffffffff819f947b)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - net/core/net_namespace.c:__net_gen_cookie
```
```
In net/core/sock_diag.c (ffffffff81a35ce2)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - net/core/sock_diag.c:__sock_gen_cookie
```
```
In net/ipv4/tcp_output.c (ffffffff81accec6)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In arch/x86/kernel/ioport.c (ffffffff81039e8e)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In kernel/locking/rwsem.c (ffffffff81c357c1)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/futex.c (ffffffff81158935)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/cgroup/pids.c (ffffffff8117a2f6)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/cgroup/misc.c (ffffffff81181008)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
```
```
In kernel/trace/trace_clock.c (ffffffff811aa210)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In kernel/bpf/core.c (ffffffff811fa46c)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_charge_modmem
```
```
In mm/page-writeback.c (ffffffff81268313)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff81273687)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/memory.c (ffffffff812a18ba)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:add_mm_counter_fast
  - mm/memory.c:sync_mm_rss
```
```
In mm/vmalloc.c (ffffffff812b961d)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/madvise.c (ffffffff812c9b9e)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/huge_memory.c (ffffffff812fb4dd)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81305dd5)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff8130687a)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/exec.c (ffffffff8132cdbe)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - fs/exec.c:acct_arg_size
```
```
In fs/pipe.c (ffffffff81332048)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/namespace.c (ffffffff8134d31c)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In drivers/tty/tty_ldsem.c (ffffffff817403d5)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_up_write
  - drivers/tty/tty_ldsem.c:ldsem_up_read
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
```
```
In net/core/sock.c (ffffffff819c9c72)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/net_namespace.c (ffffffff819dea71)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/sock_diag.c (ffffffff81a1ce35)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - net/core/sock_diag.c:__sock_gen_cookie
```
```
In net/ipv4/tcp_output.c (ffffffff81ab8096)
Location: include/asm-generic/atomic-instrumented.h:880
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In arch/x86/kernel/ioport.c (ffffffff8103f83e)
Location: include/linux/atomic/atomic-instrumented.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In kernel/futex.c (ffffffff8117d839)
Location: include/linux/atomic/atomic-instrumented.h:638
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/cgroup/pids.c (ffffffff811a1c16)
Location: include/linux/atomic/atomic-instrumented.h:638
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/trace/trace_clock.c (ffffffff811d3d80)
Location: include/linux/atomic/atomic-instrumented.h:638
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In fs/namespace.c (ffffffff8139b2ec)
Location: include/linux/atomic/atomic-instrumented.h:638
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In net/core/net_namespace.c (ffffffff81a8e87a)
Location: include/linux/atomic/atomic-instrumented.h:638
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/sock_diag.c (ffffffff81ad06b5)
Location: include/linux/atomic/atomic-instrumented.h:638
Inline: True
Inline callers:
  - net/core/sock_diag.c:__sock_gen_cookie
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
In arch/x86/kernel/ioport.c (ffffffff81046f68)
Location: include/linux/atomic/atomic-instrumented.h:680
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In kernel/futex/core.c (ffffffff811b2b5a)
Location: include/linux/atomic/atomic-instrumented.h:680
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/cgroup/pids.c (ffffffff811d260a)
Location: include/linux/atomic/atomic-instrumented.h:680
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/trace/trace_clock.c (ffffffff812088f0)
Location: include/linux/atomic/atomic-instrumented.h:680
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In fs/namespace.c (ffffffff8141eb52)
Location: include/linux/atomic/atomic-instrumented.h:680
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In drivers/dma-buf/dma-buf.c (ffffffff819ece75)
Location: include/linux/atomic/atomic-instrumented.h:680
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_export
```
```
In net/core/net_namespace.c (ffffffff81c0479b)
Location: include/linux/atomic/atomic-instrumented.h:680
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/sock_diag.c (ffffffff81c4df48)
Location: include/linux/atomic/atomic-instrumented.h:680
Inline: True
Inline callers:
  - net/core/sock_diag.c:__sock_gen_cookie
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
In arch/x86/kernel/ioport.c (ffffffff810510c8)
Location: include/linux/atomic/atomic-instrumented.h:680
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In kernel/futex/core.c (ffffffff811f39fa)
Location: include/linux/atomic/atomic-instrumented.h:680
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/cgroup/pids.c (ffffffff812164ad)
Location: include/linux/atomic/atomic-instrumented.h:680
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/trace/trace_clock.c (ffffffff81250e10)
Location: include/linux/atomic/atomic-instrumented.h:680
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In fs/namespace.c (ffffffff814ab5c2)
Location: include/linux/atomic/atomic-instrumented.h:680
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81b69d40)
Location: include/linux/atomic/atomic-instrumented.h:680
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_export
```
```
In net/core/net_namespace.c (ffffffff81db426b)
Location: include/linux/atomic/atomic-instrumented.h:680
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/sock_diag.c (ffffffff81e02d89)
Location: include/linux/atomic/atomic-instrumented.h:680
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
In arch/x86/kernel/ioport.c (ffffffff81051e0f)
Location: include/linux/atomic/atomic-instrumented.h:1684
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In kernel/futex/core.c (ffffffff8120817e)
Location: include/linux/atomic/atomic-instrumented.h:1684
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/cgroup/pids.c (ffffffff8122bded)
Location: include/linux/atomic/atomic-instrumented.h:1684
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/trace/trace_clock.c (ffffffff81268190)
Location: include/linux/atomic/atomic-instrumented.h:1684
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In fs/namespace.c (ffffffff814e03c2)
Location: include/linux/atomic/atomic-instrumented.h:1684
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In drivers/iommu/amd/iommu.c (ffffffff81afec8c)
Location: include/linux/atomic/atomic-instrumented.h:1684
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:iommu_flush_irt_and_complete
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81bbd180)
Location: include/linux/atomic/atomic-instrumented.h:1684
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_export
```
```
In net/core/net_namespace.c (ffffffff81e2491b)
Location: include/linux/atomic/atomic-instrumented.h:1684
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/sock_diag.c (ffffffff81e75309)
Location: include/linux/atomic/atomic-instrumented.h:1684
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
In arch/x86/kernel/ioport.c (ffffffff8105902f)
Location: include/linux/atomic/atomic-instrumented.h:1684
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In kernel/futex/core.c (ffffffff8121f032)
Location: include/linux/atomic/atomic-instrumented.h:1684
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/cgroup/pids.c (ffffffff81243e1d)
Location: include/linux/atomic/atomic-instrumented.h:1684
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/misc.c (ffffffff8124f4b8)
Location: include/linux/atomic/atomic-instrumented.h:1684
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_try_charge
```
```
In kernel/trace/trace_clock.c (ffffffff81282400)
Location: include/linux/atomic/atomic-instrumented.h:1684
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In fs/namespace.c (ffffffff81513683)
Location: include/linux/atomic/atomic-instrumented.h:1684
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In drivers/iommu/amd/iommu.c (ffffffff81b523dc)
Location: include/linux/atomic/atomic-instrumented.h:1684
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:iommu_flush_irt_and_complete
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81c11870)
Location: include/linux/atomic/atomic-instrumented.h:1684
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_export
```
```
In net/core/net_namespace.c (ffffffff81ee256b)
Location: include/linux/atomic/atomic-instrumented.h:1684
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/sock_diag.c (ffffffff81f34ba9)
Location: include/linux/atomic/atomic-instrumented.h:1684
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
In kernel/locking/rwsem.c (ffff800010da50ac)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/futex.c (ffff8000101b7d5c)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/cgroup/pids.c (ffff8000101dec98)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/trace/trace_clock.c (ffff80001020f068)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In kernel/trace/ring_buffer.c (ffff80001021b7cc)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/bpf/core.c (ffff80001025e810)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffff800010264124)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffff8000102973c0)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_swevent_event
  - kernel/events/core.c:perf_output_sample
```
```
In mm/page-writeback.c (ffff8000102baf6c)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffff8000102c7ec8)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/workingset.c (ffff8000102f01f8)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/vmalloc.c (ffff80001030e370)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/page_counter.c (ffff800010360ba0)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/super.c (ffff8000103863b8)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/pipe.c (ffff8000103918c0)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/namespace.c (ffff8000103b4d10)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fuse/dir.c (ffff800010508114)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_unlink
```
```
In fs/fuse/file.c (ffff80001050e12c)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffff8000105125a0)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In drivers/tty/tty_ldsem.c (ffff80001085f758)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_up_write
  - drivers/tty/tty_ldsem.c:ldsem_up_read
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In drivers/dma-buf/dma-fence.c (ffff800010966758)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_context_alloc
```
```
In drivers/firmware/efi/cper.c (ffff800010b5e8b4)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffff800010bacb8c)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/sock_diag.c (ffff800010c03c48)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/ipv4/tcp_output.c (ffff800010c876b4)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/unix/scm.c (ffff800010cf527c)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
In arch/arm/mm/context.c (c0322604)
Location: include/linux/atomic-fallback.h:1235
Inline: True
Inline callers:
  - arch/arm/mm/context.c:check_and_switch_context
```
```
In kernel/futex.c (c0401ae0)
Location: include/linux/atomic-fallback.h:1235
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/cgroup/pids.c (c0420710)
Location: include/linux/atomic-fallback.h:1235
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/trace/trace_clock.c (c044daf4)
Location: include/linux/atomic-fallback.h:1235
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In kernel/events/core.c (c04c7548)
Location: include/linux/atomic-fallback.h:1235
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_swevent_event
```
```
In fs/namespace.c (c0592a3c)
Location: include/linux/atomic-fallback.h:1235
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fuse/dir.c (c06c4144)
Location: include/linux/atomic-fallback.h:1235
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_unlink
```
```
In fs/fuse/file.c (c06c973c)
Location: include/linux/atomic-fallback.h:1235
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (c06cd698)
Location: include/linux/atomic-fallback.h:1235
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In drivers/dma-buf/dma-fence.c (c0a3ce7c)
Location: include/linux/atomic-fallback.h:1235
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_context_alloc
```
```
In net/core/sock_diag.c (c0d1cfb8)
Location: include/linux/atomic-fallback.h:1235
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
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
In kernel/locking/rwsem.c (c000000000ee7620)
Location: include/linux/atomic-fallback.h:1235
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/futex.c (c00000000021d36c)
Location: include/linux/atomic-fallback.h:1235
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/cgroup/pids.c (c00000000024cdb4)
Location: include/linux/atomic-fallback.h:1235
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/trace/trace_clock.c (c00000000028d6c8)
Location: include/linux/atomic-fallback.h:1235
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In kernel/bpf/core.c (c0000000003036ac)
Location: include/linux/atomic-fallback.h:1235
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (c000000000309010)
Location: include/linux/atomic-fallback.h:1235
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_map_charge_memlock
  - kernel/bpf/syscall.c:bpf_map_charge_init
```
```
In mm/page-writeback.c (c000000000372780)
Location: include/linux/atomic-fallback.h:1235
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (c000000000382b50)
Location: include/linux/atomic-fallback.h:1235
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/vmalloc.c (c0000000003df114)
Location: include/linux/atomic-fallback.h:1235
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/page_counter.c (c00000000044bd80)
Location: include/linux/atomic-fallback.h:1235
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/pipe.c (c00000000048993c)
Location: include/linux/atomic-fallback.h:1235
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/namespace.c (c0000000004b0c44)
Location: include/linux/atomic-fallback.h:1235
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In drivers/tty/tty_ldsem.c (c0000000008fecc0)
Location: include/linux/atomic-fallback.h:1235
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_up_write
  - drivers/tty/tty_ldsem.c:ldsem_up_read
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In drivers/dma-buf/dma-fence.c (c000000000a1d8fc)
Location: include/linux/atomic-fallback.h:1235
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_context_alloc
```
```
In net/core/sock.c (c000000000c7f908)
Location: include/linux/atomic-fallback.h:1235
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (c000000000d941dc)
Location: include/linux/atomic-fallback.h:1235
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In kernel/locking/rwsem.c (ffffffe0008c7c76)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/futex.c (ffffffe00013ca1a)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/cgroup/pids.c (ffffffe000155e7c)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_release
  - kernel/cgroup/pids.c:pids_cancel_fork
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/trace/trace_clock.c (ffffffe00016fba8)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In kernel/trace/ring_buffer.c (ffffffe0001784aa)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/bpf/core.c (ffffffe00019cb74)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffe0001a053a)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_charge_memlock
  - kernel/bpf/syscall.c:bpf_map_charge_init
```
```
In kernel/events/core.c (ffffffe0001c5510)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_event
  - kernel/events/core.c:perf_output_sample
```
```
In mm/page-writeback.c (ffffffe0001ddfc8)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffe0001e6a96)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/workingset.c (ffffffe000203c0c)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/vmalloc.c (ffffffe000216e22)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/page_counter.c (ffffffe000240406)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/super.c (ffffffe000258ce6)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/pipe.c (ffffffe000260d5a)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/namespace.c (ffffffe00027744c)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fuse/dir.c (ffffffe000373e6c)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_unlink
```
```
In fs/fuse/file.c (ffffffe000378df6)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffe00037c5ea)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In drivers/tty/tty_ldsem.c (ffffffe000537b0e)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_up_write
  - drivers/tty/tty_ldsem.c:ldsem_up_read
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In drivers/dma-buf/dma-fence.c (ffffffe0005d2de8)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_context_alloc
```
```
In net/core/sock.c (ffffffe00073d54a)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/sock_diag.c (ffffffe00078254a)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_save_cookie
```
```
In net/ipv4/tcp_output.c (ffffffe0007e8a54)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/unix/scm.c (ffffffe000840dcc)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
In arch/x86/mm/tlb.c (ffffffff81087f98)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828b2d79)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff81096dbb)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/locking/rwsem.c (ffffffff810fd055)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/futex.c (ffffffff81142ecb)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/cgroup/pids.c (ffffffff8116318c)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/trace/trace_clock.c (ffffffff8118f090)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In kernel/bpf/core.c (ffffffff811d608e)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff811d9b37)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffffffff81207a33)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/page-writeback.c (ffffffff81224a5f)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff8122eae5)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/workingset.c (ffffffff81250a69)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff8126c97c)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff8127045c)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/page_counter.c (ffffffff812b75c7)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/super.c (ffffffff812d7dc5)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/pipe.c (ffffffff812e0e1b)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/namespace.c (ffffffff812f9b03)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fuse/dir.c (ffffffff8141d039)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_unlink
```
```
In fs/fuse/file.c (ffffffff81422710)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff814264ff)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In drivers/regulator/core.c (ffffffff8163d79c)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_lock_dependent
```
```
In drivers/tty/tty_ldsem.c (ffffffff81653dc5)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_up_write
  - drivers/tty/tty_ldsem.c:ldsem_up_read
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8171a59d)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_context_alloc
```
```
In net/core/sock.c (ffffffff818b24e3)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/sock_diag.c (ffffffff8190037e)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/ipv4/tcp_output.c (ffffffff819748f5)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/unix/scm.c (ffffffff819d413b)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
In arch/x86/mm/tlb.c (ffffffff81076bf8)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828aaefa)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff8108583b)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/locking/rwsem.c (ffffffff810ed265)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/futex.c (ffffffff8113622b)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/cgroup/pids.c (ffffffff811563dc)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/trace/trace_clock.c (ffffffff811821f0)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In kernel/bpf/core.c (ffffffff811c8e4e)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff811cc8f7)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffffffff811fab63)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/page-writeback.c (ffffffff81217c0f)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff81221ba5)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/workingset.c (ffffffff812439e9)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff8125e9da)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff812623cc)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/page_counter.c (ffffffff812a8797)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/super.c (ffffffff812c8a45)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/pipe.c (ffffffff812d1a5b)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/namespace.c (ffffffff812ea723)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fuse/dir.c (ffffffff8140dab9)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_unlink
```
```
In fs/fuse/file.c (ffffffff81413190)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff81416f7f)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In drivers/regulator/core.c (ffffffff8161d98c)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_lock_dependent
```
```
In drivers/tty/tty_ldsem.c (ffffffff816341a5)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_up_write
  - drivers/tty/tty_ldsem.c:ldsem_up_read
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In drivers/dma-buf/dma-fence.c (ffffffff816f39fd)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_context_alloc
```
```
In drivers/firmware/efi/cper.c (ffffffff81845995)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffffffff8186c433)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/sock_diag.c (ffffffff818ba1ae)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/ipv4/tcp_output.c (ffffffff8192e3b5)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/unix/scm.c (ffffffff81990efb)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
In arch/x86/mm/tlb.c (ffffffff81087f48)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c5c78)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff81096d6b)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/locking/rwsem.c (ffffffff810fa215)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/futex.c (ffffffff81140d7b)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/cgroup/pids.c (ffffffff81160f5c)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/trace/trace_clock.c (ffffffff8118ce60)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In kernel/bpf/core.c (ffffffff811d3e5e)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff811d7907)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffffffff81205803)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/page-writeback.c (ffffffff812227ff)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff8122c885)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/workingset.c (ffffffff8124e809)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff8126a71c)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff8126e1fc)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/page_counter.c (ffffffff812b53d7)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/super.c (ffffffff812d5bd5)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/pipe.c (ffffffff812dec2b)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/namespace.c (ffffffff812f78f3)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fuse/dir.c (ffffffff814191d9)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_unlink
```
```
In fs/fuse/file.c (ffffffff8141e8b0)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff8142269f)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In drivers/regulator/core.c (ffffffff8166b8ec)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_lock_dependent
```
```
In drivers/tty/tty_ldsem.c (ffffffff81682185)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_up_write
  - drivers/tty/tty_ldsem.c:ldsem_up_read
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8175936d)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_context_alloc
```
```
In drivers/firmware/efi/cper.c (ffffffff818e00f5)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffffffff819034e3)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/sock_diag.c (ffffffff819513ae)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/ipv4/tcp_output.c (ffffffff819df0c5)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/unix/scm.c (ffffffff81a3ebbb)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
In arch/x86/mm/tlb.c (ffffffff8108a19f)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c8e1e)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff8109ec0b)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/locking/rwsem.c (ffffffff81105385)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/futex.c (ffffffff8114dfd6)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/cgroup/pids.c (ffffffff8116e3ac)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/trace/trace_clock.c (ffffffff8119a9c0)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In kernel/bpf/core.c (ffffffff811e217e)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff811e5ca7)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffffffff81214673)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/page-writeback.c (ffffffff812312e2)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff8123bc7b)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/workingset.c (ffffffff8125e179)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff81279ec2)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff8127dbba)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/page_counter.c (ffffffff812c5917)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/super.c (ffffffff812e6be5)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/pipe.c (ffffffff812efb9b)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/namespace.c (ffffffff81308c03)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fuse/dir.c (ffffffff8142ff49)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_unlink
```
```
In fs/fuse/file.c (ffffffff81435620)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff814394cf)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In drivers/regulator/core.c (ffffffff81685eac)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_lock_dependent
```
```
In drivers/tty/tty_ldsem.c (ffffffff8169c7c5)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_up_write
  - drivers/tty/tty_ldsem.c:ldsem_up_read
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8177484d)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_context_alloc
```
```
In drivers/firmware/efi/cper.c (ffffffff818fcb95)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffffffff819244c3)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/sock_diag.c (ffffffff81972d9e)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/ipv4/tcp_output.c (ffffffff819e8d65)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/unix/scm.c (ffffffff81a4a67b)
Location: include/asm-generic/atomic-instrumented.h:879
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
```
</details>
</li>
</ul>

## Differences
