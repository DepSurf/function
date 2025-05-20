# Function: <code>cgroup_psi_enabled</code>

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
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_psi_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81191a81)
Location: kernel/cgroup/cgroup.c:3700
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:show_delegatable_files
  - kernel/cgroup/cgroup.c:cgroup_init_cftypes
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
Direct callers:
  - kernel/sched/psi.c:psi_init
```
**Symbols:**

```
ffffffff81197ba0-ffffffff81197bb7: cgroup_psi_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_psi_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811c1411)
Location: kernel/cgroup/cgroup.c:3711
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:show_delegatable_files
  - kernel/cgroup/cgroup.c:cgroup_init_cftypes
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
Direct callers:
  - kernel/sched/build_utility.c:psi_init
```
**Symbols:**

```
ffffffff811c7c10-ffffffff811c7c2b: cgroup_psi_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_psi_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81206ca2)
Location: kernel/cgroup/cgroup.c:3877
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:delegate_show
  - kernel/cgroup/cgroup.c:delegate_show
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
Direct callers:
  - kernel/sched/build_utility.c:psi_init
```
**Symbols:**

```
ffffffff8120ab60-ffffffff8120ab85: cgroup_psi_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_psi_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8121c862)
Location: kernel/cgroup/cgroup.c:3854
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:delegate_show
  - kernel/cgroup/cgroup.c:delegate_show
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
Direct callers:
  - kernel/sched/build_utility.c:psi_init
```
**Symbols:**

```
ffffffff81220140-ffffffff81220165: cgroup_psi_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_psi_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff812343f2)
Location: kernel/cgroup/cgroup.c:3908
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:delegate_show
  - kernel/cgroup/cgroup.c:delegate_show
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
Direct callers:
  - kernel/sched/build_utility.c:psi_init
```
**Symbols:**

```
ffffffff81237e90-ffffffff81237eb5: cgroup_psi_enabled (STB_GLOBAL)
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
