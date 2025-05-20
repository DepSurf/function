# Function: <code>task_function_call</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int task_function_call(struct task_struct *p, remote_function_f func, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81178980)
Location: kernel/events/core.c:91
Inline: False
Direct callers:
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:_perf_event_enable
  - kernel/events/core.c:perf_remove_from_context
  - kernel/events/core.c:perf_ioctl
```
**Symbols:**

```
ffffffff81178980-ffffffff811789f1: task_function_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int task_function_call(struct task_struct *p, remote_function_f func, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811890c0)
Location: kernel/events/core.c:100
Inline: False
Direct callers:
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:event_function_call
```
**Symbols:**

```
ffffffff811890c0-ffffffff81189137: task_function_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int task_function_call(struct task_struct *p, remote_function_f func, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81198490)
Location: kernel/events/core.c:100
Inline: False
Direct callers:
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
```
**Symbols:**

```
ffffffff81198490-ffffffff81198503: task_function_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int task_function_call(struct task_struct *p, remote_function_f func, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a0190)
Location: kernel/events/core.c:104
Inline: False
Direct callers:
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
```
**Symbols:**

```
ffffffff811a0190-ffffffff811a0204: task_function_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int task_function_call(struct task_struct *p, remote_function_f func, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b3ac0)
Location: kernel/events/core.c:104
Inline: False
Direct callers:
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
```
**Symbols:**

```
ffffffff811b3ac0-ffffffff811b3b34: task_function_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int task_function_call(struct task_struct *p, remote_function_f func, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d2fc0)
Location: kernel/events/core.c:104
Inline: False
Direct callers:
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
```
**Symbols:**

```
ffffffff811d2fc0-ffffffff811d3034: task_function_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int task_function_call(struct task_struct *p, remote_function_f func, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e32b0)
Location: kernel/events/core.c:104
Inline: False
Direct callers:
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
```
**Symbols:**

```
ffffffff811e32b0-ffffffff811e3324: task_function_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int task_function_call(struct task_struct *p, remote_function_f func, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fa490)
Location: kernel/events/core.c:103
Inline: False
Direct callers:
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
```
**Symbols:**

```
ffffffff811fa490-ffffffff811fa4fc: task_function_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int task_function_call(struct task_struct *p, remote_function_f func, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81207560)
Location: kernel/events/core.c:103
Inline: False
Direct callers:
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
```
**Symbols:**

```
ffffffff81207560-ffffffff812075cc: task_function_call (STB_LOCAL)
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
In kernel/events/core.c (ffffffff8123298e)
Location: kernel/events/core.c:105
Inline: True
Inline callers:
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
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
In kernel/events/core.c (ffffffff8123c60e)
Location: kernel/events/core.c:107
Inline: True
Inline callers:
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
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
In kernel/events/core.c (ffffffff81240cbe)
Location: kernel/events/core.c:108
Inline: True
Inline callers:
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
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
In kernel/events/core.c (ffffffff8127b6ae)
Location: kernel/events/core.c:108
Inline: True
Inline callers:
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
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
In kernel/events/core.c (ffffffff812cf573)
Location: kernel/events/core.c:108
Inline: True
Inline callers:
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
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
In kernel/events/core.c (ffffffff81337843)
Location: kernel/events/core.c:109
Inline: True
Inline callers:
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
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
In kernel/events/core.c (ffffffff81368613)
Location: kernel/events/core.c:109
Inline: True
Inline callers:
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81391533)
Location: kernel/events/core.c:109
Inline: True
Inline callers:
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
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
int task_function_call(struct task_struct *p, remote_function_f func, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff800010290f60)
Location: kernel/events/core.c:103
Inline: False
Direct callers:
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
  - kernel/events/core.c:event_function_call
```
**Symbols:**

```
ffff800010290f60-ffff800010290ff0: task_function_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int task_function_call(struct task_struct *p, remote_function_f func, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c0ce8)
Location: kernel/events/core.c:103
Inline: False
Direct callers:
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
```
**Symbols:**

```
c04c0ce8-c04c0d78: task_function_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int task_function_call(struct task_struct *p, remote_function_f func, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c00000000033ead0)
Location: kernel/events/core.c:103
Inline: False
Direct callers:
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
```
**Symbols:**

```
c00000000033ead0-c00000000033eb84: task_function_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int task_function_call(struct task_struct *p, remote_function_f func, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c3b7e)
Location: kernel/events/core.c:103
Inline: False
Direct callers:
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
```
**Symbols:**

```
ffffffe0001c3b7e-ffffffe0001c3bd6: task_function_call (STB_LOCAL)
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
int task_function_call(struct task_struct *p, remote_function_f func, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ffb80)
Location: kernel/events/core.c:103
Inline: False
Direct callers:
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
```
**Symbols:**

```
ffffffff811ffb80-ffffffff811ffbec: task_function_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int task_function_call(struct task_struct *p, remote_function_f func, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f28d0)
Location: kernel/events/core.c:103
Inline: False
Direct callers:
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
```
**Symbols:**

```
ffffffff811f28d0-ffffffff811f293c: task_function_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int task_function_call(struct task_struct *p, remote_function_f func, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fd950)
Location: kernel/events/core.c:103
Inline: False
Direct callers:
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
```
**Symbols:**

```
ffffffff811fd950-ffffffff811fd9bc: task_function_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int task_function_call(struct task_struct *p, remote_function_f func, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120c790)
Location: kernel/events/core.c:103
Inline: False
Direct callers:
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
```
**Symbols:**

```
ffffffff8120c790-ffffffff8120c7fc: task_function_call (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
