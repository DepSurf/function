# Function: <code>tg_set_rt_bandwidth</code>

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
int tg_set_rt_bandwidth(struct task_group *tg, u64 rt_period, u64 rt_runtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810edfa0)
Location: kernel/sched/rt.c:2500
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_group_set_rt_period
  - kernel/sched/rt.c:sched_group_set_rt_runtime
  - kernel/sched/rt.c:sched_group_set_rt_runtime
```
**Symbols:**

```
ffffffff810edfa0-ffffffff810ee109: tg_set_rt_bandwidth (STB_LOCAL)
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
int tg_set_rt_bandwidth(struct task_group *tg, u64 rt_period, u64 rt_runtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffff80001014efb0)
Location: kernel/sched/rt.c:2500
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_group_set_rt_period
  - kernel/sched/rt.c:sched_group_set_rt_runtime
```
**Symbols:**

```
ffff80001014efb0-ffff80001014f224: tg_set_rt_bandwidth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tg_set_rt_bandwidth(struct task_group *tg, u64 rt_period, u64 rt_runtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c039c7a8)
Location: kernel/sched/rt.c:2500
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_group_set_rt_period
  - kernel/sched/rt.c:sched_group_set_rt_runtime
```
**Symbols:**

```
c039c7a8-c039c978: tg_set_rt_bandwidth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tg_set_rt_bandwidth(struct task_group *tg, u64 rt_period, u64 rt_runtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c0000000001a1290)
Location: kernel/sched/rt.c:2500
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_group_set_rt_period
  - kernel/sched/rt.c:sched_group_set_rt_runtime
  - kernel/sched/rt.c:sched_group_set_rt_runtime
```
**Symbols:**

```
c0000000001a1290-c0000000001a1518: tg_set_rt_bandwidth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tg_set_rt_bandwidth(struct task_group *tg, u64 rt_period, u64 rt_runtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffe0000f7918)
Location: kernel/sched/rt.c:2500
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_group_set_rt_period
  - kernel/sched/rt.c:sched_group_set_rt_runtime
```
**Symbols:**

```
ffffffe0000f7918-ffffffe0000f7ac6: tg_set_rt_bandwidth (STB_LOCAL)
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
int tg_set_rt_bandwidth(struct task_group *tg, u64 rt_period, u64 rt_runtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810d72f0)
Location: kernel/sched/rt.c:2500
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_group_set_rt_period
  - kernel/sched/rt.c:sched_group_set_rt_runtime
  - kernel/sched/rt.c:sched_group_set_rt_runtime
```
**Symbols:**

```
ffffffff810d72f0-ffffffff810d7453: tg_set_rt_bandwidth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tg_set_rt_bandwidth(struct task_group *tg, u64 rt_period, u64 rt_runtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e44d0)
Location: kernel/sched/rt.c:2500
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_group_set_rt_period
  - kernel/sched/rt.c:sched_group_set_rt_runtime
  - kernel/sched/rt.c:sched_group_set_rt_runtime
```
**Symbols:**

```
ffffffff810e44d0-ffffffff810e4639: tg_set_rt_bandwidth (STB_LOCAL)
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
