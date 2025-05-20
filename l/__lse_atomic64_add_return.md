# Function: <code>__lse_atomic64_add_return</code>

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
In kernel/locking/rwsem.c (ffff800010da50b4)
Location: arch/arm64/include/asm/atomic_lse.h:229
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/futex.c (ffff8000101b7d64)
Location: arch/arm64/include/asm/atomic_lse.h:229
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/cgroup/pids.c (ffff8000101deca0)
Location: arch/arm64/include/asm/atomic_lse.h:229
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/trace/trace_clock.c (ffff80001020f070)
Location: arch/arm64/include/asm/atomic_lse.h:229
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In kernel/trace/ring_buffer.c (ffff80001021b7d8)
Location: arch/arm64/include/asm/atomic_lse.h:229
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/bpf/core.c (ffff80001025e818)
Location: arch/arm64/include/asm/atomic_lse.h:229
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffff80001026412c)
Location: arch/arm64/include/asm/atomic_lse.h:229
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffff800010297550)
Location: arch/arm64/include/asm/atomic_lse.h:229
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_swevent_event
  - kernel/events/core.c:perf_output_sample
```
```
In mm/page-writeback.c (ffff8000102baf74)
Location: arch/arm64/include/asm/atomic_lse.h:229
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffff8000102c7ed0)
Location: arch/arm64/include/asm/atomic_lse.h:229
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/workingset.c (ffff8000102f0200)
Location: arch/arm64/include/asm/atomic_lse.h:229
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/vmalloc.c (ffff80001030e378)
Location: arch/arm64/include/asm/atomic_lse.h:229
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/page_counter.c (ffff800010360ba8)
Location: arch/arm64/include/asm/atomic_lse.h:229
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/super.c (ffff8000103863c0)
Location: arch/arm64/include/asm/atomic_lse.h:229
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/pipe.c (ffff8000103918c8)
Location: arch/arm64/include/asm/atomic_lse.h:229
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
In fs/namespace.c (ffff8000103b4d18)
Location: arch/arm64/include/asm/atomic_lse.h:229
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fuse/dir.c (ffff80001050811c)
Location: arch/arm64/include/asm/atomic_lse.h:229
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_unlink
```
```
In fs/fuse/file.c (ffff80001050e134)
Location: arch/arm64/include/asm/atomic_lse.h:229
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffff8000105125a8)
Location: arch/arm64/include/asm/atomic_lse.h:229
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In drivers/tty/tty_ldsem.c (ffff80001085f760)
Location: arch/arm64/include/asm/atomic_lse.h:229
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
In drivers/dma-buf/dma-fence.c (ffff800010966760)
Location: arch/arm64/include/asm/atomic_lse.h:229
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_context_alloc
```
```
In drivers/firmware/efi/cper.c (ffff800010b5e8bc)
Location: arch/arm64/include/asm/atomic_lse.h:229
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffff800010bacb94)
Location: arch/arm64/include/asm/atomic_lse.h:229
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/sock_diag.c (ffff800010c03c50)
Location: arch/arm64/include/asm/atomic_lse.h:229
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/ipv4/tcp_output.c (ffff800010c876bc)
Location: arch/arm64/include/asm/atomic_lse.h:229
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/unix/scm.c (ffff800010cf5284)
Location: arch/arm64/include/asm/atomic_lse.h:229
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
