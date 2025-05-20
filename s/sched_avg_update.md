# Function: <code>sched_avg_update</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void sched_avg_update(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aa7e0)
Location: kernel/sched/core.c:749
Inline: False
Direct callers:
  - kernel/sched/fair.c:__update_cpu_load
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:update_curr_dl
```
**Symbols:**

```
ffffffff810aa7e0-ffffffff810aa830: sched_avg_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void sched_avg_update(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ad420)
Location: kernel/sched/core.c:667
Inline: False
Direct callers:
  - kernel/sched/fair.c:cpu_load_update
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:update_curr_dl
```
**Symbols:**

```
ffffffff810ad420-ffffffff810ad470: sched_avg_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sched_avg_update(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b3520)
Location: kernel/sched/core.c:674
Inline: False
Direct callers:
  - kernel/sched/fair.c:cpu_load_update
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:update_curr_dl
```
**Symbols:**

```
ffffffff810b3520-ffffffff810b3570: sched_avg_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sched_avg_update(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810af420)
Location: kernel/sched/core.c:673
Inline: False
Direct callers:
  - kernel/sched/fair.c:cpu_load_update
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:update_curr_dl
```
**Symbols:**

```
ffffffff810af420-ffffffff810af4a2: sched_avg_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sched_avg_update(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b66f0)
Location: kernel/sched/core.c:675
Inline: False
Direct callers:
  - kernel/sched/fair.c:cpu_load_update
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:update_curr_dl
```
**Symbols:**

```
ffffffff810b66f0-ffffffff810b6772: sched_avg_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sched_avg_update(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810be710)
Location: kernel/sched/core.c:653
Inline: False
Direct callers:
  - kernel/sched/fair.c:cpu_load_update
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:update_curr_dl
```
**Symbols:**

```
ffffffff810be710-ffffffff810be792: sched_avg_update (STB_GLOBAL)
```
</details>
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
</ul>
