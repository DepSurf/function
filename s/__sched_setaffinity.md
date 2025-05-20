# Function: <code>__sched_setaffinity</code>

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
int __sched_setaffinity(struct task_struct *p, const struct cpumask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810fc320)
Location: kernel/sched/core.c:7948
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:relax_compatible_cpus_allowed_ptr
```
**Symbols:**

```
ffffffff810fc320-ffffffff810fc464: __sched_setaffinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __sched_setaffinity(struct task_struct *p, const struct cpumask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811188c0)
Location: kernel/sched/core.c:8056
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:relax_compatible_cpus_allowed_ptr
```
**Symbols:**

```
ffffffff811188c0-ffffffff81118a39: __sched_setaffinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __sched_setaffinity(struct task_struct *p, struct affinity_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8113ffd0)
Location: kernel/sched/core.c:8198
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:relax_compatible_cpus_allowed_ptr
```
**Symbols:**

```
ffffffff8113ffd0-ffffffff81140176: __sched_setaffinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __sched_setaffinity(struct task_struct *p, struct affinity_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:8307
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:relax_compatible_cpus_allowed_ptr
```
**Symbols:**

```
ffffffff8114f2e0-ffffffff8114f4dc: __sched_setaffinity (STB_LOCAL)
ffffffff820d52d9-ffffffff820d52f4: __sched_setaffinity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __sched_setaffinity(struct task_struct *p, struct affinity_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:8336
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:relax_compatible_cpus_allowed_ptr
```
**Symbols:**

```
ffffffff8115b180-ffffffff8115b37c: __sched_setaffinity (STB_LOCAL)
ffffffff821b0251-ffffffff821b026c: __sched_setaffinity.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct affinity_context *ctx</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct cpumask *mask</code>
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
