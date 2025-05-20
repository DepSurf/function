# Function: <code>__update_stats_enqueue_sleeper</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __update_stats_enqueue_sleeper(struct rq *rq, struct task_struct *p, struct sched_statistics *stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/stats.c:47
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_task_rt
```
**Symbols:**

```
ffffffff81e592b2-ffffffff81e592e2: __update_stats_enqueue_sleeper.cold (STB_LOCAL)
ffffffff81147f80-ffffffff811481fd: __update_stats_enqueue_sleeper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __update_stats_enqueue_sleeper(struct rq *rq, struct task_struct *p, struct sched_statistics *stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/stats.c:47
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_task_rt
```
**Symbols:**

```
ffffffff8205804a-ffffffff8205807a: __update_stats_enqueue_sleeper.cold (STB_LOCAL)
ffffffff81176700-ffffffff8117698b: __update_stats_enqueue_sleeper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __update_stats_enqueue_sleeper(struct rq *rq, struct task_struct *p, struct sched_statistics *stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/stats.c:47
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_task_rt
```
**Symbols:**

```
ffffffff820d694e-ffffffff820d697e: __update_stats_enqueue_sleeper.cold (STB_LOCAL)
ffffffff81187340-ffffffff811875cb: __update_stats_enqueue_sleeper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __update_stats_enqueue_sleeper(struct rq *rq, struct task_struct *p, struct sched_statistics *stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/stats.c:47
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_task_rt
```
**Symbols:**

```
ffffffff821b1bda-ffffffff821b1c14: __update_stats_enqueue_sleeper.cold (STB_LOCAL)
ffffffff81195a70-ffffffff81195d8b: __update_stats_enqueue_sleeper (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
