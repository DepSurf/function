# Function: <code>sched_group_rt_period</code>

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
long int sched_group_rt_period(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f0470)
Location: kernel/sched/rt.c:2580
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_rt_period_read_uint
```
**Symbols:**

```
ffffffff810f0470-ffffffff810f049d: sched_group_rt_period (STB_GLOBAL)
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
long int sched_group_rt_period(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffff800010151b08)
Location: kernel/sched/rt.c:2580
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_rt_period_read_uint
```
**Symbols:**

```
ffff800010151b08-ffff800010151b4c: sched_group_rt_period (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int sched_group_rt_period(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c039eda0)
Location: kernel/sched/rt.c:2580
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_rt_period_read_uint
```
**Symbols:**

```
c039eda0-c039ee08: sched_group_rt_period (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int sched_group_rt_period(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c0000000001a5440)
Location: kernel/sched/rt.c:2580
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_rt_period_read_uint
```
**Symbols:**

```
c0000000001a5440-c0000000001a5470: sched_group_rt_period (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int sched_group_rt_period(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffe0000f9d0a)
Location: kernel/sched/rt.c:2580
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_rt_period_read_uint
```
**Symbols:**

```
ffffffe0000f9d0a-ffffffe0000f9d36: sched_group_rt_period (STB_GLOBAL)
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
long int sched_group_rt_period(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810d9830)
Location: kernel/sched/rt.c:2580
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_rt_period_read_uint
```
**Symbols:**

```
ffffffff810d9830-ffffffff810d985d: sched_group_rt_period (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int sched_group_rt_period(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e69a0)
Location: kernel/sched/rt.c:2580
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_rt_period_read_uint
```
**Symbols:**

```
ffffffff810e69a0-ffffffff810e69cd: sched_group_rt_period (STB_GLOBAL)
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
