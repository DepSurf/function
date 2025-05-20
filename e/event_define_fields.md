# Function: <code>event_define_fields</code>

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
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff811d4437)
Location: kernel/trace/trace_events.c:2129
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_trace_add_tracer
  - kernel/trace/trace_events.c:__trace_early_add_events
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_add_event_call
  - kernel/trace/trace_events.c:event_create_dir
Direct callers:
  - kernel/trace/trace_events.c:event_trace_add_tracer
  - kernel/trace/trace_events.c:__trace_early_add_events
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_add_event_call
  - kernel/trace/trace_events.c:event_create_dir
```
**Symbols:**

```
ffffffff811d2710-ffffffff811d286b: event_define_fields.part.0 (STB_LOCAL)
ffffffff81be6125-ffffffff81be6142: event_define_fields.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int event_define_fields(struct trace_event_call *call);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff811d43cf)
Location: kernel/trace/trace_events.c:2340
Inline: True
Direct callers:
  - kernel/trace/trace_events.c:event_trace_add_tracer
  - kernel/trace/trace_events.c:__trace_early_add_events
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_add_event_call
  - kernel/trace/trace_events.c:event_create_dir
```
**Symbols:**

```
ffffffff811d4390-ffffffff811d444f: event_define_fields (STB_LOCAL)
ffffffff81bd7de2-ffffffff81bd7df8: event_define_fields.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int event_define_fields(struct trace_event_call *call);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff8120122f)
Location: kernel/trace/trace_events.c:2342
Inline: True
Direct callers:
  - kernel/trace/trace_events.c:__trace_early_add_events
  - kernel/trace/trace_events.c:__trace_add_new_event
  - kernel/trace/trace_events.c:event_create_dir
```
**Symbols:**

```
ffffffff812011f0-ffffffff812012af: event_define_fields (STB_LOCAL)
ffffffff81cb641f-ffffffff81cb6435: event_define_fields.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int event_define_fields(struct trace_event_call *call);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff8123c2b0)
Location: kernel/trace/trace_events.c:2361
Inline: True
Direct callers:
  - kernel/trace/trace_events.c:__trace_early_add_events
  - kernel/trace/trace_events.c:__trace_add_new_event
  - kernel/trace/trace_events.c:event_create_dir
```
**Symbols:**

```
ffffffff8123c2b0-ffffffff8123c3a1: event_define_fields (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int event_define_fields(struct trace_event_call *call);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff81288b30)
Location: kernel/trace/trace_events.c:2381
Inline: True
Direct callers:
  - kernel/trace/trace_events.c:__trace_early_add_events
  - kernel/trace/trace_events.c:__trace_add_new_event
  - kernel/trace/trace_events.c:event_create_dir
```
**Symbols:**

```
ffffffff81288b30-ffffffff81288cce: event_define_fields (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int event_define_fields(struct trace_event_call *call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff812a5860)
Location: kernel/trace/trace_events.c:2375
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:__trace_early_add_events
  - kernel/trace/trace_events.c:__trace_add_new_event
  - kernel/trace/trace_events.c:event_create_dir
```
**Symbols:**

```
ffffffff812a5860-ffffffff812a59e7: event_define_fields (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int event_define_fields(struct trace_event_call *call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff812c1280)
Location: kernel/trace/trace_events.c:2438
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:__trace_early_add_events
  - kernel/trace/trace_events.c:__trace_add_new_event
  - kernel/trace/trace_events.c:event_create_dir
```
**Symbols:**

```
ffffffff812c1280-ffffffff812c1407: event_define_fields (STB_LOCAL)
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
