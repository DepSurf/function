# Function: <code>check_holdout_task</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff810e9575)
Location: kernel/rcu/update.c:617
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
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
In kernel/rcu/update.c (ffffffff810f043c)
Location: kernel/rcu/update.c:620
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
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
In kernel/rcu/update.c (ffffffff810f0430)
Location: kernel/rcu/update.c:679
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
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
In kernel/rcu/update.c (ffffffff810fa0f4)
Location: kernel/rcu/update.c:678
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
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
In kernel/rcu/update.c (ffffffff81102733)
Location: kernel/rcu/update.c:630
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
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
In kernel/rcu/update.c (ffffffff8110e13b)
Location: kernel/rcu/update.c:626
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
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
In kernel/rcu/update.c (ffffffff81117858)
Location: kernel/rcu/update.c:571
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
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
In kernel/rcu/update.c (ffffffff81123c2c)
Location: kernel/rcu/update.c:598
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
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
In kernel/rcu/update.c (ffffffff811307e6)
Location: kernel/rcu/tasks.h:418
Inline: True
Inline callers:
  - kernel/rcu/update.c:check_all_holdout_tasks
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff81174442)
Location: kernel/rcu/tasks.h:806
Inline: True
Inline callers:
  - kernel/rcu/update.c:check_all_holdout_tasks
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
In kernel/rcu/update.c (ffffffff811aa3d0)
Location: kernel/rcu/tasks.h:854
Inline: True
Inline callers:
  - kernel/rcu/update.c:check_all_holdout_tasks
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
In kernel/rcu/update.c (ffffffff811bc300)
Location: kernel/rcu/tasks.h:876
Inline: True
Inline callers:
  - kernel/rcu/update.c:check_all_holdout_tasks
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void check_holdout_task(struct task_struct *t, bool needreport, bool *firstreport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:969
Inline: False
Direct callers:
  - kernel/rcu/update.c:check_all_holdout_tasks
```
**Symbols:**

```
ffffffff811cce20-ffffffff811cd058: check_holdout_task (STB_LOCAL)
ffffffff821b3862-ffffffff821b389c: check_holdout_task.cold (STB_LOCAL)
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
In kernel/rcu/update.c (ffff800010188e84)
Location: kernel/rcu/update.c:598
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
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
In kernel/rcu/update.c (c03d76ec)
Location: kernel/rcu/update.c:598
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
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
In kernel/rcu/update.c (c0000000001e3130)
Location: kernel/rcu/update.c:598
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
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
In kernel/rcu/update.c (ffffffe00011e178)
Location: kernel/rcu/update.c:598
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
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
In kernel/rcu/update.c (ffffffff8111c20c)
Location: kernel/rcu/update.c:598
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
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
In kernel/rcu/update.c (ffffffff8110d265)
Location: kernel/rcu/update.c:598
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
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
In kernel/rcu/update.c (ffffffff8111a0fc)
Location: kernel/rcu/update.c:598
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
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
In kernel/rcu/update.c (ffffffff81125858)
Location: kernel/rcu/update.c:598
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
