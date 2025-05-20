# Function: <code>cgroup_procs_write_start</code>

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
<summary>In <code>4.15</code>: ✅</summary>

```c
struct task_struct *cgroup_procs_write_start(char *buf, bool threadgroup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81130e30)
Location: kernel/cgroup/cgroup.c:2628
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
**Symbols:**

```
ffffffff81130e30-ffffffff81130efd: cgroup_procs_write_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct task_struct *cgroup_procs_write_start(char *buf, bool threadgroup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8113f500)
Location: kernel/cgroup/cgroup.c:2646
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
**Symbols:**

```
ffffffff8113f500-ffffffff8113f5cf: cgroup_procs_write_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct task_struct *cgroup_procs_write_start(char *buf, bool threadgroup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114af20)
Location: kernel/cgroup/cgroup.c:2687
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
**Symbols:**

```
ffffffff8114af20-ffffffff8114afef: cgroup_procs_write_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct task_struct *cgroup_procs_write_start(char *buf, bool threadgroup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81156700)
Location: kernel/cgroup/cgroup.c:2827
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
**Symbols:**

```
ffffffff81156700-ffffffff811567da: cgroup_procs_write_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct task_struct *cgroup_procs_write_start(char *buf, bool threadgroup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81162360)
Location: kernel/cgroup/cgroup.c:2828
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
**Symbols:**

```
ffffffff81162360-ffffffff8116243a: cgroup_procs_write_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct task_struct *cgroup_procs_write_start(char *buf, bool threadgroup, bool *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811737c0)
Location: kernel/cgroup/cgroup.c:2750
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
**Symbols:**

```
ffffffff811737c0-ffffffff811738ed: cgroup_procs_write_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct task_struct *cgroup_procs_write_start(char *buf, bool threadgroup, bool *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811704c0)
Location: kernel/cgroup/cgroup.c:2746
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
**Symbols:**

```
ffffffff811704c0-ffffffff811705e5: cgroup_procs_write_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct task_struct *cgroup_procs_write_start(char *buf, bool threadgroup, bool *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811710f0)
Location: kernel/cgroup/cgroup.c:2759
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
```
**Symbols:**

```
ffffffff811710f0-ffffffff81171216: cgroup_procs_write_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct task_struct *cgroup_procs_write_start(char *buf, bool threadgroup, bool *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:2814
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
```
**Symbols:**

```
ffffffff81cb2f24-ffffffff81cb2f38: cgroup_procs_write_start.cold (STB_LOCAL)
ffffffff811979d0-ffffffff81197b02: cgroup_procs_write_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct task_struct *cgroup_procs_write_start(char *buf, bool threadgroup, bool *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:2824
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
```
**Symbols:**

```
ffffffff81e63d08-ffffffff81e63d1d: cgroup_procs_write_start.cold (STB_LOCAL)
ffffffff811c79e0-ffffffff811c7b6b: cgroup_procs_write_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct task_struct *cgroup_procs_write_start(char *buf, bool threadgroup, bool *threadgroup_locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:2920
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
```
**Symbols:**

```
ffffffff8205c19e-ffffffff8205c1c7: cgroup_procs_write_start.cold (STB_LOCAL)
ffffffff8120a910-ffffffff8120aa93: cgroup_procs_write_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct task_struct *cgroup_procs_write_start(char *buf, bool threadgroup, bool *threadgroup_locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:2889
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
```
**Symbols:**

```
ffffffff820da994-ffffffff820da9bd: cgroup_procs_write_start.cold (STB_LOCAL)
ffffffff8121fef0-ffffffff81220073: cgroup_procs_write_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct task_struct *cgroup_procs_write_start(char *buf, bool threadgroup, bool *threadgroup_locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:2898
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
```
**Symbols:**

```
ffffffff821b6612-ffffffff821b663b: cgroup_procs_write_start.cold (STB_LOCAL)
ffffffff81237c40-ffffffff81237dc3: cgroup_procs_write_start (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct task_struct *cgroup_procs_write_start(char *buf, bool threadgroup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d3828)
Location: kernel/cgroup/cgroup.c:2828
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
**Symbols:**

```
ffff8000101d3828-ffff8000101d390c: cgroup_procs_write_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct task_struct *cgroup_procs_write_start(char *buf, bool threadgroup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c04164a0)
Location: kernel/cgroup/cgroup.c:2828
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
**Symbols:**

```
c04164a0-c0416598: cgroup_procs_write_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct task_struct *cgroup_procs_write_start(char *buf, bool threadgroup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c00000000023ea60)
Location: kernel/cgroup/cgroup.c:2828
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
**Symbols:**

```
c00000000023ea60-c00000000023eba4: cgroup_procs_write_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct task_struct *cgroup_procs_write_start(char *buf, bool threadgroup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe00014cf20)
Location: kernel/cgroup/cgroup.c:2828
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
**Symbols:**

```
ffffffe00014cf20-ffffffe00014cfd0: cgroup_procs_write_start (STB_GLOBAL)
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
struct task_struct *cgroup_procs_write_start(char *buf, bool threadgroup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115a980)
Location: kernel/cgroup/cgroup.c:2828
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
**Symbols:**

```
ffffffff8115a980-ffffffff8115aa5a: cgroup_procs_write_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct task_struct *cgroup_procs_write_start(char *buf, bool threadgroup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114dc70)
Location: kernel/cgroup/cgroup.c:2828
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
**Symbols:**

```
ffffffff8114dc70-ffffffff8114dd4a: cgroup_procs_write_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct task_struct *cgroup_procs_write_start(char *buf, bool threadgroup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81158750)
Location: kernel/cgroup/cgroup.c:2828
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
**Symbols:**

```
ffffffff81158750-ffffffff8115882a: cgroup_procs_write_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct task_struct *cgroup_procs_write_start(char *buf, bool threadgroup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811657a0)
Location: kernel/cgroup/cgroup.c:2828
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
**Symbols:**

```
ffffffff811657a0-ffffffff81165884: cgroup_procs_write_start (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool *locked</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool *threadgroup_locked</code>
</li>
<li>
<b>Param removed. </b>
<code>bool *locked</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
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
