# Function: <code>trace_inject_entry</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_inject.c (ffffffff811dd9d0)
Location: kernel/trace/trace_events_inject.c:17
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:event_inject_write
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
In kernel/trace/trace_events_inject.c (ffffffff811daad0)
Location: kernel/trace/trace_events_inject.c:17
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:event_inject_write
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
In kernel/trace/trace_events_inject.c (ffffffff811dc040)
Location: kernel/trace/trace_events_inject.c:17
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:event_inject_write
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
In kernel/trace/trace_events_inject.c (ffffffff8120b770)
Location: kernel/trace/trace_events_inject.c:17
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:event_inject_write
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
In kernel/trace/trace_events_inject.c (ffffffff81247882)
Location: kernel/trace/trace_events_inject.c:17
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:event_inject_write
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int trace_inject_entry(struct trace_event_file *file, void *rec, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_inject.c (ffffffff81295980)
Location: kernel/trace/trace_events_inject.c:17
Inline: False
Direct callers:
  - kernel/trace/trace_events_inject.c:event_inject_write
```
**Symbols:**

```
ffffffff81295980-ffffffff81295a2b: trace_inject_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int trace_inject_entry(struct trace_event_file *file, void *rec, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_inject.c (ffffffff812b2890)
Location: kernel/trace/trace_events_inject.c:17
Inline: False
Direct callers:
  - kernel/trace/trace_events_inject.c:event_inject_write
```
**Symbols:**

```
ffffffff812b2890-ffffffff812b293b: trace_inject_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int trace_inject_entry(struct trace_event_file *file, void *rec, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_inject.c (ffffffff812cee40)
Location: kernel/trace/trace_events_inject.c:17
Inline: False
Direct callers:
  - kernel/trace/trace_events_inject.c:event_inject_write
```
**Symbols:**

```
ffffffff812cee40-ffffffff812ceeeb: trace_inject_entry (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
