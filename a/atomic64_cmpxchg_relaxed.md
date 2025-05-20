# Function: <code>atomic64_cmpxchg_relaxed</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8115b3ea)
Location: include/asm-generic/atomic-instrumented.h:1492
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
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
In kernel/printk/printk_ringbuffer.c (ffffffff8111cc13)
Location: include/asm-generic/atomic-instrumented.h:1492
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_commit
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:desc_push_tail
  - kernel/printk/printk_ringbuffer.c:data_make_reusable
```
```
In kernel/futex.c (ffffffff8115752e)
Location: include/asm-generic/atomic-instrumented.h:1492
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
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
In kernel/printk/printk_ringbuffer.c (ffffffff8111cd8c)
Location: include/asm-generic/atomic-instrumented.h:1492
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_commit
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:prb_reserve
```
```
In kernel/futex.c (ffffffff8115894c)
Location: include/asm-generic/atomic-instrumented.h:1492
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8117d850)
Location: include/linux/atomic/atomic-instrumented.h:1072
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff811b2b71)
Location: include/linux/atomic/atomic-instrumented.h:1142
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff811f3a11)
Location: include/linux/atomic/atomic-instrumented.h:1142
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff81208195)
Location: include/linux/atomic/atomic-instrumented.h:2814
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff8121f049)
Location: include/linux/atomic/atomic-instrumented.h:2814
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
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
In arch/arm64/mm/context.c (ffff8000100afc24)
Location: include/asm-generic/atomic-instrumented.h:1491
Inline: True
Inline callers:
  - arch/arm64/mm/context.c:check_and_switch_context
```
```
In kernel/futex.c (ffff8000101b7d7c)
Location: include/asm-generic/atomic-instrumented.h:1491
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
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
In arch/arm/mach-imx/mmdc.c (c033356c)
Location: arch/arm/include/asm/atomic.h:406
Inline: True
Inline callers:
  - arch/arm/mach-imx/mmdc.c:mmdc_pmu_event_update
```
```
In kernel/time/posix-cpu-timers.c (c03f8848)
Location: arch/arm/include/asm/atomic.h:406
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
```
```
In kernel/futex.c (c0401b24)
Location: arch/arm/include/asm/atomic.h:406
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/core.c (c04d0710)
Location: arch/arm/include/asm/atomic.h:406
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_set_period
```
```
In fs/inode.c (c058db64)
Location: arch/arm/include/asm/atomic.h:406
Inline: True
Inline callers:
  - fs/inode.c:generic_update_time
```
```
In fs/ext4/dir.c (c0623400)
Location: arch/arm/include/asm/atomic.h:406
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (c063d410)
Location: arch/arm/include/asm/atomic.h:406
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (c0645870)
Location: arch/arm/include/asm/atomic.h:406
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (c06627f4)
Location: arch/arm/include/asm/atomic.h:406
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (c06a2fa0)
Location: arch/arm/include/asm/atomic.h:406
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (c06ab4d4)
Location: arch/arm/include/asm/atomic.h:406
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (c06ac9b8)
Location: arch/arm/include/asm/atomic.h:406
Inline: True
```
```
In fs/fat/namei_vfat.c (c06af4a8)
Location: arch/arm/include/asm/atomic.h:406
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/dir.c (c06c4a34)
Location: arch/arm/include/asm/atomic.h:406
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_create_open
```
```
In fs/fuse/readdir.c (c06d0204)
Location: arch/arm/include/asm/atomic.h:406
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In security/integrity/ima/ima_api.c (c07600d4)
Location: arch/arm/include/asm/atomic.h:406
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/blk-cgroup.c (c07b6184)
Location: arch/arm/include/asm/atomic.h:406
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In drivers/perf/arm-cci.c (c0c7aedc)
Location: arch/arm/include/asm/atomic.h:406
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:pmu_event_update
```
```
In drivers/perf/arm_pmu.c (c0c7e634)
Location: arch/arm/include/asm/atomic.h:406
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:armpmu_event_update
```
```
In net/core/sock_diag.c (c0d1cfe0)
Location: arch/arm/include/asm/atomic.h:406
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
</details>
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
