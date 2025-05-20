# Function: <code>select_fallback_rq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int select_fallback_rq(int cpu, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ab120)
Location: kernel/sched/core.c:1547
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:migration_call
  - kernel/sched/core.c:wake_up_new_task
```
**Symbols:**

```
ffffffff810ab120-ffffffff810ab2a6: select_fallback_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int select_fallback_rq(int cpu, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810add70)
Location: kernel/sched/core.c:1513
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff810add70-ffffffff810adee8: select_fallback_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int select_fallback_rq(int cpu, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b3ee0)
Location: kernel/sched/core.c:1524
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff810b3ee0-ffffffff810b405d: select_fallback_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int select_fallback_rq(int cpu, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810afe80)
Location: kernel/sched/core.c:1456
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff810afe80-ffffffff810affe7: select_fallback_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int select_fallback_rq(int cpu, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b7290)
Location: kernel/sched/core.c:1475
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff810b7290-ffffffff810b73e3: select_fallback_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int select_fallback_rq(int cpu, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:1473
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff810bee40-ffffffff810bef8d: select_fallback_rq (STB_LOCAL)
ffffffff810c2f01-ffffffff810c2f2d: select_fallback_rq.cold.84 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int select_fallback_rq(int cpu, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:1471
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff810c80d0-ffffffff810c821d: select_fallback_rq (STB_LOCAL)
ffffffff810cc1b3-ffffffff810cc1df: select_fallback_rq.cold.84 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int select_fallback_rq(int cpu, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:1911
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff810cf740-ffffffff810cf87f: select_fallback_rq (STB_LOCAL)
ffffffff810d4573-ffffffff810d4595: select_fallback_rq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int select_fallback_rq(int cpu, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:2031
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff810d95e0-ffffffff810d971f: select_fallback_rq (STB_LOCAL)
ffffffff810deb7b-ffffffff810deb9d: select_fallback_rq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int select_fallback_rq(int cpu, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:2101
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_tasks
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff810e2830-ffffffff810e2973: select_fallback_rq (STB_LOCAL)
ffffffff810e6dfd-ffffffff810e6e1e: select_fallback_rq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int select_fallback_rq(int cpu, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:2727
Inline: False
Direct callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff810dc600-ffffffff810dc788: select_fallback_rq (STB_LOCAL)
ffffffff81bdc633-ffffffff81bdc654: select_fallback_rq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int select_fallback_rq(int cpu, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:2748
Inline: False
Direct callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff810ddb20-ffffffff810ddc51: select_fallback_rq (STB_LOCAL)
ffffffff81bce7b5-ffffffff81bce7d7: select_fallback_rq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int select_fallback_rq(int cpu, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:3316
Inline: False
Direct callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff810f22c0-ffffffff810f2483: select_fallback_rq (STB_LOCAL)
ffffffff81ca5c44-ffffffff81ca5c66: select_fallback_rq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int select_fallback_rq(int cpu, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:3415
Inline: False
Direct callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff8110e0e0-ffffffff8110e312: select_fallback_rq (STB_LOCAL)
ffffffff81e5555c-ffffffff81e55580: select_fallback_rq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int select_fallback_rq(int cpu, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81134e10)
Location: kernel/sched/core.c:3471
Inline: False
Direct callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff81134e10-ffffffff811350a0: select_fallback_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int select_fallback_rq(int cpu, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81144010)
Location: kernel/sched/core.c:3540
Inline: False
Direct callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff81144010-ffffffff811442a1: select_fallback_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int select_fallback_rq(int cpu, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8114f530)
Location: kernel/sched/core.c:3559
Inline: False
Direct callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff8114f530-ffffffff8114f7c1: select_fallback_rq (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int select_fallback_rq(int cpu, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff800010139428)
Location: kernel/sched/core.c:2031
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffff800010139428-ffff800010139614: select_fallback_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int select_fallback_rq(int cpu, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c0388c1c)
Location: kernel/sched/core.c:2031
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
c0388c1c-c0388dd4: select_fallback_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int select_fallback_rq(int cpu, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c0000000001860f0)
Location: kernel/sched/core.c:2031
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
c0000000001860f0-c000000000186340: select_fallback_rq (STB_LOCAL)
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
In kernel/sched/core.c (ffffffe0000ead92)
Location: kernel/sched/core.c:2031
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int select_fallback_rq(int cpu, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:2031
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff810d3ab0-ffffffff810d3bef: select_fallback_rq (STB_LOCAL)
ffffffff810d8d6b-ffffffff810d8d8d: select_fallback_rq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int select_fallback_rq(int cpu, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:2031
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff810c20e0-ffffffff810c221f: select_fallback_rq (STB_LOCAL)
ffffffff810c7776-ffffffff810c7798: select_fallback_rq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int select_fallback_rq(int cpu, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:2031
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff810d0d10-ffffffff810d0e4f: select_fallback_rq (STB_LOCAL)
ffffffff810d50ab-ffffffff810d50cd: select_fallback_rq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int select_fallback_rq(int cpu, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:2031
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff810db250-ffffffff810db38f: select_fallback_rq (STB_LOCAL)
ffffffff810e095a-ffffffff810e097c: select_fallback_rq.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
