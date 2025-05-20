# Function: <code>trace_event_try_get_ref</code>

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
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff812026db)
Location: include/linux/trace_events.h:399
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_events.c:trace_get_event_file
```
```
In kernel/trace/trace_event_perf.c (ffffffff812040f9)
Location: include/linux/trace_events.h:399
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_init
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8120824e)
Location: include/linux/trace_events.h:399
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
```
```
In kernel/trace/trace_eprobe.c (ffffffff8120ab1f)
Location: include/linux/trace_events.h:399
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff8123dac0)
Location: include/linux/trace_events.h:406
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_events.c:trace_get_event_file
```
```
In kernel/trace/trace_event_perf.c (ffffffff8123f4e6)
Location: include/linux/trace_events.h:406
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_init
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8124481b)
Location: include/linux/trace_events.h:406
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_parse
```
```
In kernel/trace/trace_eprobe.c (ffffffff81246b59)
Location: include/linux/trace_events.h:406
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff8128b1f0)
Location: include/linux/trace_events.h:408
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_events.c:trace_get_event_file
```
```
In kernel/trace/trace_event_perf.c (ffffffff8128cfa6)
Location: include/linux/trace_events.h:408
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_init
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8129251b)
Location: include/linux/trace_events.h:408
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_parse
```
```
In kernel/trace/trace_eprobe.c (ffffffff81293ca4)
Location: include/linux/trace_events.h:408
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
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
In kernel/trace/trace_events.c (ffffffff812a8140)
Location: include/linux/trace_events.h:422
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_events.c:trace_get_event_file
```
```
In kernel/trace/trace_event_perf.c (ffffffff812a9f26)
Location: include/linux/trace_events.h:422
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_init
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812af77b)
Location: include/linux/trace_events.h:422
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_parse
```
```
In kernel/trace/trace_eprobe.c (ffffffff812b0d94)
Location: include/linux/trace_events.h:422
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
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
In kernel/trace/trace_events.c (ffffffff812c3e10)
Location: include/linux/trace_events.h:422
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_events.c:trace_get_event_file
```
```
In kernel/trace/trace_event_perf.c (ffffffff812c5c36)
Location: include/linux/trace_events.h:422
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_init
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812cbcea)
Location: include/linux/trace_events.h:422
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_parse
```
```
In kernel/trace/trace_eprobe.c (ffffffff812cd354)
Location: include/linux/trace_events.h:422
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
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
