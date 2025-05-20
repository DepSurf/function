# Function: <code>find_idlest_group_cpu</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bf528)
Location: kernel/sched/fair.c:5914
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
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
In kernel/sched/fair.c (ffffffff810c75cb)
Location: kernel/sched/fair.c:6139
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
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
In kernel/sched/fair.c (ffffffff810cfd34)
Location: kernel/sched/fair.c:5879
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
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
In kernel/sched/fair.c (ffffffff810d71c9)
Location: kernel/sched/fair.c:5744
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
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
In kernel/sched/fair.c (ffffffff810e17a9)
Location: kernel/sched/fair.c:5690
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
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
In kernel/sched/fair.c (ffffffff810eb6fd)
Location: kernel/sched/fair.c:5868
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
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
In kernel/sched/fair.c (ffffffff810e951d)
Location: kernel/sched/fair.c:5917
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
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
In kernel/sched/fair.c (ffffffff810eb13d)
Location: kernel/sched/fair.c:5980
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int find_idlest_group_cpu(struct sched_group *group, struct task_struct *p, int this_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81101c60)
Location: kernel/sched/fair.c:6026
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
**Symbols:**

```
ffffffff81101c60-ffffffff81101f1c: find_idlest_group_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int find_idlest_group_cpu(struct sched_group *group, struct task_struct *p, int this_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8111d510)
Location: kernel/sched/fair.c:6083
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
**Symbols:**

```
ffffffff8111d510-ffffffff8111d7f4: find_idlest_group_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int find_idlest_group_cpu(struct sched_group *group, struct task_struct *p, int this_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81144ea0)
Location: kernel/sched/fair.c:6458
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
**Symbols:**

```
ffffffff81144ea0-ffffffff811451c3: find_idlest_group_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int find_idlest_group_cpu(struct sched_group *group, struct task_struct *p, int this_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811553b0)
Location: kernel/sched/fair.c:6711
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
**Symbols:**

```
ffffffff811553b0-ffffffff811556d1: find_idlest_group_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int find_idlest_group_cpu(struct sched_group *group, struct task_struct *p, int this_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811616e0)
Location: kernel/sched/fair.c:7107
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
**Symbols:**

```
ffffffff811616e0-ffffffff81161a01: find_idlest_group_cpu (STB_LOCAL)
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
In kernel/sched/fair.c (ffff800010141cf8)
Location: kernel/sched/fair.c:5690
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
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
In kernel/sched/fair.c (c0390b68)
Location: kernel/sched/fair.c:5690
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
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
In kernel/sched/fair.c (c000000000190250)
Location: kernel/sched/fair.c:5690
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
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
In kernel/sched/fair.c (ffffffe0000eeaf6)
Location: kernel/sched/fair.c:5690
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
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
In kernel/sched/fair.c (ffffffff810db959)
Location: kernel/sched/fair.c:5690
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
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
In kernel/sched/fair.c (ffffffff810ca969)
Location: kernel/sched/fair.c:5690
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
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
In kernel/sched/fair.c (ffffffff810d7cd9)
Location: kernel/sched/fair.c:5690
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
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
In kernel/sched/fair.c (ffffffff810e3779)
Location: kernel/sched/fair.c:5690
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
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
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
