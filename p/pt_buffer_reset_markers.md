# Function: <code>pt_buffer_reset_markers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff81013f00)
Location: arch/x86/events/intel/pt.c:678
Inline: True
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_add
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff81013f00-ffffffff81014011: pt_buffer_reset_markers.isra.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff81013a20)
Location: arch/x86/events/intel/pt.c:819
Inline: True
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff81013a20-ffffffff81013b4f: pt_buffer_reset_markers.isra.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff81013ba0)
Location: arch/x86/events/intel/pt.c:840
Inline: True
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff81013ba0-ffffffff81013ccf: pt_buffer_reset_markers.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pt_buffer_reset_markers(struct pt_buffer *buf, struct perf_output_handle *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff81011810)
Location: arch/x86/events/intel/pt.c:917
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff81011810-ffffffff81011937: pt_buffer_reset_markers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pt_buffer_reset_markers(struct pt_buffer *buf, struct perf_output_handle *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff81011f50)
Location: arch/x86/events/intel/pt.c:918
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff81011f50-ffffffff81012076: pt_buffer_reset_markers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pt_buffer_reset_markers(struct pt_buffer *buf, struct perf_output_handle *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff810126e0)
Location: arch/x86/events/intel/pt.c:918
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff810126e0-ffffffff81012806: pt_buffer_reset_markers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pt_buffer_reset_markers(struct pt_buffer *buf, struct perf_output_handle *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff81012de0)
Location: arch/x86/events/intel/pt.c:928
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff81012de0-ffffffff81012f06: pt_buffer_reset_markers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pt_buffer_reset_markers(struct pt_buffer *buf, struct perf_output_handle *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff81014170)
Location: arch/x86/events/intel/pt.c:920
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff81014170-ffffffff810142b2: pt_buffer_reset_markers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pt_buffer_reset_markers(struct pt_buffer *buf, struct perf_output_handle *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff81014ad0)
Location: arch/x86/events/intel/pt.c:1026
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff81014ad0-ffffffff81014cbd: pt_buffer_reset_markers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pt_buffer_reset_markers(struct pt_buffer *buf, struct perf_output_handle *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff81016e70)
Location: arch/x86/events/intel/pt.c:1061
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff81016e70-ffffffff81017060: pt_buffer_reset_markers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pt_buffer_reset_markers(struct pt_buffer *buf, struct perf_output_handle *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff81017310)
Location: arch/x86/events/intel/pt.c:1061
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff81017310-ffffffff81017500: pt_buffer_reset_markers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pt_buffer_reset_markers(struct pt_buffer *buf, struct perf_output_handle *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff810182f0)
Location: arch/x86/events/intel/pt.c:1061
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff810182f0-ffffffff810184dd: pt_buffer_reset_markers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pt_buffer_reset_markers(struct pt_buffer *buf, struct perf_output_handle *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/pt.c (0)
Location: arch/x86/events/intel/pt.c:1062
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff8101ac10-ffffffff8101aeaa: pt_buffer_reset_markers (STB_LOCAL)
ffffffff81c96546-ffffffff81c9655b: pt_buffer_reset_markers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pt_buffer_reset_markers(struct pt_buffer *buf, struct perf_output_handle *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/pt.c (0)
Location: arch/x86/events/intel/pt.c:1080
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff8101cee0-ffffffff8101d18c: pt_buffer_reset_markers (STB_LOCAL)
ffffffff81e45952-ffffffff81e45967: pt_buffer_reset_markers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int pt_buffer_reset_markers(struct pt_buffer *buf, struct perf_output_handle *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/pt.c (0)
Location: arch/x86/events/intel/pt.c:1080
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff810212c0-ffffffff8102156c: pt_buffer_reset_markers (STB_LOCAL)
ffffffff820511a7-ffffffff820511bc: pt_buffer_reset_markers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int pt_buffer_reset_markers(struct pt_buffer *buf, struct perf_output_handle *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/pt.c (0)
Location: arch/x86/events/intel/pt.c:1080
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff81021010-ffffffff810212bc: pt_buffer_reset_markers (STB_LOCAL)
ffffffff820cf5da-ffffffff820cf5ef: pt_buffer_reset_markers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int pt_buffer_reset_markers(struct pt_buffer *buf, struct perf_output_handle *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/pt.c (0)
Location: arch/x86/events/intel/pt.c:1081
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff81027130-ffffffff810273dc: pt_buffer_reset_markers (STB_LOCAL)
ffffffff821a9f48-ffffffff821a9f5d: pt_buffer_reset_markers.cold (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int pt_buffer_reset_markers(struct pt_buffer *buf, struct perf_output_handle *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff81014ad0)
Location: arch/x86/events/intel/pt.c:1026
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff81014ad0-ffffffff81014cbd: pt_buffer_reset_markers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pt_buffer_reset_markers(struct pt_buffer *buf, struct perf_output_handle *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff81013da0)
Location: arch/x86/events/intel/pt.c:1026
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff81013da0-ffffffff81013f8d: pt_buffer_reset_markers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pt_buffer_reset_markers(struct pt_buffer *buf, struct perf_output_handle *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff81014a90)
Location: arch/x86/events/intel/pt.c:1026
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff81014a90-ffffffff81014c7d: pt_buffer_reset_markers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pt_buffer_reset_markers(struct pt_buffer *buf, struct perf_output_handle *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff81014cd0)
Location: arch/x86/events/intel/pt.c:1026
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff81014cd0-ffffffff81014ebd: pt_buffer_reset_markers (STB_LOCAL)
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
