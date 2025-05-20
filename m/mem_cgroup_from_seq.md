# Function: <code>mem_cgroup_from_seq</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff812426c2)
Location: include/linux/memcontrol.h:433
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
```
```
In mm/memcontrol.c (ffffffff812ad955)
Location: include/linux/memcontrol.h:433
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
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
In mm/slab_common.c (ffffffff81250be2)
Location: include/linux/memcontrol.h:467
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
```
```
In mm/memcontrol.c (ffffffff812bf4a5)
Location: include/linux/memcontrol.h:467
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
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
In mm/slab_common.c (ffffffff8127f252)
Location: include/linux/memcontrol.h:444
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
```
```
In mm/memcontrol.c (ffffffff812f47a5)
Location: include/linux/memcontrol.h:444
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_high_show
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81300085)
Location: include/linux/memcontrol.h:764
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_high_show
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81306ec5)
Location: include/linux/memcontrol.h:843
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_high_show
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
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
In mm/memcontrol.c (ffffffff81350b85)
Location: include/linux/memcontrol.h:839
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_high_show
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
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
In mm/memcontrol.c (ffffffff813c9a75)
Location: include/linux/memcontrol.h:840
Inline: True
Inline callers:
  - mm/memcontrol.c:zswap_max_show
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_high_show
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
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
In mm/memcontrol.c (ffffffff8144fe35)
Location: include/linux/memcontrol.h:831
Inline: True
Inline callers:
  - mm/memcontrol.c:zswap_max_show
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_high_show
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
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
In mm/memcontrol.c (ffffffff81485745)
Location: include/linux/memcontrol.h:849
Inline: True
Inline callers:
  - mm/memcontrol.c:zswap_max_show
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_high_show
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_numa_stat_show
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
In mm/memcontrol.c (ffffffff814b3e65)
Location: include/linux/memcontrol.h:869
Inline: True
Inline callers:
  - mm/memcontrol.c:zswap_writeback_show
  - mm/memcontrol.c:zswap_max_show
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_high_show
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_numa_stat_show
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
In mm/slab_common.c (ffff8000102e7e54)
Location: include/linux/memcontrol.h:467
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
```
```
In mm/memcontrol.c (ffff8000103612e0)
Location: include/linux/memcontrol.h:467
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
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
In mm/slab_common.c (c050bf0c)
Location: include/linux/memcontrol.h:467
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
```
```
In mm/memcontrol.c (c05538a4)
Location: include/linux/memcontrol.h:467
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
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
In mm/slab_common.c (c0000000003a9e38)
Location: include/linux/memcontrol.h:467
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
```
```
In mm/memcontrol.c (c00000000044c6c4)
Location: include/linux/memcontrol.h:467
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
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
In mm/slab_common.c (ffffffe0001fd912)
Location: include/linux/memcontrol.h:467
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
```
```
In mm/memcontrol.c (ffffffe000240a64)
Location: include/linux/memcontrol.h:467
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
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
In mm/slab_common.c (ffffffff81249232)
Location: include/linux/memcontrol.h:467
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
```
```
In mm/memcontrol.c (ffffffff812b7a85)
Location: include/linux/memcontrol.h:467
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
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
In mm/slab_common.c (ffffffff8123c1e2)
Location: include/linux/memcontrol.h:467
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
```
```
In mm/memcontrol.c (ffffffff812a8c55)
Location: include/linux/memcontrol.h:467
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
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
In mm/slab_common.c (ffffffff81246fd2)
Location: include/linux/memcontrol.h:467
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
```
```
In mm/memcontrol.c (ffffffff812b5895)
Location: include/linux/memcontrol.h:467
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
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
In mm/slab_common.c (ffffffff81256802)
Location: include/linux/memcontrol.h:467
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
```
```
In mm/memcontrol.c (ffffffff812c5db5)
Location: include/linux/memcontrol.h:467
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
```
</details>
</li>
</ul>

## Differences
