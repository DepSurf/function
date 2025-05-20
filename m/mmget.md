# Function: <code>mmget</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81080693)
Location: include/linux/sched/mm.h:75
Inline: True
Inline callers:
  - kernel/fork.c:get_task_mm
```
```
In mm/swapfile.c (ffffffff8120fa97)
Location: include/linux/sched/mm.h:75
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
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
In kernel/fork.c (ffffffff81086f33)
Location: include/linux/sched/mm.h:76
Inline: True
Inline callers:
  - kernel/fork.c:get_task_mm
```
```
In mm/swapfile.c (ffffffff8122b376)
Location: include/linux/sched/mm.h:76
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
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
In kernel/fork.c (ffffffff8108b74e)
Location: include/linux/sched/mm.h:68
Inline: True
Inline callers:
  - kernel/fork.c:copy_mm
  - kernel/fork.c:get_task_mm
```
```
In mm/swapfile.c (ffffffff8124c573)
Location: include/linux/sched/mm.h:68
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
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
In kernel/fork.c (ffffffff81092ee3)
Location: include/linux/sched/mm.h:68
Inline: True
Inline callers:
  - kernel/fork.c:get_task_mm
```
```
In mm/swapfile.c (ffffffff81260abd)
Location: include/linux/sched/mm.h:68
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
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
In kernel/fork.c (ffffffff81098fe7)
Location: include/linux/sched/mm.h:93
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:get_task_mm
```
```
In mm/swapfile.c (ffffffff8127b6cd)
Location: include/linux/sched/mm.h:93
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
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
In kernel/fork.c (ffffffff8109f54c)
Location: include/linux/sched/mm.h:93
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:get_task_mm
```
```
In mm/swapfile.c (ffffffff8128b1ad)
Location: include/linux/sched/mm.h:93
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
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
In kernel/fork.c (ffffffff810a6678)
Location: include/linux/sched/mm.h:95
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:get_task_mm
```
```
In mm/swapfile.c (ffffffff812be38f)
Location: include/linux/sched/mm.h:95
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
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
In kernel/fork.c (ffffffff810a20ea)
Location: include/linux/sched/mm.h:68
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:get_task_mm
```
```
In mm/swapfile.c (ffffffff812c9fae)
Location: include/linux/sched/mm.h:68
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/migrate.c (ffffffff812ed1af)
Location: include/linux/sched/mm.h:68
Inline: True
Inline callers:
  - mm/migrate.c:find_mm_struct
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
In kernel/fork.c (ffffffff810a2e00)
Location: include/linux/sched/mm.h:68
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:get_task_mm
```
```
In mm/swapfile.c (ffffffff812d0a0a)
Location: include/linux/sched/mm.h:68
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/migrate.c (ffffffff812f354b)
Location: include/linux/sched/mm.h:68
Inline: True
Inline callers:
  - mm/migrate.c:find_mm_struct
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
In kernel/fork.c (ffffffff810b455e)
Location: include/linux/sched/mm.h:68
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:get_task_mm
```
```
In mm/swapfile.c (ffffffff813160e5)
Location: include/linux/sched/mm.h:68
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/migrate.c (ffffffff8133d9bb)
Location: include/linux/sched/mm.h:68
Inline: True
Inline callers:
  - mm/migrate.c:find_mm_struct
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
In kernel/fork.c (ffffffff810ca946)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:mm_access
```
```
In mm/swapfile.c (ffffffff8138128a)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/migrate.c (ffffffff813b0c80)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - mm/migrate.c:find_mm_struct
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
In kernel/fork.c (ffffffff810e7f65)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:mm_access
```
```
In mm/swapfile.c (ffffffff813ffacc)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/migrate.c (ffffffff814317d0)
Location: include/linux/sched/mm.h:98
Inline: True
Inline callers:
  - mm/migrate.c:find_mm_struct
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
In kernel/fork.c (ffffffff810f3baa)
Location: include/linux/sched/mm.h:130
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:mm_access
```
```
In mm/swapfile.c (ffffffff8143295c)
Location: include/linux/sched/mm.h:130
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/migrate.c (ffffffff81467210)
Location: include/linux/sched/mm.h:130
Inline: True
Inline callers:
  - mm/migrate.c:find_mm_struct
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
In kernel/fork.c (ffffffff810fcf7b)
Location: include/linux/sched/mm.h:130
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:mm_access
```
```
In mm/swapfile.c (ffffffff8146bd7c)
Location: include/linux/sched/mm.h:130
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/migrate.c (ffffffff81496450)
Location: include/linux/sched/mm.h:130
Inline: True
Inline callers:
  - mm/migrate.c:find_mm_struct
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
In kernel/fork.c (ffff8000100f487c)
Location: include/linux/sched/mm.h:93
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:get_task_mm
```
```
In mm/swapfile.c (ffff800010326550)
Location: include/linux/sched/mm.h:93
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
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
In kernel/fork.c (c0352610)
Location: include/linux/sched/mm.h:93
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:get_task_mm
```
```
In mm/swapfile.c (c053df34)
Location: include/linux/sched/mm.h:93
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
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
In kernel/fork.c (c000000000139c8c)
Location: include/linux/sched/mm.h:93
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:get_task_mm
```
```
In mm/swapfile.c (c0000000003fcc18)
Location: include/linux/sched/mm.h:93
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
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
In kernel/fork.c (ffffffe0000c04ae)
Location: include/linux/sched/mm.h:93
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:get_task_mm
```
```
In mm/swapfile.c (ffffffe0002267aa)
Location: include/linux/sched/mm.h:93
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
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
In kernel/fork.c (ffffffff81098e6c)
Location: include/linux/sched/mm.h:93
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:get_task_mm
```
```
In mm/swapfile.c (ffffffff8128378d)
Location: include/linux/sched/mm.h:93
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
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
In kernel/fork.c (ffffffff810878bc)
Location: include/linux/sched/mm.h:93
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:get_task_mm
```
```
In mm/swapfile.c (ffffffff81275640)
Location: include/linux/sched/mm.h:93
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
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
In kernel/fork.c (ffffffff81098e1c)
Location: include/linux/sched/mm.h:93
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:get_task_mm
```
```
In mm/swapfile.c (ffffffff8128159d)
Location: include/linux/sched/mm.h:93
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
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
In kernel/fork.c (ffffffff810a0a3e)
Location: include/linux/sched/mm.h:93
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:get_task_mm
```
```
In mm/swapfile.c (ffffffff812912dd)
Location: include/linux/sched/mm.h:93
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
</details>
</li>
</ul>

## Differences
