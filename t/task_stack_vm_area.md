# Function: <code>task_stack_vm_area</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81084205)
Location: include/linux/sched.h:2018
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
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
In kernel/fork.c (ffffffff81081739)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/fork.c:put_task_stack
  - kernel/fork.c:account_kernel_stack
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
In kernel/fork.c (ffffffff8108801a)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/fork.c:put_task_stack
  - kernel/fork.c:account_kernel_stack
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
In kernel/fork.c (ffffffff8108bd6c)
Location: include/linux/sched/task.h:122
Inline: True
Inline callers:
  - kernel/fork.c:put_task_stack
  - kernel/fork.c:account_kernel_stack
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
In kernel/fork.c (ffffffff810935eb)
Location: include/linux/sched/task.h:124
Inline: True
Inline callers:
  - kernel/fork.c:put_task_stack
  - kernel/fork.c:account_kernel_stack
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
In kernel/fork.c (ffffffff81097d10)
Location: include/linux/sched/task.h:141
Inline: True
Inline callers:
  - kernel/fork.c:put_task_stack
  - kernel/fork.c:account_kernel_stack
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
In kernel/fork.c (ffffffff8109e3cd)
Location: include/linux/sched/task.h:145
Inline: True
Inline callers:
  - kernel/fork.c:put_task_stack
  - kernel/fork.c:account_kernel_stack
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
In kernel/fork.c (ffffffff810a5a86)
Location: include/linux/sched/task.h:152
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:memcg_charge_kernel_stack
  - kernel/fork.c:account_kernel_stack
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
In kernel/fork.c (ffffffff810a1328)
Location: include/linux/sched/task.h:143
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:put_task_stack
  - kernel/fork.c:account_kernel_stack
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
In kernel/fork.c (ffffffff810a2098)
Location: include/linux/sched/task.h:145
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:put_task_stack
  - kernel/fork.c:account_kernel_stack
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
In kernel/fork.c (ffffffff810b2edb)
Location: include/linux/sched/task.h:146
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:put_task_stack
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
In kernel/fork.c (ffffffff810c8fe6)
Location: include/linux/sched/task.h:151
Inline: True
Inline callers:
  - kernel/fork.c:exit_task_stack_account
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
In kernel/fork.c (ffffffff810e64a6)
Location: include/linux/sched/task.h:154
Inline: True
Inline callers:
  - kernel/fork.c:exit_task_stack_account
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
In kernel/fork.c (ffffffff810f2011)
Location: include/linux/sched/task.h:162
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:exit_task_stack_account
  - kernel/fork.c:exit_task_stack_account
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
In kernel/fork.c (ffffffff810fba79)
Location: include/linux/sched/task.h:200
Inline: True
Inline callers:
  - kernel/fork.c:exit_task_stack_account
  - kernel/fork.c:account_kernel_stack
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
In kernel/fork.c (ffff8000100f32a4)
Location: include/linux/sched/task.h:145
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:account_kernel_stack
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
In kernel/fork.c (0)
Location: include/linux/sched/task.h:150
Inline: True
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
In kernel/fork.c (0)
Location: include/linux/sched/task.h:150
Inline: True
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
In kernel/fork.c (0)
Location: include/linux/sched/task.h:150
Inline: True
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
In kernel/fork.c (ffffffff81097ced)
Location: include/linux/sched/task.h:145
Inline: True
Inline callers:
  - kernel/fork.c:put_task_stack
  - kernel/fork.c:account_kernel_stack
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
In kernel/fork.c (ffffffff8108675d)
Location: include/linux/sched/task.h:145
Inline: True
Inline callers:
  - kernel/fork.c:put_task_stack
  - kernel/fork.c:account_kernel_stack
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
In kernel/fork.c (ffffffff81097c9d)
Location: include/linux/sched/task.h:145
Inline: True
Inline callers:
  - kernel/fork.c:put_task_stack
  - kernel/fork.c:account_kernel_stack
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
In kernel/fork.c (ffffffff8109f89d)
Location: include/linux/sched/task.h:145
Inline: True
Inline callers:
  - kernel/fork.c:put_task_stack
  - kernel/fork.c:account_kernel_stack
```
</details>
</li>
</ul>

## Differences
