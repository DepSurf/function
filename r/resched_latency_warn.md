# Function: <code>resched_latency_warn</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void resched_latency_warn(int cpu, u64 latency);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff81109360)
Location: kernel/sched/debug.c:1051
Inline: False
Direct callers:
  - kernel/sched/core.c:scheduler_tick
```
**Symbols:**

```
ffffffff81109360-ffffffff811093c3: resched_latency_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void resched_latency_warn(int cpu, u64 latency);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff811274d0)
Location: kernel/sched/debug.c:1067
Inline: False
Direct callers:
  - kernel/sched/core.c:scheduler_tick
```
**Symbols:**

```
ffffffff811274d0-ffffffff81127556: resched_latency_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void resched_latency_warn(int cpu, u64 latency);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81147d50)
Location: kernel/sched/debug.c:1071
Inline: False
Direct callers:
  - kernel/sched/core.c:scheduler_tick
```
**Symbols:**

```
ffffffff81147d50-ffffffff81147df3: resched_latency_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void resched_latency_warn(int cpu, u64 latency);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811764a0)
Location: kernel/sched/debug.c:1072
Inline: False
Direct callers:
  - kernel/sched/core.c:scheduler_tick
```
**Symbols:**

```
ffffffff811764a0-ffffffff81176543: resched_latency_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void resched_latency_warn(int cpu, u64 latency);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811870d0)
Location: kernel/sched/debug.c:1118
Inline: False
Direct callers:
  - kernel/sched/core.c:scheduler_tick
```
**Symbols:**

```
ffffffff811870d0-ffffffff81187173: resched_latency_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void resched_latency_warn(int cpu, u64 latency);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81195800)
Location: kernel/sched/debug.c:1114
Inline: False
Direct callers:
  - kernel/sched/core.c:scheduler_tick
```
**Symbols:**

```
ffffffff81195800-ffffffff811958a3: resched_latency_warn (STB_GLOBAL)
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
