# Function: <code>dyn_event_release</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dyn_event_release(int argc, char **argv, struct dyn_event_operations *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff811ba5b0)
Location: kernel/trace/trace_dynevent.c:34
Inline: False
```
**Symbols:**

```
ffffffff811ba5b0-ffffffff811ba6b6: dyn_event_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dyn_event_release(int argc, char **argv, struct dyn_event_operations *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff811c9640)
Location: kernel/trace/trace_dynevent.c:34
Inline: False
```
**Symbols:**

```
ffffffff811c9640-ffffffff811c974b: dyn_event_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dyn_event_release(int argc, char **argv, struct dyn_event_operations *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff811d5330)
Location: kernel/trace/trace_dynevent.c:34
Inline: False
```
**Symbols:**

```
ffffffff811d5330-ffffffff811d5463: dyn_event_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dyn_event_release(int argc, char **argv, struct dyn_event_operations *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff811f19a0)
Location: kernel/trace/trace_dynevent.c:34
Inline: False
```
**Symbols:**

```
ffffffff811f19a0-ffffffff811f1ad3: dyn_event_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dyn_event_release(int argc, char **argv, struct dyn_event_operations *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff811f03d0)
Location: kernel/trace/trace_dynevent.c:34
Inline: False
```
**Symbols:**

```
ffffffff811f03d0-ffffffff811f0503: dyn_event_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dyn_event_release(const char *raw_command, struct dyn_event_operations *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff811f1300)
Location: kernel/trace/trace_dynevent.c:34
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:kprobe_event_delete
  - kernel/trace/trace_kprobe.c:trace_kprobe_run_command
```
**Symbols:**

```
ffffffff811f1300-ffffffff811f147e: dyn_event_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dyn_event_release(const char *raw_command, struct dyn_event_operations *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff812224a0)
Location: kernel/trace/trace_dynevent.c:72
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:kprobe_event_delete
  - kernel/trace/trace_kprobe.c:trace_kprobe_run_command
```
**Symbols:**

```
ffffffff812224a0-ffffffff8122261e: dyn_event_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dyn_event_release(const char *raw_command, struct dyn_event_operations *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff81262270)
Location: kernel/trace/trace_dynevent.c:72
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:kprobe_event_delete
  - kernel/trace/trace_kprobe.c:trace_kprobe_run_command
```
**Symbols:**

```
ffffffff81262270-ffffffff81262416: dyn_event_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dyn_event_release(const char *raw_command, struct dyn_event_operations *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff812b3a40)
Location: kernel/trace/trace_dynevent.c:72
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:kprobe_event_delete
  - kernel/trace/trace_kprobe.c:trace_kprobe_run_command
```
**Symbols:**

```
ffffffff812b3a40-ffffffff812b3be3: dyn_event_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dyn_event_release(const char *raw_command, struct dyn_event_operations *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff812d6310)
Location: kernel/trace/trace_dynevent.c:72
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:kprobe_event_delete
  - kernel/trace/trace_kprobe.c:trace_kprobe_run_command
```
**Symbols:**

```
ffffffff812d6310-ffffffff812d64b3: dyn_event_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dyn_event_release(const char *raw_command, struct dyn_event_operations *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff812f3e20)
Location: kernel/trace/trace_dynevent.c:72
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:kprobe_event_delete
  - kernel/trace/trace_kprobe.c:trace_kprobe_run_command
```
**Symbols:**

```
ffffffff812f3e20-ffffffff812f3fc3: dyn_event_release (STB_GLOBAL)
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
int dyn_event_release(int argc, char **argv, struct dyn_event_operations *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffff800010255530)
Location: kernel/trace/trace_dynevent.c:34
Inline: False
```
**Symbols:**

```
ffff800010255530-ffff80001025567c: dyn_event_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dyn_event_release(int argc, char **argv, struct dyn_event_operations *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (c0488750)
Location: kernel/trace/trace_dynevent.c:34
Inline: False
```
**Symbols:**

```
c0488750-c04888a8: dyn_event_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dyn_event_release(int argc, char **argv, struct dyn_event_operations *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (c0000000002f53a0)
Location: kernel/trace/trace_dynevent.c:34
Inline: False
```
**Symbols:**

```
c0000000002f53a0-c0000000002f55c0: dyn_event_release (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int dyn_event_release(int argc, char **argv, struct dyn_event_operations *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff811cd950)
Location: kernel/trace/trace_dynevent.c:34
Inline: False
```
**Symbols:**

```
ffffffff811cd950-ffffffff811cda83: dyn_event_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dyn_event_release(int argc, char **argv, struct dyn_event_operations *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff811c0720)
Location: kernel/trace/trace_dynevent.c:34
Inline: False
```
**Symbols:**

```
ffffffff811c0720-ffffffff811c0853: dyn_event_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dyn_event_release(int argc, char **argv, struct dyn_event_operations *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff811cb720)
Location: kernel/trace/trace_dynevent.c:34
Inline: False
```
**Symbols:**

```
ffffffff811cb720-ffffffff811cb853: dyn_event_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dyn_event_release(int argc, char **argv, struct dyn_event_operations *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff811d9980)
Location: kernel/trace/trace_dynevent.c:34
Inline: False
```
**Symbols:**

```
ffffffff811d9980-ffffffff811d9ab3: dyn_event_release (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char *raw_command</code>
</li>
<li>
<b>Param removed. </b>
<code>int argc</code>
</li>
<li>
<b>Param removed. </b>
<code>char **argv</code>
</li>
<li>
<b>Param reordered. </b>
<code>argc, argv, type</code> ➡️ <code>raw_command, type</code>
</li>
</ul>
</details>
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
