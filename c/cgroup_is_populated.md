# Function: <code>cgroup_is_populated</code>

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
In kernel/cgroup.c (0)
Location: include/linux/cgroup.h:480
Inline: True
```
```
In kernel/cpuset.c (0)
Location: include/linux/cgroup.h:480
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/cgroup.h:480
Inline: True
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
In kernel/cgroup.c (ffffffff81119c9a)
Location: include/linux/cgroup.h:501
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_events_show
```
```
In kernel/cpuset.c (ffffffff81123861)
Location: include/linux/cgroup.h:501
Inline: True
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
In kernel/cgroup.c (ffffffff81121777)
Location: include/linux/cgroup.h:518
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_events_show
```
```
In kernel/cpuset.c (ffffffff8112bf47)
Location: include/linux/cgroup.h:518
Inline: True
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
In kernel/cgroup/cgroup.c (ffffffff81121d97)
Location: include/linux/cgroup.h:538
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_events_show
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/cgroup.h:538
Inline: True
```
```
In kernel/cgroup/cpuset.c (ffffffff8112d3e1)
Location: include/linux/cgroup.h:538
Inline: True
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
In kernel/cgroup/cgroup.c (ffffffff81133e42)
Location: include/linux/cgroup.h:574
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_events_show
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81137420)
Location: include/linux/cgroup.h:574
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/cpuset.c (ffffffff8113a2c5)
Location: include/linux/cgroup.h:574
Inline: True
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
In kernel/cgroup/cgroup.c (ffffffff81142550)
Location: include/linux/cgroup.h:574
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_events_show
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81145cd0)
Location: include/linux/cgroup.h:574
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/cpuset.c (ffffffff81149127)
Location: include/linux/cgroup.h:574
Inline: True
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
In kernel/cgroup/cgroup.c (ffffffff8114dfd0)
Location: include/linux/cgroup.h:597
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_events_show
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81151890)
Location: include/linux/cgroup.h:597
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/cpuset.c (ffffffff81154e07)
Location: include/linux/cgroup.h:597
Inline: True
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
In kernel/cgroup/cgroup.c (ffffffff81159d70)
Location: include/linux/cgroup.h:610
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_events_show
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115d250)
Location: include/linux/cgroup.h:610
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/cpuset.c (ffffffff81161715)
Location: include/linux/cgroup.h:610
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:validate_change
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
In kernel/cgroup/cgroup.c (ffffffff81165a00)
Location: include/linux/cgroup.h:612
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_events_show
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81168e50)
Location: include/linux/cgroup.h:612
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/cpuset.c (ffffffff8116d3f5)
Location: include/linux/cgroup.h:612
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:validate_change
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
In kernel/cgroup/cgroup.c (ffffffff81176b40)
Location: include/linux/cgroup.h:618
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_events_show
  - kernel/cgroup/cgroup.c:cgroup_enable_threaded
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8117ac00)
Location: include/linux/cgroup.h:618
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/cpuset.c (ffffffff811802d3)
Location: include/linux/cgroup.h:618
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:validate_change
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
In kernel/cgroup/cgroup.c (ffffffff81173840)
Location: include/linux/cgroup.h:618
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_events_show
  - kernel/cgroup/cgroup.c:cgroup_enable_threaded
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81177a00)
Location: include/linux/cgroup.h:618
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/cpuset.c (ffffffff8117ca04)
Location: include/linux/cgroup.h:618
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:validate_change
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
In kernel/cgroup/cgroup.c (ffffffff81174410)
Location: include/linux/cgroup.h:618
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_events_show
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81178560)
Location: include/linux/cgroup.h:618
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/cpuset.c (ffffffff8117c6d4)
Location: include/linux/cgroup.h:618
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:validate_change
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
In kernel/cgroup/cgroup.c (ffffffff8119b4a0)
Location: include/linux/cgroup.h:618
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_events_show
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8119fec0)
Location: include/linux/cgroup.h:618
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/cpuset.c (ffffffff811a4264)
Location: include/linux/cgroup.h:618
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:validate_change
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
In kernel/cgroup/cgroup.c (ffffffff811cb6b0)
Location: include/linux/cgroup.h:619
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_events_show
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811d0580)
Location: include/linux/cgroup.h:619
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/cpuset.c (ffffffff811d6018)
Location: include/linux/cgroup.h:619
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:validate_change
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
In kernel/cgroup/cgroup.c (ffffffff8120eb30)
Location: include/linux/cgroup.h:559
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_events_show
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81214030)
Location: include/linux/cgroup.h:559
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/cpuset.c (ffffffff8121d9ad)
Location: include/linux/cgroup.h:559
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:validate_change
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
In kernel/cgroup/cgroup.c (ffffffff81224540)
Location: include/linux/cgroup.h:558
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_events_show
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81229960)
Location: include/linux/cgroup.h:558
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/cpuset.c (ffffffff81233b31)
Location: include/linux/cgroup.h:558
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:validate_change
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
In kernel/cgroup/cgroup.c (ffffffff8123c230)
Location: include/linux/cgroup.h:556
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_events_show
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff812417b0)
Location: include/linux/cgroup.h:556
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/cpuset.c (ffffffff81246e04)
Location: include/linux/cgroup.h:556
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:compute_partition_effective_cpumask
  - kernel/cgroup/cpuset.c:compute_partition_effective_cpumask
  - kernel/cgroup/cpuset.c:tasks_nocpu_error
  - kernel/cgroup/cpuset.c:tasks_nocpu_error
  - kernel/cgroup/cpuset.c:tasks_nocpu_error
  - kernel/cgroup/cpuset.c:tasks_nocpu_error
  - kernel/cgroup/cpuset.c:validate_change
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
In kernel/cgroup/cgroup.c (ffff8000101d74a8)
Location: include/linux/cgroup.h:612
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_events_show
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (ffff8000101dbf60)
Location: include/linux/cgroup.h:612
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/cpuset.c (ffff8000101e0744)
Location: include/linux/cgroup.h:612
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:validate_change
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
In kernel/cgroup/cgroup.c (c041a21c)
Location: include/linux/cgroup.h:612
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_events_show
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (c041e298)
Location: include/linux/cgroup.h:612
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/cpuset.c (c04221ac)
Location: include/linux/cgroup.h:612
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:validate_change
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
In kernel/cgroup/cgroup.c (c000000000243cec)
Location: include/linux/cgroup.h:612
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_events_show
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (c000000000249684)
Location: include/linux/cgroup.h:612
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/cpuset.c (c00000000024f6f4)
Location: include/linux/cgroup.h:612
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:validate_change
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
In kernel/cgroup/cgroup.c (ffffffe0001505f2)
Location: include/linux/cgroup.h:612
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_events_show
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (ffffffe000154038)
Location: include/linux/cgroup.h:612
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/cpuset.c (ffffffe00015749a)
Location: include/linux/cgroup.h:612
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:validate_change
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
In kernel/cgroup/cgroup.c (ffffffff8115e020)
Location: include/linux/cgroup.h:612
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_events_show
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81161470)
Location: include/linux/cgroup.h:612
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/cpuset.c (ffffffff81165a15)
Location: include/linux/cgroup.h:612
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:validate_change
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
In kernel/cgroup/cgroup.c (ffffffff81151300)
Location: include/linux/cgroup.h:612
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_events_show
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811546d0)
Location: include/linux/cgroup.h:612
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/cpuset.c (ffffffff811590d5)
Location: include/linux/cgroup.h:612
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:validate_change
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
In kernel/cgroup/cgroup.c (ffffffff8115bdf0)
Location: include/linux/cgroup.h:612
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_events_show
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115f240)
Location: include/linux/cgroup.h:612
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/cpuset.c (ffffffff811637e5)
Location: include/linux/cgroup.h:612
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:validate_change
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
In kernel/cgroup/cgroup.c (ffffffff81168f20)
Location: include/linux/cgroup.h:612
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_events_show
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8116c4e0)
Location: include/linux/cgroup.h:612
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/cpuset.c (ffffffff81171126)
Location: include/linux/cgroup.h:612
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:validate_change
```
</details>
</li>
</ul>

## Differences
