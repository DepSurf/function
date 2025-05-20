# Function: <code>trace_alloc_entry</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *trace_alloc_entry(struct trace_event_call *call, int *size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_inject.c (ffffffff811dd5a0)
Location: kernel/trace/trace_events_inject.c:153
Inline: False
Direct callers:
  - kernel/trace/trace_events_inject.c:parse_entry
```
**Symbols:**

```
ffffffff811dd5a0-ffffffff811dd69e: trace_alloc_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *trace_alloc_entry(struct trace_event_call *call, int *size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_inject.c (ffffffff811da6a0)
Location: kernel/trace/trace_events_inject.c:153
Inline: False
Direct callers:
  - kernel/trace/trace_events_inject.c:parse_entry
```
**Symbols:**

```
ffffffff811da6a0-ffffffff811da79e: trace_alloc_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *trace_alloc_entry(struct trace_event_call *call, int *size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_inject.c (ffffffff811dbbf0)
Location: kernel/trace/trace_events_inject.c:153
Inline: False
Direct callers:
  - kernel/trace/trace_events_inject.c:parse_entry
```
**Symbols:**

```
ffffffff811dbbf0-ffffffff811dbce9: trace_alloc_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *trace_alloc_entry(struct trace_event_call *call, int *size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_inject.c (ffffffff8120b320)
Location: kernel/trace/trace_events_inject.c:153
Inline: False
Direct callers:
  - kernel/trace/trace_events_inject.c:parse_entry
```
**Symbols:**

```
ffffffff8120b320-ffffffff8120b419: trace_alloc_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *trace_alloc_entry(struct trace_event_call *call, int *size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_inject.c (ffffffff812473e0)
Location: kernel/trace/trace_events_inject.c:153
Inline: False
```
**Symbols:**

```
ffffffff812473e0-ffffffff812474fe: trace_alloc_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *trace_alloc_entry(struct trace_event_call *call, int *size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_inject.c (ffffffff81295a40)
Location: kernel/trace/trace_events_inject.c:153
Inline: False
```
**Symbols:**

```
ffffffff81295a40-ffffffff81295b5e: trace_alloc_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *trace_alloc_entry(struct trace_event_call *call, int *size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_inject.c (ffffffff812b2950)
Location: kernel/trace/trace_events_inject.c:153
Inline: False
```
**Symbols:**

```
ffffffff812b2950-ffffffff812b2a6e: trace_alloc_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *trace_alloc_entry(struct trace_event_call *call, int *size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_inject.c (ffffffff812cef00)
Location: kernel/trace/trace_events_inject.c:153
Inline: False
```
**Symbols:**

```
ffffffff812cef00-ffffffff812cf01e: trace_alloc_entry (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
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
