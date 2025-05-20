# Function: <code>event_trigger_parse_num</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
int event_trigger_parse_num(char *param, struct event_trigger_data *trigger_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff81244590)
Location: kernel/trace/trace_events_trigger.c:860
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_parse
  - kernel/trace/trace_events_trigger.c:event_trigger_parse
```
**Symbols:**

```
ffffffff81244590-ffffffff812445f0: event_trigger_parse_num (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int event_trigger_parse_num(char *param, struct event_trigger_data *trigger_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff81292280)
Location: kernel/trace/trace_events_trigger.c:861
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_parse
  - kernel/trace/trace_events_trigger.c:event_trigger_parse
```
**Symbols:**

```
ffffffff81292280-ffffffff812922e0: event_trigger_parse_num (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int event_trigger_parse_num(char *param, struct event_trigger_data *trigger_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff812af4e0)
Location: kernel/trace/trace_events_trigger.c:863
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_parse
  - kernel/trace/trace_events_trigger.c:event_trigger_parse
```
**Symbols:**

```
ffffffff812af4e0-ffffffff812af540: event_trigger_parse_num (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int event_trigger_parse_num(char *param, struct event_trigger_data *trigger_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff812cba20)
Location: kernel/trace/trace_events_trigger.c:863
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_parse
  - kernel/trace/trace_events_trigger.c:event_trigger_parse
```
**Symbols:**

```
ffffffff812cba20-ffffffff812cba80: event_trigger_parse_num (STB_GLOBAL)
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
