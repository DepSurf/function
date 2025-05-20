# Function: <code>cpu_cfs_burst_write_u64</code>

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
int cpu_cfs_burst_write_u64(struct cgroup_subsys_state *css, struct cftype *cftype, u64 cfs_burst_us);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810f2ef0)
Location: kernel/sched/core.c:10398
Inline: False
```
**Symbols:**

```
ffffffff810f2ef0-ffffffff810f2f2a: cpu_cfs_burst_write_u64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cpu_cfs_burst_write_u64(struct cgroup_subsys_state *css, struct cftype *cftype, u64 cfs_burst_us);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8110ecb0)
Location: kernel/sched/core.c:10721
Inline: False
```
**Symbols:**

```
ffffffff8110ecb0-ffffffff8110ed02: cpu_cfs_burst_write_u64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cpu_cfs_burst_write_u64(struct cgroup_subsys_state *css, struct cftype *cftype, u64 cfs_burst_us);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81135a80)
Location: kernel/sched/core.c:10867
Inline: False
```
**Symbols:**

```
ffffffff81135a80-ffffffff81135ad2: cpu_cfs_burst_write_u64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cpu_cfs_burst_write_u64(struct cgroup_subsys_state *css, struct cftype *cftype, u64 cfs_burst_us);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81144c20)
Location: kernel/sched/core.c:11027
Inline: False
```
**Symbols:**

```
ffffffff81144c20-ffffffff81144c72: cpu_cfs_burst_write_u64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cpu_cfs_burst_write_u64(struct cgroup_subsys_state *css, struct cftype *cftype, u64 cfs_burst_us);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81150140)
Location: kernel/sched/core.c:10984
Inline: False
```
**Symbols:**

```
ffffffff81150140-ffffffff81150192: cpu_cfs_burst_write_u64 (STB_LOCAL)
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
