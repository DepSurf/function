# Function: <code>__cgroup_procs_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t __cgroup_procs_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81116f10)
Location: kernel/cgroup.c:2824
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_tasks_write
  - kernel/cgroup.c:cgroup_procs_write
```
**Symbols:**

```
ffffffff81116f10-ffffffff811171e8: __cgroup_procs_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup.c (ffffffff8111e290)
Location: kernel/cgroup.c:2882
Inline: True
Direct callers:
  - kernel/cgroup.c:cgroup_procs_write
  - kernel/cgroup.c:cgroup_tasks_write
```
**Symbols:**

```
ffffffff8111e290-ffffffff8111e592: __cgroup_procs_write.constprop.31 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup.c (ffffffff81126620)
Location: kernel/cgroup.c:2891
Inline: True
Direct callers:
  - kernel/cgroup.c:cgroup_procs_write
  - kernel/cgroup.c:cgroup_tasks_write
```
**Symbols:**

```
ffffffff81126620-ffffffff81126922: __cgroup_procs_write.constprop.37 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t __cgroup_procs_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off, bool threadgroup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811272f0)
Location: kernel/cgroup/cgroup.c:2485
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup-v1.c:cgroup_tasks_write
```
**Symbols:**

```
ffffffff811272f0-ffffffff81127672: __cgroup_procs_write (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t __cgroup_procs_write(struct kernfs_open_file *of, char *buf, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81173c50)
Location: kernel/cgroup/cgroup.c:4744
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
**Symbols:**

```
ffffffff81173c50-ffffffff81173d8c: __cgroup_procs_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t __cgroup_procs_write(struct kernfs_open_file *of, char *buf, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:4917
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
**Symbols:**

```
ffffffff8119aca0-ffffffff8119ae17: __cgroup_procs_write (STB_LOCAL)
ffffffff81cb3069-ffffffff81cb307e: __cgroup_procs_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t __cgroup_procs_write(struct kernfs_open_file *of, char *buf, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:4928
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
**Symbols:**

```
ffffffff811cae40-ffffffff811cafc3: __cgroup_procs_write (STB_LOCAL)
ffffffff81e63e57-ffffffff81e63e6c: __cgroup_procs_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t __cgroup_procs_write(struct kernfs_open_file *of, char *buf, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:5125
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
**Symbols:**

```
ffffffff8120e240-ffffffff8120e3c3: __cgroup_procs_write (STB_LOCAL)
ffffffff8205c2f5-ffffffff8205c30a: __cgroup_procs_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t __cgroup_procs_write(struct kernfs_open_file *of, char *buf, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:5102
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
**Symbols:**

```
ffffffff81223c50-ffffffff81223dcc: __cgroup_procs_write (STB_LOCAL)
ffffffff820dab0f-ffffffff820dab24: __cgroup_procs_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t __cgroup_procs_write(struct kernfs_open_file *of, char *buf, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:5138
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
**Symbols:**

```
ffffffff8123b940-ffffffff8123baa8: __cgroup_procs_write (STB_LOCAL)
ffffffff821b678d-ffffffff821b67a2: __cgroup_procs_write.cold (STB_LOCAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
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
