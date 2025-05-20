# Function: <code>traceprobe_conflict_field_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int traceprobe_conflict_field_name(const char *name, struct probe_arg *args, int narg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff8116e050)
Location: kernel/trace/trace_probe.c:549
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
```
**Symbols:**

```
ffffffff8116e050-ffffffff8116e0d0: traceprobe_conflict_field_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int traceprobe_conflict_field_name(const char *name, struct probe_arg *args, int narg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff8117b6a0)
Location: kernel/trace/trace_probe.c:582
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
```
**Symbols:**

```
ffffffff8117b6a0-ffffffff8117b729: traceprobe_conflict_field_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int traceprobe_conflict_field_name(const char *name, struct probe_arg *args, int narg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811872b0)
Location: kernel/trace/trace_probe.c:586
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
```
**Symbols:**

```
ffffffff811872b0-ffffffff81187339: traceprobe_conflict_field_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int traceprobe_conflict_field_name(const char *name, struct probe_arg *args, int narg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff81189f10)
Location: kernel/trace/trace_probe.c:587
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
```
**Symbols:**

```
ffffffff81189f10-ffffffff81189f96: traceprobe_conflict_field_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int traceprobe_conflict_field_name(const char *name, struct probe_arg *args, int narg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff81197ba0)
Location: kernel/trace/trace_probe.c:585
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
```
**Symbols:**

```
ffffffff81197ba0-ffffffff81197c26: traceprobe_conflict_field_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int traceprobe_conflict_field_name(const char *name, struct probe_arg *args, int narg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811ad360)
Location: kernel/trace/trace_probe.c:585
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
```
**Symbols:**

```
ffffffff811ad360-ffffffff811ad3e6: traceprobe_conflict_field_name (STB_GLOBAL)
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
In kernel/trace/trace_probe.c (ffffffff811bbb52)
Location: kernel/trace/trace_probe.c:522
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
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
In kernel/trace/trace_probe.c (ffffffff811cb4ac)
Location: kernel/trace/trace_probe.c:677
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
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
In kernel/trace/trace_probe.c (ffffffff811d73b3)
Location: kernel/trace/trace_probe.c:732
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
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
In kernel/trace/trace_probe.c (ffffffff811f3cde)
Location: kernel/trace/trace_probe.c:732
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
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
In kernel/trace/trace_probe.c (ffffffff811f268e)
Location: kernel/trace/trace_probe.c:732
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
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
In kernel/trace/trace_probe.c (ffffffff811f3531)
Location: kernel/trace/trace_probe.c:732
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
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
In kernel/trace/trace_probe.c (0)
Location: kernel/trace/trace_probe.c:754
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
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
In kernel/trace/trace_probe.c (0)
Location: kernel/trace/trace_probe.c:761
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
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
In kernel/trace/trace_probe.c (0)
Location: kernel/trace/trace_probe.c:786
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
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
In kernel/trace/trace_probe.c (0)
Location: kernel/trace/trace_probe.c:1096
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
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
In kernel/trace/trace_probe.c (0)
Location: kernel/trace/trace_probe.c:1333
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
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
In kernel/trace/trace_probe.c (ffff800010257694)
Location: kernel/trace/trace_probe.c:732
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
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
In kernel/trace/trace_probe.c (c048a84c)
Location: kernel/trace/trace_probe.c:732
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
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
In kernel/trace/trace_probe.c (c0000000002f90fc)
Location: kernel/trace/trace_probe.c:732
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811cf9d3)
Location: kernel/trace/trace_probe.c:732
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
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
In kernel/trace/trace_probe.c (ffffffff811c27a3)
Location: kernel/trace/trace_probe.c:732
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
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
In kernel/trace/trace_probe.c (ffffffff811cd7a3)
Location: kernel/trace/trace_probe.c:732
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
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
In kernel/trace/trace_probe.c (ffffffff811dba03)
Location: kernel/trace/trace_probe.c:732
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
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
</ul>
