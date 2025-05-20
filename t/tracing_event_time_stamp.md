# Function: <code>tracing_event_time_stamp</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 tracing_event_time_stamp(struct trace_buffer *buffer, struct ring_buffer_event *rbe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c3670)
Location: kernel/trace/trace.c:7248
Inline: False
```
**Symbols:**

```
ffffffff811c3670-ffffffff811c368f: tracing_event_time_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 tracing_event_time_stamp(struct trace_buffer *buffer, struct ring_buffer_event *rbe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811ee820)
Location: kernel/trace/trace.c:7326
Inline: False
```
**Symbols:**

```
ffffffff811ee820-ffffffff811ee83f: tracing_event_time_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 tracing_event_time_stamp(struct trace_buffer *buffer, struct ring_buffer_event *rbe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81226b70)
Location: kernel/trace/trace.c:7331
Inline: False
```
**Symbols:**

```
ffffffff81226b70-ffffffff81226b9f: tracing_event_time_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 tracing_event_time_stamp(struct trace_buffer *buffer, struct ring_buffer_event *rbe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81271e00)
Location: kernel/trace/trace.c:7382
Inline: False
```
**Symbols:**

```
ffffffff81271e00-ffffffff81271e2f: tracing_event_time_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 tracing_event_time_stamp(struct trace_buffer *buffer, struct ring_buffer_event *rbe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81289110)
Location: kernel/trace/trace.c:7538
Inline: False
```
**Symbols:**

```
ffffffff81289110-ffffffff8128913f: tracing_event_time_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 tracing_event_time_stamp(struct trace_buffer *buffer, struct ring_buffer_event *rbe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff812a4460)
Location: kernel/trace/trace.c:7571
Inline: False
```
**Symbols:**

```
ffffffff812a4460-ffffffff812a448f: tracing_event_time_stamp (STB_GLOBAL)
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
