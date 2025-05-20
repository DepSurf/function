# Function: <code>div64_u64_rem</code>

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
In kernel/time/timekeeping.c (ffffffff810f423c)
Location: include/linux/math64.h:36
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:scale64_check_overflow
```
```
In kernel/bpf/core.c (ffffffff81171c56)
Location: include/linux/math64.h:36
Inline: True
Inline callers:
  - kernel/bpf/core.c:__bpf_prog_run
  - kernel/bpf/core.c:__bpf_prog_run
```
```
In drivers/md/dm-stats.c (ffffffff816ad3af)
Location: include/linux/math64.h:36
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-stats.c:dm_stats_message
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
In kernel/time/timekeeping.c (ffffffff810fb3bc)
Location: include/linux/math64.h:36
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:scale64_check_overflow
```
```
In kernel/bpf/core.c (ffffffff8117fa5d)
Location: include/linux/math64.h:36
Inline: True
Inline callers:
  - kernel/bpf/core.c:__bpf_prog_run
  - kernel/bpf/core.c:__bpf_prog_run
```
```
In drivers/md/dm-stats.c (ffffffff8170dfa7)
Location: include/linux/math64.h:36
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_account_io
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
In kernel/time/timekeeping.c (ffffffff810fe17c)
Location: include/linux/math64.h:36
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:scale64_check_overflow
```
```
In kernel/bpf/core.c (ffffffff8118b8cd)
Location: include/linux/math64.h:36
Inline: True
Inline callers:
  - kernel/bpf/core.c:__bpf_prog_run
  - kernel/bpf/core.c:__bpf_prog_run
```
```
In drivers/md/dm-stats.c (ffffffff8173fe12)
Location: include/linux/math64.h:36
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
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
In kernel/time/timekeeping.c (0)
Location: include/linux/math64.h:36
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811906fe)
Location: include/linux/math64.h:36
Inline: True
Inline callers:
  - kernel/bpf/core.c:___bpf_prog_run
  - kernel/bpf/core.c:___bpf_prog_run
```
```
In drivers/md/dm-stats.c (ffffffff81759ba5)
Location: include/linux/math64.h:36
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
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
In kernel/time/timekeeping.c (0)
Location: include/linux/math64.h:52
Inline: True
```
```
In drivers/md/dm-stats.c (ffffffff817cbde5)
Location: include/linux/math64.h:52
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
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
In kernel/time/timekeeping.c (ffffffff81117245)
Location: include/linux/math64.h:52
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:scale64_check_overflow
```
```
In drivers/md/dm-stats.c (ffffffff81814bc1)
Location: include/linux/math64.h:52
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
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
In kernel/time/timekeeping.c (ffffffff81122885)
Location: include/linux/math64.h:52
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:scale64_check_overflow
```
```
In drivers/md/dm-stats.c (ffffffff81840c1f)
Location: include/linux/math64.h:52
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
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
In kernel/time/timekeeping.c (ffffffff8112ce05)
Location: include/linux/math64.h:52
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:scale64_check_overflow
```
```
In drivers/md/dm-stats.c (ffffffff81883e4b)
Location: include/linux/math64.h:52
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In net/core/devlink.c (ffffffff8194786e)
Location: include/linux/math64.h:52
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_set
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
In kernel/time/timekeeping.c (ffffffff81138dd5)
Location: include/linux/math64.h:52
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:scale64_check_overflow
```
```
In drivers/md/dm-stats.c (ffffffff818b5d6b)
Location: include/linux/math64.h:52
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In net/core/devlink.c (ffffffff8197c95e)
Location: include/linux/math64.h:52
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_set
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
In kernel/time/timekeeping.c (ffffffff81147d35)
Location: include/linux/math64.h:53
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:scale64_check_overflow
```
```
In drivers/md/dm-stats.c (ffffffff81986a3c)
Location: include/linux/math64.h:53
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In net/core/devlink.c (ffffffff81a55763)
Location: include/linux/math64.h:53
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_set
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
In kernel/time/timekeeping.c (ffffffff81144165)
Location: include/linux/math64.h:53
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:scale64_check_overflow
```
```
In drivers/md/dm-stats.c (ffffffff8198aa7c)
Location: include/linux/math64.h:53
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In net/core/devlink.c (ffffffff81a5cb03)
Location: include/linux/math64.h:53
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_set
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
In kernel/time/timekeeping.c (ffffffff811452f5)
Location: include/linux/math64.h:53
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:scale64_check_overflow
```
```
In kernel/bpf/btf.c (ffffffff8122a024)
Location: include/linux/math64.h:53
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_float_check_member
```
```
In drivers/md/dm-stats.c (ffffffff8196f033)
Location: include/linux/math64.h:53
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In net/core/devlink.c (ffffffff81a40a86)
Location: include/linux/math64.h:53
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_set
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
In kernel/time/timekeeping.c (ffffffff81168b55)
Location: include/linux/math64.h:54
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:scale64_check_overflow
```
```
In kernel/time/timeconv.c (ffffffff8116ed79)
Location: include/linux/math64.h:54
Inline: True
Inline callers:
  - kernel/time/timeconv.c:time64_to_tm
```
```
In kernel/bpf/btf.c (ffffffff812627a4)
Location: include/linux/math64.h:54
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_float_check_member
```
```
In drivers/md/dm-stats.c (ffffffff81a17953)
Location: include/linux/math64.h:54
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In net/core/devlink.c (ffffffff81af7996)
Location: include/linux/math64.h:54
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_set
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
In kernel/time/timekeeping.c (ffffffff8119c6b5)
Location: include/linux/math64.h:54
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:scale64_check_overflow
```
```
In kernel/time/timeconv.c (ffffffff811a30a0)
Location: include/linux/math64.h:54
Inline: True
Inline callers:
  - kernel/time/timeconv.c:time64_to_tm
```
```
In kernel/bpf/btf.c (ffffffff812ae197)
Location: include/linux/math64.h:54
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_float_check_member
```
```
In drivers/md/dm-stats.c (ffffffff81b8075a)
Location: include/linux/math64.h:54
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In net/core/devlink.c (ffffffff81c7b2f7)
Location: include/linux/math64.h:54
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_set
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
In kernel/time/timekeeping.c (ffffffff811db0a5)
Location: include/linux/math64.h:54
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:scale64_check_overflow
```
```
In kernel/time/timeconv.c (ffffffff811e2660)
Location: include/linux/math64.h:54
Inline: True
Inline callers:
  - kernel/time/timeconv.c:time64_to_tm
```
```
In kernel/bpf/btf.c (ffffffff8130e457)
Location: include/linux/math64.h:54
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_float_check_member
```
```
In drivers/md/dm-stats.c (ffffffff81d1ea0b)
Location: include/linux/math64.h:54
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In net/core/devlink.c (ffffffff81e33e47)
Location: include/linux/math64.h:54
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_set
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
In kernel/time/timekeeping.c (ffffffff811ef605)
Location: include/linux/math64.h:54
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:scale64_check_overflow
```
```
In kernel/time/timeconv.c (ffffffff811f6bf5)
Location: include/linux/math64.h:54
Inline: True
Inline callers:
  - kernel/time/timeconv.c:time64_to_tm
```
```
In kernel/bpf/btf.c (ffffffff8133da87)
Location: include/linux/math64.h:54
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_float_check_member
```
```
In drivers/md/dm-stats.c (ffffffff81d87bf2)
Location: include/linux/math64.h:54
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In net/devlink/leftover.c (ffffffff820357d7)
Location: include/linux/math64.h:54
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_cmd_resource_set
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
In kernel/time/timekeeping.c (ffffffff81205a85)
Location: include/linux/math64.h:54
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:scale64_check_overflow
```
```
In kernel/time/timeconv.c (ffffffff8120cd95)
Location: include/linux/math64.h:54
Inline: True
Inline callers:
  - kernel/time/timeconv.c:time64_to_tm
```
```
In kernel/bpf/btf.c (ffffffff81363cf7)
Location: include/linux/math64.h:54
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_float_check_member
```
```
In drivers/gpu/drm/drm_mm.c (ffffffff81ca0e27)
Location: include/linux/math64.h:54
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mm.c:drm_mm_scan_add_block
  - drivers/gpu/drm/drm_mm.c:drm_mm_insert_node_in_range
```
```
In drivers/md/dm-stats.c (ffffffff81e3f302)
Location: include/linux/math64.h:54
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In net/devlink/resource.c (ffffffff8210d587)
Location: include/linux/math64.h:54
Inline: True
Inline callers:
  - net/devlink/resource.c:devlink_nl_resource_set_doit
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
In kernel/time/timekeeping.c (ffff8000101a31c8)
Location: include/linux/math64.h:52
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:scale64_check_overflow
```
```
In drivers/md/dm-stats.c (ffff800010b0dcac)
Location: include/linux/math64.h:52
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In net/core/devlink.c (ffff800010c24540)
Location: include/linux/math64.h:52
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_set
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
u64 div64_u64_rem(u64 dividend, u64 divisor, u64 *remainder);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/math/div64.c (c07e0aac)
Location: lib/math/div64.c:102
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:scale64_check_overflow
  - drivers/md/dm-stats.c:dm_stats_account_io
  - net/core/devlink.c:devlink_nl_cmd_resource_set
  - net/core/devlink.c:devlink_nl_cmd_resource_set
  - net/core/devlink.c:devlink_nl_cmd_resource_set
```
**Symbols:**

```
c07e0aac-c07e0bd4: div64_u64_rem (STB_GLOBAL)
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
In kernel/time/timekeeping.c (c0000000002052c4)
Location: include/linux/math64.h:52
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:get_device_system_crosststamp
```
```
In drivers/md/dm-stats.c (c000000000c00864)
Location: include/linux/math64.h:52
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In net/core/devlink.c (c000000000d17d3c)
Location: include/linux/math64.h:52
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_set
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
In kernel/time/timekeeping.c (ffffffe00012f710)
Location: include/linux/math64.h:52
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:scale64_check_overflow
```
```
In drivers/md/dm-stats.c (ffffffe0006fadb8)
Location: include/linux/math64.h:52
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In net/core/devlink.c (ffffffe00079ca80)
Location: include/linux/math64.h:52
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_set
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
In kernel/time/timekeeping.c (ffffffff81131585)
Location: include/linux/math64.h:52
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:scale64_check_overflow
```
```
In drivers/md/dm-stats.c (ffffffff8185bbeb)
Location: include/linux/math64.h:52
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In net/core/devlink.c (ffffffff8191c7ce)
Location: include/linux/math64.h:52
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_set
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
In kernel/time/timekeeping.c (ffffffff81123fe5)
Location: include/linux/math64.h:52
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:scale64_check_overflow
```
```
In drivers/md/dm-stats.c (ffffffff818231bb)
Location: include/linux/math64.h:52
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In net/core/devlink.c (ffffffff818d657e)
Location: include/linux/math64.h:52
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_set
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
In kernel/time/timekeeping.c (ffffffff8112f2a5)
Location: include/linux/math64.h:52
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:scale64_check_overflow
```
```
In drivers/md/dm-stats.c (ffffffff818ab21b)
Location: include/linux/math64.h:52
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In net/core/devlink.c (ffffffff8196d95e)
Location: include/linux/math64.h:52
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_set
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
In kernel/time/timekeeping.c (ffffffff8113bcc5)
Location: include/linux/math64.h:52
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:scale64_check_overflow
```
```
In drivers/md/dm-stats.c (ffffffff818c7446)
Location: include/linux/math64.h:52
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In net/core/devlink.c (ffffffff8198fdae)
Location: include/linux/math64.h:52
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_set
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
