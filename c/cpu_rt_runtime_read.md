# Function: <code>cpu_rt_runtime_read</code>

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
s64 cpu_rt_runtime_read(struct cgroup_subsys_state *css, struct cftype *cft);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d2e80)
Location: kernel/sched/core.c:7651
Inline: False
```
**Symbols:**

```
ffffffff810d2e80-ffffffff810d2e90: cpu_rt_runtime_read (STB_LOCAL)
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
s64 cpu_rt_runtime_read(struct cgroup_subsys_state *css, struct cftype *cft);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff800010133190)
Location: kernel/sched/core.c:7651
Inline: False
```
**Symbols:**

```
ffff800010133190-ffff8000101331bc: cpu_rt_runtime_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
s64 cpu_rt_runtime_read(struct cgroup_subsys_state *css, struct cftype *cft);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c0382828)
Location: kernel/sched/core.c:7651
Inline: False
```
**Symbols:**

```
c0382828-c0382848: cpu_rt_runtime_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
s64 cpu_rt_runtime_read(struct cgroup_subsys_state *css, struct cftype *cft);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c00000000017e030)
Location: kernel/sched/core.c:7651
Inline: False
```
**Symbols:**

```
c00000000017e030-c00000000017e064: cpu_rt_runtime_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
s64 cpu_rt_runtime_read(struct cgroup_subsys_state *css, struct cftype *cft);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000e5a7a)
Location: kernel/sched/core.c:7651
Inline: False
```
**Symbols:**

```
ffffffe0000e5a7a-ffffffe0000e5aa4: cpu_rt_runtime_read (STB_LOCAL)
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
s64 cpu_rt_runtime_read(struct cgroup_subsys_state *css, struct cftype *cft);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bba00)
Location: kernel/sched/core.c:7651
Inline: False
```
**Symbols:**

```
ffffffff810bba00-ffffffff810bba10: cpu_rt_runtime_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
s64 cpu_rt_runtime_read(struct cgroup_subsys_state *css, struct cftype *cft);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cc4c0)
Location: kernel/sched/core.c:7651
Inline: False
```
**Symbols:**

```
ffffffff810cc4c0-ffffffff810cc4d0: cpu_rt_runtime_read (STB_LOCAL)
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
