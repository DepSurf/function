# Function: <code>iterate_groups</code>

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
In kernel/sched/psi.c (ffffffff810ef758)
Location: kernel/sched/psi.c:486
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
In kernel/sched/psi.c (ffffffff810f6bec)
Location: kernel/sched/psi.c:722
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
In kernel/sched/psi.c (ffffffff8110297c)
Location: kernel/sched/psi.c:723
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
In kernel/sched/psi.c (ffffffff8110d99c)
Location: kernel/sched/psi.c:728
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
In kernel/sched/psi.c (ffffffff8110ac8c)
Location: kernel/sched/psi.c:744
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
In kernel/sched/psi.c (ffffffff8110c8b5)
Location: kernel/sched/psi.c:749
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
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct psi_group *iterate_groups(struct task_struct *task, void **iter);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff8112b62a)
Location: kernel/sched/psi.c:761
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
Direct callers:
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_switch
```
**Symbols:**

```
ffffffff81129bd0-ffffffff81129c33: iterate_groups (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct psi_group *iterate_groups(struct task_struct *task, void **iter);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8114bd6d)
Location: kernel/sched/psi.c:760
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_task_change
Direct callers:
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_switch
```
**Symbols:**

```
ffffffff8113c3b0-ffffffff8113c428: iterate_groups (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
Location: kernel/sched/psi.c:723
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
Location: kernel/sched/psi.c:723
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
Location: kernel/sched/psi.c:723
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
In kernel/sched/psi.c (ffffffe000109c20)
Location: kernel/sched/psi.c:723
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
In kernel/sched/psi.c (ffffffff810fbc8c)
Location: kernel/sched/psi.c:723
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
In kernel/sched/psi.c (ffffffff810ebeac)
Location: kernel/sched/psi.c:723
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
In kernel/sched/psi.c (ffffffff810f8e4c)
Location: kernel/sched/psi.c:723
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
In kernel/sched/psi.c (ffffffff81103f9c)
Location: kernel/sched/psi.c:723
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
