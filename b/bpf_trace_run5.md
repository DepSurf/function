# Function: <code>bpf_trace_run5</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
void bpf_trace_run5(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811a48d0)
Location: kernel/trace/bpf_trace.c:1137
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:__bpf_trace_vector_mod
  - kernel/cpu.c:__bpf_trace_cpuhp_multi_enter
  - kernel/signal.c:__bpf_trace_signal_generate
  - mm/slab_common.c:__bpf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:__bpf_trace_kmem_alloc
  - mm/compaction.c:__bpf_trace_mm_compaction_begin
  - mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_isolate
  - fs/dax.c:__bpf_trace_dax_pmd_insert_mapping_class
  - fs/ext4/super.c:__bpf_trace_ext4_es_shrink
  - fs/ext4/super.c:__bpf_trace_ext4_remove_blocks
  - fs/ext4/super.c:__bpf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:__bpf_trace_ext4_direct_IO_exit
  - fs/ext4/super.c:__bpf_trace_ext4__mballoc
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_start
  - drivers/char/random.c:__bpf_trace_xfer_secondary_pool
  - drivers/char/random.c:__bpf_trace_credit_entropy_bits
  - drivers/ras/ras.c:__bpf_trace_aer_event
  - drivers/ras/ras.c:__bpf_trace_extlog_mem_event
  - net/core/net-traces.c:__bpf_trace_br_fdb_update
  - net/core/net-traces.c:__bpf_trace_br_fdb_add
```
**Symbols:**

```
ffffffff811a48d0-ffffffff811a4922: bpf_trace_run5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bpf_trace_run5(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b29a0)
Location: kernel/trace/bpf_trace.c:1182
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:__bpf_trace_vector_mod
  - kernel/cpu.c:__bpf_trace_cpuhp_multi_enter
  - kernel/signal.c:__bpf_trace_signal_generate
  - mm/slab_common.c:__bpf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:__bpf_trace_kmem_alloc
  - mm/compaction.c:__bpf_trace_mm_compaction_begin
  - mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_isolate
  - fs/dax.c:__bpf_trace_dax_pmd_insert_mapping_class
  - fs/ext4/super.c:__bpf_trace_ext4_es_shrink
  - fs/ext4/super.c:__bpf_trace_ext4_remove_blocks
  - fs/ext4/super.c:__bpf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:__bpf_trace_ext4_direct_IO_exit
  - fs/ext4/super.c:__bpf_trace_ext4__mballoc
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_start
  - drivers/char/random.c:__bpf_trace_xfer_secondary_pool
  - drivers/char/random.c:__bpf_trace_credit_entropy_bits
  - drivers/ras/ras.c:__bpf_trace_aer_event
  - drivers/ras/ras.c:__bpf_trace_extlog_mem_event
  - net/core/net-traces.c:__bpf_trace_br_fdb_update
  - net/core/net-traces.c:__bpf_trace_br_fdb_add
```
**Symbols:**

```
ffffffff811b29a0-ffffffff811b29f2: bpf_trace_run5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bpf_trace_run5(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c1430)
Location: kernel/trace/bpf_trace.c:1351
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:__bpf_trace_vector_mod
  - kernel/cpu.c:__bpf_trace_cpuhp_multi_enter
  - kernel/signal.c:__bpf_trace_signal_generate
  - mm/slab_common.c:__bpf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:__bpf_trace_kmem_alloc
  - mm/compaction.c:__bpf_trace_mm_compaction_begin
  - mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_isolate
  - fs/dax.c:__bpf_trace_dax_pmd_insert_mapping_class
  - fs/ext4/super.c:__bpf_trace_ext4_es_shrink
  - fs/ext4/super.c:__bpf_trace_ext4_remove_blocks
  - fs/ext4/super.c:__bpf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:__bpf_trace_ext4_direct_IO_exit
  - fs/ext4/super.c:__bpf_trace_ext4__mballoc
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_start
  - drivers/char/random.c:__bpf_trace_xfer_secondary_pool
  - drivers/ras/ras.c:__bpf_trace_aer_event
  - drivers/ras/ras.c:__bpf_trace_extlog_mem_event
  - net/core/net-traces.c:__bpf_trace_neigh_update
  - net/core/net-traces.c:__bpf_trace_neigh_create
  - net/core/net-traces.c:__bpf_trace_br_fdb_update
  - net/core/net-traces.c:__bpf_trace_br_fdb_add
  - net/core/devlink.c:__bpf_trace_devlink_hwmsg
```
**Symbols:**

```
ffffffff811c1430-ffffffff811c14d2: bpf_trace_run5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bpf_trace_run5(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811ccbe0)
Location: kernel/trace/bpf_trace.c:1375
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:__bpf_trace_vector_mod
  - kernel/cpu.c:__bpf_trace_cpuhp_multi_enter
  - kernel/signal.c:__bpf_trace_signal_generate
  - mm/slab_common.c:__bpf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:__bpf_trace_kmem_alloc
  - mm/compaction.c:__bpf_trace_mm_compaction_begin
  - mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_isolate
  - fs/dax.c:__bpf_trace_dax_pmd_insert_mapping_class
  - fs/ext4/super.c:__bpf_trace_ext4_es_shrink
  - fs/ext4/super.c:__bpf_trace_ext4_remove_blocks
  - fs/ext4/super.c:__bpf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:__bpf_trace_ext4_direct_IO_exit
  - fs/ext4/super.c:__bpf_trace_ext4__mballoc
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_start
  - drivers/char/random.c:__bpf_trace_xfer_secondary_pool
  - drivers/ras/ras.c:__bpf_trace_aer_event
  - drivers/ras/ras.c:__bpf_trace_extlog_mem_event
  - net/core/net-traces.c:__bpf_trace_neigh_update
  - net/core/net-traces.c:__bpf_trace_neigh_create
  - net/core/net-traces.c:__bpf_trace_br_fdb_update
  - net/core/net-traces.c:__bpf_trace_br_fdb_add
  - net/core/devlink.c:__bpf_trace_devlink_hwmsg
```
**Symbols:**

```
ffffffff811ccbe0-ffffffff811ccc82: bpf_trace_run5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bpf_trace_run5(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e8570)
Location: kernel/trace/bpf_trace.c:1869
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:__bpf_trace_vector_mod
  - kernel/cpu.c:__bpf_trace_cpuhp_multi_enter
  - kernel/signal.c:__bpf_trace_signal_generate
  - kernel/bpf/core.c:__bpf_trace_xdp_devmap_xmit
  - mm/slab_common.c:__bpf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:__bpf_trace_kmem_alloc
  - mm/compaction.c:__bpf_trace_mm_compaction_begin
  - mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_isolate
  - fs/io_uring.c:__bpf_trace_io_uring_poll_arm
  - fs/io_uring.c:__bpf_trace_io_uring_submit_sqe
  - fs/io_uring.c:__bpf_trace_io_uring_queue_async_work
  - fs/io_uring.c:__bpf_trace_io_uring_create
  - fs/dax.c:__bpf_trace_dax_pmd_insert_mapping_class
  - fs/ext4/super.c:__bpf_trace_ext4_es_shrink
  - fs/ext4/super.c:__bpf_trace_ext4_remove_blocks
  - fs/ext4/super.c:__bpf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:__bpf_trace_ext4_journal_start
  - fs/ext4/super.c:__bpf_trace_ext4_direct_IO_exit
  - fs/ext4/super.c:__bpf_trace_ext4__mballoc
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_start_class
  - drivers/char/random.c:__bpf_trace_xfer_secondary_pool
  - drivers/ras/ras.c:__bpf_trace_aer_event
  - drivers/ras/ras.c:__bpf_trace_extlog_mem_event
  - drivers/interconnect/core.c:__bpf_trace_icc_set_bw
  - net/core/net-traces.c:__bpf_trace_neigh_update
  - net/core/net-traces.c:__bpf_trace_neigh_create
  - net/core/net-traces.c:__bpf_trace_br_fdb_update
  - net/core/net-traces.c:__bpf_trace_br_fdb_add
  - net/core/devlink.c:__bpf_trace_devlink_hwmsg
```
**Symbols:**

```
ffffffff811e8570-ffffffff811e8612: bpf_trace_run5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bpf_trace_run5(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e7b00)
Location: kernel/trace/bpf_trace.c:2125
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:__bpf_trace_vector_mod
  - kernel/cpu.c:__bpf_trace_cpuhp_multi_enter
  - kernel/signal.c:__bpf_trace_signal_generate
  - kernel/bpf/core.c:__bpf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:__bpf_trace_xdp_cpumap_kthread
  - mm/slab_common.c:__bpf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:__bpf_trace_kmem_alloc
  - mm/compaction.c:__bpf_trace_mm_compaction_begin
  - mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_isolate
  - fs/io_uring.c:__bpf_trace_io_uring_poll_arm
  - fs/io_uring.c:__bpf_trace_io_uring_submit_sqe
  - fs/io_uring.c:__bpf_trace_io_uring_queue_async_work
  - fs/io_uring.c:__bpf_trace_io_uring_create
  - fs/dax.c:__bpf_trace_dax_pmd_insert_mapping_class
  - fs/ext4/super.c:__bpf_trace_ext4_fc_replay
  - fs/ext4/super.c:__bpf_trace_ext4_es_shrink
  - fs/ext4/super.c:__bpf_trace_ext4_remove_blocks
  - fs/ext4/super.c:__bpf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:__bpf_trace_ext4_journal_start
  - fs/ext4/super.c:__bpf_trace_ext4_direct_IO_exit
  - fs/ext4/super.c:__bpf_trace_ext4__mballoc
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_start_class
  - drivers/char/random.c:__bpf_trace_xfer_secondary_pool
  - drivers/ras/ras.c:__bpf_trace_aer_event
  - drivers/ras/ras.c:__bpf_trace_extlog_mem_event
  - drivers/interconnect/core.c:__bpf_trace_icc_set_bw
  - net/core/net-traces.c:__bpf_trace_neigh_update
  - net/core/net-traces.c:__bpf_trace_neigh_create
  - net/core/net-traces.c:__bpf_trace_br_fdb_update
  - net/core/net-traces.c:__bpf_trace_br_fdb_add
  - net/core/devlink.c:__bpf_trace_devlink_hwmsg
```
**Symbols:**

```
ffffffff811e7b00-ffffffff811e7ba7: bpf_trace_run5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bpf_trace_run5(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e8940)
Location: kernel/trace/bpf_trace.c:1821
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:__bpf_trace_vector_mod
  - kernel/cpu.c:__bpf_trace_cpuhp_multi_enter
  - kernel/signal.c:__bpf_trace_signal_generate
  - kernel/bpf/core.c:__bpf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:__bpf_trace_xdp_cpumap_kthread
  - mm/slab_common.c:__bpf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:__bpf_trace_kmem_alloc
  - mm/compaction.c:__bpf_trace_mm_compaction_begin
  - mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_isolate
  - fs/io_uring.c:__bpf_trace_io_uring_poll_arm
  - fs/io_uring.c:__bpf_trace_io_uring_submit_sqe
  - fs/io_uring.c:__bpf_trace_io_uring_queue_async_work
  - fs/io_uring.c:__bpf_trace_io_uring_create
  - fs/dax.c:__bpf_trace_dax_pmd_insert_mapping_class
  - fs/ext4/super.c:__bpf_trace_ext4_fc_replay
  - fs/ext4/super.c:__bpf_trace_ext4_es_shrink
  - fs/ext4/super.c:__bpf_trace_ext4_remove_blocks
  - fs/ext4/super.c:__bpf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:__bpf_trace_ext4_journal_start
  - fs/ext4/super.c:__bpf_trace_ext4__mballoc
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_start_class
  - drivers/iommu/intel/trace.c:__bpf_trace_qi_submit
  - drivers/ras/ras.c:__bpf_trace_aer_event
  - drivers/ras/ras.c:__bpf_trace_extlog_mem_event
  - drivers/interconnect/core.c:__bpf_trace_icc_set_bw
  - net/core/net-traces.c:__bpf_trace_neigh_update
  - net/core/net-traces.c:__bpf_trace_neigh_create
  - net/core/net-traces.c:__bpf_trace_br_fdb_update
  - net/core/net-traces.c:__bpf_trace_br_fdb_add
  - net/core/devlink.c:__bpf_trace_devlink_hwmsg
  - net/mptcp/protocol.c:__bpf_trace_ack_update_msk
```
**Symbols:**

```
ffffffff811e8940-ffffffff811e89e0: bpf_trace_run5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bpf_trace_run5(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812195b0)
Location: kernel/trace/bpf_trace.c:1905
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:__bpf_trace_vector_mod
  - kernel/cpu.c:__bpf_trace_cpuhp_multi_enter
  - kernel/signal.c:__bpf_trace_signal_generate
  - kernel/bpf/core.c:__bpf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:__bpf_trace_xdp_cpumap_kthread
  - mm/slab_common.c:__bpf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:__bpf_trace_kmem_alloc
  - mm/compaction.c:__bpf_trace_mm_compaction_begin
  - mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_isolate
  - fs/io_uring.c:__bpf_trace_io_uring_queue_async_work
  - fs/io_uring.c:__bpf_trace_io_uring_create
  - fs/dax.c:__bpf_trace_dax_pmd_insert_mapping_class
  - fs/ext4/super.c:__bpf_trace_ext4_fc_replay
  - fs/ext4/super.c:__bpf_trace_ext4_es_shrink
  - fs/ext4/super.c:__bpf_trace_ext4_remove_blocks
  - fs/ext4/super.c:__bpf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:__bpf_trace_ext4_journal_start
  - fs/ext4/super.c:__bpf_trace_ext4__mballoc
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_start_class
  - drivers/iommu/intel/trace.c:__bpf_trace_qi_submit
  - drivers/base/trace.c:__bpf_trace_devres
  - drivers/ras/ras.c:__bpf_trace_aer_event
  - drivers/ras/ras.c:__bpf_trace_extlog_mem_event
  - drivers/interconnect/core.c:__bpf_trace_icc_set_bw
  - net/core/net-traces.c:__bpf_trace_neigh_update
  - net/core/net-traces.c:__bpf_trace_neigh_create
  - net/core/net-traces.c:__bpf_trace_br_fdb_update
  - net/core/net-traces.c:__bpf_trace_br_fdb_add
  - net/core/devlink.c:__bpf_trace_devlink_hwmsg
  - net/mptcp/protocol.c:__bpf_trace_ack_update_msk
```
**Symbols:**

```
ffffffff812195b0-ffffffff8121964c: bpf_trace_run5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bpf_trace_run5(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81257e70)
Location: kernel/trace/bpf_trace.c:2086
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:__bpf_trace_vector_mod
  - kernel/cpu.c:__bpf_trace_cpuhp_multi_enter
  - kernel/signal.c:__bpf_trace_signal_generate
  - kernel/bpf/core.c:__bpf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:__bpf_trace_xdp_cpumap_kthread
  - mm/slab_common.c:__bpf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:__bpf_trace_kmem_alloc
  - mm/compaction.c:__bpf_trace_mm_compaction_end
  - mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_isolate
  - fs/dax.c:__bpf_trace_dax_pmd_insert_mapping_class
  - fs/ext4/super.c:__bpf_trace_ext4_fc_track_range
  - fs/ext4/super.c:__bpf_trace_ext4_fc_replay
  - fs/ext4/super.c:__bpf_trace_ext4_es_shrink
  - fs/ext4/super.c:__bpf_trace_ext4_remove_blocks
  - fs/ext4/super.c:__bpf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:__bpf_trace_ext4_journal_start
  - fs/ext4/super.c:__bpf_trace_ext4__mballoc
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_start_class
  - io_uring/io_uring.c:__bpf_trace_io_uring_cqe_overflow
  - io_uring/io_uring.c:__bpf_trace_io_uring_task_add
  - io_uring/io_uring.c:__bpf_trace_io_uring_fail_link
  - io_uring/io_uring.c:__bpf_trace_io_uring_register
  - io_uring/io_uring.c:__bpf_trace_io_uring_create
  - drivers/iommu/intel/trace.c:__bpf_trace_qi_submit
  - drivers/base/trace.c:__bpf_trace_devres
  - drivers/ras/ras.c:__bpf_trace_aer_event
  - drivers/ras/ras.c:__bpf_trace_extlog_mem_event
  - drivers/interconnect/core.c:__bpf_trace_icc_set_bw
  - net/core/net-traces.c:__bpf_trace_neigh_update
  - net/core/net-traces.c:__bpf_trace_neigh_create
  - net/core/net-traces.c:__bpf_trace_br_fdb_update
  - net/core/net-traces.c:__bpf_trace_br_fdb_add
  - net/core/devlink.c:__bpf_trace_devlink_hwmsg
  - net/mptcp/protocol.c:__bpf_trace_ack_update_msk
```
**Symbols:**

```
ffffffff81257e70-ffffffff81257f25: bpf_trace_run5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bpf_trace_run5(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812a75b0)
Location: kernel/trace/bpf_trace.c:2309
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:__bpf_trace_vector_mod
  - kernel/cpu.c:__bpf_trace_cpuhp_multi_enter
  - kernel/signal.c:__bpf_trace_signal_generate
  - kernel/trace/rv/rv.c:__bpf_trace_event_da_monitor_id
  - kernel/bpf/core.c:__bpf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:__bpf_trace_xdp_cpumap_kthread
  - mm/slab_common.c:__bpf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:__bpf_trace_kmem_cache_alloc
  - mm/compaction.c:__bpf_trace_mm_compaction_end
  - mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_isolate
  - fs/dax.c:__bpf_trace_dax_pmd_insert_mapping_class
  - fs/ext4/super.c:__bpf_trace_ext4_fc_track_range
  - fs/ext4/super.c:__bpf_trace_ext4_fc_replay
  - fs/ext4/super.c:__bpf_trace_ext4_es_shrink
  - fs/ext4/super.c:__bpf_trace_ext4_remove_blocks
  - fs/ext4/super.c:__bpf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:__bpf_trace_ext4__mballoc
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_start_class
  - io_uring/io_uring.c:__bpf_trace_io_uring_cqe_overflow
  - io_uring/io_uring.c:__bpf_trace_io_uring_register
  - io_uring/io_uring.c:__bpf_trace_io_uring_create
  - drivers/iommu/intel/trace.c:__bpf_trace_qi_submit
  - drivers/base/trace.c:__bpf_trace_devres
  - drivers/ras/ras.c:__bpf_trace_aer_event
  - drivers/ras/ras.c:__bpf_trace_extlog_mem_event
  - drivers/interconnect/core.c:__bpf_trace_icc_set_bw
  - net/core/net-traces.c:__bpf_trace_neigh_update
  - net/core/net-traces.c:__bpf_trace_neigh_create
  - net/core/net-traces.c:__bpf_trace_br_fdb_update
  - net/core/net-traces.c:__bpf_trace_br_fdb_add
  - net/core/devlink.c:__bpf_trace_devlink_hwmsg
  - net/mptcp/protocol.c:__bpf_trace_ack_update_msk
```
**Symbols:**

```
ffffffff812a75b0-ffffffff812a768e: bpf_trace_run5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_trace_run5(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812c9840)
Location: kernel/trace/bpf_trace.c:2318
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:__bpf_trace_vector_mod
  - kernel/cpu.c:__bpf_trace_cpuhp_multi_enter
  - kernel/signal.c:__bpf_trace_signal_generate
  - kernel/trace/rv/rv.c:__bpf_trace_event_da_monitor_id
  - kernel/bpf/core.c:__bpf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:__bpf_trace_xdp_cpumap_kthread
  - mm/slab_common.c:__bpf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:__bpf_trace_kmem_cache_alloc
  - mm/compaction.c:__bpf_trace_mm_compaction_end
  - mm/ksm.c:__bpf_trace_ksm_merge_with_ksm_page
  - mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_isolate
  - fs/dax.c:__bpf_trace_dax_pmd_insert_mapping_class
  - fs/ext4/super.c:__bpf_trace_ext4_fc_track_range
  - fs/ext4/super.c:__bpf_trace_ext4_fc_replay
  - fs/ext4/super.c:__bpf_trace_ext4_es_shrink
  - fs/ext4/super.c:__bpf_trace_ext4_remove_blocks
  - fs/ext4/super.c:__bpf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:__bpf_trace_ext4__mballoc
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_start_class
  - io_uring/io_uring.c:__bpf_trace_io_uring_cqe_overflow
  - io_uring/io_uring.c:__bpf_trace_io_uring_register
  - io_uring/io_uring.c:__bpf_trace_io_uring_create
  - drivers/iommu/intel/trace.c:__bpf_trace_qi_submit
  - drivers/base/trace.c:__bpf_trace_devres
  - drivers/ras/ras.c:__bpf_trace_aer_event
  - drivers/ras/ras.c:__bpf_trace_extlog_mem_event
  - drivers/interconnect/core.c:__bpf_trace_icc_set_bw
  - net/core/net-traces.c:__bpf_trace_neigh_update
  - net/core/net-traces.c:__bpf_trace_neigh_create
  - net/core/net-traces.c:__bpf_trace_br_fdb_update
  - net/core/net-traces.c:__bpf_trace_br_fdb_add
  - net/devlink/leftover.c:__bpf_trace_devlink_hwmsg
  - net/mptcp/protocol.c:__bpf_trace_ack_update_msk
```
**Symbols:**

```
ffffffff812c9840-ffffffff812c991e: bpf_trace_run5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_trace_run5(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812e65b0)
Location: kernel/trace/bpf_trace.c:2423
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:__bpf_trace_vector_mod
  - kernel/cpu.c:__bpf_trace_cpuhp_multi_enter
  - kernel/signal.c:__bpf_trace_signal_generate
  - kernel/sched/core.c:__bpf_trace_sched_compute_energy_tp
  - kernel/trace/rv/rv.c:__bpf_trace_event_da_monitor_id
  - kernel/bpf/core.c:__bpf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:__bpf_trace_xdp_cpumap_kthread
  - mm/slab_common.c:__bpf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:__bpf_trace_kmem_cache_alloc
  - mm/compaction.c:__bpf_trace_mm_compaction_end
  - mm/ksm.c:__bpf_trace_ksm_merge_with_ksm_page
  - mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_isolate
  - fs/dax.c:__bpf_trace_dax_pmd_insert_mapping_class
  - fs/ext4/super.c:__bpf_trace_ext4_fc_track_range
  - fs/ext4/super.c:__bpf_trace_ext4_fc_replay
  - fs/ext4/super.c:__bpf_trace_ext4_es_shrink
  - fs/ext4/super.c:__bpf_trace_ext4_remove_blocks
  - fs/ext4/super.c:__bpf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:__bpf_trace_ext4__mballoc
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_start_class
  - io_uring/io_uring.c:__bpf_trace_io_uring_cqe_overflow
  - io_uring/io_uring.c:__bpf_trace_io_uring_register
  - io_uring/io_uring.c:__bpf_trace_io_uring_create
  - drivers/iommu/intel/trace.c:__bpf_trace_qi_submit
  - drivers/base/trace.c:__bpf_trace_devres
  - drivers/ras/ras.c:__bpf_trace_aer_event
  - drivers/ras/ras.c:__bpf_trace_extlog_mem_event
  - drivers/interconnect/core.c:__bpf_trace_icc_set_bw
  - net/core/net-traces.c:__bpf_trace_neigh_update
  - net/core/net-traces.c:__bpf_trace_neigh_create
  - net/core/net-traces.c:__bpf_trace_br_fdb_update
  - net/core/net-traces.c:__bpf_trace_br_fdb_add
  - net/devlink/core.c:__bpf_trace_devlink_hwmsg
  - net/mptcp/protocol.c:__bpf_trace_ack_update_msk
```
**Symbols:**

```
ffffffff812e65b0-ffffffff812e668e: bpf_trace_run5 (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void bpf_trace_run5(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffff80001024e010)
Location: kernel/trace/bpf_trace.c:1375
Inline: False
Direct callers:
  - kernel/cpu.c:__bpf_trace_cpuhp_multi_enter
  - kernel/signal.c:__bpf_trace_signal_generate
  - mm/slab_common.c:__bpf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:__bpf_trace_kmem_alloc
  - mm/compaction.c:__bpf_trace_mm_compaction_begin
  - mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_isolate
  - fs/dax.c:__bpf_trace_dax_pmd_insert_mapping_class
  - fs/ext4/super.c:__bpf_trace_ext4_es_shrink
  - fs/ext4/super.c:__bpf_trace_ext4_remove_blocks
  - fs/ext4/super.c:__bpf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:__bpf_trace_ext4_direct_IO_exit
  - fs/ext4/super.c:__bpf_trace_ext4__mballoc
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_start
  - drivers/soc/qcom/rpmh-rsc.c:__bpf_trace_rpmh_send_msg
  - drivers/char/random.c:__bpf_trace_xfer_secondary_pool
  - drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_cpu_get_power
  - drivers/ras/ras.c:__bpf_trace_aer_event
  - net/core/net-traces.c:__bpf_trace_neigh_update
  - net/core/net-traces.c:__bpf_trace_neigh_create
  - net/core/net-traces.c:__bpf_trace_br_fdb_update
  - net/core/net-traces.c:__bpf_trace_br_fdb_add
  - net/core/devlink.c:__bpf_trace_devlink_hwmsg
```
**Symbols:**

```
ffff80001024e010-ffff80001024e0cc: bpf_trace_run5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bpf_trace_run5(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c047f098)
Location: kernel/trace/bpf_trace.c:1375
Inline: False
Direct callers:
  - kernel/cpu.c:__bpf_trace_cpuhp_multi_enter
  - kernel/signal.c:__bpf_trace_signal_generate
  - mm/slab_common.c:__bpf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:__bpf_trace_kmem_alloc
  - mm/compaction.c:__bpf_trace_mm_compaction_begin
  - fs/ext4/super.c:__bpf_trace_ext4_es_shrink
  - fs/ext4/super.c:__bpf_trace_ext4_remove_blocks
  - fs/ext4/super.c:__bpf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:__bpf_trace_ext4_direct_IO_exit
  - fs/ext4/super.c:__bpf_trace_ext4__mballoc
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_start
  - drivers/char/random.c:__bpf_trace_xfer_secondary_pool
  - drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_cpu_get_power
  - drivers/ras/ras.c:__bpf_trace_aer_event
  - net/core/net-traces.c:__bpf_trace_neigh_update
  - net/core/net-traces.c:__bpf_trace_neigh_create
  - net/core/net-traces.c:__bpf_trace_br_fdb_update
  - net/core/net-traces.c:__bpf_trace_br_fdb_add
  - net/core/devlink.c:__bpf_trace_devlink_hwmsg
```
**Symbols:**

```
c047f098-c047f1bc: bpf_trace_run5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bpf_trace_run5(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c0000000002e7e80)
Location: kernel/trace/bpf_trace.c:1375
Inline: False
Direct callers:
  - kernel/cpu.c:__bpf_trace_cpuhp_multi_enter
  - kernel/signal.c:__bpf_trace_signal_generate
  - mm/slab_common.c:__bpf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:__bpf_trace_kmem_alloc
  - mm/compaction.c:__bpf_trace_mm_compaction_begin
  - mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_isolate
  - fs/dax.c:__bpf_trace_dax_pmd_insert_mapping_class
  - fs/ext4/super.c:__bpf_trace_ext4_es_shrink
  - fs/ext4/super.c:__bpf_trace_ext4_remove_blocks
  - fs/ext4/super.c:__bpf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:__bpf_trace_ext4_direct_IO_exit
  - fs/ext4/super.c:__bpf_trace_ext4__mballoc
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_start
  - drivers/char/random.c:__bpf_trace_xfer_secondary_pool
  - drivers/vfio/pci/vfio_pci_nvlink2.c:__bpf_trace_vfio_pci_npu2_mmap
  - drivers/vfio/pci/vfio_pci_nvlink2.c:__bpf_trace_vfio_pci_nvgpu_mmap
  - drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_cpu_get_power
  - drivers/ras/ras.c:__bpf_trace_aer_event
  - net/core/net-traces.c:__bpf_trace_neigh_update
  - net/core/net-traces.c:__bpf_trace_neigh_create
  - net/core/net-traces.c:__bpf_trace_br_fdb_update
  - net/core/net-traces.c:__bpf_trace_br_fdb_add
  - net/core/devlink.c:__bpf_trace_devlink_hwmsg
```
**Symbols:**

```
c0000000002e7e80-c0000000002e7f80: bpf_trace_run5 (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void bpf_trace_run5(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c5200)
Location: kernel/trace/bpf_trace.c:1375
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:__bpf_trace_vector_mod
  - kernel/cpu.c:__bpf_trace_cpuhp_multi_enter
  - kernel/signal.c:__bpf_trace_signal_generate
  - mm/slab_common.c:__bpf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:__bpf_trace_kmem_alloc
  - mm/compaction.c:__bpf_trace_mm_compaction_begin
  - mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_isolate
  - fs/dax.c:__bpf_trace_dax_pmd_insert_mapping_class
  - fs/ext4/super.c:__bpf_trace_ext4_es_shrink
  - fs/ext4/super.c:__bpf_trace_ext4_remove_blocks
  - fs/ext4/super.c:__bpf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:__bpf_trace_ext4_direct_IO_exit
  - fs/ext4/super.c:__bpf_trace_ext4__mballoc
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_start
  - drivers/char/random.c:__bpf_trace_xfer_secondary_pool
  - drivers/ras/ras.c:__bpf_trace_aer_event
  - net/core/net-traces.c:__bpf_trace_neigh_update
  - net/core/net-traces.c:__bpf_trace_neigh_create
  - net/core/net-traces.c:__bpf_trace_br_fdb_update
  - net/core/net-traces.c:__bpf_trace_br_fdb_add
  - net/core/devlink.c:__bpf_trace_devlink_hwmsg
```
**Symbols:**

```
ffffffff811c5200-ffffffff811c52a2: bpf_trace_run5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bpf_trace_run5(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b7fe0)
Location: kernel/trace/bpf_trace.c:1375
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:__bpf_trace_vector_mod
  - kernel/cpu.c:__bpf_trace_cpuhp_multi_enter
  - kernel/signal.c:__bpf_trace_signal_generate
  - mm/slab_common.c:__bpf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:__bpf_trace_kmem_alloc
  - mm/compaction.c:__bpf_trace_mm_compaction_begin
  - mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_isolate
  - fs/dax.c:__bpf_trace_dax_pmd_insert_mapping_class
  - fs/ext4/super.c:__bpf_trace_ext4_es_shrink
  - fs/ext4/super.c:__bpf_trace_ext4_remove_blocks
  - fs/ext4/super.c:__bpf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:__bpf_trace_ext4_direct_IO_exit
  - fs/ext4/super.c:__bpf_trace_ext4__mballoc
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_start
  - drivers/char/random.c:__bpf_trace_xfer_secondary_pool
  - drivers/ras/ras.c:__bpf_trace_aer_event
  - net/core/net-traces.c:__bpf_trace_neigh_update
  - net/core/net-traces.c:__bpf_trace_neigh_create
  - net/core/net-traces.c:__bpf_trace_br_fdb_update
  - net/core/net-traces.c:__bpf_trace_br_fdb_add
  - net/core/devlink.c:__bpf_trace_devlink_hwmsg
```
**Symbols:**

```
ffffffff811b7fe0-ffffffff811b8082: bpf_trace_run5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bpf_trace_run5(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c2fd0)
Location: kernel/trace/bpf_trace.c:1375
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:__bpf_trace_vector_mod
  - kernel/cpu.c:__bpf_trace_cpuhp_multi_enter
  - kernel/signal.c:__bpf_trace_signal_generate
  - mm/slab_common.c:__bpf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:__bpf_trace_kmem_alloc
  - mm/compaction.c:__bpf_trace_mm_compaction_begin
  - mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_isolate
  - fs/dax.c:__bpf_trace_dax_pmd_insert_mapping_class
  - fs/ext4/super.c:__bpf_trace_ext4_es_shrink
  - fs/ext4/super.c:__bpf_trace_ext4_remove_blocks
  - fs/ext4/super.c:__bpf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:__bpf_trace_ext4_direct_IO_exit
  - fs/ext4/super.c:__bpf_trace_ext4__mballoc
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_start
  - drivers/char/random.c:__bpf_trace_xfer_secondary_pool
  - drivers/ras/ras.c:__bpf_trace_aer_event
  - drivers/ras/ras.c:__bpf_trace_extlog_mem_event
  - net/core/net-traces.c:__bpf_trace_neigh_update
  - net/core/net-traces.c:__bpf_trace_neigh_create
  - net/core/net-traces.c:__bpf_trace_br_fdb_update
  - net/core/net-traces.c:__bpf_trace_br_fdb_add
  - net/core/devlink.c:__bpf_trace_devlink_hwmsg
```
**Symbols:**

```
ffffffff811c2fd0-ffffffff811c3072: bpf_trace_run5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bpf_trace_run5(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811d23b0)
Location: kernel/trace/bpf_trace.c:1375
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:__bpf_trace_vector_mod
  - kernel/cpu.c:__bpf_trace_cpuhp_multi_enter
  - kernel/signal.c:__bpf_trace_signal_generate
  - mm/slab_common.c:__bpf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:__bpf_trace_kmem_alloc
  - mm/compaction.c:__bpf_trace_mm_compaction_begin
  - mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_isolate
  - fs/dax.c:__bpf_trace_dax_pmd_insert_mapping_class
  - fs/ext4/super.c:__bpf_trace_ext4_es_shrink
  - fs/ext4/super.c:__bpf_trace_ext4_remove_blocks
  - fs/ext4/super.c:__bpf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:__bpf_trace_ext4_direct_IO_exit
  - fs/ext4/super.c:__bpf_trace_ext4__mballoc
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_start
  - drivers/char/random.c:__bpf_trace_xfer_secondary_pool
  - drivers/ras/ras.c:__bpf_trace_aer_event
  - drivers/ras/ras.c:__bpf_trace_extlog_mem_event
  - net/core/net-traces.c:__bpf_trace_neigh_update
  - net/core/net-traces.c:__bpf_trace_neigh_create
  - net/core/net-traces.c:__bpf_trace_br_fdb_update
  - net/core/net-traces.c:__bpf_trace_br_fdb_add
  - net/core/devlink.c:__bpf_trace_devlink_hwmsg
```
**Symbols:**

```
ffffffff811d23b0-ffffffff811d2473: bpf_trace_run5 (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
