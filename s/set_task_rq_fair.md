# Function: <code>set_task_rq_fair</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void set_task_rq_fair(struct sched_entity *se, struct cfs_rq *prev, struct cfs_rq *next);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bf110)
Location: kernel/sched/fair.c:2831
Inline: True
Direct callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
```
**Symbols:**

```
ffffffff810bf110-ffffffff810bf299: set_task_rq_fair (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void set_task_rq_fair(struct sched_entity *se, struct cfs_rq *prev, struct cfs_rq *next);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c4590)
Location: kernel/sched/fair.c:2995
Inline: True
Direct callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
**Symbols:**

```
ffffffff810c4590-ffffffff810c4719: set_task_rq_fair (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void set_task_rq_fair(struct sched_entity *se, struct cfs_rq *prev, struct cfs_rq *next);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bedc0)
Location: kernel/sched/fair.c:3072
Inline: True
Direct callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
**Symbols:**

```
ffffffff810bedc0-ffffffff810bee01: set_task_rq_fair (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void set_task_rq_fair(struct sched_entity *se, struct cfs_rq *prev, struct cfs_rq *next);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c65a0)
Location: kernel/sched/fair.c:3361
Inline: True
Direct callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
**Symbols:**

```
ffffffff810c65a0-ffffffff810c65e4: set_task_rq_fair (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void set_task_rq_fair(struct sched_entity *se, struct cfs_rq *prev, struct cfs_rq *next);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ce470)
Location: kernel/sched/fair.c:3412
Inline: True
Direct callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
**Symbols:**

```
ffffffff810ce470-ffffffff810ce4b5: set_task_rq_fair (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void set_task_rq_fair(struct sched_entity *se, struct cfs_rq *prev, struct cfs_rq *next);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d7960)
Location: kernel/sched/fair.c:3085
Inline: True
Direct callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
**Symbols:**

```
ffffffff810d7960-ffffffff810d79b5: set_task_rq_fair (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void set_task_rq_fair(struct sched_entity *se, struct cfs_rq *prev, struct cfs_rq *next);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810deda0)
Location: kernel/sched/fair.c:3170
Inline: True
Direct callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
**Symbols:**

```
ffffffff810deda0-ffffffff810dede6: set_task_rq_fair (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void set_task_rq_fair(struct sched_entity *se, struct cfs_rq *prev, struct cfs_rq *next);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e9490)
Location: kernel/sched/fair.c:3170
Inline: True
Direct callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
**Symbols:**

```
ffffffff810e9490-ffffffff810e94d6: set_task_rq_fair (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void set_task_rq_fair(struct sched_entity *se, struct cfs_rq *prev, struct cfs_rq *next);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810eddd5)
Location: kernel/sched/fair.c:3326
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
Direct callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
**Symbols:**

```
ffffffff810f3a00-ffffffff810f3a46: set_task_rq_fair (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void set_task_rq_fair(struct sched_entity *se, struct cfs_rq *prev, struct cfs_rq *next);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ebbf5)
Location: kernel/sched/fair.c:3339
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
Direct callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
**Symbols:**

```
ffffffff810f1c40-ffffffff810f1c86: set_task_rq_fair (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void set_task_rq_fair(struct sched_entity *se, struct cfs_rq *prev, struct cfs_rq *next);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ed755)
Location: kernel/sched/fair.c:3382
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
Direct callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
**Symbols:**

```
ffffffff810f3f20-ffffffff810f3f66: set_task_rq_fair (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void set_task_rq_fair(struct sched_entity *se, struct cfs_rq *prev, struct cfs_rq *next);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81106465)
Location: kernel/sched/fair.c:3381
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
Direct callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_cgroup_fork
  - kernel/sched/core.c:set_task_cpu
```
**Symbols:**

```
ffffffff8110d870-ffffffff8110d8b3: set_task_rq_fair (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void set_task_rq_fair(struct sched_entity *se, struct cfs_rq *prev, struct cfs_rq *next);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81122b24)
Location: kernel/sched/fair.c:3408
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
Direct callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_cgroup_fork
  - kernel/sched/core.c:set_task_cpu
```
**Symbols:**

```
ffffffff81129500-ffffffff8112955b: set_task_rq_fair (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void set_task_rq_fair(struct sched_entity *se, struct cfs_rq *prev, struct cfs_rq *next);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8114a970)
Location: kernel/sched/fair.c:3629
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_cgroup_fork
  - kernel/sched/core.c:set_task_cpu
```
**Symbols:**

```
ffffffff81152fb0-ffffffff8115300b: set_task_rq_fair (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void set_task_rq_fair(struct sched_entity *se, struct cfs_rq *prev, struct cfs_rq *next);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8115c6f0)
Location: kernel/sched/fair.c:3686
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_cgroup_fork
  - kernel/sched/core.c:set_task_cpu
```
**Symbols:**

```
ffffffff81162860-ffffffff811628bb: set_task_rq_fair (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void set_task_rq_fair(struct sched_entity *se, struct cfs_rq *prev, struct cfs_rq *next);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811669c0)
Location: kernel/sched/fair.c:4171
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_cgroup_fork
  - kernel/sched/core.c:set_task_cpu
```
**Symbols:**

```
ffffffff8116f330-ffffffff8116f38b: set_task_rq_fair (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void set_task_rq_fair(struct sched_entity *se, struct cfs_rq *prev, struct cfs_rq *next);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff800010149348)
Location: kernel/sched/fair.c:3170
Inline: True
Direct callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
**Symbols:**

```
ffff800010149348-ffff8000101493b4: set_task_rq_fair (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void set_task_rq_fair(struct sched_entity *se, struct cfs_rq *prev, struct cfs_rq *next);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c0397088)
Location: kernel/sched/fair.c:3170
Inline: True
Direct callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
```
**Symbols:**

```
c0397088-c0397158: set_task_rq_fair (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void set_task_rq_fair(struct sched_entity *se, struct cfs_rq *prev, struct cfs_rq *next);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c00000000019b200)
Location: kernel/sched/fair.c:3170
Inline: True
Direct callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
**Symbols:**

```
c00000000019b200-c00000000019b274: set_task_rq_fair (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void set_task_rq_fair(struct sched_entity *se, struct cfs_rq *prev, struct cfs_rq *next);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffe0000f32be)
Location: kernel/sched/fair.c:3170
Inline: True
Direct callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
**Symbols:**

```
ffffffe0000f32be-ffffffe0000f330a: set_task_rq_fair (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void set_task_rq_fair(struct sched_entity *se, struct cfs_rq *prev, struct cfs_rq *next);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e3640)
Location: kernel/sched/fair.c:3170
Inline: True
Direct callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
**Symbols:**

```
ffffffff810e3640-ffffffff810e3686: set_task_rq_fair (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void set_task_rq_fair(struct sched_entity *se, struct cfs_rq *prev, struct cfs_rq *next);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d2740)
Location: kernel/sched/fair.c:3170
Inline: True
Direct callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
**Symbols:**

```
ffffffff810d2740-ffffffff810d2786: set_task_rq_fair (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void set_task_rq_fair(struct sched_entity *se, struct cfs_rq *prev, struct cfs_rq *next);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810df9c0)
Location: kernel/sched/fair.c:3170
Inline: True
Direct callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
**Symbols:**

```
ffffffff810df9c0-ffffffff810dfa06: set_task_rq_fair (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void set_task_rq_fair(struct sched_entity *se, struct cfs_rq *prev, struct cfs_rq *next);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810eb590)
Location: kernel/sched/fair.c:3170
Inline: True
Direct callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
**Symbols:**

```
ffffffff810eb590-ffffffff810eb5d6: set_task_rq_fair (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
