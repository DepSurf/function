# Function: <code>sched_core_lock</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sched_core_lock(int cpu, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810f1740)
Location: kernel/sched/core.c:240
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_core_cpu_starting
  - kernel/sched/core.c:__sched_core_flip
```
**Symbols:**

```
ffffffff810f1740-ffffffff810f17f6: sched_core_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sched_core_lock(int cpu, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8110a7c0)
Location: kernel/sched/core.c:314
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_core_cpu_starting
  - kernel/sched/core.c:__sched_core_flip
```
**Symbols:**

```
ffffffff8110a7c0-ffffffff8110a881: sched_core_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sched_core_lock(int cpu, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81133620)
Location: kernel/sched/core.c:311
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_core_cpu_deactivate
  - kernel/sched/core.c:sched_core_cpu_starting
  - kernel/sched/core.c:__sched_core_flip
```
**Symbols:**

```
ffffffff81133620-ffffffff811336ee: sched_core_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sched_core_lock(int cpu, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81141f10)
Location: kernel/sched/core.c:332
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_core_cpu_deactivate
  - kernel/sched/core.c:sched_core_cpu_starting
  - kernel/sched/core.c:__sched_core_flip
```
**Symbols:**

```
ffffffff81141f10-ffffffff81141fde: sched_core_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sched_core_lock(int cpu, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8114d210)
Location: kernel/sched/core.c:333
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_core_cpu_deactivate
  - kernel/sched/core.c:sched_core_cpu_starting
  - kernel/sched/core.c:__sched_core_flip
```
**Symbols:**

```
ffffffff8114d210-ffffffff8114d2de: sched_core_lock (STB_LOCAL)
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
