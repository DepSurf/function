# Function: <code>sched_group_set_rt_runtime</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sched_group_set_rt_runtime(struct task_group *tg, long int rt_runtime_us);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f03a0)
Location: kernel/sched/rt.c:2541
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_rt_runtime_write
```
**Symbols:**

```
ffffffff810f03a0-ffffffff810f03f0: sched_group_set_rt_runtime (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int sched_group_set_rt_runtime(struct task_group *tg, long int rt_runtime_us);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffff8000101519e0)
Location: kernel/sched/rt.c:2541
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_rt_runtime_write
```
**Symbols:**

```
ffff8000101519e0-ffff800010151a50: sched_group_set_rt_runtime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sched_group_set_rt_runtime(struct task_group *tg, long int rt_runtime_us);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c039ec40)
Location: kernel/sched/rt.c:2541
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_rt_runtime_write
```
**Symbols:**

```
c039ec40-c039ec84: sched_group_set_rt_runtime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sched_group_set_rt_runtime(struct task_group *tg, long int rt_runtime_us);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c0000000001a5360)
Location: kernel/sched/rt.c:2541
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_rt_runtime_write
```
**Symbols:**

```
c0000000001a5360-c0000000001a53b0: sched_group_set_rt_runtime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sched_group_set_rt_runtime(struct task_group *tg, long int rt_runtime_us);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffe0000f9c34)
Location: kernel/sched/rt.c:2541
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_rt_runtime_write
```
**Symbols:**

```
ffffffe0000f9c34-ffffffe0000f9c88: sched_group_set_rt_runtime (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sched_group_set_rt_runtime(struct task_group *tg, long int rt_runtime_us);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810d9760)
Location: kernel/sched/rt.c:2541
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_rt_runtime_write
```
**Symbols:**

```
ffffffff810d9760-ffffffff810d97b0: sched_group_set_rt_runtime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sched_group_set_rt_runtime(struct task_group *tg, long int rt_runtime_us);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e68d0)
Location: kernel/sched/rt.c:2541
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_rt_runtime_write
```
**Symbols:**

```
ffffffff810e68d0-ffffffff810e6920: sched_group_set_rt_runtime (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
</ul>
