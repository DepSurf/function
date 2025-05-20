# Function: <code>trace_event_dyn_try_get_ref</code>

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
bool trace_event_dyn_try_get_ref(struct trace_event_call *dyn_call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff81222370)
Location: kernel/trace/trace_dynevent.c:22
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
```
**Symbols:**

```
ffffffff81222370-ffffffff812223e6: trace_event_dyn_try_get_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool trace_event_dyn_try_get_ref(struct trace_event_call *dyn_call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff81262100)
Location: kernel/trace/trace_dynevent.c:22
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_parse
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
```
**Symbols:**

```
ffffffff81262100-ffffffff81262182: trace_event_dyn_try_get_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool trace_event_dyn_try_get_ref(struct trace_event_call *dyn_call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff812b3890)
Location: kernel/trace/trace_dynevent.c:22
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_parse
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
```
**Symbols:**

```
ffffffff812b3890-ffffffff812b3912: trace_event_dyn_try_get_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool trace_event_dyn_try_get_ref(struct trace_event_call *dyn_call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff812d6160)
Location: kernel/trace/trace_dynevent.c:22
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_parse
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
```
**Symbols:**

```
ffffffff812d6160-ffffffff812d61e2: trace_event_dyn_try_get_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool trace_event_dyn_try_get_ref(struct trace_event_call *dyn_call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff812f3c70)
Location: kernel/trace/trace_dynevent.c:22
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_parse
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
```
**Symbols:**

```
ffffffff812f3c70-ffffffff812f3cf2: trace_event_dyn_try_get_ref (STB_GLOBAL)
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
