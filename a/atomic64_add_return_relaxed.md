# Function: <code>atomic64_add_return_relaxed</code>

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
In arch/arm64/mm/context.c (ffff8000100afeac)
Location: include/asm-generic/atomic-instrumented.h:909
Inline: True
Inline callers:
  - arch/arm64/mm/context.c:check_and_switch_context
```
```
In drivers/regulator/core.c (ffff8000108420cc)
Location: include/asm-generic/atomic-instrumented.h:909
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_lock_dependent
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
In arch/arm/mm/context.c (c0322608)
Location: arch/arm/include/asm/atomic.h:376
Inline: True
Inline callers:
  - arch/arm/mm/context.c:check_and_switch_context
```
```
In kernel/futex.c (c0401ae4)
Location: arch/arm/include/asm/atomic.h:376
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/cgroup/pids.c (c0420714)
Location: arch/arm/include/asm/atomic.h:376
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/trace/trace_clock.c (c044daf8)
Location: arch/arm/include/asm/atomic.h:376
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In kernel/events/core.c (c04c754c)
Location: arch/arm/include/asm/atomic.h:376
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_swevent_event
```
```
In fs/namespace.c (c0592a40)
Location: arch/arm/include/asm/atomic.h:376
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fuse/dir.c (c06c4148)
Location: arch/arm/include/asm/atomic.h:376
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_unlink
```
```
In fs/fuse/file.c (c06c9740)
Location: arch/arm/include/asm/atomic.h:376
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (c06cd69c)
Location: arch/arm/include/asm/atomic.h:376
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In drivers/dma-buf/dma-fence.c (c0a3ce80)
Location: arch/arm/include/asm/atomic.h:376
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_context_alloc
```
```
In net/core/sock_diag.c (c0d1cfbc)
Location: arch/arm/include/asm/atomic.h:376
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
In kernel/locking/rwsem.c (c0000000001c10f4)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/futex.c (c00000000021d370)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/cgroup/pids.c (c00000000024cdb8)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/trace/trace_clock.c (c00000000028d6cc)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_counter
```
```
In kernel/bpf/core.c (c0000000003036b0)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (c000000000309014)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_map_charge_memlock
  - kernel/bpf/syscall.c:bpf_map_charge_init
```
```
In mm/page-writeback.c (c000000000372784)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (c000000000382b54)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/vmalloc.c (c0000000003df118)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/page_counter.c (c00000000044bd84)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/pipe.c (c000000000489940)
Location: arch/powerpc/include/asm/atomic.h:370
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
In fs/namespace.c (c0000000004b0c48)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In drivers/tty/tty_ldsem.c (c0000000008fecc4)
Location: arch/powerpc/include/asm/atomic.h:370
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
In drivers/dma-buf/dma-fence.c (c000000000a1d900)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_context_alloc
```
```
In net/core/sock.c (c000000000c7f90c)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (c000000000d941e0)
Location: arch/powerpc/include/asm/atomic.h:370
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
In kernel/locking/rwsem.c (ffffffe00010abce)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
```
```
In drivers/regulator/core.c (ffffffe000522a04)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_lock_dependent
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
