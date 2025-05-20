# Function: <code>task_cgroup</code>

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
In mm/memcontrol.c (ffffffff811ff152)
Location: include/linux/cgroup.h:473
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_info
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
In kernel/cgroup_pids.c (ffffffff81122380)
Location: include/linux/cgroup.h:477
Inline: True
Inline callers:
  - kernel/cgroup_pids.c:pids_can_fork
```
```
In mm/memcontrol.c (ffffffff81222f03)
Location: include/linux/cgroup.h:477
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_info
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
In mm/memcontrol.c (ffffffff812352f3)
Location: include/linux/cgroup.h:477
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_info
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
In mm/memcontrol.c (ffffffff81240c51)
Location: include/linux/cgroup.h:497
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_info
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81260991)
Location: include/linux/cgroup.h:519
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_info
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81286d8b)
Location: include/linux/cgroup.h:519
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8129bcbf)
Location: include/linux/cgroup.h:521
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_context
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
In mm/memcontrol.c (ffffffff812b6e92)
Location: include/linux/cgroup.h:534
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_context
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
In mm/memcontrol.c (ffffffff812c8d67)
Location: include/linux/cgroup.h:536
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_context
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
In mm/memcontrol.c (ffffffff812fe3be)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_context
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
In mm/memcontrol.c (ffffffff81be9bfa)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_context
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
In mm/memcontrol.c (ffffffff81bdbc17)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_context
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
In mm/memcontrol.c (ffffffff81cc295f)
Location: include/linux/cgroup.h:542
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_context
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
In mm/memcontrol.c (ffffffff81e74ed7)
Location: include/linux/cgroup.h:543
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_context
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
In mm/memcontrol.c (ffffffff81456e98)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_context
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
In mm/memcontrol.c (ffffffff8148c6f8)
Location: include/linux/cgroup.h:484
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_context
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
In mm/memcontrol.c (ffffffff814bc048)
Location: include/linux/cgroup.h:482
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_context
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
In mm/memcontrol.c (ffff800010369518)
Location: include/linux/cgroup.h:536
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_context
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
In mm/memcontrol.c (c055aa00)
Location: include/linux/cgroup.h:536
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_context
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
In mm/memcontrol.c (c000000000457bf4)
Location: include/linux/cgroup.h:536
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_context
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
In mm/memcontrol.c (ffffffe000246fde)
Location: include/linux/cgroup.h:536
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_context
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
In mm/memcontrol.c (ffffffff812c1347)
Location: include/linux/cgroup.h:536
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_context
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
In mm/memcontrol.c (ffffffff812b2397)
Location: include/linux/cgroup.h:536
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_context
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
In mm/memcontrol.c (ffffffff812bf157)
Location: include/linux/cgroup.h:536
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_context
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
In mm/memcontrol.c (ffffffff812cfbbb)
Location: include/linux/cgroup.h:536
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_context
```
</details>
</li>
</ul>

## Differences
