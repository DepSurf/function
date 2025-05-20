# Function: <code>parse_field</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811a0741)
Location: kernel/trace/trace_events_hist.c:2441
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_atom
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
In kernel/trace/trace_events_hist.c (ffffffff811adea1)
Location: kernel/trace/trace_events_hist.c:2559
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_atom
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
In kernel/trace/trace_events_hist.c (ffffffff811bbe0b)
Location: kernel/trace/trace_events_hist.c:2713
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_atom
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
In kernel/trace/trace_events_hist.c (ffffffff811c765b)
Location: kernel/trace/trace_events_hist.c:2824
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_atom
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
int parse_field(char *str, struct trace_event_call *call, struct ftrace_event_field **pf, u64 *pv);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_inject.c (ffffffff811dd2e0)
Location: kernel/trace/trace_events_inject.c:36
Inline: False
Direct callers:
  - kernel/trace/trace_events_inject.c:parse_entry
```
```
In kernel/trace/trace_events_hist.c (ffffffff811e1b40)
Location: kernel/trace/trace_events_hist.c:1919
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:parse_atom
```
**Symbols:**

```
ffffffff811dd2e0-ffffffff811dd59f: parse_field (STB_LOCAL)
ffffffff811e1b40-ffffffff811e1deb: parse_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
int parse_field(char *str, struct trace_event_call *call, struct ftrace_event_field **pf, u64 *pv);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_inject.c (ffffffff811da3f0)
Location: kernel/trace/trace_events_inject.c:36
Inline: False
Direct callers:
  - kernel/trace/trace_events_inject.c:parse_entry
```
```
In kernel/trace/trace_events_hist.c (ffffffff811df760)
Location: kernel/trace/trace_events_hist.c:1929
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:parse_atom
```
**Symbols:**

```
ffffffff811da3f0-ffffffff811da6a0: parse_field (STB_LOCAL)
ffffffff811df760-ffffffff811dfa0b: parse_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
int parse_field(char *str, struct trace_event_call *call, struct ftrace_event_field **pf, u64 *pv);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_inject.c (ffffffff811db950)
Location: kernel/trace/trace_events_inject.c:36
Inline: False
Direct callers:
  - kernel/trace/trace_events_inject.c:parse_entry
```
```
In kernel/trace/trace_events_hist.c (ffffffff811e09a0)
Location: kernel/trace/trace_events_hist.c:1955
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:parse_atom
```
**Symbols:**

```
ffffffff811db950-ffffffff811dbbe8: parse_field (STB_LOCAL)
ffffffff811e09a0-ffffffff811e0c20: parse_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
int parse_field(char *str, struct trace_event_call *call, struct ftrace_event_field **pf, u64 *pv);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_inject.c (ffffffff8120b080)
Location: kernel/trace/trace_events_inject.c:36
Inline: False
Direct callers:
  - kernel/trace/trace_events_inject.c:parse_entry
```
```
In kernel/trace/trace_events_hist.c (ffffffff8120f8e0)
Location: kernel/trace/trace_events_hist.c:1989
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:parse_atom
```
**Symbols:**

```
ffffffff8120b080-ffffffff8120b318: parse_field (STB_LOCAL)
ffffffff8120f8e0-ffffffff8120fbce: parse_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
int parse_field(char *str, struct trace_event_call *call, struct ftrace_event_field **pf, u64 *pv);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_inject.c (ffffffff81247140)
Location: kernel/trace/trace_events_inject.c:36
Inline: False
```
```
In kernel/trace/trace_events_hist.c (ffffffff81251090)
Location: kernel/trace/trace_events_hist.c:2247
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:parse_atom
```
**Symbols:**

```
ffffffff81247140-ffffffff812473d2: parse_field (STB_LOCAL)
ffffffff81251090-ffffffff812513ff: parse_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
int parse_field(char *str, struct trace_event_call *call, struct ftrace_event_field **pf, u64 *pv);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_inject.c (ffffffff812956d0)
Location: kernel/trace/trace_events_inject.c:36
Inline: False
```
```
In kernel/trace/trace_events_hist.c (ffffffff812a02f0)
Location: kernel/trace/trace_events_hist.c:2287
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:parse_atom
```
**Symbols:**

```
ffffffff812956d0-ffffffff81295962: parse_field (STB_LOCAL)
ffffffff812a02f0-ffffffff812a06da: parse_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
int parse_field(char *str, struct trace_event_call *call, struct ftrace_event_field **pf, u64 *pv);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_inject.c (ffffffff812b25e0)
Location: kernel/trace/trace_events_inject.c:36
Inline: False
```
```
In kernel/trace/trace_events_hist.c (ffffffff812be080)
Location: kernel/trace/trace_events_hist.c:2301
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:parse_atom
```
**Symbols:**

```
ffffffff812b25e0-ffffffff812b2872: parse_field (STB_LOCAL)
ffffffff812be080-ffffffff812be4c6: parse_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
int parse_field(char *str, struct trace_event_call *call, struct ftrace_event_field **pf, u64 *pv);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_inject.c (ffffffff812ceb90)
Location: kernel/trace/trace_events_inject.c:36
Inline: False
```
```
In kernel/trace/trace_events_hist.c (ffffffff812da6e0)
Location: kernel/trace/trace_events_hist.c:2294
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:parse_atom
```
**Symbols:**

```
ffffffff812ceb90-ffffffff812cee22: parse_field (STB_LOCAL)
ffffffff812da6e0-ffffffff812dab26: parse_field (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffff800010247934)
Location: kernel/trace/trace_events_hist.c:2824
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_atom
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (c0000000002e038c)
Location: kernel/trace/trace_events_hist.c:2824
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_atom
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
In kernel/trace/trace_events_hist.c (ffffffff811bfc7b)
Location: kernel/trace/trace_events_hist.c:2824
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_atom
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
In kernel/trace/trace_events_hist.c (ffffffff811b2a5b)
Location: kernel/trace/trace_events_hist.c:2824
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_atom
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
In kernel/trace/trace_events_hist.c (ffffffff811bda4b)
Location: kernel/trace/trace_events_hist.c:2824
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_atom
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
In kernel/trace/trace_events_hist.c (ffffffff811cbaeb)
Location: kernel/trace/trace_events_hist.c:2824
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_atom
```
</details>
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
