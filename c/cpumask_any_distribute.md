# Function: <code>cpumask_any_distribute</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cpumask_any_distribute(const struct cpumask *srcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff8160d240)
Location: lib/cpumask.c:265
Inline: False
Direct callers:
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/deadline.c:find_later_rq
```
**Symbols:**

```
ffffffff8160d240-ffffffff8160d292: cpumask_any_distribute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cpumask_any_distribute(const struct cpumask *srcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff815f06e0)
Location: lib/cpumask.c:265
Inline: False
Direct callers:
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/deadline.c:find_later_rq
```
**Symbols:**

```
ffffffff815f06e0-ffffffff815f0746: cpumask_any_distribute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cpumask_any_distribute(const struct cpumask *srcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff8165d7c0)
Location: lib/cpumask.c:265
Inline: False
Direct callers:
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/deadline.c:find_later_rq
```
**Symbols:**

```
ffffffff8165d7c0-ffffffff8165d826: cpumask_any_distribute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cpumask_any_distribute(const struct cpumask *srcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81776dc0)
Location: lib/cpumask.c:265
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:find_later_rq
  - kernel/sched/build_policy.c:find_lowest_rq
```
**Symbols:**

```
ffffffff81776dc0-ffffffff81776e3d: cpumask_any_distribute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int cpumask_any_distribute(const struct cpumask *srcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff8201f840)
Location: lib/cpumask.c:178
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:find_later_rq
  - kernel/sched/build_policy.c:find_lowest_rq
```
**Symbols:**

```
ffffffff8201f840-ffffffff8201f8aa: cpumask_any_distribute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int cpumask_any_distribute(const struct cpumask *srcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff8209f850)
Location: lib/cpumask.c:187
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:find_later_rq
  - kernel/sched/build_policy.c:find_lowest_rq
  - kernel/bpf/cpumask.c:bpf_cpumask_any_distribute
```
**Symbols:**

```
ffffffff8209f850-ffffffff8209f8ba: cpumask_any_distribute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int cpumask_any_distribute(const struct cpumask *srcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff821778b0)
Location: lib/cpumask.c:192
Inline: False
Direct callers:
  - kernel/workqueue.c:kick_pool
  - kernel/sched/build_policy.c:find_later_rq
  - kernel/sched/build_policy.c:find_lowest_rq
  - kernel/bpf/cpumask.c:bpf_cpumask_any_distribute
```
**Symbols:**

```
ffffffff821778b0-ffffffff8217791a: cpumask_any_distribute (STB_GLOBAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>unsigned int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
