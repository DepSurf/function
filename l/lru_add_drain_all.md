# Function: <code>lru_add_drain_all</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void lru_add_drain_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8119e220)
Location: mm/swap.c:870
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/shmem.c:shmem_add_seals
  - mm/compaction.c:sysfs_compact_node
  - mm/compaction.c:sysctl_compaction_handler
  - mm/mlock.c:do_mlock
  - mm/mlock.c:SyS_mlockall
  - mm/ksm.c:ksm_scan_thread
  - mm/migrate.c:SyS_move_pages
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_move_task
  - fs/block_dev.c:invalidate_bdev
```
**Symbols:**

```
ffffffff8119e220-ffffffff8119e38b: lru_add_drain_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void lru_add_drain_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811b3bd0)
Location: mm/swap.c:689
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/shmem.c:shmem_add_seals
  - mm/compaction.c:sysfs_compact_node
  - mm/compaction.c:sysctl_compaction_handler
  - mm/mlock.c:SyS_mlockall
  - mm/mlock.c:do_mlock
  - mm/fadvise.c:SyS_fadvise64
  - mm/ksm.c:ksm_scan_thread
  - mm/migrate.c:SyS_move_pages
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memory-failure.c:shake_page
  - fs/block_dev.c:invalidate_bdev
```
**Symbols:**

```
ffffffff811b3bd0-ffffffff811b3d46: lru_add_drain_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void lru_add_drain_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811c4260)
Location: mm/swap.c:690
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/shmem.c:shmem_add_seals
  - mm/compaction.c:sysfs_compact_node
  - mm/compaction.c:sysctl_compaction_handler
  - mm/mlock.c:SyS_mlockall
  - mm/mlock.c:do_mlock
  - mm/fadvise.c:SyS_fadvise64
  - mm/ksm.c:ksm_scan_thread
  - mm/migrate.c:SYSC_move_pages
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memory-failure.c:shake_page
  - fs/block_dev.c:invalidate_bdev
```
**Symbols:**

```
ffffffff811c4260-ffffffff811c43e0: lru_add_drain_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void lru_add_drain_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811cc800)
Location: mm/swap.c:727
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/shmem.c:shmem_add_seals
  - mm/compaction.c:sysfs_compact_node
  - mm/compaction.c:sysctl_compaction_handler
  - mm/mlock.c:SyS_mlockall
  - mm/mlock.c:do_mlock
  - mm/fadvise.c:SyS_fadvise64
  - mm/ksm.c:ksm_scan_thread
  - mm/migrate.c:SYSC_move_pages
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - fs/block_dev.c:invalidate_bdev
```
**Symbols:**

```
ffffffff811cc800-ffffffff811cc81a: lru_add_drain_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void lru_add_drain_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811e1820)
Location: mm/swap.c:727
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/shmem.c:shmem_add_seals
  - mm/compaction.c:sysfs_compact_node
  - mm/compaction.c:sysctl_compaction_handler
  - mm/fadvise.c:SyS_fadvise64
  - mm/ksm.c:ksm_scan_thread
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:SYSC_move_pages
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - fs/block_dev.c:invalidate_bdev
```
**Symbols:**

```
ffffffff811e1820-ffffffff811e183a: lru_add_drain_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void lru_add_drain_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap.c (0)
Location: mm/swap.c:671
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/compaction.c:sysfs_compact_node
  - mm/compaction.c:sysctl_compaction_handler
  - mm/fadvise.c:ksys_fadvise64_64
  - mm/ksm.c:ksm_scan_thread
  - mm/memory_hotplug.c:__offline_pages
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:kernel_move_pages
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memfd.c:memfd_fcntl
  - fs/block_dev.c:invalidate_bdev
```
**Symbols:**

```
ffffffff8120323a-ffffffff81203246: lru_add_drain_all.cold.28 (STB_LOCAL)
ffffffff81202db0-ffffffff81202f2c: lru_add_drain_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void lru_add_drain_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap.c (0)
Location: mm/swap.c:667
Inline: False
Direct callers:
  - mm/fadvise.c:vfs_fadvise
  - mm/page_alloc.c:alloc_contig_range
  - mm/compaction.c:sysfs_compact_node
  - mm/compaction.c:sysctl_compaction_handler
  - mm/ksm.c:ksm_scan_thread
  - mm/memory_hotplug.c:__offline_pages
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:kernel_move_pages
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memfd.c:memfd_fcntl
  - fs/block_dev.c:invalidate_bdev
```
**Symbols:**

```
ffffffff81215bda-ffffffff81215be6: lru_add_drain_all.cold.30 (STB_LOCAL)
ffffffff81215750-ffffffff812158cc: lru_add_drain_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void lru_add_drain_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap.c (0)
Location: mm/swap.c:668
Inline: False
Direct callers:
  - mm/fadvise.c:vfs_fadvise
  - mm/compaction.c:sysfs_compact_node
  - mm/compaction.c:sysctl_compaction_handler
  - mm/gup.c:__gup_longterm_locked
  - mm/page_alloc.c:alloc_contig_range
  - mm/ksm.c:ksm_scan_thread
  - mm/memory_hotplug.c:__offline_pages
  - mm/migrate.c:do_pages_move
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memfd.c:memfd_wait_for_pins
  - fs/block_dev.c:invalidate_bdev
```
**Symbols:**

```
ffffffff812255dd-ffffffff812255fc: lru_add_drain_all.cold (STB_LOCAL)
ffffffff81225150-ffffffff812252b7: lru_add_drain_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void lru_add_drain_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap.c (0)
Location: mm/swap.c:709
Inline: False
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/compaction.c:sysfs_compact_node
  - mm/compaction.c:sysctl_compaction_handler
  - mm/gup.c:__gup_longterm_locked
  - mm/page_alloc.c:alloc_contig_range
  - mm/ksm.c:ksm_scan_thread
  - mm/memory_hotplug.c:__offline_pages
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:do_pages_move
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memfd.c:memfd_wait_for_pins
  - fs/block_dev.c:invalidate_bdev
```
**Symbols:**

```
ffffffff8123343a-ffffffff81233446: lru_add_drain_all.cold (STB_LOCAL)
ffffffff81232fd0-ffffffff8123314f: lru_add_drain_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void lru_add_drain_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap.c (0)
Location: mm/swap.c:762
Inline: False
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/compaction.c:sysfs_compact_node
  - mm/compaction.c:sysctl_compaction_handler
  - mm/page_alloc.c:alloc_contig_range
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/memory_hotplug.c:__offline_pages
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:do_pages_move
  - mm/khugepaged.c:khugepaged_do_scan
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memfd.c:memfd_wait_for_pins
  - fs/block_dev.c:invalidate_bdev
```
**Symbols:**

```
ffffffff81260a2a-ffffffff81260a36: lru_add_drain_all.cold (STB_LOCAL)
ffffffff812605f0-ffffffff81260789: lru_add_drain_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void lru_add_drain_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap.c (0)
Location: mm/swap.c:748
Inline: False
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/compaction.c:sysfs_compact_node
  - mm/compaction.c:sysctl_compaction_handler
  - mm/page_alloc.c:alloc_contig_range
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/memory_hotplug.c:offline_pages
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:do_pages_move
  - mm/khugepaged.c:khugepaged_do_scan
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memfd.c:memfd_wait_for_pins
  - fs/block_dev.c:invalidate_bdev
```
**Symbols:**

```
ffffffff81be6e60-ffffffff81be6e6c: lru_add_drain_all.cold (STB_LOCAL)
ffffffff8126a690-ffffffff8126a843: lru_add_drain_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void lru_add_drain_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8126f9d0)
Location: mm/swap.c:848
Inline: False
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/compaction.c:sysfs_compact_node
  - mm/compaction.c:sysctl_compaction_handler
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/migrate.c:migrate_vma_prepare
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memfd.c:memfd_wait_for_pins
  - fs/block_dev.c:invalidate_bdev
```
**Symbols:**

```
ffffffff8126f9d0-ffffffff8126f9e2: lru_add_drain_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void lru_add_drain_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812accb0)
Location: mm/swap.c:839
Inline: False
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/compaction.c:compact_store
  - mm/compaction.c:sysctl_compaction_handler
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/migrate.c:migrate_vma_prepare
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memfd.c:memfd_wait_for_pins
  - block/bdev.c:invalidate_bdev
```
**Symbols:**

```
ffffffff812accb0-ffffffff812accc2: lru_add_drain_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void lru_add_drain_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81306da0)
Location: mm/swap.c:847
Inline: False
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/compaction.c:compact_store
  - mm/compaction.c:sysctl_compaction_handler
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/migrate_device.c:migrate_vma_unmap
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:memory_reclaim
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memfd.c:memfd_wait_for_pins
  - block/bdev.c:__invalidate_device
```
**Symbols:**

```
ffffffff81306da0-ffffffff81306db8: lru_add_drain_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void lru_add_drain_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81371180)
Location: mm/swap.c:937
Inline: False
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/compaction.c:compact_store
  - mm/compaction.c:sysctl_compaction_handler
  - mm/gup.c:collect_longterm_unpinnable_pages
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/migrate_device.c:migrate_device_unmap
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:memory_reclaim
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memfd.c:memfd_wait_for_pins
  - block/bdev.c:__invalidate_device
```
**Symbols:**

```
ffffffff81371180-ffffffff81371198: lru_add_drain_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void lru_add_drain_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff813a3310)
Location: mm/swap.c:903
Inline: False
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/compaction.c:compact_store
  - mm/gup.c:collect_longterm_unpinnable_pages
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/migrate_device.c:migrate_device_unmap
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:memory_reclaim
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memfd.c:memfd_wait_for_pins
  - block/bdev.c:__invalidate_device
```
**Symbols:**

```
ffffffff813a3310-ffffffff813a3328: lru_add_drain_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void lru_add_drain_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff813ccf80)
Location: mm/swap.c:903
Inline: False
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/compaction.c:compact_store
  - mm/gup.c:collect_longterm_unpinnable_pages
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/migrate_device.c:migrate_device_unmap
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:memory_reclaim
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_any_page
  - mm/memfd.c:memfd_wait_for_pins
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - block/bdev.c:bdev_mark_dead
```
**Symbols:**

```
ffffffff813ccf80-ffffffff813ccf98: lru_add_drain_all (STB_GLOBAL)
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
void lru_add_drain_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffff8000102c3120)
Location: mm/swap.c:709
Inline: False
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/compaction.c:sysfs_compact_node
  - mm/compaction.c:sysctl_compaction_handler
  - mm/gup.c:__gup_longterm_locked
  - mm/page_alloc.c:alloc_contig_range
  - mm/ksm.c:ksm_scan_thread
  - mm/migrate.c:do_pages_move
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memfd.c:memfd_wait_for_pins
  - fs/block_dev.c:invalidate_bdev
```
**Symbols:**

```
ffff8000102c3120-ffff8000102c32f0: lru_add_drain_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void lru_add_drain_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (c04ee1d0)
Location: mm/swap.c:709
Inline: False
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/compaction.c:sysctl_compaction_handler
  - mm/gup.c:__gup_longterm_locked
  - mm/page_alloc.c:alloc_contig_range
  - mm/ksm.c:ksm_do_scan
  - mm/migrate.c:migrate_prep
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memfd.c:memfd_wait_for_pins
  - fs/block_dev.c:invalidate_bdev
```
**Symbols:**

```
c04ee1d0-c04ee398: lru_add_drain_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void lru_add_drain_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (c00000000037d400)
Location: mm/swap.c:709
Inline: False
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/compaction.c:sysfs_compact_node
  - mm/compaction.c:sysctl_compaction_handler
  - mm/gup.c:__gup_longterm_locked
  - mm/page_alloc.c:alloc_contig_range
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/memory_hotplug.c:__offline_pages
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:do_pages_move
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memfd.c:memfd_wait_for_pins
  - fs/block_dev.c:invalidate_bdev
```
**Symbols:**

```
c00000000037d400-c00000000037d6a0: lru_add_drain_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void lru_add_drain_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffe0001e435e)
Location: mm/swap.c:709
Inline: False
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/compaction.c:sysctl_compaction_handler
  - mm/gup.c:__gup_longterm_locked
  - mm/page_alloc.c:alloc_contig_range
  - mm/ksm.c:ksm_do_scan
  - mm/migrate.c:migrate_prep
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memfd.c:memfd_wait_for_pins
  - fs/block_dev.c:invalidate_bdev
```
**Symbols:**

```
ffffffe0001e435e-ffffffe0001e4526: lru_add_drain_all (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void lru_add_drain_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap.c (0)
Location: mm/swap.c:709
Inline: False
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/compaction.c:sysfs_compact_node
  - mm/compaction.c:sysctl_compaction_handler
  - mm/gup.c:__gup_longterm_locked
  - mm/page_alloc.c:alloc_contig_range
  - mm/ksm.c:ksm_scan_thread
  - mm/memory_hotplug.c:__offline_pages
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:do_pages_move
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memfd.c:memfd_wait_for_pins
  - fs/block_dev.c:invalidate_bdev
```
**Symbols:**

```
ffffffff8122ba8a-ffffffff8122ba96: lru_add_drain_all.cold (STB_LOCAL)
ffffffff8122b620-ffffffff8122b79f: lru_add_drain_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void lru_add_drain_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap.c (0)
Location: mm/swap.c:709
Inline: False
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/compaction.c:sysfs_compact_node
  - mm/compaction.c:sysctl_compaction_handler
  - mm/gup.c:__gup_longterm_locked
  - mm/page_alloc.c:alloc_contig_range
  - mm/ksm.c:ksm_scan_thread
  - mm/memory_hotplug.c:__offline_pages
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:do_pages_move
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memfd.c:memfd_wait_for_pins
  - fs/block_dev.c:invalidate_bdev
```
**Symbols:**

```
ffffffff8121eb7a-ffffffff8121eb86: lru_add_drain_all.cold (STB_LOCAL)
ffffffff8121e710-ffffffff8121e88f: lru_add_drain_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void lru_add_drain_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap.c (0)
Location: mm/swap.c:709
Inline: False
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/compaction.c:sysfs_compact_node
  - mm/compaction.c:sysctl_compaction_handler
  - mm/gup.c:__gup_longterm_locked
  - mm/page_alloc.c:alloc_contig_range
  - mm/ksm.c:ksm_scan_thread
  - mm/memory_hotplug.c:__offline_pages
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:do_pages_move
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memfd.c:memfd_wait_for_pins
  - fs/block_dev.c:invalidate_bdev
```
**Symbols:**

```
ffffffff8122982a-ffffffff81229836: lru_add_drain_all.cold (STB_LOCAL)
ffffffff812293c0-ffffffff8122953f: lru_add_drain_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void lru_add_drain_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap.c (0)
Location: mm/swap.c:709
Inline: False
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/compaction.c:sysfs_compact_node
  - mm/compaction.c:sysctl_compaction_handler
  - mm/gup.c:__gup_longterm_locked
  - mm/page_alloc.c:alloc_contig_range
  - mm/ksm.c:ksm_scan_thread
  - mm/memory_hotplug.c:__offline_pages
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:do_pages_move
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memfd.c:memfd_wait_for_pins
  - fs/block_dev.c:invalidate_bdev
```
**Symbols:**

```
ffffffff81238c3a-ffffffff81238c46: lru_add_drain_all.cold (STB_LOCAL)
ffffffff812387d0-ffffffff8123894f: lru_add_drain_all (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
