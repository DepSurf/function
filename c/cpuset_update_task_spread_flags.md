# Function: <code>cpuset_update_task_spread_flags</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8121a86c)
Location: kernel/cgroup/cpuset.c:556
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_flags
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_flags
```
**Symbols:**

```
ffffffff81218120-ffffffff81218179: cpuset_update_task_spread_flags.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8123041f)
Location: kernel/cgroup/cpuset.c:556
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_attach_task
  - kernel/cgroup/cpuset.c:update_tasks_flags
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach_task
  - kernel/cgroup/cpuset.c:update_tasks_flags
```
**Symbols:**

```
ffffffff8122d880-ffffffff8122d8d9: cpuset_update_task_spread_flags.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81248eaf)
Location: kernel/cgroup/cpuset.c:586
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_attach_task
  - kernel/cgroup/cpuset.c:update_tasks_flags
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach_task
  - kernel/cgroup/cpuset.c:update_tasks_flags
```
**Symbols:**

```
ffffffff81245bd0-ffffffff81245c29: cpuset_update_task_spread_flags.part.0 (STB_LOCAL)
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
