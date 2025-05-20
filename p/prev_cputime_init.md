# Function: <code>prev_cputime_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8107ea10)
Location: include/linux/sched.h:552
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810806ce)
Location: include/linux/sched.h:569
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81084fb1)
Location: include/linux/sched.h:596
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81081edd)
Location: include/linux/sched/cputime.h:176
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
In kernel/fork.c (ffffffff81088752)
Location: include/linux/sched/cputime.h:178
Inline: True
```
```
In kernel/cgroup/stat.c (ffffffff811357e0)
Location: include/linux/sched/cputime.h:178
Inline: True
Inline callers:
  - kernel/cgroup/stat.c:cgroup_stat_init
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
In kernel/fork.c (ffffffff8108c514)
Location: include/linux/sched/cputime.h:178
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8113c341)
Location: include/linux/sched/cputime.h:178
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_cgroup_housekeeping
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
In kernel/fork.c (ffffffff81093f43)
Location: include/linux/sched/cputime.h:178
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81147a01)
Location: include/linux/sched/cputime.h:178
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_cgroup_housekeeping
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
In kernel/fork.c (ffffffff810986c3)
Location: include/linux/sched/cputime.h:178
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/cgroup/cgroup.c (ffffffff81152c71)
Location: include/linux/sched/cputime.h:178
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_cgroup_housekeeping
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
In kernel/fork.c (ffffffff8109ecaf)
Location: include/linux/sched/cputime.h:180
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/cgroup/cgroup.c (ffffffff8115e8c1)
Location: include/linux/sched/cputime.h:180
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_cgroup_housekeeping
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
In kernel/fork.c (ffffffff810a62a7)
Location: include/linux/sched/cputime.h:180
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_signal
```
```
In kernel/cgroup/cgroup.c (ffffffff8116ebe1)
Location: include/linux/sched/cputime.h:180
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_cgroup_housekeeping
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
In kernel/fork.c (ffffffff810a1ba5)
Location: include/linux/sched/cputime.h:180
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_signal
```
```
In kernel/cgroup/cgroup.c (ffffffff8116b611)
Location: include/linux/sched/cputime.h:180
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_cgroup_housekeeping
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
In kernel/fork.c (ffffffff810a2a0e)
Location: include/linux/sched/cputime.h:180
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_signal
```
```
In kernel/cgroup/cgroup.c (ffffffff8116c191)
Location: include/linux/sched/cputime.h:180
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_cgroup_housekeeping
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
In kernel/fork.c (ffffffff810b4133)
Location: include/linux/sched/cputime.h:180
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_signal
```
```
In kernel/cgroup/cgroup.c (ffffffff81191d9e)
Location: include/linux/sched/cputime.h:180
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_cgroup_housekeeping
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
In kernel/fork.c (ffffffff810ca496)
Location: include/linux/sched/cputime.h:181
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_signal
```
```
In kernel/cgroup/cgroup.c (ffffffff811c178e)
Location: include/linux/sched/cputime.h:181
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_cgroup_housekeeping
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
In kernel/fork.c (ffffffff810e7b20)
Location: include/linux/sched/cputime.h:181
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_signal
```
```
In kernel/cgroup/cgroup.c (ffffffff81203d6e)
Location: include/linux/sched/cputime.h:181
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_cgroup_housekeeping
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
In kernel/fork.c (ffffffff810f3749)
Location: include/linux/sched/cputime.h:172
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_signal
```
```
In kernel/cgroup/cgroup.c (ffffffff812192ce)
Location: include/linux/sched/cputime.h:172
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_cgroup_housekeeping
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
In kernel/fork.c (ffffffff810fcaf9)
Location: include/linux/sched/cputime.h:172
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_signal
```
```
In kernel/cgroup/cgroup.c (ffffffff81230dde)
Location: include/linux/sched/cputime.h:172
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_cgroup_housekeeping
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
In kernel/fork.c (ffff8000100f3820)
Location: include/linux/sched/cputime.h:180
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/cgroup/cgroup.c (ffff8000101cf0e0)
Location: include/linux/sched/cputime.h:180
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_cgroup_housekeeping
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
In kernel/fork.c (c0351fb8)
Location: include/linux/sched/cputime.h:180
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/cgroup/cgroup.c (c0412c9c)
Location: include/linux/sched/cputime.h:180
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_cgroup_housekeeping
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
In kernel/fork.c (c000000000139604)
Location: include/linux/sched/cputime.h:180
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/cgroup/cgroup.c (c00000000023930c)
Location: include/linux/sched/cputime.h:180
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_cgroup_housekeeping
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
In kernel/fork.c (ffffffe0000bff86)
Location: include/linux/sched/cputime.h:180
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/cgroup/cgroup.c (ffffffe000149926)
Location: include/linux/sched/cputime.h:180
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_cgroup_housekeeping
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
In kernel/fork.c (ffffffff810985cf)
Location: include/linux/sched/cputime.h:180
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/cgroup/cgroup.c (ffffffff81156ee1)
Location: include/linux/sched/cputime.h:180
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_cgroup_housekeeping
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
In kernel/fork.c (ffffffff81087015)
Location: include/linux/sched/cputime.h:180
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/cgroup/cgroup.c (ffffffff8114a201)
Location: include/linux/sched/cputime.h:180
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_cgroup_housekeeping
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
In kernel/fork.c (ffffffff8109857f)
Location: include/linux/sched/cputime.h:180
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/cgroup/cgroup.c (ffffffff81154cb1)
Location: include/linux/sched/cputime.h:180
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_cgroup_housekeeping
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
In kernel/fork.c (ffffffff810a01a6)
Location: include/linux/sched/cputime.h:180
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/cgroup/cgroup.c (ffffffff811621d1)
Location: include/linux/sched/cputime.h:180
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_cgroup_housekeeping
```
</details>
</li>
</ul>

## Differences
