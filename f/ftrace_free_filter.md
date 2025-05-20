# Function: <code>ftrace_free_filter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ftrace_free_filter(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81142c80)
Location: kernel/trace/ftrace.c:1339
Inline: False
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
```
**Symbols:**

```
ffffffff81142c80-ffffffff81142cd3: ftrace_free_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ftrace_free_filter(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8114aa80)
Location: kernel/trace/ftrace.c:1308
Inline: False
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
```
**Symbols:**

```
ffffffff8114aa80-ffffffff8114aad3: ftrace_free_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ftrace_free_filter(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81154970)
Location: kernel/trace/ftrace.c:1314
Inline: False
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
```
**Symbols:**

```
ffffffff81154970-ffffffff811549c3: ftrace_free_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ftrace_free_filter(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811572d0)
Location: kernel/trace/ftrace.c:1357
Inline: False
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
```
**Symbols:**

```
ffffffff811572d0-ffffffff8115733f: ftrace_free_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ftrace_free_filter(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81163e40)
Location: kernel/trace/ftrace.c:1333
Inline: False
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
```
**Symbols:**

```
ffffffff81163e40-ffffffff81163eac: ftrace_free_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ftrace_free_filter(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81172cb0)
Location: kernel/trace/ftrace.c:1322
Inline: False
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
```
**Symbols:**

```
ffffffff81172cb0-ffffffff81172d1c: ftrace_free_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ftrace_free_filter(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81180330)
Location: kernel/trace/ftrace.c:1271
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
```
**Symbols:**

```
ffffffff81180330-ffffffff8118039c: ftrace_free_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ftrace_free_filter(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118d500)
Location: kernel/trace/ftrace.c:1268
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
```
**Symbols:**

```
ffffffff8118d500-ffffffff8118d56c: ftrace_free_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ftrace_free_filter(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81199110)
Location: kernel/trace/ftrace.c:1269
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
```
**Symbols:**

```
ffffffff81199110-ffffffff8119917c: ftrace_free_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void ftrace_free_filter(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b28c6)
Location: kernel/trace/ftrace.c:1257
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
```
**Symbols:**

```
ffffffff811af4b0-ffffffff811af51f: ftrace_free_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void ftrace_free_filter(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b0336)
Location: kernel/trace/ftrace.c:1256
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
```
**Symbols:**

```
ffffffff811ace60-ffffffff811acecf: ftrace_free_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void ftrace_free_filter(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b0c46)
Location: kernel/trace/ftrace.c:1256
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
```
**Symbols:**

```
ffffffff811ad900-ffffffff811ad96f: ftrace_free_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void ftrace_free_filter(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811daac6)
Location: kernel/trace/ftrace.c:1257
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
```
**Symbols:**

```
ffffffff811d7660-ffffffff811d76cf: ftrace_free_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void ftrace_free_filter(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff812109e6)
Location: kernel/trace/ftrace.c:1251
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
  - kernel/trace/fprobe.c:unregister_fprobe
  - kernel/trace/fprobe.c:register_fprobe_ips
  - kernel/trace/fprobe.c:register_fprobe
```
**Symbols:**

```
ffffffff8120cb50-ffffffff8120cbcb: ftrace_free_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void ftrace_free_filter(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81259e66)
Location: kernel/trace/ftrace.c:1255
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
  - kernel/trace/fprobe.c:unregister_fprobe
  - kernel/trace/fprobe.c:register_fprobe_ips
  - kernel/trace/fprobe.c:register_fprobe
```
**Symbols:**

```
ffffffff81253de0-ffffffff81253e5b: ftrace_free_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ftrace_free_filter(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8126ae30)
Location: kernel/trace/ftrace.c:1286
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
  - kernel/trace/fprobe.c:register_fprobe_ips
  - kernel/trace/fprobe.c:register_fprobe
```
**Symbols:**

```
ffffffff8126ae30-ffffffff8126aeab: ftrace_free_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ftrace_free_filter(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81285470)
Location: kernel/trace/ftrace.c:1287
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
  - kernel/trace/fprobe.c:register_fprobe_ips
  - kernel/trace/fprobe.c:register_fprobe
```
**Symbols:**

```
ffffffff81285470-ffffffff812854eb: ftrace_free_filter (STB_GLOBAL)
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
void ftrace_free_filter(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffff800010211c48)
Location: kernel/trace/ftrace.c:1269
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
```
**Symbols:**

```
ffff800010211c48-ffff800010211ce0: ftrace_free_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ftrace_free_filter(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c04506f4)
Location: kernel/trace/ftrace.c:1269
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
```
**Symbols:**

```
c04506f4-c045077c: ftrace_free_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ftrace_free_filter(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c0000000002918c0)
Location: kernel/trace/ftrace.c:1269
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
```
**Symbols:**

```
c0000000002918c0-c000000000291994: ftrace_free_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ftrace_free_filter(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffe000172038)
Location: kernel/trace/ftrace.c:1269
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
```
**Symbols:**

```
ffffffe000172038-ffffffe0001720b6: ftrace_free_filter (STB_GLOBAL)
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
void ftrace_free_filter(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81191730)
Location: kernel/trace/ftrace.c:1269
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
```
**Symbols:**

```
ffffffff81191730-ffffffff8119179c: ftrace_free_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ftrace_free_filter(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81184840)
Location: kernel/trace/ftrace.c:1269
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
```
**Symbols:**

```
ffffffff81184840-ffffffff811848ac: ftrace_free_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ftrace_free_filter(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118f500)
Location: kernel/trace/ftrace.c:1269
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
```
**Symbols:**

```
ffffffff8118f500-ffffffff8118f56c: ftrace_free_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ftrace_free_filter(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119d0b0)
Location: kernel/trace/ftrace.c:1269
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
```
**Symbols:**

```
ffffffff8119d0b0-ffffffff8119d11c: ftrace_free_filter (STB_GLOBAL)
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
