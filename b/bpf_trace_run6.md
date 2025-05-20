# Function: <code>bpf_trace_run6</code>

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
void bpf_trace_run6(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811a4930)
Location: kernel/trace/bpf_trace.c:1138
Inline: False
Direct callers:
  - kernel/bpf/core.c:__bpf_trace_xdp_redirect_template
  - mm/oom_kill.c:__bpf_trace_compact_retry
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:__bpf_trace_mm_shrink_slab_end
  - mm/slab_common.c:__bpf_trace_kmem_alloc_node
  - mm/compaction.c:__bpf_trace_mm_compaction_end
  - fs/ext4/super.c:__bpf_trace_ext4_fsmap_class
  - fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space_done
  - fs/ext4/super.c:__bpf_trace_ext4_find_delalloc_range
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_extend
  - drivers/net/phy/mdio_bus.c:__bpf_trace_mdio_access
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_read
  - drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_get_power
  - drivers/ras/ras.c:__bpf_trace_non_standard_event
```
**Symbols:**

```
ffffffff811a4930-ffffffff811a498a: bpf_trace_run6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bpf_trace_run6(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b2a00)
Location: kernel/trace/bpf_trace.c:1183
Inline: False
Direct callers:
  - kernel/bpf/core.c:__bpf_trace_xdp_redirect_template
  - mm/oom_kill.c:__bpf_trace_compact_retry
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:__bpf_trace_mm_shrink_slab_end
  - mm/slab_common.c:__bpf_trace_kmem_alloc_node
  - mm/compaction.c:__bpf_trace_mm_compaction_end
  - fs/ext4/super.c:__bpf_trace_ext4_fsmap_class
  - fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space_done
  - fs/ext4/super.c:__bpf_trace_ext4_find_delalloc_range
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_extend
  - drivers/net/phy/mdio_bus.c:__bpf_trace_mdio_access
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_read
  - drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_get_power
  - drivers/ras/ras.c:__bpf_trace_non_standard_event
```
**Symbols:**

```
ffffffff811b2a00-ffffffff811b2a5a: bpf_trace_run6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bpf_trace_run6(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c14e0)
Location: kernel/trace/bpf_trace.c:1352
Inline: False
Direct callers:
  - kernel/bpf/core.c:__bpf_trace_xdp_redirect_template
  - mm/oom_kill.c:__bpf_trace_compact_retry
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:__bpf_trace_mm_shrink_slab_end
  - mm/slab_common.c:__bpf_trace_kmem_alloc_node
  - mm/compaction.c:__bpf_trace_mm_compaction_end
  - fs/ext4/super.c:__bpf_trace_ext4_fsmap_class
  - fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space_done
  - fs/ext4/super.c:__bpf_trace_ext4_find_delalloc_range
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_extend
  - drivers/net/phy/mdio_bus.c:__bpf_trace_mdio_access
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_read
  - drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_get_power
  - drivers/ras/ras.c:__bpf_trace_non_standard_event
```
**Symbols:**

```
ffffffff811c14e0-ffffffff811c158a: bpf_trace_run6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bpf_trace_run6(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811ccc90)
Location: kernel/trace/bpf_trace.c:1376
Inline: False
Direct callers:
  - kernel/bpf/core.c:__bpf_trace_xdp_redirect_template
  - mm/oom_kill.c:__bpf_trace_compact_retry
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:__bpf_trace_mm_shrink_slab_end
  - mm/slab_common.c:__bpf_trace_kmem_alloc_node
  - mm/compaction.c:__bpf_trace_mm_compaction_end
  - fs/ext4/super.c:__bpf_trace_ext4_fsmap_class
  - fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space_done
  - fs/ext4/super.c:__bpf_trace_ext4_find_delalloc_range
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_extend
  - block/blk-iocost.c:__bpf_trace_iocost_iocg_activate
  - drivers/net/phy/mdio_bus.c:__bpf_trace_mdio_access
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_read
  - drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_get_power
  - drivers/ras/ras.c:__bpf_trace_non_standard_event
```
**Symbols:**

```
ffffffff811ccc90-ffffffff811ccd3a: bpf_trace_run6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bpf_trace_run6(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e8620)
Location: kernel/trace/bpf_trace.c:1870
Inline: False
Direct callers:
  - kernel/bpf/core.c:__bpf_trace_xdp_redirect_template
  - mm/oom_kill.c:__bpf_trace_compact_retry
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:__bpf_trace_mm_shrink_slab_end
  - mm/slab_common.c:__bpf_trace_kmem_alloc_node
  - mm/compaction.c:__bpf_trace_mm_compaction_end
  - fs/io_uring.c:__bpf_trace_io_uring_register
  - fs/ext4/super.c:__bpf_trace_ext4_fsmap_class
  - fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space_done
  - fs/ext4/super.c:__bpf_trace_ext4_find_delalloc_range
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_extend
  - block/blk-iocost.c:__bpf_trace_iocost_iocg_activate
  - drivers/net/phy/mdio_bus.c:__bpf_trace_mdio_access
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_read
  - drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_get_power
  - drivers/ras/ras.c:__bpf_trace_non_standard_event
```
**Symbols:**

```
ffffffff811e8620-ffffffff811e86ca: bpf_trace_run6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bpf_trace_run6(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e7bb0)
Location: kernel/trace/bpf_trace.c:2126
Inline: False
Direct callers:
  - kernel/bpf/core.c:__bpf_trace_xdp_redirect_template
  - mm/oom_kill.c:__bpf_trace_compact_retry
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:__bpf_trace_mm_shrink_slab_end
  - mm/slab_common.c:__bpf_trace_kmem_alloc_node
  - mm/compaction.c:__bpf_trace_mm_compaction_end
  - fs/io_uring.c:__bpf_trace_io_uring_register
  - fs/ext4/super.c:__bpf_trace_ext4_fsmap_class
  - fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space_done
  - fs/ext4/super.c:__bpf_trace_ext4_find_delalloc_range
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_extend
  - block/blk-iocost.c:__bpf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:__bpf_trace_iocost_iocg_state
  - drivers/net/phy/mdio_bus.c:__bpf_trace_mdio_access
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_read
  - drivers/ras/ras.c:__bpf_trace_non_standard_event
```
**Symbols:**

```
ffffffff811e7bb0-ffffffff811e7c5f: bpf_trace_run6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bpf_trace_run6(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e89e0)
Location: kernel/trace/bpf_trace.c:1822
Inline: False
Direct callers:
  - mm/oom_kill.c:__bpf_trace_compact_retry
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:__bpf_trace_mm_shrink_slab_end
  - mm/slab_common.c:__bpf_trace_kmem_alloc_node
  - mm/compaction.c:__bpf_trace_mm_compaction_end
  - fs/io_uring.c:__bpf_trace_io_uring_register
  - fs/ext4/super.c:__bpf_trace_ext4_fsmap_class
  - fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space_done
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_extend
  - block/blk-iocost.c:__bpf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:__bpf_trace_iocost_iocg_state
  - drivers/net/phy/mdio_bus.c:__bpf_trace_mdio_access
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_read
  - drivers/ras/ras.c:__bpf_trace_non_standard_event
```
**Symbols:**

```
ffffffff811e89e0-ffffffff811e8a88: bpf_trace_run6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bpf_trace_run6(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81219650)
Location: kernel/trace/bpf_trace.c:1906
Inline: False
Direct callers:
  - mm/oom_kill.c:__bpf_trace_compact_retry
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:__bpf_trace_mm_shrink_slab_end
  - mm/slab_common.c:__bpf_trace_kmem_alloc_node
  - mm/compaction.c:__bpf_trace_mm_compaction_end
  - fs/io_uring.c:__bpf_trace_io_uring_poll_arm
  - fs/io_uring.c:__bpf_trace_io_uring_register
  - fs/ext4/super.c:__bpf_trace_ext4_fsmap_class
  - fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space_done
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_extend
  - block/blk-iocost.c:__bpf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:__bpf_trace_iocost_iocg_state
  - drivers/net/phy/mdio_bus.c:__bpf_trace_mdio_access
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_read
  - drivers/ras/ras.c:__bpf_trace_non_standard_event
```
**Symbols:**

```
ffffffff81219650-ffffffff812196f4: bpf_trace_run6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bpf_trace_run6(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81257f30)
Location: kernel/trace/bpf_trace.c:2087
Inline: False
Direct callers:
  - mm/oom_kill.c:__bpf_trace_compact_retry
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:__bpf_trace_mm_shrink_slab_end
  - mm/slab_common.c:__bpf_trace_kmem_alloc_node
  - fs/ext4/super.c:__bpf_trace_ext4_fsmap_class
  - fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space_done
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_extend
  - block/blk-iocost.c:__bpf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:__bpf_trace_iocost_iocg_state
  - io_uring/io_uring.c:__bpf_trace_io_uring_poll_arm
  - drivers/net/phy/mdio_bus.c:__bpf_trace_mdio_access
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_read
  - drivers/ras/ras.c:__bpf_trace_non_standard_event
```
**Symbols:**

```
ffffffff81257f30-ffffffff81257fed: bpf_trace_run6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bpf_trace_run6(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812a76a0)
Location: kernel/trace/bpf_trace.c:2310
Inline: False
Direct callers:
  - mm/oom_kill.c:__bpf_trace_compact_retry
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:__bpf_trace_mm_shrink_slab_end
  - mm/slab_common.c:__bpf_trace_kmalloc
  - mm/vmalloc.c:__bpf_trace_alloc_vmap_area
  - mm/khugepaged.c:__bpf_trace_mm_khugepaged_scan_file
  - fs/ext4/super.c:__bpf_trace_ext4_fsmap_class
  - fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space_done
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_extend
  - block/blk-iocost.c:__bpf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:__bpf_trace_iocost_iocg_state
  - drivers/net/phy/mdio_bus.c:__bpf_trace_mdio_access
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_read
  - drivers/ras/ras.c:__bpf_trace_non_standard_event
```
**Symbols:**

```
ffffffff812a76a0-ffffffff812a7786: bpf_trace_run6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_trace_run6(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812c9930)
Location: kernel/trace/bpf_trace.c:2319
Inline: False
Direct callers:
  - mm/oom_kill.c:__bpf_trace_compact_retry
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:__bpf_trace_mm_shrink_slab_end
  - mm/slab_common.c:__bpf_trace_kmalloc
  - mm/vmalloc.c:__bpf_trace_alloc_vmap_area
  - mm/khugepaged.c:__bpf_trace_mm_khugepaged_scan_file
  - fs/ext4/super.c:__bpf_trace_ext4_fsmap_class
  - fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space_done
  - fs/jbd2/journal.c:__bpf_trace_jbd2_shrink_checkpoint_list
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_extend
  - block/blk-iocost.c:__bpf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:__bpf_trace_iocost_iocg_state
  - drivers/net/phy/mdio_bus.c:__bpf_trace_mdio_access
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_read
  - drivers/ras/ras.c:__bpf_trace_non_standard_event
```
**Symbols:**

```
ffffffff812c9930-ffffffff812c9a16: bpf_trace_run6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_trace_run6(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812e66a0)
Location: kernel/trace/bpf_trace.c:2424
Inline: False
Direct callers:
  - mm/oom_kill.c:__bpf_trace_compact_retry
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:__bpf_trace_mm_shrink_slab_end
  - mm/slab_common.c:__bpf_trace_kmalloc
  - mm/vmalloc.c:__bpf_trace_alloc_vmap_area
  - mm/khugepaged.c:__bpf_trace_mm_khugepaged_scan_file
  - fs/ext4/super.c:__bpf_trace_ext4_fsmap_class
  - fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space_done
  - fs/jbd2/journal.c:__bpf_trace_jbd2_shrink_checkpoint_list
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_extend
  - block/blk-iocost.c:__bpf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:__bpf_trace_iocost_iocg_state
  - drivers/net/phy/mdio_bus.c:__bpf_trace_mdio_access
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_read
  - drivers/ras/ras.c:__bpf_trace_non_standard_event
```
**Symbols:**

```
ffffffff812e66a0-ffffffff812e6786: bpf_trace_run6 (STB_GLOBAL)
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
void bpf_trace_run6(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffff80001024e0d0)
Location: kernel/trace/bpf_trace.c:1376
Inline: False
Direct callers:
  - kernel/bpf/core.c:__bpf_trace_xdp_redirect_template
  - mm/oom_kill.c:__bpf_trace_compact_retry
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:__bpf_trace_mm_shrink_slab_end
  - mm/slab_common.c:__bpf_trace_kmem_alloc_node
  - mm/compaction.c:__bpf_trace_mm_compaction_end
  - fs/ext4/super.c:__bpf_trace_ext4_fsmap_class
  - fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space_done
  - fs/ext4/super.c:__bpf_trace_ext4_find_delalloc_range
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_extend
  - block/blk-iocost.c:__bpf_trace_iocost_iocg_activate
  - drivers/net/phy/mdio_bus.c:__bpf_trace_mdio_access
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_read
  - drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_get_power
  - drivers/ras/ras.c:__bpf_trace_non_standard_event
```
**Symbols:**

```
ffff80001024e0d0-ffff80001024e18c: bpf_trace_run6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bpf_trace_run6(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c047f1bc)
Location: kernel/trace/bpf_trace.c:1376
Inline: False
Direct callers:
  - kernel/bpf/core.c:__bpf_trace_xdp_redirect_template
  - mm/oom_kill.c:__bpf_trace_compact_retry
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:__bpf_trace_mm_shrink_slab_end
  - mm/slab_common.c:__bpf_trace_kmem_alloc_node
  - mm/compaction.c:__bpf_trace_mm_compaction_end
  - fs/ext4/super.c:__bpf_trace_ext4_fsmap_class
  - fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space_done
  - fs/ext4/super.c:__bpf_trace_ext4_find_delalloc_range
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_extend
  - block/blk-iocost.c:__bpf_trace_iocost_iocg_activate
  - drivers/net/phy/mdio_bus.c:__bpf_trace_mdio_access
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_read
  - drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_get_power
  - drivers/ras/ras.c:__bpf_trace_non_standard_event
```
**Symbols:**

```
c047f1bc-c047f2e8: bpf_trace_run6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bpf_trace_run6(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c0000000002e7f80)
Location: kernel/trace/bpf_trace.c:1376
Inline: False
Direct callers:
  - kernel/bpf/core.c:__bpf_trace_xdp_redirect_template
  - mm/oom_kill.c:__bpf_trace_compact_retry
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:__bpf_trace_mm_shrink_slab_end
  - mm/slab_common.c:__bpf_trace_kmem_alloc_node
  - mm/compaction.c:__bpf_trace_mm_compaction_end
  - fs/ext4/super.c:__bpf_trace_ext4_fsmap_class
  - fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space_done
  - fs/ext4/super.c:__bpf_trace_ext4_find_delalloc_range
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_extend
  - block/blk-iocost.c:__bpf_trace_iocost_iocg_activate
  - drivers/net/phy/mdio_bus.c:__bpf_trace_mdio_access
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_read
  - drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_get_power
  - drivers/ras/ras.c:__bpf_trace_non_standard_event
```
**Symbols:**

```
c0000000002e7f80-c0000000002e8080: bpf_trace_run6 (STB_GLOBAL)
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
void bpf_trace_run6(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c52b0)
Location: kernel/trace/bpf_trace.c:1376
Inline: False
Direct callers:
  - kernel/bpf/core.c:__bpf_trace_xdp_redirect_template
  - mm/oom_kill.c:__bpf_trace_compact_retry
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:__bpf_trace_mm_shrink_slab_end
  - mm/slab_common.c:__bpf_trace_kmem_alloc_node
  - mm/compaction.c:__bpf_trace_mm_compaction_end
  - fs/ext4/super.c:__bpf_trace_ext4_fsmap_class
  - fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space_done
  - fs/ext4/super.c:__bpf_trace_ext4_find_delalloc_range
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_extend
  - block/blk-iocost.c:__bpf_trace_iocost_iocg_activate
  - drivers/net/phy/mdio_bus.c:__bpf_trace_mdio_access
  - drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_get_power
  - drivers/ras/ras.c:__bpf_trace_non_standard_event
```
**Symbols:**

```
ffffffff811c52b0-ffffffff811c535a: bpf_trace_run6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bpf_trace_run6(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b8090)
Location: kernel/trace/bpf_trace.c:1376
Inline: False
Direct callers:
  - kernel/bpf/core.c:__bpf_trace_xdp_redirect_template
  - mm/oom_kill.c:__bpf_trace_compact_retry
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:__bpf_trace_mm_shrink_slab_end
  - mm/slab_common.c:__bpf_trace_kmem_alloc_node
  - mm/compaction.c:__bpf_trace_mm_compaction_end
  - fs/ext4/super.c:__bpf_trace_ext4_fsmap_class
  - fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space_done
  - fs/ext4/super.c:__bpf_trace_ext4_find_delalloc_range
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_extend
  - block/blk-iocost.c:__bpf_trace_iocost_iocg_activate
  - drivers/net/phy/mdio_bus.c:__bpf_trace_mdio_access
  - drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_get_power
  - drivers/ras/ras.c:__bpf_trace_non_standard_event
```
**Symbols:**

```
ffffffff811b8090-ffffffff811b813a: bpf_trace_run6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bpf_trace_run6(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c3080)
Location: kernel/trace/bpf_trace.c:1376
Inline: False
Direct callers:
  - kernel/bpf/core.c:__bpf_trace_xdp_redirect_template
  - mm/oom_kill.c:__bpf_trace_compact_retry
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:__bpf_trace_mm_shrink_slab_end
  - mm/slab_common.c:__bpf_trace_kmem_alloc_node
  - mm/compaction.c:__bpf_trace_mm_compaction_end
  - fs/ext4/super.c:__bpf_trace_ext4_fsmap_class
  - fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space_done
  - fs/ext4/super.c:__bpf_trace_ext4_find_delalloc_range
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_extend
  - block/blk-iocost.c:__bpf_trace_iocost_iocg_activate
  - drivers/net/phy/mdio_bus.c:__bpf_trace_mdio_access
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_read
  - drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_get_power
  - drivers/ras/ras.c:__bpf_trace_non_standard_event
```
**Symbols:**

```
ffffffff811c3080-ffffffff811c312a: bpf_trace_run6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bpf_trace_run6(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811d2480)
Location: kernel/trace/bpf_trace.c:1376
Inline: False
Direct callers:
  - kernel/bpf/core.c:__bpf_trace_xdp_redirect_template
  - mm/oom_kill.c:__bpf_trace_compact_retry
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:__bpf_trace_mm_shrink_slab_end
  - mm/slab_common.c:__bpf_trace_kmem_alloc_node
  - mm/compaction.c:__bpf_trace_mm_compaction_end
  - fs/ext4/super.c:__bpf_trace_ext4_fsmap_class
  - fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space_done
  - fs/ext4/super.c:__bpf_trace_ext4_find_delalloc_range
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_extend
  - block/blk-iocost.c:__bpf_trace_iocost_iocg_activate
  - drivers/net/phy/mdio_bus.c:__bpf_trace_mdio_access
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_read
  - drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_get_power
  - drivers/ras/ras.c:__bpf_trace_non_standard_event
```
**Symbols:**

```
ffffffff811d2480-ffffffff811d254b: bpf_trace_run6 (STB_GLOBAL)
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
