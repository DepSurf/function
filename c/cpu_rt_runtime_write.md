# Function: <code>cpu_rt_runtime_write</code>

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
int cpu_rt_runtime_write(struct cgroup_subsys_state *css, struct cftype *cft, s64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d2e60)
Location: kernel/sched/core.c:7645
Inline: False
```
**Symbols:**

```
ffffffff810d2e60-ffffffff810d2e73: cpu_rt_runtime_write (STB_LOCAL)
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
int cpu_rt_runtime_write(struct cgroup_subsys_state *css, struct cftype *cft, s64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff800010133158)
Location: kernel/sched/core.c:7645
Inline: False
```
**Symbols:**

```
ffff800010133158-ffff80001013318c: cpu_rt_runtime_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cpu_rt_runtime_write(struct cgroup_subsys_state *css, struct cftype *cft, s64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c0382808)
Location: kernel/sched/core.c:7645
Inline: False
```
**Symbols:**

```
c0382808-c0382828: cpu_rt_runtime_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cpu_rt_runtime_write(struct cgroup_subsys_state *css, struct cftype *cft, s64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c00000000017dff0)
Location: kernel/sched/core.c:7645
Inline: False
```
**Symbols:**

```
c00000000017dff0-c00000000017e028: cpu_rt_runtime_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cpu_rt_runtime_write(struct cgroup_subsys_state *css, struct cftype *cft, s64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000e5a48)
Location: kernel/sched/core.c:7645
Inline: False
```
**Symbols:**

```
ffffffe0000e5a48-ffffffe0000e5a7a: cpu_rt_runtime_write (STB_LOCAL)
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
int cpu_rt_runtime_write(struct cgroup_subsys_state *css, struct cftype *cft, s64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bb9e0)
Location: kernel/sched/core.c:7645
Inline: False
```
**Symbols:**

```
ffffffff810bb9e0-ffffffff810bb9f3: cpu_rt_runtime_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cpu_rt_runtime_write(struct cgroup_subsys_state *css, struct cftype *cft, s64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cc4a0)
Location: kernel/sched/core.c:7645
Inline: False
```
**Symbols:**

```
ffffffff810cc4a0-ffffffff810cc4b3: cpu_rt_runtime_write (STB_LOCAL)
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
