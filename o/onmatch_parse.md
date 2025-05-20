# Function: <code>onmatch_parse</code>

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
In kernel/trace/trace_events_hist.c (ffffffff811a1e94)
Location: kernel/trace/trace_events_hist.c:3739
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
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
In kernel/trace/trace_events_hist.c (ffffffff811afe8b)
Location: kernel/trace/trace_events_hist.c:3824
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
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
In kernel/trace/trace_events_hist.c (ffffffff811be074)
Location: kernel/trace/trace_events_hist.c:4320
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
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
In kernel/trace/trace_events_hist.c (ffffffff811c98f4)
Location: kernel/trace/trace_events_hist.c:4442
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct action_data *onmatch_parse(struct trace_array *tr, char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e4170)
Location: kernel/trace/trace_events_hist.c:3544
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:parse_actions
```
**Symbols:**

```
ffffffff811e4170-ffffffff811e4350: onmatch_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct action_data *onmatch_parse(struct trace_array *tr, char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e1ba0)
Location: kernel/trace/trace_events_hist.c:3563
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:parse_actions
```
**Symbols:**

```
ffffffff811e1ba0-ffffffff811e1d80: onmatch_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct action_data *onmatch_parse(struct trace_array *tr, char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e2970)
Location: kernel/trace/trace_events_hist.c:3631
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
```
**Symbols:**

```
ffffffff811e2970-ffffffff811e2b50: onmatch_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct action_data *onmatch_parse(struct trace_array *tr, char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff81212850)
Location: kernel/trace/trace_events_hist.c:3688
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
```
**Symbols:**

```
ffffffff81212850-ffffffff81212a30: onmatch_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct action_data *onmatch_parse(struct trace_array *tr, char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812535c0)
Location: kernel/trace/trace_events_hist.c:4065
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
```
**Symbols:**

```
ffffffff812535c0-ffffffff81253848: onmatch_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct action_data *onmatch_parse(struct trace_array *tr, char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812a2b80)
Location: kernel/trace/trace_events_hist.c:4121
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
```
**Symbols:**

```
ffffffff812a2b80-ffffffff812a2e08: onmatch_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct action_data *onmatch_parse(struct trace_array *tr, char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812c09e0)
Location: kernel/trace/trace_events_hist.c:4164
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
```
**Symbols:**

```
ffffffff812c09e0-ffffffff812c0c65: onmatch_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct action_data *onmatch_parse(struct trace_array *tr, char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812dcf40)
Location: kernel/trace/trace_events_hist.c:4157
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:parse_actions
```
**Symbols:**

```
ffffffff812dcf40-ffffffff812dd1f8: onmatch_parse (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffff800010249740)
Location: kernel/trace/trace_events_hist.c:4442
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
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
In kernel/trace/trace_events_hist.c (c0000000002e2c64)
Location: kernel/trace/trace_events_hist.c:4442
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
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
In kernel/trace/trace_events_hist.c (ffffffff811c1f14)
Location: kernel/trace/trace_events_hist.c:4442
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
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
In kernel/trace/trace_events_hist.c (ffffffff811b4cf4)
Location: kernel/trace/trace_events_hist.c:4442
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
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
In kernel/trace/trace_events_hist.c (ffffffff811bfce4)
Location: kernel/trace/trace_events_hist.c:4442
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
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
In kernel/trace/trace_events_hist.c (ffffffff811cdd84)
Location: kernel/trace/trace_events_hist.c:4442
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
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
