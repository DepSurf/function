# Function: <code>trace_save_cmdline</code>

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
In kernel/trace/trace.c (ffffffff8114e7dc)
Location: kernel/trace/trace.c:1556
Inline: True
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
In kernel/trace/trace.c (ffffffff811574ac)
Location: kernel/trace/trace.c:1801
Inline: True
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
In kernel/trace/trace.c (ffffffff811625ec)
Location: kernel/trace/trace.c:1845
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int trace_save_cmdline(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811624b0)
Location: kernel/trace/trace.c:1915
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
```
**Symbols:**

```
ffffffff811624b0-ffffffff811625a1: trace_save_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int trace_save_cmdline(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8116f4b0)
Location: kernel/trace/trace.c:1918
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
```
**Symbols:**

```
ffffffff8116f4b0-ffffffff8116f5a3: trace_save_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int trace_save_cmdline(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8117e530)
Location: kernel/trace/trace.c:1930
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
```
**Symbols:**

```
ffffffff8117e530-ffffffff8117e60a: trace_save_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int trace_save_cmdline(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118be20)
Location: kernel/trace/trace.c:1931
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
```
**Symbols:**

```
ffffffff8118be20-ffffffff8118bf04: trace_save_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int trace_save_cmdline(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811992c0)
Location: kernel/trace/trace.c:2114
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
```
**Symbols:**

```
ffffffff811992c0-ffffffff81199396: trace_save_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int trace_save_cmdline(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a4c20)
Location: kernel/trace/trace.c:2140
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
```
**Symbols:**

```
ffffffff811a4c20-ffffffff811a4cf6: trace_save_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c0d3d)
Location: kernel/trace/trace.c:2244
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
Direct callers:
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
```
**Symbols:**

```
ffffffff811bdae0-ffffffff811bdb9d: trace_save_cmdline.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811be96d)
Location: kernel/trace/trace.c:2388
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
Direct callers:
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
```
**Symbols:**

```
ffffffff811bb700-ffffffff811bb7bd: trace_save_cmdline.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int trace_save_cmdline(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bb960)
Location: kernel/trace/trace.c:2395
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
  - kernel/trace/trace.c:__update_max_tr
```
**Symbols:**

```
ffffffff811bb960-ffffffff811bba1f: trace_save_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int trace_save_cmdline(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811e6050)
Location: kernel/trace/trace.c:2409
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
  - kernel/trace/trace.c:__update_max_tr
```
**Symbols:**

```
ffffffff811e6050-ffffffff811e610f: trace_save_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int trace_save_cmdline(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8121dce0)
Location: kernel/trace/trace.c:2400
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
  - kernel/trace/trace.c:__update_max_tr
```
**Symbols:**

```
ffffffff8121dce0-ffffffff8121ddcb: trace_save_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int trace_save_cmdline(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81268390)
Location: kernel/trace/trace.c:2420
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
  - kernel/trace/trace.c:__update_max_tr
```
**Symbols:**

```
ffffffff81268390-ffffffff8126847b: trace_save_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int trace_save_cmdline(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8127f550)
Location: kernel/trace/trace.c:2491
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
  - kernel/trace/trace.c:__update_max_tr
```
**Symbols:**

```
ffffffff8127f550-ffffffff8127f63b: trace_save_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int trace_save_cmdline(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81299d30)
Location: kernel/trace/trace.c:2486
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
  - kernel/trace/trace.c:__update_max_tr
```
**Symbols:**

```
ffffffff81299d30-ffffffff81299e18: trace_save_cmdline (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int trace_save_cmdline(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff800010222670)
Location: kernel/trace/trace.c:2140
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
```
**Symbols:**

```
ffff800010222670-ffff800010222788: trace_save_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int trace_save_cmdline(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c045dc28)
Location: kernel/trace/trace.c:2140
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
```
**Symbols:**

```
c045dc28-c045dd1c: trace_save_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int trace_save_cmdline(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002a3850)
Location: kernel/trace/trace.c:2140
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
```
**Symbols:**

```
c0000000002a3850-c0000000002a3998: trace_save_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int trace_save_cmdline(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe00017cad6)
Location: kernel/trace/trace.c:2140
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
```
**Symbols:**

```
ffffffe00017cad6-ffffffe00017cba6: trace_save_cmdline (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int trace_save_cmdline(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119d240)
Location: kernel/trace/trace.c:2140
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
```
**Symbols:**

```
ffffffff8119d240-ffffffff8119d316: trace_save_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int trace_save_cmdline(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811902a0)
Location: kernel/trace/trace.c:2140
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
```
**Symbols:**

```
ffffffff811902a0-ffffffff81190376: trace_save_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int trace_save_cmdline(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119b010)
Location: kernel/trace/trace.c:2140
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
```
**Symbols:**

```
ffffffff8119b010-ffffffff8119b0e6: trace_save_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int trace_save_cmdline(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a8cb0)
Location: kernel/trace/trace.c:2140
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
```
**Symbols:**

```
ffffffff811a8cb0-ffffffff811a8d86: trace_save_cmdline (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
