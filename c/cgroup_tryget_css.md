# Function: <code>cgroup_tryget_css</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8112f27c)
Location: kernel/cgroup/cgroup.c:474
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cpu_stat_show
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8113d72c)
Location: kernel/cgroup/cgroup.c:477
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cpu_stat_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114912c)
Location: kernel/cgroup/cgroup.c:482
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cpu_stat_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115457c)
Location: kernel/cgroup/cgroup.c:484
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cpu_stat_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811601ac)
Location: kernel/cgroup/cgroup.c:484
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cpu_stat_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81171169)
Location: kernel/cgroup/cgroup.c:477
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cpu_stat_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116dd1e)
Location: kernel/cgroup/cgroup.c:474
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cpu_stat_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116e9ae)
Location: kernel/cgroup/cgroup.c:474
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cpu_stat_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81194c0b)
Location: kernel/cgroup/cgroup.c:498
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cpu_stat_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811c5885)
Location: kernel/cgroup/cgroup.c:499
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cpu_stat_show
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81207f95)
Location: kernel/cgroup/cgroup.c:504
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cpu_stat_show
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8121d725)
Location: kernel/cgroup/cgroup.c:503
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cpu_stat_show
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct cgroup_subsys_state *cgroup_tryget_css(struct cgroup *cgrp, struct cgroup_subsys *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81232280)
Location: kernel/cgroup/cgroup.c:3675
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cpu_local_stat_show
  - kernel/cgroup/cgroup.c:cpu_stat_show
```
**Symbols:**

```
ffffffff81232280-ffffffff81232356: cgroup_tryget_css (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d180c)
Location: kernel/cgroup/cgroup.c:484
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cpu_stat_show
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c0414944)
Location: kernel/cgroup/cgroup.c:484
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cpu_stat_show
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c00000000023c3c8)
Location: kernel/cgroup/cgroup.c:484
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cpu_stat_show
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe00014b260)
Location: kernel/cgroup/cgroup.c:484
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cpu_stat_show
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811587cc)
Location: kernel/cgroup/cgroup.c:484
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cpu_stat_show
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114c04c)
Location: kernel/cgroup/cgroup.c:484
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cpu_stat_show
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115659c)
Location: kernel/cgroup/cgroup.c:484
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cpu_stat_show
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81163caf)
Location: kernel/cgroup/cgroup.c:484
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cpu_stat_show
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
