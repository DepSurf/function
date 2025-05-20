# Function: <code>bpf_trace_run7</code>

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
void bpf_trace_run7(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811a4990)
Location: kernel/trace/bpf_trace.c:1139
Inline: False
Direct callers:
  - kernel/bpf/core.c:__bpf_trace_xdp_devmap_xmit
  - mm/oom_kill.c:__bpf_trace_reclaim_retry_zone
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:__bpf_trace_mm_shrink_slab_start
  - mm/percpu.c:__bpf_trace_percpu_alloc_percpu
  - mm/khugepaged.c:__bpf_trace_mm_khugepaged_scan_pmd
  - block/blk-wbt.c:__bpf_trace_wbt_step
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_result
  - drivers/thermal/power_allocator.c:__bpf_trace_thermal_power_allocator_pid
```
**Symbols:**

```
ffffffff811a4990-ffffffff811a49f2: bpf_trace_run7 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bpf_trace_run7(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b2a60)
Location: kernel/trace/bpf_trace.c:1184
Inline: False
Direct callers:
  - kernel/bpf/core.c:__bpf_trace_xdp_devmap_xmit
  - mm/oom_kill.c:__bpf_trace_reclaim_retry_zone
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:__bpf_trace_mm_shrink_slab_start
  - mm/percpu.c:__bpf_trace_percpu_alloc_percpu
  - mm/khugepaged.c:__bpf_trace_mm_khugepaged_scan_pmd
  - block/blk-wbt.c:__bpf_trace_wbt_step
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_result
  - drivers/thermal/power_allocator.c:__bpf_trace_thermal_power_allocator_pid
```
**Symbols:**

```
ffffffff811b2a60-ffffffff811b2ac2: bpf_trace_run7 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bpf_trace_run7(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c1590)
Location: kernel/trace/bpf_trace.c:1353
Inline: False
Direct callers:
  - kernel/bpf/core.c:__bpf_trace_xdp_devmap_xmit
  - mm/oom_kill.c:__bpf_trace_reclaim_retry_zone
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:__bpf_trace_mm_shrink_slab_start
  - mm/percpu.c:__bpf_trace_percpu_alloc_percpu
  - mm/khugepaged.c:__bpf_trace_mm_khugepaged_scan_pmd
  - block/blk-wbt.c:__bpf_trace_wbt_step
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_write
  - drivers/thermal/power_allocator.c:__bpf_trace_thermal_power_allocator_pid
```
**Symbols:**

```
ffffffff811c1590-ffffffff811c1642: bpf_trace_run7 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bpf_trace_run7(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811ccd40)
Location: kernel/trace/bpf_trace.c:1377
Inline: False
Direct callers:
  - kernel/bpf/core.c:__bpf_trace_xdp_devmap_xmit
  - mm/oom_kill.c:__bpf_trace_reclaim_retry_zone
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:__bpf_trace_mm_shrink_slab_start
  - mm/percpu.c:__bpf_trace_percpu_alloc_percpu
  - mm/khugepaged.c:__bpf_trace_mm_khugepaged_scan_pmd
  - block/blk-iocost.c:__bpf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:__bpf_trace_iocg_inuse_update
  - block/blk-wbt.c:__bpf_trace_wbt_step
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_write
  - drivers/thermal/power_allocator.c:__bpf_trace_thermal_power_allocator_pid
```
**Symbols:**

```
ffffffff811ccd40-ffffffff811ccdf2: bpf_trace_run7 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bpf_trace_run7(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e86d0)
Location: kernel/trace/bpf_trace.c:1871
Inline: False
Direct callers:
  - mm/oom_kill.c:__bpf_trace_reclaim_retry_zone
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:__bpf_trace_mm_shrink_slab_start
  - mm/percpu.c:__bpf_trace_percpu_alloc_percpu
  - mm/khugepaged.c:__bpf_trace_mm_khugepaged_scan_pmd
  - fs/iomap/trace.c:__bpf_trace_iomap_apply
  - block/blk-iocost.c:__bpf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:__bpf_trace_iocg_inuse_update
  - block/blk-wbt.c:__bpf_trace_wbt_step
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_write
  - drivers/thermal/gov_power_allocator.c:__bpf_trace_thermal_power_allocator_pid
```
**Symbols:**

```
ffffffff811e86d0-ffffffff811e8782: bpf_trace_run7 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bpf_trace_run7(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e7c60)
Location: kernel/trace/bpf_trace.c:2127
Inline: False
Direct callers:
  - mm/oom_kill.c:__bpf_trace_reclaim_retry_zone
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:__bpf_trace_mm_shrink_slab_start
  - mm/percpu.c:__bpf_trace_percpu_alloc_percpu
  - mm/migrate.c:__bpf_trace_mm_migrate_pages
  - mm/khugepaged.c:__bpf_trace_mm_khugepaged_scan_pmd
  - fs/iomap/trace.c:__bpf_trace_iomap_apply
  - block/blk-iocost.c:__bpf_trace_iocg_inuse_update
  - block/blk-wbt.c:__bpf_trace_wbt_step
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_write
  - drivers/thermal/gov_power_allocator.c:__bpf_trace_thermal_power_allocator_pid
```
**Symbols:**

```
ffffffff811e7c60-ffffffff811e7d17: bpf_trace_run7 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bpf_trace_run7(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e8a90)
Location: kernel/trace/bpf_trace.c:1823
Inline: False
Direct callers:
  - kernel/bpf/core.c:__bpf_trace_xdp_redirect_template
  - mm/oom_kill.c:__bpf_trace_reclaim_retry_zone
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:__bpf_trace_mm_shrink_slab_start
  - mm/percpu.c:__bpf_trace_percpu_alloc_percpu
  - mm/migrate.c:__bpf_trace_mm_migrate_pages
  - mm/khugepaged.c:__bpf_trace_mm_khugepaged_scan_pmd
  - fs/iomap/trace.c:__bpf_trace_iomap_apply
  - block/blk-iocost.c:__bpf_trace_iocg_inuse_update
  - block/blk-wbt.c:__bpf_trace_wbt_step
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_write
  - drivers/thermal/gov_power_allocator.c:__bpf_trace_thermal_power_allocator_pid
```
**Symbols:**

```
ffffffff811e8a90-ffffffff811e8b40: bpf_trace_run7 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bpf_trace_run7(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81219700)
Location: kernel/trace/bpf_trace.c:1907
Inline: False
Direct callers:
  - kernel/bpf/core.c:__bpf_trace_xdp_redirect_template
  - mm/oom_kill.c:__bpf_trace_reclaim_retry_zone
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:__bpf_trace_mm_shrink_slab_start
  - mm/percpu.c:__bpf_trace_percpu_alloc_percpu
  - mm/migrate.c:__bpf_trace_mm_migrate_pages
  - mm/khugepaged.c:__bpf_trace_mm_khugepaged_scan_pmd
  - fs/io_uring.c:__bpf_trace_io_uring_submit_sqe
  - fs/jbd2/journal.c:__bpf_trace_jbd2_shrink_checkpoint_list
  - block/blk-iocost.c:__bpf_trace_iocg_inuse_update
  - block/blk-wbt.c:__bpf_trace_wbt_step
  - drivers/iommu/intel/trace.c:__bpf_trace_prq_report
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_write
  - drivers/thermal/gov_power_allocator.c:__bpf_trace_thermal_power_allocator_pid
```
**Symbols:**

```
ffffffff81219700-ffffffff812197ac: bpf_trace_run7 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bpf_trace_run7(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81257ff0)
Location: kernel/trace/bpf_trace.c:2088
Inline: False
Direct callers:
  - kernel/bpf/core.c:__bpf_trace_xdp_redirect_template
  - mm/oom_kill.c:__bpf_trace_reclaim_retry_zone
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:__bpf_trace_mm_shrink_slab_start
  - mm/rmap.c:__bpf_trace_mm_migrate_pages
  - mm/khugepaged.c:__bpf_trace_mm_khugepaged_scan_pmd
  - fs/jbd2/journal.c:__bpf_trace_jbd2_shrink_checkpoint_list
  - block/blk-iocost.c:__bpf_trace_iocg_inuse_update
  - block/blk-wbt.c:__bpf_trace_wbt_step
  - io_uring/io_uring.c:__bpf_trace_io_uring_submit_sqe
  - io_uring/io_uring.c:__bpf_trace_io_uring_complete
  - io_uring/io_uring.c:__bpf_trace_io_uring_queue_async_work
  - drivers/iommu/intel/trace.c:__bpf_trace_prq_report
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_write
  - drivers/thermal/gov_power_allocator.c:__bpf_trace_thermal_power_allocator_pid
```
**Symbols:**

```
ffffffff81257ff0-ffffffff812580b5: bpf_trace_run7 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bpf_trace_run7(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812a77a0)
Location: kernel/trace/bpf_trace.c:2311
Inline: False
Direct callers:
  - kernel/bpf/core.c:__bpf_trace_xdp_redirect_template
  - mm/oom_kill.c:__bpf_trace_reclaim_retry_zone
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:__bpf_trace_mm_shrink_slab_start
  - mm/rmap.c:__bpf_trace_mm_migrate_pages
  - mm/khugepaged.c:__bpf_trace_mm_khugepaged_scan_pmd
  - fs/jbd2/journal.c:__bpf_trace_jbd2_shrink_checkpoint_list
  - block/blk-iocost.c:__bpf_trace_iocg_inuse_update
  - block/blk-wbt.c:__bpf_trace_wbt_step
  - io_uring/io_uring.c:__bpf_trace_io_uring_complete
  - drivers/iommu/intel/trace.c:__bpf_trace_prq_report
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_write
  - drivers/thermal/gov_power_allocator.c:__bpf_trace_thermal_power_allocator_pid
```
**Symbols:**

```
ffffffff812a77a0-ffffffff812a788e: bpf_trace_run7 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_trace_run7(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812c9a30)
Location: kernel/trace/bpf_trace.c:2320
Inline: False
Direct callers:
  - kernel/bpf/core.c:__bpf_trace_xdp_redirect_template
  - mm/oom_kill.c:__bpf_trace_reclaim_retry_zone
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:__bpf_trace_mm_shrink_slab_start
  - mm/rmap.c:__bpf_trace_mm_migrate_pages
  - mm/khugepaged.c:__bpf_trace_mm_khugepaged_scan_pmd
  - block/blk-iocost.c:__bpf_trace_iocg_inuse_update
  - block/blk-wbt.c:__bpf_trace_wbt_step
  - io_uring/io_uring.c:__bpf_trace_io_uring_complete
  - drivers/iommu/intel/trace.c:__bpf_trace_prq_report
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_write
  - drivers/thermal/gov_power_allocator.c:__bpf_trace_thermal_power_allocator_pid
```
**Symbols:**

```
ffffffff812c9a30-ffffffff812c9b1e: bpf_trace_run7 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_trace_run7(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812e67a0)
Location: kernel/trace/bpf_trace.c:2425
Inline: False
Direct callers:
  - kernel/bpf/core.c:__bpf_trace_xdp_redirect_template
  - mm/oom_kill.c:__bpf_trace_reclaim_retry_zone
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_isolate
  - mm/vmscan.c:__bpf_trace_mm_shrink_slab_start
  - mm/khugepaged.c:__bpf_trace_mm_khugepaged_scan_pmd
  - block/blk-iocost.c:__bpf_trace_iocg_inuse_update
  - block/blk-wbt.c:__bpf_trace_wbt_step
  - io_uring/io_uring.c:__bpf_trace_io_uring_complete
  - drivers/iommu/intel/trace.c:__bpf_trace_prq_report
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_write
  - drivers/thermal/gov_power_allocator.c:__bpf_trace_thermal_power_allocator_pid
```
**Symbols:**

```
ffffffff812e67a0-ffffffff812e688e: bpf_trace_run7 (STB_GLOBAL)
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
void bpf_trace_run7(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffff80001024e190)
Location: kernel/trace/bpf_trace.c:1377
Inline: False
Direct callers:
  - kernel/bpf/core.c:__bpf_trace_xdp_devmap_xmit
  - mm/oom_kill.c:__bpf_trace_reclaim_retry_zone
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:__bpf_trace_mm_shrink_slab_start
  - mm/percpu.c:__bpf_trace_percpu_alloc_percpu
  - mm/khugepaged.c:__bpf_trace_mm_khugepaged_scan_pmd
  - block/blk-iocost.c:__bpf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:__bpf_trace_iocg_inuse_update
  - block/blk-wbt.c:__bpf_trace_wbt_step
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_write
  - drivers/thermal/power_allocator.c:__bpf_trace_thermal_power_allocator_pid
```
**Symbols:**

```
ffff80001024e190-ffff80001024e250: bpf_trace_run7 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bpf_trace_run7(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c047f2e8)
Location: kernel/trace/bpf_trace.c:1377
Inline: False
Direct callers:
  - kernel/bpf/core.c:__bpf_trace_xdp_devmap_xmit
  - mm/oom_kill.c:__bpf_trace_reclaim_retry_zone
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:__bpf_trace_mm_shrink_slab_start
  - mm/percpu.c:__bpf_trace_percpu_alloc_percpu
  - block/blk-iocost.c:__bpf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:__bpf_trace_iocg_inuse_update
  - block/blk-wbt.c:__bpf_trace_wbt_step
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_write
  - drivers/thermal/power_allocator.c:__bpf_trace_thermal_power_allocator_pid
```
**Symbols:**

```
c047f2e8-c047f41c: bpf_trace_run7 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bpf_trace_run7(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c0000000002e8080)
Location: kernel/trace/bpf_trace.c:1377
Inline: False
Direct callers:
  - arch/powerpc/kernel/irq.c:__bpf_trace_tlbie
  - kernel/bpf/core.c:__bpf_trace_xdp_devmap_xmit
  - mm/oom_kill.c:__bpf_trace_reclaim_retry_zone
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:__bpf_trace_mm_shrink_slab_start
  - mm/percpu.c:__bpf_trace_percpu_alloc_percpu
  - mm/khugepaged.c:__bpf_trace_mm_khugepaged_scan_pmd
  - block/blk-iocost.c:__bpf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:__bpf_trace_iocg_inuse_update
  - block/blk-wbt.c:__bpf_trace_wbt_step
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_write
  - drivers/thermal/power_allocator.c:__bpf_trace_thermal_power_allocator_pid
```
**Symbols:**

```
c0000000002e8080-c0000000002e8180: bpf_trace_run7 (STB_GLOBAL)
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
void bpf_trace_run7(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c5360)
Location: kernel/trace/bpf_trace.c:1377
Inline: False
Direct callers:
  - kernel/bpf/core.c:__bpf_trace_xdp_devmap_xmit
  - mm/oom_kill.c:__bpf_trace_reclaim_retry_zone
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:__bpf_trace_mm_shrink_slab_start
  - mm/percpu.c:__bpf_trace_percpu_alloc_percpu
  - mm/khugepaged.c:__bpf_trace_mm_khugepaged_scan_pmd
  - block/blk-iocost.c:__bpf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:__bpf_trace_iocg_inuse_update
  - block/blk-wbt.c:__bpf_trace_wbt_step
  - drivers/thermal/power_allocator.c:__bpf_trace_thermal_power_allocator_pid
```
**Symbols:**

```
ffffffff811c5360-ffffffff811c5412: bpf_trace_run7 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bpf_trace_run7(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b8140)
Location: kernel/trace/bpf_trace.c:1377
Inline: False
Direct callers:
  - kernel/bpf/core.c:__bpf_trace_xdp_devmap_xmit
  - mm/oom_kill.c:__bpf_trace_reclaim_retry_zone
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:__bpf_trace_mm_shrink_slab_start
  - mm/percpu.c:__bpf_trace_percpu_alloc_percpu
  - mm/khugepaged.c:__bpf_trace_mm_khugepaged_scan_pmd
  - block/blk-iocost.c:__bpf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:__bpf_trace_iocg_inuse_update
  - block/blk-wbt.c:__bpf_trace_wbt_step
  - drivers/thermal/power_allocator.c:__bpf_trace_thermal_power_allocator_pid
```
**Symbols:**

```
ffffffff811b8140-ffffffff811b81f2: bpf_trace_run7 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bpf_trace_run7(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c3130)
Location: kernel/trace/bpf_trace.c:1377
Inline: False
Direct callers:
  - kernel/bpf/core.c:__bpf_trace_xdp_devmap_xmit
  - mm/oom_kill.c:__bpf_trace_reclaim_retry_zone
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:__bpf_trace_mm_shrink_slab_start
  - mm/percpu.c:__bpf_trace_percpu_alloc_percpu
  - mm/khugepaged.c:__bpf_trace_mm_khugepaged_scan_pmd
  - block/blk-iocost.c:__bpf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:__bpf_trace_iocg_inuse_update
  - block/blk-wbt.c:__bpf_trace_wbt_step
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_write
  - drivers/thermal/power_allocator.c:__bpf_trace_thermal_power_allocator_pid
```
**Symbols:**

```
ffffffff811c3130-ffffffff811c31e2: bpf_trace_run7 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bpf_trace_run7(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811d2550)
Location: kernel/trace/bpf_trace.c:1377
Inline: False
Direct callers:
  - kernel/bpf/core.c:__bpf_trace_xdp_devmap_xmit
  - mm/oom_kill.c:__bpf_trace_reclaim_retry_zone
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:__bpf_trace_mm_shrink_slab_start
  - mm/percpu.c:__bpf_trace_percpu_alloc_percpu
  - mm/khugepaged.c:__bpf_trace_mm_khugepaged_scan_pmd
  - block/blk-iocost.c:__bpf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:__bpf_trace_iocg_inuse_update
  - block/blk-wbt.c:__bpf_trace_wbt_step
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_write
  - drivers/thermal/power_allocator.c:__bpf_trace_thermal_power_allocator_pid
```
**Symbols:**

```
ffffffff811d2550-ffffffff811d2623: bpf_trace_run7 (STB_GLOBAL)
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
