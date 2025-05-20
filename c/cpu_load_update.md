# Function: <code>cpu_load_update</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cpu_load_update(struct rq *this_rq, long unsigned int this_load, long unsigned int pending_updates);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b6cc0)
Location: kernel/sched/fair.c:4711
Inline: False
Direct callers:
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:cpu_load_update_active
  - kernel/sched/fair.c:cpu_load_update_active
  - kernel/sched/fair.c:cpu_load_update_nohz_stop
```
**Symbols:**

```
ffffffff810b6cc0-ffffffff810b6e02: cpu_load_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cpu_load_update(struct rq *this_rq, long unsigned int this_load, long unsigned int pending_updates);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bc590)
Location: kernel/sched/fair.c:4941
Inline: False
Direct callers:
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:cpu_load_update_active
  - kernel/sched/fair.c:cpu_load_update_active
  - kernel/sched/fair.c:cpu_load_update_nohz_stop
```
**Symbols:**

```
ffffffff810bc590-ffffffff810bc6d2: cpu_load_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cpu_load_update(struct rq *this_rq, long unsigned int this_load, long unsigned int pending_updates);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b71e0)
Location: kernel/sched/fair.c:5084
Inline: False
Direct callers:
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:cpu_load_update_active
  - kernel/sched/fair.c:cpu_load_update_active
  - kernel/sched/fair.c:cpu_load_update_nohz_stop
```
**Symbols:**

```
ffffffff810b71e0-ffffffff810b733c: cpu_load_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cpu_load_update(struct rq *this_rq, long unsigned int this_load, long unsigned int pending_updates);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810be330)
Location: kernel/sched/fair.c:5423
Inline: False
Direct callers:
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:cpu_load_update_active
  - kernel/sched/fair.c:cpu_load_update_active
  - kernel/sched/fair.c:cpu_load_update_nohz_stop
```
**Symbols:**

```
ffffffff810be330-ffffffff810be48c: cpu_load_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cpu_load_update(struct rq *this_rq, long unsigned int this_load, long unsigned int pending_updates);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c5410)
Location: kernel/sched/fair.c:5619
Inline: False
Direct callers:
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:cpu_load_update_active
  - kernel/sched/fair.c:cpu_load_update_active
  - kernel/sched/fair.c:cpu_load_update_nohz_stop
```
**Symbols:**

```
ffffffff810c5410-ffffffff810c54d2: cpu_load_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cpu_load_update(struct rq *this_rq, long unsigned int this_load, long unsigned int pending_updates);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ce9a0)
Location: kernel/sched/fair.c:5361
Inline: False
Direct callers:
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:cpu_load_update_active
  - kernel/sched/fair.c:cpu_load_update_active
  - kernel/sched/fair.c:cpu_load_update_nohz_stop
```
**Symbols:**

```
ffffffff810ce9a0-ffffffff810ceaf8: cpu_load_update (STB_LOCAL)
```
</details>
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
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
