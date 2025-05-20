# Function: <code>tracing_record_taskinfo_skip</code>

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
bool tracing_record_taskinfo_skip(int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81162e00)
Location: kernel/trace/trace.c:2020
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
```
**Symbols:**

```
ffffffff81162e00-ffffffff81162e50: tracing_record_taskinfo_skip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool tracing_record_taskinfo_skip(int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8116fdc0)
Location: kernel/trace/trace.c:2023
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
```
**Symbols:**

```
ffffffff8116fdc0-ffffffff8116fe10: tracing_record_taskinfo_skip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool tracing_record_taskinfo_skip(int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8117ee10)
Location: kernel/trace/trace.c:2035
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
```
**Symbols:**

```
ffffffff8117ee10-ffffffff8117ee62: tracing_record_taskinfo_skip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool tracing_record_taskinfo_skip(int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118c710)
Location: kernel/trace/trace.c:2036
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
```
**Symbols:**

```
ffffffff8118c710-ffffffff8118c760: tracing_record_taskinfo_skip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool tracing_record_taskinfo_skip(int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81199f60)
Location: kernel/trace/trace.c:2219
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
```
**Symbols:**

```
ffffffff81199f60-ffffffff81199fb0: tracing_record_taskinfo_skip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool tracing_record_taskinfo_skip(int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a5900)
Location: kernel/trace/trace.c:2245
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
```
**Symbols:**

```
ffffffff811a5900-ffffffff811a5950: tracing_record_taskinfo_skip (STB_LOCAL)
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
In kernel/trace/trace.c (ffffffff811c0ed0)
Location: kernel/trace/trace.c:2349
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_record_tgid
  - kernel/trace/trace.c:tracing_record_tgid
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
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
In kernel/trace/trace.c (ffffffff811beb00)
Location: kernel/trace/trace.c:2493
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_record_tgid
  - kernel/trace/trace.c:tracing_record_tgid
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
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
In kernel/trace/trace.c (ffffffff811be3c0)
Location: kernel/trace/trace.c:2506
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_record_tgid
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
  - kernel/trace/trace.c:__update_max_tr
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
In kernel/trace/trace.c (ffffffff811e8c20)
Location: kernel/trace/trace.c:2520
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_record_tgid
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
  - kernel/trace/trace.c:__update_max_tr
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
In kernel/trace/trace.c (ffffffff812208e0)
Location: kernel/trace/trace.c:2511
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_record_tgid
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
  - kernel/trace/trace.c:__update_max_tr
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
In kernel/trace/trace.c (ffffffff8126b730)
Location: kernel/trace/trace.c:2535
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_record_tgid
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
  - kernel/trace/trace.c:__update_max_tr
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
In kernel/trace/trace.c (ffffffff812828a0)
Location: kernel/trace/trace.c:2606
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_record_tgid
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
  - kernel/trace/trace.c:__update_max_tr
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
In kernel/trace/trace.c (ffffffff8129d990)
Location: kernel/trace/trace.c:2601
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_record_tgid
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
  - kernel/trace/trace.c:__update_max_tr
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
bool tracing_record_taskinfo_skip(int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff800010221848)
Location: kernel/trace/trace.c:2245
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
```
**Symbols:**

```
ffff800010221848-ffff8000102218c8: tracing_record_taskinfo_skip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool tracing_record_taskinfo_skip(int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c045e73c)
Location: kernel/trace/trace.c:2245
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
```
**Symbols:**

```
c045e73c-c045e7b4: tracing_record_taskinfo_skip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool tracing_record_taskinfo_skip(int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002a4b60)
Location: kernel/trace/trace.c:2245
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
```
**Symbols:**

```
c0000000002a4b60-c0000000002a4c28: tracing_record_taskinfo_skip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool tracing_record_taskinfo_skip(int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe00017d334)
Location: kernel/trace/trace.c:2245
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
```
**Symbols:**

```
ffffffe00017d334-ffffffe00017d3a6: tracing_record_taskinfo_skip (STB_LOCAL)
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
bool tracing_record_taskinfo_skip(int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119df20)
Location: kernel/trace/trace.c:2245
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
```
**Symbols:**

```
ffffffff8119df20-ffffffff8119df70: tracing_record_taskinfo_skip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool tracing_record_taskinfo_skip(int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81190f80)
Location: kernel/trace/trace.c:2245
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
```
**Symbols:**

```
ffffffff81190f80-ffffffff81190fd0: tracing_record_taskinfo_skip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool tracing_record_taskinfo_skip(int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119bcf0)
Location: kernel/trace/trace.c:2245
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
```
**Symbols:**

```
ffffffff8119bcf0-ffffffff8119bd40: tracing_record_taskinfo_skip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool tracing_record_taskinfo_skip(int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a9990)
Location: kernel/trace/trace.c:2245
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
```
**Symbols:**

```
ffffffff811a9990-ffffffff811a99e0: tracing_record_taskinfo_skip (STB_LOCAL)
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
