# Function: <code>find_compatible_hist</code>

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
In kernel/trace/trace_events_hist.c (ffffffff811a2fe1)
Location: kernel/trace/trace_events_hist.c:2842
Inline: True
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
In kernel/trace/trace_events_hist.c (ffffffff811b1b4e)
Location: kernel/trace/trace_events_hist.c:2958
Inline: True
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
In kernel/trace/trace_events_hist.c (ffffffff811bfcc6)
Location: kernel/trace/trace_events_hist.c:3115
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_field_var_hist
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
In kernel/trace/trace_events_hist.c (ffffffff811cb516)
Location: kernel/trace/trace_events_hist.c:3230
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct hist_trigger_data *find_compatible_hist(struct hist_trigger_data *target_hist_data, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e1150)
Location: kernel/trace/trace_events_hist.c:2325
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
**Symbols:**

```
ffffffff811e1150-ffffffff811e1243: find_compatible_hist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct hist_trigger_data *find_compatible_hist(struct hist_trigger_data *target_hist_data, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811deb10)
Location: kernel/trace/trace_events_hist.c:2335
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
**Symbols:**

```
ffffffff811deb10-ffffffff811dec03: find_compatible_hist (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff811e6267)
Location: kernel/trace/trace_events_hist.c:2392
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_field_var_hist
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
In kernel/trace/trace_events_hist.c (ffffffff81217127)
Location: kernel/trace/trace_events_hist.c:2446
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_field_var_hist
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
In kernel/trace/trace_events_hist.c (ffffffff8125550a)
Location: kernel/trace/trace_events_hist.c:2823
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_field_var_hist
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
In kernel/trace/trace_events_hist.c (ffffffff812a49ca)
Location: kernel/trace/trace_events_hist.c:2874
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812c28a9)
Location: kernel/trace/trace_events_hist.c:2896
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812df159)
Location: kernel/trace/trace_events_hist.c:2889
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_field_var_hist
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
In kernel/trace/trace_events_hist.c (ffff80001024a96c)
Location: kernel/trace/trace_events_hist.c:3230
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_field_var_hist
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
In kernel/trace/trace_events_hist.c (c0000000002e5b0c)
Location: kernel/trace/trace_events_hist.c:3230
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_field_var_hist
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
In kernel/trace/trace_events_hist.c (ffffffff811c3b36)
Location: kernel/trace/trace_events_hist.c:3230
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_field_var_hist
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
In kernel/trace/trace_events_hist.c (ffffffff811b6916)
Location: kernel/trace/trace_events_hist.c:3230
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_field_var_hist
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
In kernel/trace/trace_events_hist.c (ffffffff811c1906)
Location: kernel/trace/trace_events_hist.c:3230
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_field_var_hist
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
In kernel/trace/trace_events_hist.c (ffffffff811cf9a6)
Location: kernel/trace/trace_events_hist.c:3230
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_field_var_hist
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
</ul>
