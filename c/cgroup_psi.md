# Function: <code>cgroup_psi</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810ef72d)
Location: include/linux/cgroup.h:653
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810f6bbc)
Location: include/linux/cgroup.h:666
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff8110294c)
Location: include/linux/cgroup.h:668
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff8110d96c)
Location: include/linux/cgroup.h:674
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_change
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
In kernel/sched/psi.c (ffffffff8110ac5c)
Location: include/linux/cgroup.h:674
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_change
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
In kernel/sched/psi.c (ffffffff8110c86a)
Location: include/linux/cgroup.h:674
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_change
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
In kernel/sched/psi.c (ffffffff8112b644)
Location: include/linux/cgroup.h:674
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
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
In kernel/sched/build_utility.c (ffffffff8114bd79)
Location: include/linux/cgroup.h:675
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_task_change
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
In kernel/sched/build_utility.c (ffffffff8117ad8e)
Location: include/linux/psi.h:34
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_cgroup_alloc
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_change
```
```
In kernel/cgroup/cgroup.c (ffffffff8120d732)
Location: include/linux/psi.h:34
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_show
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
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
In kernel/sched/build_utility.c (ffffffff8118b8fe)
Location: include/linux/psi.h:35
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_cgroup_alloc
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_change
```
```
In kernel/cgroup/cgroup.c (ffffffff81223122)
Location: include/linux/psi.h:35
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_show
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
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
In kernel/sched/build_utility.c (ffffffff8119a25d)
Location: include/linux/psi.h:35
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_cgroup_alloc
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_change
```
```
In kernel/cgroup/cgroup.c (ffffffff8123ae12)
Location: include/linux/psi.h:35
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_show
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffff8000101676a8)
Location: include/linux/cgroup.h:668
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (c03b455c)
Location: include/linux/cgroup.h:668
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (c0000000001bf414)
Location: include/linux/cgroup.h:668
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffe000109c38)
Location: include/linux/cgroup.h:668
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810fbc5c)
Location: include/linux/cgroup.h:668
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810ebe7c)
Location: include/linux/cgroup.h:668
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810f8e1c)
Location: include/linux/cgroup.h:668
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff81103f6c)
Location: include/linux/cgroup.h:668
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
```
</details>
</li>
</ul>

## Differences
