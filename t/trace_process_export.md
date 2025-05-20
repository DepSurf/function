# Function: <code>trace_process_export</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8115f810)
Location: kernel/trace/trace.c:2230
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_function
```
**Symbols:**

```
ffffffff8115f810-ffffffff8115f842: trace_process_export.isra.40 (STB_LOCAL)
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
In kernel/trace/trace.c (ffffffff81162c00)
Location: kernel/trace/trace.c:2407
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_function
```
**Symbols:**

```
ffffffff81162c00-ffffffff81162c32: trace_process_export.isra.40 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void trace_process_export(struct trace_export *export, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8116dea0)
Location: kernel/trace/trace.c:2415
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_function
```
**Symbols:**

```
ffffffff8116dea0-ffffffff8116deda: trace_process_export (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void trace_process_export(struct trace_export *export, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8117ce50)
Location: kernel/trace/trace.c:2427
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_function
```
**Symbols:**

```
ffffffff8117ce50-ffffffff8117ce8a: trace_process_export (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118fc93)
Location: kernel/trace/trace.c:2428
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_function
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119da2f)
Location: kernel/trace/trace.c:2612
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_function
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a93ff)
Location: kernel/trace/trace.c:2638
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_function
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
In kernel/trace/trace.c (ffffffff811c1503)
Location: kernel/trace/trace.c:2749
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_function
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
In kernel/trace/trace.c (ffffffff811b7887)
Location: kernel/trace/trace.c:267
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_exports
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
In kernel/trace/trace.c (ffffffff811b83b7)
Location: kernel/trace/trace.c:267
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_exports
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
In kernel/trace/trace.c (ffffffff811e28a7)
Location: kernel/trace/trace.c:280
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_exports
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
In kernel/trace/trace.c (ffffffff812197ae)
Location: kernel/trace/trace.c:290
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_exports
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
In kernel/trace/trace.c (ffffffff8126365e)
Location: kernel/trace/trace.c:289
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_exports
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
In kernel/trace/trace.c (ffffffff8127a7be)
Location: kernel/trace/trace.c:330
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_exports
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
In kernel/trace/trace.c (ffffffff8129534e)
Location: kernel/trace/trace.c:325
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_exports
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff8000102260f8)
Location: kernel/trace/trace.c:2638
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_function
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0463694)
Location: kernel/trace/trace.c:2638
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_function
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002abb60)
Location: kernel/trace/trace.c:2638
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_function
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe000180f92)
Location: kernel/trace/trace.c:2638
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_function
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a1a1f)
Location: kernel/trace/trace.c:2638
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_function
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811949ef)
Location: kernel/trace/trace.c:2638
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_function
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119f7ef)
Location: kernel/trace/trace.c:2638
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_function
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811ad576)
Location: kernel/trace/trace.c:2638
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_function
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
</ul>
