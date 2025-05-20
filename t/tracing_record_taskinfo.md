# Function: <code>tracing_record_taskinfo</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void tracing_record_taskinfo(struct task_struct *task, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811659e0)
Location: kernel/trace/trace.c:2038
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_record_tgid
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace_sched_switch.c:probe_sched_wakeup
```
**Symbols:**

```
ffffffff811659e0-ffffffff81165a84: tracing_record_taskinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void tracing_record_taskinfo(struct task_struct *task, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81172970)
Location: kernel/trace/trace.c:2041
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_record_tgid
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace_sched_switch.c:probe_sched_wakeup
```
**Symbols:**

```
ffffffff81172970-ffffffff81172a14: tracing_record_taskinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void tracing_record_taskinfo(struct task_struct *task, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81181960)
Location: kernel/trace/trace.c:2053
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_record_tgid
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace_sched_switch.c:probe_sched_wakeup
```
**Symbols:**

```
ffffffff81181960-ffffffff81181a01: tracing_record_taskinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void tracing_record_taskinfo(struct task_struct *task, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118f320)
Location: kernel/trace/trace.c:2054
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_record_tgid
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace_sched_switch.c:probe_sched_wakeup
```
**Symbols:**

```
ffffffff8118f320-ffffffff8118f3c1: tracing_record_taskinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void tracing_record_taskinfo(struct task_struct *task, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119cce0)
Location: kernel/trace/trace.c:2237
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_record_tgid
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace_sched_switch.c:probe_sched_wakeup
```
**Symbols:**

```
ffffffff8119cce0-ffffffff8119cd87: tracing_record_taskinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void tracing_record_taskinfo(struct task_struct *task, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a8690)
Location: kernel/trace/trace.c:2263
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_record_tgid
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace_sched_switch.c:probe_sched_wakeup
```
**Symbols:**

```
ffffffff811a8690-ffffffff811a8737: tracing_record_taskinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void tracing_record_taskinfo(struct task_struct *task, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c0ed0)
Location: kernel/trace/trace.c:2367
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_record_tgid
  - kernel/trace/trace.c:tracing_record_tgid
Direct callers:
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace_sched_switch.c:probe_sched_wakeup
```
**Symbols:**

```
ffffffff811c0780-ffffffff811c086a: tracing_record_taskinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void tracing_record_taskinfo(struct task_struct *task, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811beb00)
Location: kernel/trace/trace.c:2511
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_record_tgid
  - kernel/trace/trace.c:tracing_record_tgid
Direct callers:
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace_sched_switch.c:probe_sched_wakeup
```
**Symbols:**

```
ffffffff811be3a0-ffffffff811be48a: tracing_record_taskinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void tracing_record_taskinfo(struct task_struct *task, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811be3c0)
Location: kernel/trace/trace.c:2522
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_record_tgid
  - kernel/trace/trace.c:tracing_record_tgid
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace.c:__update_max_tr
Direct callers:
  - kernel/trace/trace_sched_switch.c:probe_sched_wakeup
```
**Symbols:**

```
ffffffff811be1f0-ffffffff811be281: tracing_record_taskinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void tracing_record_taskinfo(struct task_struct *task, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811e8c20)
Location: kernel/trace/trace.c:2536
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_record_tgid
  - kernel/trace/trace.c:tracing_record_tgid
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace.c:__update_max_tr
Direct callers:
  - kernel/trace/trace_sched_switch.c:probe_sched_wakeup
```
**Symbols:**

```
ffffffff811e8a50-ffffffff811e8ae1: tracing_record_taskinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void tracing_record_taskinfo(struct task_struct *task, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff812208e0)
Location: kernel/trace/trace.c:2527
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_record_tgid
  - kernel/trace/trace.c:tracing_record_tgid
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace.c:__update_max_tr
```
**Symbols:**

```
ffffffff81220680-ffffffff81220756: tracing_record_taskinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void tracing_record_taskinfo(struct task_struct *task, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8126b730)
Location: kernel/trace/trace.c:2551
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_record_tgid
  - kernel/trace/trace.c:tracing_record_tgid
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace.c:__update_max_tr
```
**Symbols:**

```
ffffffff8126b4a0-ffffffff8126b576: tracing_record_taskinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void tracing_record_taskinfo(struct task_struct *task, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff812828a0)
Location: kernel/trace/trace.c:2622
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_record_tgid
  - kernel/trace/trace.c:tracing_record_tgid
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace.c:__update_max_tr
```
**Symbols:**

```
ffffffff81282610-ffffffff812826e6: tracing_record_taskinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void tracing_record_taskinfo(struct task_struct *task, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8129d990)
Location: kernel/trace/trace.c:2617
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_record_tgid
  - kernel/trace/trace.c:tracing_record_tgid
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace.c:__update_max_tr
```
**Symbols:**

```
ffffffff8129d700-ffffffff8129d7d6: tracing_record_taskinfo (STB_GLOBAL)
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
void tracing_record_taskinfo(struct task_struct *task, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff8000102251d0)
Location: kernel/trace/trace.c:2263
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_record_tgid
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace_sched_switch.c:probe_sched_wakeup
```
**Symbols:**

```
ffff8000102251d0-ffff8000102252a4: tracing_record_taskinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void tracing_record_taskinfo(struct task_struct *task, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0462670)
Location: kernel/trace/trace.c:2263
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_record_tgid
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace_sched_switch.c:probe_sched_wakeup
```
**Symbols:**

```
c0462670-c0462754: tracing_record_taskinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void tracing_record_taskinfo(struct task_struct *task, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002aa6f0)
Location: kernel/trace/trace.c:2263
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_record_tgid
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace_sched_switch.c:probe_sched_wakeup
  - kernel/trace/trace_sched_switch.c:probe_sched_wakeup
```
**Symbols:**

```
c0000000002aa6f0-c0000000002aa7f8: tracing_record_taskinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void tracing_record_taskinfo(struct task_struct *task, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe00018017e)
Location: kernel/trace/trace.c:2263
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_record_tgid
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace_sched_switch.c:probe_sched_wakeup
```
**Symbols:**

```
ffffffe00018017e-ffffffe000180226: tracing_record_taskinfo (STB_GLOBAL)
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
void tracing_record_taskinfo(struct task_struct *task, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a0cb0)
Location: kernel/trace/trace.c:2263
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_record_tgid
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace_sched_switch.c:probe_sched_wakeup
```
**Symbols:**

```
ffffffff811a0cb0-ffffffff811a0d57: tracing_record_taskinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void tracing_record_taskinfo(struct task_struct *task, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81193cc0)
Location: kernel/trace/trace.c:2263
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_record_tgid
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace_sched_switch.c:probe_sched_wakeup
```
**Symbols:**

```
ffffffff81193cc0-ffffffff81193d67: tracing_record_taskinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void tracing_record_taskinfo(struct task_struct *task, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119ea80)
Location: kernel/trace/trace.c:2263
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_record_tgid
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace_sched_switch.c:probe_sched_wakeup
```
**Symbols:**

```
ffffffff8119ea80-ffffffff8119eb27: tracing_record_taskinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void tracing_record_taskinfo(struct task_struct *task, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811ac770)
Location: kernel/trace/trace.c:2263
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_record_tgid
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace_sched_switch.c:probe_sched_wakeup
```
**Symbols:**

```
ffffffff811ac770-ffffffff811ac817: tracing_record_taskinfo (STB_GLOBAL)
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
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
