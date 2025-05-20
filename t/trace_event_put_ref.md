# Function: <code>trace_event_put_ref</code>

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
In kernel/trace/trace_events.c (ffffffff8120275f)
Location: include/linux/trace_events.h:407
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:trace_put_event_file
```
```
In kernel/trace/trace_event_perf.c (ffffffff8120411f)
Location: include/linux/trace_events.h:407
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_init
```
```
In kernel/trace/trace_events_trigger.c (ffffffff81208317)
Location: include/linux/trace_events.h:407
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_free
```
```
In kernel/trace/trace_eprobe.c (ffffffff8120afd8)
Location: include/linux/trace_events.h:407
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
In kernel/trace/trace_events.c (ffffffff8123db6b)
Location: include/linux/trace_events.h:414
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:trace_put_event_file
  - kernel/trace/trace_events.c:trace_put_event_file
```
```
In kernel/trace/trace_event_perf.c (ffffffff8123f8b3)
Location: include/linux/trace_events.h:414
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_uprobe_destroy
  - kernel/trace/trace_event_perf.c:perf_uprobe_destroy
  - kernel/trace/trace_event_perf.c:perf_kprobe_destroy
  - kernel/trace/trace_event_perf.c:perf_kprobe_destroy
  - kernel/trace/trace_event_perf.c:perf_trace_destroy
  - kernel/trace/trace_event_perf.c:perf_trace_destroy
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_event_perf.c:perf_trace_init
```
```
In kernel/trace/trace_events_trigger.c (ffffffff81244905)
Location: include/linux/trace_events.h:414
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_parse
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_parse
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_free
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_free
```
```
In kernel/trace/trace_eprobe.c (ffffffff812470cc)
Location: include/linux/trace_events.h:414
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
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
In kernel/trace/trace_events.c (ffffffff8128b29b)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:trace_put_event_file
  - kernel/trace/trace_events.c:trace_put_event_file
```
```
In kernel/trace/trace_event_perf.c (ffffffff8128d383)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_uprobe_destroy
  - kernel/trace/trace_event_perf.c:perf_uprobe_destroy
  - kernel/trace/trace_event_perf.c:perf_kprobe_destroy
  - kernel/trace/trace_event_perf.c:perf_kprobe_destroy
  - kernel/trace/trace_event_perf.c:perf_trace_destroy
  - kernel/trace/trace_event_perf.c:perf_trace_destroy
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_event_perf.c:perf_trace_init
```
```
In kernel/trace/trace_events_trigger.c (ffffffff81292605)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_parse
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_parse
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_free
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_free
```
```
In kernel/trace/trace_eprobe.c (ffffffff81294275)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
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
In kernel/trace/trace_events.c (ffffffff812a81eb)
Location: include/linux/trace_events.h:430
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:trace_put_event_file
  - kernel/trace/trace_events.c:trace_put_event_file
```
```
In kernel/trace/trace_event_perf.c (ffffffff812aa303)
Location: include/linux/trace_events.h:430
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_uprobe_destroy
  - kernel/trace/trace_event_perf.c:perf_uprobe_destroy
  - kernel/trace/trace_event_perf.c:perf_kprobe_destroy
  - kernel/trace/trace_event_perf.c:perf_kprobe_destroy
  - kernel/trace/trace_event_perf.c:perf_trace_destroy
  - kernel/trace/trace_event_perf.c:perf_trace_destroy
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_event_perf.c:perf_trace_init
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812af865)
Location: include/linux/trace_events.h:430
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_parse
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_parse
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_free
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_free
```
```
In kernel/trace/trace_eprobe.c (ffffffff812b1274)
Location: include/linux/trace_events.h:430
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
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
In kernel/trace/trace_events.c (ffffffff812c3ebc)
Location: include/linux/trace_events.h:430
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:trace_put_event_file
  - kernel/trace/trace_events.c:trace_put_event_file
```
```
In kernel/trace/trace_event_perf.c (ffffffff812c6013)
Location: include/linux/trace_events.h:430
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_uprobe_destroy
  - kernel/trace/trace_event_perf.c:perf_uprobe_destroy
  - kernel/trace/trace_event_perf.c:perf_kprobe_destroy
  - kernel/trace/trace_event_perf.c:perf_kprobe_destroy
  - kernel/trace/trace_event_perf.c:perf_trace_destroy
  - kernel/trace/trace_event_perf.c:perf_trace_destroy
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_event_perf.c:perf_trace_init
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812cbdd4)
Location: include/linux/trace_events.h:430
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_parse
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_parse
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_free
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_free
```
```
In kernel/trace/trace_eprobe.c (ffffffff812cd822)
Location: include/linux/trace_events.h:430
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
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
