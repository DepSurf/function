# Function: <code>__is_good_name</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff8129918a)
Location: kernel/trace/trace.h:1957
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
  - kernel/trace/trace_events_synth.c:parse_synth_field
```
```
In kernel/trace/trace_probe.c (ffffffff812b60c8)
Location: kernel/trace/trace.h:1957
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff812b644a)
Location: kernel/trace/trace.h:1990
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
  - kernel/trace/trace_events_synth.c:parse_synth_field
```
```
In kernel/trace/trace_probe.c (ffffffff812d9119)
Location: kernel/trace/trace.h:1990
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff812d2a9a)
Location: kernel/trace/trace.h:2011
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
  - kernel/trace/trace_events_synth.c:parse_synth_field
```
```
In kernel/trace/trace_probe.c (ffffffff812f7059)
Location: kernel/trace/trace.h:2011
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
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
