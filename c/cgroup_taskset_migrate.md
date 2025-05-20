# Function: <code>cgroup_taskset_migrate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int cgroup_taskset_migrate(struct cgroup_taskset *tset, struct cgroup *dst_cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff811169e0)
Location: kernel/cgroup.c:2486
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_migrate
  - kernel/cgroup.c:cgroup_update_dfl_csses
```
**Symbols:**

```
ffffffff811169e0-ffffffff81116c78: cgroup_taskset_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cgroup_taskset_migrate(struct cgroup_taskset *tset, struct cgroup_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff8111dc90)
Location: kernel/cgroup.c:2527
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_migrate
```
**Symbols:**

```
ffffffff8111dc90-ffffffff8111dfa3: cgroup_taskset_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cgroup_taskset_migrate(struct cgroup_taskset *tset, struct cgroup_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81125fc0)
Location: kernel/cgroup.c:2532
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_migrate
```
**Symbols:**

```
ffffffff81125fc0-ffffffff811262d3: cgroup_taskset_migrate (STB_LOCAL)
```
</details>
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
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct cgroup_root *root</code>
</li>
<li>
<b>Param removed. </b>
<code>struct cgroup *dst_cgrp</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
