# Function: <code>__ftrace_function_set_filter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff81163698)
Location: kernel/trace/trace_events_filter.c:2174
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:ftrace_function_set_filter_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff8116ddf7)
Location: kernel/trace/trace_events_filter.c:2121
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:ftrace_function_set_filter_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811794e7)
Location: kernel/trace/trace_events_filter.c:2154
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:ftrace_function_set_filter_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff8117bf9d)
Location: kernel/trace/trace_events_filter.c:2158
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:ftrace_function_set_filter_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff8118982d)
Location: kernel/trace/trace_events_filter.c:2157
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:ftrace_function_set_filter_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff8119a4f9)
Location: kernel/trace/trace_events_filter.c:1921
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
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
In kernel/trace/trace_events_filter.c (ffffffff811a86e9)
Location: kernel/trace/trace_events_filter.c:1915
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
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
In kernel/trace/trace_events_filter.c (ffffffff811b65fb)
Location: kernel/trace/trace_events_filter.c:1939
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
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
In kernel/trace/trace_events_filter.c (ffffffff811c1c8b)
Location: kernel/trace/trace_events_filter.c:1941
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __ftrace_function_set_filter(int filter, char *buf, int len, struct function_filter_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811d9b00)
Location: kernel/trace/trace_events_filter.c:1941
Inline: False
```
**Symbols:**

```
ffffffff811d9b00-ffffffff811d9c28: __ftrace_function_set_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __ftrace_function_set_filter(int filter, char *buf, int len, struct function_filter_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811d6c00)
Location: kernel/trace/trace_events_filter.c:1920
Inline: False
```
**Symbols:**

```
ffffffff811d6c00-ffffffff811d6d28: __ftrace_function_set_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __ftrace_function_set_filter(int filter, char *buf, int len, struct function_filter_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811d7ff0)
Location: kernel/trace/trace_events_filter.c:1920
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
```
**Symbols:**

```
ffffffff811d7ff0-ffffffff811d8118: __ftrace_function_set_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __ftrace_function_set_filter(int filter, char *buf, int len, struct function_filter_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff81205070)
Location: kernel/trace/trace_events_filter.c:2013
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
```
**Symbols:**

```
ffffffff81205070-ffffffff81205198: __ftrace_function_set_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __ftrace_function_set_filter(int filter, char *buf, int len, struct function_filter_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff812406f0)
Location: kernel/trace/trace_events_filter.c:2041
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
```
**Symbols:**

```
ffffffff812406f0-ffffffff81240831: __ftrace_function_set_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff8128dac5)
Location: kernel/trace/trace_events_filter.c:2138
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __ftrace_function_set_filter(int filter, char *buf, int len, struct function_filter_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff812aa850)
Location: kernel/trace/trace_events_filter.c:2229
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
```
**Symbols:**

```
ffffffff812aa850-ffffffff812aa98f: __ftrace_function_set_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __ftrace_function_set_filter(int filter, char *buf, int len, struct function_filter_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff812c66d0)
Location: kernel/trace/trace_events_filter.c:2493
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
```
**Symbols:**

```
ffffffff812c66d0-ffffffff812c680f: __ftrace_function_set_filter (STB_LOCAL)
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
In kernel/trace/trace_events_filter.c (ffff800010241330)
Location: kernel/trace/trace_events_filter.c:1941
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (c047cdf0)
Location: kernel/trace/trace_events_filter.c:1941
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (c0000000002d2618)
Location: kernel/trace/trace_events_filter.c:1941
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffe00019634a)
Location: kernel/trace/trace_events_filter.c:1941
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
```
</details>
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
In kernel/trace/trace_events_filter.c (ffffffff811ba2ab)
Location: kernel/trace/trace_events_filter.c:1941
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
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
In kernel/trace/trace_events_filter.c (ffffffff811ad08b)
Location: kernel/trace/trace_events_filter.c:1941
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
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
In kernel/trace/trace_events_filter.c (ffffffff811b807b)
Location: kernel/trace/trace_events_filter.c:1941
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
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
In kernel/trace/trace_events_filter.c (ffffffff811c611b)
Location: kernel/trace/trace_events_filter.c:1941
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
