# Function: <code>set_task_rq</code>

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
In kernel/sched/core.c (ffffffff810ab310)
Location: kernel/sched/sched.h:929
Inline: True
Inline callers:
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:sched_move_task
```
```
In kernel/sched/fair.c (ffffffff810b44d6)
Location: kernel/sched/sched.h:929
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_move_group_fair
  - kernel/sched/fair.c:task_fork_fair
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
In kernel/sched/core.c (ffffffff810b103d)
Location: kernel/sched/sched.h:965
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/fair.c (ffffffff810bf2c8)
Location: kernel/sched/sched.h:965
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
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
In kernel/sched/core.c (ffffffff810b72d2)
Location: kernel/sched/sched.h:995
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/fair.c (ffffffff810c4744)
Location: kernel/sched/sched.h:995
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
In kernel/sched/core.c (ffffffff810b35e2)
Location: kernel/sched/sched.h:1163
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/fair.c (ffffffff810bee34)
Location: kernel/sched/sched.h:1163
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
In kernel/sched/core.c (ffffffff810ba852)
Location: kernel/sched/sched.h:1181
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/fair.c (ffffffff810c6614)
Location: kernel/sched/sched.h:1181
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
In kernel/sched/core.c (ffffffff810c1cd2)
Location: kernel/sched/sched.h:1270
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/fair.c (ffffffff810ce4e4)
Location: kernel/sched/sched.h:1270
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
In kernel/sched/core.c (ffffffff810cb002)
Location: kernel/sched/sched.h:1424
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/fair.c (ffffffff810d79e4)
Location: kernel/sched/sched.h:1424
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
In kernel/sched/core.c (ffffffff810d2c95)
Location: kernel/sched/sched.h:1482
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/fair.c (ffffffff810dee20)
Location: kernel/sched/sched.h:1482
Inline: True
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
In kernel/sched/core.c (ffffffff810dd105)
Location: kernel/sched/sched.h:1496
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/fair.c (ffffffff810e9518)
Location: kernel/sched/sched.h:1496
Inline: True
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
In kernel/sched/core.c (ffffffff810e5ce5)
Location: kernel/sched/sched.h:1536
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/fair.c (ffffffff810eddca)
Location: kernel/sched/sched.h:1536
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
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
In kernel/sched/core.c (ffffffff810e3a33)
Location: kernel/sched/sched.h:1594
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/fair.c (ffffffff810ebbea)
Location: kernel/sched/sched.h:1594
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void set_task_rq(struct task_struct *p, unsigned int cpu);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e41d0)
Location: kernel/sched/sched.h:1605
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
Direct callers:
  - kernel/sched/core.c:init_idle
```
```
In kernel/sched/fair.c (ffffffff810ed74a)
Location: kernel/sched/sched.h:1605
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
```
**Symbols:**

```
ffffffff81bce582-ffffffff81bce5e1: set_task_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void set_task_rq(struct task_struct *p, unsigned int cpu);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810faee0)
Location: kernel/sched/sched.h:1893
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_cgroup_fork
  - kernel/sched/core.c:set_task_cpu
Direct callers:
  - kernel/sched/core.c:init_idle
```
```
In kernel/sched/fair.c (ffffffff8110645a)
Location: kernel/sched/sched.h:1893
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
```
**Symbols:**

```
ffffffff81ca59c0-ffffffff81ca5a1f: set_task_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void set_task_rq(struct task_struct *p, unsigned int cpu);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81117345)
Location: kernel/sched/sched.h:1893
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_cgroup_fork
  - kernel/sched/core.c:set_task_cpu
Direct callers:
  - kernel/sched/core.c:init_idle
```
```
In kernel/sched/fair.c (ffffffff81122b19)
Location: kernel/sched/sched.h:1893
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
```
**Symbols:**

```
ffffffff81e552d0-ffffffff81e55338: set_task_rq (STB_LOCAL)
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
In kernel/sched/core.c (ffffffff81142332)
Location: kernel/sched/sched.h:1942
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_cgroup_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/fair.c (ffffffff8114a965)
Location: kernel/sched/sched.h:1942
Inline: True
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
In kernel/sched/core.c (ffffffff8114dfad)
Location: kernel/sched/sched.h:1985
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_cgroup_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/fair.c (ffffffff8115c6e5)
Location: kernel/sched/sched.h:1985
Inline: True
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
In kernel/sched/core.c (ffffffff81159de8)
Location: kernel/sched/sched.h:2027
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_cgroup_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/fair.c (ffffffff811669b5)
Location: kernel/sched/sched.h:2027
Inline: True
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
In kernel/sched/core.c (ffff80001013cbe8)
Location: kernel/sched/sched.h:1496
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/fair.c (ffff8000101493f8)
Location: kernel/sched/sched.h:1496
Inline: True
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
In kernel/sched/core.c (c038d08c)
Location: kernel/sched/sched.h:1496
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/fair.c (c03971a0)
Location: kernel/sched/sched.h:1496
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
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
In kernel/sched/core.c (c00000000018b2d4)
Location: kernel/sched/sched.h:1496
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/fair.c (c00000000019b2c8)
Location: kernel/sched/sched.h:1496
Inline: True
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
In kernel/sched/core.c (ffffffe0000ec3ce)
Location: kernel/sched/sched.h:1496
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/fair.c (ffffffe0000f333c)
Location: kernel/sched/sched.h:1496
Inline: True
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
In kernel/sched/core.c (ffffffff810d7315)
Location: kernel/sched/sched.h:1496
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/fair.c (ffffffff810e36c0)
Location: kernel/sched/sched.h:1496
Inline: True
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
In kernel/sched/core.c (ffffffff810c5c05)
Location: kernel/sched/sched.h:1496
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/fair.c (ffffffff810d27c8)
Location: kernel/sched/sched.h:1496
Inline: True
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
In kernel/sched/core.c (ffffffff810d3f55)
Location: kernel/sched/sched.h:1496
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/fair.c (ffffffff810dfa48)
Location: kernel/sched/sched.h:1496
Inline: True
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
In kernel/sched/core.c (ffffffff810deefa)
Location: kernel/sched/sched.h:1496
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/fair.c (ffffffff810eb610)
Location: kernel/sched/sched.h:1496
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
