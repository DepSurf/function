# Function: <code>event_trigger_check_remove</code>

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
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool event_trigger_check_remove(const char *glob);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff81244630)
Location: kernel/trace/trace_events_trigger.c:717
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_parse
  - kernel/trace/trace_events_trigger.c:event_trigger_parse
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
```
**Symbols:**

```
ffffffff81244430-ffffffff81244444: event_trigger_check_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool event_trigger_check_remove(const char *glob);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff81292330)
Location: kernel/trace/trace_events_trigger.c:718
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_parse
  - kernel/trace/trace_events_trigger.c:event_trigger_parse
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
```
**Symbols:**

```
ffffffff812920e0-ffffffff812920f4: event_trigger_check_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool event_trigger_check_remove(const char *glob);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff812af590)
Location: kernel/trace/trace_events_trigger.c:720
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_parse
  - kernel/trace/trace_events_trigger.c:event_trigger_parse
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
```
**Symbols:**

```
ffffffff812af340-ffffffff812af354: event_trigger_check_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool event_trigger_check_remove(const char *glob);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff812cbad0)
Location: kernel/trace/trace_events_trigger.c:720
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_parse
  - kernel/trace/trace_events_trigger.c:event_trigger_parse
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
```
**Symbols:**

```
ffffffff812cb850-ffffffff812cb864: event_trigger_check_remove (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
