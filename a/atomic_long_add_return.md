# Function: <code>atomic_long_add_return</code>

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
In mm/page-writeback.c (ffffffff81198862)
Location: include/asm-generic/atomic-long.h:69
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff811a0788)
Location: include/asm-generic/atomic-long.h:69
Inline: True
```
```
In mm/page_counter.c (ffffffff811f931e)
Location: include/asm-generic/atomic-long.h:69
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_charge
  - mm/page_counter.c:page_counter_try_charge
```
```
In drivers/tty/tty_ldsem.c (ffffffff814ebc49)
Location: include/asm-generic/atomic-long.h:69
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
In net/core/sock.c (ffffffff81702a3d)
Location: include/asm-generic/atomic-long.h:69
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_schedule
  - net/core/sock.c:__sk_mem_schedule
```
```
In net/ipv4/tcp_output.c (ffffffff81778f71)
Location: include/asm-generic/atomic-long.h:69
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In kernel/locking/rwsem-xadd.c (ffffffff8189dcc1)
Location: include/asm-generic/atomic-long.h:69
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed
  - kernel/locking/rwsem-xadd.c:__rwsem_mark_wake
```
```
In mm/page-writeback.c (ffffffff811ad7b5)
Location: include/asm-generic/atomic-long.h:69
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff811b6b4d)
Location: include/asm-generic/atomic-long.h:69
Inline: True
```
```
In mm/page_counter.c (ffffffff8121cee3)
Location: include/asm-generic/atomic-long.h:69
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In drivers/tty/tty_ldsem.c (ffffffff8153ce75)
Location: include/asm-generic/atomic-long.h:69
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
In net/core/sock.c (ffffffff81767f00)
Location: include/asm-generic/atomic-long.h:69
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_schedule
```
```
In net/ipv4/tcp_output.c (ffffffff817e6123)
Location: include/asm-generic/atomic-long.h:69
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In kernel/locking/rwsem-xadd.c (ffffffff818d2b59)
Location: include/asm-generic/atomic-long.h:69
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed
```
```
In kernel/bpf/syscall.c (ffffffff8118d39e)
Location: include/asm-generic/atomic-long.h:69
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
```
```
In mm/page-writeback.c (ffffffff811bdd15)
Location: include/asm-generic/atomic-long.h:69
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff811c712c)
Location: include/asm-generic/atomic-long.h:69
Inline: True
```
```
In mm/page_counter.c (ffffffff8122f4e3)
Location: include/asm-generic/atomic-long.h:69
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/pipe.c (ffffffff8124fcfe)
Location: include/asm-generic/atomic-long.h:69
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
In drivers/tty/tty_ldsem.c (ffffffff815694c5)
Location: include/asm-generic/atomic-long.h:69
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
In net/core/sock.c (ffffffff81794efb)
Location: include/asm-generic/atomic-long.h:69
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (ffffffff81816843)
Location: include/asm-generic/atomic-long.h:69
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In kernel/locking/rwsem-xadd.c (ffffffff819099b4)
Location: include/asm-generic/atomic-long.h:69
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed
```
```
In kernel/bpf/syscall.c (ffffffff81191f87)
Location: include/asm-generic/atomic-long.h:69
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
```
```
In mm/page-writeback.c (ffffffff811c5ce7)
Location: include/asm-generic/atomic-long.h:69
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff811cf8b5)
Location: include/asm-generic/atomic-long.h:69
Inline: True
```
```
In mm/page_counter.c (ffffffff8123ad23)
Location: include/asm-generic/atomic-long.h:69
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/pipe.c (ffffffff8125bc65)
Location: include/asm-generic/atomic-long.h:69
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
In drivers/tty/tty_ldsem.c (ffffffff8157ca15)
Location: include/asm-generic/atomic-long.h:69
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
In net/core/sock.c (ffffffff817b35de)
Location: include/asm-generic/atomic-long.h:69
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (ffffffff81836b43)
Location: include/asm-generic/atomic-long.h:69
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In kernel/locking/rwsem-xadd.c (ffffffff81993938)
Location: include/asm-generic/atomic-long.h:70
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed
```
```
In kernel/bpf/syscall.c (ffffffff8119f6b7)
Location: include/asm-generic/atomic-long.h:70
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
```
```
In mm/page-writeback.c (ffffffff811daaf7)
Location: include/asm-generic/atomic-long.h:70
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff811e4ce6)
Location: include/asm-generic/atomic-long.h:70
Inline: True
```
```
In mm/page_counter.c (ffffffff8125a5b3)
Location: include/asm-generic/atomic-long.h:70
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/pipe.c (ffffffff8127e01a)
Location: include/asm-generic/atomic-long.h:70
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
In drivers/tty/tty_ldsem.c (ffffffff815e1536)
Location: include/asm-generic/atomic-long.h:70
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
In net/core/sock.c (ffffffff8182b9be)
Location: include/asm-generic/atomic-long.h:70
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (ffffffff818b61f7)
Location: include/asm-generic/atomic-long.h:70
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
Location: include/asm-generic/atomic-long.h:72
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed
```
```
In kernel/bpf/syscall.c (ffffffff811b5a97)
Location: include/asm-generic/atomic-long.h:72
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
```
```
In mm/page-writeback.c (ffffffff811fc2c3)
Location: include/asm-generic/atomic-long.h:72
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff8120644c)
Location: include/asm-generic/atomic-long.h:72
Inline: True
```
```
In mm/page_counter.c (ffffffff8127e3c1)
Location: include/asm-generic/atomic-long.h:72
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/pipe.c (ffffffff812a4f74)
Location: include/asm-generic/atomic-long.h:72
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
In drivers/tty/tty_ldsem.c (ffffffff8161a7b5)
Location: include/asm-generic/atomic-long.h:72
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
In net/core/sock.c (ffffffff81875541)
Location: include/asm-generic/atomic-long.h:72
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (ffffffff8190ba34)
Location: include/asm-generic/atomic-long.h:72
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
In kernel/locking/rwsem-xadd.c (ffffffff81a2b941)
Location: include/asm-generic/atomic-long.h:72
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed
  - kernel/locking/rwsem-xadd.c:__rwsem_mark_wake
```
```
In kernel/bpf/core.c (ffffffff811c09a9)
Location: include/asm-generic/atomic-long.h:72
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff811c36b7)
Location: include/asm-generic/atomic-long.h:72
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In mm/page-writeback.c (ffffffff8120ed73)
Location: include/asm-generic/atomic-long.h:72
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff81218bcc)
Location: include/asm-generic/atomic-long.h:72
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/page_counter.c (ffffffff81292ab1)
Location: include/asm-generic/atomic-long.h:72
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/pipe.c (ffffffff812ba044)
Location: include/asm-generic/atomic-long.h:72
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
In drivers/tty/tty_ldsem.c (ffffffff81637a15)
Location: include/asm-generic/atomic-long.h:72
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
In net/core/sock.c (ffffffff81895e13)
Location: include/asm-generic/atomic-long.h:72
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (ffffffff81939d04)
Location: include/asm-generic/atomic-long.h:72
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In kernel/locking/rwsem.c (ffffffff81a9b062)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/bpf/core.c (ffffffff811d14ee)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff811d4e07)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In mm/page-writeback.c (ffffffff8121e96f)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff812285f5)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/vmalloc.c (ffffffff81268ec7)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/page_counter.c (ffffffff812ad497)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/pipe.c (ffffffff812d6ccb)
Location: include/asm-generic/atomic-long.h:56
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
In drivers/tty/tty_ldsem.c (ffffffff8166bcd5)
Location: include/asm-generic/atomic-long.h:56
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
In net/core/sock.c (ffffffff818e0323)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (ffffffff8199dfc5)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In kernel/locking/rwsem.c (ffffffff81ad29b2)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/bpf/core.c (ffffffff811dda6e)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff811e1517)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In mm/page-writeback.c (ffffffff8122c40f)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff81236495)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/vmalloc.c (ffffffff81277e0c)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/page_counter.c (ffffffff812befe7)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/pipe.c (ffffffff812e883b)
Location: include/asm-generic/atomic-long.h:56
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
In drivers/tty/tty_ldsem.c (ffffffff8168e345)
Location: include/asm-generic/atomic-long.h:56
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
In net/core/sock.c (ffffffff819124e3)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (ffffffff819d4a85)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In kernel/locking/rwsem.c (ffffffff81bcaac0)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/bpf/core.c (ffffffff811fa57f)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff811ffc77)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_map_charge_memlock
```
```
In mm/page-writeback.c (ffffffff81259094)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff81265004)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/memory.c (ffffffff8128c85a)
Location: include/asm-generic/atomic-long.h:57
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
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/madvise.c (ffffffff812b6ad5)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/huge_memory.c (ffffffff812e9d97)
Location: include/asm-generic/atomic-long.h:57
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
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:__collapse_huge_page_copy
```
```
In mm/page_counter.c (ffffffff812f42ca)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/exec.c (ffffffff8131bbde)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - fs/exec.c:acct_arg_size
```
```
In fs/pipe.c (ffffffff81320aa6)
Location: include/asm-generic/atomic-long.h:57
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
In drivers/tty/tty_ldsem.c (ffffffff81740605)
Location: include/asm-generic/atomic-long.h:57
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
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (ffffffff81ac1456)
Location: include/asm-generic/atomic-long.h:57
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
In kernel/locking/rwsem.c (ffffffff81c4397e)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/bpf/core.c (ffffffff811f95cc)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_charge_modmem
```
```
In mm/page-writeback.c (ffffffff81263584)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff8126f986)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/memory.c (ffffffff81297b07)
Location: include/asm-generic/atomic-long.h:57
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
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/madvise.c (ffffffff812c2d25)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/huge_memory.c (ffffffff812f4f77)
Location: include/asm-generic/atomic-long.h:57
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
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff812ffbba)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/exec.c (ffffffff81326d1e)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - fs/exec.c:acct_arg_size
```
```
In fs/pipe.c (ffffffff8132c008)
Location: include/asm-generic/atomic-long.h:57
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
In drivers/tty/tty_ldsem.c (ffffffff8175c535)
Location: include/asm-generic/atomic-long.h:57
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
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (ffffffff81accec6)
Location: include/asm-generic/atomic-long.h:57
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
In kernel/locking/rwsem.c (ffffffff81c357c1)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/cgroup/misc.c (ffffffff81181008)
Location: include/asm-generic/atomic-long.h:57
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811fa46c)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_charge_modmem
```
```
In mm/page-writeback.c (ffffffff81268313)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff81273687)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/memory.c (ffffffff812a18ba)
Location: include/asm-generic/atomic-long.h:57
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
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/madvise.c (ffffffff812c9b9e)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/huge_memory.c (ffffffff812fb4dd)
Location: include/asm-generic/atomic-long.h:57
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
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff8130687a)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/exec.c (ffffffff8132cdbe)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - fs/exec.c:acct_arg_size
```
```
In fs/pipe.c (ffffffff81332048)
Location: include/asm-generic/atomic-long.h:57
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
In drivers/tty/tty_ldsem.c (ffffffff817403d5)
Location: include/asm-generic/atomic-long.h:57
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
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (ffffffff81ab8096)
Location: include/asm-generic/atomic-long.h:57
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
In kernel/ucount.c (ffffffff810ea413)
Location: include/linux/atomic/atomic-instrumented.h:1216
Inline: True
Inline callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:do_dec_rlimit_put_ucounts
  - kernel/ucount.c:dec_rlimit_ucounts
  - kernel/ucount.c:inc_rlimit_ucounts
```
```
In kernel/locking/rwsem.c (ffffffff81d53fdc)
Location: include/linux/atomic/atomic-instrumented.h:1216
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/cgroup/misc.c (ffffffff811a8e65)
Location: include/linux/atomic/atomic-instrumented.h:1216
Inline: True
```
```
In kernel/bpf/core.c (ffffffff8122bb6c)
Location: include/linux/atomic/atomic-instrumented.h:1216
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_charge_modmem
```
```
In mm/page-writeback.c (ffffffff812a4f26)
Location: include/linux/atomic/atomic-instrumented.h:1216
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff812b096d)
Location: include/linux/atomic/atomic-instrumented.h:1216
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/memory.c (ffffffff812e28a4)
Location: include/linux/atomic/atomic-instrumented.h:1216
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:add_mm_counter_fast
  - mm/memory.c:sync_mm_rss
```
```
In mm/vmalloc.c (ffffffff812fbbbd)
Location: include/linux/atomic/atomic-instrumented.h:1216
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/madvise.c (ffffffff8130ebbe)
Location: include/linux/atomic/atomic-instrumented.h:1216
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/huge_memory.c (ffffffff81345316)
Location: include/linux/atomic/atomic-instrumented.h:1216
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
Location: include/linux/atomic/atomic-instrumented.h:1216
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff813506ca)
Location: include/linux/atomic/atomic-instrumented.h:1216
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/exec.c (ffffffff8137a55e)
Location: include/linux/atomic/atomic-instrumented.h:1216
Inline: True
Inline callers:
  - fs/exec.c:acct_arg_size
```
```
In fs/pipe.c (ffffffff8137f7d8)
Location: include/linux/atomic/atomic-instrumented.h:1216
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
In drivers/tty/tty_ldsem.c (ffffffff817c0bb5)
Location: include/linux/atomic/atomic-instrumented.h:1216
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
In net/core/sock.c (ffffffff81a79113)
Location: include/linux/atomic/atomic-instrumented.h:1216
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (ffffffff81b75256)
Location: include/linux/atomic/atomic-instrumented.h:1216
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In kernel/ucount.c (ffffffff811050e2)
Location: include/linux/atomic/atomic-instrumented.h:1299
Inline: True
Inline callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:inc_rlimit_ucounts
```
```
In kernel/locking/rwsem.c (ffffffff81f2506f)
Location: include/linux/atomic/atomic-instrumented.h:1299
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/cgroup/misc.c (ffffffff811da181)
Location: include/linux/atomic/atomic-instrumented.h:1299
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_try_charge
```
```
In kernel/bpf/core.c (ffffffff8126d68c)
Location: include/linux/atomic/atomic-instrumented.h:1299
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_charge_modmem
```
```
In mm/page-writeback.c (ffffffff812fcef1)
Location: include/linux/atomic/atomic-instrumented.h:1299
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff8130c1e9)
Location: include/linux/atomic/atomic-instrumented.h:1299
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/memory.c (ffffffff81343088)
Location: include/linux/atomic/atomic-instrumented.h:1299
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:add_mm_counter_fast
  - mm/memory.c:sync_mm_rss
```
```
In mm/vmalloc.c (ffffffff81360beb)
Location: include/linux/atomic/atomic-instrumented.h:1299
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/madvise.c (ffffffff81376a46)
Location: include/linux/atomic/atomic-instrumented.h:1299
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/huge_memory.c (ffffffff813bb1b5)
Location: include/linux/atomic/atomic-instrumented.h:1299
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
Location: include/linux/atomic/atomic-instrumented.h:1299
Inline: True
```
```
In mm/page_counter.c (ffffffff813c89ba)
Location: include/linux/atomic/atomic-instrumented.h:1299
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/exec.c (ffffffff813fa2ae)
Location: include/linux/atomic/atomic-instrumented.h:1299
Inline: True
Inline callers:
  - fs/exec.c:acct_arg_size
```
```
In fs/pipe.c (ffffffff813ff942)
Location: include/linux/atomic/atomic-instrumented.h:1299
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
In drivers/tty/tty_ldsem.c (ffffffff818fd4a5)
Location: include/linux/atomic/atomic-instrumented.h:1299
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
In net/core/sock.c (ffffffff81bed573)
Location: include/linux/atomic/atomic-instrumented.h:1299
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_output.c (ffffffff81d04a69)
Location: include/linux/atomic/atomic-instrumented.h:1299
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In kernel/ucount.c (ffffffff8112ab32)
Location: include/linux/atomic/atomic-instrumented.h:1299
Inline: True
Inline callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:inc_rlimit_ucounts
```
```
In kernel/locking/rwsem.c (ffffffff820d098f)
Location: include/linux/atomic/atomic-instrumented.h:1299
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/cgroup/misc.c (ffffffff8121f701)
Location: include/linux/atomic/atomic-instrumented.h:1299
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_try_charge
```
```
In kernel/bpf/core.c (ffffffff812c2a3c)
Location: include/linux/atomic/atomic-instrumented.h:1299
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_charge_modmem
```
```
In mm/page-writeback.c (ffffffff81367331)
Location: include/linux/atomic/atomic-instrumented.h:1299
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff813784b9)
Location: include/linux/atomic/atomic-instrumented.h:1299
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/vmalloc.c (ffffffff813dc551)
Location: include/linux/atomic/atomic-instrumented.h:1299
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/page_counter.c (ffffffff8144d0ad)
Location: include/linux/atomic/atomic-instrumented.h:1299
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/pipe.c (ffffffff81489742)
Location: include/linux/atomic/atomic-instrumented.h:1299
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
In drivers/tty/tty_ldsem.c (ffffffff81a56ba5)
Location: include/linux/atomic/atomic-instrumented.h:1299
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
In kernel/ucount.c (ffffffff81137c82)
Location: include/linux/atomic/atomic-instrumented.h:3248
Inline: True
Inline callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:inc_rlimit_ucounts
```
```
In kernel/locking/rwsem.c (ffffffff82154d1f)
Location: include/linux/atomic/atomic-instrumented.h:3248
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/dma/swiotlb.c (ffffffff811d72e1)
Location: include/linux/atomic/atomic-instrumented.h:3248
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_do_find_slots
```
```
In kernel/cgroup/misc.c (ffffffff81235869)
Location: include/linux/atomic/atomic-instrumented.h:3248
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_try_charge
```
```
In kernel/bpf/core.c (ffffffff812e992c)
Location: include/linux/atomic/atomic-instrumented.h:3248
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_charge_modmem
```
```
In mm/page-writeback.c (ffffffff813999b1)
Location: include/linux/atomic/atomic-instrumented.h:3248
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff813ac7b4)
Location: include/linux/atomic/atomic-instrumented.h:3248
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/vmalloc.c (ffffffff81410e3e)
Location: include/linux/atomic/atomic-instrumented.h:3248
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/page_counter.c (ffffffff8148296d)
Location: include/linux/atomic/atomic-instrumented.h:3248
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/pipe.c (ffffffff814be670)
Location: include/linux/atomic/atomic-instrumented.h:3248
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
In drivers/tty/tty_ldsem.c (ffffffff81aa1185)
Location: include/linux/atomic/atomic-instrumented.h:3248
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
In kernel/ucount.c (ffffffff81142e92)
Location: include/linux/atomic/atomic-instrumented.h:3248
Inline: True
Inline callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:inc_rlimit_ucounts
```
```
In kernel/locking/rwsem.c (ffffffff82237b5f)
Location: include/linux/atomic/atomic-instrumented.h:3248
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/dma/swiotlb.c (ffffffff811ec2a1)
Location: include/linux/atomic/atomic-instrumented.h:3248
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_search_pool_area
```
```
In kernel/bpf/core.c (ffffffff81307b7c)
Location: include/linux/atomic/atomic-instrumented.h:3248
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_charge_modmem
```
```
In mm/page-writeback.c (ffffffff813c37b1)
Location: include/linux/atomic/atomic-instrumented.h:3248
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/shrinker.c (ffffffff813e4062)
Location: include/linux/atomic/atomic-instrumented.h:3248
Inline: True
Inline callers:
  - mm/shrinker.c:do_shrink_slab
  - mm/shrinker.c:do_shrink_slab
```
```
In mm/vmalloc.c (ffffffff8143d62e)
Location: include/linux/atomic/atomic-instrumented.h:3248
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/page_counter.c (ffffffff814b1ced)
Location: include/linux/atomic/atomic-instrumented.h:3248
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/pipe.c (ffffffff814f0b0c)
Location: include/linux/atomic/atomic-instrumented.h:3248
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
In drivers/tty/tty_ldsem.c (ffffffff81af3be5)
Location: include/linux/atomic/atomic-instrumented.h:3248
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
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/trace/ring_buffer.c (ffff80001021b7cc)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/bpf/core.c (ffff80001025e810)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffff800010264124)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In mm/page-writeback.c (ffff8000102baf6c)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffff8000102c7ec8)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/vmalloc.c (ffff80001030e370)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/page_counter.c (ffff800010360ba0)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/pipe.c (ffff8000103918c0)
Location: include/asm-generic/atomic-long.h:56
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
In drivers/tty/tty_ldsem.c (ffff80001085f758)
Location: include/asm-generic/atomic-long.h:56
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
In net/core/sock.c (ffff800010bacb8c)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (ffff800010c876b4)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In kernel/locking/rwsem.c (c0e9cf80)
Location: include/asm-generic/atomic-long.h:550
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/trace/ring_buffer.c (c045a234)
Location: include/asm-generic/atomic-long.h:550
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/bpf/core.c (c0491eb0)
Location: include/asm-generic/atomic-long.h:550
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (c0496724)
Location: include/asm-generic/atomic-long.h:550
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In mm/page-writeback.c (c04e65ec)
Location: include/asm-generic/atomic-long.h:550
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_update_write_bandwidth
```
```
In mm/vmscan.c (c04f1840)
Location: include/asm-generic/atomic-long.h:550
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/vmalloc.c (c0529ddc)
Location: include/asm-generic/atomic-long.h:550
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/page_counter.c (c0553324)
Location: include/asm-generic/atomic-long.h:550
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/pipe.c (c0578164)
Location: include/asm-generic/atomic-long.h:550
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
In drivers/tty/tty_ldsem.c (c0966b64)
Location: include/asm-generic/atomic-long.h:550
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
In net/core/sock.c (c0cc86b4)
Location: include/asm-generic/atomic-long.h:550
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (c0d969ec)
Location: include/asm-generic/atomic-long.h:550
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/bpf/core.c (c0000000003036ac)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (c000000000309010)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_map_charge_memlock
  - kernel/bpf/syscall.c:bpf_map_charge_init
```
```
In mm/page-writeback.c (c000000000372780)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (c000000000382b50)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/vmalloc.c (c0000000003df114)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/page_counter.c (c00000000044bd80)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/pipe.c (c00000000048993c)
Location: include/asm-generic/atomic-long.h:56
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
In drivers/tty/tty_ldsem.c (c0000000008fecc0)
Location: include/asm-generic/atomic-long.h:56
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
In net/core/sock.c (c000000000c7f908)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (c000000000d941dc)
Location: include/asm-generic/atomic-long.h:56
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
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/trace/ring_buffer.c (ffffffe0001784aa)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/bpf/core.c (ffffffe00019cb74)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffe0001a053a)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_charge_memlock
  - kernel/bpf/syscall.c:bpf_map_charge_init
```
```
In mm/page-writeback.c (ffffffe0001ddfc8)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffe0001e6a96)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/vmalloc.c (ffffffe000216e22)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/page_counter.c (ffffffe000240406)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/pipe.c (ffffffe000260d5a)
Location: include/asm-generic/atomic-long.h:56
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
In drivers/tty/tty_ldsem.c (ffffffe000537b0e)
Location: include/asm-generic/atomic-long.h:56
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
In net/core/sock.c (ffffffe00073d54a)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (ffffffe0007e8a54)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In kernel/locking/rwsem.c (ffffffff81a71822)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/bpf/core.c (ffffffff811d608e)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff811d9b37)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In mm/page-writeback.c (ffffffff81224a5f)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff8122eae5)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/vmalloc.c (ffffffff8127045c)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/page_counter.c (ffffffff812b75c7)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/pipe.c (ffffffff812e0e1b)
Location: include/asm-generic/atomic-long.h:56
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
In drivers/tty/tty_ldsem.c (ffffffff81653dc5)
Location: include/asm-generic/atomic-long.h:56
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
In net/core/sock.c (ffffffff818b24e3)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (ffffffff819748f5)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In kernel/locking/rwsem.c (ffffffff81a2dc12)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/bpf/core.c (ffffffff811c8e4e)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff811cc8f7)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In mm/page-writeback.c (ffffffff81217c0f)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff81221ba5)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/vmalloc.c (ffffffff812623cc)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/page_counter.c (ffffffff812a8797)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/pipe.c (ffffffff812d1a5b)
Location: include/asm-generic/atomic-long.h:56
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
In drivers/tty/tty_ldsem.c (ffffffff816341a5)
Location: include/asm-generic/atomic-long.h:56
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
In net/core/sock.c (ffffffff8186c433)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (ffffffff8192e3b5)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In kernel/locking/rwsem.c (ffffffff81addc32)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/bpf/core.c (ffffffff811d3e5e)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff811d7907)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In mm/page-writeback.c (ffffffff812227ff)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff8122c885)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/vmalloc.c (ffffffff8126e1fc)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/page_counter.c (ffffffff812b53d7)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/pipe.c (ffffffff812dec2b)
Location: include/asm-generic/atomic-long.h:56
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
In drivers/tty/tty_ldsem.c (ffffffff81682185)
Location: include/asm-generic/atomic-long.h:56
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
In net/core/sock.c (ffffffff819034e3)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (ffffffff819df0c5)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In kernel/locking/rwsem.c (ffffffff81aea154)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/bpf/core.c (ffffffff811e217e)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (ffffffff811e5ca7)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In mm/page-writeback.c (ffffffff812312e2)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/vmscan.c (ffffffff8123bc7b)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/vmalloc.c (ffffffff8127dbba)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/page_counter.c (ffffffff812c5917)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/pipe.c (ffffffff812efb9b)
Location: include/asm-generic/atomic-long.h:56
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
In drivers/tty/tty_ldsem.c (ffffffff8169c7c5)
Location: include/asm-generic/atomic-long.h:56
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
In net/core/sock.c (ffffffff819244c3)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (ffffffff819e8d65)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
</details>
</li>
</ul>

## Differences
