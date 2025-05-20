# Function: <code>trace_event_enum_update</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void trace_event_enum_update(struct trace_enum_map **map, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff81160b70)
Location: kernel/trace/trace_events.c:2294
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_module_notify
  - kernel/trace/trace.c:tracer_init_tracefs
```
**Symbols:**

```
ffffffff81160b70-ffffffff81160ef7: trace_event_enum_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void trace_event_enum_update(struct trace_enum_map **map, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff8116b270)
Location: kernel/trace/trace_events.c:2199
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:trace_module_notify
```
**Symbols:**

```
ffffffff8116b270-ffffffff8116b617: trace_event_enum_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void trace_event_enum_update(struct trace_enum_map **map, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff81176560)
Location: kernel/trace/trace_events.c:2168
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:trace_module_notify
```
**Symbols:**

```
ffffffff81176560-ffffffff8117690a: trace_event_enum_update (STB_GLOBAL)
```
</details>
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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
