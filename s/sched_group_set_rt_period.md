# Function: <code>sched_group_set_rt_period</code>

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
int sched_group_set_rt_period(struct task_group *tg, u64 rt_period_us);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f0430)
Location: kernel/sched/rt.c:2567
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_rt_period_write_uint
```
**Symbols:**

```
ffffffff810f0430-ffffffff810f0463: sched_group_set_rt_period (STB_GLOBAL)
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
int sched_group_set_rt_period(struct task_group *tg, u64 rt_period_us);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffff800010151aa0)
Location: kernel/sched/rt.c:2567
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_rt_period_write_uint
```
**Symbols:**

```
ffff800010151aa0-ffff800010151b04: sched_group_set_rt_period (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sched_group_set_rt_period(struct task_group *tg, u64 rt_period_us);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c039ed08)
Location: kernel/sched/rt.c:2567
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_rt_period_write_uint
```
**Symbols:**

```
c039ed08-c039eda0: sched_group_set_rt_period (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sched_group_set_rt_period(struct task_group *tg, u64 rt_period_us);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c0000000001a53f0)
Location: kernel/sched/rt.c:2567
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_rt_period_write_uint
```
**Symbols:**

```
c0000000001a53f0-c0000000001a5438: sched_group_set_rt_period (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sched_group_set_rt_period(struct task_group *tg, u64 rt_period_us);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffe0000f9cbe)
Location: kernel/sched/rt.c:2567
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_rt_period_write_uint
```
**Symbols:**

```
ffffffe0000f9cbe-ffffffe0000f9d0a: sched_group_set_rt_period (STB_GLOBAL)
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
int sched_group_set_rt_period(struct task_group *tg, u64 rt_period_us);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810d97f0)
Location: kernel/sched/rt.c:2567
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_rt_period_write_uint
```
**Symbols:**

```
ffffffff810d97f0-ffffffff810d9823: sched_group_set_rt_period (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sched_group_set_rt_period(struct task_group *tg, u64 rt_period_us);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e6960)
Location: kernel/sched/rt.c:2567
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_rt_period_write_uint
```
**Symbols:**

```
ffffffff810e6960-ffffffff810e6993: sched_group_set_rt_period (STB_GLOBAL)
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
