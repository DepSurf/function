# Function: <code>cgroup_enable_task_cg_lists</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff811180e5)
Location: kernel/cgroup.c:1872
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff8111fc26)
Location: kernel/cgroup.c:1892
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff8112807b)
Location: kernel/cgroup.c:1900
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81125689)
Location: kernel/cgroup/cgroup.c:1610
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81131955)
Location: kernel/cgroup/cgroup.c:1781
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_mount
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
In kernel/cgroup/cgroup.c (ffffffff81140093)
Location: kernel/cgroup/cgroup.c:1797
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_mount
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
In kernel/cgroup/cgroup.c (ffffffff8114bb03)
Location: kernel/cgroup/cgroup.c:1835
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_mount
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
In kernel/cgroup/cgroup.c (ffffffff811573c9)
Location: kernel/cgroup/cgroup.c:1894
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cgroup_enable_task_cg_lists();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81162f60)
Location: kernel/cgroup/cgroup.c:1894
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff81162f60-ffffffff81163127: cgroup_enable_task_cg_lists (STB_GLOBAL)
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
void cgroup_enable_task_cg_lists();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d45c8)
Location: kernel/cgroup/cgroup.c:1894
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffff8000101d45c8-ffff8000101d4840: cgroup_enable_task_cg_lists (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cgroup_enable_task_cg_lists();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c04171d4)
Location: kernel/cgroup/cgroup.c:1894
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
**Symbols:**

```
c04171d4-c0417400: cgroup_enable_task_cg_lists (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cgroup_enable_task_cg_lists();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c00000000023fb80)
Location: kernel/cgroup/cgroup.c:1894
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
c00000000023fb80-c00000000023fe18: cgroup_enable_task_cg_lists (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cgroup_enable_task_cg_lists();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe00014dac2)
Location: kernel/cgroup/cgroup.c:1894
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
**Symbols:**

```
ffffffe00014dac2-ffffffe00014dcec: cgroup_enable_task_cg_lists (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void cgroup_enable_task_cg_lists();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115b580)
Location: kernel/cgroup/cgroup.c:1894
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff8115b580-ffffffff8115b747: cgroup_enable_task_cg_lists (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cgroup_enable_task_cg_lists();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114e870)
Location: kernel/cgroup/cgroup.c:1894
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff8114e870-ffffffff8114ea31: cgroup_enable_task_cg_lists (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cgroup_enable_task_cg_lists();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81159350)
Location: kernel/cgroup/cgroup.c:1894
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff81159350-ffffffff81159517: cgroup_enable_task_cg_lists (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cgroup_enable_task_cg_lists();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811663d0)
Location: kernel/cgroup/cgroup.c:1894
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff811663d0-ffffffff8116658b: cgroup_enable_task_cg_lists (STB_GLOBAL)
```
</details>
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
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
