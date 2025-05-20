# Function: <code>sched_mm_cid_migrate_to</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sched_mm_cid_migrate_to(struct rq *dst_rq, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8114e360)
Location: kernel/sched/core.c:11751
Inline: False
Direct callers:
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:ttwu_do_activate
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:move_queued_task
```
**Symbols:**

```
ffffffff8114e360-ffffffff8114e613: sched_mm_cid_migrate_to (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sched_mm_cid_migrate_to(struct rq *dst_rq, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8115a1a0)
Location: kernel/sched/core.c:11750
Inline: False
Direct callers:
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:ttwu_do_activate
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:move_queued_task
```
**Symbols:**

```
ffffffff8115a1a0-ffffffff8115a475: sched_mm_cid_migrate_to (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
