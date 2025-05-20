# Function: <code>cpu_rt_period_write_uint</code>

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
int cpu_rt_period_write_uint(struct cgroup_subsys_state *css, struct cftype *cftype, u64 rt_period_us);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d2e30)
Location: kernel/sched/core.c:7657
Inline: False
```
**Symbols:**

```
ffffffff810d2e30-ffffffff810d2e43: cpu_rt_period_write_uint (STB_LOCAL)
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
int cpu_rt_period_write_uint(struct cgroup_subsys_state *css, struct cftype *cftype, u64 rt_period_us);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff8000101330f0)
Location: kernel/sched/core.c:7657
Inline: False
```
**Symbols:**

```
ffff8000101330f0-ffff800010133124: cpu_rt_period_write_uint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cpu_rt_period_write_uint(struct cgroup_subsys_state *css, struct cftype *cftype, u64 rt_period_us);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c03827cc)
Location: kernel/sched/core.c:7657
Inline: False
```
**Symbols:**

```
c03827cc-c03827e8: cpu_rt_period_write_uint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cpu_rt_period_write_uint(struct cgroup_subsys_state *css, struct cftype *cftype, u64 rt_period_us);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c00000000017df70)
Location: kernel/sched/core.c:7657
Inline: False
```
**Symbols:**

```
c00000000017df70-c00000000017dfa8: cpu_rt_period_write_uint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cpu_rt_period_write_uint(struct cgroup_subsys_state *css, struct cftype *cftype, u64 rt_period_us);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000e59ec)
Location: kernel/sched/core.c:7657
Inline: False
```
**Symbols:**

```
ffffffe0000e59ec-ffffffe0000e5a1e: cpu_rt_period_write_uint (STB_LOCAL)
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
int cpu_rt_period_write_uint(struct cgroup_subsys_state *css, struct cftype *cftype, u64 rt_period_us);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bb9b0)
Location: kernel/sched/core.c:7657
Inline: False
```
**Symbols:**

```
ffffffff810bb9b0-ffffffff810bb9c3: cpu_rt_period_write_uint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cpu_rt_period_write_uint(struct cgroup_subsys_state *css, struct cftype *cftype, u64 rt_period_us);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cc470)
Location: kernel/sched/core.c:7657
Inline: False
```
**Symbols:**

```
ffffffff810cc470-ffffffff810cc483: cpu_rt_period_write_uint (STB_LOCAL)
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
