# Function: <code>enable_trace_eprobe</code>

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
<summary>In <code>5.15</code>: ✅</summary>

```c
int enable_trace_eprobe(struct trace_event_call *call, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_eprobe.c (ffffffff8120a140)
Location: kernel/trace/trace_eprobe.c:693
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:eprobe_register
```
**Symbols:**

```
ffffffff8120a140-ffffffff8120a36b: enable_trace_eprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int enable_trace_eprobe(struct trace_event_call *call, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_eprobe.c (ffffffff812460f0)
Location: kernel/trace/trace_eprobe.c:760
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:eprobe_register
```
**Symbols:**

```
ffffffff812460f0-ffffffff812462ff: enable_trace_eprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int enable_trace_eprobe(struct trace_event_call *call, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_eprobe.c (ffffffff81293020)
Location: kernel/trace/trace_eprobe.c:736
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:eprobe_register
```
**Symbols:**

```
ffffffff81293020-ffffffff812932e5: enable_trace_eprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int enable_trace_eprobe(struct trace_event_call *call, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_eprobe.c (ffffffff812b01a0)
Location: kernel/trace/trace_eprobe.c:640
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:eprobe_register
```
**Symbols:**

```
ffffffff812b01a0-ffffffff812b04a8: enable_trace_eprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int enable_trace_eprobe(struct trace_event_call *call, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_eprobe.c (ffffffff812cc710)
Location: kernel/trace/trace_eprobe.c:644
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:eprobe_register
```
**Symbols:**

```
ffffffff812cc710-ffffffff812cca70: enable_trace_eprobe (STB_LOCAL)
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
