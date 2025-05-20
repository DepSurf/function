# Function: <code>ftrace_probe_print</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ftrace_probe_print(const char *name, struct seq_file *m, long unsigned int ip, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_functions.c (ffffffff81156a30)
Location: kernel/trace/trace_functions.c:431
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_cpudump_print
  - kernel/trace/trace_functions.c:ftrace_dump_print
  - kernel/trace/trace_functions.c:ftrace_stacktrace_print
  - kernel/trace/trace_functions.c:ftrace_traceoff_print
  - kernel/trace/trace_functions.c:ftrace_traceon_print
```
**Symbols:**

```
ffffffff81156a30-ffffffff81156a84: ftrace_probe_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ftrace_probe_print(const char *name, struct seq_file *m, long unsigned int ip, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_functions.c (ffffffff811612b0)
Location: kernel/trace/trace_functions.c:437
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_cpudump_print
  - kernel/trace/trace_functions.c:ftrace_dump_print
  - kernel/trace/trace_functions.c:ftrace_stacktrace_print
  - kernel/trace/trace_functions.c:ftrace_traceoff_print
  - kernel/trace/trace_functions.c:ftrace_traceon_print
```
**Symbols:**

```
ffffffff811612b0-ffffffff81161304: ftrace_probe_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ftrace_probe_print(const char *name, struct seq_file *m, long unsigned int ip, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_functions.c (ffffffff8116bd10)
Location: kernel/trace/trace_functions.c:437
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_cpudump_print
  - kernel/trace/trace_functions.c:ftrace_dump_print
  - kernel/trace/trace_functions.c:ftrace_stacktrace_print
  - kernel/trace/trace_functions.c:ftrace_traceoff_print
  - kernel/trace/trace_functions.c:ftrace_traceon_print
```
**Symbols:**

```
ffffffff8116bd10-ffffffff8116bd64: ftrace_probe_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_functions.c (ffffffff8116f030)
Location: kernel/trace/trace_functions.c:477
Inline: True
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_cpudump_print
  - kernel/trace/trace_functions.c:ftrace_dump_print
  - kernel/trace/trace_functions.c:ftrace_stacktrace_print
  - kernel/trace/trace_functions.c:ftrace_traceoff_print
  - kernel/trace/trace_functions.c:ftrace_traceon_print
```
**Symbols:**

```
ffffffff8116f030-ffffffff8116f09c: ftrace_probe_print.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_functions.c (ffffffff8117c120)
Location: kernel/trace/trace_functions.c:501
Inline: True
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_cpudump_print
  - kernel/trace/trace_functions.c:ftrace_dump_print
  - kernel/trace/trace_functions.c:ftrace_stacktrace_print
  - kernel/trace/trace_functions.c:ftrace_traceoff_print
  - kernel/trace/trace_functions.c:ftrace_traceon_print
```
**Symbols:**

```
ffffffff8117c120-ffffffff8117c18c: ftrace_probe_print.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_functions.c (ffffffff8118b260)
Location: kernel/trace/trace_functions.c:501
Inline: True
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_cpudump_print
  - kernel/trace/trace_functions.c:ftrace_dump_print
  - kernel/trace/trace_functions.c:ftrace_stacktrace_print
  - kernel/trace/trace_functions.c:ftrace_traceoff_print
  - kernel/trace/trace_functions.c:ftrace_traceon_print
```
**Symbols:**

```
ffffffff8118b260-ffffffff8118b2cc: ftrace_probe_print.isra.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_functions.c (ffffffff81198b90)
Location: kernel/trace/trace_functions.c:501
Inline: True
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_cpudump_print
  - kernel/trace/trace_functions.c:ftrace_dump_print
  - kernel/trace/trace_functions.c:ftrace_stacktrace_print
  - kernel/trace/trace_functions.c:ftrace_traceoff_print
  - kernel/trace/trace_functions.c:ftrace_traceon_print
```
**Symbols:**

```
ffffffff81198b90-ffffffff81198bfc: ftrace_probe_print.isra.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_functions.c (ffffffff811a6780)
Location: kernel/trace/trace_functions.c:501
Inline: True
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_cpudump_print
  - kernel/trace/trace_functions.c:ftrace_dump_print
  - kernel/trace/trace_functions.c:ftrace_stacktrace_print
  - kernel/trace/trace_functions.c:ftrace_traceoff_print
  - kernel/trace/trace_functions.c:ftrace_traceon_print
```
**Symbols:**

```
ffffffff811a6780-ffffffff811a67ef: ftrace_probe_print.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_functions.c (ffffffff811b1f70)
Location: kernel/trace/trace_functions.c:501
Inline: True
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_cpudump_print
  - kernel/trace/trace_functions.c:ftrace_dump_print
  - kernel/trace/trace_functions.c:ftrace_stacktrace_print
  - kernel/trace/trace_functions.c:ftrace_traceoff_print
  - kernel/trace/trace_functions.c:ftrace_traceon_print
```
**Symbols:**

```
ffffffff811b1f70-ffffffff811b1fdf: ftrace_probe_print.isra.0 (STB_LOCAL)
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
In kernel/trace/trace_functions.c (ffffffff811ca180)
Location: kernel/trace/trace_functions.c:501
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_cpudump_print
  - kernel/trace/trace_functions.c:ftrace_dump_print
  - kernel/trace/trace_functions.c:ftrace_stacktrace_print
  - kernel/trace/trace_functions.c:ftrace_traceoff_print
  - kernel/trace/trace_functions.c:ftrace_traceon_print
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
In kernel/trace/trace_functions.c (ffffffff811c7814)
Location: kernel/trace/trace_functions.c:504
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_cpudump_print
  - kernel/trace/trace_functions.c:ftrace_dump_print
  - kernel/trace/trace_functions.c:ftrace_stacktrace_print
  - kernel/trace/trace_functions.c:ftrace_traceoff_print
  - kernel/trace/trace_functions.c:ftrace_traceon_print
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
In kernel/trace/trace_functions.c (ffffffff811c8814)
Location: kernel/trace/trace_functions.c:666
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_cpudump_print
  - kernel/trace/trace_functions.c:ftrace_dump_print
  - kernel/trace/trace_functions.c:ftrace_stacktrace_print
  - kernel/trace/trace_functions.c:ftrace_traceoff_print
  - kernel/trace/trace_functions.c:ftrace_traceon_print
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
In kernel/trace/trace_functions.c (ffffffff811f41e4)
Location: kernel/trace/trace_functions.c:666
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_cpudump_print
  - kernel/trace/trace_functions.c:ftrace_dump_print
  - kernel/trace/trace_functions.c:ftrace_stacktrace_print
  - kernel/trace/trace_functions.c:ftrace_traceoff_print
  - kernel/trace/trace_functions.c:ftrace_traceon_print
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
In kernel/trace/trace_functions.c (ffffffff8122e383)
Location: kernel/trace/trace_functions.c:661
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_cpudump_print
  - kernel/trace/trace_functions.c:ftrace_dump_print
  - kernel/trace/trace_functions.c:ftrace_stacktrace_print
  - kernel/trace/trace_functions.c:ftrace_traceoff_print
  - kernel/trace/trace_functions.c:ftrace_traceon_print
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
In kernel/trace/trace_functions.c (ffffffff8127a273)
Location: kernel/trace/trace_functions.c:661
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_cpudump_print
  - kernel/trace/trace_functions.c:ftrace_dump_print
  - kernel/trace/trace_functions.c:ftrace_stacktrace_print
  - kernel/trace/trace_functions.c:ftrace_traceoff_print
  - kernel/trace/trace_functions.c:ftrace_traceon_print
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
In kernel/trace/trace_functions.c (ffffffff81291d23)
Location: kernel/trace/trace_functions.c:661
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_cpudump_print
  - kernel/trace/trace_functions.c:ftrace_dump_print
  - kernel/trace/trace_functions.c:ftrace_stacktrace_print
  - kernel/trace/trace_functions.c:ftrace_traceoff_print
  - kernel/trace/trace_functions.c:ftrace_traceon_print
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
In kernel/trace/trace_functions.c (ffffffff812ad513)
Location: kernel/trace/trace_functions.c:661
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_cpudump_print
  - kernel/trace/trace_functions.c:ftrace_dump_print
  - kernel/trace/trace_functions.c:ftrace_stacktrace_print
  - kernel/trace/trace_functions.c:ftrace_traceoff_print
  - kernel/trace/trace_functions.c:ftrace_traceon_print
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_functions.c (ffff80001022fae0)
Location: kernel/trace/trace_functions.c:501
Inline: True
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_cpudump_print
  - kernel/trace/trace_functions.c:ftrace_dump_print
  - kernel/trace/trace_functions.c:ftrace_stacktrace_print
  - kernel/trace/trace_functions.c:ftrace_traceoff_print
  - kernel/trace/trace_functions.c:ftrace_traceon_print
```
**Symbols:**

```
ffff80001022fae0-ffff80001022fb70: ftrace_probe_print.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_functions.c (c046bc38)
Location: kernel/trace/trace_functions.c:501
Inline: True
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_cpudump_print
  - kernel/trace/trace_functions.c:ftrace_dump_print
  - kernel/trace/trace_functions.c:ftrace_stacktrace_print
  - kernel/trace/trace_functions.c:ftrace_traceoff_print
  - kernel/trace/trace_functions.c:ftrace_traceon_print
```
**Symbols:**

```
c046bc38-c046bcb8: ftrace_probe_print.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_functions.c (c0000000002b99f0)
Location: kernel/trace/trace_functions.c:501
Inline: True
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_cpudump_print
  - kernel/trace/trace_functions.c:ftrace_dump_print
  - kernel/trace/trace_functions.c:ftrace_stacktrace_print
  - kernel/trace/trace_functions.c:ftrace_traceoff_print
  - kernel/trace/trace_functions.c:ftrace_traceon_print
```
**Symbols:**

```
c0000000002b99f0-c0000000002b9ac4: ftrace_probe_print.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_functions.c (ffffffe000187d20)
Location: kernel/trace/trace_functions.c:501
Inline: True
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_cpudump_print
  - kernel/trace/trace_functions.c:ftrace_dump_print
  - kernel/trace/trace_functions.c:ftrace_stacktrace_print
  - kernel/trace/trace_functions.c:ftrace_traceoff_print
  - kernel/trace/trace_functions.c:ftrace_traceon_print
```
**Symbols:**

```
ffffffe000187d20-ffffffe000187da0: ftrace_probe_print.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_functions.c (ffffffff811aa590)
Location: kernel/trace/trace_functions.c:501
Inline: True
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_cpudump_print
  - kernel/trace/trace_functions.c:ftrace_dump_print
  - kernel/trace/trace_functions.c:ftrace_stacktrace_print
  - kernel/trace/trace_functions.c:ftrace_traceoff_print
  - kernel/trace/trace_functions.c:ftrace_traceon_print
```
**Symbols:**

```
ffffffff811aa590-ffffffff811aa5ff: ftrace_probe_print.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_functions.c (ffffffff8119d4f0)
Location: kernel/trace/trace_functions.c:501
Inline: True
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_cpudump_print
  - kernel/trace/trace_functions.c:ftrace_dump_print
  - kernel/trace/trace_functions.c:ftrace_stacktrace_print
  - kernel/trace/trace_functions.c:ftrace_traceoff_print
  - kernel/trace/trace_functions.c:ftrace_traceon_print
```
**Symbols:**

```
ffffffff8119d4f0-ffffffff8119d55f: ftrace_probe_print.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_functions.c (ffffffff811a8360)
Location: kernel/trace/trace_functions.c:501
Inline: True
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_cpudump_print
  - kernel/trace/trace_functions.c:ftrace_dump_print
  - kernel/trace/trace_functions.c:ftrace_stacktrace_print
  - kernel/trace/trace_functions.c:ftrace_traceoff_print
  - kernel/trace/trace_functions.c:ftrace_traceon_print
```
**Symbols:**

```
ffffffff811a8360-ffffffff811a83cf: ftrace_probe_print.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_functions.c (ffffffff811b6120)
Location: kernel/trace/trace_functions.c:501
Inline: True
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_cpudump_print
  - kernel/trace/trace_functions.c:ftrace_dump_print
  - kernel/trace/trace_functions.c:ftrace_stacktrace_print
  - kernel/trace/trace_functions.c:ftrace_traceoff_print
  - kernel/trace/trace_functions.c:ftrace_traceon_print
```
**Symbols:**

```
ffffffff811b6120-ffffffff811b618f: ftrace_probe_print.isra.0 (STB_LOCAL)
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
</ul>
