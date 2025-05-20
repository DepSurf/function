# Function: <code>arch_atomic64_add_return</code>

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
In arch/x86/mm/tlb.c (ffffffff8107daee)
Location: arch/x86/include/asm/atomic64_64.h:152
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff826f2171)
Location: arch/x86/include/asm/atomic64_64.h:152
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff8108ac74)
Location: arch/x86/include/asm/atomic64_64.h:152
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/locking/rwsem-xadd.c (ffffffff819efc45)
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
In kernel/cgroup/pids.c (ffffffff81146d0c)
Location: arch/x86/include/asm/atomic64_64.h:152
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/trace/trace_clock.c (ffffffff811700f0)
Location: arch/x86/include/asm/atomic64_64.h:152
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In kernel/bpf/syscall.c (ffffffff811b5a97)
Location: arch/x86/include/asm/atomic64_64.h:152
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
```
```
In kernel/events/core.c (ffffffff811d8dcc)
Location: arch/x86/include/asm/atomic64_64.h:152
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/page-writeback.c (ffffffff811fc2c3)
Location: arch/x86/include/asm/atomic64_64.h:152
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff8120644c)
Location: arch/x86/include/asm/atomic64_64.h:152
Inline: True
```
```
In mm/workingset.c (ffffffff81225845)
Location: arch/x86/include/asm/atomic64_64.h:152
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff8123f180)
Location: arch/x86/include/asm/atomic64_64.h:152
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_counter.c (ffffffff8127e3c1)
Location: arch/x86/include/asm/atomic64_64.h:152
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/super.c (ffffffff8129c1e5)
Location: arch/x86/include/asm/atomic64_64.h:152
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/pipe.c (ffffffff812a4f74)
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
In fs/namespace.c (ffffffff812bd4e9)
Location: arch/x86/include/asm/atomic64_64.h:152
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fs-writeback.c (ffffffff812c9a35)
Location: arch/x86/include/asm/atomic64_64.h:152
Inline: True
```
```
In drivers/tty/tty_ldsem.c (ffffffff8161a7b5)
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
In drivers/dma-buf/dma-fence.c (ffffffff816e37ed)
Location: arch/x86/include/asm/atomic64_64.h:152
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_context_alloc
```
```
In drivers/firmware/efi/cper.c (ffffffff818483e5)
Location: arch/x86/include/asm/atomic64_64.h:152
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffffffff81875541)
Location: arch/x86/include/asm/atomic64_64.h:152
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/sock_diag.c (ffffffff818b8e82)
Location: arch/x86/include/asm/atomic64_64.h:152
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/ipv4/tcp_output.c (ffffffff8190ba34)
Location: arch/x86/include/asm/atomic64_64.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/unix/garbage.c (ffffffff8195d6b9)
Location: arch/x86/include/asm/atomic64_64.h:152
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_inflight
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
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828a9181)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff81092c71)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/locking/rwsem-xadd.c (ffffffff81a2b675)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed
  - kernel/locking/rwsem-xadd.c:__rwsem_mark_wake
```
```
In kernel/cgroup/pids.c (ffffffff8115288c)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/trace/trace_clock.c (ffffffff8117dca0)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In kernel/bpf/core.c (ffffffff811c09a9)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff811c36b7)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffffffff811e92c4)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/page-writeback.c (ffffffff8120ed73)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff81218bcc)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/workingset.c (ffffffff81238dc6)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff812537d9)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_counter.c (ffffffff81292ab1)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/super.c (ffffffff812b1325)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/pipe.c (ffffffff812ba044)
Location: arch/x86/include/asm/atomic64_64.h:158
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
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fs-writeback.c (ffffffff812dec65)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
```
```
In drivers/regulator/core.c (ffffffff816233cc)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_lock_dependent
```
```
In drivers/tty/tty_ldsem.c (ffffffff81637a15)
Location: arch/x86/include/asm/atomic64_64.h:158
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
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_context_alloc
```
```
In drivers/firmware/efi/cper.c (ffffffff81874635)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffffffff81895e13)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/sock_diag.c (ffffffff818dfad2)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/ipv4/tcp_output.c (ffffffff81939d04)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/unix/garbage.c (ffffffff819921f9)
Location: arch/x86/include/asm/atomic64_64.h:158
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
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c1968)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff81096c67)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/locking/rwsem.c (ffffffff810f7f15)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/cgroup/pids.c (ffffffff8115ef0c)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/trace/trace_clock.c (ffffffff8118ab80)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In kernel/bpf/core.c (ffffffff811d14ee)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff811d4e07)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffffffff812025e3)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/page-writeback.c (ffffffff8121e96f)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff812285f5)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/workingset.c (ffffffff81249fca)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff81265a0d)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff81268ec7)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/page_counter.c (ffffffff812ad497)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/super.c (ffffffff812cddb5)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/pipe.c (ffffffff812d6ccb)
Location: arch/x86/include/asm/atomic64_64.h:158
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
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fs-writeback.c (ffffffff812fd316)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
```
```
In fs/fuse/dir.c (ffffffff8140ae87)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_unlink
```
```
In fs/fuse/file.c (ffffffff81410520)
Location: arch/x86/include/asm/atomic64_64.h:158
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
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In drivers/regulator/core.c (ffffffff8165557c)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_lock_dependent
```
```
In drivers/tty/tty_ldsem.c (ffffffff8166bcd5)
Location: arch/x86/include/asm/atomic64_64.h:158
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
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_context_alloc
```
```
In drivers/firmware/efi/cper.c (ffffffff818b8895)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffffffff818e0323)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/sock_diag.c (ffffffff8192e11e)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/ipv4/tcp_output.c (ffffffff8199dfc5)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/unix/scm.c (ffffffff819fdebb)
Location: arch/x86/include/asm/atomic64_64.h:158
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
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c7de1)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff8109d49b)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/locking/rwsem.c (ffffffff81103d45)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/futex.c (ffffffff8114a8ab)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/cgroup/pids.c (ffffffff8116ab6c)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/trace/trace_clock.c (ffffffff81196a70)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In kernel/bpf/core.c (ffffffff811dda6e)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff811e1517)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffffffff8120f413)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/page-writeback.c (ffffffff8122c40f)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff81236495)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/workingset.c (ffffffff81258419)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff8127432c)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff81277e0c)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/page_counter.c (ffffffff812befe7)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/super.c (ffffffff812df7e5)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/pipe.c (ffffffff812e883b)
Location: arch/x86/include/asm/atomic64_64.h:158
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
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fs-writeback.c (ffffffff8130f806)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
```
```
In fs/fuse/dir.c (ffffffff81424a59)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_unlink
```
```
In fs/fuse/file.c (ffffffff8142a130)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff8142df1f)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In drivers/regulator/core.c (ffffffff81677aac)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_lock_dependent
```
```
In drivers/tty/tty_ldsem.c (ffffffff8168e345)
Location: arch/x86/include/asm/atomic64_64.h:158
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
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_context_alloc
```
```
In drivers/firmware/efi/cper.c (ffffffff818eb295)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffffffff819124e3)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/sock_diag.c (ffffffff819603ae)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/ipv4/tcp_output.c (ffffffff819d4a85)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/unix/scm.c (ffffffff81a34aab)
Location: arch/x86/include/asm/atomic64_64.h:158
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
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/mm/tlb.c (ffffffff8108b6d8)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff82ceac27)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810a42fb)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/locking/rwsem.c (ffffffff81bcaee3)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/futex.c (ffffffff8115b3d3)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/cgroup/pids.c (ffffffff8117c8e6)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/trace/trace_clock.c (ffffffff811abda0)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In kernel/bpf/core.c (ffffffff811fa57f)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff811ffc77)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_map_charge_memlock
```
```
In kernel/bpf/bpf_iter.c (ffffffff81215756)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:prepare_seq_file
```
```
In kernel/events/core.c (ffffffff8123a60f)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/uprobes.c (ffffffff81246ced)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/page-writeback.c (ffffffff81259094)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff81265004)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/shmem.c (ffffffff8126e8ed)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff8128c85a)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:add_mm_counter_fast
  - mm/memory.c:sync_mm_rss
```
```
In mm/rmap.c (ffffffff812a54f6)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff812a8cec)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/madvise.c (ffffffff812b6ad5)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff812bbc3d)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
```
```
In mm/ksm.c (ffffffff812d3d18)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812e5357)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
```
```
In mm/huge_memory.c (ffffffff812e9d97)
Location: arch/x86/include/asm/atomic64_64.h:158
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
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:__collapse_huge_page_copy
```
```
In mm/page_counter.c (ffffffff812f4351)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_uncharge
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In mm/userfaultfd.c (ffffffff81308207)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/super.c (ffffffff81316595)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/exec.c (ffffffff8131bbde)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/exec.c:acct_arg_size
```
```
In fs/pipe.c (ffffffff81320aa6)
Location: arch/x86/include/asm/atomic64_64.h:158
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
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fs-writeback.c (ffffffff81348f15)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
```
```
In fs/fuse/dir.c (ffffffff814740ca)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_unlink
```
```
In fs/fuse/file.c (ffffffff8147a1e0)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff8147e5d2)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In drivers/regulator/core.c (ffffffff817282bf)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_lock
  - drivers/regulator/core.c:regulator_lock_dependent
```
```
In drivers/tty/tty_ldsem.c (ffffffff81740605)
Location: arch/x86/include/asm/atomic64_64.h:158
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
In drivers/firmware/efi/cper.c (ffffffff819be985)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffffffff819e4364)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/net_namespace.c (ffffffff819f9924)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_gen_cookie
```
```
In net/core/sock_diag.c (ffffffff81a3390e)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/ipv4/tcp_output.c (ffffffff81ac1456)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/unix/scm.c (ffffffff81b298eb)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/mm/tlb.c (ffffffff8108b728)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff82fd8472)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff8109ff17)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/locking/rwsem.c (ffffffff81c43cd3)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/futex.c (ffffffff81157517)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/cgroup/pids.c (ffffffff81179796)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/trace/trace_clock.c (ffffffff811a9660)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In kernel/bpf/core.c (ffffffff811f95cc)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_charge_modmem
```
```
In kernel/bpf/syscall.c (ffffffff811fb4bd)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
```
```
In kernel/bpf/bpf_iter.c (ffffffff81217420)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:prepare_seq_file
```
```
In kernel/events/core.c (ffffffff81243a43)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/uprobes.c (ffffffff8125135a)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/page-writeback.c (ffffffff81263584)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff8126f986)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/shmem.c (ffffffff812792e7)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff81297b07)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:add_mm_counter_fast
  - mm/memory.c:sync_mm_rss
```
```
In mm/rmap.c (ffffffff812b0984)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff812b3f3d)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/madvise.c (ffffffff812c2d25)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff812c76ed)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
```
```
In mm/ksm.c (ffffffff812df710)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812f0720)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
```
```
In mm/huge_memory.c (ffffffff812f4f77)
Location: arch/x86/include/asm/atomic64_64.h:158
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
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff812ffc41)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_uncharge
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In mm/userfaultfd.c (ffffffff81313fa9)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/super.c (ffffffff81321ab5)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/exec.c (ffffffff81326d1e)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/exec.c:acct_arg_size
```
```
In fs/pipe.c (ffffffff8132c008)
Location: arch/x86/include/asm/atomic64_64.h:158
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
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fs-writeback.c (ffffffff81355e78)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
```
```
In fs/fuse/dir.c (ffffffff8148ea1d)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_unlink
```
```
In fs/fuse/file.c (ffffffff81494ed3)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff81499a1d)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In drivers/regulator/core.c (ffffffff81744e6f)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_lock
  - drivers/regulator/core.c:regulator_lock_dependent
```
```
In drivers/tty/tty_ldsem.c (ffffffff8175c535)
Location: arch/x86/include/asm/atomic64_64.h:158
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
In drivers/firmware/efi/cper.c (ffffffff819c0335)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffffffff819e3be2)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/net_namespace.c (ffffffff819f947b)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/core/net_namespace.c:__net_gen_cookie
  - net/core/net_namespace.c:__net_gen_cookie
```
```
In net/core/sock_diag.c (ffffffff81a35ce2)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/core/sock_diag.c:__sock_gen_cookie
  - net/core/sock_diag.c:__sock_gen_cookie
```
```
In net/ipv4/tcp_output.c (ffffffff81accec6)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/unix/scm.c (ffffffff81b3821b)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/mm/tlb.c (ffffffff8108c307)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff831e2e68)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810a0c2a)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/locking/rwsem.c (ffffffff81c35b23)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/futex.c (ffffffff81158935)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/cgroup/pids.c (ffffffff8117a2f6)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/cgroup/misc.c (ffffffff81181008)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
```
```
In kernel/trace/trace_clock.c (ffffffff811aa210)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In kernel/bpf/core.c (ffffffff811fa46c)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_charge_modmem
```
```
In kernel/bpf/syscall.c (ffffffff811fc1dd)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
```
```
In kernel/bpf/bpf_iter.c (ffffffff8121a890)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:prepare_seq_file
```
```
In kernel/events/core.c (ffffffff812489de)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/uprobes.c (ffffffff81255454)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/page-writeback.c (ffffffff81268313)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff81273687)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/shmem.c (ffffffff8127e2d3)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff812a18ba)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:add_mm_counter_fast
  - mm/memory.c:sync_mm_rss
```
```
In mm/rmap.c (ffffffff812b5fb6)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff812b961d)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/madvise.c (ffffffff812c9b9e)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff812ce066)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
```
```
In mm/ksm.c (ffffffff812e8040)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812f6ae9)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
```
```
In mm/huge_memory.c (ffffffff812fb4dd)
Location: arch/x86/include/asm/atomic64_64.h:158
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
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff8130687a)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
  - mm/page_counter.c:page_counter_cancel
```
```
In mm/userfaultfd.c (ffffffff8131a168)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/super.c (ffffffff81327b45)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/exec.c (ffffffff8132cdbe)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/exec.c:acct_arg_size
```
```
In fs/pipe.c (ffffffff81332048)
Location: arch/x86/include/asm/atomic64_64.h:158
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
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fs-writeback.c (ffffffff8135ca58)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
```
```
In fs/fuse/dir.c (ffffffff8149444d)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_unlink
```
```
In fs/fuse/file.c (ffffffff81499f33)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff8149ec4d)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In drivers/regulator/core.c (ffffffff8172882c)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_lock_dependent
```
```
In drivers/tty/tty_ldsem.c (ffffffff817403d5)
Location: arch/x86/include/asm/atomic64_64.h:158
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
In drivers/firmware/efi/cper.c (ffffffff819a4a45)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffffffff819c9c72)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/net_namespace.c (ffffffff819dea58)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
  - net/core/net_namespace.c:setup_net
```
```
In net/core/sock_diag.c (ffffffff81a1ce23)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/core/sock_diag.c:__sock_gen_cookie
  - net/core/sock_diag.c:__sock_gen_cookie
```
```
In net/ipv4/tcp_output.c (ffffffff81ab8096)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/unix/scm.c (ffffffff81b25ebb)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/mm/tlb.c (ffffffff8109bb30)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff832c680b)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810b209d)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/ucount.c (ffffffff810ea413)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:do_dec_rlimit_put_ucounts
  - kernel/ucount.c:dec_rlimit_ucounts
  - kernel/ucount.c:inc_rlimit_ucounts
```
```
In kernel/locking/rwsem.c (ffffffff8112d1d5)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/futex.c (ffffffff8117d839)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/cgroup/pids.c (ffffffff811a1c16)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/cgroup/misc.c (ffffffff811a8e65)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
```
```
In kernel/trace/trace_clock.c (ffffffff811d3d80)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In kernel/bpf/core.c (ffffffff8122bb6c)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_charge_modmem
```
```
In kernel/bpf/syscall.c (ffffffff8122cd3d)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_sub
```
```
In kernel/bpf/bpf_iter.c (ffffffff81251690)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:prepare_seq_file
```
```
In kernel/events/core.c (ffffffff812837e2)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/uprobes.c (ffffffff81290e93)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/page-writeback.c (ffffffff812a4f26)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff812b096d)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/memory.c (ffffffff812e28a4)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:add_mm_counter_fast
  - mm/memory.c:sync_mm_rss
```
```
In mm/rmap.c (ffffffff812f885d)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff812fbbbd)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/madvise.c (ffffffff8130ebbe)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff813134e6)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
```
```
In mm/ksm.c (ffffffff8132ff52)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff81341145)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
```
```
In mm/huge_memory.c (ffffffff81345316)
Location: arch/x86/include/asm/atomic64_64.h:158
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
In mm/khugepaged.c (ffffffff8134fc43)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff813506ca)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
  - mm/page_counter.c:page_counter_cancel
```
```
In mm/userfaultfd.c (ffffffff81366e6c)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In fs/super.c (ffffffff81375115)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/exec.c (ffffffff8137a55e)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/exec.c:acct_arg_size
```
```
In fs/pipe.c (ffffffff8137f7d8)
Location: arch/x86/include/asm/atomic64_64.h:158
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
In fs/namespace.c (ffffffff8139b2ec)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fs-writeback.c (ffffffff813aaed9)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
```
```
In fs/fuse/dir.c (ffffffff814ec16d)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_unlink
```
```
In fs/fuse/file.c (ffffffff814f1953)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff814f6ead)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/genhd.c (ffffffff815e3ea7)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In drivers/regulator/core.c (ffffffff817a8e90)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_lock_dependent
```
```
In drivers/tty/tty_ldsem.c (ffffffff817c0bb5)
Location: arch/x86/include/asm/atomic64_64.h:158
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
In drivers/firmware/efi/cper.c (ffffffff81a51d15)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffffffff81a79113)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/net_namespace.c (ffffffff81a8e861)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
  - net/core/net_namespace.c:setup_net
```
```
In net/core/sock_diag.c (ffffffff81ad06a3)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/core/sock_diag.c:__sock_gen_cookie
  - net/core/sock_diag.c:__sock_gen_cookie
```
```
In net/core/page_pool.c (ffffffff81ad9479)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page
```
```
In net/ipv4/tcp_output.c (ffffffff81b75256)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/unix/scm.c (ffffffff81bebb0b)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/mm/tlb.c (ffffffff810aefa7)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff834795a9)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810c89f4)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/ucount.c (ffffffff811050e2)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:do_dec_rlimit_put_ucounts
  - kernel/ucount.c:dec_rlimit_ucounts
  - kernel/ucount.c:inc_rlimit_ucounts
```
```
In kernel/locking/rwsem.c (ffffffff8114e4f5)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/futex/core.c (ffffffff811b2b5a)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/cgroup/pids.c (ffffffff811d260a)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/cgroup/misc.c (ffffffff811da181)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_try_charge
```
```
In kernel/trace/trace_clock.c (ffffffff812088f0)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In kernel/bpf/core.c (ffffffff8126d68c)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_charge_modmem
```
```
In kernel/bpf/syscall.c (ffffffff8126f0fd)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_sub
```
```
In kernel/bpf/bpf_iter.c (ffffffff81299293)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:prepare_seq_file
```
```
In kernel/events/core.c (ffffffff812d67f6)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/uprobes.c (ffffffff812e634c)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/page-writeback.c (ffffffff812fcef1)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff8130c1e9)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/memory.c (ffffffff81343088)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:add_mm_counter_fast
  - mm/memory.c:sync_mm_rss
```
```
In mm/rmap.c (ffffffff8135eddb)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff81360beb)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/madvise.c (ffffffff81376a46)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff8137e8a8)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
```
```
In mm/ksm.c (ffffffff813a0347)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate_device.c (ffffffff813b7f58)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
```
```
In mm/huge_memory.c (ffffffff813bb1b5)
Location: arch/x86/include/asm/atomic64_64.h:158
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
In mm/khugepaged.c (ffffffff813c330c)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
```
```
In mm/page_counter.c (ffffffff813c89ba)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
  - mm/page_counter.c:page_counter_cancel
```
```
In mm/userfaultfd.c (ffffffff813e4352)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In fs/super.c (ffffffff813f4405)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/exec.c (ffffffff813fa2ae)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/exec.c:acct_arg_size
```
```
In fs/pipe.c (ffffffff813ff942)
Location: arch/x86/include/asm/atomic64_64.h:158
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
In fs/namespace.c (ffffffff8141eb52)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fs-writeback.c (ffffffff81431aa5)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
```
```
In fs/fuse/dir.c (ffffffff8157aec4)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_entry_unlinked
```
```
In fs/fuse/file.c (ffffffff81581398)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_attr
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff81586d3d)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/genhd.c (ffffffff81693182)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In drivers/regulator/core.c (ffffffff818e35e8)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_lock_dependent
```
```
In drivers/tty/tty_ldsem.c (ffffffff818fd4a5)
Location: arch/x86/include/asm/atomic64_64.h:158
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
In drivers/dma-buf/dma-buf.c (ffffffff819ece75)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_export
```
```
In drivers/firmware/efi/cper.c (ffffffff81bc0d05)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffffffff81bed573)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/net_namespace.c (ffffffff81c04782)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
  - net/core/net_namespace.c:setup_net
```
```
In net/core/sock_diag.c (ffffffff81c4df32)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/core/sock_diag.c:__sock_gen_cookie
  - net/core/sock_diag.c:__sock_gen_cookie
```
```
In net/core/xdp.c (ffffffff81c51aa6)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff81c5a625)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_return_skb_page
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
```
```
In net/ipv4/tcp_output.c (ffffffff81d04a69)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/unix/scm.c (ffffffff81d83feb)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/mm/tlb.c (ffffffff810c9347)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff83ea36f2)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810e5d51)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/ucount.c (ffffffff8112ab32)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:do_dec_rlimit_put_ucounts
  - kernel/ucount.c:dec_rlimit_ucounts
  - kernel/ucount.c:inc_rlimit_ucounts
```
```
In kernel/locking/rwsem.c (ffffffff8117d4e0)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/futex/core.c (ffffffff811f39fa)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/cgroup/pids.c (ffffffff812164ad)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/misc.c (ffffffff8121f701)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_try_charge
```
```
In kernel/trace/trace_clock.c (ffffffff81250e10)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In kernel/bpf/core.c (ffffffff812c2a3c)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_charge_modmem
```
```
In kernel/bpf/syscall.c (ffffffff812c497d)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_sub
```
```
In kernel/bpf/bpf_iter.c (ffffffff812f5023)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:prepare_seq_file
```
```
In kernel/events/core.c (ffffffff8133f5cf)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/page-writeback.c (ffffffff81367331)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff813784b9)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/rmap.c (ffffffff813d894d)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff813dc551)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/page_counter.c (ffffffff8144d0ad)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
  - mm/page_counter.c:page_counter_cancel
```
```
In fs/super.c (ffffffff8147d4d5)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/pipe.c (ffffffff81489742)
Location: arch/x86/include/asm/atomic64_64.h:158
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
In fs/namespace.c (ffffffff814ab5c2)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fs-writeback.c (ffffffff814bcdd5)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_io_lists_depopulated
```
```
In fs/fuse/dir.c (ffffffff816206c4)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_entry_unlinked
```
```
In fs/fuse/file.c (ffffffff816271e8)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_attr
  - fs/fuse/file.c:fuse_read_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff8162cfcd)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/genhd.c (ffffffff8175291b)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In drivers/regulator/core.c (ffffffff81a38728)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_lock_dependent
```
```
In drivers/tty/tty_ldsem.c (ffffffff81a56ba5)
Location: arch/x86/include/asm/atomic64_64.h:158
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
In drivers/dma-buf/dma-buf.c (ffffffff81b69d40)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_export
```
```
In drivers/firmware/efi/cper.c (ffffffff81d645f5)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/net_namespace.c (ffffffff81db4252)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
  - net/core/net_namespace.c:setup_net
```
```
In net/core/sock_diag.c (ffffffff81e02d73)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
```
```
In net/core/xdp.c (ffffffff81e06e65)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff81e10105)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_return_skb_page
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
```
```
In net/unix/scm.c (ffffffff81f5186b)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/mm/tlb.c (ffffffff810cc9e5)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff836c7982)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810f14cd)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff8111e2cb)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_cpu_intensive_report
```
```
In kernel/ucount.c (ffffffff81137c82)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:do_dec_rlimit_put_ucounts
  - kernel/ucount.c:dec_rlimit_ucounts
  - kernel/ucount.c:inc_rlimit_ucounts
```
```
In kernel/locking/rwsem.c (ffffffff8118e1c0)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/dma/swiotlb.c (ffffffff811d72e1)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_do_find_slots
```
```
In kernel/futex/core.c (ffffffff8120817e)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/cgroup/pids.c (ffffffff8122bded)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/misc.c (ffffffff81235869)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_try_charge
```
```
In kernel/trace/trace_clock.c (ffffffff81268190)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In kernel/bpf/core.c (ffffffff812e992c)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_charge_modmem
```
```
In kernel/bpf/syscall.c (ffffffff812eba5d)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_sub
```
```
In kernel/bpf/bpf_iter.c (ffffffff81322dc7)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:prepare_seq_file
```
```
In kernel/events/core.c (ffffffff81370704)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/page-writeback.c (ffffffff813999b1)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff813ac7b4)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/rmap.c (ffffffff8140ad57)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - mm/rmap.c:set_tlb_ubc_flush_pending
```
```
In mm/vmalloc.c (ffffffff81410e3e)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/page_counter.c (ffffffff8148296d)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
  - mm/page_counter.c:page_counter_cancel
```
```
In fs/super.c (ffffffff814b2295)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/pipe.c (ffffffff814be670)
Location: arch/x86/include/asm/atomic64_64.h:77
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
In fs/namespace.c (ffffffff814e03c2)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fs-writeback.c (ffffffff814f1ef5)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_io_lists_depopulated
```
```
In fs/fuse/dir.c (ffffffff81658b14)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_entry_unlinked
```
```
In fs/fuse/file.c (ffffffff8165f5a8)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_attr
  - fs/fuse/file.c:fuse_read_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff816651fd)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/genhd.c (ffffffff8178eade)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In drivers/xen/grant-table.c (ffffffff81a6371a)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/regulator/core.c (ffffffff81a822fc)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_lock_dependent
```
```
In drivers/tty/tty_ldsem.c (ffffffff81aa1185)
Location: arch/x86/include/asm/atomic64_64.h:77
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
In drivers/iommu/amd/iommu.c (ffffffff81afec8c)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:iommu_flush_irt_and_complete
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81bbd180)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_export
```
```
In drivers/firmware/efi/cper.c (ffffffff81dcf725)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/net_namespace.c (ffffffff81e24902)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
  - net/core/net_namespace.c:setup_net
```
```
In net/core/sock_diag.c (ffffffff81e752f3)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
```
```
In net/core/xdp.c (ffffffff81e797a8)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff81e83997)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_return_skb_page
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
```
```
In net/unix/scm.c (ffffffff81fb11eb)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/mm/tlb.c (ffffffff810d507e)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff838f8582)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810fa8af)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff81127ffb)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_cpu_intensive_report
```
```
In kernel/ucount.c (ffffffff81142e92)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:do_dec_rlimit_put_ucounts
  - kernel/ucount.c:dec_rlimit_ucounts
  - kernel/ucount.c:inc_rlimit_ucounts
```
```
In kernel/locking/rwsem.c (ffffffff8119cb70)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/dma/swiotlb.c (ffffffff811ec2a1)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_search_pool_area
```
```
In kernel/futex/core.c (ffffffff8121f032)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/cgroup/pids.c (ffffffff81243e1d)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/misc.c (ffffffff8124f4b8)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_try_charge
```
```
In kernel/trace/trace_clock.c (ffffffff81282400)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In kernel/bpf/core.c (ffffffff81307b7c)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_charge_modmem
```
```
In kernel/bpf/syscall.c (ffffffff81309fad)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_sub
```
```
In kernel/bpf/bpf_iter.c (ffffffff81346cf7)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:prepare_seq_file
```
```
In kernel/events/core.c (ffffffff81399a04)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/page-writeback.c (ffffffff813c37b1)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/shrinker.c (ffffffff813e4062)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - mm/shrinker.c:do_shrink_slab
  - mm/shrinker.c:do_shrink_slab
```
```
In mm/rmap.c (ffffffff81437487)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
```
```
In mm/vmalloc.c (ffffffff8143d62e)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/zswap.c (ffffffff8146f60b)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - mm/zswap.c:zswap_lru_add
```
```
In mm/page_counter.c (ffffffff814b1ced)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
  - mm/page_counter.c:page_counter_cancel
```
```
In fs/super.c (ffffffff814e38f5)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/pipe.c (ffffffff814f0b0c)
Location: arch/x86/include/asm/atomic64_64.h:77
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
In fs/namespace.c (ffffffff81513683)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/fs-writeback.c (ffffffff81526605)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_io_lists_depopulated
```
```
In fs/fuse/dir.c (ffffffff81692854)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_entry_unlinked
```
```
In fs/fuse/file.c (ffffffff816993e8)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_attr
  - fs/fuse/file.c:fuse_read_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff8169f4fd)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/genhd.c (ffffffff817d13cd)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In drivers/xen/grant-table.c (ffffffff81ab5f69)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/regulator/core.c (ffffffff81ad48dc)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_lock_dependent
```
```
In drivers/tty/tty_ldsem.c (ffffffff81af3be5)
Location: arch/x86/include/asm/atomic64_64.h:77
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
In drivers/iommu/amd/iommu.c (ffffffff81b523dc)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:iommu_flush_irt_and_complete
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81c11870)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_export
```
```
In drivers/gpu/drm/drm_file.c (ffffffff81c97598)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_file.c:drm_file_alloc
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9baf1)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem.c:drm_gem_lock_reservations
```
```
In drivers/gpu/drm/drm_modeset_lock.c (ffffffff81ca891f)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_modeset_lock.c:drm_modeset_acquire_init
```
```
In drivers/firmware/efi/cper.c (ffffffff81e88455)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/skbuff.c (ffffffff81ed12f1)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - net/core/skbuff.c:napi_pp_put_page
```
```
In net/core/net_namespace.c (ffffffff81ee2552)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
  - net/core/net_namespace.c:setup_net
```
```
In net/core/sock_diag.c (ffffffff81f34b93)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
```
```
In net/core/xdp.c (ffffffff81f3978a)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff81f4481d)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
```
```
In net/unix/scm.c (ffffffff8207e8fb)
Location: arch/x86/include/asm/atomic64_64.h:77
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
Location: arch/arm64/include/asm/atomic.h:91
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/futex.c (ffff8000101b7d5c)
Location: arch/arm64/include/asm/atomic.h:91
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/cgroup/pids.c (ffff8000101dec98)
Location: arch/arm64/include/asm/atomic.h:91
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/trace/trace_clock.c (ffff80001020f068)
Location: arch/arm64/include/asm/atomic.h:91
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In kernel/trace/ring_buffer.c (ffff80001021b7cc)
Location: arch/arm64/include/asm/atomic.h:91
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/bpf/core.c (ffff80001025e810)
Location: arch/arm64/include/asm/atomic.h:91
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffff800010264124)
Location: arch/arm64/include/asm/atomic.h:91
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffff8000102973c0)
Location: arch/arm64/include/asm/atomic.h:91
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_swevent_event
  - kernel/events/core.c:perf_output_sample
```
```
In mm/page-writeback.c (ffff8000102baf6c)
Location: arch/arm64/include/asm/atomic.h:91
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffff8000102c7ec8)
Location: arch/arm64/include/asm/atomic.h:91
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/workingset.c (ffff8000102f01f8)
Location: arch/arm64/include/asm/atomic.h:91
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/vmalloc.c (ffff80001030e370)
Location: arch/arm64/include/asm/atomic.h:91
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/page_counter.c (ffff800010360ba0)
Location: arch/arm64/include/asm/atomic.h:91
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/super.c (ffff8000103863b8)
Location: arch/arm64/include/asm/atomic.h:91
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/pipe.c (ffff8000103918c0)
Location: arch/arm64/include/asm/atomic.h:91
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
Location: arch/arm64/include/asm/atomic.h:91
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fuse/dir.c (ffff800010508114)
Location: arch/arm64/include/asm/atomic.h:91
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_unlink
```
```
In fs/fuse/file.c (ffff80001050e12c)
Location: arch/arm64/include/asm/atomic.h:91
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffff8000105125a0)
Location: arch/arm64/include/asm/atomic.h:91
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In drivers/tty/tty_ldsem.c (ffff80001085f758)
Location: arch/arm64/include/asm/atomic.h:91
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
Location: arch/arm64/include/asm/atomic.h:91
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_context_alloc
```
```
In drivers/firmware/efi/cper.c (ffff800010b5e8b4)
Location: arch/arm64/include/asm/atomic.h:91
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffff800010bacb8c)
Location: arch/arm64/include/asm/atomic.h:91
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/sock_diag.c (ffff800010c03c48)
Location: arch/arm64/include/asm/atomic.h:91
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/ipv4/tcp_output.c (ffff800010c876b4)
Location: arch/arm64/include/asm/atomic.h:91
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/unix/scm.c (ffff800010cf527c)
Location: arch/arm64/include/asm/atomic.h:91
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
```
</details>
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
In arch/x86/mm/tlb.c (ffffffff81087f98)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828b2d79)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff81096dbb)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/locking/rwsem.c (ffffffff810fd055)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/futex.c (ffffffff81142ecb)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/cgroup/pids.c (ffffffff8116318c)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/trace/trace_clock.c (ffffffff8118f090)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In kernel/bpf/core.c (ffffffff811d608e)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff811d9b37)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffffffff81207a33)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/page-writeback.c (ffffffff81224a5f)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff8122eae5)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/workingset.c (ffffffff81250a69)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff8126c97c)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff8127045c)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/page_counter.c (ffffffff812b75c7)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/super.c (ffffffff812d7dc5)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/pipe.c (ffffffff812e0e1b)
Location: arch/x86/include/asm/atomic64_64.h:158
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
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fs-writeback.c (ffffffff81307de6)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
```
```
In fs/fuse/dir.c (ffffffff8141d039)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_unlink
```
```
In fs/fuse/file.c (ffffffff81422710)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff814264ff)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In drivers/regulator/core.c (ffffffff8163d79c)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_lock_dependent
```
```
In drivers/tty/tty_ldsem.c (ffffffff81653dc5)
Location: arch/x86/include/asm/atomic64_64.h:158
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
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_context_alloc
```
```
In net/core/sock.c (ffffffff818b24e3)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/sock_diag.c (ffffffff8190037e)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/ipv4/tcp_output.c (ffffffff819748f5)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/unix/scm.c (ffffffff819d413b)
Location: arch/x86/include/asm/atomic64_64.h:158
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
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828aaefa)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff8108583b)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/locking/rwsem.c (ffffffff810ed265)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/futex.c (ffffffff8113622b)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/cgroup/pids.c (ffffffff811563dc)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/trace/trace_clock.c (ffffffff811821f0)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In kernel/bpf/core.c (ffffffff811c8e4e)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff811cc8f7)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffffffff811fab63)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/page-writeback.c (ffffffff81217c0f)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff81221ba5)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/workingset.c (ffffffff812439e9)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff8125e9da)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff812623cc)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/page_counter.c (ffffffff812a8797)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/super.c (ffffffff812c8a45)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/pipe.c (ffffffff812d1a5b)
Location: arch/x86/include/asm/atomic64_64.h:158
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
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fs-writeback.c (ffffffff812f8a06)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
```
```
In fs/fuse/dir.c (ffffffff8140dab9)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_unlink
```
```
In fs/fuse/file.c (ffffffff81413190)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff81416f7f)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In drivers/regulator/core.c (ffffffff8161d98c)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_lock_dependent
```
```
In drivers/tty/tty_ldsem.c (ffffffff816341a5)
Location: arch/x86/include/asm/atomic64_64.h:158
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
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_context_alloc
```
```
In drivers/firmware/efi/cper.c (ffffffff81845995)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffffffff8186c433)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/sock_diag.c (ffffffff818ba1ae)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/ipv4/tcp_output.c (ffffffff8192e3b5)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/unix/scm.c (ffffffff81990efb)
Location: arch/x86/include/asm/atomic64_64.h:158
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
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c5c78)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff81096d6b)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/locking/rwsem.c (ffffffff810fa215)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/futex.c (ffffffff81140d7b)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/cgroup/pids.c (ffffffff81160f5c)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/trace/trace_clock.c (ffffffff8118ce60)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In kernel/bpf/core.c (ffffffff811d3e5e)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff811d7907)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffffffff81205803)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/page-writeback.c (ffffffff812227ff)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff8122c885)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/workingset.c (ffffffff8124e809)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff8126a71c)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff8126e1fc)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/page_counter.c (ffffffff812b53d7)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/super.c (ffffffff812d5bd5)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/pipe.c (ffffffff812dec2b)
Location: arch/x86/include/asm/atomic64_64.h:158
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
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fs-writeback.c (ffffffff81305bd6)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
```
```
In fs/fuse/dir.c (ffffffff814191d9)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_unlink
```
```
In fs/fuse/file.c (ffffffff8141e8b0)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff8142269f)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In drivers/regulator/core.c (ffffffff8166b8ec)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_lock_dependent
```
```
In drivers/tty/tty_ldsem.c (ffffffff81682185)
Location: arch/x86/include/asm/atomic64_64.h:158
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
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_context_alloc
```
```
In drivers/firmware/efi/cper.c (ffffffff818e00f5)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffffffff819034e3)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/sock_diag.c (ffffffff819513ae)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/ipv4/tcp_output.c (ffffffff819df0c5)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/unix/scm.c (ffffffff81a3ebbb)
Location: arch/x86/include/asm/atomic64_64.h:158
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
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c8e1e)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff8109ec0b)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/locking/rwsem.c (ffffffff81105385)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/futex.c (ffffffff8114dfd6)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/cgroup/pids.c (ffffffff8116e3ac)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/trace/trace_clock.c (ffffffff8119a9c0)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In kernel/bpf/core.c (ffffffff811e217e)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff811e5ca7)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffffffff81214673)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/page-writeback.c (ffffffff812312e2)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff8123bc7b)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/workingset.c (ffffffff8125e179)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff81279ec2)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff8127dbba)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/page_counter.c (ffffffff812c5917)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/super.c (ffffffff812e6be5)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/pipe.c (ffffffff812efb9b)
Location: arch/x86/include/asm/atomic64_64.h:158
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
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fs-writeback.c (ffffffff81317116)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
```
```
In fs/fuse/dir.c (ffffffff8142ff49)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_unlink
```
```
In fs/fuse/file.c (ffffffff81435620)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff814394cf)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In drivers/regulator/core.c (ffffffff81685eac)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_lock_dependent
```
```
In drivers/tty/tty_ldsem.c (ffffffff8169c7c5)
Location: arch/x86/include/asm/atomic64_64.h:158
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
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_context_alloc
```
```
In drivers/firmware/efi/cper.c (ffffffff818fcb95)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffffffff819244c3)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/sock_diag.c (ffffffff81972d9e)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/ipv4/tcp_output.c (ffffffff819e8d65)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/unix/scm.c (ffffffff81a4a67b)
Location: arch/x86/include/asm/atomic64_64.h:158
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
```
</details>
</li>
</ul>

## Differences
